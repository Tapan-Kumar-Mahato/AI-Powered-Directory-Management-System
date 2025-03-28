# AI-Powered Directory Management System

An intuitive Python-based application that organizes files in a selected folder using AI-powered logic and user-defined filters. This system categorizes files into different types, filters them based on size and date, and provides a clean, automated directory structure.

---

## Features
- **File Categorization:** Automatically moves files into predefined categories (Images, Videos, Documents, etc.).
- **User Filters:** Organize based on file size (e.g., larger than 1MB) and last modified date.
- **GUI Interface:** Easy-to-use Tkinter interface with progress tracking, checkboxes, and themes.
- **Themes:** Switch between light and dark modes for better usability.
- **Keyboard Shortcuts:** Access key functions quickly using shortcuts.

---

## Installation

1. **Clone the Repository:**
   ```bash
   git clone <repository_url>
   cd AI-Directory-Manager
   ```

2. **Install Dependencies:**
   - Ensure you have Python installed (version 3.x).
   - Install `tkinter` (built-in in most Python installations).

   ```bash
   pip install -r requirements.txt  # (If applicable)
   ```

---

## Usage

1. **Run the Application:**
   ```bash
   python main.py
   ```

2. **Select Folder:** Click the "Select Folder and Organize Files" button.
3. **Apply Filters:** Use checkboxes to filter files by size and date.
4. **Track Progress:** View the file processing status through a progress bar.
5. **Switch Themes:** Click "Toggle Theme" to switch between light and dark modes.

---

## Project Structure
```
AI-Directory-Manager/
│
├── main.py              # Main GUI logic
├── file_organizer.py    # File categorization and organization functions
├── README.md            # Project documentation
└── .gitignore           # Ignore unnecessary files
```

---

## Contributing
Feel free to fork the project and submit pull requests. Suggestions and improvements are always welcome!

---

## License
This project is licensed under the MIT License.

