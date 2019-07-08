# Github Tutorial

## Github upload walk-through

### Using Command Line (cli)
1. In your command line, navigate to your project directory. Type git init to initialize the directory as a Git repository.
2. Type git remote add origin https://github.com/jrgomez/github-upload.git
3. Type git add .
4. Type git commit -m "initializing repository"
5. Type git push -u origin master to push the files you have locally to the remote on GitHub. (You may be asked to log in.)

#### Using Atom
1. In Atom, open the folder for your project
2. At the top of your screen, click Packages. Select GitHub, and then toggle the Git Tab from the drop-down menu.
3. Select Create Repository within the Git tab on the right-hand size of your screen.
4. Select Init to accept the default prompt of the pop up window
5. In the Git tab, you can see that your files are ready for staging. It should be accounted for, but double check to make sure that none of your binaries or files that you listed in the .gitignore are listed in this dialog menu.
- If they are, double check your .gitignore file to make sure they're included or remove them from your directory.
6. Select Stage All
- This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
7. In the box at the bottom of the Git panel, type a commit message. Something like "initial commit - moving project" could work.
8. Select Commit
9. Close Atom
10. In your command line, navigate to your project directory.
11. Type git remote add origin https://github.com/jrgomez/github-upload
12. Return to Atom, and select the Up/Down arrow icon at the bottom of your Git Tab
13. Click Push, above the noted dialog.
14. Return to your repository, and note a successful push by finding your files on GitHub's code tab.
