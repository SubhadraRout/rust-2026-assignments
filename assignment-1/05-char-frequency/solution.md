# Solution notes: Character frequency

## Approach

I used a `HashMap` to count how many times each character appears in the input string. Then I converted the map into a vector and sorted it by count in descending order. If two characters had the same count, I sorted them alphabetically.

## Edge cases handled

* Empty string
* Single character
* Repeated characters
* Equal frequencies
* Spaces are counted as characters

## Anything special

The solution uses a `HashMap` for counting and sorts the final result according to the required order.
