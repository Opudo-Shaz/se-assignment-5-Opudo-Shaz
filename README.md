[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15248432&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   i) Check that the computer has requirements for visual studio code i.e RAM 4gb+,
   ii)Open browser and browse the visual studio code official website called htts://code.visualstudio.com and download vs code installer.
   iii) Navigate to downloads where the installler is downloaded by default an double click on it and start visual studio code installation.
   iv)By default it will be installed under program files folder. You can now access it by double clicking on the icon or by serching start menu.
   You can choose to add it to environment path variable so that you can easily access it through command line.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   Initial configurations to make to a new vs code include :- Extensions for programming languages desiredi.e python,javascript,php,dart, extentions for debugging and for code formatting.
   You can also integrate vs code to terminal and version control serach as git for hosting and collaboration.
   You can also set your preffered appearance and theme for vs code as well as customize its appearance.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
   Activity bar; is located on the far left side of the window and provides different views and functionalities of vs code.
   Side bar;it is located next to the activity bar and contains various views like Explorer,search bar, souce control and extensions.
   Editor group; it consist of many editor panes where you can split editor and work on multiple files at the same time. It allows multi tasking and code comparision.
   Status bar; the status bar is located at the bottom of the window and provide quick access to icons for: changing encoding,indentation settings and language mode.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
      Command pallete is a tool that allow users to access various functionalities and command in vs code through the search interface.
      It can be accessed by shortccut keys like crt+shift+p in both windows and linux or by clicking the view menu and selecting command pallete.
      Examples of tasks that can be performed using commmand pallete include:-opening files, running tasks, switching between editor tabs, chnging themes and installing extensions.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
   Extensions are used in vs code to extend its functionality to support different programming languages and frameworks. It enhances the editor's capabilities and enable users to customize their development environment.
   Users can find extensions by clicking on the extension view present in the activity bar and serching the desired extension using key words i.e seraching python brings list of extensions related to python and choose.
   Extensions once found in the search bar of the extension view can be installed just by single click on the button install.
   Users can their installed extensions by disabling, uninstalling and updating them from the extension view.
   Examples of extensions used for software development include;-live server, prettier code, HTL CSS support,debugger for chrome.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
      To open integrated terminal in vs code one can use keyboad shortcut (ctrl+'') or by clicking terminal in the activity view.
      Once the integrated terminal is open, you can use it just like a regular terminal. You can run commands, execute scripts, install dependencies using package managers, and perform any other terminal-related tasks.
      Integrated terminal is advantegeous to external terminal in that it leads to seamless integration where developers have a single environment for coding and execution of commands.
7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
   To create a new file, you can right-click in the Explorer view of the Side Bar and choose "New File" or use the keyboard shortcut Ctrl+N (Windows/Linux).
   To create a new folder, right-click in the Explorer view and select "New Folder" or use the    shortcut Shift+Alt+N (Windows/Linux).
   You can move files and folders within the Explorer view by dragging and dropping them to the desired location. To copy, hold Ctrl (Windows/Linux) while dragging.
   To rename a file or folder, you can right-click on it in the Explorer view and choose "Rename" or press F2. To delete, right-click and select "Delete" or use the Delete key.
   Users can efficiently navigate files and directories using the following methods:-
   Utilizing the Explorer view in the Side Bar to navigate between files and folders. You can collapse and expand directories to manage directory structures effectively.
   Using the Ctrl+P (Windows/Linux) keyboard shortcut to quickly search for and open files by typing part of the file name.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
      Users can find and customize settings using the "Settings" menu, which allows them to modify a wide range of editor and extension-related configurations.
      Users can fing settings in vs code through the settings ui or by use of command pallete.
      To change the theme, open the Settings UI and search for "Color Theme". You can then select a different color theme from the dropdown list. For example, selecting "Dark+ (default dark)" or "Light+ (default light)" will change the overall theme of the editor.
      To adjust the font size, search for "Editor: Font Size" in the Settings UI. You can then modify the font size by entering your preferred value in the input field.
      Search for "Open Keyboard Shortcuts" in the Command Palette to access the Keyboard Shortcuts editor. From here, you can customize keybindings and modify existing keybinding mappings to suit your preferences.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
      Install the Necessary Extensions
      Create or Open a Project
      Create a Launch Configuration
      Set Breakpoints
      Start the Debugger
      Iterate and Inspect
As the program starts running, it will pause at your breakpoints, allowing you to inspect variables, call stack, and other relevant information using the debugging features available in VS Code.
Some of the common debugging features available in vs code include:-Conditional breakpoints,watch expressions,call stack navigation and variabble inspection features.
10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
      Install Git:Ensure that Git is installed on your system. If it's not already installed, you can download it from the official Git website and follow the installation instructions.
      Open a Project:Open the project folder in VS Code that you want to initialize as a Git repository.
      Initialize a Git Repository:to initialize the project as a Git repository, click the Source Control icon in the Activity Bar (usually on the left-hand side) or use the keyboard shortcut Ctrl+Shift+G (Windows/Linux) or Cmd+Shift+G (Mac). Then click the "Initialize Repository" button. This creates a hidden folder named .git at the root of your project.
      Stage and Commit Changes:after making changes to your code, you can stage the changes by clicking the "+" next to the file(s) you want to include in the commit in the Source Control view. Then, enter a commit message in the text input area at the top of the Source Control view and press Ctrl+Enter (Windows/Linux) to commit the changes.
      Push Changes to GitHub:If you haven't already set up a remote repository on GitHub, you can do so by creating a new repository on GitHub and following the instructions provided to add a remote URL to your local repository. Once the remote repository is set up, you can push changes by clicking the ellipsis (...) in the Source Control view and selecting "Push".
      Pull Changes from GitHub:Similarly, you can also pull changes from the GitHub remote by clicking the ellipsis (...) in the Source Control view and selecting "Pull" to synchronize your local repository with the remote changes.
 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

