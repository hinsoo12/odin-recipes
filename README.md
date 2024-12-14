# Odin Recipes

A simple project to practice basic HTML structure and linking between pages. This project involves creating a main index page and multiple recipe pages with consistent formatting and content structure.

## Project Structure

```
odin-recipes/
|-- index.html
|-- recipes/
    |-- lasagna.html
    |-- recipe2.html
    |-- recipe3.html
```

## Iterations

### Iteration 1: Initial Structure
1. Create an `index.html` file in the `odin-recipes` directory.
2. Add the usual boilerplate HTML structure.
3. Add an `<h1>` heading with the text "Odin Recipes" to the `<body>`.

### Iteration 2: Recipe Page
1. Create a `recipes` directory within `odin-recipes`.
2. Add an HTML file for your recipe (e.g., `lasagna.html`) inside the `recipes` directory.
   - Include the usual boilerplate HTML.
   - Add an `<h1>` heading with the recipe's name as its content.
3. In the `index.html` file, add a link to the recipe page under the `<h1>Odin Recipes</h1>` heading:
   ```html
   <a href="recipes/lasagna.html">Lasagna</a>
   ```

### Iteration 3: Recipe Page Content
1. Update each recipe page to include:
   - An image of the dish under the `<h1>` heading.
   - A "Description" section with a heading and a paragraph or two describing the recipe.
   - An "Ingredients" section with a heading and an unordered list of ingredients.
   - A "Steps" section with a heading and an ordered list of preparation steps.

### Iteration 4: Add More Recipes
1. Create two additional recipe pages (e.g., `recipe2.html`, `recipe3.html`) with the same structure as the first recipe page.
2. Link the new recipes on the `index.html` page:
   - Use an unordered list to display all recipe links:
     ```html
     <ul>
       <li><a href="recipes/lasagna.html">Lasagna</a></li>
       <li><a href="recipes/recipe2.html">Recipe 2</a></li>
       <li><a href="recipes/recipe3.html">Recipe 3</a></li>
     </ul>
     ```

## Usage
1. Open `index.html` in your browser to view the list of recipes.
2. Click on a recipe link to view its details, including description, ingredients, and preparation steps.

## Technologies Used
- HTML
