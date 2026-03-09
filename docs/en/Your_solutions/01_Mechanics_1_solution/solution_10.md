# 🌀 Problem 10 — Kinematics

The position of a point is

$$
\vec r(t) = (a\cos(\omega t),\; b\sin(\omega t),\; bt)
$$

where \(a,b,\omega\) are positive constants.

---

# 1️⃣ Trajectory

From the parametric equations

$$
x = a\cos(\omega t)
$$

$$
y = b\sin(\omega t)
$$

Divide:

$$
\frac{x}{a} = \cos(\omega t)
$$

$$
\frac{y}{b} = \sin(\omega t)
$$

Square both equations and add them:

$$
\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2
=
\cos^2(\omega t) + \sin^2(\omega t)
$$

Using the trigonometric identity

$$
\cos^2(\omega t) + \sin^2(\omega t) = 1
$$

we obtain

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

Therefore the projection in the \(xy\)-plane is an **ellipse**.

Since

$$
z = bt
$$

increases linearly with time, the full trajectory is a **helix**.

---

# 2️⃣ Velocity Vector

Velocity is the derivative of position.

Differentiate each component.

### x-component

$$
\frac{dx}{dt} = -a\omega\sin(\omega t)
$$

### y-component

$$
\frac{dy}{dt} = b\omega\cos(\omega t)
$$

### z-component

$$
\frac{dz}{dt} = b
$$

Therefore

$$
\vec v(t) =
(-a\omega\sin(\omega t),\; b\omega\cos(\omega t),\; b)
$$

---

# 3️⃣ Speed

The magnitude of velocity is

$$
|\vec v(t)|
=
\sqrt{
(-a\omega\sin(\omega t))^2 +
(b\omega\cos(\omega t))^2 +
b^2
}
$$

Simplify:

$$
|\vec v(t)|
=
\sqrt{
a^2\omega^2\sin^2(\omega t)
+
b^2\omega^2\cos^2(\omega t)
+
b^2
}
$$

---

# 4️⃣ Path Length

The path length from \(0\) to \(t_0\) is

$$
L =
\int_0^{t_0}
\sqrt{
a^2\omega^2\sin^2(\omega t)
+
b^2\omega^2\cos^2(\omega t)
+
b^2
}\, dt
$$

---

# 🎯 Final Results

| Quantity | Result |
|--------|--------|
| Projection in xy-plane | ellipse |
| Equation | \(x^2/a^2 + y^2/b^2 = 1\) |
| 3D trajectory | helix |
| Velocity | \((-a\omega\sin(\omega t), b\omega\cos(\omega t), b)\) |
| Path length | integral above |