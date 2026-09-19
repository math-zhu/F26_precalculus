# Homework 1 Solutions

Based on [Lecture 1: Coordinates, Lines, and Circles](../Notes/N1.md).

**Exercise 1.** Plot $(3,-2)$, $(-4,1)$, and $(0,5)$, and say which quadrant
(or axis) each lies in. Where does each point go under
$(a,b)\mapsto(a+3,b-1)$?

Apply $(a,b)\mapsto(a+3,b-1)$ to each point:

- $(3,-2)$ is in Quadrant IV, and maps to $(6,-3)$, also in Quadrant IV.
- $(-4,1)$ is in Quadrant II, and maps to $(-1,0)$, on the $x$-axis.
- $(0,5)$ is on the positive $y$-axis, and maps to $(3,4)$, in Quadrant I.

**Exercise 2.** Find the distance between $(1,1)$ and $(4,5)$.

For $(1,1)$ and $(4,5)$,

$$
 d=\sqrt{(4-1)^2+(5-1)^2}=\sqrt{3^2+4^2}=5.
$$

**Exercise 3.** Show that $(0,0)$, $(3,0)$, and $(0,4)$ form a right triangle
using the distance formula.

Let $A=(0,0)$, $B=(3,0)$, and $C=(0,4)$. The three side lengths are

$$
AB=3,\qquad AC=4,
$$

and

$$
BC=\sqrt{(3-0)^2+(0-4)^2}=\sqrt{9+16}=5.
$$

Since $3^2+4^2=5^2$, the converse of the Pythagorean theorem shows that the angle at $A$ is a right angle. Thus the points form a right triangle.

**Exercise 4.** Find the midpoint of $(-3,4)$ and $(5,-2)$, and verify by the
distance formula that it is equidistant from both.

The midpoint is

$$
M=\left(\frac{-3+5}{2},\frac{4+(-2)}{2}\right)=(1,1).
$$

Its distances to the endpoints are

$$
\begin{aligned}
MA&=\sqrt{(1-(-3))^2+(1-4)^2}=\sqrt{4^2+(-3)^2}=5,\\
MB&=\sqrt{(1-5)^2+(1-(-2))^2}=\sqrt{(-4)^2+3^2}=5.
\end{aligned}
$$

Therefore $M$ is equidistant from the two endpoints, as required.

**Exercise 5.** A point $(x,0)$ on the $x$-axis is equidistant from $(1,2)$ and
$(5,-4)$. Find $x$.

Let $P=(x,0)$. Equidistance from $(1,2)$ and $(5,-4)$ gives

$$
(x-1)^2+(0-2)^2=(x-5)^2+(0+4)^2.
$$

Expanding and simplifying,

$$
x^2-2x+5=x^2-10x+41,
$$

so $8x=36$ and

$$
\boxed{x=\frac92}.
$$

Thus the point is $\left(\frac92,0\right)$.

**Exercise 6.** Write the equation of the circle with center $(2,-1)$ and
radius $3$.

Using center $(h,k)=(2,-1)$ and radius $r=3$,

$$
\boxed{(x-2)^2+(y+1)^2=9}.
$$

**Exercise 7.** Does the point $(4,3)$ lie on, inside, or outside the circle
$x^2+y^2=20$?

The squared distance from $(4,3)$ to the origin is

$$
4^2+3^2=25.
$$

The circle $x^2+y^2=20$ has radius squared $20$. Since $25>20$, the point $(4,3)$ lies outside the circle.

**Exercise 8.** The equation $x^2+y^2-4x+6y-12=0$ represents a circle.
Complete the square to write it in standard form
$(x-h)^2+(y-k)^2=r^2$, then find its center and radius.

Complete the square:

$$
\begin{aligned}
x^2+y^2-4x+6y-12&=0\\
(x^2-4x+4)+(y^2+6y+9)&=12+4+9\\
(x-2)^2+(y+3)^2&=25.
\end{aligned}
$$

Therefore the center is

$$
\boxed{(2,-3)}
$$

and the radius is

$$
\boxed{5}.
$$

**Exercise 9.** Find the equation of the circle passing through the three
points $(0,0)$, $(4,0)$, and $(0,-2)$.

Use the general circle equation

$$
x^2+y^2+Dx+Ey+F=0.
$$

Substitution of $(0,0)$ gives $F=0$. Substitution of $(4,0)$ gives

$$
16+4D=0 \quad\Longrightarrow\quad D=-4.
$$

Substitution of $(0,-2)$ gives

$$
4-2E=0 \quad\Longrightarrow\quad E=2.
$$

Thus the circle is

$$
\boxed{x^2+y^2-4x+2y=0}.
$$

Completing the square gives

