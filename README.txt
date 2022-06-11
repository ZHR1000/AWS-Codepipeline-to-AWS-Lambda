Reference: https://www.serverlessguru.com/blog/aws-ci-cd-pipeline-to-deploy-a-serverless-framework-project

Commands:
<pre-requisite node js and npm>
PS D:\GIT\AWS-GIT\zpoc> npm install -g serverless
PS D:\GIT\AWS-GIT\zpoc> serverless create --template aws-python3
PS D:\GIT\AWS-GIT\zpoc> git init
PS D:\GIT\AWS-GIT\zpoc> git remote add origin <AWS-Repo-HTTPS-URL>
PS D:\GIT\AWS-GIT\zpoc> git status
PS D:\GIT\AWS-GIT\zpoc> git add .
PS D:\GIT\AWS-GIT\zpoc> git commit -am "Update codes"
PS D:\GIT\AWS-GIT\zpoc> git push --set-upstream origin master
