# Chapter 22: Electromagnetic Waves

<!-- Page 625 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 625-

Wireless technology is all around us: radio and television, cell phones, wi-fi, Bluetooth, and all wireless communication. These devices work by electromagnetic waves traveling through space. Wireless devices are applications of Marconi's development of long-distance transmission of information a century ago.

In this photo we see the first humans to land on the Moon. In the background is a television camera that sent live moving images through empty space to Earth where it was shown live.

We will see in this Chapter that Maxwell predicted the existence of EM waves from his famous equations. Maxwell's equations themselves are a magnificent summary of electromagnetism. We will also see that EM waves carry energy and momentum, and that light itself is an electromagnetic wave.

Electromagnetic Waves

CHAPTER-OPENING QUESTION-Guess now!
Which of the following best describes the difference between radio waves and X-rays?
(a) X-rays are radiation whereas radio waves are electromagnetic waves.
(b) Both can be thought of as electromagnetic waves. They differ only in wavelength and frequency.
(c) X-rays are pure energy. Radio waves are made of fields, not energy.
(d) Radio waves come from electric currents in an antenna. X-rays are not related to electric charge.
(e) X-rays are made up of particles called photons whereas radio waves are oscillations in space.

The culmination of electromagnetic theory in the nineteenth century was the prediction, and the experimental verification, that waves of electromagnetic fields could travel through space. This achievement opened a whole new world of communication: first the wireless telegraph, then radio and television, and more recently cell phones, remote-control devices, wi-fi, and Bluetooth. Most important was the spectacular prediction that light is an electromagnetic wave.

The theoretical prediction of electromagnetic waves was the work of the Scottish physicist James Clerk Maxwell (1831-1879; Fig. 22-1), who unified, in one magnificent theory, all the phenomena of electricity and magnetism.

CONTENTS
22-1 Changing Electric Fields Produce Magnetic Fields; Maxwell's Equations
22-2 Production of Electromagnetic Waves
22-3 Light as an Electromagnetic Wave and the Electromagnetic Spectrum
22-4 Measuring the Speed of Light
22-5 Energy in EM Waves
22-6 Momentum Transfer and Radiation Pressure
22-7 Radio and Television; Wireless Communication

FIGURE 22-1 James Clerk Maxwell.

625

---

<!-- Page 626 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13
Page 626

22-1 Changing Electric Fields Produce Magnetic Fields; Maxwell's Equations

The development of electromagnetic theory in the early part of the nineteenth century by Oersted, Ampère, and others was not actually done in terms of electric and magnetic fields. The idea of the field was introduced somewhat later by Faraday, and was not generally used until Maxwell showed that all electric and magnetic phenomena could be described using only four equations involving electric and magnetic fields. These equations, known as Maxwell's equations, are the basic equations for all electromagnetism. They are fundamental in the same sense that Newton's three laws of motion and the law of universal gravitation are for mechanics. In a sense, they are even more fundamental, because they are consistent with the theory of relativity (Chapter 26), whereas Newton's laws are not. Because all of electromagnetism is contained in this set of four equations, Maxwell's equations are considered one of the great triumphs of the human intellect.

