# Automatic File Organizer using Python

## Overview

The **Automatic File Organizer** is a Python automation project that organizes files into categorized folders based on their file extensions. It helps users maintain a clean and well-structured directory by automatically sorting files such as images, documents, videos, audio files, archives, source code, and other file types.

This project is designed to run in **Google Colab**, where users upload a ZIP file containing mixed files. The program extracts the ZIP archive, organizes the files into appropriate folders, and generates a new organized ZIP file for download.

---

## Features

* Automatically organizes files by extension
* Creates folders automatically if they do not exist
* Supports multiple file categories
* Handles duplicate filenames without overwriting existing files
* Generates a log file for tracking file movements
* Displays a summary of organized files
* Compatible with Google Colab
* Compresses the organized files into a downloadable ZIP archive

---

## Technologies Used

* Python 3
* Google Colab

### Python Libraries

* `os`
* `shutil`
* `zipfile`
* `logging`
* `google.colab.files`

---

## Supported File Categories

| Category  | Supported Extensions                              |
| --------- | ------------------------------------------------- |
| Images    | .jpg, .jpeg, .png, .gif, .bmp, .webp              |
| Documents | .pdf, .doc, .docx, .txt, .ppt, .pptx, .xls, .xlsx |
| Videos    | .mp4, .avi, .mov, .mkv, .wmv                      |
| Audio     | .mp3, .wav, .aac, .flac                           |
| Archives  | .zip, .rar, .7z, .tar, .gz                        |
| Programs  | .py, .java, .cpp, .c, .html, .css, .js            |
| Others    | Any unsupported file extension                    |

---

## Project Workflow

1. Upload a ZIP file containing files.
2. Extract the ZIP archive.
3. Scan all files in the extracted folder.
4. Identify the extension of each file.
5. Create folders for different file categories.
6. Move files into their respective folders.
7. Rename duplicate files automatically if required.
8. Record all operations in a log file.
9. Display the organization summary.
10. Compress the organized folder into a ZIP file.
11. Download the organized ZIP archive.

---

## Project Structure

```text
File_Organizer/
│
├── organizer.py
├── organizer.log
├── requirements.txt
├── README.md
└── sample_files.zip
```

---

## Output

After execution, the project creates an organized folder with files sorted into categories such as:

```text
Uploaded_Files/
│
├── Images/
├── Documents/
├── Videos/
├── Audio/
├── Archives/
├── Programs/
└── Others/
```

An organized ZIP archive is also generated for download.

---

## Advantages

* Saves time by automating file organization.
* Keeps directories clean and structured.
* Reduces manual effort.
* Prevents accidental overwriting of duplicate files.
* Easy to understand and modify.
* Suitable for beginners learning Python automation.

---

## Future Enhancements

* Organize files inside nested folders.
* Add a graphical user interface (GUI).
* Support drag-and-drop functionality.
* Integrate cloud storage services.
* Allow users to define custom file categories.
* Schedule automatic file organization.

---

## Conclusion

The **Automatic File Organizer** is a simple yet practical Python automation project that demonstrates file handling, directory management, logging, and ZIP file processing. It provides an efficient solution for organizing files automatically and serves as an excellent beginner-friendly project for learning Python automation.

---

## Author

**M. Ayshwarya**
Aeronautical Engineering Graduate
Python Development Internship Project
