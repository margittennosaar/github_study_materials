# Beginning with GitHub

If you do not have GitHub account yet then create it first - [GitHub signup](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home).

- [Steps with README file](#sub-heading)
- [Steps without README file](#sub-heading-1)
- [Everyday workflow with GitHub](#sub-heading-2)



## Steps (creating repo with README file)

1. Create [a new repository](https://docs.github.com/en/github/getting-started-with-github/create-a-repo) in GitHub.

2. Using terminal or another command-line tool, create a new folder to your project, in a location you want. 

        mkdir your_project_name

3. Get into the new project folder

        cd your_project_name

4. Create a local git repository

        git init

5. Connect local and remote repositories 

        git remote add origin URL_TO_REPO

6. Check for the changes and pull the latest code from GitHub

        git pull origin main

7. Write code; make your changes. When you are done, add your changes to staging.

        git add . 

8. Commit your changes

        git commit -m "write a short title for your changes you are committing"

9. Push your changes to the remote repository

        git push origin main

**In a nutshell:** 

- make remote repo
- make local repo 
- connect remote and local
- pull changes from remote to local
- make changes and then add changes
- commit changes
- push changes

## Steps (creating repo without README file)

1. Create [a new repository](https://docs.github.com/en/github/getting-started-with-github/create-a-repo) in GitHub.

2. Using terminal or another command-line tool, create a new folder to your project, in a location you want. 

        mkdir your_project_name

3. Get into the new project folder

        cd your_project_name

4. Create a local git repository

        git init

5. Add README file

        echo "# Project title" >> README.md

6. Add your changes to staging.

        git add . 

8. Commit your changes

        git commit -m "first init"

5. Connect local and remote repositories 

        git remote add origin URL_TO_REPO

6. Push your changes to the remote repository

        git push origin master

**In a nutshell:** 

- make remote repo
- make local repo 
- make README file
- add changes
- commit changes
- connect remote and local
- push changes

## Everyday work with GitHub 

- **pull** latest code from remote repo
- make your changes
- **add** your changes to staging 
- **commit** your changes to staging
- **push** your changes