# dependency-management-bot

HAVE YOU EVER BEEN WORRIED ABOUT KEEPING YOUR NODE MODULES UP TO DATE?
This collection solve this for you by going through the package.json of your configured repository on GitHub, figures out which dependencies have a pending minor or patch update and create a pull request for the same.

SETUP
Let's go through how you can set this up for your needs.

Note: This collection uses the Auto Update Node Modules Bot environment present in the workspace. Make sure you copy that over to your workspace before trying to run this collection.

1. GitHub Token
Navigate to GitHub Settings to create a new token to be used in this collection and set it in the provided environment in the token key. Also, make sure you set your GitHub username as the value of the username key.

2. Repository Details
repository: GitHub Repository Name
pullReqBase: Target Branch for the Pull Request as well as the branch where the new branch is to be created from
newBranch: The name of the new branch
Once all these values are set, just setup a monitor that runs once a day and sit back and relax!
