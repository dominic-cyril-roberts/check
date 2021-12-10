# ***check***
The todo-list/jot-shit-down app I've always wanted and keep making on paper


## Key Features

- Arbitrarily deep nesting of `items`
- Every `item` should be expandable into its own `list`
- `items` in a `list` should be ordered, and the order should be mutable
- Integration with various image/icon sources to tag `items` and `lists` as desired

## Entities

- `item`
    - `id`: unique identifier
    - `title`: This is all that is displayed for child items in `list view`
    - `description`: This is displayed for the "parent" `item` in `list view`
    - `next-child`: the `id` belonging to the `item` of the current `item's` first child (this is the first item "under" the current one)
    - `next-sibling`: the `id` belonging to the `item` of the current `item's` next sibling (this is the next item in the list) 
    - `type` (provisional): - This is how we would polymorph `items` into having more specific behaviors
        - `todo`: renders the item with a ``checkbox`` and introduces a boolean, `complete` (default false) to reflect the `checkbox's` / `item's` completion status
    - `icons` (optional): images/emoji's to attach to the item

## Flows

- `List View/Item-Detail View`: Display the title and description of the top level `item`, and the titles of the it's child items, appropriately tabbed
- `Add Item to Nowhere`: add an item to the top level items list
- `Add item as child`: append a new item as a child to an existing item list
- `Delete an Item`: remove an item by id
- `Move an item`: i mean...you can read things
- `Edit an item`: modify an item's title, description or type