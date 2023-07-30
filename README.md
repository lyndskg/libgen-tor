# libgen-tor

libgen-tor is a Library Genesis Downloader aimed at providing users with a convenient way to download .pdf or .epub files for various publications, books, and other resources from Library Genesis (LibGen). As LibGen restricts downloads only from Tor mirrors rather than clear net aliases, this project will utilize the Tor network to access and retrieve the desired files.

## Coding Languages:
To accomplish this task effectively, the project can be developed using Python. Python is well-suited for web scraping tasks, interacting with the Tor network, and handling file I/O operations. Additionally, it offers a wide range of libraries that simplify the process, such as Requests for HTTP requests and BeautifulSoup for parsing HTML.


## Basic Workflow:

1. Install Dependencies: Make sure you have Python and necessary libraries installed. You may need to install packages like Requests, BeautifulSoup, and Stem (Python library for Tor) to interact with the Tor network.
2. Set Up Tor Connection: To access the Tor network, you'll need to configure a Tor proxy. The Stem library provides the functionality to connect to the Tor network programmatically. It will allow your Python code to route requests through the Tor network.
3. Search and Retrieve Publications: Design a search function that takes user input (e.g., book title, author, ISBN) and sends a search query to Library Genesis. Scrape the search results to extract relevant information such as the book's unique identifier (ID) and its Tor mirror URL.
4. Download Files: Utilize the Tor proxy to access the Tor mirror URL and initiate the download of the requested .pdf or .epub file. Save the downloaded file to a specified location on the user's machine.
5. Error Handling and User Interaction: Implement error handling mechanisms to deal with issues such as invalid inputs, unavailable files, or Tor network connectivity problems. Provide a user-friendly interface to guide users through the process and display download progress.


## Basic I/O Details:
1. Input: User-provided search queries (book title, author, ISBN, etc.).
2. Output: Downloaded .pdf or .epub files saved to a specified folder on the user's machine.


Status updates and progress information displayed to the user.

