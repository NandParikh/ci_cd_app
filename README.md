# ci_cd_app

A new Flutter project.

## Getting Started CICD

- Create simple flutter project in vs code
- create new GitHub project
- copy the GitHub url
- go to vs-code and in repository commit and push code
- add your project name and GitHub remote url
- push the code
- check code is on GitHub
- now for ci/cd : create folder called ".github" under your flutter project dir
- add another folder named "workflows"
- add file name called "main.yaml"
- which contains branches and jobs
- this file required secrets.TOKEN for that
- now go to GitHub > project > settings > secrets and variables > Repository secrets > New repository secret
- You are in Actions secrets/ New secret
- Add name like :TOKEN
- for secret : go to GitHub profile > Settings > Developer settings > Personal Access Token > Token classic > Generate new token (classic) > set expiry 
- Add notes like "GitHub actions"
- Select scope : Repo checkbox checked and save

