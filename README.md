# File Organizer - Automation Script

This Python script automatically organizes files in a selected directory into categorized folders based on file types (Documents, Images, Videos, Others). It provides a simple graphical interface using Tkinter.

## Features
- Organizes files into folders: Documents, Images, Videos, Others
- Simple and intuitive GUI (Tkinter)
- One-click folder selection and organization

## Requirements
- Python 3.x
- Standard libraries only (os, shutil, tkinter)

## Usage
1. Run the script:
   ```bash
   python main.py
   ```
2. Click the "Select Folder" button in the window.
3. Choose the directory you want to organize.
4. The script will sort files into subfolders by type.

## Folder Structure
- Documents: .pdf, .doc, .docx, .txt, .xls, .xlsx, .ppt, .pptx, .odt, .rtf
- Images: .jpg, .jpeg, .png, .gif, .bmp, .tiff, .svg, .webp
- Videos: .mp4, .avi, .mov, .wmv, .flv, .mkv, .webm
- Others: All other file types

## Notes
- Only files in the selected directory (not subfolders) are organized.
- Existing folders with the same names will be used or created if missing. # infotact
