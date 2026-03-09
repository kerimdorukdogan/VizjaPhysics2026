# 🧭 Problem 7 – Elimination of Time and Interpretation of Acceleration

The motion is given in parametric form:

$$
x(t) = 2t^2
$$

$$
y(t) = 3t^3
$$

We want to:

- eliminate the parameter \(t\)
- describe the trajectory
- calculate \( \vec{v}(t) \), \( |\vec{v}(t)| \), \( \vec{a}(t) \), and \( |\vec{a}(t)| \)
- decide whether the acceleration is constant

---

# 📌 Step 1: Eliminate the parameter \(t\)

From

$$
x = 2t^2
$$

we get:

$$
t^2 = \frac{x}{2}
$$

So:

$$
t = \pm \sqrt{\frac{x}{2}}
$$

Now use

$$
y = 3t^3 = 3t \cdot t^2
$$

Substitute \( t^2 = \frac{x}{2} \):

$$
y = 3t \cdot \frac{x}{2}
$$

To remove the sign ambiguity cleanly, square the relation.

From:

$$
y = 3t^3
$$

we get:

$$
y^2 = 9t^6
$$

And since:

$$
t^2 = \frac{x}{2}
\quad\Rightarrow\quad
t^6 = \left(\frac{x}{2}\right)^3 = \frac{x^3}{8}
$$

So:

$$
y^2 = 9 \cdot \frac{x^3}{8}
$$

Therefore the trajectory is:

$$
\boxed{y^2 = \frac{9}{8}x^3}
$$

---

# ✏️ Step 2: Describe the trajectory

The curve

$$
y^2 = \frac{9}{8}x^3
$$

is a **semicubical parabola**.

Also, since

$$
x = 2t^2 \ge 0
$$

the motion exists only for:

$$
x \ge 0
$$

So the trajectory lies on the **right side** of the plane.

---

# 🚀 Step 3: Find the velocity vector

Velocity is the derivative of position:

$$
\vec{v}(t) = \left(\frac{dx}{dt}, \frac{dy}{dt}\right)
$$

Differentiate:

$$
\frac{dx}{dt} = 4t
$$

$$
\frac{dy}{dt} = 9t^2
$$

So:

$$
\boxed{\vec{v}(t) = (4t,\; 9t^2)}
$$

---

# 📏 Step 4: Find the speed

The magnitude of velocity is:

$$
|\vec{v}(t)| = \sqrt{(4t)^2 + (9t^2)^2}
$$

$$
|\vec{v}(t)| = \sqrt{16t^2 + 81t^4}
$$

Factor:

$$
|\vec{v}(t)| = \sqrt{t^2(16 + 81t^2)}
$$

$$
\boxed{|\vec{v}(t)| = |t|\sqrt{16 + 81t^2}}
$$

---

# 🧮 Step 5: Find the acceleration vector

Acceleration is the derivative of velocity:

$$
\vec{a}(t) = \left(\frac{d^2x}{dt^2}, \frac{d^2y}{dt^2}\right)
$$

Differentiate again:

$$
\frac{d^2x}{dt^2} = 4
$$

$$
\frac{d^2y}{dt^2} = 18t
$$

So:

$$
\boxed{\vec{a}(t) = (4,\; 18t)}
$$

---

# 📐 Step 6: Find the magnitude of acceleration

$$
|\vec{a}(t)| = \sqrt{4^2 + (18t)^2}
$$

$$
|\vec{a}(t)| = \sqrt{16 + 324t^2}
$$

So:

$$
\boxed{|\vec{a}(t)| = \sqrt{16 + 324t^2}}
$$

---

# ❓ Step 7: Is the acceleration constant?

The acceleration vector is:

$$
\vec{a}(t) = (4,\; 18t)
$$

Its second component depends on time, so the vector changes with time.

Therefore:

❌ The acceleration is **not constant**.

---

# ✅ Final Results

Trajectory:

$$
\boxed{y^2 = \frac{9}{8}x^3}
$$

Velocity:

$$
\boxed{\vec{v}(t) = (4t,\; 9t^2)}
$$

Speed:

$$
\boxed{|\vec{v}(t)| = |t|\sqrt{16 + 81t^2}}
$$

Acceleration:

$$
\boxed{\vec{a}(t) = (4,\; 18t)}
$$

Acceleration magnitude:

$$
\boxed{|\vec{a}(t)| = \sqrt{16 + 324t^2}}
$$

Acceleration constant?

$$
\boxed{\text{No, it is not constant}}
$$