Although we will not present Maxwell's equations in mathematical form since they involve calculus, we will summarize them here in words. They are:
(1) a generalized form of Coulomb's law that relates electric field to its source, electric charge (= Gauss's law, Section 16-12);
(2) a similar law for the magnetic field, except that magnetic field lines are always continuous-they do not begin or end (as electric field lines do, on charges);
(3) an electric field is produced by a changing magnetic field (Faraday's law);
(4) a magnetic field is produced by an electric current (Ampère's law), or by a changing electric field.
Law (3) is Faraday's law (see Chapter 21, especially Section 21-4). The first part of law (4), that a magnetic field is produced by an electric current, was discovered by Oersted, and the mathematical relation is given by Ampère's law (Section 20-8). But the second part of law (4) is an entirely new aspect predicted by Maxwell: Maxwell argued that if a changing magnetic field produces an electric field, as given by Faraday's law, then the reverse might be true as well: a changing electric field will produce a magnetic field. This was an hypothesis by Maxwell. It is based on the idea of symmetry in nature. Indeed, the size of the effect in most cases is so small that Maxwell recognized it would be difficult to detect it experimentally.
* Maxwell's Fourth Equation (Ampère's Law Extended)

To back up the idea that a changing electric field might produce a magnetic field, we use an indirect argument that goes something like this. According to Ampère's law (Section 20-8), $\Sigma B_{\|} \Delta \ell=\mu_{0} I$. That is, divide any closed path you choose into short segments $\Delta \ell$, multiply each segment by the parallel component of the magnetic field $B$ at that segment, and then sum all these products over the complete closed path. That sum will then equal $\mu_{0}$ times the total current $I$ that passes through a surface bounded by the path. When we applied Ampère's law to the field around a straight wire (Section 20-8), we imagined the current as passing through the circular area enclosed by our circular loop. That area is the flat surface 1 shown in Fig. 22-2. However, we could just as well use the sack-shaped surface 2 in Fig. 22-2 as the surface for Ampère's law because the same current $I$ passes through it.

FIGURE 22-2 Ampère's law applied to two different surfaces bounded by the same closed path.

626
CHAPTER 22 Electromagnetic Waves

---

<!-- Page 627 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 627

Now consider the closed path for the situation of Fig. 22-3 where a capacitor is being discharged. Ampère's law works for surface 1 (current $I$ passes through surface 1), but it does not work for surface 2 because no current passes through surface 2. There is a magnetic field around the wire, so the left side of Ampère's law
$$\Sigma B_{\|} \Delta \ell=\mu_{0} I$$
is not zero around the circular closed path; yet no current flows through surface 2 , so the right side is zero for surface 2 . We seem to have a contradiction of Ampère's law. There is a magnetic field present in Fig. 22-3, however, only if charge is flowing to or away from the capacitor plates. The changing charge on the plates means that the electric field between the plates is changing in time. Maxwell resolved the problem of no current through surface 2 in Fig. 22-3 by proposing that the changing electric field between the plates is equivalent to an electric current. He called it a displacement current, $I_{\mathrm{D}}$. An ordinary current $I$ is then called a "conduction current," and Ampère's law, as generalized by Maxwell, becomes
$$\sum B_{\|} \Delta \ell=\mu_{0}\left(I+I_{\mathrm{D}}\right) .$$

Ampère's law will now apply also for surface 2 in Fig. 22-3, where $I_{\mathrm{D}}$ refers to the changing electric field.

Combining Eq. 17-7 for the charge on a capacitor, $Q=C V$, with Eq. 17-8, $C=\epsilon_{0} A / d$, and with the magnitudes in Eq. 17-4a, $V=E d$, we can write $Q=C V=\left(\epsilon_{0} A / d\right)(E d)=\epsilon_{0} A E$. Then the current $I_{\mathrm{D}}$ becomes
$$I_{\mathrm{D}}=\frac{\Delta Q}{\Delta t}=\epsilon_{0} \frac{\Delta \Phi_{E}}{\Delta t},$$
where $\Phi_{E}=E A$ is the electric flux, defined in analogy to magnetic flux (Section 21-2). Then, Ampère's law becomes
$$\Sigma B_{\|} \Delta \ell=\mu_{0} I+\mu_{0} \epsilon_{0} \frac{\Delta \Phi_{E}}{\Delta t} .$$

This equation embodies Maxwell's idea that a magnetic field can be caused not only by a normal electric current, but also by a changing electric field or changing electric flux.

22-2 Production of Electromagnetic Waves

According to Maxwell, a magnetic field will be produced in empty space if there is a changing electric field. From this, Maxwell derived another startling conclusion. If a changing magnetic field produces an electric field, that electric field is itself changing. This changing electric field will, in turn, produce a magnetic field, which will be changing, and so it too will produce a changing electric field; and so on. When Maxwell worked with his equations, he found that the net result of these interacting changing fields was a wave of electric and magnetic fields that can propagate (travel) through space! We now examine, in a simplified way, how such electromagnetic waves can be produced.

Consider two conducting rods that will serve as an "antenna" (Fig. 22-4a). Suppose these two rods are connected by a switch to the opposite terminals of a battery. When the switch is closed, the upper rod quickly becomes positively charged and the lower one negatively charged. Electric field lines are formed as indicated by the lines in Fig. 22-4b. While the charges are flowing, a current exists whose direction is indicated by the black arrows. A magnetic field is therefore produced near the antenna. The magnetic field lines encircle the rod-like antenna and therefore, in Fig. 22-4, $\overrightarrow{\mathbf{B}}$ points into the page ( $\otimes$ ) on the right and out of the page ( $\odot$ ) on the left. Now we ask, how far out do these electric and magnetic fields extend? In the static case, the fields would extend outward indefinitely far. However, when the switch in Fig. 22-4 is closed, the fields quickly appear nearby, but it takes time for them to reach distant points. Both electric and magnetic fields store energy, and this energy cannot be transferred to distant points at infinite speed.

FIGURE 22-3 A capacitor discharging. A conduction current passes through surface 1, but no conduction current passes through the sacklike surface 2. An extra term is needed in Ampère's law.

Ampère's law (general form)

FIGURE 22-4 Fields produced by charge flowing into conductors. It takes time for the $\overrightarrow{\mathbf{E}}$ and $\overrightarrow{\mathbf{B}}$ fields to travel outward to distant points. The fields are shown to the right of the antenna, but they move out in all directions, symmetrically about the (vertical) antenna.

SECTION 22-2 Production of Electromagnetic Waves
627

---

<!-- Page 628 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 628

FIGURE 22-5 Sequence showing electric and magnetic fields that spread outward from oscillating charges on two conductors (the antenna) connected to an ac source (see the text).

Now we look at the situation of Fig. 22-5, where our antenna is connected to an ac generator. In Fig. 22-5a, the connection has just been completed. Charge starts building up, and fields form just as in Fig. 22-4b. The + and - signs in Fig. 22-5a indicate the net charge on each rod at a given instant. The black arrows indicate the direction of the current. The electric field is represented by red lines in the plane of the page; and the magnetic field, according to the right-hand rule, is into ( $\otimes$ ) or out of ( $\odot$ ) the page in blue. In Fig. 22-5b, the voltage of the ac generator has reversed in direction; the current is reversed and the new magnetic field is in the opposite direction. Because the new fields have changed direction, the old lines fold back to connect up to some of the new lines and form closed loops as shown. ${ }^{\dagger}$ The old fields, however, don't suddenly disappear; they are on their way to distant points. Indeed, because a changing magnetic field produces an electric field, and a changing electric field produces a magnetic field, this combination of changing electric and magnetic fields moving outward is selfsupporting, no longer depending on the antenna charges.

The fields not far from the antenna, referred to as the near field, become quite complicated, but we are not so interested in them. We are mainly interested in the fields far from the antenna (they are generally what we detect), which we refer to as the radiation field. The electric field lines form loops, as shown in Fig. 22-6a, and continue moving outward. The magnetic field lines also form closed loops, but are not shown because they are perpendicular to the page. Although the lines are shown only on the right of the source, fields also travel in other directions. The field strengths are greatest in directions perpendicular to the oscillating charges; and they drop to zero along the direction of oscillation-above and below the antenna in Fig. 22-6a.

FIGURE 22-6 (a) The radiation fields (far from the antenna) produced by a sinusoidal signal on the antenna. The red closed loops represent electric field lines. The magnetic field lines, perpendicular to the page and represented by blue ⊗ and $\odot$, also form closed loops. (b) Very far from the antenna, the wave fronts (field lines) are essentially flat over a fairly large area, and are referred to as plane waves.

The magnitudes of both $\overrightarrow{\mathbf{E}}$ and $\overrightarrow{\mathbf{B}}$ in the radiation field are found to decrease with distance as $1 / r$. (Compare this to the static electric field given by Coulomb's law where $\overrightarrow{\mathbf{E}}$ decreases as $1 / r^{2}$.) The energy carried by the electromagnetic wave is proportional (as for any wave, Chapter 11) to the square of the amplitude, $E^{2}$ or $B^{2}$, as will be discussed further in Section 22-7, so the intensity of the wave decreases as $1 / r^{2}$. Thus the energy carried by EM waves follows the inverse square law just as for sound waves (Eqs. 11-16).

Several things about the radiation field can be noted from Fig. 22-6. First, the electric and magnetic fields at any point are perpendicular to each other, and to the direction of wave travel. Second, we can see that the fields alternate in direction ( $\overrightarrow{\mathbf{B}}$ is into the page at some points and out of the page at others; $\overrightarrow{\mathbf{E}}$ points up at some points and down at others). Thus, the field strengths vary from a maximum in one direction, to zero, to a maximum in the other direction. The electric and magnetic fields are "in phase": that is, they each are zero at the same points and reach their maxima at the same points in space. Finally, very far from the antenna (Fig. 22-6b) the field lines are quite flat over a reasonably large area, and the waves are referred to as plane waves.
${ }^{\dagger}$ We are considering waves traveling through empty space. There are no charges for lines of $\overrightarrow{\mathbf{E}}$ to start or stop on, so they form closed loops. Magnetic field lines always form closed loops.

628
CHAPTER 22 Electromagnetic Waves

---

<!-- Page 629 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 629

If the source voltage varies sinusoidally, then the electric and magnetic field strengths in the radiation field will also vary sinusoidally. The sinusoidal character of the waves is shown in Fig. 22-7, which displays the field directions and magnitudes plotted as a function of position along the direction of wave travel. Notice that $\overrightarrow{\mathbf{B}}$ and $\overrightarrow{\mathbf{E}}$ are perpendicular to each other and to the direction of wave travel.

We call these waves electromagnetic (EM) waves. They are transverse waves because the amplitude is perpendicular to the direction of wave travel. However, EM waves are always waves of fields, not of matter (like waves on water or a rope). Because they are fields, EM waves can propagate in empty space.

As we have seen, EM waves are produced by electric charges that are oscillating, and hence are undergoing acceleration. In fact, we can say in general that
accelerating electric charges give rise to electromagnetic waves.
Maxwell derived a formula for the speed of EM waves:
$$v=c=\frac{E}{B},$$
where $c$ is the special symbol for the speed of electromagnetic waves in empty space, and $E$ and $B$ are the magnitudes of electric and magnetic fields at the same point in space. More specifically, it was also shown that
$$c=\frac{1}{\sqrt{\epsilon_{0} \mu_{0}}} .$$
[speed of EM waves] (22-3)

FIGURE 22-7 Electric and magnetic field strengths in an electromagnetic wave. $\overrightarrow{\mathbf{E}}$ and $\overrightarrow{\mathbf{B}}$ are at right angles to each other. The entire pattern moves in a direction perpendicular to both $\overrightarrow{\mathbf{E}}$ and $\overrightarrow{\mathbf{B}}$.
which is exactly equal to the measured speed of light in vacuum (Section 22-4).
When Maxwell put in the values for $\epsilon_{0}$ and $\mu_{0}$, he found
$$c=\frac{1}{\sqrt{\epsilon_{0} \mu_{0}}}=\frac{1}{\sqrt{\left(8.85 \times 10^{-12} \mathrm{C}^{2} / \mathrm{N} \cdot \mathrm{~m}^{2}\right)\left(4 \pi \times 10^{-7} \mathrm{~N} \cdot \mathrm{~s}^{2} / \mathrm{C}^{2}\right)}}=3.00 \times 10^{8} \mathrm{~m} / \mathrm{s},$$
which is exactly equal to the measured speed of light in vacuum (Section 22-4).
EXERCISE A At a particular instant in time, a wave has its electric field pointing north and its magnetic field pointing up. In which direction is the wave traveling? (a) South, (b) west, (c) east, (d) down, (e) not enough information. [See Fig. 22-7.]

22-3 Light as an Electromagnetic Wave and the Electromagnetic Spectrum

Maxwell's prediction that EM waves should exist was startling. Equally remarkable was the speed at which EM waves were predicted to travel- $3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}$, the same as the measured speed of light.

Light had been shown some 60 years before Maxwell's work to behave like a wave (we'll discuss this in Chapter 24). But nobody knew what kind of wave it was. What is it that is oscillating in a light wave? Maxwell, on the basis of the calculated speed of EM waves, argued that light must be an electromagnetic wave. This idea soon came to be generally accepted by scientists, but not fully until after EM waves were experimentally detected. EM waves were first generated and detected experimentally by Heinrich Hertz (1857-1894) in 1887, eight years after Maxwell's death. Hertz used a spark-gap apparatus in which charge was made to rush back and forth for a short time, generating waves whose frequency was about $10^{9} \mathrm{~Hz}$. He detected them some distance away using a loop of wire in which an emf was induced when a changing magnetic field passed through.

SECTION 22-3
629

---

<!-- Page 630 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 630

These waves were later shown to travel at the speed of light, $3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}$, and to exhibit all the characteristics of light such as reflection, refraction, and interference. The only difference was that they were not visible. Hertz's experiment was a strong confirmation of Maxwell's theory.

The wavelengths of visible light were measured in the first decade of the nineteenth century, long before anyone imagined that light was an electromagnetic wave. The wavelengths were found to lie between $4.0 \times 10^{-7} \mathrm{~m}$ and $7.5 \times 10^{-7} \mathrm{~m}$, or 400 nm to $750 \mathrm{~nm}\left(1 \mathrm{~nm}=10^{-9} \mathrm{~m}\right)$. The frequencies of visible light can be found using Eq. 11-12, which we rewrite here:
$$c=\lambda f,$$
where $f$ and $\lambda$ are the frequency and wavelength, respectively, of the wave. Here, $c$ is the speed of light, $3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}$; it gets the special symbol $c$ because of its universality for all EM waves in free space. Equation 22-4 tells us that the frequencies of visible light are between $4.0 \times 10^{14} \mathrm{~Hz}$ and $7.5 \times 10^{14} \mathrm{~Hz}$. (Recall that $1 \mathrm{~Hz}=1$ cycle per second $=1 \mathrm{~s}^{-1}$.)

But visible light is only one kind of EM wave. As we have seen, Hertz produced EM waves of much lower frequency, about $10^{9} \mathrm{~Hz}$. These are now called radio waves, because frequencies in this range are used to transmit radio and TV signals. Electromagnetic waves, or EM radiation as we sometimes call it, have been produced or detected over a wide range of frequencies. They are usually categorized as shown in Fig. 22-8, which is known as the electromagnetic spectrum.

Radio waves and microwaves can be produced in the laboratory using electronic equipment (Fig. 22-5). Higher-frequency waves are very difficult to produce electronically. These and other types of EM waves are produced in natural processes, as emission from atoms, molecules, and nuclei (more on this later). EM waves can be produced by the acceleration of electrons or other charged particles, such as electrons in the antenna of Fig. 22-5. X-rays have very short wavelengths (and very high frequencies), and they are produced (Chapters 25 and 28) when fast-moving electrons are rapidly decelerated upon striking a metal target. Even the visible light emitted by an ordinary incandescent bulb is due to electrons undergoing acceleration within the hot filament.
EXERCISE B Return to the Chapter-Opening Question, page 625, and answer it again now. Try to explain why you may have answered differently the first time.

