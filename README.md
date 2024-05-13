# PROG6221-PART1

# Recipe Guide

This program allows the user to enter details for a recipe, including ingredients and steps. It then displays the recipe and provides options to scale the recipe, reset quantities, clear the recipe, or exit the program.


# Display Recipe Guideline

The program then displays the full recipe, including the ingredients and steps, in a neat format.The user can request that the recipe be scaled by a factor of 0.5 (half), 2 (double), or 3 (triple), and all the ingredient quantities will be changed accordingly when the recipe is displayed. 

The user can also request that the quantities be reset to the original values. The user can clear all the data to enter a new recipe.The program uses automatic properties to simplify the code and make it more readable. It also follows internationally acceptable coding standards, including meaningful variable names, comments explaining the logic of the code, and consistent indentation.To compile and run the program, you can follow the instructions in the provided readme file. The program does not persist the user data between runs, as required. The user shall be able to enter an unlimited number of recipes.

2. The user shall be able to enter a name for each recipe.

3. The software shall display a list of all the recipes to the user in alphabetical order by name.

4. The user can choose which recipe to display from the list.

5. For each ingredient, the user shall additionally be able to enter:

a. The number of calories, and

b. The food group that the ingredient belongs to.

6. The software shall calculate and display the total calories of all the ingredients in a recipe.

7. The software shall notify the user when the total calories of a recipe exceed 300

# What The Program Does

This program allows The user shall be able to enter the details for a single recipe:

The number of ingredients.

b. For each ingredient: the name, quantity, and unit of measurement. For example, one tablespoon of sugar.

c. The number of steps.

d. For each step: a description of what the user should do.

2. The software shall display the full recipe, including the ingredients and step
The user shall be able to request that the recipe is scaled by a factor of 0.5 (half), 2 (double), or (triple). 
3. All the ingredient quantities shall be changed accordingly when the recipe is displayed. For example, one tablespoon of sugar will become two tablespoons of sugar if the factor is 2.

4. The user can request that the quantities be reset to the original values.

5. The user shall be able to clear all the data to enter a new recipe.
6. Based on the feedback from Part 1, we'll implement the changes and add new features for Part 2:

Allow entering an unlimited number of recipes.
Allow entering a name for each recipe.
Display a list of all recipes in alphabetical order by name.
Allow the user to choose which recipe to display from the list.
For each ingredient, allow entering the number of calories and the food group.
Calculate and display the total calories of all ingredients in a recipe.
Notify the user when the total calories of a recipe exceed 300.
Use generic collections instead of arrays.
Use a delegate to notify the user when a recipe exceeds 300 calories.
Create a unit test to test the total calorie calculation.

# PROG6221-PART2

Implemented the ability to enter an unlimited number of recipes.
Allowed entering a name for each recipe.
Displayed a list of all recipes in alphabetical order by name.
Allowed the user to choose which recipe to display from the list.
Added the ability to enter the number of calories and the food group for each ingredient.
Calculated and displayed the total calories of all ingredients in a recipe.
Notified the user when the total calories of a recipe exceed 300.
Used generic collections (List<T>) instead of arrays.
Used a delegate to notify the user when a recipe exceeds 300 calories.
Created a unit test to test the total calorie calculation.
https://github.com/10066644/PROG6221-PART1.git
