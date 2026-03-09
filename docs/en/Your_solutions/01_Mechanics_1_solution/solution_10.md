# 🌀 Problem 10 – Kinematics

A point moves according to:

$$
\vec{r}(t) = (a\cos(\omega t),\; b\sin(\omega t),\; bt)
$$

where \(a\), \(b\), and \(\omega\) are positive constants.

We want to:

- find the trajectory equation
- compute the path length from \(t=0\) to \(t=t_0\)
- describe the trajectory and special cases

---

# 📌 Step 1: Write the coordinate equations

From the vector form:

$$
x(t) = a\cos(\omega t)
$$

$$
y(t) = b\sin(\omega t)
$$

$$
z(t) = bt
$$

---

# 🔍 Step 2: Find the trajectory equation in the \(xy\)-plane

We eliminate \(t\) between \(x\) and \(y\).

From:

$$
x = a\cos(\omega t)
\quad\Rightarrow\quad
\frac{x}{a} = \cos(\omega t)
$$

From:

$$
y = b\sin(\omega t)
\quad\Rightarrow\quad
\frac{y}{b} = \sin(\omega t)
$$

Now use:

$$
\cos^2(\omega t) + \sin^2(\omega t) = 1
$$

So:

$$
\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = 1
$$

This means that the projection in the \(xy\)-plane is an ellipse.

Since:

$$
z = bt
$$

increases linearly with time, the full trajectory is an **elliptical helix**.

---

# ✏️ Step 3: Compute the velocity vector

Differentiate \(\vec{r}(t)\):

$$
\vec{v}(t) = \frac{d\vec{r}}{dt}
$$

So:

$$
\vec{v}(t) =
(-a\omega \sin(\omega t),\; b\omega \cos(\omega t),\; b)
$$

---

# 📏 Step 4: Compute the speed

The speed is the magnitude of velocity:

$$
|\vec{v}(t)| =
\sqrt{(-a\omega \sin(\omega t))^2 + (b\omega \cos(\omega t))^2 + b^2}
$$

So:

$$
|\vec{v}(t)| =
\sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}
$$

This is the general speed formula.

---

# 🧮 Step 5: Compute the path length

The path length from \(t=0\) to \(t=t_0\) is:

$$
L = \int_0^{t_0} |\vec{v}(t)|\,dt
$$

Therefore:

$$
\boxed{
L =
\int_0^{t_0}
\sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}\, dt
}
$$

This is the exact arc-length expression.

---

# 💡 Step 6: Special case \(a=b\)

If:

$$
a=b
$$

then the ellipse becomes a circle, and the trajectory becomes a **circular helix**.

In that case the speed simplifies to:

$$
|\vec{v}(t)| =
\sqrt{a^2\omega^2(\sin^2(\omega t)+\cos^2(\omega t)) + b^2}
$$

Since:

$$
\sin^2(\omega t)+\cos^2(\omega t)=1
$$

we get:

$$
|\vec{v}(t)| = \sqrt{a^2\omega^2 + b^2}
$$

which is constant.

So the path length becomes:

$$
L = \sqrt{a^2\omega^2 + b^2}\; t_0
$$

---

# ✅ Final Results

Trajectory in the \(xy\)-plane:

$$
\boxed{\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = 1}
$$

Full trajectory:

$$
\boxed{\text{elliptical helix}}
$$

Velocity vector:

$$
\boxed{
\vec{v}(t)=(-a\omega \sin(\omega t),\; b\omega \cos(\omega t),\; b)
}
$$

Path length:

$$
\boxed{
L =
\int_0^{t_0}
\sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}\, dt
}
$$

Special case \(a=b\):

$$
\boxed{L = \sqrt{a^2\omega^2 + b^2}\; t_0}
$$

---

# 🚀 Final Answer

The point moves on an **elliptical helix** with projection:

$$
\boxed{\left(\frac{x}{a}\right)^2 + \left(\frac{y}{b}\right)^2 = 1}
$$

and the general path length is:

$$
\boxed{
L =
\int_0^{t_0}
\sqrt{a^2\omega^2 \sin^2(\omega t) + b^2\omega^2 \cos^2(\omega t) + b^2}\, dt
}
$$