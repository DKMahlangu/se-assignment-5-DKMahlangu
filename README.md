# SE-Assignment-5
## Installation and Navigation of Visual Studio Code (VS Code)

### 1. Installation of VS Code:
   - To download VS Code go to your web browser then the official Visual Studio Code website (https://code.visualstudio.com/). Click on the "Download for Windows" button. This will download the installer (.exe file) for VS Code.
   - Once the download is complete, navigate to your Downloads folder and double-click the VSCodeSetup.exe file to run the installer.
   - Read through the license agreement and click "I accept the agreement" if you agree.
   - Choose where you want to install VS Code. The default location is usually fine.
   - You will be presented with several additional options. It is recommended to check the create a desktop icon box, Add to PATH (available after restart) box, Register Code as an editor for supported file types box, and Add "Open with Code" action to Windows Explorer file context menu box.
   - Click "Next" to go through the setup steps.
   - Finally, click "Install" to begin the installation process. Wait for the installation to complete. This should only take a few minutes.
   - Once the installation is complete, you can choose to launch VS Code immediately by checking the "Launch Visual Studio Code" checkbox and clicking "Finish". Alternatively, you can launch VS Code from the desktop icon or by searching for "Visual Studio Code" in the Start menu.

### 2. First-time Setup:
**Initial configurations and settings that should be adjusted are:**
   - **Theme:** Go to `File > Preferences > Color Theme` or `(Ctrl+K, Ctrl+T)` and choose a theme that suits your preference.
   - **Font:** Adjust the font size and family by going to `File > Preferences > Settings` or  `(Ctrl+,)` and searching for editor.fontSize and editor.fontFamily.
   - Enable **Auto Save** to automatically save your work by going to `File > Auto save`.

**Recommended extensions.**
   - **Prettier - Code Formatter:** Automatically format your code.
   - **ESLint:** For JavaScript and TypeScript linting.
   - **Visual Studio IntelliCode:** Provides AI-assisted code completions.
   - **Debugger for Chrome:** Debug JavaScript code running in the Chrome browser.
   - **Live Server:** Launch a development local server with live reload feature for static & dynamic pages.
   - **Path Intellisense:** Autocompletes filenames.
   - **GitLens:** Enhances Git capabilities with features like blame annotations, rich commit history, and more.
   - **GitHub Pull Requests and Issues:** Integrates GitHub pull requests and issues directly into VS Code

### 3. User Interface Overview:
The main components of the VS Code user interface are designed to enhance productivity and streamline the development process.

Identify and describe the purpose of:
   - **The Activity Bar:**
     Located on the far left-hand side. The Activity Bar allows users to switch between different views and provides quick access to various functionalities like Explorer, Search, Source Control, Debug, and Extensions.
     
   - **The side Bar:**
     Located on the right side of the Activity Bar. The Side Bar shows context-specific views based on the selected activity from the Activity Bar, such as file navigation, search results, source control status, and debugging tools.

   - **The Editor Group:**
     Located at the central area of the interface. The Editor Group is where you write, edit, and view your code files. VS Code allows multiple editor groups for side-by-side editing.
     
   - **Status Bar:**
     Located at the bottom of the interface. The Status Bar provides information about the current state of the editor and workspace. It offers shortcuts and contextual information relevant to the file or task at hand, such as current branch, line and column, language mode, spaces/tabs and size, encoding and more.

### 5. Command Palette:
**What is the Command Palette in VS Code, and how can it be accessed?**
 
The Command Palette in VS Code is an indispensable tool that provides quick access to a wide range of commands and features, enhancing your productivity and efficiency. You can access the command pallet by pressing  `Ctrl+Shift+P` or by clicking on the `View` menu at the top of the screen then select `Command Palette` from the dropdown menu
  
**common tasks that can be performed using command pallet are:** 

 -Openning a file or folder [ go to command pallet and type `create: file` or `create: folder` ]
 -Changing the theme color of your VS code [ go to command pallet and type `Preferences: Color Theme` ]

There are many examples of what you can do on the command pallet it depends on what you want, you just go to the command pallet and type what you want or only a part of what you want then enter, a list of suggestions will be shown then you'll choose what you want.
 
### 6. Extensions in VS Code:
**Discuss the role of extensions in VS Code.**

VS Code extensions let you add languages, debuggers, and tools to your installation to support your development workflow. They allow users to customize their development environment, add new features, and improve productivity by integrating tools and services directly into the editor

**How can users find, install, and manage extensions?**

You can browse and install extensions from within VS Code by clicking on the Extensions icon in the Activity Bar on the side of VS Code or on the command pallet you can type `View: Extensions`, a list of suggested extensions will be shown, you can browse through the list to check if the extension you want isnt listed or you can search for the extension you want to install, it is preferable to install an extension that is verified by microsoft or if it is not verified by mirosoft check how many times it has been downloaded and the ratings of it.

you can manage the extensions by clicking the `view` menu at the top of the screen then click `Extensions` all the extensions you have installed will be shown under `Installed`, you can enable or disable or update the extension you want by clicking on it.

**Provide examples of essential extensions for web development.**
  - Prettier
  - Live server, Go live, Live share
  - ESLint
  - Debbuger
  - IntelliSense for CSS class names in HTML
  - Bracket Pair Colorizer

### 7. Integrated Terminal:
The integrated terminal in Visual Studio Code (VS Code) is a built-in command line interface that allows you to execute shell commands directly within the editor. You can open integrated terminal by pressing  `Ctrl+Shift+P` to open the Command Palette then type `Terminal: Create New Integrated Terminal` and select it or go to the top menu and select `View > Terminal`.

**Integrated terminal is used for:**
   - Running commands
   - You can have multiple terminals
   - You can split the terminal view to have two terminals side-by-side.
   - You can Choose which terminal you want to use (e.g GitBash, Command prompt, Powershell).
     
**Advantages of using the integrated terminal**
   - **Convenience and Efficiency:** You can write code, run commands, and see the results without switching windows.
   - **Project Context:** The integrated terminal opens in the context of the current project directory, making it easier to run commands that are relevant to your project's files and structure.
   - **Consistency:** The look and feel of the terminal are consistent with the rest of the VS Code interface, providing a unified development environment.
   - **Multiple Terminals:** Easily manage multiple terminal instances within the same interface, allowing for tasks such as running a development server in one terminal and executing Git commands in another.
   - **Task Automation:** You can run VS Code tasks directly in the integrated terminal, automating repetitive commands and workflows.
   - **Environment Integration:** The integrated terminal respects the environment variables and settings of the VS Code workspace, ensuring that commands run with the correct configurations.
   - **Extensions Support:** Some VS Code extensions enhance the terminal's capabilities, providing additional features and integrations that are not available in external terminals

### 8. File and Folder Management:
You can create or open a file or folder by going at the top of screen then click on `File` then select `Open file or folder` from the options shown or you can open the file or folder from the VS code explorer. The files or folders that you have created will be shown on the VS code explorer, there you can easily navigate through them and also manage them easily.

### 9. Settings and Preferences:
Settings are located at the bottom of the activity bar, you can click on them then `Theme` or you can go to `file > preference > settings` to manage settings or `file > preference > theme` to change the theme.

### 10. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

### 11. Using Source Control:
   - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.


