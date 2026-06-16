# Solution notes: Run-length encode

## Approach

I looped through the input string and counted consecutive repeated characters. When the character changed, I stored the character and its count in the result vector. After the loop, I added the last character and its count.

## Edge cases handled

* Empty string
* Single character
* Repeated characters
* Different characters
* Whitespace characters

## Anything special

The solution goes through the input only once, making it simple and efficient.
