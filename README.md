# 📁 Python File Organizer

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)

A powerful, lightweight automation script to declutter any directory. This tool intelligently categorizes files into structured folders based on their extensions using Python's native file system libraries.

---

## 📂 Project Structure

```text
python-file-organizer/
├── main.py          # The core automation engine
├── .gitignore       # Prevents tracking of local files/folders
└── README.md        # Project documentation and guide
```

## 📂 Key Features

1. Smart Categorization: Automatically groups files into folders like Images, Documents, Videos, and Archives.
2. Dynamic Folder Creation: New folders are created only when a matching file is detected.
3. Safety First: Skips existing folders to prevent infinite loops or accidental data loss.
4. Fallback Logic: Moves unrecognized file types to an Others folder to ensure a 100% clean root directory.

## 🛠️ Installation & Usage
1. Clone the repository
```bash

git clone [https://github.com/taniiishaa/python-file-organizer.git](https://github.com/taniiishaa/python-file-organizer.git)
cd python-file-organizer
```

## 2.Run the automation
```bash
python main.py
```

## 3. Provide the path

When prompted, paste the full path to the messy folder (e.g., D:\Media).

    [!TIP] Windows Users: Do not wrap the path in quotes when pasting into the terminal. Use D:\Media instead of "D:\Media".

## 🤝 Contributing

This is an open-source project! Whether you want to add more file extensions to the map or improve the error handling, feel free to fork this repo and submit a Pull Request.
