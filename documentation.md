---
output: pdf_document
---

# ADDITIONAL CAS FUNCTIONS

## Functions and graphs

### `two_points(x1,y1,x2,y2)`

finds information of 2 points in a cartesian plane

$$\text{two\_points}(-2,4,2,0)$$
$$\to\text{equation: y=}2-x$$
$$\to\text{midpoint: }(0,2)$$
$$\to\text{length: }4\sqrt{2}$$

### `stationary(f(x),x)`

finds the stationary points of any function

$$\text{stationary}(x^4-2x^2,x)$$
$$\to\begin{bmatrix}x&-1&0&1\\y&-1&0&-1\end{bmatrix}$$

## Complex numbers

### `cis(x)`

find rectangular form of a polar complex number

$$\text{cis}(\frac{\pi}{6})$$
$$\to\frac{\sqrt{3}}{2}+\frac{1}{2}i$$

### `to_polar(z)`

convert rectangular complex number to polar

$$\text{to\_polar}(5+5\sqrt{3}i)$$
$$\to10\text{cis}(\frac{\pi}{3})$$

## Geometry

### `circle_line(cx,cy,r,l)`

finds the areas of parts of a circle intersected by a line

$$\text{circle\_line}(2,1,3,2x)$$
$$\to\text{pizza1: }9.96$$
$$\to\text{pizza2: }18.31$$
$$\to\text{triangle: }7.2$$

## Vectors

### `mag(v)`

finds the magnitude of a vector

$$\text{mag}(\begin{bmatrix}3&4\end{bmatrix})$$
$$\to5$$

### `ang(v1, v2)`

finds the angle between 2 vectors

$$\text{ang}(\begin{bmatrix}1&0\end{bmatrix},\begin{bmatrix}1&\sqrt{3}\end{bmatrix})$$
$$\to\frac{\pi}{3}$$

### `scalar_resolute(v1,v2)`

finds the scalar resolute of 2 vectors

$$\text{scalar\_resolute}(\begin{bmatrix}1&2\end{bmatrix},\begin{bmatrix}3&4\end{bmatrix})$$
$$\to\frac{11}{5}$$

### `vector_resolute(v1,v2)`

finds the vector resolute of 2 vectors

$$\text{vector\_resolute}(\begin{bmatrix}1&0\end{bmatrix},\begin{bmatrix}2&1\end{bmatrix})$$
$$\to\begin{bmatrix}\frac{4}{5}&\frac{2}{5}\end{bmatrix}$$
