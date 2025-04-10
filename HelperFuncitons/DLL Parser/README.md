# Search DLLs for a String

This repository contains a Python script that searches for a specified string in all DLL files within a given directory. Only those DLL files that contain at least one occurrence of the search string are displayed. For each file with a match, the script prints the file path, the offset(s) where the string was found, and a snippet of context (10 bytes before and after the occurrence).

## Features

- **Cross-Platform Compatibility:** Works on both Windows and Linux.
- **Selective Display:** Only shows DLL files that contain the specified search string.
- **Binary Inspection:** Searches for the string in the binary content of the DLL files.
- **Context Snippets:** Provides a context snippet (10 bytes before and after) for each match to help identify the location within the file.

## Requirements

- Python 3.x

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/ShehmeerAbidRajput/Andriod-Security.git
   cd HelperFunctions

## How to Run the Script

Follow these steps to run the `search_dlls.py` script:

1. **Open a Terminal or Command Prompt:**

   - **Windows:**  
     Open Command Prompt by searching for "cmd" in the Start Menu.
     
   - **Linux/macOS:**  
     Open your Terminal application.

2. **Navigate to the HelperFunctions Directory:**

   Change to the directory where the script is located. For example:

   ```bash
   cd path/to/Andriod-Security/HelperFunctions

3. **Run the script**

   - **Windows:**
    ```bash  
     python search_dlls.py
     
   - **Linux/macOS:**  
    ```bash
     python3 search_dlls.py