We will meet various types of EM waves later. However, it is worth mentioning here that infrared (IR) radiation (EM waves whose frequency is just less than that of visible light) is mainly responsible for the heating effect of the Sun. The Sun emits not only visible light but substantial amounts of IR and UV (ultraviolet) as well. The molecules of our skin tend to "resonate" at infrared frequencies, so it is these that are preferentially absorbed and thus warm us. We humans experience EM waves differently depending on their wavelengths: Our eyes detect wavelengths between about $4 \times 10^{-7} \mathrm{~m}$ and $7.5 \times 10^{-7} \mathrm{~m}$ (visible light), whereas our skin detects

630
CHAPTER 22 longer wavelengths (IR). Many EM wavelengths we don't detect directly at all.

---

<!-- Page 631 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 631.

Light and other electromagnetic waves travel at a speed of $3 \times 10^{8} \mathrm{~m} / \mathrm{s}$. Compare this to sound, which travels (see Chapter 12) at a speed of about $300 \mathrm{~m} / \mathrm{s}$ in air, a million times slower; or to typical freeway speeds of a car, $30 \mathrm{~m} / \mathrm{s}(100 \mathrm{~km} / \mathrm{h}$, or $60 \mathrm{mi} / \mathrm{h}$ ), 10 million times slower than light. EM waves differ from sound waves in another big way: sound waves travel in a medium such as air, and involve motion of air molecules; EM waves do not involve any material-only fields, and they can travel in empty space.

EXAMPLE 22-1 Wavelengths of EM waves. Calculate the wavelength (a) of a $60-\mathrm{Hz}$ EM wave, (b) of a $93.3-\mathrm{MHz}$ FM radio wave, and (c) of a beam of visible red light from a laser at frequency $4.74 \times 10^{14} \mathrm{~Hz}$.
APPROACH All of these waves are electromagnetic waves, so their speed is $c=3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}$. We solve for $\lambda$ in Eq. 22-4: $\lambda=c / f$.
SOLUTION (a)
$$\lambda=\frac{c}{f}=\frac{3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}}{60 \mathrm{~s}^{-1}}=5.0 \times 10^{6} \mathrm{~m},$$
or 5000 km .60 Hz is the frequency of ac current in the United States, and, as we see here, one wavelength stretches all the way across the continental USA.
(b)
$$\lambda=\frac{3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}}{93.3 \times 10^{6} \mathrm{~s}^{-1}}=3.22 \mathrm{~m}$$

The length of an FM radio antenna is often about half this $\left(\frac{1}{2} \lambda\right)$, or $1 \frac{1}{2} \mathrm{~m}$.
(c)
$$\lambda=\frac{3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}}{4.74 \times 10^{14} \mathrm{~s}^{-1}}=6.33 \times 10^{-7} \mathrm{~m}(=633 \mathrm{~nm}) .$$

EXERCISE C What are the frequencies of (a) an $80-\mathrm{m}$-wavelength radio wave, and (b) an X-ray of wavelength $5.5 \times 10^{-11} \mathrm{~m}$ ?

EXAMPLE 22-2 ESTIMATE Cell phone antenna. The antenna of a cell phone is often $\frac{1}{4}$ wavelength long. A particular cell phone has an $8.5-\mathrm{cm}$-long straight rod for its antenna. Estimate the operating frequency of this phone.
APPROACH The basic equation relating wave speed, wavelength, and frequency is $c=\lambda f$; the wavelength $\lambda$ equals four times the antenna's length.
SOLUTION The antenna is $\frac{1}{4} \lambda$ long, so $\lambda=4(8.5 \mathrm{~cm})=34 \mathrm{~cm}=0.34 \mathrm{~m}$. Then $f=c / \lambda=\left(3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}\right) /(0.34 \mathrm{~m})=8.8 \times 10^{8} \mathrm{~Hz}=880 \mathrm{MHz}$.
NOTE Radio antennas are not always straight conductors. The conductor may be a round loop to save space. See Fig. 22-18b.

EXERCISE D How long should a $\frac{1}{4}-\lambda$ antenna be for an aircraft radio operating at 165 MHz ?

Electromagnetic waves can travel along transmission lines as well as in empty space. When a source of emf is connected to a transmission line-be it two parallel wires or a coaxial cable (Fig. 22-9)-the electric field within the wire is not set up immediately at all points along the wires. This is based on the same argument we used in Section 22-2 with reference to Fig. 22-5. Indeed, it can be shown that if the wires are separated by empty space or air, the electrical signal travels along the wires at the speed $c=3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}$. For example, when you flip a light switch, the light actually goes on a tiny fraction of a second later. If the wires are in a medium whose electric permittivity is $\epsilon$ and magnetic permeability is $\mu$ (Sections 17-8 and 20-12, respectively), the speed is not given by Eq. 22-3, but by
$$v=\frac{1}{\sqrt{\epsilon \mu}}$$
instead.
CAUTION
Sound and EM waves
are different

FIGURE 22-9 Coaxial cable.

SECTION 22-3 Light as an Electromagnetic Wave and the Electromagnetic Spectrum
631

---

<!-- Page 632 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13
Page 632

EXAMPLE 22-3 ESTIMATE Phone call time lag. You make a telephone call from New York to a friend in London. Estimate how long it will take the electrical signal generated by your voice to reach London, assuming the signal is (a) carried on a telephone cable under the Atlantic Ocean, and (b) sent via satellite $36,000 \mathrm{~km}$ above the ocean. Would there be a noticeable delay in either case?
APPROACH The signal is carried on a telephone wire or in the air via satellite. In either case it is an electromagnetic wave. Electronics as well as the wire or cable slow things down, but as a rough estimate we take the speed to be $c=3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}$.
SOLUTION The distance from New York to London is about 5000 km .
(a) The time delay via the cable is $t=d / c \approx\left(5 \times 10^{6} \mathrm{~m}\right) /\left(3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}\right)=$ 0.017 s .
(b) Via satellite the time would be longer because communications satellites, which are usually geosynchronous (Example 5-12), move at a height of $36,000 \mathrm{~km}$. The signal would have to go up to the satellite and back down, or about $72,000 \mathrm{~km}$. The actual distance the signal would travel would be a little more than this as the signal would go up and down on a diagonal ( 5000 km New York to London, small compared to the distance up to the satellite). Thus $t=d / c \approx\left(7.2 \times 10^{7} \mathrm{~m}\right) /\left(3 \times 10^{8} \mathrm{~m} / \mathrm{s}\right) \approx 0.24 \mathrm{~s}$, one way. Both directions $\approx \frac{1}{2} \mathrm{~s}$.
NOTE When the signal travels via the underwater cable, there is only a hint of a delay and conversations are fairly normal. When the signal is sent via satellite, the delay is noticeable. The length of time between the end of when you speak and your friend receives it and replies, and then you hear the reply, would be about a half second beyond the normal time in a conversation, as we just calculated. This is enough to be noticeable, and you have to adjust for it so you don't start talking again while your friend's reply is on the way back to you.

EXERCISE E If you are on the phone via satellite to someone only 100 km away, would you notice the same effect discussed in the NOTE above?

EXERCISE F If your voice traveled as a sound wave, how long would it take to go from New York to London?

22-4 Measuring the Speed of Light
Galileo attempted to measure the speed of light by trying to measure the time required for light to travel a known distance between two hilltops. He stationed an assistant on one hilltop and himself on another, and ordered the assistant to lift the cover from a lamp the instant he saw a flash from Galileo's lamp. Galileo measured the time between the flash of his lamp and when he received the light from his assistant's lamp. The time was so short that Galileo concluded it merely represented human reaction time, and that the speed of light must be extremely high.

The first successful determination that the speed of light is finite was made by the Danish astronomer Ole Roemer (1644-1710). Roemer had noted that the carefully measured orbital period of Io, a moon of Jupiter with an average period of 42.5 h , varied slightly, depending on the relative position of Earth and Jupiter. He attributed this variation in the apparent period to the change in distance between the Earth and Jupiter during one of Io's periods, and the time it took light to travel the extra distance. Roemer concluded that the speed of lightthough great-is finite.

Since then a number of techniques have been used to measure the speed of light. Among the most important were those carried out by the American Albert A. Michelson (1852-1931). Michelson used the rotating mirror apparatus diagrammed

632
CHAPTER 22 Electromagnetic Waves

---

<!-- Page 633 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 63\}

in Fig. 22-10 for a series of high-precision experiments carried out from 1880 to the 1920s. Light from a source would hit one face of a rotating eight-sided mirror. The reflected light traveled to a stationary mirror a large distance away and back again as shown. If the rotating mirror was turning at just the right rate, the returning beam of light would reflect from one face of the mirror into a small telescope through which the observer looked. If the speed of rotation was only slightly different, the beam would be deflected to one side and would not be seen by the observer. From the required speed of the rotating mirror and the known distance to the stationary mirror, the speed of light could be calculated. In the 1920s, Michelson set up the rotating mirror on the top of Mt. Wilson in southern California and the stationary mirror on Mt. Baldy (Mt. San Antonio) 35 km away. He later measured the speed of light in vacuum using a long evacuated tube.

