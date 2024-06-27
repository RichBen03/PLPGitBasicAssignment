# PLPGitBasicAssignment
### 1. GitHub Repository Creation:

-  I Logged in to my GitHub account.
-  I Created a new repository on GitHub and called it PLPBasicGitAssignment
- I Initialized it with a README file.

### 2. Local Folder Setup:

- I opened my gitbash and navigated to my c drive using the cd command(cd C:/)and created a new folder called PLPBasicGitAssignment inside my C drive using the mkdir command.(mkdir PLPBasicGitAssignment)
- I navigated to folder i created using the cd command(cd PLPBasicGitAssignment )

### 3. Git Initialization:

- I Initialized a new Git repository in my folder using the init command:
  git init and it said i have intialixed an empty repository
### 4. Connecting to Github:
-   I Linked my local repository to the GitHub repository i had intially created in github using the git remote add origin command

**SINCE MY BRANCH WAS MASTER I HAD TO SWITCH BETWEEN THE MAIN AND MASTER BRANCHES:**
**git config init.defaultBranch main**
**then renamed my branch to main git branch -m master main**
### 4. Creating files
- Inside my current working directory,i created a new text file,hello.txt, using the touch command in UNiX, touch hello.txt then added a simple text,"Hello, Git!", by using the vi editor and going to insert mode by pressing "i" on my keyboard to enable me to type. Later after finishing editing my file i exited the vi editor by pressing "shift with combination with double zz"(shift+zz)

### 4. Committing changes:
- I staged my changes by using the git add . command then commited my work using git commit and whilst added a message "Added hello.txt with greetings" git commit -m ""Added hello.txt with greetings"
- 
### 4. Pushing to Github:
- I then pushed my changes to github using the command git push -u origin main
  
