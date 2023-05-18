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
