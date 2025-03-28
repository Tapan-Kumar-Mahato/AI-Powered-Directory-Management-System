#AI-Powered Directory Management System 🗂️
An intuitive Python-based application that organizes files in a selected folder using AI-powered logic and user-defined filters. This system categorizes files into different types, filters them based on size and date, and provides a clean, automated directory structure.

Features 🔧
File Categorization: Automatically moves files into predefined categories (e.g., Images, Videos, Documents).

User Filters: Organize files based on:

File Size (e.g., larger than 1MB).

Last Modified Date (e.g., modified within the last 30 days).

GUI Interface: Easy-to-use Tkinter interface with progress tracking, checkboxes, and themes.

Themes: Toggle between light and dark modes for better usability.

Keyboard Shortcuts: Access key functions quickly using shortcuts.

Modular Code Structure: Separate modules for file categorization and filtering to enhance readability and maintainability.

Installation 🏗️
1. Clone the Repository:
bash
Copy
Edit
git clone <repository_url>
cd AI-Directory-Manager
2. Install Dependencies:
Ensure you have Python 3.x installed.

Tkinter is required (already built-in with most Python installations).

Optional: Install dependencies (if any are listed in requirements.txt):

bash
Copy
Edit
pip install -r requirements.txt
Usage 🚀
To Run the Application:
bash
Copy
Edit
python main.py
Steps:
Select Folder: Click the "Select Folder and Organize Files" button to choose the directory you want to organize.

Apply Filters:

Size Filter: Filter files larger than a specified size (default: 1 MB).

Date Filter: Filter files based on the last modified date (default: files modified within the last 30 days).

Track Progress: The progress bar shows real-time file processing updates.

Switch Themes: Use the "Toggle Theme" button to switch between light and dark modes.

Keyboard Shortcuts: Use the following shortcuts:

Ctrl + O: Open folder dialog.

Ctrl + R: Reset all filters and progress.

Ctrl + Q: Quit the application.

Project Structure 📁
php
Copy
Edit
AI-Directory-Manager/
│
├── main.py                 # Main GUI logic
├── file_organizer.py        # File categorization and organization functions
├── file_filters.py          # File filtering logic (size and date filters)
├── README.md                # Project documentation
└── .gitignore               # Ignore unnecessary files
How File Filtering Works 🛠️
File Size Filter: Files larger than 1 MB (or your selected limit) are included during the filtering process.

Date Filter: Files modified within the last 30 days (or your selected limit) are included.

Toggle Filters: Users can enable or disable these filters via checkboxes in the GUI.

Contributing 🤝
Contributions are welcome! If you'd like to improve the project, feel free to:

Fork the repository.

Create a branch for your feature or bug fix.

Submit a pull request.

Suggestions and feedback are always appreciated!

License 📜
This project is licensed under the MIT License.
See the LICENSE file for more information.

Acknowledgments 🌟
Thanks to the open-source community and Python developers who made this project possible!
