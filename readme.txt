https://github.com/Nitesh-loop/web-project-react.git

#create a react project
npx create-react-app web-react
npm install react react-dom

#git setup:
git init
git remote add origin https://github.com/Nitesh-loop/web-project-react.git
git config user.email "nitesh166k@gmail.com"
git config user.name "Nitesh-loop"
git add .
git commit -m "Initial commit"
git push -u origin main

#Add GitHub Actions Workflow:
Create a .github/workflows directory in the root of your project, and within it, create a YAML file for your workflow, such as ci.yml.

#Commit and Push GitHub Actions Workflow:
git add .github/workflows/ci.yml
git commit -m "Add GitHub Actions workflow"
git push

#go to repo setting/pages
select the gh-pages in branch and save

#Add the homepage:
go to the react project and go to package.json:
add this line after "private"
"homepage": "https://nitesh-loop.github.io/web-project-react/",

#commit and push again






##########################################################

fatal: detected dubious ownership in repository at 'C:/Users/91865/Documents/Nitesh/projects/vs code project/web-react'
'C:/Users/91865/Documents/Nitesh/projects/vs code project/web-react/.git' is owned by:
        BUILTIN/Administrators (S-1-5-32-544)
but the current user is:
        DESKTOP-L1PJA6M/sumitvyz (S-1-5-21-2002555106-2911254780-3496387047-1001)
To add an exception for this directory, call:

        git config --global --add safe.directory 'C:/Users/91865/Documents/Nitesh/projects/vs code project/web-react'

----------------------------------------------------------------------------------------------------------------------------------

This error typically occurs when there is a discrepancy between the owner of the .git directory and the current user. To resolve this issue, Git provides a mechanism to add an exception for the directory in question.


>> git config --global --add safe.directory 'C:/Users/91865/Documents/Nitesh/projects/vs code project/web-react'



This command adds an exception for the specified directory, allowing Git to proceed without encountering the ownership issue.

After adding the exception, you should be able to use Git commands in the repository without further issues.


##########################################################





