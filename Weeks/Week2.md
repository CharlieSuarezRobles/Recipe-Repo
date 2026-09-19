# Week 2:

## Goal:
In this week, we will teach you:
1. How to design a feature in `Figma`
2. How to decide what your website is going to store
3. 

1. We could decide how the UI (User Interface which is what you see on a website) of the feature is going to look like. While doing so, we always need to think about the problem that our feature solves and how the user is going to experience such feature from the moment they start until they finish it.

-In TSE, we have the designers make the features in an app called `Figma` and have the PM check that those align with what the client expects.

-For our project, I've also made designs in `Figma` which you can see on the following link:
()

2. We could decide what things our website will need to store permanently based on all the features we have, meaning that if you go to the website in and out, the thing it stores needs to persist.

-In TSE, the engineering manager of each team tends to do this.

-To figure out what our website will need to store, we will look at each feature.
Looking at feature 1, we need to store recipes because the chef will need to go in and out of the website every day. Each recipe needs to have a name for the dish, an image of the plate, its ingredients, and instructions.
Looking at feature 2, because it just involves searching, we don't need to store anything unless we want to store what we searched.
Looking at feature 3, because it just involves editing a recipe and we already have recipes stored, nothing else needs to be stored.
Looking at feature 4, because if involves sharing, if let's say chef A wants to send a recipe to chef B, the website needs to know from who to who a recipe is going to, so our website needs to store users. If we think about it deeper, the chef will likely want to know the name of the other chef they are sending the recipe to, and their last name in case many chefs have the same name.
Looking at feature 5, if we want the chef to quickly change the ratios of a recipe, we will perhaps need to have a place in which they can put a ratio and have all the ratios of the recipe change. Because such feature also involve recipes, nothing else needs to be stored.

So, we have the following things that our website needs to store:
- Recipes: (name, image, ingredients, instructions)
- User: (name, lastname)

After knowing how our features are going to look for our website and what it is going to store, we will then proceed to implement these, meaning we will need to write all the code for it. To do so, we implement feature by feature, meaning that we write all the code corresponding to each feature and to the things it requires stored. In the case of feature 1, we would just need to write the code to make the website store recipes, not users yet, and we would only need to create all the webpages that feature 1 needs. We do it this way and not implement all features at the same time to have something concrete done.


### Plannification:

### For each feature:

#### Design the database schema:

#### Determine all new backend routes and other backend code needed:

#### Create the API routes that call the backend:

#### Create the necessary hooks:

#### Create the necessary frontend components:

#### Create the necessary pages

#### Style your pages