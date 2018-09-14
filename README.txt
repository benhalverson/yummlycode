---------- goal ----------

Add only CSS and JS to the included HTML file to fulfill the mocks and specs. Other than the contents of the STYLE and SCRIPT tags, DO NOT MODIFY THE MARKUP AT ALL.

Your results should look as close as possible to the provided mocks, including color, size, spacing, etc. If any of the mocks or instructions are unclear, please ask me for clarification. While some of the requirements may be difficult to accomplish without modifying the HTML, there's nothing that's actually intended to trick you, so please reach out for advice if needed.

---------- specs ----------

Mock 1 is how the page should look on first load.

Mock 2 shows that clicking a RECIPE CARD (any of the blue rectangles in mock 1) should show the ingredients. This is a toggle, so if the ingredients are already showing, clicking the same recipe card should hide the ingredients.

Mock 3 shows that the ingredients should be able to scroll if necessary.

When clicking a RECIPE NAME, do not show or hide the ingredients. Instead, open a new window to its recipe page on Yummly. The URL format is https://www.yummly.com/recipe/NAME-ID where NAME is the recipe name with spaces replaced by hyphens, and ID is the data-id attribute in the recipe markup.

  For example, clicking "Grilled Shrimp Tacos" should open a new window to:
  https://www.yummly.com/recipe/Grilled-Shrimp-Tacos-1102925

Clicking an ingredient should open a new window to an ingredient search on Yummly. the URL format is https://www.yummly.com/recipes?allowedIngredient=NAME where NAME is only the ingredient name, excluding the amount.

  For example, clicking "2 tbsp ghee" should go to:
  https://www.yummly.com/recipes?allowedIngredient=ghee

The buttons at the top should reorder the recipe cards.
  "Randomize" should pick a random order each time it is clicked.
  "Sort by Name" should order them from A to Z.
  "Sort by Calories" should order them from lowest to highest caloric content.

---------- bonus ----------

These features are not required, but would be fantastic to include:

  Animate showing and hiding the list of ingredients. Design details are up to you.

  If a list is already sorted, clicking the same button should REVERSE the order.

    For example, clicking "Sort by Calories" should start with Paneer Masala Dosa and end with Baked Macaroni and Cheese. If the list is already in this order, then clicking "Sort by Calories" again would start with Baked Macaroni and Cheese and end with Paneer Masala Dosa.

---------- note ----------

Yummly's data changes over time, so as long as you build the URLs the correct way, don't be concerned if a recipe page or ingredient search page appear broken on the Yummly side. You're only responsible for your page, not ours!

Again, please ask if you have any questions or concerns about the project.

HB Stone
hb@yummly.com