# ⏳ Problem 6 – Variable Velocity

The velocity of the object is given by:

$$
v(t) = t^2 + 2t - 5
$$

We also know that at time:

$$
t = 0
$$

the position is:

$$
x(0) = 4
$$

We want to find:

- the **position** at \( t = 3 \)
- the **acceleration** at \( t = 3 \)

---

# 📌 Step 1: Find the position function

Velocity is the derivative of position:

$$
v(t) = \frac{dx}{dt}
$$

So:

$$
\frac{dx}{dt} = t^2 + 2t - 5
$$

To find position, integrate:

$$
x(t) = \int (t^2 + 2t - 5)\,dt
$$

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + C
$$

---

# 🔍 Step 2: Use the initial condition

We know:

$$
x(0) = 4
$$

Substitute \( t = 0 \):

$$
4 = \frac{0^3}{3} + 0^2 - 5(0) + C
$$

$$
4 = C
$$

So the position function is:

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

---

# ✏️ Step 3: Find the position at \( t = 3 \)

Substitute \( t = 3 \):

$$
x(3) = \frac{3^3}{3} + 3^2 - 5(3) + 4
$$

$$
x(3) = \frac{27}{3} + 9 - 15 + 4
$$

$$
x(3) = 9 + 9 - 15 + 4
$$

$$
x(3) = 7
$$

So the position at \( t = 3 \) is:

$$
x(3) = 7
$$

---

# 🧮 Step 4: Find the acceleration

Acceleration is the derivative of velocity:

$$
a(t) = \frac{dv}{dt}
$$

Given:

$$
v(t) = t^2 + 2t - 5
$$

Differentiate:

$$
a(t) = 2t + 2
$$

Now substitute \( t = 3 \):

$$
a(3) = 2(3) + 2
$$

$$
a(3) = 6 + 2 = 8
$$

So:

$$
a(3) = 8
$$

---

# ✅ Final Results

Position at \( t = 3 \):

$$
x(3) = 7
$$

Acceleration at \( t = 3 \):

$$
a(3) = 8
$$

---

# 💡 Interpretation

- The velocity changes with time, so the motion is **not uniform**
- By integrating velocity, we get the position
- By differentiating velocity, we get the acceleration

✔ This is a standard relation between position, velocity, and acceleration.

---

# 🚀 Final Answer

$$
\boxed{x(3) = 7}
$$

$$
\boxed{a(3) = 8}
$$