Today the speed of light, $c$, in vacuum is taken as
$$c=2.99792458 \times 10^{8} \mathrm{~m} / \mathrm{s},$$
and is defined to be this value. This means that the standard for length, the meter, is no longer defined separately. Instead, as we noted in Section 1-5, the meter is now formally defined as the distance light travels in vacuum in 1/299,792,458 of a second.

We usually round off $c$ to
$$c=3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}$$
when extremely precise results are not required. In air, the speed is only slightly less.

22-5 Energy in EM Waves
Electromagnetic waves carry energy from one region of space to another. This energy is associated with the moving electric and magnetic fields. In Section 17-9, we saw that the energy density $u_{E}\left(\mathrm{~J} / \mathrm{m}^{3}\right)$ stored in an electric field $E$ is $u_{E}=\frac{1}{2} \epsilon_{0} E^{2}$ (Eq. 17-11). The energy density stored in a magnetic field $B$, as we discussed in Section 21-11, is given by $u_{B}=\frac{1}{2} B^{2} / \mu_{0}$ (Eq. 21-10). Thus, the total energy stored per unit volume in a region of space where there is an electromagnetic wave is
$$u=u_{E}+u_{B}=\frac{1}{2} \epsilon_{0} E^{2}+\frac{1}{2} \frac{B^{2}}{\mu_{0}} .$$

In this equation, $E$ and $B$ represent the electric and magnetic field strengths of the wave at any instant in a small region of space. We can write Eq. 22-5 in terms of the $E$ field only using Eqs. 22-2 ( $B=E / c$ ) and $22-3\left(c=1 / \sqrt{\epsilon_{0} \mu_{0}}\right)$ to obtain
$$u=\frac{1}{2} \epsilon_{0} E^{2}+\frac{1}{2} \frac{\epsilon_{0} \mu_{0} E^{2}}{\mu_{0}}=\epsilon_{0} E^{2} .$$

Note here that the energy density associated with the $B$ field equals that due to the $E$ field, and each contributes half to the total energy. We can also write the energy density in terms of the $B$ field only:
$$u=\epsilon_{0} E^{2}=\epsilon_{0} c^{2} B^{2}=\frac{B^{2}}{\mu_{0}},$$
or in one term containing both $E$ and $B$,
$$u=\epsilon_{0} E^{2}=\epsilon_{0} E c B=\frac{\epsilon_{0} E B}{\sqrt{\epsilon_{0} \mu_{0}}}$$
or
$$u=\sqrt{\frac{\epsilon_{0}}{\mu_{0}}} E B .$$

Equations 22-6 give the energy density of EM waves in any region of space at any instant.

FIGURE 22-10 Michelson's speed-of-light apparatus (not to scale).

SECTION 22-5 Energy in EM Waves
633

---

<!-- Page 634 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13
Page 634

FIGURE 22-11 Electromagnetic wave carrying energy through area $A$.

The energy a wave transports per unit time per unit area is the intensity $I$, as defined in Sections 11-9 and 12-2. ${ }^{\dagger}$ The units of $I$ are $\mathrm{W} / \mathrm{m}^{2}$. The energy $\Delta U$ is the energy density (Eq. 22-6a) times the volume $V$. Hence the energy passing through an area $A$ in a time $\Delta t$ (see Fig. 22-11) is
$$\Delta U=u \Delta V=(u)(A \Delta x)=\left(\epsilon_{0} E^{2}\right)(A c \Delta t)$$
because $\Delta x=c \Delta t$. Therefore, the magnitude of the intensity (energy per unit area per time $\Delta t$, or power per unit area) is
$$I=\frac{\Delta U}{A \Delta t}=\frac{\left(\epsilon_{0} E^{2}\right)(A c \Delta t)}{A \Delta t}=\epsilon_{0} c E^{2} .$$

From Eqs. 22-2 and 22-3, this can also be written
$$I=\epsilon_{0} c E^{2}=\frac{c}{\mu_{0}} B^{2}=\frac{E B}{\mu_{0}} .$$

We can also find the average intensity over an extended period of time, if $E$ and $B$ are sinusoidal. Then $\overline{E^{2}}=E_{0}^{2} / 2$, just as for electric currents and voltages, Section 18-7, Eqs. 18-8. Thus
$$\bar{I}=\frac{1}{2} \epsilon_{0} c E_{0}^{2}=\frac{1}{2} \frac{c}{\mu_{0}} B_{0}^{2}=\frac{E_{0} B_{0}}{2 \mu_{0}} .$$

Here $E_{0}$ and $B_{0}$ are the maximum values of $E$ and $B$. We can also write
$$\bar{I}=\frac{E_{\mathrm{rms}} B_{\mathrm{rms}}}{\mu_{0}},$$
where $E_{\text {rms }}$ and $B_{\text {rms }}$ are the rms values $\left(E_{\text {rms }}=\sqrt{\overline{E^{2}}}=E_{0} / \sqrt{2}\right.$, and $B_{\mathrm{rms}}=\sqrt{\overline{B^{2}}}=B_{0} / \sqrt{2}$ ).

EXAMPLE 22-4 $\boldsymbol{E}$ and $\boldsymbol{B}$ from the Sun. Radiation from the Sun reaches the Earth (above the atmosphere) with an intensity of about $1350 \mathrm{~W} / \mathrm{m}^{2}= 1350 \mathrm{~J} / \mathrm{s} \cdot \mathrm{m}^{2}$. Assume that this is a single EM wave, and calculate the maximum values of $E$ and $B$.
APPROACH We solve Eq. 22-8 ( $\bar{I}=\frac{1}{2} \epsilon_{0} c E_{0}^{2}$ ) for $E_{0}$ in terms of $\bar{I}$ and use $\bar{I}=1350 \mathrm{~J} / \mathrm{s} \cdot \mathrm{m}^{2}$.
$$\text { SOLUTION } \begin{aligned}
E_{0} & =\sqrt{\frac{2 \bar{I}}{\epsilon_{0} c}}=\sqrt{\frac{2\left(1350 \mathrm{~J} / \mathrm{s} \cdot \mathrm{~m}^{2}\right)}{\left(8.85 \times 10^{-12} \mathrm{C}^{2} / \mathrm{N} \cdot \mathrm{~m}^{2}\right)\left(3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}\right)}} \\
& =1.01 \times 10^{3} \mathrm{~V} / \mathrm{m} .
\end{aligned}$$

From Eq. 22-2, $B=E / c$, so
$$B_{0}=\frac{E_{0}}{c}=\frac{1.01 \times 10^{3} \mathrm{~V} / \mathrm{m}}{3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}}=3.37 \times 10^{-6} \mathrm{~T} .$$

NOTE Although $B$ has a small numerical value compared to $E$ (because of the way the different units for $E$ and $B$ are defined), $B$ contributes the same energy to the wave as $E$ does, as we saw earlier.
${ }^{\dagger}$ The intensity $I$ for EM waves is often called the Poynting vector and given the symbol $\overrightarrow{\mathbf{S}}$. Its direction is that in which the energy is being transported, which is the direction the wave is traveling, and its magnitude is the intensity $(S=I)$.

634
CHAPTER 22 Electromagnetic Waves

---

<!-- Page 635 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 635

22-6 Momentum Transfer and Radiation Pressure

If electromagnetic waves carry energy, then we would expect them to also carry linear momentum. When an electromagnetic wave encounters the surface of an object, a force will be exerted on the surface as a result of the momentum transfer ( $F=\Delta p / \Delta t$ ) just as when a moving object strikes a surface. The force per unit area exerted by the waves is called radiation pressure, and its existence was predicted by Maxwell. He showed that if a beam of EM radiation (light, for example) is completely absorbed by an object, then the momentum transferred is
$$\Delta p=\frac{\Delta U}{c}$$
$$\left[\begin{array}{c}
\text { radiation } \\
\text { fully } \\
\text { absorbed }
\end{array}\right] \quad \mathbf{( 2 2 - 9 a )}$$
where $\Delta U$ is the energy absorbed by the object in a time $\Delta t$ and $c$ is the speed of light. If, instead, the radiation is fully reflected (suppose the object is a mirror), then the momentum transferred is twice as great, just as when a ball bounces elastically off a surface:
$$\Delta p=\frac{2 \Delta U}{c}$$
$$\left[\begin{array}{c}
\text { radiation } \\
\text { fully } \\
\text { reflected }
\end{array}\right] \quad(\mathbf{2 2 - 9 b})$$

If a surface absorbs some of the energy, and reflects some of it, then $\Delta p=a \Delta U / c$, where $a$ has a value between 1 and 2 .

Using Newton's second law we can calculate the force and the pressure exerted by EM radiation on an object. The force $F$ is given by
$$F=\frac{\Delta p}{\Delta t}$$

The radiation pressure $P$ (assuming full absorption) is given by (see Eq. 22-9a)
$$P=\frac{F}{A}=\frac{1}{A} \frac{\Delta p}{\Delta t}=\frac{1}{A c} \frac{\Delta U}{\Delta t}$$

We discussed in Section 22-5 that the average intensity $\bar{I}$ is defined as energy per unit time per unit area:
$$\bar{I}=\frac{\Delta U}{A \Delta t}$$

Hence the radiation pressure is
$$P=\frac{\bar{I}}{c}$$
$$\left[\begin{array}{l}
\text { fully } \\
\text { absorbed }
\end{array}\right]$$

If the light is fully reflected, the radiation pressure is twice as great (Eq. 22-9b):
$$P=\frac{2 \bar{I}}{c}$$

