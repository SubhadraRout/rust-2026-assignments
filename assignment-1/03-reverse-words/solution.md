# Solution notes: Reverse words

## Approach

I used `split_whitespace()` to split the sentence into words, reversed the order using `rev()`, and joined them back together with a single space.

## Edge cases handled

* Empty string
* Whitespace-only string
* Multiple spaces, tabs, and newlines
* Single word

## Anything special

`split_whitespace()` automatically removes extra whitespace, so the output is trimmed and contains only single spaces between words.
