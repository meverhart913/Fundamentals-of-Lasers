Module 1 – Laser Fundamentals

Lesson 1: What Is Light? The Foundation of Every Laser

Review

This is our first lesson, so there is nothing to review yet. Everything that follows—laser crystals, dopants, pumping, resonators, and industrial systems—depends on understanding one thing first:

> What is light?



A laser is simply an extremely well-controlled way of producing light. Before we can understand lasers, we need to understand what light actually is.


---

Part 1 – Intuition: How Can Something Travel Through Empty Space?

Imagine you're standing on opposite sides of a lake.

If you yell, your voice travels through the air because air molecules vibrate.

If there were no air, your voice couldn't reach the other side.

Now think about the Sun.

The space between the Sun and Earth is almost a perfect vacuum. There is essentially nothing there.

Yet sunlight still reaches Earth in about 8 minutes 20 seconds.

That immediately tells us something remarkable:

> Light does not need a material (called a medium) to travel.



This is one of the biggest differences between light and sound.

Property	Sound	Light

Needs air?	Yes	No
Travels through vacuum?	No	Yes
Travels as...	Pressure wave	Electromagnetic wave



---

Part 2 – Math Toolbox: Scientific Notation

Laser engineering involves numbers ranging from 10⁻¹⁵ to 10⁹ and beyond. Writing all those zeros quickly becomes impractical.

Instead, we use powers of ten.

Examples:

1,000 = 10³

0.001 = 10⁻³

1,000,000 = 10⁶

0.000001 = 10⁻⁶


You'll see this constantly in photonics.

For example:

Speed of light:

c = 3.00 \times 10^8\ \text{m/s}

This means:

300,000,000 meters every second.


---

SI Prefixes You'll Use Frequently

Prefix	Symbol	Power

milli	m	10⁻³
micro	μ	10⁻⁶
nano	n	10⁻⁹
pico	p	10⁻¹²
femto	f	10⁻¹⁵
kilo	k	10³
mega	M	10⁶
giga	G	10⁹


Example:

1064 nm (nanometers)

means

1064\times10^{-9}\ \text{meters}

You'll soon recognize 1064 nm as one of the most important wavelengths in laser engineering.


---

Part 3 – What Is an Electromagnetic Wave?

Light is an electromagnetic wave.

That means it consists of two oscillating fields:

an electric field

a magnetic field


These fields continuously generate one another as the wave travels.

Imagine them as two invisible waves oscillating at right angles:

Electric field
                ↑
                │
                │
──────────────→──────────────
 Direction of travel
                │
                ↓
         Magnetic field

A more complete picture is:

Electric Field (E)

              ↑
             / \
            /   \
-----------/-----\------------->

 Direction of Travel

^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
 Magnetic Field (B)

The electric field (E) and magnetic field (B) are always:

perpendicular to each other,

and perpendicular to the direction the light is traveling.


This relationship is a consequence of the equations that govern electromagnetism. Later in the course, we'll derive it from Maxwell's equations.


---

Part 4 – Wavelength and Frequency

Every wave has two fundamental properties.

Wavelength (λ)

The wavelength (Greek letter lambda, λ) is the distance between identical points on successive waves, such as crest to crest.

/\        /\
     /  \      /  \
____/    \____/    \____

<---- λ ---->

It is measured in:

meters (m)

micrometers (µm)

nanometers (nm)



---

Frequency (f)

Frequency tells us how many complete waves pass a point each second.

Measured in hertz (Hz):

1 Hz = 1 wave per second

1000 Hz = 1000 waves per second


Visible light has frequencies around:

4\times10^{14}

to

8\times10^{14}\ \text{Hz}

That's hundreds of trillions of oscillations every second.


---

Part 5 – The First Fundamental Equation

One of the most important equations in optics is:

c=f\lambda

where:

 = speed of light

 = frequency

 = wavelength


This equation tells us that if the wavelength changes, the frequency must also change because the speed of light in a vacuum is constant.

Worked Example

Suppose a laser emits at:

1064 nm

Convert to meters:

1064\times10^{-9}
=
1.064\times10^{-6}\ \text{m}

Now calculate the frequency:

f=\frac{c}{\lambda}

Substitute the values:

f=
\frac{3.00\times10^8}
{1.064\times10^{-6}}

Result:

f\approx2.82\times10^{14}\ \text{Hz}

That means a typical Nd:YAG laser oscillates about 282 trillion times every second.


---

Part 6 – Engineering Perspective

Why do laser engineers care about wavelength?

Because wavelength determines how light interacts with matter.

For example:

Water strongly absorbs around 2.94 µm, making Er:YAG lasers excellent for precise tissue ablation.

Metals absorb certain wavelengths better than others, affecting cutting and welding efficiency.

Silica optical fibers have very low loss near 1.55 µm, which is why erbium-doped fiber systems dominate long-distance telecommunications.


We'll spend much of the course exploring how wavelength drives material choice and application.


---

Lesson Summary

Light is an electromagnetic wave that can travel through a vacuum.

It consists of oscillating electric and magnetic fields.

Every light wave has a wavelength and a frequency.

These are related by the equation .

Wavelength is one of the most important parameters in laser engineering because it governs how light interacts with materials.



---

Review Questions

1. Why can light travel through space while sound cannot?


2. What is the difference between wavelength and frequency?


3. If wavelength decreases, what happens to frequency?


4. Why is scientific notation useful in photonics?


5. Why is wavelength so important when selecting a laser for an application?




---

Practical Engineering Example

A fiber laser emits light at 1070 nm.

Calculate its frequency using:

f=\frac{c}{\lambda}

Use:






Try solving it yourself before checking with a calculator. We'll discuss the result next lesson.


---

Quiz

Don't look up the answers—try them first.

1. True or False: Light needs air to travel.


2. What does the symbol λ represent?


3. What are the units of frequency?


4. If a laser's wavelength doubles, what happens to its frequency (assuming light is traveling in a vacuum)?



When you've answered, I'll provide the solutions with explanations.


---

Running Glossary

Electromagnetic (EM): Relating to coupled electric and magnetic fields.

Electromagnetic wave: A self-propagating wave of oscillating electric and magnetic fields.

Vacuum: A region containing essentially no matter.

Wavelength (λ): The distance between identical points on successive cycles of a wave.

Frequency (f): The number of wave cycles passing a point each second, measured in hertz (Hz).

Hertz (Hz): One cycle per second.

Speed of light (c): Approximately  m/s in a vacuum (a well-established physical constant).


In the next lesson, we'll build on this by exploring the electromagnetic spectrum, why different wavelengths have different energies, and how that leads naturally to photons and the quantum description of light. This is the bridge from classical physics into laser physics.