EXAMPLE 22-5 ESTIMATE Solar pressure. Radiation from the Sun that reaches the Earth's surface (after passing through the atmosphere) transports energy at a rate of about $1000 \mathrm{~W} / \mathrm{m}^{2}$. Estimate the pressure and force exerted by the Sun on your outstretched hand.
APPROACH The radiation is partially reflected and partially absorbed, so let us estimate simply $P=\bar{I} / c$.
SOLUTION $P \approx \frac{\bar{I}}{c}=\frac{1000 \mathrm{~W} / \mathrm{m}^{2}}{3 \times 10^{8} \mathrm{~m} / \mathrm{s}} \approx 3 \times 10^{-6} \mathrm{~N} / \mathrm{m}^{2}$.
An estimate of the area of your outstretched hand might be about 10 cm by 20 cm , so $A \approx 0.02 \mathrm{~m}^{2}$. Then the force is
$$F=P A \approx\left(3 \times 10^{-6} \mathrm{~N} / \mathrm{m}^{2}\right)\left(0.02 \mathrm{~m}^{2}\right) \approx 6 \times 10^{-8} \mathrm{~N} .$$

NOTE These numbers are tiny. The force of gravity on your hand, for comparison, is maybe a half pound, or with $m=0.2 \mathrm{~kg}, m g \approx(0.2 \mathrm{~kg})\left(9.8 \mathrm{~m} / \mathrm{s}^{2}\right) \approx 2 \mathrm{~N}$. The radiation pressure on your hand is imperceptible compared to gravity.

SECTION 22-6
635

---

<!-- Page 636 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13
Page 636

EXAMPLE 22-6 ESTIMATE A solar sail. Proposals have been made to use the radiation pressure from the Sun to help propel spacecraft around the solar system. (a) About how much force would be applied on a $1 \mathrm{~km} \times 1 \mathrm{~km}$ highly reflective sail when about the same distance from the Sun as the Earth is? (b) By how much would this increase the speed of a $5000-\mathrm{kg}$ spacecraft in one year? (c) If the spacecraft started from rest, about how far would it travel in a year?

APPROACH (a) Pressure $P$ is force per unit area, so $F=P A$. We use the estimate of Example 22-5, doubling it for a reflecting surface $P=2 I / c$. (b) We find the acceleration from Newton's second law, and assume it is constant, and then find the speed from $v=v_{0}+a t$. (c) The distance traveled is given by $x=\frac{1}{2} a t^{2}$.
SOLUTION (a) Doubling the result of Example 22-5, we get a solar pressure that is about $2 \bar{I} / c \approx 10^{-5} \mathrm{~N} / \mathrm{m}^{2}$, rounding off. Then the force is $F \approx P A= \left(10^{-5} \mathrm{~N} / \mathrm{m}^{2}\right)\left(10^{3} \mathrm{~m}\right)\left(10^{3} \mathrm{~m}\right) \approx 10 \mathrm{~N}$.
(b) The acceleration is $a \approx F / m \approx(10 \mathrm{~N}) /(5000 \mathrm{~kg}) \approx 2 \times 10^{-3} \mathrm{~m} / \mathrm{s}^{2}$. One year has $(365$ days $)(24 \mathrm{~h} /$ day $)(3600 \mathrm{~s} / \mathrm{h}) \approx 3 \times 10^{7} \mathrm{~s}$. The speed increase is $v-v_{0}=a t \approx\left(2 \times 10^{-3} \mathrm{~m} / \mathrm{s}^{2}\right)\left(3 \times 10^{7} \mathrm{~s}\right) \approx 6 \times 10^{4} \mathrm{~m} / \mathrm{s}(\approx 200,000 \mathrm{~km} / \mathrm{h}!)$.
(c) Starting from rest, this acceleration would result in a distance traveled of about $d=\frac{1}{2} a t^{2} \approx \frac{1}{2}\left(2 \times 10^{-3} \mathrm{~m} / \mathrm{s}^{2}\right)\left(3 \times 10^{7} \mathrm{~s}\right)^{2} \approx 10^{12} \mathrm{~m}$ in a year, about seven times the Sun-Earth distance. This result would apply if the spacecraft was far from the Earth so the Earth's gravitational force is small compared to 10 N .
NOTE A large sail providing a small force over a long time could result in a lot of motion. [Gravity due to the Sun and planets has been ignored, but in reality would have to be considered.]

Although you cannot directly feel the effects of radiation pressure, the phenomenon is quite dramatic when applied to atoms irradiated by a finely focused laser beam. An atom has a mass on the order of $10^{-27} \mathrm{~kg}$, and a laser beam can deliver energy at a rate of $1000 \mathrm{~W} / \mathrm{m}^{2}$. This is the same intensity used in Example $22-5$, but here a radiation pressure of $10^{-6} \mathrm{~N} / \mathrm{m}^{2}$ would be very significant on a molecule whose mass might be $10^{-23}$ to $10^{-26} \mathrm{~kg}$. It is possible to move atoms and molecules around by steering them with a laser beam, in a device called optical tweezers. Optical tweezers have some remarkable applications. They are of great interest to biologists, especially since optical tweezers can manipulate live microorganisms, and components within a cell, without damaging them. Optical tweezers have been used to measure the elastic properties of DNA by pulling each end of the molecule with such a laser "tweezers."
22-7 Radio and Television; Wireless Communication

PHYSICS APPLIED Wireless transmission

FIGURE 22-12 Guglielmo Marconi (1874-1937), on the left, receiving signals in Cornwall, 1901.

PHYSICS APPLIED
Optical tweezers (move cell parts, DNA elasticity)

Electromagnetic waves offer the possibility of transmitting information over long distances. Among the first to realize this and put it into practice was Guglielmo Marconi (1874-1937) who, in the 1890s, invented and developed wireless communication. With it, messages could be sent at the speed of light without the use of wires. The first signals were merely long and short pulses that could be translated into words by a code, such as the "dots" and "dashes" of the Morse code: they were digital wireless, believe it or not. In 1895 Marconi sent wireless signals a kilometer or two in Italy. By 1901 he had sent test signals 3000 km across the ocean from Newfoundland, Canada, to Cornwall, England (Fig. 22-12). In 1903 he sent the first practical commercial messages from Cape Cod, Massachusetts, to England: the London Times printed news items sent from its New York correspondent. 1903 was also the year of the first powered airplane flight by the Wright brothers. The hallmarks of the modern age-wireless communication and flight-date from the same year. Our modern world of wireless communication, including radio, television, cordless phones, cell phones, Bluetooth, wi-fi, and satellite communication, are based on Marconi's pioneering work.

636
CHAPTER 22 Electromagnetic Waves

---

<!-- Page 637 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13
Page 637

The next decade saw the development of vacuum tubes. Out of this early work radio and television were born. We now discuss briefly (1) how radio and TV signals are transmitted, and (2) how they are received at home.

The process by which a radio station transmits information (words and music) is outlined in Fig. 22-13. The audio (sound) information is changed into an electrical signal of the same frequencies by, say, a microphone, a laser, or a magnetic read/write head. This electrical signal is called an audiofrequency (AF) signal, because the frequencies are in the audio range ( 20 to $20,000 \mathrm{~Hz}$ ). The signal is amplified electronically and is then mixed with a radio-frequency ( RF ) signal called its carrier frequency, which represents that station. AM radio stations have carrier frequencies from about 530 kHz to 1700 kHz . For example, " 710 on your dial" means a station whose carrier frequency is 710 kHz . FM radio stations have much higher carrier frequencies, between 88 MHz and 108 MHz . The carrier frequencies for broadcast TV stations in the United States lie between 54 MHz and 72 MHz , between 76 MHz and 88 MHz , between 174 MHz and 216 MHz , and between 470 MHz and 698 MHz . Today's digital broadcasting (see Sections 17-10 and 17-11) uses the same frequencies as the pre-2009 analog transmission.
a radio transmitter.

The mixing of the audio and carrier frequencies is done in two ways. In
PHYSICS APPLIED amplitude modulation (AM), the amplitude of the high-frequency carrier wave

$A M$ and $F M$ is made to vary in proportion to the amplitude of the audio signal, as shown in Fig. 22-14. It is called "amplitude modulation" because the amplitude of the carrier is altered ("modulate" means to change or alter). In frequency modulation (FM), the frequency of the carrier wave is made to change in proportion to the audio signal's amplitude, as shown in Fig. 22-15. The mixed signal is amplified further and sent to the transmitting antenna (Fig. 22-13), where the complex mixture of frequencies is sent out in the form of EM waves. In digital communication, the signal is put into digital form (Section 17-10) which modulates the carrier.

A television transmitter works in a similar way, using FM for audio and AM for video; both audio and video signals are mixed with carrier frequencies.

FIGURE 22-14 In amplitude modulation (AM), the amplitude of the carrier signal is made to vary in proportion to the audio signal's amplitude.

FIGURE 22-15 In frequency modulation (FM), the frequency of the carrier signal is made to change in proportion to the audio signal's amplitude. This method is used by FM radio and television.

SECTION 22-7 Radio and Television; Wireless Communication
637

---

<!-- Page 638 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13
Page 638

FIGURE 22-16 Block diagram of a simple radio receiver.

FIGURE 22-17 Simple tuning stage of a radio.

