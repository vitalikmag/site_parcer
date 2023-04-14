# site_parcer
This Python script uses the Pexels API to search for images based on a user's query and download them to a local directory.

## Prerequisites
• Python 3.6 or higher
• requests library
• tqdm library
• Pexels API key
## Installation
• Clone the repository to your local machine.
• Install the required dependencies using pip install requests tqdm.
• Obtain a Pexels API key from the Pexels website.
• Set the API_KEY variable in the main.py script to your API key.
## Usage
• Run the main.py script using python main.py.
• Enter a keyword to search for images.
• The script will download up to 80 images (the maximum per page for the Pexels API) for the given keyword.
• If there are more than 80 images for the given keyword, the script will download all of them.