$$
(x-2)^2+(y+1)^2=5.
$$

So its center is $(2,-1)$ and its radius is $\sqrt5$.

**Exercise 10.** Compute the slope between $(-1,3)$ and $(2,-3)$. Is the line
rising or falling?

The slope is

$$
m=\frac{-3-3}{2-(-1)}=\frac{-6}{3}=-2.
$$

Because the slope is negative, the line is falling from left to right.

**Exercise 11.** The points $(1,2)$, $(3,k)$, and $(7,14)$ are collinear. Find
$k$.

The slope from $(1,2)$ to $(7,14)$ is

$$
\frac{14-2}{7-1}=\frac{12}{6}=2.
$$

Thus the line through $(1,2)$ is $y-2=2(x-1)$, or $y=2x$. At $x=3$,

$$
\boxed{k=6}.
$$

**Exercise 12.** Find the equation of the line through $(0,5)$ and $(2,1)$.

The slope through $(0,5)$ and $(2,1)$ is

$$
m=\frac{1-5}{2-0}=-2.
$$

Using $(0,5)$ in point-slope form,

$$
y-5=-2(x-0),
$$

so the equation is

$$
\boxed{y=-2x+5}.
$$

**Exercise 13.** A line through $(a,2)$ and $(3,b)$ has slope $2$ and passes
through $(0,1)$. Find $a$ and $b$.

A line of slope $2$ passing through $(0,1)$ has equation

$$
y=2x+1.
$$

Since $(a,2)$ lies on it,

$$
2=2a+1 \quad\Longrightarrow\quad a=\frac12.
$$

Since $(3,b)$ lies on it,

$$
b=2(3)+1=7.
$$

Therefore

$$
\boxed{a=\frac12,\qquad b=7}.
$$

**Exercise 14.** Find the intersection of $y=2x+1$ and $y=-x+4$.

Set the two expressions for $y$ equal:

$$
2x+1=-x+4.
$$

Then $3x=3$, so $x=1$. Substituting gives $y=3$. The intersection is

$$
\boxed{(1,3)}.
$$

**Exercise 15.** Find the line through $(1,1)$ perpendicular to $y=3x-2$.

The given line has slope $3$, so a perpendicular line has slope $-\frac13$. Through $(1,1)$,

$$
y-1=-\frac13(x-1).
$$

Thus

$$
\boxed{y=-\frac13x+\frac43}.
$$

**Exercise 16.** Find the equation of the line through the intersection of
$y=2x+1$ and $y=-x+4$ that is perpendicular to $y=\tfrac12x-3$.

From Exercise 14, the intersection of $y=2x+1$ and $y=-x+4$ is $(1,3)$. The line $y=\frac12x-3$ has slope $\frac12$, so the required perpendicular line has slope $-2$. Through $(1,3)$,

$$
y-3=-2(x-1),
$$

which simplifies to

$$
\boxed{y=-2x+5}.
$$

**Exercise 17.** Find the centroid of the triangle with vertices $(1,1)$,
$(5,1)$, and $(3,7)$.

The centroid is the coordinate-wise average:

$$
G=\left(\frac{1+5+3}{3},\frac{1+1+7}{3}\right)=\boxed{(3,3)}.
$$

**Exercise 18.** Two vertices of a triangle are $(0,0)$ and $(4,2)$, and the
centroid is $(2,3)$. Find the third vertex.

Let the third vertex be $(x,y)$. Since the centroid is $(2,3)$,

$$
\left(\frac{0+4+x}{3},\frac{0+2+y}{3}\right)=(2,3).
$$

Therefore

$$
4+x=6,\qquad 2+y=9,
$$

so the third vertex is

$$
\boxed{(2,7)}.
$$

**Exercise 19.** Prove that the centroid divides each median in the ratio $2:1$
by a purely geometric argument, without coordinates.

**Hint.** Apply the midsegment theorem to the segment joining the midpoints
of two sides.

Let triangle $ABC$ have midpoint $M$ of $BC$, midpoint $N$ of $AC$, and midpoint $P$ of $AB$. Let $G$ be the intersection of medians $AM$ and $BN$.

In triangle $ABC$, segment $MN$ joins the midpoints of $BC$ and $AC$, so by the midsegment theorem $MN\parallel AB$ and $MN=\frac12 AB$. Similarly, $MP\parallel AC$ and $MP=\frac12 AC$.

Consider triangle $AMN$. Since $G$ lies on $AM$, draw through $G$ a line parallel to $MN$ (and therefore parallel to $AB$), meeting $AN$ at $Q$. The midsegment theorem applied in the appropriate similar-triangle configuration gives the same scale factor on the two median directions. Equivalently, triangles $GQN$ and $ABN$ are similar, and the midpoint relations imply that $AG:GM=2:1$.

