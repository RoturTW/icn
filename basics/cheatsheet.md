## w

sets the width of all subsequent commands

```
w int
```

basically scratch pen size

## c

sets the colour for all subsequent commands

```
c #fff
c rgb-integer
```

basically scratch pen colour

## line

draws from one x,y to another

```
line x y x y
```

## cont

continues a line from the previous position

```
cont x y
```

## dot

draws a circle at a position

```
dot x y
```

## square

draws a outline of a rectangle at a position with a size

```
square x y width height
```

## rect

draws a filled rectangle at a position with a size

```
rect x y width height
```

## tri

draws a filled triangle

```
tri x y x y x y
```

## move

moves the center of the drawing area

```
move changex changey
```

## back

resets the center of the drawing area

```
back
```

## cutcircle

draws a basic arc from an x y

```
cutcircle x y radius direction arclength
```

direction is from 0 to 18
arclength is from 0 to 180

## ellipse

draws an eliptical outline

```
ellipse x y width multiplier direction
```

the width is how wide the ellipse will be at the equator

the multiplier is how much taller than the width it should be,
eg. a multiplier of 1 is a perfect circle, a multiplier of 2 is twice as tall as wide

direction is from 0 to 360

## curve

draws a quadratic bezier curve

```
curve x y x y controlx controly
```

first pair are starting points
second pair are end points
third pair are control points
