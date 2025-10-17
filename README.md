# 🎱 2-Dimensional Billiards

2-dimensional Billiards are studied in **abstract mathematics**, but their visual representation requires the use of **computer tools** which you will develop in this challenge.
These tools are a useful support to understand the math and make conjectures about the **long-term behaviour** of billiards.

---

## 💡 Description

Imagine a **convex polygonal billiard table**, where the billiard is frictionless and the ball travels at constant speed.
When it hits a wall, the ball reflects just like light does.

**Main question:**
What can you say about the long-term behaviour of the billiard depending on initial conditions and the shape of the table?

**Instructions:**
- Do **not animate** things first — draw a **static version** at time **T**.
- Then animate it in a **separate program**.
- Your code should be **flexible**:
  - Ask the user for the **shape of the table**.
  - Write code that **does not depend** on the shape.

---

## 🔍 Suggestions for Investigation

- Try various shapes:
  - Square
  - Rectangle
  - Regular *n*-gon (what is that?)
  - Non-convex shapes

- Can you generalize to **three dimensions** and animate it?
  - Animate it as if the situation is viewed from the **ball’s perspective**.
  - That could make a cool **video game** (astronaut simulator?).

- Can you generalize to **smooth shapes**, for example:
  - A circle
  - An ellipse
  - A hand-drawn closed curve

---

## ⚙️ Restrictions

- Code **mostly from scratch**.
- Use only:
  - **Python**
  - **NumPy**
  - **Matplotlib**
- Nothing fancier than that.

For animations, you’ll need:
```python
from matplotlib.animation import FuncAnimation
Then look up the documentation on Matplotlib’s website.
```

## 🕹️ Longer-Term Project

Can you integrate this kind of bouncing behaviour in a **2D or even 3D video game**?
Using the **pygame** library, integrate your physics into the game.

This kind of math is the **basis of a graphics game engine**, so the possibilities are endless and the difficulty level is as hard as you want it to be.

### 💡 Tips
- **Object-Oriented Programming (OOP)** is recommended.
- Be creative but use **realistic billiards**, not an emulation of physics.

---

## 🧑‍🏫 Need Help?

Ask a **math teacher** for help if you get stuck or have ideas you want to test.
