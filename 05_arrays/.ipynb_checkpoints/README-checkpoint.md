# Chapter 5: Arrays

### Two Pointer

### `list` type
- provides arrays: key property = dynamically-resized
    - no bounds to how many values you can add to it 
    - tuples similar but are immutable (can't change them)

### Operations
- `x.append()`
- `x.remove()`
- `x.insert()`
- `x.min()`
- `x.max()`
- `reversed(x)` -> returns iterator
- `x.reverse()` -> in-place
- `sorted(x)` -> returns a copy
- `x.sort()` -> in-place
- `del x[i]` -> removes element at ith place
- `del x[x:]` -> removes slice


### 2D Array 
- [[1,2,3],[4,5],[6],[7,8,9]]

### [Deep Copy V. Shallow Copy](deepShallowCopy.ipynb)
- Deep Copy: 
    - creates new object 
    - recursively populates new object with copies of child object 
- Shallow Copy:
    - creates new object
    - populates new object with **references** to child objects
    
### Slicing 
- `x[::-1]` -> reverses list
- `x[k:] + x[:k]` -> rotates array by `k`

### List Comprehension

### [Binary Search](binarySearch.ipynb)
