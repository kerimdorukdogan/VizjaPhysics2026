# 🧭 Problem 3 – Path Intersection

Alice moves along the path:

$$
A(t) = (2 + t,\; 8 - 3t)
$$

Bob moves along the path:

$$
B(t) = (2t - 1,\; 2t + 2)
$$

We want to determine:

- whether their paths intersect
- if they collide, when and where it happens

---

# 📌 Step 1: Set positions equal

For a collision, both coordinates must be equal at the same time.

So we set:

$$
2 + t = 2t - 1
$$

and

$$
8 - 3t = 2t + 2
$$

---

# 🔍 Step 2: Solve the first equation

$$
2 + t = 2t - 1
$$

Subtract \(t\):

$$
2 = t - 1
$$

Add 1:

$$
t = 3
$$

---

# ✏️ Step 3: Check the second equation

Substitute \(t = 3\):

Left side:

$$
8 - 3(3) = 8 - 9 = -1
$$

Right side:

$$
2(3) + 2 = 6 + 2 = 8
$$

These are **not equal**.

---

# ❗ Step 4: Conclusion

Because the two equations do not give the same value, there is **no common time** when both coordinates match.

So the paths **do not intersect at the same time**.

✔ Alice and Bob **do not collide**.

---

# 💡 Interpretation

Even though their geometric paths might cross in space, they arrive there at **different times**.

So physically they **never meet**.

---

# 🚀 Final Answer

Alice and Bob **do not collide**, because there is no time \(t\) that satisfies both position equations simultaneously.