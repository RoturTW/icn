# Curve

You can draw smooth curves in icn using the curve command.

```
curve start control end
```

<figure><img src="../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

```python
curve 0 -100 0 100 100 -100
```

Lets break it down,

0, -100 is right at the bottom in the middle and is our starting point, you can see it as the left point on the curve

0, 100 is the top middle, and it defines where the curve's control point is

100, -100 is the bottom right and its where the curve ends



For the full icn above, heres the code

```python
w 0
c #000
tri -100 -100 100 -100 0 100
c #fff
curve 0 -100 100 -100 0 100
```
