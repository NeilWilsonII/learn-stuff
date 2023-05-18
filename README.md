# learn-stuff
Github is a useful tool for version controlling your code. It ensures that code changes are captured over time, and that applications can be rolled back to previous versions.

A project in github is referred to as a repository or repo. Repos can be cloned from Github to your local computer where you can add/modify/delete code.

Downloading code from Github to your personal machine is referred to as "cloning". This is accomplished with the ```git clone``` command.

To authenticate to Github and clone a repo, it is typically recommended to set up an SSH Keypair. This stores a private key on your machine which is used to authenticate to Github. To complete these steps, follow this guide: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent.

Once your SSH Key is setup. Clone this repository by clicking the "Code" button, selecting "SSH", and then using the copy url button. 
![image](https://github.com/NeilWilsonII/learn-stuff/assets/37984321/fa4b2fd7-cf9f-4fba-abbd-573dc4136cc4)

Navigate to your terminal and clone the repo:
``` git clone git@github.com:NeilWilsonII/learn-stuff.git ```

Now in your IDE (I recommend VS Code), you can open the learn-stuff repo.

In the bottom right of VS Code, you can open a new terminal. If you click the "+" dropdown, and select Gitbash, your terminal will open a Gitbash window where you can see both your project AND which branch you are on!

![image](https://github.com/NeilWilsonII/learn-stuff/assets/37984321/5be64b2b-12f1-4917-bf02-0eeb0ce9fc48)

In the above photo, you can see that your clone of the project learn-stuff is on the branch "Main". Main is typically the most important branch in a repository. It's the "main" source of truth and is typically the branch that gets deployed to production.

Why use branches?

Branches are used so that units of work can be broken off into small chunks and worked on by multiple developers at the same time! A branch is just a copy of the repository code. You can create a new branch in the Github UI or in your terminal.

After cloning this repository to your local machine, check out your own branch, replacing my name with yours:
```git checkout -b neil-new-branch```

You can now see, I'm on my own branch. I can now make changes to the code without affecting the main branch!
![image](https://github.com/NeilWilsonII/learn-stuff/assets/37984321/a6484f0e-cb97-43e4-ade7-a98cc953d367)

## Make
