# Solution notes: Group Anagrams

## Approach

I converted each word to lowercase and sorted its characters to create a signature. I used a `HashMap` to group words with the same signature. Finally, I returned all the groups.

## Edge cases handled

* Empty input
* Single word
* Different word lengths
* Case-insensitive comparison
* Original word order preserved within each group

## Anything special

The signature is created by sorting the lowercase characters of each word, making all anagrams share the same key.
