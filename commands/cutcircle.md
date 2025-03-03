# Cutcircle

Creates a circle at the specified `(x, y)` position, sets the radius of the circle to "size," rotates the circle to the specified "angle" in degrees, and fills the outline of the circle with "filled" degrees of the line.

```js
cutcircle x y size angle filled
```

Parameters:

* `x`: The x-coordinate of the circle's center.
* `y`: The y-coordinate of the circle's center.
* `size`: The radius of the circle.
* `angle`: The rotation angle of the circle (0 to 36).
* `filled`: The degree of the outline to be filled (0 to 360).

Examples:

```js
cutcircle 0 0 10 0 180
```

Creates an outline of a full circle with a radius of 10 at position `(0, 0)`.

![Screenshot 2024-07-04 at 19 51 46](https://github.com/Mistium/Origin-OS/assets/92952823/d79761e5-c71e-4292-ba85-38ca1f5815da)

```js
cutcircle 0 0 10 0 90
```

Creates an outline of a half circle with a radius of 10 at position `(0, 0)`, facing upwards.

![Screenshot 2024-07-04 at 19 52 21](https://github.com/Mistium/Origin-OS/assets/92952823/a6d5dd75-1b85-481f-8bdc-28011447ad62)

```js
cutcircle 0 0 10 9 90
```

Creates an outline of a half circle with a radius of 10 at position `(0, 0)`, facing right.

![Screenshot 2024-07-04 at 19 52 37](https://github.com/Mistium/Origin-OS/assets/92952823/8e950c2e-ed8a-4b1c-9b42-7a20704dd1f1)

```js
cutcircle 0 0 10 18 90
```

Creates an outline of a half circle with a radius of 10 at position `(0, 0)`, facing downwards.

![Screenshot 2024-07-04 at 19 52 50](https://github.com/Mistium/Origin-OS/assets/92952823/9219d3e2-c459-489d-8222-c83be173063b)

```js
cutcircle 0 0 5 4.5 90
```

Creates a half circle facing north east with a radius of 5.

![Screenshot 2024-07-04 at 19 53 58](https://github.com/Mistium/Origin-OS/assets/92952823/95b9f874-9d3e-4acd-a740-97b5fad9bc1c)
