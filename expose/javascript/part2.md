# Part 2

## 1.

Line 12 prints:

```js
3;
```

Because `i` is declared with `var`, so it is function-scoped and still accessible after the for loop ends.

## 2.

Line 13 prints:

```js
150;
```

Because `discountedPrice` is declared with `var`, so it is still accessible outside the loop.

## 3.

Line 14 prints:

```js
150;
```

Because `finalPrice` is function-scoped with `var`.

## 4.

The function returns:

```js
[50, 100, 150];
```

Each price is discounted by 50%.

## 5.

Line 12 causes a `ReferenceError` because `i` was declared with `let` and is block-scoped.

## 6.

Line 13 causes a `ReferenceError` because `discountedPrice` was declared with `let` inside the loop block.

## 7.

Line 14 prints:

```js
150;
```

Because `finalPrice` is still accessible in the function scope.

## 8.

The function returns:

```js
[50, 100, 150];
```

## 9.

Line 11 causes a `ReferenceError` because `i` is block-scoped.

## 10.

Line 12 prints:

```js
3;
```

Because `length` is accessible in the function scope.

## 11.

The function returns:

```js
[50, 100, 150];
```

## 12.

A.

```js
student.name;
```

B.

```js
student["Grad Year"];
```

C.

```js
student.greeting();
```

D.

```js
student["Favorite Teacher"].name;
```

E.

```js
student.courseLoad[0];
```

## 13.

### A.

```js
"3" + 2;
```

Output:

```js
"32";
```

### B.

```js
"3" - 2;
```

Output:

```js
1;
```

### C.

```js
3 + null;
```

Output:

```js
3;
```

### D.

```js
"3" + null;
```

Output:

```js
"3null";
```

### E.

```js
true + 3;
```

Output:

```js
4;
```

### F.

```js
false + null;
```

Output:

```js
0;
```

### G.

```js
"3" + undefined;
```

Output:

```js
"3undefined";
```

### H.

```js
"3" - undefined;
```

Output:

```js
NaN;
```

## 14.

### A.

```js
"2" > 1;
```

Output:

```js
true;
```

### B.

```js
"2" < "12";
```

Output:

```js
false;
```

### C.

```js
2 == "2";
```

Output:

```js
true;
```

### D.

```js
2 === "2";
```

Output:

```js
false;
```

### E.

```js
true == 2;
```

Output:

```js
false;
```

### F.

```js
true === Boolean(2);
```

Output:

```js
true;
```

## 15.

`==` allows type conversion before comparison, while `===` checks both value and type without type conversion.

## 17.

The result is:

```js
[2, 4, 6];
```

Each array element is passed into `doSomething()`, which multiplies the value by 2.

## 19.

Output:

```js
1;
4;
3;
2;
```

`4` prints before the timeouts finish. The `0ms` timeout runs before the `1000ms` timeout.
