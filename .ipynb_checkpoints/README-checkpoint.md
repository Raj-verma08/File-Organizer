# File-Organizer
**File Organizer**
A Python script that helps you organize files in a specified directory by grouping them based on their file extensions. The script will move files to corresponding folders (e.g., .jpg files go to a Images folder, .pdf files to a Documents folder) to keep your directory tidy.

**Features**
Sorts and organizes files based on file extensions.
Automatically creates folders for each file type if they do not already exist.
Moves files to their corresponding folders.
Works with any directory on your system.

**Technologies Used**
Python
OS Module

**Installation**
Clone the repository:
    git clone https://github.com/Anshu639/File-Organizer.git
Navigate to the project folder:
    cd File-Organizer
Ensure you have Python installed. You can check by running:
    python --version

**Usage**
Run the script in the terminal, passing the directory you want to organize as an argument:
    python file_organizer.py /path/to/directory
Note: Replace /path/to/directory with the full path of the directory you want to organize.

The script will create folders based on file extensions (e.g., Images, Documents, Music) and move the corresponding files into these folders.

**Example:**
Suppose you have the following files in a directory:
/Downloads
├── vacation.jpg
├── song.mp3
├── report.pdf
├── script.py
Running the script will organize the files as follows:

Copy code
/Downloads
├── Images
│   └── vacation.jpg
├── Music
│   └── song.mp3
├── Documents
│   └── report.pdf
├── Scripts
│   └── script.py