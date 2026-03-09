# 🧮 Problem 4 – Vector Calculus

The position of the object is given by:

$$
\vec{r}(t) = (3t^2)\,\hat{i} + (5t - 8t^2)\,\hat{j}
$$

We want to find:

- the **velocity vector** \( \vec{v}(t) \)
- the **acceleration vector** \( \vec{a}(t) \)

as functions of time.

---

# 📌 Step 1: Recall the definitions

Velocity is the derivative of position with respect to time:

$$
\vec{v}(t) = \frac{d\vec{r}(t)}{dt}
$$

Acceleration is the derivative of velocity:

$$
\vec{a}(t) = \frac{d\vec{v}(t)}{dt}
$$

---

# 🔍 Step 2: Differentiate the position vector

Given:

$$
\vec{r}(t) = (3t^2)\,\hat{i} + (5t - 8t^2)\,\hat{j}
$$

Differentiate each component separately.

For the \( \hat{i} \)-component:

$$
\frac{d}{dt}(3t^2) = 6t
$$

For the \( \hat{j} \)-component:

$$
\frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

So the velocity vector is:

$$
\vec{v}(t) = 6t\,\hat{i} + (5 - 16t)\,\hat{j}
$$

---

# ✏️ Step 3: Differentiate again to get acceleration

Now differentiate the velocity vector:

$$
\vec{v}(t) = 6t\,\hat{i} + (5 - 16t)\,\hat{j}
$$

For the \( \hat{i} \)-component:

$$
\frac{d}{dt}(6t) = 6
$$

For the \( \hat{j} \)-component:

$$
\frac{d}{dt}(5 - 16t) = -16
$$

So the acceleration vector is:

$$
\vec{a}(t) = 6\,\hat{i} - 16\,\hat{j}
$$

---

# ✅ Final Result

The velocity vector is:

$$
\vec{v}(t) = 6t\,\hat{i} + (5 - 16t)\,\hat{j}
$$

The acceleration vector is:

$$
\vec{a}(t) = 6\,\hat{i} - 16\,\hat{j}
$$

---

# 💡 Interpretation

- The velocity changes with time in both directions
- The acceleration is constant
- The object accelerates positively in the \(x\)-direction
- The object accelerates negatively in the \(y\)-direction

✔ This is a standard vector differentiation problem.

---

# 🚀 Final Answer

$$
\boxed{\vec{v}(t) = 6t\,\hat{i} + (5 - 16t)\,\hat{j}}
$$

$$
\boxed{\vec{a}(t) = 6\,\hat{i} - 16\,\hat{j}}
$$