Now let us look at the other end of the process, the reception of radio and TV programs at home. A simple radio receiver is diagrammed in Fig. 22-16. The EM waves sent out by all stations are received by the antenna. The signals the antenna detects and sends to the receiver are very small and contain frequencies from many different stations. The receiver uses a resonant $L C$ circuit (Section 21-15) to select out a particular RF frequency (actually a narrow range of frequencies) corresponding to a particular station. A simple way of tuning a station is shown in Fig. 22-17. A particular station is "tuned in" by adjusting $C$ and/or $L$ so that the resonant frequency of the circuit ( $f_{0}=1 /(2 \pi \sqrt{L C})$, Eq. 21-19) equals that of the station's carrier frequency. The signal, containing both audio and carrier frequencies, next goes to the demodulator, or detector (Fig. 22-16), where "demodulation" takes place-that is, the audio signal is separated from the RF carrier frequency. The audio signal is amplified and sent to a loudspeaker or headphones.

Modern receivers have more stages than those shown. Various means are used to increase the sensitivity and selectivity (ability to detect weak signals and distinguish them from other stations), and to minimize distortion of the original signal. ${ }^{\dagger}$

A television receiver does similar things to both the audio and the video signals. The audio signal goes finally to the loudspeaker, and the video signal to the monitor screen, such as an LCD (Sections 17-11 and 24-11).

FIGURE 22-18 Antennas. (a) Electric field of EM wave produces a current in an antenna consisting of straight wire or rods. (b) The moving and changing magnetic field induces an emf and current in a loop antenna.

FIGURE 22-19 A satellite dish.

One kind of antenna consists of one or more conducting rods; the electric field in the EM waves exerts a force on the electrons in the conductor, causing them to move back and forth at the frequencies of the waves (Fig. 22-18a). A second type of antenna consists of a tubular coil of wire which detects the magnetic field of the wave: the changing $B$ field induces an emf in the coil (Fig. 22-18b). A satellite dish (Fig. 22-19) consists of a parabolic reflector that focuses the EM waves onto a "horn," similar to a concave mirror telescope (Fig. 25-22).
${ }^{\dagger}$ For FM stereo broadcasting, two signals are carried by the carrier wave. One signal contains frequencies up to about 15 kHz , which includes most audio frequencies. The other signal includes the same range of frequencies, but 19 kHz is added to it. A stereo receiver subtracts this $19,000-\mathrm{Hz}$ signal and distributes the two signals to the left and right channels. The first signal consists of the sum of left and right channels $(\mathrm{L}+\mathrm{R})$, so monophonic radios (one speaker) detect all the sound. The second signal is the difference between left and right $(\mathrm{L}-\mathrm{R})$. Hence a stereo receiver must add and subtract the two signals to get pure left and right signals for each channel.

638
CHAPTER 22 Electromagnetic Waves

---

<!-- Page 639 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13
Page 639

EXAMPLE 22-7 Tuning a station. Calculate the transmitting wavelength of an FM radio station that transmits at 100.1 MHz .
APPROACH Radio is transmitted as an EM wave, so the speed is $c=3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}$. The wavelength is found from Eq. 22-4, $\lambda=c / f$.
SOLUTION The carrier frequency is $f=100.1 \mathrm{MHz} \approx 1.0 \times 10^{8} \mathrm{~s}^{-1}$, so
$$\lambda=\frac{c}{f}=\frac{\left(3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}\right)}{\left(1.0 \times 10^{8} \mathrm{~s}^{-1}\right)}=3.0 \mathrm{~m} .$$

NOTE The wavelengths of other FM signals ( 88 MHz to 108 MHz ) are close to the $3.0-\mathrm{m}$ wavelength of this station. FM antennas are typically 1.5 m long, or about a half wavelength. This length is chosen so that the antenna reacts in a resonant fashion and thus is more sensitive to FM frequencies. AM radio antennas would have to be very long and impractical to be either $\frac{1}{2} \lambda$ or $\frac{1}{4} \lambda$.

Other EM Wave Communications
The various regions of the radio-wave spectrum are assigned by governmental agencies for various purposes. Besides those mentioned above, there are "bands" assigned for use by ships, airplanes, police, military, amateurs, satellites and space, and radar. Cell phones, for example, are complete radio transmitters and receivers. In the U.S., CDMA cell phones function on two different bands: 800 MHz and $1900 \mathrm{MHz}(=1.9 \mathrm{GHz})$. Europe, Asia, and much of the rest of the world use a different system: the international standard called GSM (Global System for Mobile Communication), on $900-\mathrm{MHz}$ and $1800-\mathrm{MHz}$ bands. The U.S. now also has the GSM option (at 850 MHz and 1.9 GHz ), as does much of the rest of the Americas. A $700-\mathrm{MHz}$ band is being made available for cell phones (it used to carry TV broadcast channels, no longer used). Radio-controlled toys (cars, sailboats, robotic animals, etc.) can use various frequencies from 27 MHz to 75 MHz . Automobile remote entry (keyless) may operate around 300 MHz or 400 MHz .

Cable TV channels are carried as electromagnetic waves along a coaxial cable (Fig. 22-9) rather than being broadcast and received through the "air." The channels are in the same part of the EM spectrum, hundreds of MHz, but some are at frequencies not available for TV broadcast. Digital satellite TV and radio are carried in the microwave portion of the spectrum (12 to 14 GHz and 2.3 GHz , respectively).

Wireless from the Moon
In 1969, astronauts first landed on the Moon. It was shown live on television (Fig. 22-20). The transmitting TV camera can be seen in the Chapter-Opening photo, page 625. At that time, someone pointed out that Columbus and other early navigators could have imagined that humans might one day reach the Moon. But they would never have believed possible that moving images could be sent from the Moon to the Earth through empty space.

FIGURE 22-20 The first person on the Moon, Neil Armstrong, July 20, 1969, pointed out "One small step for a man, one giant leap for mankind."

Summary

James Clerk Maxwell synthesized an elegant theory in which all electric and magnetic phenomena could be described using four equations, now called Maxwell's equations. They are based on earlier ideas, but Maxwell added one more-that a changing electric field produces a magnetic field.

Maxwell's theory predicted that transverse electromagnetic (EM) waves would be produced by accelerating electric charges, and these waves would propagate (move) through space at the speed of light:
$$c=\frac{1}{\sqrt{\epsilon_{0} \mu_{0}}}=3.00 \times 10^{8} \mathrm{~m} / \mathrm{s} .$$

The oscillating electric and magnetic fields in an EM wave are perpendicular to each other and to the direction of propagation. These EM waves are waves of fields, not matter, and can propagate in empty space.

The wavelength $\lambda$ and frequency $f$ of EM waves are related to their speed $c$ by
$$c=\lambda f$$
just as for other waves.

Summary
639

---

<!-- Page 640 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 640

After EM waves were experimentally detected, it became generally accepted that light is an EM wave. The electromagnetic spectrum includes EM waves of a wide variety of wavelengths, from microwaves and radio waves to visible light to X-rays and gamma rays, all of which travel through space at a speed $c=3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}$.

The average intensity ( $\mathrm{W} / \mathrm{m}^{2}$ ) of an EM wave is
$$\bar{I}=\frac{1}{2} \epsilon_{0} c E_{0}^{2}=\frac{1}{2} \frac{c}{\mu_{0}} B_{0}^{2}=\frac{1}{2} \frac{E_{0} B_{0}}{\mu_{0}},$$

Questions
1. The electric field in an EM wave traveling north oscillates in an east-west plane. Describe the direction of the magnetic field vector in this wave. Explain.
2. Is sound an EM wave? If not, what kind of wave is it?
3. Can EM waves travel through a perfect vacuum? Can sound waves?
4. When you flip a light switch on, does the light go on immediately? Explain.
5. Are the wavelengths of radio and television signals longer or shorter than those detectable by the human eye?
6. When you connect two loudspeakers to the output of a stereo amplifier, should you be sure the lead-in wires are equal in length to avoid a time lag between speakers? Explain.
7. In the electromagnetic spectrum, what type of EM wave would have a wavelength of $10^{3} \mathrm{~km}$ ? 1 km ? 1 m ? 1 cm ? 1 mm ? $1 \mu \mathrm{~m}$ ?
where $E_{0}$ and $B_{0}$ are the peak values of the electric and magnetic fields, respectively, in the wave.

EM waves carry momentum and exert a radiation pressure proportional to the intensity $I$ of the wave.

Radio, TV, cell phone, and other wireless signals are transmitted through space in the radio-wave or microwave part of the EM spectrum.
8. Can radio waves have the same frequencies as sound waves $(20 \mathrm{~Hz}-20,000 \mathrm{~Hz}) ?$
9. If a radio transmitter has a vertical antenna, should a receiver's antenna (rod type) be vertical or horizontal to obtain best reception?
10. The carrier frequencies of FM broadcasts are much higher than for AM broadcasts. On the basis of what you learned about diffraction in Chapter 11, explain why AM signals can be detected more readily than FM signals behind low hills or buildings.
11. Discuss how cordless telephones make use of EM waves. What about cell phones?
12. A lost person may signal by switching a flashlight on and off using Morse code. This is actually a modulated EM wave. Is it AM or FM? What is the frequency of the carrier, approximately?

