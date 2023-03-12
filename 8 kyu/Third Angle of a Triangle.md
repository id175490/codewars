# **[Third Angle of a Triangle](https://www.codewars.com/kata/5a023c426975981341000014/javascript)**

## **Description**:

You are given two interior angles (in degrees) of a triangle.

Write a function to return the 3rd.

## **Note**:

Only positive integers will be tested.

https://en.wikipedia.org/wiki/Triangle

## **Solution**:

```javascript
const otherAngle = (a, b) => 180 - a - b;
```
