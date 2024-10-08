[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].


# Recipebox
### A categorised list of recipes to try and enjoy

One can view recipes by Category, Country of Origin, Prep-time, Difficulty, or simply view a list of all recipes

Structure:

- Directory holding each list.md, and directories for each meal category (Breakfast, Lunch, Dinner, Snack, Dessert) (divide BLD to mains and sides) in which meals will be organised
- if needed, add a drinks section
- Each recipe will need a "metadata/categorisation" section to include the sortable tags above, each should have a link to the homepage of the Recipebox at the top
- Each recipe should use a reasonably standardised template, To be developed
- Attribution for each recipe should be given as a subtitle of the title at the box
- DO I want to add date stamps?
- Will need subdirectories to hold sublists such as canada.md or easy.md


View Recipes By:
- Country of Origin
- Prep-Time
- Difficulty

View Recipes By Meal-Type:
- Breakfast
- Lunch
- Dinner
- Dessert
- Snack

Or, View All Recipes

[testing](https://github.com/wyattshanahan/Recipebox/blob/main/countries/Canada.md)

proposed structure:

upper level:
- meal-category
- difficulty
- country
- prep-time

lower level:
- m-c
  
  -breakfast
	-lunch
	-dinner
	-dessert
	-side
	-snack
	-drink
  
- difficulty
	very easy
	easy
	medium
	hard
	very hard
- country
	country.md, stored in ../countries
- prep-time
	less than 30 min?
	30-60 min
	61m-2 h
	>2h
