# Array

- ### In JavaScript arrays are their built-in methods ?

| Array        | Method      | Action                                             | Returned     |
| ------------ | ----------- | -------------------------------------------------- | ------------ |
| [a, b, c, d] | .length     | Returns the length of the array                    | 4            |
| [1,15,22,-1] | .sort()     | Returns a sorted array                             | [-1,1,15,22] |
| [1,2,3]      | .push(10)   | Adds a new value at the end of the array           | [1,2,3,10]   |
| [1,2,4,5]    | .pop()      | Removes the last element of the array              | [1,2,4]      |
| [1,2,3,4]    | .shift()    | Removes the first element of the array             | [2,3,4]      |
| [1,2,3]      | .unshift(1) | Adds a new value as the first element of the array | [1,1,2,3]    |
| [1,2,3]      | .reverse()  | Reverses the order of array elements               | [3,2,1]      |

---
- ### Remove Duplicates From a JavaScript Array ?

`let arr = [1, 2, 3, 4, 1, 2, 3];
const remove_dublicate = (data) => {
return data.filter((value, index) => data.indexOf(value) === index);
};
console.log(remove_dublicate(arr));`