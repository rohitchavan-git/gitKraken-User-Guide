# Intro
This is a little guide to help you get introduced to using git with GitKraken

# Chapter 0: Setup
1. Install git: https://git-scm.com/download
2. Set user info using the command line
    * `git config --global user.email "you@example.com"`
    * `git config --global user.name "Your Name"`
3. Create your github account with your Brock email: https://github.com/
4. Get your github education pack: https://education.github.com/pack
5. Install GitKraken: https://www.gitkraken.com/download
6. Sign into GitKraken using your Github account

# Chapter 1: Working Locally
1. Open GitKraken
2. Click (2) in the top left corner to initialize a new repository.
3. Go to Init, and create a "Local Only" repository. Create a folder called "git-stuff" and set it as your "New repository path". Click "Create Repository"
4. Create a text file in the "git-stuff" folder. (A "README.md" is automatically created for you)
5. In GitKraken, click "// WIP" in the center window.
6. Click the green button that says "Stage all changes"
7. Type a message in the "Commit message" section.
8. Click "Commit changes to 1 file" button.
9. Your commit was added to the tree in the center of GitKraken.
10. Open the file you created and type in "Hello World". Save and close the file.
11. In GitKraken, you can inspect the file and see the changes that were made.
12. While inspecting, click "Stage File".
13. The file has now moved to the "Staged Files" section.
14. Type a messsage and commit.

# Chapter 2: Working with Github
1. Go to github and create a new project: https://github.com/new
2. Name it something descriptive, and make it private (So you can control who sees it), then click "Create repository"
3. Copy the url in "Quick Setup"
4. Go to GitKraken and click the "Green Plus" button that appears when you hover over "REMOTE" on the left.
5. Click "URL". Enter the name you want to commit with. Paste the URL you copied into "Pull URL" and "Push URL". Then click "Add Remote"
6. Click "Push" at the top. Click "Submit".
7. Refresh the github page and you will see your repo there.
8. Locally, add a new file, and put some text in it.
9. Add it to your repo and commit it.
10. Click the "Push" button.
11. Your changes will now be on Github.
12. On Github, click "Create new file". Name it something, and give it some contents.
13. On GitKraken, click the "Pull" button.
14. Now your local repo is up to date.

# Chapter 3: Working with another repo and Branches
1. Go to https://github.com/rohitchavan-git/full-stack-angular5-springboot2-example
2. Click the "Fork" icon in the top right to fork this repo to your github
   account.
3. Navigate to your github page
   (`https://github.com/<your_user_name>/`full-stack-angular5-springboot2-example`) Click "Clone or download" and copy the url
3. Go to GitKraken, click "File -> Clone Repo".
4. Select a location to clone to, and copy the paste the URL. Click "Clone the repo!"
5. Open the folder in GitKraken
6. Create a branch with your name
    * Click the "Branch" button at the top, and type in your name.
7. Create some files.
8. Add and commit them.
10. Check the differences between your branch by clicking on the commit in the GUI and selecting the file.
11. Checkout the master branch by double clicking on the branch on the left side.
12. You will see the file is now gone from your folder. But it is still on your branch. You can see this because the highlighted commit in GitKraken is one before the branch you created.
13. Get someone to add you as a collaborator to the repo.
14. Once done, switch to your branch, and push it. Click Submit
15. Now go to https://github.com/rohitchavan-git/full-stack-angular5-springboot2-example and you'll see your branch under "branches"
