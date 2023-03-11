# **[Reversed Strings](https://www.codewars.com/kata/5168bb5dfe9a00b126000018/solutions/javascript)**

## **Description**:

Complete the solution so that it reverses the string passed into it.

## **Examples**:

```
(input --> output)
'world'  =>  'dlrow'
'word'   =>  'drow'
```

## **Solution**:

```javascript
const solution = (str) =>
  str === "" ? "" : solution(str.substring(1)) + str.charAt(0);
```