MisConceptual Questions
1. In a vacuum, what is the difference between a radio wave and an X-ray?
(a) Wavelength.
(b) Frequency.
(c) Speed.
2. The radius of an atom is on the order of $10^{-10} \mathrm{~m}$. In comparison, the wavelength of visible light is
(a) much smaller.
(b) about the same size.
(c) much larger.
3. Which of the following travel at the same speed as light? (Choose all that apply.)
(a) Radio waves.
(d) Ultrasonic waves.
(g) Gamma rays.
(b) Microwaves.
(e) Infrared radiation.
(h) X-rays.
(c) Radar.
(f) Cell phone signals.
4. Which of the following types of electromagnetic radiation travels the fastest?
(a) Radio waves.
(b) Visible light waves.
(c) X-rays.
(d) Gamma rays.
(e) All the above travel at the same speed.
5. In empty space, which quantity is always larger for X-ray radiation than for a radio wave?
(a) Amplitude.
(c) Frequency.
(b) Wavelength.
(d) Speed.
6. If electrons in a wire vibrate up and down 1000 times per second, they will create an electromagnetic wave having
(a) a wavelength of 1000 m .
(c) a speed of $1000 \mathrm{~m} / \mathrm{s}$.
(b) a frequency of 1000 Hz .
(d) an amplitude of 1000 m .
7. If the Earth-Sun distance were doubled, the intensity of radiation from the Sun that reaches the Earth's surface would (a) quadruple. (b) double. (c) drop to $\frac{1}{2}$. (d) drop to $\frac{1}{4}$.

640
CHAPTER 22 Electromagnetic Waves
8. An electromagnetic wave is traveling straight down toward the center of the Earth. At a certain moment in time the electric field points west. In which direction does the magnetic field point at this moment?
(a) North.
(d) West.
(g) Either (a) or (b).
(b) South.
(e) Up.
(h) Either (c) or (d).
(c) East.
(f) Down.
(i) Either (e) or (f).
9. If the intensity of an electromagnetic wave doubles,
(a) the electric field must also double.
(b) the magnetic field must also double.
(c) both the magnetic field and the electric field must increase by a factor of $\sqrt{2}$.
(d) Any of the above.
10. If all else is the same, for which surface would the radiation pressure from light be the greatest?
(a) A black surface.
(b) A gray surface.
(c) A yellow surface.
(d) A white surface.
(e) All experience the same radiation pressure, because they are exposed to the same light.
11. Starting in 2009, TV stations in the U.S. switched to digital signals. [See Sections 22-7, 17-10, and 17-11.] To watch today's digital broadcast TV, could you use a pre-2009 TV antenna meant for analog? Explain.
(a) No; analog antennas do not receive digital signals.
(b) No; digital signals are broadcast at different frequencies, so you need a different antenna.
(c) Yes; digital signals are broadcast with the same carrier frequencies, so your old antenna will be fine.
(d) No; you cannot receive digital signals through an antenna and need to switch to cable or satellite.

---

<!-- Page 641 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 641-
For assigned homework and other learning materials, go to the MasteringPhysics website.

Problems

22-1 $\overrightarrow{\mathbf{B}}$ Produced by Changing $\overrightarrow{\mathbf{E}}$
*1. (II) Determine the rate at which the electric field changes between the round plates of a capacitor, 8.0 cm in diameter, if the plates are spaced 1.1 mm apart and the voltage across them is changing at a rate of $120 \mathrm{~V} / \mathrm{s}$.
*2. (II) Calculate the displacement current $I_{\mathrm{D}}$ between the square plates, 5.8 cm on a side, of a capacitor if the electric field is changing at a rate of $1.6 \times 10^{6} \mathrm{~V} / \mathrm{m} \cdot \mathrm{s}$.
*3. (II) At a given instant, a 3.8-A current flows in the wires connected to a parallel-plate capacitor. What is the rate at which the electric field is changing between the plates if the square plates are 1.60 cm on a side?
*4. (III) A $1500-\mathrm{nF}$ capacitor with circular parallel plates 2.0 cm in diameter is accumulating charge at the rate of $32.0 \mathrm{mC} / \mathrm{s}$ at some instant in time. What will be the induced magnetic field strength 10.0 cm radially outward from the center of the plates? What will be the value of the field strength after the capacitor is fully charged?

22-2 EM Waves
5. (I) If the electric field in an EM wave has a peak magnitude of $0.72 \times 10^{-4} \mathrm{~V} / \mathrm{m}$, what is the peak magnitude of the magnetic field strength?
6. (I) If the magnetic field in a traveling EM wave has a peak magnitude of 10.5 nT , what is the peak magnitude of the electric field?
7. (I) In an EM wave traveling west, the $B$ field oscillates up and down vertically and has a frequency of 90.0 kHz and an rms strength of $7.75 \times 10^{-9} \mathrm{~T}$. Determine the frequency and rms strength of the electric field. What is the direction of its oscillations?
8. (I) How long does it take light to reach us from the Sun, $1.50 \times 10^{8} \mathrm{~km}$ away?
9. (II) How long should it take the voices of astronauts on the Moon to reach the Earth? Explain in detail.

22-3 Electromagnetic Spectrum
10. (I) An EM wave has a wavelength of 720 nm . What is its frequency, and how would we classify it?
11. (I) An EM wave has frequency $7.14 \times 10^{14} \mathrm{~Hz}$. What is its wavelength, and how would we classify it?
12. (I) A widely used "short-wave" radio broadcast band is referred to as the $49-\mathrm{m}$ band. What is the frequency of a $49-\mathrm{m}$ radio signal?
13. (I) What is the frequency of a microwave whose wavelength is 1.50 cm ?
14. (II) Electromagnetic waves and sound waves can have the same frequency. (a) What is the wavelength of a $1.00-\mathrm{kHz}$ electromagnetic wave? (b) What is the wavelength of a $1.00-\mathrm{kHz}$ sound wave? (The speed of sound in air is $341 \mathrm{~m} / \mathrm{s}$.) (c) Can you hear a $1.00-\mathrm{kHz}$ electromagnetic wave?
15. (II) (a) What is the wavelength of a $22.75 \times 10^{9} \mathrm{~Hz}$ radar signal? (b) What is the frequency of an X-ray with wavelength 0.12 nm ?
16. (II) How long would it take a message sent as radio waves from Earth to reach Mars when Mars is (a) nearest Earth, (b) farthest from Earth? Assume that Mars and Earth are in the same plane and that their orbits around the Sun are circles (Mars is $\approx 230 \times 10^{6} \mathrm{~km}$ from the Sun).
17. (II) Our nearest star (other than the Sun) is 4.2 light-years away. That is, it takes 4.2 years for the light it emits to reach Earth. How far away is it in meters?
18. (II) A light-year is a measure of distance (not time). How many meters does light travel in a year?
19. (II) Pulsed lasers used for science and medicine produce very brief bursts of electromagnetic energy. If the laser light wavelength is 1062 nm (Neodymium-YAG laser), and the pulse lasts for 34 picoseconds, how many wavelengths are found within the laser pulse? How brief would the pulse need to be to fit only one wavelength?

22-4 Measuring the Speed of Light
20. (II) What is the minimum angular speed at which Michelson's eight-sided mirror would have had to rotate to reflect light into an observer's eye by succeeding mirror faces ( $1 / 8$ of a revolution, Fig. 22-10)?
21. (II) A student wants to scale down Michelson's light-speed experiment to a size that will fit in one room. An eightsided mirror is available, and the stationary mirror can be mounted 12 m from the rotating mirror. If the arrangement is otherwise as shown in Fig. 22-10, at what minimum rate must the mirror rotate?

22-5 Energy in EM Wave
22. (I) The $\overrightarrow{\mathbf{E}}$ field in an EM wave has a peak of $22.5 \mathrm{mV} / \mathrm{m}$. What is the average rate at which this wave carries energy across unit area per unit time?
23. (II) The magnetic field in a traveling EM wave has an rms strength of 22.5 nT . How long does it take to deliver 365 J of energy to $1.00 \mathrm{~cm}^{2}$ of a wall that it hits perpendicularly?
24. (II) How much energy is transported across a $1.00-\mathrm{cm}^{2}$ area per hour by an EM wave whose $E$ field has an rms strength of $30.8 \mathrm{mV} / \mathrm{m}$ ?
25. (II) A spherically spreading EM wave comes from an 1800-W source. At a distance of 5.0 m , what is the intensity, and what is the rms value of the electric field?
26. (II) If the amplitude of the $B$ field of an EM wave is $2.2 \times 10^{-7} \mathrm{~T}$, (a) what is the amplitude of the $E$ field? (b) What is the average power transported across unit area by the EM wave?
27. (II) What is the average energy contained in a $1.00-\mathrm{m}^{3}$ volume near the Earth's surface due to radiant energy from the Sun? See Example 22-4.
28. (II) A $15.8-\mathrm{mW}$ laser puts out a narrow beam 2.40 mm in diameter. What are the rms values of $E$ and $B$ in the beam?
29. (II) Estimate the average power output of the Sun, given that about $1350 \mathrm{~W} / \mathrm{m}^{2}$ reaches the upper atmosphere of the Earth.
30. (II) A high-energy pulsed laser emits a $1.0-\mathrm{ns}$-long pulse of average power $1.5 \times 10^{11} \mathrm{~W}$. The beam is nearly a cylinder $2.2 \times 10^{-3} \mathrm{~m}$ in radius. Determine (a) the energy delivered in each pulse, and ( $b$ ) the rms value of the electric field.

Problems
641

---

<!-- Page 642 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 642

