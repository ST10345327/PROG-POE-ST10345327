# RecipeApp README File				

## Introduction
This is a console-based recipe application written in C# as part 2 of the PROG6221 assessment. The application allows users to add, display, and manage recipes, including ingredients and steps. It also calculates the total calories of each recipe and notifies the user if the total calories exceed 300.

## Application Instructions

To compile and run this software, follow the following steps:

1. Ensure that you have installed VS/Visual Studio on your computer.
2. Clone this repository from gitHub, to your local machine.
3. Open the solution file ('RecipeApp.sln') in VS/ Visual Studio.
4. Build the solution to compile the software.
5. Run the compiled application.
6. Congratulations!

## How to Run
To run the application, follow these steps:
1. Clone the repository to your local machine.
2. Open the solution file (`RecipeApp.sln`) in Visual Studio.
3. Set the startup project to the `RecipeApp` project.
4. Build the solution by clicking on the Build menu and selecting “Build Solution” or pressing Ctrl+Shift+B.
5. Press F5 or click on the “Start” button to run the program.
6. Follow the on-screen instructions to interact with the application.

## Functionality
- **Add a Recipe**: Enter details for a new recipe, including name, ingredients, and steps.
- **Display Recipes**: View a list of all recipes, sorted alphabetically by name, along with their ingredients and steps.
- **Calculate Total Calories**: The application calculates the total calories of each recipe based on the calories of its ingredients.
- **Notify Exceeding Calories**: If the total calories of a recipe exceed 300, the application notifies the user.



## File Structure
- `Program.cs`: Main program file containing the entry point and main logic of the application.
- `Recipe.cs`: Class file defining the `Recipe` class with properties and methods for managing recipes.
- `Ingredient.cs`: Class file defining the `Ingredient` class with properties and methods for managing ingredients.

## Unit Tests
Unit tests for the application’s functionality can be found in the `RecipeAppTests` project. These tests cover the calculation of total calories and other critical functions of the application.

## Feedback Incorporation
Based on feedback received from the lecturer, the following changes were made for Part 2 of the assessment:
- Added support for multiple recipes and additional features such as entering a name for each recipe.
- Implemented the ability to enter additional details for each ingredient, calculate total calories, and notify the user of calorie exceedance.
- Utilized generic collections to store recipes, ingredients, and steps instead of arrays.
- Created unit tests to ensure the correctness of the total calorie calculation.

## GitHub Repository
Link to the GitHub repository: [RecipeApp GitHub Repository]( https://github.com/st10345327/recipe-app)

For any questions or issues, please contact [ST10345327@RCCONNECT.EDU.ZA].
## Developer Information
Name: Olebogeng	Phawe	ST10345327
