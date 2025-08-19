# The Odin Project

## Project: Recipes

### Iteration 1: initial structure

1. Within the odin-recipes directory, create an index.html file.
2. Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.

### Iteration 2: recipe page

1. Create a new directory within the odin-recipes directory and name it recipes.
2. Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use at Allrecipes. Be sure to include the usual boilerplate HTML. This boilerplate code should be in every .html file you create.
3. For now, just include an h1 heading with the recipe’s name as its content.
4. Back in the index.html file, add a link to the recipe page you just created. Example: Under the <h1>Odin Recipes</h1> heading, write out the link like so: <a href="recipes/recipename.html">Recipe Title</a>. The text of the link should again be the recipe name.
5. Add a link back to the index page on your recipe page for easier navigation. You can place this link at the top or bottom of your recipe page (e.g., lasagna.html). Here’s an example:

   `<a href="../index.html">Home</a>`

   This allows users to quickly return to the home page after viewing the recipe.

### Iteration 3: recipe page content

Your new recipe page should have the following content:

1. A free image of the finished dish under the h1 heading that you added earlier.
2. Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.
3. Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.
4. Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.

### Iteration 4: add more recipes

1. Add two more recipes with identical page structures to the recipe page you’ve already created.
2. Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.

Example:

```
 <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
  </ul>
```

Your links won’t be flashy, but for now, just focus on building them out.
