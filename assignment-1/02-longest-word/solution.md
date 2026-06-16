# Solution notes: Longest word

## Approach

I used `split_whitespace()` to go through each word in the sentence. I kept track of the longest word found so far and updated it whenever I found a longer one.

## Edge cases handled

* Empty string
* Whitespace-only string
* Single word
* Multiple words with the same length (returns the first one)

## Anything special

The function returns a borrowed `&str` from the original sentence without creating a new `String`. It only goes through the sentence once.
