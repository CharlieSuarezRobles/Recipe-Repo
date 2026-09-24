# Week 3

## Goal
In this week, we will start implementing the feature. For now, we will teach you:
- A basic definition of the frontend
- How to set up the frontend of a new project
- The basic structure of the frontend

### Introduction to the frontend

The **frontend** is the part of our website that creates what chefs see and interact with, such as the recipe form and its buttons. We’ll use several tools to build it:

- **TypeScript** is a programming language. We’ll use it to write code that controls what happens when a chef interacts with the page. It builds on JavaScript and helps catch some mistakes while we code.
- **React** is a JavaScript library. A *library* is code written by other developers that we can use in our own project. React helps us build the interface out of pieces called **components**, such as a recipe form or recipe card.
- **CSS** is a styling language. It controls how the interface looks, including colors, spacing, and layout.
- **Vite** is a tool that lets us run the frontend on our computer while we build it. It gives us a link we can open in a browser to see the website, and the page updates when we change our code.

We’ll learn how to use each of these as we build the recipe website.

### Why are we creating a new project?

In Week 1, you cloned `Recipe-Repo` and saw that it already contained many files. You might be wondering where those files came from. To find out, we’ll start with an empty folder called `Dummy-Repo` and use a few commands to create a frontend inside it. You’ll see which files the initial setup creates for us.

`Dummy-Repo` is a separate practice project, so we won’t be changing `Recipe-Repo` in this exercise. The steps you learn here will also help you start a new project of your own later.

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

### The basic structure of the frontend

When you run the frontend locally and open its link in a browser, these are the main files involved:

1. **`package.json`** contains the `dev` command. When you type `npm run dev`, npm finds that command and starts Vite.
2. **`index.html`** is the webpage Vite sends to the browser. It contains a place for React to display the interface and points to `src/main.tsx`.
3. **`src/main.tsx`** starts React and tells it to display the `App` component.
4. **`src/App.tsx`** defines the main interface you see in the browser. This is one of the files we’ll edit when we start building our recipe website.
5. **`src/index.css`** and **`src/App.css`** control how the page looks. The TypeScript files import these CSS files so their styles are applied.

This is a useful path to follow when exploring the project, but the files are not all “executed” one after another. For example, CSS provides styling; it does not run like TypeScript code.

You’ll also see other folders and files. **`node_modules/`** contains packages installed with npm, while **`public/`** and **`src/assets/`** can hold images and other assets. Files such as `vite.config.ts`, `eslint.config.js`, and the `tsconfig` files configure the tools we use to develop the frontend. You do not need to understand every one of them before making your first change.

