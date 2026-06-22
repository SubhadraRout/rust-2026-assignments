# Solution notes: Min Max

## Approach

I first checked if the slice was empty. If it was, I returned `None`. Otherwise, I initialized the minimum and maximum with the first element and updated them while looping through the slice once.

## Edge cases handled

* Empty slice
* Single element
* All equal elements
* Negative numbers
* Large and small integer values

## Anything special

The solution uses a single `for` loop without any iterator helper methods, as required.