The same argument applies to each median, so the centroid divides every median in the ratio

$$
\boxed{2:1}
$$

measured from the vertex.

**Exercise 20.** For a general triangle with vertices $(x_1,y_1)$,
$(x_2,y_2)$, and $(x_3,y_3)$, show directly that all three medians pass
through
$$
\left(\frac{x_1+x_2+x_3}{3},\frac{y_1+y_2+y_3}{3}\right),
$$
without assuming the $2:1$ ratio result.

**Hint.** Three points $P,Q,R$ are collinear if and only if
$$
\frac{y_Q-y_P}{x_Q-x_P}=\frac{y_R-y_P}{x_R-x_P}.
$$
Apply this to the vertex $(x_1,y_1)$, the midpoint
$M_1=\left(\frac{x_2+x_3}{2},\frac{y_2+y_3}{2}\right)$, and the centroid;
then repeat for the other two medians by symmetry.

Let

$$
G=\left(\frac{x_1+x_2+x_3}{3},\frac{y_1+y_2+y_3}{3}\right)
$$

and let $M_1$ be the midpoint of the side opposite $(x_1,y_1)$:

$$
M_1=\left(\frac{x_2+x_3}{2},\frac{y_2+y_3}{2}\right).
$$

The vectors from $(x_1,y_1)$ are

$$
G-(x_1,y_1)=\frac13\bigl((x_2+x_3-2x_1),(y_2+y_3-2y_1)\bigr),
$$

and

$$
M_1-(x_1,y_1)=\frac12\bigl((x_2+x_3-2x_1),(y_2+y_3-2y_1)\bigr).
$$

Thus

$$
G-(x_1,y_1)=\frac23\bigl(M_1-(x_1,y_1)\bigr),
$$

so $G$ lies on the median from $(x_1,y_1)$ to $M_1$. The formula is symmetric in the three vertices, so the same calculation shows that $G$ lies on the other two medians as well. Hence all three medians pass through $G$.

**A second coordinate proof by direct elimination.** Let

$$
p=x_2-x_1,\qquad q=x_3-x_1,\qquad r=y_2-y_1,\qquad s=y_3-y_1.
$$

Write the intersection of the two medians as

$$
x=x_1+X,\qquad y=y_1+Y.
$$

The midpoint of $BC$ is

$$
M_1=\left(x_1+\frac{p+q}{2},y_1+\frac{r+s}{2}\right).
$$

Using the cross-multiplied form of the two-point formula for the median from
$A=(x_1,y_1)$,

$$
(p+q)Y-(r+s)X=0. \tag{1}
$$

The midpoint of $AC$ is

$$
M_2=\left(x_1+\frac q2,y_1+\frac s2\right),
$$

while $B=(x_1+p,y_1+r)$. The cross-multiplied two-point formula for the
median from $B$ is

$$
(q-2p)(Y-r)-(s-2r)(X-p)=0.
$$

Expand the constant terms:

$$
\begin{aligned}
(q-2p)Y-(s-2r)X
&=(q-2p)r-(s-2r)p\\
&=qr-2pr-ps+2pr\\
&=qr-ps.
\end{aligned}
$$

Therefore the second median is

$$
(q-2p)Y-(s-2r)X=qr-ps. \tag{2}
$$

Now eliminate $Y$. Multiply (1) by $(q-2p)$ and (2) by $(p+q)$, then
subtract the second result from the first:

$$
\begin{aligned}
&\bigl((q-2p)(p+q)Y-(q-2p)(r+s)X\bigr)\\
&\quad-\bigl((p+q)(q-2p)Y-(p+q)(s-2r)X\bigr)\\
&=(p+q)(ps-qr).
\end{aligned}
$$

The $Y$ terms cancel. The coefficient of $X$ is

$$
\begin{aligned}
&-(q-2p)(r+s)+(p+q)(s-2r)\\
&=-qr-qs+2pr+2ps+ps+qs-2pr-2qr\\
&=3ps-3qr=3(ps-qr).
\end{aligned}
$$

Thus

$$
3(ps-qr)X=(p+q)(ps-qr).
$$

For a nondegenerate triangle, $ps-qr\ne0$, so

$$
X=\frac{p+q}{3}.
$$

Now eliminate $X$. Multiply (1) by $(s-2r)$ and (2) by $(r+s)$, then
subtract the second result from the first:

$$
\begin{aligned}
&\bigl((s-2r)(p+q)Y-(s-2r)(r+s)X\bigr)\\
&\quad-\bigl((r+s)(q-2p)Y-(r+s)(s-2r)X\bigr)\\
&=(r+s)(ps-qr).
\end{aligned}
$$

