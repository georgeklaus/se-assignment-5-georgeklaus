[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15252328&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate. 

**ANSWERS AT THE END OF THE PAGE**

Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 


**ANSWERS TO PROJECT**


**Installation of VS Code on Linux Mint**

Steps to Download and Install Visual Studio Code:
1. I opened the Terminal:

You can open the terminal by pressing Ctrl + Alt + T or by searching for "Terminal" in the application menu.
2. I updated the Package List (sudo apt-get update)

3. I installed prerequisites: Ensure you have the necessary tools to add a new repository and install packages over HTTPS:
   (sudo apt install software-properties-common apt-transport-https wget)
4. I added the Microsoft GPG Key: Download and add the Microsoft GPG key
   (wget -qO- https://packages.microsoft.com/keys/microsoft.asc | sudo apt-key add -)
5. I also added the VS Code Repository to the system
   (sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main")
6. I updated the Package List Again 
   (sudo apt-get update)
7. I installed VS Code using: 
   (sudo apt install code)
8. I then launched VS Code by typing 'code' in the terminal.


**First-time Setup**

Initial Configurations and Settings:

Theme and Appearance:

I opened VS Code.
   Go to File > Preferences > Color Theme and select a preferred theme (e.g., Dark+, Light+).
Font and Editor Settings:

   Go to File > Preferences > Settings or press Ctrl + ,.
Adjusted settings such as editor.fontSize and editor.lineHeight for optimal readability.
Extensions:

   I opened the Extensions view by clicking the Extensions icon on the Activity Bar.
Installed essential extensions such as:
   1. Python (for Python development)
   2. ESLint (for JavaScript linting)
   3. Prettier - Code formatter (for code formatting)
   4. Live Server (for live reloading in web development)


**User Interface Overview**

Main Components of the VS Code User Interface:
1. Activity Bar:

   Located on the far left of the window.
   Contains icons for quick access to different views such as Explorer, Search, Source Control, Run and Debug, and Extensions.
2. Side Bar:

   Located next to the Activity Bar.
   Displays different views depending on the Activity Bar selection (e.g., file explorer, search results).
3. Editor Group:

   Central area where you write and view your code.
   Supports multiple tabs and split views for working on several files simultaneously.
4. Status Bar:

   Located at the bottom of the window.
   Displays important information about the workspace and the current file, such as encoding, line endings, and language mode.


**Command Palette**

What is the Command Palette?
   -This is a powerful feature that allows you to access all VS Code commands.
   -Accessing the Command Palette: Press Ctrl + Shift + P (or F1).
Common Tasks Using the Command Palette:
1. Change Theme: Type Preferences: Color Theme and select a new theme.
2. Install Extensions: Type Extensions: Install Extensions and search for desired extensions.
3. Open Settings: Type Preferences: Open Settings.


**Extensions in VS Code**
Role of Extensions:
   Extensions: Enhance VS Code by adding new functionalities, language support, themes, and more.

Finding, Installing, and Managing Extensions:
1. Opened Extensions View:

   Clicked on the Extensions icon in the Activity Bar by pressing Ctrl + Shift + X.

2. Search for Extensions:

   Used the search bar to find specific extensions (e.g., "Python", "Prettier").

3. Install Extensions:

   Clicked the "Install" button next to the desired extension.
   Extensions can be enabled, disabled, or uninstalled from the Extensions view.

*Examples of Essential Extensions for Web Development:*

1. Live Server: Launch a local development server with live reload feature for static and dynamic pages.
2. Prettier - Code formatter: Automatically format your code according to pre-defined rules.
3. ESLint: Lint JavaScript and TypeScript code to enforce consistent coding styles.
3. Debugger for Chrome: Debug JavaScript code running in the Chrome browser.
4. HTML CSS Support: Provides IntelliSense for HTML and CSS.


*Integrated Terminal*

How to Open and Use the Integrated Terminal:
1. Open Terminal:

   Go to View > Terminal or press Ctrl + (backtick).
2. Use the Terminal:

   You can run shell commands directly within VS Code.
   The terminal supports multiple instances, allowing you to switch between them using the dropdown menu in the terminal panel.

*Advantages of Using the Integrated Terminal:*

1. Convenience: Runs commands without leaving the code editor.
2. Environment: Shares the same environment and working directory as the editor.
3. Efficiency: Quickly switches between coding and terminal tasks.

*File and Folder Management*

Creating, Opening, and Managing Files and Folders:

1. Create a New File:

   Go to File > New File or press Ctrl + N.
2. Create a New Folder:

   Right-click in the Explorer view (Side Bar) and select New Folder.
3. Open a File or Folder:

   Go to File > Open File or File > Open Folder or press Ctrl + O.
4. Navigate Between Files:

   Use the Explorer view to browse and open files.
   Use Ctrl + P to quickly open files by typing their names.
   Use Ctrl + Tab to switch between open files.

*Settings and Preferences*

Finding and Customizing Settings:

1. I opened Settings:

   Go to File > Preferences > Settings or press Ctrl + ,.
2. Change Theme:

   In the settings, searched for "theme" and selected preferred color theme.
3. Adjust Font Size:

   In the settings, searched for editor.fontSize and set it to my preferred size.
4. Modify Keybindings:

   Go to File > Preferences > Keyboard Shortcuts or press Ctrl + K, Ctrl + S.
   Customize keybindings to suit my workflow.

*Debugging in VS Code*

Setting Up and Starting Debugging:

1. I opened a File to Debug:

Open the code file you want to debug.
2. Added Breakpoints:

Click in the gutter to the left of the line numbers to add breakpoints.
3. Configure Debugging:

Go to Run > Add Configuration and select the appropriate environment (e.g., Python, Node.js).
4. Start Debugging:

Press F5 or go to Run > Start Debugging.

*Key Debugging Features:*

1. Breakpoints: Pauses execution at specific lines.
2. Watch Variables: Monitors the values of variables.
3. Call Stack: Views the call stack to understand the sequence of function calls.
4. Step Over/Into/Out: Controls the execution flow line by line.

**Using Source Control**

Integrating Git with VS Code:

1. Install Git:

   I downloaded and installed Git from https://git-scm.com/download/linux.
2. Initialize a Repository:

   Open your project folder in VS Code.
   Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing Ctrl + Shift + G.
   Click Initialize Repository.
3. Make Commits:

   Stage changes by clicking the + icon next to the file.
   Enter a commit message and click the checkmark icon to commit the changes.
4. Push Changes to GitHub:

   Link your local repository to a remote repository on GitHub.
   Use the terminal to run:  (git remote add origin https://github.com/yourusername/your-repo.git
git push -u origin master)
   
   Alternatively, you can use the built-in Git integration to push changes by clicking the "..." icon in the Source Control view and selecting Push.

**Refferences**

https://code.visualstudio.com/docs/setup/linux

https://code.visualstudio.com/docs/editor/extension-marketplace#:~:text=You%20can%20browse%20and%20install,Ctrl%2BShift%2BX).


