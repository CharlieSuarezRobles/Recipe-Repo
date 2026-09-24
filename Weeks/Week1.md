# Week 1

## Broad Goal
Our goal for this quarter is to teach you core skills of web development, and to do so, we are going
to make a small website from end to end.

Disclaimer:
The Recipe-Repo website is meant for learning purposes. There might be information about chefs and recipes that might not be the most accurate.

## Why create a website?
- To read or learn something (e.g. News sties)
- To interact with other people (e.g. Reddit, Discord, Instagram)
- To purchase or offer products and services (e.g. Amazon)
- To entertain, listen, or play (e.g. YouTube)

- More generally, a website makes you capable of completing a task or speeding up such

## Goal:
In this week, we will teach you:
1. The basic process web developers follow when planning and building a website.
2. How to get this folder (Recipe-Repo) that lives on the internet into your local computer.

## How to Start a Project

### 1. Identify the Problem and the Users

Before creating a website, you need to determine why it should exist. Start by identifying:

- A problem that has not yet been solved, or a problem that your website could solve better.
- The group of people affected by the problem.

#### In This Project

For this project, we identified that writing and organizing recipes can be tedious for chefs.

> **Note:** Other websites may already address this problem. In a real project, you generally need to solve a new problem or improve upon existing solutions so that people have a reason to use your website.

### 2. Break the Problem into Features

After identifying the main problem, break it into smaller problems. Continue breaking them down until each problem is small enough to become a feature of the website.


#### In This Project

Our main problem is that writing and organizing recipes is tedious. We can break this problem down as follows:

#### Feature 1: Create Recipes

**Problem:** Chefs may need to write recipes in a notebook using a pencil or pen. Because handwriting can take a long time, recording recipes can be tedious.

**Solution:** Create a place where chefs can type, save new recipes, and see all their saved recipes.

#### Feature 2: Search for Recipes

**Problem:** Chefs may need to prepare many different meals quickly. Finding a particular recipe in a notebook can be tedious because they may need to search through many pages.

**Solution:** Allow chefs to quickly search through their saved recipes.

#### Feature 3: Edit Recipes

**Problem:** If a recipe changes, a chef must erase and rewrite part of it. This may be impossible if the recipe was written in pen. There may also not be enough space to add new information.

**Solution:** Allow chefs to edit their saved recipes.

#### Feature 4: Share Recipes

**Problem:** Sharing a handwritten recipe with someone far away can be inconvenient. The chef may need to mail the notebook or type the entire recipe into a message.

**Solution:** Allow chefs to share recipes with other people through the website.

#### Feature 5: Adjust Recipe Quantities

**Problem:** If a chef wants to prepare a different amount of food, they must recalculate every ingredient quantity manually.

**Solution:** Allow chefs to adjust the number of servings and automatically recalculate the ingredient quantities.

### 3. Prioritize the Features

After identifying the features, decide the order in which they should be developed.

#### In This Project

We will begin with **Feature 1: Create Recipes**. The other features require recipes to already exist, so users must be able to create and save recipes first.

Next week, we will decide:

- What information the website needs to store for each recipe.
- What pages the website needs for this feature.

## Setup:
The goal for us now is to get the **Recipe-Repo** from the internet to your local computer. To do so, you will need to do the following:

### Creating a new Github acccount

You will need to create a new Github account. Github is a special kind of application called Version Control that lets multiple people work together on a project that lives on the cloud and manage different versions of that project simultaneously. If you have an account, feel free to skip the steps below, otherwise:

