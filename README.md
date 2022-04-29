# testRepo_1
To test out github push pull

## **Problem arose when we were starting UiPath and Github lessons.**

On the repository creation page. There was an option to create a readme file.
And upon uploading from UiPath, the rest went into a seperate branch?

_Still new to github and branches etc, not even sure how to choose stuff_

As the tutor demostrated cloning, some students were having issues with the cloning. UiPath would throw an error.
The folder from explorer would only show the readme file.

## Research on push pulls from github
"You can choose the default branch for a repository. The default branch is the base branch for pull requests and code commits."

https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-branches-in-your-repository/changing-the-default-branch
I think uipath downloads from the 'main', not master

![[UiPath, Github Clone from default branch.png]]


## Solution
**Github repo. Settings>Branches>Set the default to the one that you require.**
Where the project.json and xaml files are at.

Then UiPath would be able to clone it.


# further things to research
I am not sure, but might be possible to change branches etc thereafter.
I need to figure out what branches are.

There looks to be an icon on branches on the UiPath Studio interface at the bottom when it is connected.
As of 20220429. There doesn't seem to be an option in the UiPath Studio to just connect to a repository. Just Clone, Copy to Git, Git init, Disconnect, Change signature.
