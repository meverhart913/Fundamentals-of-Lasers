---
module: 1
lesson: 1
title: What Is Light?
difficulty: Beginner
estimated_time: 45–60 minutes
prerequisites: None
last_updated: 2026-07-07
author: OpenAI ChatGPT
version: 1.0
---

# Module 1 – Laser Fundamentals

# Lesson 1 – What Is Light?

> *"Every laser ever built—from the first ruby laser to today's multi-kilowatt fiber lasers—exists to control one thing: light. Before we can understand lasers, we must first understand what light actually is."*

---

# Table of Contents

- [Learning Objectives](#learning-objectives)
- [Why This Lesson Matters](#why-this-lesson-matters)
- [Review](#review)
- [Intuition Before Physics](#intuition-before-physics)
- [Math Toolbox 1.1 – Scientific Notation](#math-toolbox-11--scientific-notation)
- [The Speed of Light](#the-speed-of-light)
- [What Makes Light Different?](#what-makes-light-different)
- [Looking Ahead](#looking-ahead)

---

# Learning Objectives

By the end of this lesson you should be able to:

- Explain what light is in plain English.
- Describe how light differs from sound.
- Explain why light can travel through empty space.
- Understand why light is considered electromagnetic radiation.
- Use scientific notation comfortably.
- Convert between engineering prefixes.
- Explain why wavelength is the most important specification on many laser datasheets.

---

# Why This Lesson Matters

Every laser datasheet starts with a wavelength.

Examples include:

| Laser | Wavelength |
|---------|-----------:|
| HeNe | 632.8 nm |
| Nd:YAG | 1064 nm |
| Yb Fiber | ~1070 nm |
| Er:YAG | 2940 nm |
| CO₂ | 10.6 μm |

Why is wavelength always listed first?

Because wavelength determines nearly everything that follows.

It influences:

- Material absorption
- Pump source selection
- Beam delivery
- Optical coatings
- Eye safety
- Fiber compatibility
- Nonlinear optics
- Industrial applications

Understanding wavelength begins with understanding light itself.

---

# Review

This is Lesson 1.

No prior knowledge of optics is assumed.

We'll build everything from first principles.

If you understand high-school algebra, you're mathematically prepared to begin.

As the course progresses, we'll gradually introduce:

- Trigonometry
- Exponentials
- Calculus
- Differential equations
- Complex numbers
- Fourier analysis
- Introductory quantum mechanics

Each topic will be introduced only when it becomes useful.

---

# Intuition Before Physics

Let's ignore equations for a moment.

Imagine you're standing beside a lake.

You throw a rock into the water.

Ripples spread outward.

```
                O
              (Splash)

          ~~~~~~~~~~~~~
       ~~~~~~~~~~~~~~~~~~~
     ~~~~~~~~~~~~~~~~~~~~~~~
```

Energy is moving away from the splash.

Notice something important:

The water itself isn't traveling across the lake.

Instead, the disturbance moves while individual water molecules mostly move up and down.

This is one way waves transport energy.

Now imagine standing across a football field from a friend.

You shout.

Your voice travels through the air.

Again...

Energy moves.

The air molecules vibrate back and forth.

The molecules themselves do not travel from your mouth to your friend's ears.

Instead, the disturbance moves through the air.

So far we've seen two kinds of waves:

| Wave | Travels Through |
|-------|-----------------|
| Water waves | Water |
| Sound waves | Air (or another material) |

Now let's consider sunlight.

Between Earth and the Sun is nearly empty space.

There is essentially no air.

No water.

No material medium.

Yet sunlight still reaches Earth.

It travels approximately

**150 million kilometers**

in only

**8 minutes 20 seconds.**

This leads us to one of the most important observations in all of physics.

> **Light does not require a material medium to travel.**

Unlike sound...

Unlike water waves...

Light moves through empty space.

That simple observation puzzled scientists for centuries.

It eventually led to one of the greatest revolutions in physics.

---

# Engineering Insight

Understanding this single fact explains why lasers are useful almost everywhere.

A laser can:

- Operate in space
- Operate underwater
- Travel through vacuum chambers
- Travel through optical fibers
- Be focused by mirrors
- Be manipulated without requiring air

This makes lasers fundamentally different from technologies that rely on mechanical vibrations.

---

# Math Toolbox 1.1 – Scientific Notation

Laser engineering involves numbers that differ by more than **30 orders of magnitude**.

Writing all those zeros quickly becomes impossible.

Instead, engineers use scientific notation.

Examples:

```
1,000
=
1 × 10³

0.001
=
1 × 10⁻³

1,000,000
=
1 × 10⁶

0.000001
=
1 × 10⁻⁶
```

### Engineering Prefixes

| Prefix | Symbol | Value |
|---------|---------|-------:|
| tera | T | 10¹² |
| giga | G | 10⁹ |
| mega | M | 10⁶ |
| kilo | k | 10³ |
| — | — | 10⁰ |
| milli | m | 10⁻³ |
| micro | μ | 10⁻⁶ |
| nano | n | 10⁻⁹ |
| pico | p | 10⁻¹² |
| femto | f | 10⁻¹⁵ |

You will become extremely comfortable converting between these units throughout the course.

For example,

```
1064 nm

=

1064 × 10⁻⁹ m

=

1.064 × 10⁻⁶ m
```

That final form is much easier to use in engineering calculations.

---

# Worked Example

Convert the following into meters.

### Example 1

532 nm

Solution

```
532 × 10⁻⁹

=

5.32 × 10⁻⁷ m
```

---

### Example 2

2.94 μm

Solution

```
2.94 × 10⁻⁶ m
```

Notice how both values are written using powers of ten.

This makes equations significantly easier.

---

# The Speed of Light

The speed of light in a vacuum is one of the fundamental constants of nature.

Its exact value is

$$
c = 299\,792\,458\ \text{m/s}
$$

Unlike most physical quantities, this value is **defined exactly**, not measured approximately.

For nearly all engineering calculations we round it to

$$
c \approx 3.00 \times 10^8\ \text{m/s}
$$

This approximation introduces negligible error in most laser engineering calculations.

> **Engineering Rule ER-001**
>
> Unless extreme precision is required, use
>
> $$
> c = 3.00 \times 10^8\ \text{m/s}
> $$
>
> Doing so greatly simplifies calculations while maintaining engineering accuracy.

---

# What Makes Light Different?

At this point we know something remarkable.

Light

- carries energy,
- behaves like a wave,
- and travels through empty space.

But *how*?

That question puzzled scientists for centuries.

The answer eventually required an entirely new branch of physics.

It turns out that light is neither just a wave nor just a particle.

It has properties of both.

Understanding that dual nature is what eventually made lasers possible.

We'll begin exploring that idea in the next section of this lesson.

---

# Looking Ahead

In Part 2, we will answer questions that naturally arise from this lesson:

- What is an electromagnetic wave?
- What are electric and magnetic fields?
- What are wavelength and frequency?
- Why is the speed of light always the same in a vacuum?
- Where does the equation

$$
c = f\lambda
$$

come from?

By the end of Part 2, you'll be able to calculate the frequency of a laser simply from its wavelength—a calculation every laser engineer performs regularly.