# Dynamic-Technocrat-File-Organizer

**Project Description**
------------------------

The Dynamic Technocrat File Organizer is a graphical user interface (GUI) application designed to simplify file management. It allows users to load a directory, automatically categorize files into predefined types (e.g., Images, Documents, Audio, Videos, Archives, Scripts, Executables, and Others), and generate a visual report of the file distribution.

**Table of Contents**
-----------------

1. [Setup](#setup)
2. [Usage](#usage)
3. [Features](#features)
4. [Troubleshooting](#troubleshooting)
5. [Contributing](#contributing)
6. [License](#license)

### Setup
--------

#### Prerequisites

- Python 3.x (Tested on Python 3.9 and above)
- Required Libraries: `tkinter`, `matplotlib`, `shutil`, `os` (most are Python standard library, except for `matplotlib` which can be installed via pip)

#### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/YourGitHubUsername/DynamicTechnocratFileOrganizer.git
   ```
2. **Install `matplotlib` (if not already installed)**:
   ```bash
   pip install matplotlib
   ```
3. **Run the Application**:
   ```bash
   python main.py  # Assuming your main application file is named main.py
   ```

### Usage
-----

1. **Launch the Application**: Run `main.py` to start the GUI application.
2. **Load a Folder**:
   - Click on "📂 Load Folder".
   - Select a directory you wish to organize.
3. **View File Counts**:
   - Automatically displayed after loading a folder.
4. **Categorize Files**:
   - Click on "🔄 Categorize Files" to organize files into their respective categories.
5. **Generate Report**:
   - Click on "📊 Generate Report" to view a graphical distribution of file types.

### Features
----------

- **Automatic File Categorization**: Based on predefined file extensions.
- **Graphical Report**: Visual representation of file type distribution.
- **User-Friendly Interface**: Simplified GUI for ease of use.

### Troubleshooting
-----------------

- **No Folder Selected Error**:
  - Ensure you have selected a valid directory before attempting to categorize files.
- **Permission Errors During File Movement**:
  - Run the application with elevated privileges if you're trying to access restricted directories.
- **Missing Dependencies**:
  - Verify that `matplotlib` is installed. If not, install it using `pip`.

### Contributing
------------

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### License
-------

Distributed under the [MIT License](https://opensource.org/licenses/MIT). See `LICENSE` for more information.

**Contact**
------------

- **Developer**: Obaude Ayodeji Michael obaudeayodejimichael@gmail.com 
- **Project Link**: https://github.com/OBAUDE95/Dynamic-Technocrat-File-Organizer/


**To-Do (for you):**

1. **Replace `YourGitHubUsername`** with your actual GitHub username in the repository link.
2. **Update your email address** in the contact section.
3. **Review and refine** the documentation as needed to best represent your project.
4. **Create a `LICENSE` file** in your repository with the MIT License terms, if you haven't already.
