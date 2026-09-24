# Week 2

## Goal
In this week, we will teach you:
1. How to design a feature
2. Set up figma

## Designing a feature

In our example, we will design feature 1 from last week. To do so, we will follow the next steps:

### 1. Define the user's goal

This is what the feature is supposed to achieve.

Example:
Feature 1 is supposed to be a place in which chefs can type, save, and see all the recipes they've saved.

### 2. Determine the information that needs to permanently be stored

For feature 1, we need to store the following:

- Recipe name
- Recipe picture
- Description
- Preparation time
- Ingredients
- Instructions

### 3. Describe the user flow

We describe the set of actions the user needs to take to solve the problem the feature addresses along with the effect that each of the actions will have on the website:


1. **User action:** The chef opens the **Recipes** page.

   **Website response:** The website displays all saved recipes.

2. **User action:** The chef clicks **Create New Recipe**.

   **Website response:** The website opens the **Create Recipe** page.

3. **User action:** The chef enters the recipe information.

   **Website response:** The website displays the entered information in the form.

4. **User action:** The chef clicks **Save Recipe**.

   **Website response:**

   - The website saves the recipe.
   - The website shows it has saved it.
   - The website opens the **Recipes** page.
   - The saved recipe appears on the page.

### 4. Find edge cases and see how you could handle them

These are cases that are not part of the normal flow or in other words, cases that can break things. To find such, you need to look at each of the steps in the user flow that you defined and think about the assumptions that you made about each step.

In our example, by saying the chef enters the recipe information, we are assuming they do it correctly, what if they missed the recipe name, the description, or any other field? Also, when we say the chef clicks on **Save Recipe**, we are assuming nothing bad is going to happen, what if for some reason they accidentally exit the website, they will accidentally lose the entire recipe they've written. Using this thought process, we find edge cases.

While finding each, we need to decide how to handle them. If let's say the chef misses the recipe name, we should tell the chef **You have fields missing** or **Please fill out the recipe name field**.

For feature 1, the edge cases and how we address them are:

- Edge case: The chef fills out the recipe with one or more fields missing
- Solution: Tell the chef **You have the <field> field missing**

- Edge case: The chef accidentally exits the save-recipe page before they save it
- Solution: Have a pop up appear that tells the chef **You haven't saved the recipe. Are you sure you want to exit** and then have the chef confirm.

- Edge case: The chef clicks on **save** but the website fails to save the recipe.
- Solution: Tell the chef **Failed to save recipe** and maybe tell them why such thing happened

### 5. Define completion criteria

To define such, we combine all the steps we defined in the user flow with all the edge cases along with their solutions. This is because if the developers have coded a feature that can do all of this, then it can do everything that we expect it to do.

So, the completion criteria is:

1. **User action:** The chef opens the **Recipes** page.

   **Website response:** The website displays all saved recipes.

2. **User action:** The chef clicks **Create New Recipe**.

   **Website response:** The website opens the **Create Recipe** page.

3. **User action:** The chef enters the recipe information.

   **Website response:** The website displays the entered information in the form.

4. **User action:** The chef clicks **Save Recipe**.

   **Website response:**

   - The website saves the recipe.
   - The website shows it has saved it.
   - The website opens the **Recipes** page.
   - The saved recipe appears on the page.

- Edge case: The chef fills out the recipe with one or more fields missing
- Solution: Tell the chef **You have the <field> field missing**

- Edge case: The chef accidentally exits the save-recipe page before they save it
- Solution: Have a pop up appear that tells the chef **You haven't saved the recipe. Are you sure you want to exit** and then have the chef confirm.

- Edge case: The chef clicks on **save** but the website fails to save the recipe.
- Solution: Tell the chef **Failed to save recipe** and maybe tell them why such thing happened

### 6. Design the interface

This is the step in which we design how everything within the feature is going to look like. These are the buttons, images, webpages, and other visual stuff. There are apps that help us design stuff quickly. The one we use in TSE is called **Figma**. 

There are many considerations one needs to take when designing a feature and even the entire app for the first time. These considerations depend on what your website can do. Some are thinking what the primary and secondary colors of the website are going to be, taking into consideration color-blinded people, the people who can't read small letters, people whom might not see your website the same as others, people who are deaf, people who only read other languages, among other concepts. Note that designers are the ones who take care of these. One as a developer doesn't need to pay attention to all of these design decisions, but when one notices something off, it's recommended to tell such thing to the designers as they might have missed something.

You can see the design for Feature 1 in the following [Figma design](https://www.figma.com/design/8hsncacL9ABEkdrO0P9CIE/Untitled?node-id=0-1&p=f&t=x33SJU8SsGr6l9c8-0).

### Next steps

You would keep going through all these steps to design each feature. Generally, the designers and the PM are the ones that do these. After a few features have been thought out, it will be time for the developers to start implementing them one by one or even several at the same time, from the ones that have the most priority to the ones that have the least. We don't want to implement all at the same time because 1, we never know all the features our website would need and 2, it's better to have a feature done than having several half way. So, using this approach and to keep things simple, we will talk about how to implement feature 1 next week.

## Setting up Figma

Now, it's time to get Figma. This is the app that designers use to make the UI for every feature and the one that developers use to know how the designers want the feature to look like. To install it, do the following steps:

### Creating a Figma Account

1. Open your browser and go to [figma.com](https://www.figma.com/).

2. Click **Get started**.

3. Create an account using your email address, Google account, or another available sign-in option.

4. Follow the instructions displayed by Figma to finish setting up your account.

### Getting the Figma Education Plan

Figma offers eligible college students free access to the Figma Education plan. This plan includes Professional features such as Dev Mode.

1. Go to the [Figma for Education](https://www.figma.com/education/) webpage.

2. Click **Get verified**.

3. Sign in to Figma. If you do not have an account, create one using your `@ucsd.edu` email address.

4. Enter the requested information about yourself and your school.

5. If Figma asks you to verify your student status, follow the instructions provided. You may need to verify your UCSD email address or submit proof that you are currently a student.

6. Submit your application and wait for Figma to review it.

7. After your application is approved, sign in to Figma and confirm that your account has access to the Education plan.

> **Note:** Approval may not be immediate. You can continue using Figma's free Starter plan while waiting for your student status to be verified.