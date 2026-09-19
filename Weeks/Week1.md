# Week 1

## Broad Goal:
Our goal for this quarter is to teach you core skills of web development, and to do so, we are going
to make a small website from end to end.

## Why create a website?
- To read or learn something (e.g. News sties)
- To interact with other people (e.g. Reddit, Discord, Instagram)
- To purchase or offer products and services (e.g. Amazon)
- To entertain, listen, or play (e.g. YouTube)

- More generally, a website makes you capable of completing a task or speeding up such

## Goal:
In this week, we will teach you:
1. How to get this folder (Recipe-Repo) that lives in the cloud into your local computer.
2. The basic process web developers follow when planning and building a website.


## How to start a project:
The first thing you need to decide is why you need a website in the first place. To do that, you first need to find either a problem that has been solved or a problem whose solution already exists and that your website will improve. You also need to find the kind of people that are impacted by the problem.

- In the case of Triton Software Engineering, we have our VP Products person look for new clients. After, these clients come and initially talk to some of our PVP (President Vicepresident) members to identify the problems they have.

- In the case of this project, I've found that writing and organizing recipes can be quite tedious for chefs.
Side note: In our case, I'm pretty sure this problem has been solved before, but generally, you would need to find a new problem or solve it better than other existing websites so that you actual have users going to your website.



After solving knowing the problem, you would need to break it down into subproblems over and over again until we get a problem that is small enough that we can make it a feature. 

- In the case of Triton Software Engineering, each client has one of our PMs ask them about their problem and breaking it down into small pieces until they become features.

- In the case of this project, our problem is the fact that writing and organizing recipes is tedious. So, we think why such is the case. Below are some reasons why:

1. Chefs need to write the recipes in a notebook with pencil a paper. Because handwriting takes long, writing a recipe is tedious. 
Solution:
Have a place in which the chef can create and type a new recipe.

2. Chefs need to cook lots of different meals quickly that they need to quickly find recipes. It is currently tedious to do so because in a notebook they need to turn several pages until they find the specific recipe.
Solution:
We want the chef to have the ability to quickly search through recipes.

3. If a recipe has changed, the chef needs to get their eraser and erase some letters. If they wrote the recipe with a pen, this is impossible to do. Furthermore, if the new stuff they write is a lot, they won't have enough space to finish writing the recipe.
Solution:
Have a place in which the chef can edit a recipe.

4. Sharing recipes is incovenient. If a chef wants to share one recipe with another one that lives across the globe, they will either have to either send the book through mail, or send a very long message through a social media app which will still take long.
Solution:
Let the chef be able to share a recipe.

5. If a chef wants to make 50% more, double, or some different quantity of food that the recipe mentions, the chef needs to recalculate every quantity the recipe mentions.
Solution:
Let the chef quickly change the recipe.



After having our features, we decide in which order we should execute each of our features. 

-In TSE, the PM decides the ordering by thinking about the importance of each feature.

-For our project, we will decide to do feature 1 first because if the chef can't write a recipe in the website, they can't do any stuff with it that all the other features demand. We will decide what things the website will need to store and what webpages the website will need to have for this feature next week.

## Setup:
The goal for us now is to get the `Recipe-Repo` from the cloud to your local computer. To do so, you will need to do the following:

### Creating a new Github acccount

You will need to create a new Github account. Github is a special kind of application called Version Control that lets multiple people work together on a project that lives on the cloud and manage different versions of that project simultaneously. If you have an account, feel free to skip the steps below, otherwise:

1. Open your browser and go to `https://github.com/`, you will something like the image below. Select sign up and create your new Github account
(Week 1 Github 1)

2. Once clicking on sign up, you will see a webpage like the one below. Fill up the information to create your new account. Once you do so, a code will be sent to your email which you will have to put on the Github website.
(Week 1 Github 2)

3. After, you will have to sign in to Github with the email and password that you set. The webpage will look like the image below.
(Week 1 Github 3)

4. Once you've signed in, your screen will look like as follows:
(Week 1 Github 4)

### Installing VS Code

VS Code is an application that puts several things needed for the coding process together to help you make code more easily. If you have VS Code installed, feel free to skip this section, otherwise, you will need to follow the next steps:

1. Go to `code.visualstudio.com`and your screen will look like the image below. You will see `Download for Windows` or `Download for MacOs` depending on your operating system. Click such button to begin downloading VS Code and save the application that you are downloading wherever you want, or if you are undecided, under `downloads`.
(Week 1 VS Code 1)