22-6 Radiation Pressure
31. (II) Estimate the radiation pressure due to a bulb that emits 25 W of EM radiation at a distance of 9.5 cm from the center of the bulb. Estimate the force exerted on your fingertip if you place it at this point.
32. (II) What size should the solar panel on a satellite orbiting Jupiter be if it is to collect the same amount of radiation from the Sun as a $1.0-\mathrm{m}^{2}$ solar panel on a satellite orbiting Earth? [Hint: Assume the inverse square law (Eq. 11-16b).]
33. (III) Suppose you have a car with a $100-\mathrm{hp}$ engine. How large a solar panel would you need to replace the engine with solar power? Assume that the solar panels can utilize $20 \%$ of the maximum solar energy that reaches the Earth's surface $\left(1000 \mathrm{~W} / \mathrm{m}^{2}\right)$.
22-7 Radio, TV
34. (I) What is the range of wavelengths for (a) FM radio ( 88 MHz to 108 MHz ) and (b) AM radio ( 535 kHz to 1700 kHz )?
35. (I) Estimate the wavelength for a $1.9-\mathrm{GHz}$ cell phone transmitter.
36. (I) Compare 980 on the AM dial to 98.1 on FM. Which has the longer wavelength, and by what factor is it larger?
37. (I) The variable capacitor in the tuner of an AM radio has a capacitance of 2500 pF when the radio is tuned to a station at 550 kHz . What must the capacitance be for a station near the other end of the dial, 1610 kHz ?
38. (II) A certain FM radio tuning circuit has a fixed capacitor $C=810 \mathrm{pF}$. Tuning is done by a variable inductance. What range of values must the inductance have to tune stations from 88 MHz to 108 MHz ?
39. (II) An amateur radio operator wishes to build a receiver that can tune a range from 14.0 MHz to 15.0 MHz . A variable capacitor has a minimum capacitance of 86 pF . (a) What is the required value of the inductance? (b) What is the maximum capacitance used on the variable capacitor?
40. (II) A satellite beams microwave radiation with a power of 13 kW toward the Earth's surface, 550 km away. When the beam strikes Earth, its circular diameter is about 1500 m . Find the rms electric field strength of the beam.
41. (III) A 1.60-m-long FM antenna is oriented parallel to the electric field of an EM wave. How large must the electric field be to produce a $1.00-\mathrm{mV}(\mathrm{rms})$ voltage between the ends of the antenna? What is the rate of energy transport per $\mathrm{m}^{2}$ ?

General Problems
42. Who will hear the voice of a singer first: a person in the balcony 50.0 m away from the stage (see Fig. 22-21), or a person 1200 km away at home whose ear is next to the radio listening to a live broadcast? Roughly how much sooner? Assume the microphone is a few centimeters from the singer and the temperature is $20^{\circ} \mathrm{C}$.

FIGURE 22-21 Problem 42.
43. A global positioning system (GPS) functions by determining the travel times for EM waves from various satellites to a land-based GPS receiver. If the receiver is to detect a change in travel distance on the order of 3 m , what is the associated change in travel time (in ns ) that must be measured?
44. The voice from an astronaut on the Moon (Fig. 22-22) was beamed to a listening crowd on Earth. If you were standing 28 m from the loudspeaker on Earth, what was the total time lag between when you heard the sound and when the sound entered a microphone on the Moon? Explain whether the microphone was inside the space helmet, or outside, and why.

FIGURE 22-22
Problem 44.
45. Radio-controlled clocks throughout the United States receive a radio signal from a transmitter in Fort Collins, Colorado, that accurately (within a microsecond) marks the beginning of each minute. A slight delay, however, is introduced because this signal must travel from the transmitter to the clocks. Assuming Fort Collins is no more than 3000 km from any point in the U.S., what is the longest travel-time delay?
46. If the Sun were to disappear or radically change its output, how long would it take for us on Earth to learn about it?
47. Cosmic microwave background radiation fills space with an average energy density of about $4 \times 10^{-14} \mathrm{~J} / \mathrm{m}^{3}$. (a) Find the rms value of the electric field associated with this radiation. (b) How far from a $7.5-\mathrm{kW}$ radio transmitter emitting uniformly in all directions would you find a comparable value?
48. Estimate the rms electric field in the sunlight that hits Mars, knowing that the Earth receives about $1350 \mathrm{~W} / \mathrm{m}^{2}$ and that Mars is 1.52 times farther from the Sun (on average) than is the Earth.
49. The average intensity of a particular TV station's signal is $1.0 \times 10^{-13} \mathrm{~W} / \mathrm{m}^{2}$ when it arrives at a $33-\mathrm{cm}$-diameter satellite TV antenna. (a) Calculate the total energy received by the antenna during 4.0 hours of viewing this station's programs. (b) Estimate the amplitudes of the $E$ and $B$ fields of the EM wave.
50. What length antenna would be appropriate for a portable device that could receive satellite TV?
51. A radio station is allowed to broadcast at an average power not to exceed 25 kW . If an electric field amplitude of $0.020 \mathrm{~V} / \mathrm{m}$ is considered to be acceptable for receiving the radio transmission, estimate how many kilometers away you might be able to detect this station.

642
CHAPTER 22 Electromagnetic Waves

---

<!-- Page 643 -->

GIAN_PPA7_GE_22_625-643v4.1HR1.QXD 29-08-2014 15:13 Page 643
52. The radiation pressure (Section 22-6) created by electromagnetic waves might someday be used to power spacecraft through the use of a "solar sail," Example 22-6. (a) Assuming total reflection, what would be the pressure on a solar sail located at the same distance from the Sun as the Earth (where $I=1350 \mathrm{~W} / \mathrm{m}^{2}$ )? (b) Suppose the sail material has a mass of $1 \mathrm{~g} / \mathrm{m}^{2}$. What would be the acceleration of the sail due to solar radiation pressure? (c) A realistic solar sail would have a payload. How big a sail would you need to accelerate a $100-\mathrm{kg}$ payload at $1 \times 10^{-3} \mathrm{~m} / \mathrm{s}^{2}$ ?
53. Suppose a $35-\mathrm{kW}$ radio station emits EM waves uniformly in all directions. (a) How much energy per second crosses a $1.0-\mathrm{m}^{2}$ area 1.0 km from the transmitting antenna? (b) What is the rms magnitude of the $\overrightarrow{\mathbf{E}}$ field at this point, assuming the station is operating at full power? What is the rms voltage induced in a $1.0-\mathrm{m}$-long vertical car antenna (c) 1.0 km away, (d) 50 km away?

Search and Learn
1. How practical is solar power for various devices? Assume that on a sunny day, sunlight has an intensity of $1000 \mathrm{~W} / \mathrm{m}^{2}$ at the surface of Earth and that a solar-cell panel can convert $20 \%$ of that sunlight into electric power. Calculate the area $A$ of solar panel needed to power (a) a calculator that consumes $50 \mathrm{~mW},(b)$ a hair dryer that consumes 1500 W , (c) a car that would require 40 hp . (d) In each case, would the area $A$ be small enough to be mounted on the device itself, or in the case of (b) on the roof of a house?
2. The Arecibo radio telescope in Puerto Rico can detect a radio wave with an intensity as low as $1 \times 10^{-23} \mathrm{~W} / \mathrm{m}^{2}$. Consider a "best-case" scenario for communication with extraterrestrials: suppose an advanced civilization a distance $x$ away from Earth is able to transform the entire power output of a Sun-like star completely into a radio-wave signal which is transmitted uniformly in all directions. (a) In order for Arecibo to detect this radio signal, what is the maximum value for $x$ in light-years ( $1 \mathrm{ly} \approx 10^{16} \mathrm{~m}$ )? (b) How does this maximum value compare with the 100,000 -ly size of our Milky Way galaxy? The intensity of sunlight at Earth's orbital distance from the Sun is $1350 \mathrm{~W} / \mathrm{m}^{2}$. [Hint: Assume the inverse square law (Eq. 11-16b).]
54. A point source emits light energy uniformly in all directions at an average rate $P_{0}$ with a single frequency $f$. Show that the peak electric field in the wave is given by
$$E_{0}=\sqrt{\frac{\mu_{0} c P_{0}}{2 \pi r^{2}}} .$$
[Hint: The surface area of a sphere is $4 \pi r^{2}$.]
55. What is the maximum power level of a radio station so as to avoid electrical breakdown of air at a distance of 0.65 m from the transmitting antenna? Assume the antenna is a point source. Air breaks down in an electric field of about $3 \times 10^{6} \mathrm{~V} / \mathrm{m}$.
56. Estimate how long an AM antenna would have to be if it were (a) $\frac{1}{2} \lambda$ or (b) $\frac{1}{4} \lambda$. AM radio is roughly $1 \mathrm{MHz}(530 \mathrm{kHz}$ to 1.7 MHz ).
57. 12 km from a radio station's transmitting antenna, the amplitude of the electric field is $0.12 \mathrm{~V} / \mathrm{m}$. What is the average power output of the radio station?
3. Laser light can be focused (at best) to a spot with a radius $r$ equal to its wavelength $\lambda$. Suppose a $1.0-\mathrm{W}$ beam of green laser light $\left(\lambda=5 \times 10^{-7} \mathrm{~m}\right)$ forms such a spot and illuminates a cylindrical object of radius $r$ and length $r$ (Fig. 22-23). Estimate (a) the radiation pressure and force on the object, and (b) its acceleration, if its density equals that of water and it absorbs all the radiation. [This order-of-magnitude calculation convinced researchers of the feasibility of "optical tweezers," page 636.]

FIGURE 22-23
Search and Learn 3. $\lambda=5 \times 10^{-7} \mathrm{~m}$

ANSWERS TO EXERCISES

A: (c).
B: (b).
C: (a) $3.8 \times 10^{6} \mathrm{~Hz}$; (b) $5.5 \times 10^{18} \mathrm{~Hz}$.

D: 45 cm .
E: Yes; the signal still travels $72,000 \mathrm{~km}$.
F: Over 4 hours.

Search and Learn
643

---

