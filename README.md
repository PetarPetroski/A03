# A03
**PART 1: Create Tutorial on Setting up Git/Webstorm/Github**
-----------------------------------------------------------------------

To set up Git/Webstorm/Github, first you need to download them.

Download Webstorm from : https://www.jetbrains.com/student/

Download Git from : https://git-scm.com/downloads

Create a Github account: https://github.com/join

Firstly, go to the official Git website (https://git-scm.com/downloads) and download the latest version of Git for your operating system.

Once the download is complete, locate the downloaded file and install Git by following the instructions. In most cases, double-clicking the file should start the installation process.

You may choose to uninstall the previous version of Git, if you have any, and install the new version that you just downloaded.

Open Webstorm, your integrated development environment (IDE).

Check for updates in Webstorm by going to the Help menu and selecting "Check for Updates." Make sure you have the latest version of Webstorm.

Open the Webstorm settings by pressing (Ctrl+Alt+S) and select "Version Control" from the left-hand menu. Then, select "Git" as your version control system. (Jetbrains)

Click on "Test" to check if Webstorm is correctly connected to Git. The path in the location box should be C:\Program Files\Git\bin\git.exe. If Git is installed correctly, you will get the message "Git Executed Successfully" along with the version number. If not, download Git by following the instructions in Step 1.

Click "OK" to exit the settings.

Click "Create New Project" on the Webstorm main page.

Choose a location and give your project a name. Replace the word "untitled" with the name you choose. For example, you can name it "IS117DemoS20" and save it at C:\IS117Download\Webstorm\IS117DemoS20.

Click "Create."

Create a new file by clicking File -> New -> HTML File -> HTML 5. Name the file "index" in lower case.

Make some changes to the file.

Go to VCS -> Import into Version Control -> Create Git Repository.

Click "OK."

Commit the changes to Git by going to VCS -> Git -> Commit File. Click "Commit." If this is your first commit, you will be prompted to set your Git username and email. Use your .EDU email and click "Set and Commit."

Add the project to GitHub by clicking VCS -> Import into Version Control -> Share Project on GitHub. Click "Share." If successful, you will receive a message saying "Successfully shared project on GitHub." Your file is now on the internet. (GitHub Guides)

Add a new file to the GitHub repository by creating a new file and naming it "README.MD."

Add some text to the file and commit the changes.

Make a change to the index.html file in Webstorm.

Commit the changes to Git by going to VCS -> Git -> Commit. Add a commit comment and click "Commit."

Push the change to GitHub by going to VCS -> Git -> Push (Ctrl+Shift+K).

**Congratulations! Your revised index.html file is now on GitHub.**

**Part 2: Glossary to include these terms in a bulleted list.**
-----------------------------------------------------------------------

**Branch**- A branch is like a separate copy of a project where you can make changes without affecting the original version. This allows you to work on new features or fixes without disrupting the main version that people use. Once you're done making changes, you can merge your branch back into the main version to add your changes to the live version. (GitHub Docs)

**Clone**- A clone is like making a copy of a project and keeping it on your computer instead of on a website. This allows you to work on the project without being connected to the internet. You can make changes to the project using your preferred software, and Git will help you keep track of those changes. The original project is still available on the website, so when you're back online, you can upload your changes to the website to keep everything up to date. (GitHub Docs)

**Commit**- A commit is like a record of changes you make to a file or a group of files. When you save your work using Git, it gives each change a special ID that lets you keep track of who made the changes and when. You can also add a short message to describe what changes you made. This helps you keep track of the different versions of your work and makes it easier to find specific changes later. (GitHub Docs)

**Fetch**- Using "git fetch" is like checking for updates to a project without actually changing anything on your own computer. It gets the latest changes from the website where the project is stored and brings them to your computer, but it doesn't make any changes to your version of the project until you decide to do so. This allows you to review the changes made by others before deciding whether to keep them in your version of the project. In contrast, "git pull" automatically merges the changes into your version of the project without giving you a chance to review them first. (GitHub Docs)

**GIT**- Git is a free tool used to keep track of changes in text files. It was created by the same person who made the Linux operating system and is the foundation for GitHub, a website that makes it easier to share and collaborate on code. (GitHub Docs)

**Github**- A website where people can store and collaborate on projects using Git version control software. It provides tools for tracking changes made to code and other files, and allows people to work together on projects from different locations. GitHub is used by developers and other people who work with code to share and improve software projects. (Beer)

**Merge**- Merging means taking the changes made in one version of a project and adding them to another version of the same project. This is usually done when someone has suggested changes to a project and wants to add them to the main version. This is called a "pull request". Merging can be done using the website where the project is stored, or by typing commands into a program called the command line. If the changes don't conflict with each other, the website can automatically merge them. If there are conflicts, merging has to be done using the command line. (GitHub Docs)

**Merge Conflict**- A merge conflict is a problem that happens when different versions of a project have changes to the same part of a file, or when one version changes a file while another version deletes it. This makes it hard to merge the changes together. Before the changes can be merged, the conflict has to be fixed by either combining the changes or choosing which version of the file to keep. (GitHub Docs)

**Push**- Pushing means sending your changes to a website where other people can see them. This is useful when you've made changes to a project and want to share them with other people who are working on the same project. For example, if you've changed a file on your own computer, you can push those changes to the website so that everyone else can see them too. This allows everyone to work with the latest version of the project. (GitHub Docs)

**Pull**- Pulling means getting changes made by others and combining them with your own changes. This is useful when working on a project with other people and you want to make sure everyone has the latest version of the project. For example, if someone has made changes to a file that you're both working on, you can pull in those changes to your own copy so that you're all working with the most up-to-date version. It's similar to "fetching", which is also a way to get changes from others, but pulling automatically merges the changes into your own copy. (GitHub Docs)

**Remote**- A remote version is a copy of a project that's stored on a website like GitHub.com. It's the version that everyone can see and work on. People can make copies of this version on their own computers, which are called local clones. The local clone can be connected to the remote version so that changes made to the project on the local computer can be shared with others by syncing the changes with the remote version. This ensures that everyone is working with the same version of the project. (GitHub Docs)

**Repository**- A repository is like a folder for a project. It contains all the files and documents related to the project, and keeps track of changes made to each file. This means you can see who made changes to the project and when. Repositories can have many people working on them together, and can be public (anyone can see them) or private (only certain people can see them). (GitHub Docs)

**Works Cited**
-----------------------------------------------------------------------
GitHub. (n.d.). GitHub glossary. GitHub Docs. Retrieved February 14, 2023, from https://docs.github.com/en/get-started/quickstart/github-glossary 

Beer, B. (2018). Introducing GitHub. 2ed. O’Reilly Press. 

Jetbrains. (2019). Git.   Retrieved March 21, 2019, from https://www.jetbrains.com/help/webstorm/using-git-integration.html

GitHub (2019) GitHub Guides Tutorial. Retrieved  March 19, 2019, from https://guides.github.com/activities/hello-world/ 
