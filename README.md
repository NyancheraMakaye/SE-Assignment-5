# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
Prerequisisties include ;the operating system(windows 11), disk space, a reliable internet connection, administrator access.
steps to download
a. open the preffered web browser and go to the official visual studio code website https://code.visualstudio.com/
b. click on the download for windows button. this will download the vs code installer.
c. once the download is complete, locate the file, usually in the downloads folder, double click to run it.
d. the intaller will prompt you with a dialog asking if you want to allow changes to your device. click "yes" to proceed.
e. the set up wizard will appear. click "next" to continue.
f. by default, the vs code installs to c:\program files\microsoft vs code. click next
g. you can optionally select additional tasks such as creating a desktop icon or adding vs code to the PATH. choose as desired then click "next"
h. click "install" to begin the installation process.
i. once the installation is complete, click "finish"to exit the setup wizard.
j. after installation, launch the vs code by double clicking the desktop icon or searching for "visual studio code"in the start menu.
k. regularly check for updates by clicking on the gear icon in the bottom left corner of VS code, then navigating to extensions, updates and clicking "update all extensions" 



2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   font and theme- change under settings>text editor>font
   change the theme and color theme for better readability
   set your preferred indentation and tad size under settings>text editor>formatting
   adjust autosave settings under settings>files:autosave
   useful extensions; programming languages(python,javascript), version control(git extension), code formatting(prettier), debugging tools(debugger for chrome, python)


3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
main components
explorer- allows navigation through files and folders i n the project directory
search- tools for searching across files
source control- integrates with version control systems for managing code changes
run and debug- supports running and debugging applications
extensions- manages VS code extensions for adding functionalities and features
split view- allows splitting the editor into multiple panes for side by side editing of different files

 -Activity Bar: Located on the left side, provides access to different views like Explorer, Search, Source Control, Run, and Extensions.
 - Side Bar: Displays different views and their contents, like the file explorer.
 - Editor Group: Where you edit your files. Multiple files can be opened in tabs.
 - Status Bar: Located at the bottom, shows information about the current file and project.



4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

the command palette in vs code allows users to access and execute various commands and actions within the editor, it allows you to run commands
Accessed via `Ctrl+Shift+P` (Windows/Linux) or `Cmd+Shift+P` (macOS)
common tasks include; opening files and folders, managing files and editors, editing and formatting, Git integration, extension management, debugging, terminal and tasks, setting and preferences, search and replace.


5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
extensions play a crucial role in enhancing its functionality and customizing the editor to suit different programming languages, workflows, and preferences.
users can explore the extensions view(icon with four squares)to find and install extensions that enhance their coding experience.
essential extensions- python, java, Git, prettier


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

You can open it with Ctrl + on windows(Cmd + on Mac).
Use the terminal to run commands, compile code, or execute scripts without leaving the editor
the integrated terminal enables copy, paste, search, and session clearing. it also allows you to easily pick up where you left off. it supports multiple terminal sessions.


7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
how to create files
open vs code
navigate to the folder where you want to create the file using the explorer side bar
right click on the folder name and select"new file"
enter the file name with the desired extension
opening files
in vs code,go to file>open , navigate to the file you want to open and select it.

creating folders
right click on the folder where you want to create a new one on the explorer side bar
select "new folder", enter the folder name.
opening folders
go to file>open folder 
select the file you want to open, click "open"

managing files and folders
renaming- right click on the folder or file in the explorer side bar:select rename and enter the new name
deleting- right click on the file or folder in the explorer sidebar:select delete. also, you can use the shortcut cmd+del(mac)or shift+del(windows)after selecting the file/folder.
moving- you can drag them to a new location in the explorer side bar.
searching- use the search bar at the top of the explorer sidebar.

a user can use the explorer sidebar(for file navigation,folder structure), command palette(one can type commands), go to (use ctrl+p for windows or cmd+p for mac as shortcuts, start typing the name of the file you want to open. vs code provides suggestions.), split editor- splits the editor vertically enabling you to view and edit multiple files side by side, which can be useful for comparing or editing related files simultaneously, extensions and keyboard shortcuts.


8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
users can find the gear icon located in the lower left corner of the activity bar to open the settings view.
use the search bar at the top of the settings view to find specific settings by name or functionality.

changing theme- click on the gear icon to open settings view. in the search bar at the top, type "color theme"and execute. click on the dropdown menu under "color theme"and select the theme you prefer
changing the font size- open vs code and go to settings. in the search bar,type"font size" and adjust the "editor:font size"setting as desired(eg 12,24,16)
changing keybindings- open vs code and go to preferences>keyboard shortcuts, search for the command you want to customise and click on the pencil icon next to it to edit. enter your desired keybinding sequence in the input field.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
setting up- configure debugging settings in "launch.json"
set breakpoints by clicking in the gutter next to line numbers
access debug controls from the activity bar.
start debugging session, inspect variables, step through code and view call stacks

debugging features- multiple language support, integrated debugging interface, breakpoints, variable inspection, call stack navigation, watch expressions, debug console, run and debug configurationsand debugging tasks


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.
ensure git is installed in your machine
open your project in vs code(if your project is not under version control,initialise a git repository: open the integrated terminal in vs code>view>terminal ,use the "git init" command to initialise a new git repository in your project directory)
click on the git icon to open the source control view.
use the "+" button next to each file in the source control view to stage changes to commit
commit message- enter a commit messagein the text box at the top of the source control view and press "ctrl+enter' to commit changes
create a repository in github by clicking on the new button in order to create a new repository, enter repository name,choose visibility and initialize with a readme file. 
in vs code, add the remote repository url to ypur local repository" git remote add origin https...."
push the committed changes to github using "git push -u main.

references;chatgpt, class slides.

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

