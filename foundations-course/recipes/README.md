# Odin Recipes

## Description
This project is part of **The Odin Project** and aims to help practice HTML fundamentals by building a basic recipe website. The goal is to create a functional structure of a recipe site where each recipe is displayed on a separate page, and users can navigate through different recipes easily. The website won't be styled yet, as this iteration focuses purely on the structure and organization of the HTML code. Later, in future projects, we will revisit this site to add styling using CSS.

### Skills Practiced:
- Structuring basic HTML pages
- Creating internal and external links
- Organizing files in directories
- Working with images and text elements
- Creating lists (unordered and ordered)

## Project Structure
- **index.html**: The main page of the website, displaying a list of recipes with links to individual recipe pages.
- **recipes/**: A directory that contains individual recipe pages (e.g., `lasagna.html`).
  - Each recipe page contains:
    - A title
    - An image of the dish
    - A brief description of the recipe
    - A list of ingredients
    - The steps required to make the dish.

## Iteration Breakdown

### Iteration 1: Initial Structure
- Created an **index.html** file with the basic HTML structure.
- Added an `<h1>` heading with the text "Odin Recipes".
- Set up links to different recipe pages (to be added in future iterations).

### Iteration 2: Recipe Pages
- Created a **recipes/** directory to store the individual recipe HTML files.
- Created a recipe page (e.g., `lasagna.html`) with basic HTML structure.
- Added a link back to the home page (index.html) and links to each recipe from the home page.

### Iteration 3: Recipe Page Content
- Enhanced each recipe page to include:
  - An image of the dish.
  - A description of the recipe.
  - A list of ingredients in an unordered list.
  - A list of preparation steps in an ordered list.

### Iteration 4: Additional Recipes
- Added two more recipe pages.
- Updated the index page to include links to all recipes in an unordered list for easier navigation.

## Running the Project Locally
1. Clone the repository to your local machine:

```bash
git clone git@github.com:<your-username>/odin-recipes.git
