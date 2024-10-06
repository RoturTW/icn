# Lines

To draw a line, you can choose between drawing a full line or continuing from the last point of the previously drawn element.

## Drawing lines

You can draw a full line using the command below

```javascript
line x y x y
```

This command will draw a single line between two x,y positions

```javascript
line 10 10 -10 -10
```

You can also continue the previous line using cont

```
cont x y
```

## Using Cont

```javascript
line 10 10 -10 -10
line -10 -10 10 -10
```

Would draw the exact same thing as

```javascript
line 10 10 -10 -10
cont 10 -10
```
