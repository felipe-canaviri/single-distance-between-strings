# Single distance between two strings

Given two string `s1` and `s2`, find if `s1` can be converted to `s2` with exactly one change. This change can be one of the following:
  - Add a character
  - Delete a character
  - Change a character

### Examples
```
Input:  s1 = "greeting", s2 = "greetings"
Output: yes
Number of edits is 1

Input:  s1 = "architecture", s2 = "architecture"
Output: no
Number of edits is 0

Input:  s1 = "shapes", s2 = "shape"
Output: yes
Number of edits is 1

Input:  s1 = "point", s2 = "coin"
Output: no
Number of edits is 2

Input:  s1 = "gold", s2 = "bold"
Output: si
Number of edits is 1
```

Create a method to verify that the given strings have a single distance between them.
