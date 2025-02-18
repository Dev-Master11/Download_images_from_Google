**Download Images from Website**

This is a simple Flask web application that lets users input a URL, scrape images from the webpage using Selenium and BeautifulSoup, and download them in a ZIP file.

### Features:
- Scrapes all images from a specified webpage.
- Downloads images to a local folder.
- Provides a ZIP file containing all images for easy download.
- Runs in headless mode using Selenium for smoother execution.

### Prerequisites:
Make sure you have the following installed before running the application:

- Python 3.x
- Google Chrome
- ChromeDriver (automatically managed by `webdriver_manager`)

### Installation:
1. Clone the repository:
   ```bash
   git clone https://github.com/Dev-Master11/Download_images_from_Google.git
   cd Download_images_from_Google
   ```

2. Create a virtual environment (optional, but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Windows use `venv\Scripts\activate`
   ```

### Usage:
1. Run the Flask application:
   ```bash
   python app.py
   ```

2. Open a web browser and go to:
   ```
   http://127.0.0.1:5000/
   ```

3. Enter a URL, click submit, and download the scraped images as a ZIP file.

### Dependencies:
- Flask
- Selenium
- WebDriver Manager
- Requests
- BeautifulSoup
- Zipfile
