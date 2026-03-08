Install and Use VS Code with WSL (Ubuntu)

1. Install VS Code on Windows
    Download from: https://code.visualstudio.com
    Install normally on Windows.

2. Install WSL Extension in VS Code
    Open VS Code.
    Go to Extensions (left sidebar).
    Search for: WSL
    Install: "Remote - WSL" by Microsoft.

3. Open a WSL Window
    Press: Ctrl + Shift + P
    Type: WSL
    Select: "New WSL Window"
    A new VS Code window opens connected to Ubuntu.

4. Open a Folder from WSL Ubuntu
    Press: Ctrl + K, then Ctrl + O
    Go to:
        /home/<your-username>/
    Select any folder (example: Readme)
    Click OK.

5. Check WSL Connection
    Look at bottom-left corner of VS Code:
        It should show "> < WSL: Ubuntu"
    This means VS Code is connected to Ubuntu WSL.

6. Open Terminal in VS Code
    Press: Ctrl + `
    You should see:
        hrcs@HRCS:~/yourfolder$
    This is the Ubuntu terminal inside VS Code.

7. Create a Test File
    In VS Code Explorer → New File
    Example: test.py

    Add sample code:
        print("Hello from VS Code in WSL!")

    Run in terminal:
        python3 test.py

8. Install Language Extensions (optional)
    Open Extensions panel and install:
        Python
        C/C++ (Microsoft)
        Java Extension Pack
    These will install directly into WSL Ubuntu.

9. Useful Commands
    Open VS Code from WSL terminal:
        code .
    Open VS Code from any folder:
        code <foldername>

10. Close WSL VS Code Window
    Just close the VS Code window.
    This does not affect your WSL Ubuntu installation.
