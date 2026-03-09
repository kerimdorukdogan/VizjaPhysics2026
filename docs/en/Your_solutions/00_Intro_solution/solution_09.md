# 🧲 Problem 9 – Vector Derivatives

We are given the position vector:

$$
\vec{r}(t) = (3t^2,\; 2t,\; 5)
$$

We want to find:

- the **velocity vector** \( \vec{v}(t) \)
- the **acceleration vector** \( \vec{a}(t) \)

---

# 📌 Step 1: Find the velocity vector

Velocity is the derivative of position with respect to time:

$$
\vec{v}(t) = \frac{d\vec{r}(t)}{dt}
$$

Differentiate each component separately:

$$
\vec{r}(t) = (3t^2,\; 2t,\; 5)
$$

So:

$$
\frac{d}{dt}(3t^2) = 6t
$$

$$
\frac{d}{dt}(2t) = 2
$$

$$
\frac{d}{dt}(5) = 0
$$

Therefore:

$$
\vec{v}(t) = (6t,\; 2,\; 0)
$$

---

# 🔍 Step 2: Find the acceleration vector

Acceleration is the derivative of velocity with respect to time:

$$
\vec{a}(t) = \frac{d\vec{v}(t)}{dt}
$$

Differentiate each component of \( \vec{v}(t) \):

$$
\vec{v}(t) = (6t,\; 2,\; 0)
$$

So:

$$
\frac{d}{dt}(6t) = 6
$$

$$
\frac{d}{dt}(2) = 0
$$

$$
\frac{d}{dt}(0) = 0
$$

Therefore:

$$
\vec{a}(t) = (6,\; 0,\; 0)
$$

---

# ✅ Final Result

The velocity vector is:

$$
\vec{v}(t) = (6t,\; 2,\; 0)
$$

The acceleration vector is:

$$
\vec{a}(t) = (6,\; 0,\; 0)
$$

---

# 💡 Interpretation

- The object moves with changing speed in the **x-direction**
- It has constant velocity in the **y-direction**
- It has no motion in the **z-direction**
- The acceleration is constant and points only along the **x-axis**

---

# 🚀 Final Answer

$$
\boxed{\vec{v}(t) = (6t,\; 2,\; 0)}
$$

$$
\boxed{\vec{a}(t) = (6,\; 0,\; 0)}
$$