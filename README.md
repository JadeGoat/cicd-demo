# cicd_github_template

# cicd_react_template

# Setup
#### Repo
Clone repo using command
```
git clone <url>
```
#### React
Install base package using command
```
npm install
```

# Usage
#### To Run code
Run command
```
npm run dev
```
#### Build docker image and run
eg. Access http://localhost:5173/cicd_github_template

# Troubleshooting
#### Renaming repo name
Update config in vite.config.js to be same as repo name

#### Github Page
Update the node-version in the workflows/cd_deploy.yaml to be the same as package.json
