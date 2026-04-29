# Part 1

## 1.

Line 9 prints:

```js
values added: 20
```

## 2.

Line 13 prints:

```js
final result: 20
```

Because `var` is function-scoped.

## 3.

We should avoid using `var` because it is function-scoped and can create unexpected behavior and bugs.

## 4.

Line 9 prints:

```js
values added: 20
```

## 5.

Line 13 causes a `ReferenceError` because `result` is block-scoped with `let`.

## 6.

The code causes a `TypeError` because `const` variables cannot be reassigned.

## 7.

Line 13 does not execute because the code already throws a `TypeError`.