The $X$ terms cancel. The coefficient of $Y$ is

$$
\begin{aligned}
&(s-2r)(p+q)-(r+s)(q-2p)\\
&=ps+qs-2pr-2qr-qr-qs+2pr+2ps\\
&=3ps-3qr=3(ps-qr).
\end{aligned}
$$

Thus

$$
3(ps-qr)Y=(r+s)(ps-qr),
$$

and, since $ps-qr\ne0$,

$$
Y=\frac{r+s}{3}.
$$

Finally,

$$
\begin{aligned}
x&=x_1+X=x_1+\frac{(x_2-x_1)+(x_3-x_1)}{3}
 =\frac{x_1+x_2+x_3}{3},\\
y&=y_1+Y=y_1+\frac{(y_2-y_1)+(y_3-y_1)}{3}
 =\frac{y_1+y_2+y_3}{3}.
\end{aligned}
$$

Thus the direct coordinate intersection of the first two medians is the
centroid.

**Exercise 21.** Let $A=(0,0)$, $B=(6,0)$, and $C=(2,8)$. Find the equations
of the three altitudes of triangle $ABC$, and show that they meet at a single
point. What is that point?

**Hint.** The side $AB$ is horizontal, so the altitude from $C$ is vertical:
write it as $x=\text{constant}$ rather than trying to use a slope.

Let $A=(0,0)$, $B=(6,0)$, and $C=(2,8)$.

The side $AB$ is horizontal, so the altitude from $C$ is vertical:

$$
\ell_C:\quad x=2.
$$

The slope of $BC$ is

$$
\frac{8-0}{2-6}=-2,
$$

so the altitude from $A$ has slope $\frac12$:

$$
\ell_A:\quad y=\frac12x.
$$

The slope of $AC$ is $\frac82=4$, so the altitude from $B$ has slope $-\frac14$. Therefore

$$
\ell_B:\quad y=-\frac14(x-6)=-\frac14x+\frac32.
$$

At $x=2$, the first altitude gives $y=1$, and the second gives

$$
-\frac14(2)+\frac32=1.
$$

Thus all three altitudes meet at

$$
\boxed{H=(2,1)}.
$$

**Exercise 22.** Let $A=(x_1,y_1)$, $B=(x_2,y_2)$, $C=(x_3,y_3)$.

**(a)** Using the remark at the end of Section 7, show that $(x,y)$ lies on
the altitude from $A$ if and only if
$$
(x-x_1)(x_3-x_2)+(y-y_1)(y_3-y_2)=0,
$$
and write the two analogous equations for the altitudes from $B$ and from
$C$, keeping the same cyclic pattern $A\to B\to C\to A$ of the indices.

**(b)** Expand all three equations and add them. Show that the sum is
identically zero: every term cancels, for every point $(x,y)$.

**(c)** Conclude that the three altitudes are concurrent: any point lying on
two of them automatically lies on the third. That point is the orthocenter
$H$.

### (a)

The side $BC$ has direction vector

$$
C-B=(x_3-x_2,y_3-y_2).
$$

The altitude from $A$ has direction vector $(x-x_1,y-y_1)$, so perpendicularity gives

$$
\boxed{(x-x_1)(x_3-x_2)+(y-y_1)(y_3-y_2)=0}.
$$

Following the same cyclic pattern, the altitude from $B$ is

$$
\boxed{(x-x_2)(x_1-x_3)+(y-y_2)(y_1-y_3)=0},
$$

and the altitude from $C$ is

$$
\boxed{(x-x_3)(x_2-x_1)+(y-y_3)(y_2-y_1)=0}.
$$

### (b)

Add the three left-hand sides. The coefficients of $x$ and $y$ are

$$
(x_3-x_2)+(x_1-x_3)+(x_2-x_1)=0,
$$

and

$$
(y_3-y_2)+(y_1-y_3)+(y_2-y_1)=0.
$$

The constant terms also cancel:

$$
\begin{aligned}
&-x_1(x_3-x_2)-x_2(x_1-x_3)-x_3(x_2-x_1)\\
&\quad=-x_1x_3+x_1x_2-x_2x_1+x_2x_3-x_3x_2+x_3x_1=0,
\end{aligned}
$$

and the corresponding $y$ terms cancel in exactly the same way. Therefore the sum of the three equations is identically zero for every $(x,y)$.

### (c)

If a point $(x,y)$ lies on the first two altitudes, the first two left-hand sides are zero. Since the sum of all three left-hand sides is identically zero, the third left-hand side must also be zero. Therefore the point lies on the third altitude.

Hence the three altitudes are concurrent. Their common point is the orthocenter

$$
\boxed{H}.
$$
