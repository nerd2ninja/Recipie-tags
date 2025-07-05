# Recipie-tags
A system to create recipies by tag so that users can query by available ingrediants, cooking methods, dietary needs, and preferences.

#Layout

First and foremost, ingredients will be pulled from [USDA FoodData Central](https://fdc.nal.usda.gov/download-datasets) using the json. 

All ingrediants listed must match the json "Description" tag from the USDA FoodData Central

[fx](https://search.nixos.org/packages?channel=25.05&show=fx&from=0&size=50&sort=relevance&type=packages&query=json+viewer) is a pretty nice to use viewer for json data and its hotkeys can be found [here](https://fx.wtf/key-bindings)

So, for example, if a recepie calls for cheddar cheese, the ingrediant should be listed as "Cheese, cheddar" just as it is listed in the description tag.

