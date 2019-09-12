## **If you created the repo on your computer first, and then made a repo online on GitHub:**

You will need to initialize directory as repo and [link to existing repo you created on GitHub](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)

Process:

Make sure you are in your repo via the `pwd` terminal command

```
git init 
git add -A
git commit -m "first commit"
git remote add origin https://github.com/__username__/__repo__.git
git push -u origin master
```

## **If you made the repo online on GitHub first, and have not yet made a local repo:**

**_This method will not work if you are using a framework such as React or Laravel_** Otherwise, you have an easy task

Navigate to your "Sites" folder via `cd` and confirm you are in the right location via `pwd`

`git clone https://github.com/__username__/__repo__.git`
