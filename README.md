Step-by-step instructions:
1. Create new project folder and navigate into it via terminal
2. Initialize new git repository: git init new-project
3. Add files in main brunch 
4. Commit added files in main brunch: git commit -a -m"commit_message"
5. Specify remote repository URL: git remote add main <your_repo_url>
6. Push your commit to remote repository: git push main master
7. Create new dev branch and checkout into it: git checkout -b /branches/development
8. Add needful files and changes
9. Commit changes: : git commit -a -m"commit_message"
10. Push your commit to remote repository: git push main development
11. If you need to merge changes from development branch into main: 
    11.1 Checkout main branch: git checkout main
    11.2 Merge branches: git merge development