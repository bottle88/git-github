How to Push local files to github?


Step 1: Create a new repository on GitHub
- Go to github.com and log in to your account.
- Click on the "+" sign in the top-right corner and select "New repository".
- Enter a name for your repository, a description (optional), and choose any additional settings you want.
- Click on "Create repository".

Step 2: Initialize Git in your local project directory
- Open your terminal or command prompt.
- Navigate to the root directory of your project using the `cd` command.
- Run the following command to initialize Git:
```
git init
```

Step 3: Add your files to the Git repository
- Use the following command to add all the files in your project directory to the Git repository:
```
git add .
```
Note: The `.` specifies that you want to add all files. If you only want to add specific files, you can specify their names instead of using `.`.

Step 4: Commit your changes
- Use the following command to commit your changes with a meaningful message:
```
git commit -m "Initial commit"
```
Replace "Initial commit" with your own descriptive message.

Step 5: Add your GitHub repository as a remote
- Go to your GitHub repository page and copy the URL provided (e.g., https://github.com/your-username/your-repo.git).
- In your terminal, run the following command to add the remote repository:
```
git remote add origin <repository-url>
```
Replace `<repository-url>` with the URL you copied from GitHub.

Step 6: Push your changes to GitHub
- Use the following command to push your local commits to the remote repository on GitHub:
```
git push -u origin master
```
Note: If you're working on a different branch instead of the `master` branch, replace `master` with the name of your branch.

Step 7: Enter your GitHub credentials
- When prompted, enter your GitHub username and password to authenticate and push your changes to the remote repository.

After completing these steps, your local project will be added to GitHub. You can now view your project on GitHub and continue pushing your changes using `git push` in the future.


To push changes in the local repo to github ,

1. ```git add . ```

2. ```git commit -m "Second commit"```

3. ```git push ```


DOUBTS?

idk why i am unable to add files to 'main' branch ?