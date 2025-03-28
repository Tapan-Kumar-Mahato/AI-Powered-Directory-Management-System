AI-Powered Directory Management System
An intuitive Python-based application that organizes files in a selected folder using AI-powered logic and user-defined filters. This system categorizes files into different types, filters them based on size and date, and provides a clean, automated directory structure.

Features
File Categorization: Automatically moves files into predefined categories (Images, Videos, Documents, etc.).

User Filters: Organize files based on size (e.g., larger than 1MB) and last modified date (e.g., modified within the last 30 days).

GUI Interface: Easy-to-use Tkinter interface with progress tracking, checkboxes, and themes.

Themes: Switch between light and dark modes for better usability.

Keyboard Shortcuts: Access key functions quickly using shortcuts.

Modular Code Structure: File categorization and filtering logic are separated for better readability and maintainability.

Installation
Clone the Repository:

bash
Copy
Edit
git clone <repository_url>
cd AI-Directory-Manager
Install Dependencies:

Ensure you have Python installed (version 3.x).

Install tkinter (built-in in most Python installations).

bash
Copy
Edit
pip install -r requirements.txt  # (If applicable)
Usage
Run the Application:

bash
Copy
Edit
python main.py
Select Folder: Click the "Select Folder and Organize Files" button.

Apply Filters:

Size Filter: Optionally filter files larger than a specified size (default: 1 MB).

Date Filter: Optionally filter files based on the last modified date (default: files modified in the last 30 days).

Track Progress: View the file processing status through a progress bar.

Switch Themes: Click "Toggle Theme" to switch between light and dark modes.

Project Structure
php
Copy
Edit
AI-Directory-Manager/
│
├── main.py                 # Main GUI logic
├── file_organizer.py       # File categorization and organization functions
├── file_filters.py         # File filtering logic (size and date filters)
├── README.md               # Project documentation
└── .gitignore              # Ignore unnecessary files
How File Filtering Works:
File Size Filter: Files larger than 1 MB (or your selected limit) are included during the filtering process.

Date Filter: Files modified within the last 30 days (or your selected limit) are included.

Toggle Filters: Users can enable or disable these filters via checkboxes in the GUI.

Contributing
Feel free to fork the project and submit pull requests. Suggestions and improvements are always welcome!

License
This project is licensed under the MIT License.

