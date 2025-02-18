# A02

How to use VS Code: <br>
Step 1. Install VS Code <br>
You can go to VS Code's official website to download it, make sure you download it for the proper OS. <br>
Step 2. Open VS Code <br>
After the download is complete you can launch VS Code <br>
Step 3. Open a Folder or File <br>
So once VS Code fully opens you will have to Click File > Open Folder (to work with a project). This will open and the folder and display the code files that you have inside it. <br>
Step 4. Install Extensions (Optional but Recommended) <br>
Since it is the first time insalling VS Code you will most liekly need to install extensions to be able to code in the language you would like to. So to download an extension you have to click the Extensions icon  or (Ctrl + Shift + X). Then you search for the extension you are looking for, an example could be downloading the Java Extension Pack. <br>
Step 5. Open the Terminal <br>
To open the terminal you would click Terminal > New Terminal, this is going to allow you to run commands like compiling code, running scripts, or using Git <br>
Step 6. Create and Edit Files <br>
Now to create a file you can click File > New File or Right-click in the Explorer Panel and select New File. Also make sure that the end of the file name ends in whatever language you are going to code in. For example if you are going to code in python you would end the file name with .py <br>
Step 7. Run Code <br>
To be able to run the code you can install the Code Runner extension or you can use the built-in terminal to run code. So for java if you are using the terminal you would have to compile the file by saying javac file.java then after it is compiled you have to write java file, then this should work and run your code. <br>
Step 8. Use Git for Version Control (Optional) <br>
So you can use Git as a version control where you can send all your files to as a back up. So to be able to use git you have to open a new terminal, the default terminal should be powershell so to use git you are going to have to make a new terminal and open a git bash terminal. Then after that you will have to initialize and link your computer with git using a specific lines to terminal code. But after that process you would initialize a repository and add/commit changes. <br>
Step 9. Customize Settings <br>
So you can customize your setting but it is necessary to do it. But if you want to you would Click File > Preferences > Settings then you can adjust themes, font size, and other preferences. <br>
Step 10. Close VS Code <br>
Lastly you would make sure that everything is saved you can ctrl +s to save or you can Click File > Save. Then after making sure everything is saved you can close the application by clicking the X in the top right corner.  <br>

How to use __Git__: <br>
Step 1. Install __Git__ <br>
You can go to the official __git__ website which is git-scm.com, after installing __git__ you should open git bash but if you don't have that you can use terminal/command prompt. <br>
Step 2. Set Up __Git__ <br>
Since it's your first time you have to configure your name and email. The commands to do that are (git config --global user.name "Your Name" and git config --global user.email "your@email.com".<br>
Step 3. Create or initiliaze a __repository__ <br>
So to do this you will have to navigate to the project folder, you can do this by saying cd and then the path to the folder. Once you are in the folder you want to initialize the __repository__ you would put the command (git init).<br>
Step 4. You can check status of your __repository__ <br>
So now that you made the __repository__ you can check the status of the __repository__ with the command (git status). This command will show which files are untracked/tracked and modified files.
Step 5. Add Files to staging 
You can add files to get tracked and you can also use this command to add files to the stage to when you want to __push__ something to __github__. The commands for this would be (git add . and git add filename).<br>
Step 6. __Commit__ Changes
So after you do the add command you can commit to save your changes with a commit message. The command for this would be (git commit -m "Message").<br>
Step 7. Creating a __branch__ <br>
to create and switch to that branch you would do the command (git checkout -b newbranchname). And to switch to a branch only you would do (git checkout branchname).<br>
Step 8. Merging branches<br>
To merge a branch you would switch to the main branch and the you would do the merge command with the branch you want to merge with. So the commands for this would be (git checkout main) and (git merge newbranchname).<br>
Step 9. Undo changes (ONLY when needed)<br>
To undo the last commit but keep the changes that occured in the commit you would do (git reset --soft HEAD~1) but to discard both the commit and the changes you would do (git checkout -- filename)<br>


How to use GitHub:<br>
Step 1. Create an account<br>
You would go to github.com to create an account.<br>
Step 2. Creating a Repo<br>
To create a new repo through github you would click new repository and then give it a name and decide the status of it if it will be public or private then after that you would click create repository. <br>
Step 3. Connect your local Git repo with GitHub<br>
To do this you would copy and paste the ssh url from GitHub to your terminal. The command for this would be (git remote add origin https://github.com/your-username/repo-name.git).<br>
Step 4. Pushing code to GitHub<br>
So to push code to GitHub it would be a similar process to the push from git. The command is (git push origin main)<br>
Step 5.Clone a Repository <br>
To clone a repo you will have to be in your terminal and put the command Run(git clone https://github.com/username/repo-name.git)<br>
Step 6. Pull Latest Changes from GitHub<br>
If you want to get the latest changes from the remote repository the command is (git pull origin main).<br>
Step 7. Creating a pull request <br>
So when you make a commit you will need to open aa pull request before hand. So to do this you will have to be on GitHub and click the Pull Requests and then click New Pull Request. That will create a new pull request and then you can push and commit the changes you have to the code. When you are finished all you would do is simply close the pull request.<br>





Glossary:<br>
Branch-A branch is a separate version of your project where you can make changes without affecting the main code.<br>
Clone-To clone means to create a local copy of a GitHub repository on your computer.<br>
Commit-A commit is a saved snapshot of changes in your repository.<br>
Fetch-Fetch downloads the latest changes from a remote repository but does not automatically update your local branch.<br>
GIT-Git is a version control system that tracks changes in code. <br>
Github-GitHub is a cloud-based platform that hosts Git repositories.<br>
Merge-To merge means to combine changes from one branch into another, usually integrating a feature branch into the main branch.<br>
Merge Conflict-A merge conflict occurs when Git cannot automatically merge changes because the same lines in a file were modified in different ways.<br>
Push-Push uploads your local commits to a remote repository, making your changes available on GitHub.<br>
Pull-Pull fetches and integrates the latest changes from a remote repository into your local branch.<br>
Remote-A remote is a connection to a Git repository hosted on GitHub or another server.<br>
Repository-A repository (repo) is a Git project that contains all the files, folders, and commit history for a project.<br>

Refrences:<br>
https://www.w3schools.com/git/default.asp<br>
For all 3 git,github, and vs code I have worked with them previousoly so that is where most of the knowledge came from.<br>