2. Double click on the VS Code application that you downloaded and you will see the following popup appear. Click on `I accept the agreement`.
(Week 1 VS Code 2)

3. From there and on, you will keep clicking on `next` until you see the following popup. In such popup, ensure that `Add to PATH` is selected. Then, keep clicking on next and finally click on `install` and once its done, you click on `finish` and you will see that VS Code will open immediately and it will have a popup which looks like the image below. For now, you can click `Continue without signing in`.
(Week 1 VS Code 3)
(Week 1 VS Code 4)

4. You will see the VS Code application which will look like the on the image below. 
(Week 1 VS Code 5)

### Setting up Copilot

Copilot is a tool that helps you write code using AI. It immensely speeds up the process of writing code. If you don't already have it, follow the next steps to get it.

4. To get copilot, click on the symbol which is marked on red as you can see on the image below, and then click on `Sign in to use Github Copilot`.
(Week 1 Copilot 1)
(Week 1 Copilot 2)
5. After you click such button, you will see a popup appear. Click on `Continue with Github`. You will get sent to a webpage that looks like the image below. Click on `Continue` and in your VS Code you will be logged in as your Github account that you created.
(Week 1 Copilot 3)

### Getting Copilot's Premium features

As a UCSD student, you are eligible to get Copilot's Premium features for free. For that, you can go here and follow the steps.

<details>
<summary><strong>Optional: Get GitHub Copilot Student for free</strong></summary>

GitHub provides eligible students with free access to Copilot’s premium features through GitHub Education.

### 1. Add your UCSD email to GitHub

1. Open GitHub.
2. Go to **Settings → Emails**.
3. Add your `@ucsd.edu` email.
4. Verify it through the message sent to your UCSD inbox.

### 2. Apply for GitHub Education

