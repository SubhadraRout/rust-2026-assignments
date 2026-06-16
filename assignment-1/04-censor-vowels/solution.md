# Solution notes: Censor vowels

## Approach

I looped through each character in the string. If the character was a vowel, I replaced it with `*`. Otherwise, I kept the character the same. Finally, I replaced the original string with the new one.

## Edge cases handled

* Empty string
* Uppercase and lowercase vowels
* Strings without vowels
* Digits and punctuation

## Anything special

The original string is updated after building the modified string.
