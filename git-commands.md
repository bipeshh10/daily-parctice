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
    gitpush
   ```
7. To preview the current  gitstatus
    ```
    git status
    ```
8. To check linked remote url
    ```
    git remote -v
    ```
