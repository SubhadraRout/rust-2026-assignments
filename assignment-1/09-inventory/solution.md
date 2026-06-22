# Solution notes: Inventory

## Approach

I used a `HashMap` to merge items with the same name by adding their quantities together. For the summary function, I borrowed the inventory, counted the number of items, and calculated the total quantity.

## Edge cases handled

* Empty inventory
* Duplicate item names
* Different item names

## Anything special

`summary()` only borrows the inventory, while `restock()` takes ownership of both vectors and returns a new merged inventory.
