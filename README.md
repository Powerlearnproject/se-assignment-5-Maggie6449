[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15384357&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
  *Download visual studio code
   .open your web browsernand go to the visual studio code website
   .click on the"Download" button
   .select the windows version to download the installer.
  *Run the intaller
    . once the download is complete, locate  the downloaded file in your downloads folder.
    .double click  the installer to run it.
   *Select Workloads and Components:
     In the Visual Studio Installer, select the workloads and components you need based on your development requirements. Common workloads include ".NET Desktop Developor"Web 
       Development.
   *Install
     Click the "Install" button to start the installation process.
     This may take some time, as it involves downloading and installing the selected components.
   *Launch Visual Studio:
    Once the installation is complete, launch Visual Studio.
    Sign in with your Microsoft account or create one if prompted
   *Choose Development Environment:
   On the welcome screen, select your development environment. For example, you can choose "Development Settings" based on your preferred coding style.
   *Start Coding:
    You're now ready to start coding! Create a new project or open an existing one to begin your development work.




2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
     *Theme and appearance
      go to "file>preference>color theme' to choose a theme that suits your preference
      customize the editor font size and family   by  going to 'file> preference> settings' and searching for "font"
     *Extensions
     go to the entensions view by clicking the extension icon in the activity bar on the side of the window
     install essential extensions for your development needs e.g Python- provides intellisense,debugging and more
     Gitlen-enhances git capabilities with  vs code.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.
     *Activity bar-located on the far left
                   it allows you to switch between different views like explorer,search
     *Side bar-this is the main area for the explorer, search, sourcecontrol.
               it provides detailed panels and tools for managing files,searching within the project and more.
     *Editor bar-the cental area where you open and edit files.
                 suppots multiple tabs for different files and allow splitting into multiple editor groups efor side by sidre editing.
     *status bar-you can perform actions like opening files, runningtasks and managing extension

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.
     *command palette is a powerful feature tha provides a wide range of commands and functinality within editor.
     it allows you to perform tasks, open files, manage extensions
     to open command; go to 'view.command palette' in the top menu bar.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
     *Extension enhances functionality by adding language support, productivity tools, theming options,debugging enhancements and tools for maintaining code quality.
     it can be opened by opening the extension view ,searching for desired extension,and clicking the "install" button; they can also manage installed extension from view by enabling ,disabling, updating or uninstalling them.
     examples;prettier-an opionated code formatter
              Enslint-integrates the enslit javasript linter
              python

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
     *you can click on "Terminal" in the top menu and select "New Terminal,"
     Advantage;
         *seamless integration- it is directly intergrated within vs code, allowing you to work within the same window without switching between applications
         *context awareness- the integrated terminal automatically opens to the  workspace directory you are currently working in.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?
     *creating - click on the explorer icon in the activity bar to open the explorer view., right click on the parent directory where you want to create,select "New file" or "New folder" from the context menu and enter the folder name.
     *open-
     

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.
     *user can custonmize settings through the setting UI accessible  via the gear icon in the activity Bar, where they can modify preferencesglobally using a son file.this is flexiblility allows for tailored confirgurati onin editor behaviour, themes, extensions  and key binding to enhance coding efficiency and workflow management.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?Open Project: Open or create a project folder where your program files are located
   - 
Install VS Code: Download and install Visual Studio Code from their official website.
Install Extensions (if necessary): Add language-specific extensions for better support.
Set Breakpoints: Click in the gutter next to line numbers to set breakpoints where you want the program to pause.
Configure Launch Configuration: Create or configure launch.json to specify how to start your program in debugging mode.
Start Debugging: Press F5 or use the play button in the Debug view to launch your program in debug mode.
Debugging Controls: Use controls like Step Over, Step Into, and Continue to navigate through your program's execution.
Inspect and Interact: Monitor variable values, view call stacks, and interact via the Debug Console to diagnose issues.

Keys;
Variable Watch: Monitor the values of variables in real-time.
Call Stack: View the current execution stack trace and navigate through it.
Conditional Breakpoints: Pause execution only when certain conditions are met.

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub
      
      *Install Git:Ensure Git is installed on your system. You can download it from Git's official website.
      *Install VS CodeDownload and install Visual Studio Code from the official website: VS Code Download
      *.Open Your Project Folder:Open the project folder in VS Code where you want to initialize Git.
      *Initialize Git Repository:Open the Command Palette (Ctrl+Shift+P or Cmd+Shift+P) in VS Code.
                                Type and select "Git: Initialize Repository".
                                Choose the folder you want to initialize as a Git repository.Stage and Commit Changes:


      *Stage and Commit Changes:In VS Code, you'll see changes in the Source Control view (third icon in the Activity Bar on the side).
                                Click on the + next to any file you want to stage (prepare for commit).
                                Click on the + next to any file you want to stage (prepare for commit).Click the check mark icon to commit your changes locally.
      *Push Changes to GitHub:
                              Make sure you have a GitHub account and create a repository on GitHub if you haven't already.


      *Add Remote Repository:After committing changes locally, click on the "Publish to GitHub" button that appears in the bottom right corner of the VS Code window.
                             If prompted, sign in to GitHub and select the repository you want to push changes to.
       *Push Changes:After configuring the remote repository, VS Code will push your committed changes to GitHub. You'll see progress notifications in the bottom left corner.






                                
                                






:






 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

