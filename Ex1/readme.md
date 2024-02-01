# array_front9 Function

The `array_front9` function checks if the number 9 is present in the first four elements of a given list.

Given an array of ints, return True if one of the first 4 elements in the array is a 9. The array length may be less than 4.

array_front9([1, 2, 9, 3, 4]) → True
array_front9([1, 2, 3, 4, 9]) → False
array_front9([1, 2, 3, 4, 5]) → False

## Usage

```python
nums = [1, 9, 2, 3, 4]
result = array_front9(nums)
print(result)
