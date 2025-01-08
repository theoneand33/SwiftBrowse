# SwiftBrowse
Fast, Private, Lightweight browser based on PyQt5

Still in VERY EARLY ALPHA! Use at your own risk.

## I will be continuing this project very soon! Stay tuned! ##

### Steps to Run SwiftBrowse on Windows, macOS, and Linux

#### Prerequisites
- Ensure Python 3.x is installed.
- Ensure `pip` (Python package installer) is installed.

#### General Setup
1. **Clone the Repository**
   ```sh
   git clone https://github.com/theoneand33/SwiftBrowse.git
   cd SwiftBrowse
   ```
   or
  
   Click code then click download zip then extract the zip file then run 
   ```
   cd SwiftBrowse
   ```
2. **Install Required Packages**
   ```sh
   pip install -r requirements.txt
   ```

#### Windows
1. **Set Environment Variable**
   ```sh
   set QTWEBENGINE_CHROMIUM_FLAGS=--enable-features=NetworkServiceInProcess
   ```

2. **Run the Application**
   ```sh
   python3 SwiftBrowseB1Alpha.py
   ```

#### macOS
1. **Set Environment Variable**
   ```sh
   export QTWEBENGINE_CHROMIUM_FLAGS=--enable-features=NetworkServiceInProcess
   ```

2. **Run the Application**
   ```sh
   python3 SwiftBrowseB1Alpha.py
   ```

#### Linux
1. **Set Environment Variable**
   ```sh
   export QTWEBENGINE_CHROMIUM_FLAGS=--enable-features=NetworkServiceInProcess
   ```

2. **Run the Application**
   ```sh
   python3 SwiftBrowseB1Alpha.py
   ```

#### Notes
- Use a terminal or command prompt to execute the commands.
- If you encounter permission issues, use `sudo` on Linux/macOS or run the command prompt as an administrator on Windows.
