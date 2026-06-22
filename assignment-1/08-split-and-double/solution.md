# Solution notes: Split and Double

## Approach

I used `split_at_mut()` to split the vector into two mutable slices at the given index. Then I looped through each slice and doubled every element. Finally, I returned both slices.

## Edge cases handled

* Empty vector
* Split at index `0`
* Split at the end of the vector
* Single element
* Panic when `mid` is greater than the vector length

## Anything special

`split_at_mut()` creates two disjoint mutable slices, allowing both halves to be modified safely at the same time.
