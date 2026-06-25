# Hashing

Hashing is a technique used to store and retrieve data efficiently using hash-based data structures such as `unordered_map` and `unordered_set`.

## Topics Covered
- Unordered Map
- Unordered Set
- Frequency Counting
- Duplicate Detection
- Prefix Sum + Hash Map

## Time Complexity
- Insertion: O(1) average
- Search: O(1) average
- Deletion: O(1) average

## Problems

| LeetCode | Problem | Concepts |
|----------|---------|----------|
| 217 | Contains Duplicate | Unordered Set |
| 349 | Intersection of Two Arrays | Unordered Set |
| 1 | Two Sum | Unordered Map |
| 169 | Majority Element | Hash Map |
| 560 | Subarray Sum Equals K | Prefix Sum + Hash Map |

## Key STL Functions

### unordered_set
```cpp
insert()
find()
erase()
```

### unordered_map
```cpp
mp[key]++
find()
erase()
```

## Notes
- Use `unordered_set` when only unique elements are required.
- Use `unordered_map` when frequencies or key-value pairs are needed.
- Hashing helps reduce time complexity from O(n²) to O(n) in many problems.
