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

