[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15302195&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

   the prerequisites that might be needed is
   1
   - windows 11(64-bit)
   -1.6 GHz or faster processor
   -1 GB of RAM
   -Glibcxx version 3.4.25 or later

   steps to download
step 1: go to your web browser and search for visual studio code download for windows 11 
step 2:download the visual studio code installer by selecting the window installer (VSCodUserSetup-{version}.exe) 
step 3. locate the installer on your file explorer and run the installer and follow the prompts to install visual studio code
step 4. we choose the location for installation based on your preference
step 5. choose the setup type which can be the user or system but we will choose the user setup which is the recommended one as it provide a smoother background update experience
step 6. install vs code and the installer will download and install vs code
step7. launch vs code which will be from the start menu or by searching for it in search bar.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.After installing VS Code, here are some initial configurations and settings to adjust for an optimal coding environment:

1. *Theme and Color Scheme*: Change the theme and color scheme to your preference. Popular themes include Dark+, Light+, and Material Icon Theme.
2. *Font and Font Size*: Adjust the font and font size to your comfort. Popular fonts include Fira Code, Consolas, and Monaco.
3. *Indentation and Formatting*: Set indentation to 4 spaces and configure formatting settings to your preference.
4. *Code Completion and IntelliSense*: Enable code completion and IntelliSense for your programming language.
5. *Terminal and Command Palette*: Configure the terminal and command palette to your preference.
6. *Explorer and File Navigation*: Customize the explorer and file navigation settings to your liking.
7. *Debugging and Testing*: Set up debugging and testing configurations for your project.

Important settings:

1. *Settings Sync*: Enable settings sync to synchronize your settings across devices.
2. *Auto Save*: Enable auto-save to save your files automatically.
3. *Format on Save*: Enable format on save to format your code automatically on save.

Important extensions:

1. *ESLint*: For code linting and formatting.
2. *Prettier*: For code formatting.
3. *Debugger for Chrome*: For debugging JavaScript applications.
4. *Python Extension Pack*: For Python development.
5. *Java Extension Pack*: For Java development.
6. *C++ Extension Pack*: For C++ development.
7. *GitLens*: For Git version control.
8. *Visual Studio Code Icons*: For custom icons.


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   the main components of the VS code user interface are:

   1.editor its the main area where you write and edit code, 
   2. side bar which is the left hand column that contains various views such as the explorer, search, source control and debug, 
   3. another component is the status bar which is the bottom bar that deplays information about the current file, such as file type and encoding, line and column numbers and lastly error and warning counts.
   4. activity bar which is the top left icon bar that provides quick access to various features
   5. command palette which is a dropdown menu that allows you to run commands and access features using keyboard shortcuts or by typing commands
   6. panels which is the area below the editor that deplays various information such as output, problems,and terminal
   7. icons its various icons throughout the interface that provide additional functionality such as fold code,format code and debugging.

   the purpose of the following:

   1. Activity bar it provide quick access to various features and views such as explorer, search, source control abd debug and allows you to switch between different views and features without using the menu or keyboard shortcuts.
   2. side bar displays various views and information related to your project such as the explo rer in file and folder stracture, the search in charge of search results, source control in charge of version control information and the debug that has the debug console and variable views that allows you to navigate and manage your projects files, searh for specific code and access version control and debugging tools.
   3. Editor it is the main area where you write and edit code, displays the current file or files being edited and allows you to split the editor into multiple sections to view and edit different files simultaneously.
   4. status bar which deplays information about the current file or project such as file type and encoding, line and column numbers, error and warning counts, version control status  it also provide quick access to certain features such as formatting code or running tests.


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   command palette is a dropdown menu that allows you to run commands and access features using keyboard shortcuts or by typing commands. it can be accessed by:
    
    1.pressing ctrl+shift +p in windows to open the command palette
    2. type a command or search for a specific feature using the search bar
    3. select the desired command from the dropdown list to execute it.

    examples of common tasks that can be performed:
    1. Editing
    - formating document via shift+alt+f
    _format selection via ctrl+k ctrl +f

    2. debugging
    _start debugging f5
    -stop debugging shift +f5

    3. navigation
    -go to defination f12
    -go to declaration ctrl+shift+f12
    - go to symbol in file ctrl+shift+o

    4. extensions
    -open settings ctrl+shift+p then you type settings
    - open keyboard shortcuts ctrl+shift+p then type keyboard shortcuts

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

   extensions play a crucial role in vs code because they enhance its functionality and making it a more comprehensive development environment.its roles include adding new features and functionality to vs code, providing language support, debugging tools and code completion . they can also integrate with other tools and services such as version control systems and project management tools.

   users can find them in the vs code extensions marketplace which can be accessed through the extensions icon in the left sidebar or by pressing ctrl+shift+x in windows then the users can search for extensions by name, category or tag.

   users can install extensions directly from the extensions marketplace by clicking the install button and they will download and install, they can also install them from the command line using the code --install-extension command

   users can manage them through the extension panel, where they can be enabled and disabled and also their settings can be configured and they can aslo be uninstalled from the extension panel. 

   essential extensions for web development.
    HTML snippets for quick codig
    CSS Intellisense whih offers css code completion and debugging tools
    JavaScript(ES6) code snippets
    Debugger for chrome
    ESLint
    Prettier
    Live Server
    Auto Close
    Path Intellisense

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   to open the integrated terminal in vs code we:
   1. press ctrl+shift in windows
   2. alternatively use the command palette and type terminal: ctrate new terminal
   3. the integrated terminal will open at the bottom of the vs code window.
 
 Advantages of using the integrated terminal:

1. *Convenience*: The integrated terminal is easily accessible within VS Code, eliminating the need to switch between applications.
2. *Context awareness*: The terminal is aware of the current file or folder you are working on, making it easier to run commands related to your project.
3. *Seamless integration*: The terminal integrates well with VS Code features like debugging, testing, and version control.
4. *Multi-terminal support*: You can open multiple terminals in different splits, making it easy to work on multiple tasks simultaneously.
5. *Customization*: The integrated terminal supports customization of appearance, behavior, and shell settings.
6. *Improved workflow*: The integrated terminal enables a more efficient workflow by reducing the need to switch between applications.
7. *Better debugging*: The integrated terminal allows for easier debugging, as you can run commands and see output directly in the terminal.
8. *Version control*: The integrated terminal makes it easy to use version control systems like Git, as you can run commands like `git status` and `git commit` directly in the terminal.
 
 Compared to an external terminal the intergrated terminal offers a more streamlined and efficient experience, allowing you to stay focused on your code and avoid context switching.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

In VS Code, you can create, open, and manage files and folders using the following methods:

step 1:Create a new file

1. Open the Command Palette (Ctrl + Shift + P) and type "New File" or "Create File"
2. Click on "New File" or "Create File" to create a new file in the current directory
3. Alternatively, right-click in the Explorer panel and select "New File"

step 2:Open a file

1. Navigate to the file in the Explorer panel
2. Click on the file to open it in the editor
3. Alternatively, use the Command Palette to search for the file by name

step 3:Create a new folder

1. Open the Command Palette (Ctrl + Shift + P) and type "New Folder" or "Create Folder"
2. Click on "New Folder" or "Create Folder" to create a new folder in the current directory
3. Alternatively, right-click in the Explorer panel and select "New Folder"

step 4:Create a new folder

1. Open the Command Palette (Ctrl + Shift + P) and type "New Folder" or "Create Folder"
2. Click on "New Folder" or "Create Folder" to create a new folder in the current directory
3. Alternatively, right-click in the Explorer panel and select "New Folder"

step 5:Open a folder

1. Navigate to the folder in the Explorer panel
2. Click on the folder to open it and view its contents

To navigate between different files and directories efficiently, you can use the following methods:

_Explorer panel:_

1. Use the Explorer panel to browse and navigate through your files and folders
2. Click on a file or folder to open it

_Breadcrumb navigation:_

1. Use the breadcrumb navigation at the top of the editor to navigate through the file hierarchy
2. Click on a folder or file in the breadcrumb trail to navigate to it

_Command Palette:_

1. Use the Command Palette to search for files by name
2. Type "Open File" or "Open Folder" and select the file or folder from the search results

_Keyboard shortcuts:_

1. Use keyboard shortcuts to navigate through files and folders
2. Examples:
    - Ctrl + P (Windows/Linux) or Cmd + P (Mac) to open the Command Palette
    - Ctrl + Shift + E (Windows/Linux) or Cmd + Shift + E (Mac) to open the Explorer panel
    - Ctrl + Tab (Windows/Linux) or Cmd + Tab (Mac) to switch between open files


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

  users can find and customize settings in vs code in the following ways:

   1. *Settings Editor*:
    - Open the Command Palette (Ctrl + Shift + P) and type "Settings" or "Preferences"
    - Click on "Settings" or "Preferences" to open the Settings Editor
    - Search for specific settings or browse through the categories
2. *Settings File*:
    - Open the Command Palette (Ctrl + Shift + P) and type "Open Settings (JSON)"
    - This will open the settings.json file in the editor
    - Edit the file to add or modify settings

Examples of customizing settings:

1. *Change the Theme*:
    - Open the Settings Editor
    - Search for "theme"
    - Select a theme from the dropdown list (e.g., "Dark+", "Light+", "Material Icon Theme")
    - Alternatively, add a theme extension and select it from the list
2. *Change Font Size*:
    - Open the Settings Editor
    - Search for "font size"
    - Enter a new font size value (e.g., 14, 16, 18)
    - Alternatively, use the keyboard shortcut Ctrl + Plus sign (+) or Ctrl + Minus sign (-) to increment or decrement the font size
3. *Change Keybindings*:
    - Open the Settings Editor
    - Search for "keybindings"
    - Click on the "Keyboard Shortcuts" link
    - Search for a specific command or keybinding
    - Click on the "Edit" button to modify the keybinding
    - Enter a new key combination or select a predefined keybinding

Examples of keybindings:

- *Format Document*: Ctrl + Shift + F (Windows/Linux) or Cmd + Shift + F (Mac)
- *Toggle Sidebar*: Ctrl + B (Windows/Linux) or Cmd + B (Mac)
- *Debug Start*: F5 (Windows/Linux) or F5 (Mac)


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Step 1: Create a new project*

- Create a new folder for your project
- Open the folder in VS Code
- Create a new file for your program (e.g., `(link unavailable)` for Python)

*Step 2: Install the debugger extension*

- Open the Extensions panel (Ctrl + Shift + X)
- Search for the debugger extension for your language (e.g., "Python" for Python)
- Install the extension

*Step 3: Configure the debugger*

- Open the Debugger panel (Ctrl + Shift + D)
- Select the debugger extension you installed
- Configure the debugger settings as needed (e.g., port number, runtime executable)

*Step 4: Set breakpoints*

- Open your program file (e.g., `(link unavailable)`)
- Click in the margin next to the line where you want to set a breakpoint
- A red dot will appear, indicating the breakpoint

*Step 5: Start debugging*

- Press F5 or click the "Start Debugging" button
- The debugger will start and pause at the first breakpoint

*Key debugging features in VS Code:*

1. *Breakpoints*: Set breakpoints to pause the debugger at specific lines of code.
2. *Step Over*: Step over a line of code to execute it and move to the next line.
3. *Step Into*: Step into a function or method to debug its contents.
4. *Step Out*: Step out of a function or method to return to the calling code.
5. *Variables*: View and edit variable values in the Debugger panel.
6. *Call Stack*: View the call stack to see the sequence of function calls.
7. *Console*: Use the console to evaluate expressions and print values.
8. *Debug Console*: Use the debug console to interact with the debugger.
9. *Conditional Breakpoints*: Set breakpoints that only trigger when a condition is met.
10. *Logpoints*: Set logpoints to print messages to the console without pausing the debugger.



10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

 to discribe this process we will use an assignment example.

 firstly you log into lms and click the assignment link then you accept it
 step 2. open the assingment in github and vie it as a README then you copy the link 
 step 3. open git bash and cd to the location of your choice
 step 4. then git clone the link you copied from github
 step 5. then cd to the link desplayed after git cloning
 step 6. now that your are inside the file type in code . to open vs code
 step 7. after writing your assignment then oen a terminal then choose a new terminal, it will then pop out at the bottom of your vs code
 step 8. click the plus sign on the right to navigate to git bash command line
 step 9. type in the command git add .
 step 10. then git commit -m "the messange you are pussing" and enter
 step 11. after commiting we then git push 
 step 12. go back to github and refresh the page to see new changes and then copy the code again and go back to lms to submit it.

 
 Submision Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

