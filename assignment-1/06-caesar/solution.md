# Solution notes: Caesar cipher

## Approach

I looped through each character in the input string. If it was an uppercase or lowercase letter, I shifted it by the given amount while wrapping around the alphabet. Non-letter characters were left unchanged.

## Edge cases handled

* Empty string
* Negative shifts
* Large shifts
* Uppercase and lowercase letters
* Digits, punctuation, and spaces

## Anything special

I used `ALPHABET.len()` to determine the alphabet size instead of hard-coding `26`.
