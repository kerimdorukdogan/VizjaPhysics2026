# 🚀 Problem 1 — Vector Algebra

We are given two vectors in three-dimensional space:

$$
\vec{a} = (2,1,-3)
$$

$$
\vec{b} = (4,-2,1)
$$

We calculate:

- magnitude of both vectors
- dot product
- cross product
- angle between the vectors

---

# 📌 1. Magnitude of vectors

Magnitude formula:

$$
|\vec{v}|=\sqrt{x^2+y^2+z^2}
$$

### Vector a

$$
|\vec a|=\sqrt{2^2+1^2+(-3)^2}
$$

$$
|\vec a|=\sqrt{4+1+9}
$$

$$
|\vec a|=\sqrt{14}
$$

### Vector b

$$
|\vec b|=\sqrt{4^2+(-2)^2+1^2}
$$

$$
|\vec b|=\sqrt{16+4+1}
$$

$$
|\vec b|=\sqrt{21}
$$

---

# 📌 2. Dot Product

Formula:

$$
\vec a \cdot \vec b
=
a_x b_x + a_y b_y + a_z b_z
$$

Compute:

$$
(2)(4)+(1)(-2)+(-3)(1)
$$

$$
8-2-3
$$

$$
=3
$$

---

# 📌 3. Cross Product

Using determinant form:

$$
\vec a \times \vec b
=
\begin{vmatrix}
i & j & k \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

Compute components:

### i component

$$
1\cdot1 - (-3)(-2)
=
1-6
=
-5
$$

### j component

$$
2\cdot1 - (-3)(4)
=
2+12
=
14
$$

### k component

$$
2(-2) - 1(4)
=
-4-4
=
-8
$$

Result:

$$
\vec a \times \vec b =
(-5,-14,-8)
$$

---

# 📌 4. Angle Between Vectors

Formula:

$$
\cos\theta =
\frac{\vec a \cdot \vec b}{|\vec a||\vec b|}
$$

Substitute values:

$$
\cos\theta =
\frac{3}{\sqrt{14}\sqrt{21}}
$$

$$
\cos\theta =
\frac{3}{\sqrt{294}}
$$

Angle:

$$
\theta = \cos^{-1}\left(\frac{3}{\sqrt{294}}\right)
$$

Numerically:

$$
\theta \approx 79.9^\circ
$$

---

# 🎯 Final Results

| Quantity | Result |
|------|------|
| Magnitude of a | √14 |
| Magnitude of b | √21 |
| Dot product | 3 |
| Cross product | (-5, -14, -8) |
| Angle between vectors | ≈ 79.9° |