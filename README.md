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
After it is saved, you should see that a file with the name of the repo has been downloaded

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
e.g.
```
git checkout -b add-my-name
```

## Add and commit changes



