# 🚀 Problem 1 – Projectile Motion

A projectile is fired from the ground with initial velocity:

$$
v_0 = 100 \text{ m/s}
$$

at angle:

$$
\theta = 37^\circ
$$

We assume **no air resistance**.

We want to find:

- the differential equations of motion
- the time of flight
- the maximum height
- the range

---

# 📌 Step 1: Resolve the initial velocity into components

Horizontal component:

$$
v_{0x} = v_0 \cos\theta
$$

Vertical component:

$$
v_{0y} = v_0 \sin\theta
$$

Substitute the values:

$$
v_{0x} = 100\cos 37^\circ
$$

$$
v_{0y} = 100\sin 37^\circ
$$

Using approximate values:

$$
\cos 37^\circ \approx 0.8, \qquad \sin 37^\circ \approx 0.6
$$

So:

$$
v_{0x} \approx 80 \text{ m/s}
$$

$$
v_{0y} \approx 60 \text{ m/s}
$$

---

# 🧭 Step 2: Write the differential equations of motion

In projectile motion without air resistance:

- horizontal acceleration is zero
- vertical acceleration is due to gravity

So:

$$
\frac{d^2x}{dt^2} = 0
$$

$$
\frac{d^2y}{dt^2} = -g
$$

where:

$$
g = 9.81 \text{ m/s}^2
$$

From these, the velocity components are:

$$
\frac{dx}{dt} = v_{0x}
$$

$$
\frac{dy}{dt} = v_{0y} - gt
$$

And the position equations are:

$$
x(t) = v_{0x} t
$$

$$
y(t) = v_{0y} t - \frac{1}{2}gt^2
$$

So approximately:

$$
x(t) = 80t
$$

$$
y(t) = 60t - 4.905t^2
$$

---

# ⏱️ Step 3: Determine the time of flight

The projectile returns to the ground when:

$$
y(t) = 0
$$

So:

$$
60t - 4.905t^2 = 0
$$

Factor out \(t\):

$$
t(60 - 4.905t) = 0
$$

Thus:

$$
t = 0
\quad \text{or} \quad
t = \frac{60}{4.905}
$$

So the total time of flight is:

$$
T \approx 12.23 \text{ s}
$$

---

# 📈 Step 4: Determine the maximum height

At the highest point, vertical velocity becomes zero:

$$
v_y = v_{0y} - gt = 0
$$

So:

$$
60 - 9.81t = 0
$$

$$
t = \frac{60}{9.81} \approx 6.12 \text{ s}
$$

Now substitute this into \(y(t)\):

$$
H_{\max} = 60(6.12) - 4.905(6.12)^2
$$

$$
H_{\max} \approx 183.5 \text{ m}
$$

We can also use the standard formula:

$$
H_{\max} = \frac{v_{0y}^2}{2g}
$$

$$
H_{\max} = \frac{60^2}{2 \cdot 9.81}
= \frac{3600}{19.62}
\approx 183.5 \text{ m}
$$

---

# 📏 Step 5: Determine the range

The range is:

$$
R = v_{0x} \cdot T
$$

So:

$$
R = 80 \cdot 12.23
$$

$$
R \approx 978.4 \text{ m}
$$

We can also use:

$$
R = \frac{v_0^2 \sin(2\theta)}{g}
$$

which gives approximately the same result.

---

# ✅ Final Results

Differential equations:

$$
\frac{d^2x}{dt^2} = 0
$$

$$
\frac{d^2y}{dt^2} = -g
$$

Time of flight:

$$
T \approx 12.23 \text{ s}
$$

Maximum height:

$$
H_{\max} \approx 183.5 \text{ m}
$$

Range:

$$
R \approx 978.4 \text{ m}
$$

---

# 💡 Interpretation

- The horizontal motion is uniform because there is no horizontal acceleration
- The vertical motion is uniformly accelerated downward because of gravity
- The projectile rises, slows down vertically, reaches a peak, and then falls back down

✔ This is a standard 2D projectile motion problem.

---

# 🚀 Final Answer

$$
\boxed{\frac{d^2x}{dt^2}=0,\qquad \frac{d^2y}{dt^2}=-g}
$$

$$
\boxed{T \approx 12.23 \text{ s}}
$$

$$
\boxed{H_{\max} \approx 183.5 \text{ m}}
$$

$$
\boxed{R \approx 978.4 \text{ m}}
$$