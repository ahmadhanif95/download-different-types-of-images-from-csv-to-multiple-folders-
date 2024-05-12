# Download Different Types of Images from CSV to Multiple Folders

This script automates the process of downloading images from URLs listed in a CSV file and organizing them into separate folders based on their classes. Each image will be downloaded and stored in a folder named after its respective class.

## Requirements
- Python 3.x
- Pandas library
- Requests library

## Installation
1. Clone this repository to your local machine.
2. Install the required libraries using pip:
    ```bash
    pip install pandas requests
    ```

## Usage
1. Place your CSV file containing image URLs and their corresponding classes in the same directory as the script.
2. Run the script using the following Anaconda Jupyter Notebook:



## CSV Format
The CSV file should have two columns:
1. **Image URL**: The URLs of the images you want to download.
2. **Class**: The class or category of each image.

Example CSV format:
```
Image URL,Class
https://example.com/image1.jpg,cat
https://example.com/image2.jpg,dog
https://example.com/image3.jpg,cat
https://example.com/image4.jpg,dog
```

## Output
After running the script, the images will be downloaded and organized into folders based on their classes. Each folder will contain the images belonging to that class.

Example output directory structure:
```
.
├── download_images.py
├── your_csv_file.csv
├── cat
│   ├── image1.jpg
│   └── image3.jpg
└── dog
    ├── image2.jpg
    └── image4.jpg
```

## Notes
- Make sure the URLs in the CSV file are valid and accessible.
- Ensure that the classes provided in the CSV file are appropriate folder names.
- This script does not handle duplicate image URLs. If there are duplicate URLs, only one copy of the image will be downloaded.

Feel free to contribute to this project by submitting pull requests or reporting issues. If you have any questions or need assistance, please open an issue in the repository.
