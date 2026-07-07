---

# Electromagnetic Waves

In Part 1, we established three important facts:

- Light carries energy.
- Light behaves like a wave.
- Light can travel through empty space.

The next question is obvious:

> **If light isn't vibrating air or water, then what is actually waving?**

The answer is surprising.

Light is a disturbance in two invisible fields:

- the **electric field (E)**
- the **magnetic field (B)**

These fields continuously create one another as the wave travels.

Unlike water waves, nothing physical is moving through space.

Instead, changing electric fields create magnetic fields, and changing magnetic fields create electric fields.

This self-sustaining process allows light to propagate through a vacuum.

---

## A Mental Model

Imagine stretching two jump ropes at right angles.

One rope moves up and down.

The other moves side to side.

Now imagine the entire system moving forward.

That is a useful visualization of an electromagnetic wave.

```
           Electric Field (E)

                 ↑
                 │
                 │
─────────────────┼─────────────────► Direction of Travel
                 │
                 │
                 ⊙ Magnetic Field (B)
```

A more realistic representation is:

```
                 Electric Field

                     /\
                    /  \
                   /    \
──────────────────/──────\────────────►

          Direction of Propagation

Magnetic field oscillates
perpendicular to both.
```

The three directions are always perpendicular.

| Quantity | Direction |
|----------|-----------|
| Electric field | Up and down |
| Magnetic field | Left and right |
| Wave motion | Forward |

This relationship is a consequence of **Maxwell's Equations**, which we'll derive later in Module 1.

---

> **Historical Note**
>
> In 1864, James Clerk Maxwell predicted that oscillating electric and magnetic fields could travel through space as waves.
>
> Years later, Heinrich Hertz generated and detected these waves experimentally.
>
> Today we call them **electromagnetic waves**.

---

# Wavelength

Every repeating wave has a length.

The distance between two identical points on adjacent waves is called the **wavelength**.

The Greek letter lambda is used.

$$
\lambda
$$

(pronounced *lambda*)

```
           Crest           Crest

             /\             /\
            /  \           /  \
___________/    \_________/    \_________

        <------ λ ------->
```

Common units are:

| Unit | Symbol | Equivalent |
|------|--------|------------|
| meter | m | Base SI unit |
| millimeter | mm | $10^{-3}$ m |
| micrometer | μm | $10^{-6}$ m |
| nanometer | nm | $10^{-9}$ m |

Laser engineers almost always use:

- nm
- μm

---

## Examples

| Laser | Wavelength |
|---------|-----------:|
| HeNe | 632.8 nm |
| Nd:YAG | 1064 nm |
| Fiber Laser | 1070 nm |
| Er:YAG | 2940 nm |
| CO₂ | 10.6 μm |

Notice that infrared lasers often use micrometers instead of nanometers because the numbers become easier to read.

---

# Frequency

Now imagine standing beside a road.

Cars pass you.

You could measure:

- the distance between cars

or

- how many cars pass every second.

Waves work exactly the same way.

The number of complete waves passing a point every second is called the **frequency**.

Its symbol is

$$
f
$$

Its SI unit is

**Hertz (Hz)**

where

$$
1\text{ Hz}=1\text{ cycle/second}
$$

Visible light has frequencies around

$$
4\times10^{14}
\text{ to }
8\times10^{14}\text{ Hz}
$$

That means hundreds of trillions of oscillations every second.

---

# Relationship Between Wavelength and Frequency

Suppose waves move at a speed of

10 meters per second.

Suppose each wave is

2 meters long.

How many waves pass you every second?

```
10 meters traveled each second

Each wave is 2 meters long

10 ÷ 2 = 5 waves each second
```

So

Frequency

=

Speed

÷

Wavelength

This isn't unique to light.

It applies to **every wave**.

Mathematically,

$$
f=\frac{\text{Speed}}{\lambda}
$$

For light,

the speed is always

$$
c
$$

Therefore,

$$
f=\frac{c}{\lambda}
$$

Rearranging gives

$$
\boxed{c=f\lambda}
$$

This is one of the most important equations in optics.

---

# Understanding the Equation

Let's think about what it means.

If

$$
c=f\lambda
$$

and

$c$

is constant,

then wavelength and frequency must move in opposite directions.

If wavelength becomes shorter...

frequency becomes larger.

If wavelength becomes longer...

frequency becomes smaller.

```
Long wavelength

/\          /\

↓

Lower frequency

----------------------------

Short wavelength

/\/\/\/\/\/\/\/\/

↓

Higher frequency
```

---

> **Engineering Insight**
>
> Engineers often speak of wavelength and frequency interchangeably because one immediately determines the other in a given medium.
>
> However, manufacturers almost always specify lasers by **wavelength**, not frequency.

---

# Worked Example 1

An Nd:YAG laser emits light at

1064 nm.

Calculate its frequency.

---

### Step 1

Convert nanometers into meters.

$$
1064\text{ nm}
=
1064\times10^{-9}
\text{ m}
$$

or

$$
1.064\times10^{-6}\text{ m}
$$

---

### Step 2

Use

$$
f=\frac{c}{\lambda}
$$

Substitute

$$
c=3.00\times10^8
$$

$$
\lambda=1.064\times10^{-6}
$$

---

### Step 3

Calculate

$$
f
=
\frac{3.00\times10^8}
{1.064\times10^{-6}}
$$

Result

$$
f
\approx
2.82\times10^{14}\text{ Hz}
$$

---

### Interpretation

An Nd:YAG laser's electric field changes direction approximately

**282 trillion times every second.**

That is almost impossible to visualize.

Fortunately,

we don't need to visualize it.

We only need mathematical models that accurately predict its behavior.

---

# Worked Example 2

A green laser emits at

532 nm.

Estimate its frequency.

Try solving this before reading further.

---

### Solution

Convert

$$
532\text{ nm}
=
5.32\times10^{-7}\text{ m}
$$

Then

$$
f=
\frac{3.00\times10^8}
{5.32\times10^{-7}}
$$

Result

$$
f
\approx
5.64\times10^{14}\text{ Hz}
$$

Notice something interesting.

532 nm has exactly half the wavelength of 1064 nm.

Its frequency is therefore approximately double.

This relationship becomes extremely important when we study **second harmonic generation (SHG)** in Module 7.

---

# Common Misconceptions

## Misconception 1

> "Higher wavelength means faster light."

Incorrect.

In a vacuum, all electromagnetic waves travel at the same speed:

$$
c=299,792,458\text{ m/s}
$$

Only the wavelength and frequency change.

---

## Misconception 2

> "Frequency is more important than wavelength."

Neither is inherently more important.

They contain the same information because

$$
c=f\lambda
$$

Engineers typically use wavelength because it directly relates to:

- optical coatings
- detector sensitivity
- material absorption
- fiber transmission
- safety standards

---

# Design Rule DR-001

Always verify units before performing wavelength calculations.

Many engineering mistakes arise from confusing:

- nm
- μm
- mm
- m

A unit conversion error of 1,000× is easy to make—and can invalidate an entire design calculation.

---

# Looking Ahead

So far we've treated light purely as a wave.

But some experiments cannot be explained by waves alone.

In Part 3, we'll introduce one of the most revolutionary ideas in physics:

> **Light also behaves like a stream of particles called photons.**

We'll derive the equation

$$
E = hf
$$

and discover why different laser wavelengths carry different amounts of energy—a concept that directly influences gain media, pump selection, nonlinear optics, and laser-material interactions throughout the rest of the course.