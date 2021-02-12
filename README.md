# PythonBookStoreDatabase

# A simple desktop application using tkinter and sqlite3

## Installation

From the root directory of this file in your  terminal, enter the following to install the necessary pyinstaller dependencies
    
On windows:

    'pip install pyinstaller'

On Mac:

    'pip3 install pyinstaller'

Create the local app with the following:

    'pyinstaller frontend.py'

If you don't want to have the terminal, or extra diagnostic files installed use the following:

    'pyinstaller --onefile --windowed frontend.py'


Click on the resulting app or exe file and you're done!

If you'd like to seed some test data, please put the books.db file into the same folder as your executable file