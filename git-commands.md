# FOR NEW PROJECT
1. Git Initialization
    ```
     git init
    ```
2. Add files and folders to git for tracking
    ```
    git add .
    ```
   **Note: . is for all files and folder , in place of . we can add files name.**
3. After completing: save all the codes as some version
    ```
    git commit -m "[Your_commit_message]"
    eg: git commit -m "project initialized"
    ```
4. Optional Step: changing main branch

    ***NOTE:default branch is always "master"****

    ```
    git branch -M "[your_main_branch_name]"
    ```
5. Add remote repo link or repository url
    ```
    git remote add origin "[your_repository_url]"
    ```
6. Push the recent commited code to remote for first time:
    ```
    git push -u origin "[your_current_branch_name]"
    ```
   Later (if one push is already done using -u: `upstream`)
   ```
    git push
   ```
7. To preview the current  gitstatus
    ```
    git status
    ```
8. To check linked remote url
    ```
    git remote -v
    ```
9. to check the list 
    ```
    git config --list
    ```

# Extra commands
1. to check the status of git (vcs)
    ```
    git status
    ```
2. To update thr remote repo url
    ```
    git remote set-url origin [your_repo_url]
    ```
    To verify/display added remote url:
    ```
    git remote -v
    ```    
3. To config the user.name and user.email:
    ```
    Project Based Config:
    git config user.name [your_github_username]
    git config user.email [your_github_email]
    ```
    Global Config:
    ```
    git config --global user.name[your_github_username]
    git config --global user.email [your_github_email]
    ```
   To verify/display Config
   (Note: enter to view more config and q to exit the opened editor):
   ```
   git config --list
   ```
g
 # AFTER CHANGING ON PROJECT

 1. git add .
 2. git commit -m "[your_commit_message]"
 git push

 # using personal access token (PAT) on https url:
- https://[PAT]@github.com/[github_username]//[project_name]

 To update the remote url:
 - git remote set-url origin 
