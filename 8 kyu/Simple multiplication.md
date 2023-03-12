# **[Simple multiplication](https://www.codewars.com/kata/583710ccaa6717322c000105/javascript)**

## **Description**:

This kata is about multiplying a given number by eight if it is an even number and by nine otherwise.

## **Solution**:

```javascript
const simpleMultiplication = (number) =>
  (number % 2 == 0 ? number * 8 : number * 9);
```
