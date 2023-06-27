# OCR Image Processing Script for HRC2

This script performs Optical Character Recognition (OCR) on PNG images, processes them, and outputs information in a sorted list.

## Prerequisites

You need to have installed:

-   **Python 3.7** or newer. If Python is not installed, download it from the [official website](https://www.python.org/downloads/).
-   **pip** (Python package installer), usually comes with Python installation.
-   **git** for cloning the repository from GitHub.

## Installation

Follow the steps below to install and run the script:

### Step 1: Clone the Repository

Clone the repository to your local machine using git.

bashCopy code

`git clone https://github.com/username/repository.git` 

_Replace `username` and `repository` with the appropriate GitHub username and repository name._

### Step 2: Install Required Python Libraries

Navigate to the cloned repository and install the required Python libraries by running the following command:

bashCopy code

`pip install -r requirements.txt` 

### Step 3: Install Tesseract OCR

This script also requires **Tesseract OCR** to function. Download and install it from the [official GitHub repository](https://github.com/tesseract-ocr/tesseract/wiki). Ensure that it's added to your system's PATH.

On Windows, you can also define the tesseract path in your script like so:

pythonCopy code

`pytesseract.pytesseract.tesseract_cmd = 'C:\\Program Files\\Tesseract-OCR\\tesseract.exe'` 

## Running the Script

To run the script, navigate to the repository directory and run:

bashCopy code

`python HRC2Reader.py` 

This will process all PNG images in the same directory as the script, and print the resulting data to the console. You can modify the script to process images from different locations or to output the data in a different way.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
