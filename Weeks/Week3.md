# Week 3:

## Goal:
In this week, we will start implementing the feature. For now, we will teach you:
- What the frontend and the backend are
- How to set up the frontend of a new project

### Introduction to frontend and backend

So far, our goal is to have feature 1 be on a website. In other words, we want people to be able to access it through the internet whenever they want to. To build that website, we will write code in a project folder. In our case, that code will make feature 1 possible.

Now, if you pay attention, whenever your computer is offline, it usually can’t load a website. That suggests that the website’s files are coming from somewhere else. And yes, they are usually provided by a remote computer. When you open a website, your **browser** requests a webpage from that computer. The browser receives files such as HTML, CSS, and JavaScript, displays the page, and runs the JavaScript needed for its interactions.

The remote computer needs to be available to respond when someone requests the website. We call a computer or program that provides something to other computers a **server**.

Another problem we have is that feature 1 requires our website to store recipes. If a user saves a recipe, we want it to still be there when they return and, depending on the feature, to be available from another computer. We therefore need a place to store recipes, such as a **database**, and code that handles requests to save and retrieve them.

We could put the code that sends webpages and the code that handles recipes on the same server. For this project, though, we will use two separate parts. One serves the files the browser needs to display the website. The other runs code that handles recipe requests and communicates with the database.

So, let’s say the user clicks **Save recipe**. JavaScript running in the browser sends the recipe to the second server. That server runs code to check the recipe and save it in the database. It then sends a response to the browser, which can show the user whether the recipe was saved successfully.

With this setup, we can make feature 1 possible. We can call the server that provides the website’s files the **frontend server**, and the server that handles recipe requests the **backend server**. The code that creates the interface and handles interactions in the browser is called the **frontend**. The code that handles the recipe requests on the second server is called the **backend**.

So far, we have thought of our project as one folder containing all its code. However, these two parts have different jobs, so we will organize the project into a **`frontend/`** folder and a **`backend/`** folder. The `frontend/` folder contains the code and tools for building the interface; the `backend/` folder contains the code for handling requests and working with the database.


### Creating and Opening the Project Directory

1. Open the appropriate terminal:

   - If you are using Windows, open the Ubuntu terminal.
   - If you are using macOS, open Terminal.

2. Create a directory for the project:

   ```bash
   mkdir Dummy-Repo
   ```

   The `mkdir` command creates a new directory.

3. Navigate into the new directory:

   ```bash
   cd Dummy-Repo
   ```

   The `cd` command changes your current directory to the directory specified after it.

4. Open the directory in VS Code:

   ```bash
   code .
   ```

   The period (`.`) represents the directory you are currently in, so this command opens `Dummy-Repo` in VS Code.

5. In VS Code, select **Terminal → New Terminal**.

   The terminal should open inside the `Dummy-Repo` directory. Use this VS Code terminal for the remaining commands.

### Setting Up the Frontend

The frontend will use:

- **React** to create the user interface.
- **Vite** to run and build the frontend.
- **TypeScript** as the programming language.
- **React Router** to create and navigate between multiple pages.
- **ESLint** to identify possible problems in the code.

1. In the VS Code terminal, verify that Node.js and npm are installed:

   ```bash
   node --version
   npm --version
   ```

   Both commands should display version numbers.

2. Create the frontend application:

   ```bash
   npm create vite@latest frontend
   ```

3. Vite will ask which framework you want to use. Select:

   ```text
   React
   ```

4. Vite will ask which variant you want to use. Select:

   ```text
   TypeScript
   ```

5. Vite will ask which linter you want to use. Select:

   ```text
   ESLint
   ```

6. Vite will then ask whether it should install the dependencies and start the application:

   ```text
   Install with npm and start now?
   ```

   Select:

   ```text
   Yes
   ```

   Vite will install the frontend dependencies and start the development server.

7. When the development server starts, the terminal should display a local address similar to:

   ```text
   http://localhost:5173
   ```

   Open this address in your browser. You should see the default Vite and React webpage.

8. Return to the VS Code terminal and press:

   ```text
   Ctrl+C
   ```

   This stops the development server.

9. Navigate into the frontend directory if the terminal is not already inside it:

    ```bash
    cd frontend
    ```

10. Install React Router:

    ```bash
    npm install react-router-dom
    ```

    React Router allows the application to display different pages for URLs such as `/`, `/recipes`, and `/recipes/create`.

11. Start the frontend again:

    ```bash
    npm run dev
    ```

After completing these steps, the project should have the following basic structure:

```text
Dummy-Repo/
└── frontend/
    ├── node_modules/
    ├── public/
    ├── src/
    ├── .gitignore
    ├── eslint.config.js
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── README.md
    ├── tsconfig.app.json
    ├── tsconfig.json
    ├── tsconfig.node.json
    └── vite.config.ts
```

