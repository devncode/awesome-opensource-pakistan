# Contribution Guidelines

Hi. 👋

We can make possible this project to be the platform where developers can find opensource projects build in Pakistan and can contribution to them, thanks to kind volunteers like you. We are grateful for your contributions and are excited to welcome you aboard.

Happy contributing.

### Implementing feature

We have listed couple issues with `enhancement` tag so you can easily find and start working.

Make sure to check the description of feature, ask any questions using comments and request for assigning you if you find yourself confident in building the feature.

Please use this template for naming while creating branch .

`feature_{issue#}_{short_info}`

### Suggest feature

You are more than welcome to suggest us for improvment of this project, just simple goto issues and create new issue also make sure to tag it as `enhancement` and we will start with discussing using comment box.

### Find a Bug

Have you find some bug during testing or contributing then please report us using creating new issue and tagging it as `bug` and we will get back to you as soon as possible.

### Fix a Bug

oh! great, just pick a issue, make sure you understand it otherwise ask question using comment box and request to assigne you.

Please use this template for naming while creating branch.

`bug_{issue#}_{short_info}`

## General instruction!

<img align="right" width="300" src="images/fork.png" alt="fork this repository" />

If you don't have git installed in your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="images/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the clone button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

<br/>
<br/>

<img align="right" width="300" src="images/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/this-is-you/awesome-opensource-pakistan.git
```

where `this-is-you` is your GitHub username. Here you're copying the contents of the first-contributions repository in GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd awesome-opensource-pakistan
```

Now create a branch using the `git checkout` command:

```
git checkout -b <add-your-new-branch-name>
```

For example:

```
git checkout -b feature_22_header_page
or
git checkout -b bug_15_missing_image
```

## Make necessary changes and commit those changes

<img align="right" width="450" src="images/git-status.png" alt="git status" />

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add .
```

Now commit those changes using the `git commit` command:

```
git commit -m "fixed#{issue#} <your-message>"
```

replace {issue#} with the issue number you are working.

replace `<your-message>` with description of what you have changed.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replace `<add-your-branch-name>` with the name of the branch you created earlier.

## Submit your changes for review

Now if you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="images/compare-and-pull.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="images/submit-pull-request.png" alt="submit pull request" />

Soon, I'll be merging all your pull requests into the master branch of this project. You will get a notification email once the changes have been merged.