1. Open the [GitHub Education benefits page](https://github.com/settings/education/benefits).
2. Click **Start an application**.
3. Submit the requested student information.
4. Wait for GitHub’s decision.

### 3. Activate Copilot Student

1. Return to the GitHub Education benefits page after approval.
2. Find the Copilot Student benefit.
3. Click **Learn more**.
4. Follow the activation instructions.

</details>

### Installing WSL (Windows Users Only)

1. On the taskbar, look for `PowerShell`, and click on `Run as Adminstrator` as you can see on the image below. A pop up will appear, click on `Yes`.
(Week 1 WSL 1)
2. You will see a terminal open. On it, type `wsl --install -d Ubuntu`. This command will install WSL which is a terminal that will allow you to type commands used in the operating system called Ubuntu.
3. After the installation has finished, you will need to restart your computer so that the effects of the installation apply.
4. Once your computer has restarted, on the taskbar, type `Ubuntu` which will look like the one on the image below. Open it. Then, Ubuntu will prompt you to create a username and a password. These will be for your Ubuntu operating system.
If for some reason, you don't see the Ubuntu app, you will need to repeat steps 1 through 3 again, but this time you won't need to restart the computer. After doing these steps, the powershell will prompt you to create a new username and password. Fill those out.
(Week 1 WSL 2)

After these steps, you will have an Ubuntu operating system with WSL installed.

### Installing Git

Git is an application installed on your local computer that keeps track of different versions that a folder (which we call repository) and all of the files inside of it have. It works with Github. Github is an application that store repositories on the cloud whereas git helps you manage these from your local computer. To install git, the steps are:

1. Go to your terminal. If you are on a Windows machine, you need to open Ubuntu and in the terminal that will open, you will need to type `git --version`. If the terminal responds with `git version x.xx.x` or something looking like that, that means you already have git, so you can skip the next steps. If it otherwise says, `git: command not found`, then do step 2.
2. ON the terminal, type `sudo apt update`, press enter, and then `sudo apt install git`. Then do `git --version` again and you should have it installed.
3. Connect git to the Github account that you created. To do this, type in the terminal `git config --global user.name "Your name"`, and then type `git config --global user.email "your-github-email@example.com"`. Verify that you did this correctly by typing `git config --global --list` on the terminal. (Note: include the quotes on your command, they are not part of the placeholder)

### Creating a secure connection between Git and Github

As we said, Git is an app that runs on your computer that helps control Github repositories which live in the cloud from your computer. In order for Github to know that the authorized user is the one typing the github commands in your computer, we need a secure connection. To create such secure connection, you will need to create two keys, one public and another one private and you will need to give the public one to github. Below, you can see those steps in more detail:

1. Check if your Ubuntu already has an SSH key. For that, type in the terminal `ls -al ~./ssh`. If you get something that says `No such file or directory`, that means you don't have a key, so you have the do the next steps.
2. Create a new SSH key pair and name it as your email. To do so, in the terminal, type `ssh-keygen -t ed25519 -C "your-email@example.com"`. SSH-keygen creates a new SSH key pair, the `-t ed25519` specifies the kind of algorithm (like a procedure) that is used to generate such key, and `-C "your-email@example.com"` the name that you are giving to your new keys. The two keys created are one public and one private which we need to create the secure connection.
3. After entering such command, it will ask you where to save your new keys, you can just press enter. This tells the computer to just save them in the default location. It will also ask you for a passphrase. You can just press enter so that your keys have no passphrase. Note that you will usually want to have passphrase, but for simplicity purpose we won't have such this time.
4. Then you need to copy the public key into your clipboard so that you can later paste it in Github. To do so, on the terminal, type `clip.exe < ~/.ssh/id_ed25519.pub`. This will read the `~/.ssh/id_ed25519.pub` file and put it into the clipboard.
5. Now, you need to enter it into Github. To do so, open Github you should see what you see on the image below. Then click on your profile picture and then select `settings`. You can see that on the second image below. Then select `SSH and GPG keys` as you can see three images below. Then click on `New SSH key`. Give any title you want to your key, leave the `Key type` option as `Authentication Key` and paste your key under `Key`. If for some reason your clipboard doesn't have the key anymore, type the `clip.exe < ~/.ssh/id_ed25519.pub` command on your terminal again. After filling out those three parts, you need to type on `add key`. Afterwards, Github will ask you for your password again, type it and you will have your public key added to Github.
(Week 1 Creating a Secure Connection 1)
(Week 1 Creating a Secure Connection 2)
(Week 1 Creating a Secure Connection 3)
(Week 1 Creating a Secure Connection 4)
6. Test that Github's public key corresponds to the private key that you created. To do so, type `ssh -T git@github.com` in your terminal. You will see a message that will sort of look like `Are you sure you want to continue connecting`. Select `yes`, and then you will see something like `Hi [username]! You've successfully authenticated...`. This means that you correctly created a secure connection between Git and Github.

### Install Node.js and npm

Node.js allows your computer to execute JavaScript outside a web browser. npm is a command-line application that installs and manages the dependencies used by a JavaScript or TypeScript project.

1. Open the appropriate terminal:

   - If you use Windows, open Ubuntu and install `curl`:

     ```bash
     sudo apt update
     sudo apt install curl
     ```

   - If you use macOS, open Terminal and verify that `curl` is available:

     ```bash
     curl --version
     ```

2. Install `nvm`:

   ```bash
   curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.7/install.sh | bash
   ```

   `nvm` stands for Node Version Manager. It allows you to install and switch between versions of Node.js.

3. Close and reopen the terminal. Then verify that `nvm` was installed:

   ```bash
   command -v nvm
   ```

   It should display:

   ```text
   nvm
   ```

4. Install the long-term-support version of Node.js:

   ```bash
   nvm install --lts
   ```

   Installing Node.js this way also installs npm.

5. Verify that Node.js and npm are installed:

   ```bash
   node --version
   npm --version
   ```

   Both commands should display version numbers.


### Clone the Recipe-Repo repository:




### Clone the Wellness





1. Create a Github account
2. Install VS Code
3. Install WSL with Ubuntu distribution (If using Windows)
4. Open the terminal. In it, you will see a few words that looks like the one on the image below. The words that you see in green on your terminal will be your username. In this terminal, you can type lots of commands that tell the computer what to do. You will type `git clone <url>`. This will get the `Recipe-Repo` folder from the cloud and bring a copy into your computer.
![alt text](image.png)
5. Type `ls` in the terminal. This will tell the computer to display all the names of the files and folders that are inside of the folder (directory) that you are currently on. Among them, you should see one named `Recipe-Repo`.
6. Type `cd Recipe-Repo` in the terminal. This will tell it to go to such folder. After you execute such command, you will see `/Recipe-Repo` appear. This is a path that tells you where among all the folders that your computer has you are in. If you do `cd ..`, you will go out of `Recipe-Repo` back into the parent folder. So, you will see that `/Recipe-Repo` will go away.
![alt text](image-1.png)
7. Once inside `Recipe-Repo`, type `code .`. This tells your computer to open VS Code and in it, open the `Recipe-Repo` folder (which we also call repository in this case).
