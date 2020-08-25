# Instance of Restaurant Class: guard_and_grace_dinner_menu

## Attributes
```
restaurant_description = "Named after the chef’s daughter, Guard and Grace is a take on the big, fancy, modern steakhouse – miles and miles of fiery grills and charcuterie, oyster bar and bar tops, private rooms, and a posh, walk-in, floor-to-high-ceiling glassed wine cellar – yet still, with more of a bright, airy playfulness than the usual dark, stiff, mano a mano atmosphere."
item_name = ["oak fired carrots", "spinach dip", "oak fired octoput"]
item_ingredients = {
  "oak fired carrots": "herb yogurt, fennel herb salad, pistachio crumble",
  "spinach dip": "goat cheese, crispy prosciutto, cherry peppers",
  "oak fired octoput": "white bean & celery salad, spanish chorizo, sherry vinaigrette, red pepper sauce"
}
inventory = {"goat cheese": 101, "cherry peppers": 77, "spanish chorizo": 172}
is_open = true
```

## Methods
```
change_description  # Modify string restaurant_description
order_item  # Order "oak fired carrots"
open_store  # Modify is_open to true
restock  # Modify values stores in the inventory hash
```
