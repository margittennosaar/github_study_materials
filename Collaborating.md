# Collaborating on GitHub

1. **Clone** project you want to work with

        git clone repo_URL

2. Make sure that you are working with the latest version. **Pull** the newest code.

        git pull origin main

3. Start working with **your branch and switch to it**

        git checkout -b my_branch_name

4. Make changes you want and then **add changes to staging**

        git add .

5. **Commit your changes** to staging

        git commit -m "what those changes were about"

6. **Push your branch to remote repo**. Please note that you might have multiple commits done before you push it. 

        git push origin my_branch_name

7. On remote repo (GitHub page), you have now one pushed branches. The next step is to **compare changes and pull request** for merge changes to main.

8. Write comments if needed and **create pull request**. 

9. You can specify **reviewer** to send a notification to them for checking your code. 

10. If there are no conflicts, you can easily **merge pull request**.

11. After the merge, you can **delete your branch**. 

12. When you continue to contribute to this project, start over from step 2. 

    In a nutshell: 
    - checkout main to be in the right branch
    - pull main
    - create and switch to a new branch
    - add changes
    - commit changes
    - push your new branch
    - in GitHub, review the code and if all good, merge it
    - delete branch
