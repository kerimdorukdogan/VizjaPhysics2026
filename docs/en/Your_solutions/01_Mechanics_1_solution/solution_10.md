# 🌀 Problem 10 — Kinematics

The motion of a point \(M\) is given by:

$$
\vec{r}(t) = (a\cos(\omega t),\; b\sin(\omega t),\; bt)
$$

where \(a\), \(b\), and \(\omega\) are positive constants.

We want to determine:

- the trajectory
- the velocity vector
- the path length from \(t=0\) to \(t=t_0\)

---

## 📌 Given

| Coordinate | Expression |
|----------|------------|
| \(x(t)\) | $a\cos(\omega t)$ |
| \(y(t)\) | $b\sin(\omega t)$ |
| \(z(t)\) | $bt$ |

---

## 📈 Motion Sketch

```text
              z
              ↑
              |
              |        •
              |      •
              |    •
              |  •
              |•
             / 
            /     helical motion
           /
          +------------------------→ x
         /
        y
```

The point moves around the \(z\)-axis while also moving upward.  
This produces a **helical trajectory**.

---

## 🧠 Key Concepts

The \(x\) and \(y\) coordinates describe oscillatory motion:

$$
x = a\cos(\omega t)
$$

$$
y = b\sin(\omega t)
$$

The \(z\) coordinate increases linearly:

$$
z = bt
$$

So the point rotates in the horizontal plane while steadily moving upward.

Velocity is the derivative of position:

$$
\vec{v}(t) = \frac{d\vec{r}}{dt}
$$

The path length from \(0\) to \(t_0\) is:

$$
L = \int_0^{t_0} |\vec{v}(t)|\,dt
$$

---

## 🔍 Step-by-Step Solution

### 1️⃣ Find the trajectory in the \(xy\)-plane

We start with:

$$
x = a\cos(\omega t)
$$

$$
y = b\sin(\omega t)
$$

Divide by constants:

$$
\frac{x}{a} = \cos(\omega t)
$$

$$
\frac{y}{b} = \sin(\omega t)
$$

Now square both equations and add them:

$$
\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2
=
\cos^2(\omega t) + \sin^2(\omega t)
$$

Since:

$$
\cos^2(\omega t) + \sin^2(\omega t) = 1
$$

we obtain:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

This is the equation of an **ellipse** in the \(xy\)-plane.

Because \(z=bt\) increases with time, the full 3D trajectory is a **helix**.

---

### 2️⃣ Compute the velocity vector

Differentiate each coordinate with respect to time.

For the \(x\)-component:

$$
\frac{dx}{dt} = -a\omega \sin(\omega t)
$$

For the \(y\)-component:

$$
\frac{dy}{dt} = b\omega \cos(\omega t)
$$

For the \(z\)-component:

$$
\frac{dz}{dt} = b
$$

Therefore:

$$
\vec{v}(t) =
\left(
-a\omega \sin(\omega t),\;
b\omega \cos(\omega t),\;
b
\right)
$$

---

### 3️⃣ Compute the speed

The speed is the magnitude of the velocity vector:

$$
|\vec{v}(t)|
=
\sqrt{
\left(-a\omega \sin(\omega t)\right)^2
+
\left(b\omega \cos(\omega t)\right)^2
+
b^2
}
$$

Simplify:

$$
|\vec{v}(t)|
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

### 4️⃣ Compute the path length

The path length from \(t=0\) to \(t=t_0\) is:

$$
L = \int_0^{t_0} |\vec{v}(t)|\,dt
$$

So:

$$
L
=
\int_0^{t_0}
\sqrt{
a^2\omega^2\sin^2(\omega t)
+
b^2\omega^2\cos^2(\omega t)
+
b^2
}
\,dt
$$

This is the required expression for the distance traveled.

---

## 🎯 Final Results

| Quantity | Result |
|----------|--------|
| Projection in the \(xy\)-plane | $\frac{x^2}{a^2}+\frac{y^2}{b^2}=1$ |
| 3D trajectory | Helix |
| Velocity vector | $\left(-a\omega \sin(\omega t),\; b\omega \cos(\omega t),\; b\right)$ |
| Path length | $\int_0^{t_0} |\vec{v}(t)|\,dt$ |

---

## 💡 Interpretation

- In the \(xy\)-plane, the point moves along an **ellipse**.
- At the same time, the \(z\)-coordinate grows linearly.
- Combining circular/elliptic motion with vertical motion creates a **helical path**.

This is a standard example of **3D kinematics**.

---

## ✅ Final Answer

The projection in the \(xy\)-plane is:

$$
\frac{x^2}{a^2} + \frac{y^2}{b^2} = 1
$$

The velocity vector is:

$$
\vec{v}(t) =
\left(
-a\omega \sin(\omega t),\;
b\omega \cos(\omega t),\;
b
\right)
$$

The path length from \(0\) to \(t_0\) is:

$$
L
=
\int_0^{t_0}
\sqrt{
a^2\omega^2\sin^2(\omega t)
+
b^2\omega^2\cos^2(\omega t)
+
b^2
}
\,dt
$$