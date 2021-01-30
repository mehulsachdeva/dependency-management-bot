# dependency-management-bot

HAVE YOU EVER BEEN WORRIED ABOUT KEEPING YOUR NODE MODULES UP TO DATE? <br />
This collection solve this for you by going through the package.json of your configured repository on GitHub, figures out which dependencies have a pending minor or patch update and create a pull request for the same. <br />

SETUP <br />
Let's go through how you can set this up for your needs. <br />

Note: This collection uses the Auto Update Node Modules Bot environment present in the workspace. Make sure you copy that over to your workspace before trying to run this collection. <br />

1. GitHub Token <br />
Navigate to GitHub Settings to create a new token to be used in this collection and set it in the provided environment in the token key. Also, make sure you set your GitHub username as the value of the username key. <br />

2. Repository Details <br />
repository: GitHub Repository Name <br />
pullReqBase: Target Branch for the Pull Request as well as the branch where the new branch is to be created from <br />
newBranch: The name of the new branch <br />

Once all these values are set, just setup a monitor that runs once a day and sit back and relax!
