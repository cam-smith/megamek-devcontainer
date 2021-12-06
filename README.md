# megamek-devcontainer

![VSCode Remote Container][VSCodeDevContainer-screenshot]


VSCode Devcontainer for the megamek project, follows the wiki guide for getting started found [here](https://github.com/MegaMek/megamek/wiki/Complete-Development-Environment-Setup-using-IntelliJ-Idea#step-5-initialize-git-repositories)

# Prerequisites
You'll need to have [VSCode](https://code.visualstudio.com/)

And have installed the [Remote - Containers extension for VSCode](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers), though VSCode should auto prompt you to install it if nessisary when opening this repo.

# Setup

You'll still need to [clone the repo's](https://github.com/MegaMek/megamek/wiki/Complete-Development-Environment-Setup-using-IntelliJ-Idea#step-5-initialize-git-repositories) inside this folder,

![ClonedRepos][clonedRepos-screenshot]

 And setup your local settings by adding a settings_local.gradle file in each project see [here](https://github.com/MegaMek/megamek/wiki/Complete-Development-Environment-Setup-using-IntelliJ-Idea#step-81-megameklab)

But once done you should have a self contained environment that will compile the megamek suite.  Either run the build tasks, or open a terminal navigate to the project folders and run 

>gradle run --no-daemon

[clonedRepos-screenshot]: images/clonedRepos.png
[VSCodeDevContainer-screenshot]: images/VSCodeDevContainer.png