1. Open your browser and go to [github.com](https://github.com/). You should see a page similar to the image below.

   Click **Sign up** and follow the instructions to create a new GitHub account.

   ![alt text](<Week 1 Github 1.png>)

2. Once clicking on sign up, you will see a webpage like the one below. Fill up the information to create your new account. Once you do so, a code will be sent to your email which you will have to put on the Github website.

   ![alt text](<Week 1 Github 2.png>)

3. After, you will have to sign in to Github with the email and password that you set. The webpage will look like the image below.

   ![alt text](<Week 1 Github 3.png>)

4. Once you've signed in, your screen will look like as follows:

   ![alt text](<Week 1 Github 4.png>)

### Installing VS Code

VS Code is an application that puts several things needed for the coding process together to help you make code more easily. If you have VS Code installed, feel free to skip this section, otherwise, you will need to follow the next steps:

1. Go to [code.visualstudio.com](https://code.visualstudio.com/). The page should look similar to the image below.

   Depending on your operating system, you will see either **Download for Windows** or **Download for macOS**. Click the appropriate button to begin downloading VS Code.

   Save the installer wherever you prefer. If you are unsure, save it in your `Downloads` folder.

   ![alt text](<Week 1 VS Code 1.png>)

2. Double click on the VS Code application that you downloaded and you will see the following popup appear. Click on **I accept the agreement**.

   ![alt text](<Week 1 VS Code 2.png>)

3. From there and on, you will keep clicking on **next** until you see the following popup. In such popup, ensure that **Add to PATH** is selected. Then, keep clicking on next and finally click on **install** and once its done, you click on **finish** and you will see that VS Code will open immediately and it will have a popup which looks like the image below. For now, you can click **Continue without signing in**.

   ![alt text](<Week 1 VS Code 3.png>)

   ![alt text](<Week 1 VS Code 4.png>)

4. You will see the VS Code application which will look like the on the image below. 

   ![alt text](<Week 1 VS Code 5.png>)

### Setting up Copilot

Copilot is a tool that helps you write code using AI. It immensely speeds up the process of writing code. If you don't already have it, follow the next steps to get it.

1. To get copilot, click on the symbol which is marked on red as you can see on the image below, and then click on **Sign in to use Github Copilot**.

   ![alt text](<Week 1 Copilot 1.png>)

   ![alt text](<Week 1 Copilot 2.png>)

2. After you click such button, you will see a popup appear. Click on **Continue with Github**. You will get sent to a webpage that looks like the image below. Click on **Continue** and in your VS Code you will be logged in as your Github account that you created.

   ![alt text](<Week 1 Copilot 3.png>)

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

1. On the taskbar, look for **PowerShell**, and click on **Run as Adminstrator** as you can see on the image below. A pop up will appear, click on **Yes**.

   ![alt text](<Week 1 WSL 1.png>)

2. You will see a terminal open. In it, enter the following command:

   ```powershell
   wsl --install -d Ubuntu
   ```

   This command installs WSL and Ubuntu, allowing you to run Linux commands on your Windows computer.

3. After the installation has finished, you will need to restart your computer so that the effects of the installation apply.
4. Once your computer has restarted, on the taskbar, type **Ubuntu** which will look like the one on the image below. Open it. Then, Ubuntu will prompt you to create a username and a password. These will be for your Ubuntu operating system.
If for some reason, you don't see the Ubuntu app, you will need to repeat steps 1 through 3 again, but this time you won't need to restart the computer. After doing these steps, the powershell will prompt you to create a new username and password. Fill those out.

   ![alt text](<Week 1 WSL 2.png>)

After these steps, you will have an Ubuntu operating system with WSL installed.

### Installing Git

Git is an application installed on your local computer that keeps track of different versions that a folder (which we call repository) and all of the files inside of it have. It works with Github. Github is an application that store repositories on the cloud whereas git helps you manage these from your local computer. To install git, the steps are:


1. Go to your terminal. If you are using a Windows computer, open Ubuntu. In the terminal, enter the following command:

   ```bash
   git --version
   ```

   If the terminal displays something similar to:

   ```text
   git version x.xx.x
   ```

   Git is already installed, so you can skip the next steps.

   If the terminal displays:

   ```text
   git: command not found
   ```

   continue to step 2.


2. In the terminal, enter the following command and press **Enter**:

   ```bash
   sudo apt update
   ```

   Then, install Git by entering:

   ```bash
   sudo apt install git
   ```

   Finally, verify that Git was installed successfully:

   ```bash
   git --version
   ```

   You should see something similar to:

   ```text
   git version x.xx.x
   ```

3. Connect Git to the GitHub account you created. In the terminal, enter the following command, replacing `"Your Name"` with your name:

   ```bash
   git config --global user.name "Your Name"
   ```

   Next, enter the email address associated with your GitHub account:

   ```bash
   git config --global user.email "your-github-email@example.com"
   ```

   Keep the quotation marks, but replace the text inside them with your own information.

   Finally, verify your Git configuration:

   ```bash
   git config --global --list
   ```

   You should see your name and email address in the output.

### Creating a secure connection between Git and Github

As we said, Git is an app that runs on your computer that helps control Github repositories which live in the cloud from your computer. In order for Github to know that the authorized user is the one typing the github commands in your computer, we need a secure connection. To create such secure connection, you will need to create two keys, one public and another one private and you will need to give the public one to github. Below, you can see those steps in more detail:


1. Check whether Ubuntu already has an SSH key. In the terminal, enter:

   ```bash
   ls -al ~/.ssh
   ```

   If the terminal displays something similar to:

   ```text
   No such file or directory
   ```

   you do not have an `.ssh` folder yet, so continue to the next step.


2. Create a new SSH key pair using the email address associated with your GitHub account. In the terminal, enter:

   ```bash
   ssh-keygen -t ed25519 -C "your-email@example.com"
   ```

   Replace `"your-email@example.com"` with your GitHub email address, but keep the quotation marks.

   In this command:

   - `ssh-keygen` creates a new SSH key pair.
   - `-t ed25519` specifies the algorithm used to generate the keys.
   - `-C "your-email@example.com"` adds your email as a label that helps you identify the keys.

   This command creates two keys:

   - A **public key**, which you will add to GitHub.
   - A **private key**, which must remain on your computer and should never be shared.

   Together, these keys allow your computer to connect securely to GitHub.


3. After entering such command, it will ask you where to save your new keys, you can just press enter. This tells the computer to just save them in the default location. It will also ask you for a passphrase. You can just press enter so that your keys have no passphrase. Note that you will usually want to have passphrase, but for simplicity purposes we won't have such this time.

4. Copy your public SSH key to the Windows clipboard so that you can add it to GitHub. In the Ubuntu terminal, enter:

   ```bash
   clip.exe < ~/.ssh/id_ed25519.pub
   ```

   This command reads the contents of your public key file, `~/.ssh/id_ed25519.pub`, and copies them to your clipboard.

   > **Important:** Copy only the public key. Never copy or share the private key stored in `~/.ssh/id_ed25519`.

5. Add the public SSH key to your GitHub account:

   1. Open [GitHub](https://github.com/).

   2. Click your profile picture in the upper-right corner, as shown in the images below.

   3. Select **Settings**.

   4. In the menu on the left, select **SSH and GPG keys**.

   5. Click **New SSH key**.

   6. Complete the form:

      - **Title:** Enter any name that will help you identify the computer, such as `Personal Windows Laptop`.
      - **Key type:** Leave this set to **Authentication Key**.
      - **Key:** Paste the public key that you copied earlier.

      If the key is no longer in your clipboard, return to the Ubuntu terminal and run:

      ```bash
      clip.exe < ~/.ssh/id_ed25519.pub
      ```

   7. Click **Add SSH key**.

   8. If GitHub asks you to confirm your identity, enter your GitHub password or complete the requested verification.

   Your public SSH key should now be connected to your GitHub account.

   ![alt text](<Week 1 Creating a Secure Connection 1.png>)

   ![alt text](<Week 1 Creating a Secure Connection 2.png>)

   ![alt text](<Week 1 Creating a Secure Connection 3.png>)

   ![alt text](<Week 1 Creating a Secure Connection 4.png>)

6. Test your SSH connection to GitHub. In the Ubuntu terminal, enter:

   ```bash
   ssh -T git@github.com
   ```

   The first time you connect, you may see a message similar to:

   ```text
   Are you sure you want to continue connecting (yes/no/[fingerprint])?
   ```

   Type:

   ```text
   yes
   ```

   If the connection is successful, you should see a message similar to:

   ```text
   Hi username! You've successfully authenticated, but GitHub does not provide shell access.
   ```

   This message confirms that your SSH key is working and that Ubuntu can connect securely to your GitHub account.

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


### Clone the Recipe-Repo repository

1. Open the GitHub repository page shown in the image below, and click **Code**. Select the **SSH** tab, and then click the copy icon to copy the repository's SSH URL to your clipboard.

   ![alt text](<Week 1 cloning 1.png>)

   ![alt text](<Week 1 cloning 2.png>)

2. Open the Ubuntu terminal and enter the following command, replacing `[URL]` with the SSH URL you copied from GitHub:

   ```bash
   git clone [URL]
   ```

   For example:

   ```bash
   git clone git@github.com:organization/Recipe-Repo.git
   ```

3. To view the files and directories in your current location, enter:

   ```bash
   ls
   ```

   You should now see a directory named `Recipe-Repo`. This is the repository that you cloned from GitHub.

4. Navigate into the `Recipe-Repo` directory by entering:

   ```bash
   cd Recipe-Repo
   ```

   The `cd` command changes your current directory to the directory specified after it. In this case, it moves you into `Recipe-Repo`.

5. Open the current directory in VS Code by entering:

   ```bash
   code .
   ```

   The period (`.`) represents the directory you are currently in, so this command opens `Recipe-Repo` in VS Code.

   If you see a warning like the one in the image below, select **Permanently allow host `wsl.localhost`**, and then click **Allow**.

   After this step, you should see the entire `Recipe-Repo` repository in VS Code.

   ![alt text](<Week 1 cloning 3.png>)

### Learning how to user the VS Code terminal

VS Code has a terminal itself. If you click on terminal, as you see on the image below, you will see a huge square popup as you can see on two images below. This is your VS Code terminal. In it, you can also type commands.

   ![alt text](<Week 1 terminal 1.png>)

   ![alt text](<Week 1 terminal 2.png>)

For windows users, if you are using this terminal for the first time, it will live in Windows which we don't want, so you will need to do the following extra steps:

1. Click on extensions as the image below shows

   ![alt text](<Week 1 terminal 3.png>)

2. Search for WSL, the one on the image below and click on **install**

   ![alt text](<Week 1 terminal 4.png>)

3. After, click on **Open the menu** and on **Connect to WSL**. After doing this, you should see a WSL Ubuntu blue square appear on the bottom left corner

   ![alt text](<Week 1 terminal 5.png>)

   ![alt text](<Week 1 terminal 6.png>)


4. Close VS Code and open the Ubuntu terminal. Navigate to the `Recipe-Repo` directory, and then enter:

   ```bash
   code .
   ```

   This command opens the `Recipe-Repo` directory in VS Code.

   Once VS Code opens, open its integrated terminal. You should see green and blue text similar to the image below. This indicates that the terminal is running in Ubuntu through WSL rather than directly in Windows.

   ![alt text](<Week 1 terminal 7.png>)

### Setting up the Repository

Whenever you are working on a new application, you will always need to run through a set of steps specific to that application to work on it locally. To do so, you will usually have to read the README.md file that appears inside the outermost folder. So, go to such file and do the setup for this project. Note that when the README.md asks you to type in commands, you will have to type them inside of the VS Code terminal.