# Changelog

### 2.7.3
- Merged [#96](https://github.com/brentvollebregt/auto-py-to-exe/pull/96): Fixed Python 2.7 compatibility

### 2.7.2
- Made warnings appear at the top of the ui when using versions of PyInstaller/Python that a known to conflict
- Added argument `--output-dir` to set the default output directory
- Added argument `--logging-level` to override logging level for console output
- Added helpful links to the top of the ui
- Removed Python 3.4 from supported versions as it is not officially supported by PyInstaller anymore
- Some other build and background improvements

### 2.7.1
- Fixed binary not reading arguments
- Fixed input being emptied when cancelling file dialogs

## 2.7.0
- Completely refactored project
    - Code separation
    - Cleaned up logging silencing
    - Advanced tab is built dynamically to support newly added PyInstaller commands
    - Added "Settings" ui tab for non-PyInstaller settings
    - Better input colouring for inputs expecting files/directories
- Started adding tests to help support multiple operating systems and versions of Python more confidently.
- Automatic deployments on tag

*Note: This introduces a different format for exported configuration json files which causes older configuration files to be incompatible.*

### 2.6.6
- Added support for Eel 0.11.0

### 2.6.5
- Fix #61: Don't try to use Chrome if Eel detects a path that does not exist

### 2.6.4
- Leave a space between extra command data and the Python file

### 2.6.3
- Allow PyInstaller dev branches to be used

### 2.6.2
- Fix #58: Do not supply keyword arguments to os.startfile.

### 2.6.1
- When the server stops, close the UI
- Fix #56: Stop Python process freezing when displaying tkinter dialogs
- Don't pass filetypes to tkinter's askopenfilename on MacOS

## 2.6.0
- Allow importing and exporting od argument configurations as json files
- Other improvements to behind-the-scenes state

## Earlier
- No changelog notes for earlier versions.
