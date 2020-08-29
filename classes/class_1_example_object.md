# Instance of Menu Class: guard_and_grace_dinner_menu

## Attributes
```
restaurant_description = "Named after the chef’s daughter, Guard and Grace is a take on the big, fancy, modern steakhouse – miles and miles of fiery grills and charcuterie, oyster bar and bar tops, private rooms, and a posh, walk-in, floor-to-high-ceiling glassed wine cellar – yet still, with more of a bright, airy playfulness than the usual dark, stiff, mano a mano atmosphere."
item_name = ["oak fired carrots", "spinach dip", "oak fired octoput"]
item_ingredients = {
  "oak fired carrots": "herb yogurt, fennel herb salad, pistachio crumble",
  "spinach dip": "goat cheese, crispy prosciutto, cherry peppers",
  "oak fired octopus": "white bean & celery salad, spanish chorizo, sherry vinaigrette, red pepper sauce"
}
font = "Cabin"
```

## Methods
```
change_description = "Guard and Grace is a good Denver restaurant, and this is a less verbose description of it."  # Modify string restaurant_description
order_item[0] = "oak fired carrots"  # Order "oak fired carrots"
delete_item("oak fired carrots") = "herb yogurt, fennel herb salad, pistachio crumble"  # Delete the key-value pair in the hash. Return value of delete_item(key) is the value from hash whose key is equal to (key).
```
