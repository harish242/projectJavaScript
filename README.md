# Meal Planner Project

Welcome to the Meal Planner project, a web application designed to help users plan their meals based on their daily calorie requirements. This project provides a practical solution to the challenges of managing and planning daily meals in a busy modern lifestyle.

![Meal Planner](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2562ce31-9f31-46a5-9ba1-3df636d436e4/image_(1).png)

## Project Objective

The objective of this project is to create a meal planner application using HTML, CSS, and JavaScript. The application will take user data, calculate their daily calorie requirement, and generate meal plans along with recipes.

## Project Context

Modern life has made it challenging to manage and plan daily meals. There is a vast amount of information on the internet, making it time-consuming to find new recipes and gather all the necessary details in one place. Meal Planner aims to simplify meal planning and provide users with convenient access to recipes.

## Tech Stack Prerequisite

- HTML
- CSS
- JavaScript

## Project Steps

### Step 1: Nav Bar

- Create a navigation section with a logo for the website.

### Step 2: User Form

- Implement a user form to collect data for daily calorie requirement calculation.
- The form should include fields for weight (kg), height (cm), age, gender, and physical activity level.
- Physical activity level should have options for "light," "moderate," and "active."
- Include a submit button.

### Step 3: Meal Plan

- Display three meal cards for breakfast, lunch, and dinner.
- Each meal card should include a meal image, meal name, calorie information, and a "get-recipe" button.

### Step 4: Recipe

- Create recipe tabs for "Ingredients" and "Steps."
- Ingredients tab should list ingredients and their quantities.
- Steps tab should display the ordered list of steps for the recipe.

### Step 6: Daily Calorie Requirement

- Calculate the BMR (Basal Metabolic Rate) of the user based on input data and gender.
- Calculate the daily calorie requirement using the BMR and the user's selected physical activity level.

### Step 7: Generate Meal Plan

- Use the Newton Food API to generate a new meal plan based on daily calorie requirements.
- Populate the meal plan section with meals from the API.
- Display the meal plan section only after generating the meal plan.

### Step 8: Generate Recipe

- Fetch recipes from the API when the user clicks the "get-recipe" button on a meal card.
- Display the recipe details, including ingredients and steps, in the recipe section.
- Show the recipe section only after fetching data from the API.

## Project Checkpoints

- Navbar and User Form: Implement the navigation bar and user data input form.
- Meal Plan and Recipe Section: Create the meal plan and recipe tabs.
- Daily Calorie Calculation and Meal Plan Generation: Calculate daily calorie requirements and generate meal plans.
- Fetching and Displaying Recipes: Fetch and display recipe details from the API.

## Getting Started

To run the Meal Planner project locally, follow these steps:

1. Clone the project repository to your local machine.
2. Open the project folder in your code editor.
3. Launch the project by opening the HTML file in your web browser.

## Project Contributors

- [Your Name]
- [Team Member Names, if applicable]

## Acknowledgments

- Thanks to Newton School for providing project guidance and resources.

Enjoy planning your meals with Meal Planner!
