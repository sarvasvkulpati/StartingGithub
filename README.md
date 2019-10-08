# StartingGithub

## Steps
1. **Fork the repo**
2. **Clone your repo**
3. **Create a new branch**
4. **Add and Commit changes**
5. **Push Changes**
6. **Submit Pull Request**

## Fork the repo
The first thing you need to do is create a copy of the repository under your personal account. Doing this is called **"forking"** the repository. 

![Fork the repo](https://media.giphy.com/media/7YDbvYHi47c6TbdKih/giphy.gif)


## Clone your repo
Once you have a copy of the repository under your personal account, you need to download the repository to your computer so that you can add changes. We call this **"cloning"** the repository.

We do this in two steps:

1. First copy the link of the repo from the big green button saying "clone or download" in the top right corner like below

![Get the repo clone link](https://media.giphy.com/media/1zKRICRW93OdgYCUuR/giphy.gif)


2. In your terminal, type in the following line in a directory you want your repo saved

```
git clone <link you copied>
```
After it is saved, you should see that a file with the name of the repo has been downloaded.
If you want to follow along with this tutorial, type the following line into the terminal.

```
git clone https://github.com/sarvasvkulpati/StartingGithub.git
```

## Create a new branch
When we add new features, we add them on a different **branch**. A branch allows you to experiment with changes to your repository without messing up your code. It does this by creating a copy of your code that you can add changes to.

1. First, enter your repositories folder from the command line

```
cd StartingGithub
```

2. Next, we create a branch

```
git checkout -b <branch name here>
```
Since you'll be adding your name, it would be a good idea to name your branch something descriptive, like "add-my-name"
```
git checkout -b add-my-name
```

## Add and commit changes
Next, open the file you need to make changes to, and add your edits. If you're following along with this repo, open Contributors.md and add your name to the file. 

After making your contributions, tyep the following command into your terminal
```
git status
```
You should see something like this
![git status](https://github.com/sarvasvkulpati/StartingGithub/blob/master/status.png)

Now, we need to tell git that we want this file saved. To do this, we type the following command
```
git add Contributors.md
```
If you edit multiple files, you can also use the -A flag, which adds all files:
```
git add -A
```
Finally, we save the file. Saving the file to your local repository is called **commiting** your changes. When we commit changes, we usually also add a message, denoted by the -m flag, to explain what we changed.
```
git commit -m "added my name"
```
## Push changes

Finally, you need to save your local changes to github's servers. Doing so is called **pushing** your code to a **remote**, in this case, the remote is Github.
When you clone a repository from Github, your downloaded repo comes with the remotes pre-installed. You can check this by typing:
```
git remote -v
```
you'll see something like this
![git status](https://github.com/sarvasvkulpati/StartingGithub/blob/master/remote.png)

To push your code, type in the following 
```
git push origin <branch-name>
```
If you're following the tutorial, this branch name would be add-my-name

## Submit a pull request
As a last step, we need to add the changes from your copy of the repo to the main copy of the repo. To do this, you need to submit a request to the owner of the main repo, so they can check whether your changes are appropriate after which they can **pull** your changes into the main repo. This request is called a **pull request**

After pushing your changes to your personal repo, you should see a green button that appears above saying "compare and pull request. After clicking that, you can add a message, and then click create pull request.

![pull request](https://media.giphy.com/media/4H1uNfgYevSSBSSRhB/giphy.gif)
