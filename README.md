# Automated File Organizer

This Python-based application automatically organizes downloaded files into folders based on their file extensions. It helps keep your download folder organized by sorting files (e.g., PDFs, images, videos, documents) into corresponding directories.

## Features

- Automatically detects and organizes downloaded files based on their extensions.
- Creates folders for each file type (e.g., PDFs, Images, Videos, Documents).
- Reduces manual file sorting and helps keep the file system clean and organized.
- Error handling and notifications for successful sorting.

## Technologies Used

- **Python**: Core programming language for the application.
- **OS module**: Used for file system management and automation.
- **File System Management**: Organizing files into appropriate directories based on file extensions.

## Setup and Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/YourUsername/Automated-File-Organizer.git

2. **Navigate to the project folder**:

    ```bash
    cd Automated-File-Organizer

3. **Install dependencies (if needed)**:

    If you have any dependencies, they can be listed in the requirements.txt file. You can install them using:

    ```bash
    pip install -r requirements.txt

4. **Run the script**:

    Execute the script to start organizing your files:
   
    ```bash
    python file_organizer.py

## How It Works
- The script continuously monitors the "Downloads" folder for any new files.
- Once a new file is detected, it checks the file extension (e.g., .pdf, .jpg, .mp4) and moves the file to the appropriate folder based on predefined categories.
- If a folder for a specific file type doesn't exist, the script creates it automatically.
- The program uses the os module to handle file and directory operations.

## Example of Organized Folders:
- Downloads/PDFs/
- Downloads/Images/
- Downloads/Videos/
- Downloads/Documents/

## How to Customize
- **Add new file types**: You can easily add more file extensions to be recognized and sorted by modifying the script.
- **Change the monitored folder**: If you'd like to monitor a folder other than the "Downloads" folder, simply update the folder path in the script.

## Contributing
- If you'd like to contribute to this project, feel free to fork the repository and create a pull request with your changes. Any suggestions for improvements are welcome!
