# Chapter 28: Quantum Mechanics of Atoms

<!-- Page 803 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 803

A neon tube is a thin glass tube, moldable into various shapes, filled with neon (or other) gas that glows with a particular color when a current at high voltage passes through it. Gas atoms, excited to upper energy levels, jump down to lower energy levels and emit light (photons) whose wavelengths (color) are characteristic of the type of gas.

In this Chapter we study what quantum mechanics tells us about atoms, their energy levels, and the effect of the exclusion principle for atoms with more than one electron. We also discuss interesting applications such as lasers and holography.

Quantum Mechanics of Atoms

CHAPTER-OPENING QUESTION-Guess now!
The uncertainty principle states that
(a) no measurement can be perfect because it is technologically impossible to make perfect measuring instruments.
(b) it is impossible to measure exactly where a particle is, unless it is at rest.
(c) it is impossible to simultaneously know both the position and the momentum of a particle with complete certainty.
(d) a particle cannot actually have a completely certain value of momentum.

Bohr's model of the atom gave us a first (though rough) picture of what an atom is like. It proposed explanations for why there is emission and absorption of light by atoms at only certain wavelengths. The wavelengths of the line spectra and the ionization energy for hydrogen (and one-electron ions) are in excellent agreement with experiment. But the Bohr model had important limitations. It was not able to predict line spectra for more complex atoms-atoms with more than one electron-not even for the neutral helium atom, which has only two electrons. Nor could it explain why emission lines, when viewed with great precision, consist of two or more very closely spaced lines (referred to as fine structure). The Bohr model also did not explain why some spectral lines were brighter than others. And it could not explain the bonding of atoms in molecules or in solids and liquids.

From a theoretical point of view, too, the Bohr model was not satisfactory: it was a strange mixture of classical and quantum ideas. Moreover, the wave-particle duality was not really resolved.

CONTENTS
28-1 Quantum MechanicsA New Theory
28-2 The Wave Function and Its Interpretation; the DoubleSlit Experiment
28-3 The Heisenberg Uncertainty Principle
28-4 Philosophic Implications; Probability versus Determinism
28-5 Quantum-Mechanical View of Atoms
28-6 Quantum Mechanics of the Hydrogen Atom; Quantum Numbers
28-7 Multielectron Atoms; the Exclusion Principle
28-8 The Periodic Table of Elements
*28-9 X-Ray Spectra and Atomic Number
*28-10 Fluorescence and Phosphorescence
28-11 Lasers
*28-12 Holography

803

---

<!-- Page 804 -->

GIAN_PPA7_28_803-828v5.1HR_SL.QXD 6/27/16 2:56 PM Page 804

FIGURE 28-1 Erwin Schrödinger with Lise Meitner. (She was a codiscoverer of nuclear fission, Chapter 31.)

FIGURE 28-2 Werner Heisenberg (center) on Lake Como (Italy) with Enrico Fermi (left) and Wolfgang Pauli (right).

We mention these limitations of the Bohr model not to disparage it-for it was a landmark in the history of science. Rather, we mention them to show why, in the early 1920s, it became increasingly evident that a new, more comprehensive theory was needed. It was not long in coming. Less than two years after de Broglie gave us his matter-wave hypothesis, Erwin Schrödinger (1887-1961; Fig. 28-1) and Werner Heisenberg (1901-1976; Fig. 28-2) independently developed a new comprehensive theory.
28-1 Quantum Mechanics-A New Theory
The new theory, called quantum mechanics, has been extremely successful. It unifies the wave-particle duality into a single consistent theory and has successfully dealt with the spectra emitted by complex atoms, even the fine details. It explains the relative brightness of spectral lines and how atoms form molecules. It is also a much more general theory that covers all quantum phenomena from blackbody radiation to atoms and molecules. It has explained a wide range of natural phenomena and from its predictions many new practical devices have become possible. Indeed, it has been so successful that it is accepted today by nearly all physicists as the fundamental theory underlying physical processes.

Quantum mechanics deals mainly with the microscopic world of atoms and light. But this new theory, when it is applied to macroscopic phenomena, must be able to produce the old classical laws. This, the correspondence principle (already mentioned in Section 27-12), is satisfied fully by quantum mechanics.

This doesn't mean we should throw away classical theories such as Newton's laws. In the everyday world, classical laws are far easier to apply and they give sufficiently accurate descriptions. But when we deal with high speeds, close to the speed of light, we must use the theory of relativity; and when we deal with the tiny world of the atom, we use quantum mechanics.

Although we won't go into the detailed mathematics of quantum mechanics, we will discuss the main ideas and how they involve the wave and particle properties of matter to explain atomic structure and other applications.
28-2 The Wave Function and Its Interpretation; the Double-Slit Experiment

The important properties of any wave are its wavelength, frequency, and amplitude. For an electromagnetic wave, the frequency (or wavelength) determines whether the light is in the visible spectrum or not, and if so, what color it is. We also have seen that the frequency is a measure of the energy of the corresponding photon, $E=h f$ (Eq. 27-4). The amplitude or displacement of an electromagnetic wave at any point is the strength of the electric (or magnetic) field at that point, and is related to the intensity of the wave (the brightness of the light).

804
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 805 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 805

For material particles such as electrons, quantum mechanics relates the wavelength to momentum according to de Broglie's formula, $\lambda=h / p$ Eq. 27-8. But what corresponds to the amplitude or displacement of a matter wave? The amplitude of an electromagnetic wave is represented by the electric and magnetic fields, $E$ and $B$. In quantum mechanics, this role is played by the wave function, which is given the symbol $\Psi$ (the Greek capital letter psi, pronounced "sigh"). Thus $\Psi$ represents the wave displacement, as a function of time and position, of a new kind of field which we might call a "matter" field or a matter wave.

To understand how to interpret the wave function $\Psi$, we make an analogy with light using the wave-particle duality.

We saw in Chapter 11 that the intensity I of any wave is proportional to the square of the amplitude. This holds true for light waves as well, as we saw in Chapter 22. That is,
$$I \propto E^{2}$$
where $E$ is the electric field strength. From the particle point of view, the intensity of a light beam (of given frequency) is proportional to the number of photons, $N$, that pass through a given area per unit time. The more photons there are, the greater the intensity. Thus
$$I \propto E^{2} \propto N$$

This proportion can be turned around so that we have
$$N \propto E^{2}$$

That is, the number of photons (striking a page of this book, say) is proportional to the square of the electric field strength.

If the light beam is very weak, only a few photons will be involved. Indeed, it is possible to "build up" a photograph in a camera using very weak light so the effect of photons arriving can be seen. If we are dealing with only one photon, the relationship above ( $N \propto E^{2}$ ) can be interpreted in a slightly different way. At any point, the square of the electric field strength $E^{2}$ is a measure of the probability that a photon will be at that location. At points where $E^{2}$ is large, there is a high probability the photon will be there; where $E^{2}$ is small, the probability is low.

We can interpret matter waves in the same way, as was first suggested by Max Born (1882-1970) in 1927. The wave function $\Psi$ may vary in magnitude from point to point in space and time. If $\Psi$ describes a collection of many electrons, then $\Psi^{2}$ at any point will be proportional to the number of electrons expected to be found at that point. When dealing with small numbers of electrons we can't make very exact predictions, so $\Psi^{2}$ takes on the character of a probability. If $\Psi$, which depends on time and position, represents a single electron (say, in an atom), then $\Psi^{2}$ is interpreted like this: $\Psi^{2}$ at a certain point in space and time represents the probability of finding the electron at the given position and time. Thus $\Psi^{2}$ is often referred to as the probability density or probability distribution.

Double-Slit Interference Experiment for Electrons
To understand this better, we take as a thought experiment the familiar double-slit experiment, and consider it both for light and for electrons.

Consider two slits whose size and separation are on the order of the wavelength of whatever we direct at them, either light or electrons, Fig. 28-3. We know very well what would happen in this case for light, since this is just Young's double-slit experiment (Section 24-3): an interference pattern would be seen on the screen behind. If light were replaced by electrons with wavelength comparable to the slit size, they too would produce an interference pattern (recall Fig. 27-12). In the case of light, the pattern would be visible to the eye or could be recorded on film, semiconductor sensor, or screen. For electrons, a fluorescent screen could be used (it glows where an electron strikes).

FIGURE 28-3 Parallel beam, of light or electrons, falls on two slits whose sizes are comparable to the wavelength. An interference pattern is observed.

SECTION 28-2 The Wave Function and Its Interpretation; the Double-Slit Experiment
805

---

<!-- Page 806 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 806

FIGURE 28-4 Young's double-slit experiment done with electronsnote that the pattern is not evident with only a few electrons (top photo), but with more and more electrons (second and third photos), the familiar double-slit interference pattern (Chapter 24) is seen.

If we reduced the flow of electrons (or photons) so they passed through the slits one at a time, we would see a flash each time one struck the screen. At first, the flashes would seem random. Indeed, there is no way to predict just where any one electron would hit the screen. If we let the experiment run for a long time, and kept track of where each electron hit the screen, we would soon see a pattern emerging-the interference pattern predicted by the wave theory; see Fig. 28-4. Thus, although we could not predict where a given electron would strike the screen, we could predict probabilities. (The same can be said for photons.) The probability, as we saw, is proportional to $\Psi^{2}$. Where $\Psi^{2}$ is zero, we would get a minimum in the interference pattern. And where $\Psi^{2}$ is a maximum, we would get a peak in the interference pattern.

The interference pattern would thus occur even when electrons (or photons) passed through the slits one at a time. So the interference pattern could not arise from the interaction of one electron with another. It is as if an electron passed through both slits at the same time, interfering with itself. This is possible because an electron is not precisely a particle. It is as much a wave as it is a particle, and a wave could travel through both slits at once. But what would happen if we covered one of the slits so we knew that the electron passed through the other slit, and a little later we covered the second slit so the electron had to have passed through the first slit? The result would be that no interference pattern would be seen. We would see, instead, two bright areas (or diffraction patterns) on the screen behind the slits.

If both slits are open, the screen shows an interference pattern as if each electron passed through both slits, like a wave. Yet each electron would make a tiny spot on the screen as if it were a particle.

The main point of this discussion is this: if we treat electrons (and other particles) as if they were waves, then $\Psi$ represents the wave amplitude. If we treat them as particles, then we must treat them on a probabilistic basis. The square of the wave function, $\Psi^{2}$, gives the probability of finding a given electron at a given point. We cannot predict-or even follow-the path of a single electron precisely through space and time.

28-3 The Heisenberg Uncertainty Principle
Whenever a measurement is made, some uncertainty is always involved. For example, you cannot make an absolutely exact measurement of the length of a table. Even with a measuring stick that has markings 1 mm apart, there will be an inaccuracy of perhaps $\frac{1}{2} \mathrm{~mm}$ or so. More precise instruments will produce more precise measurements. But there is always some uncertainty involved in a measurement, no matter how good the measuring device. We expect that by using more precise instruments, the uncertainty in a measurement can be made indefinitely small.

But according to quantum mechanics, there is actually a limit to the precision of certain measurements. This limit is not a restriction on how well instruments can be made; rather, it is inherent in nature. It is the result of two factors: the wave-particle duality, and the unavoidable interaction between the thing observed and the observing instrument. Let us look at this in more detail.

To make a measurement on an object without disturbing it, at least a little, is not possible. Consider trying to locate a lost Ping-pong ball in a dark room: you could probe about with your hand or a stick, or you could shine a light and detect the photons reflecting off the ball. When you search with your hand or a stick, you find the ball's position when you touch it, but at the same time you unavoidably bump it, and give it some momentum. Thus you won't know its future position. If you search for the Ping-pong ball using light, in order to "see" the ball at least one photon (really, quite a few) must scatter from it, and the reflected photon must enter your eye or some other detector. When a photon strikes an ordinary-sized object, it only slightly alters the motion or position of the object.

806
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 807 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 807

But a photon striking a tiny object like an electron transfers enough momentum to greatly change the electron's motion and position in an unpredictable way. The mere act of measuring the position of an object at one time makes our knowledge of its future position imprecise.

Now let us see where the wave-particle duality comes in. Imagine a thought experiment in which we are trying to measure the position of an object, say an electron, with photons, Fig. 28-5. (The arguments would be similar if we were using, instead, an electron microscope.) As we saw in Chapter 25, objects can be seen to a precision at best of about the wavelength of the radiation used due to diffraction. If we want a precise position measurement, we must use a short wavelength. But a short wavelength corresponds to high frequency and large momentum ( $p=h / \lambda$ ); and the more momentum the photons have, the more momentum they can give the object when they strike it. If we use photons of longer wavelength, and correspondingly smaller momentum, the object's motion when struck by the photons will not be affected as much. But the longer wavelength means lower resolution, so the object's position will be less accurately known. Thus the act of observing produces an uncertainty in both the position and the momentum of the electron. This is the essence of the uncertainty principle first enunciated by Heisenberg in 1927.

Quantitatively, we can make an approximate calculation of the magnitude of the uncertainties. If we use light of wavelength $\lambda$, the position can be measured at best to a precision of about $\lambda$. That is, the uncertainty in the position measurement, $\Delta x$, is approximately
$$\Delta x \approx \lambda .$$

Suppose that the object can be detected by a single photon. The photon has a momentum $p_{x}=h / \lambda$ (Eq. 27-6). When the photon strikes our object, it will give some or all of this momentum to the object, Fig. 28-5. Therefore, the final $x$ momentum of our object will be uncertain in the amount
$$\Delta p_{x} \approx \frac{h}{\lambda}$$
since we can't tell how much momentum will be transferred. The product of these uncertainties is
$$(\Delta x)\left(\Delta p_{x}\right) \approx(\lambda)\left(\frac{h}{\lambda}\right) \approx h .$$

The uncertainties could be larger than this, depending on the apparatus and the number of photons needed for detection. A more careful mathematical calculation shows the product of the uncertainties as, at best, about
$$(\Delta x)\left(\Delta p_{x}\right) \gtrsim \frac{h}{2 \pi}$$

This is a mathematical statement of the Heisenberg uncertainty principle, or, as it is sometimes called, the indeterminancy principle. It tells us that we cannot measure both the position and momentum of an object precisely at the same time. The more accurately we try to measure the position, so that $\Delta x$ is small, the greater will be the uncertainty in momentum, $\Delta p_{x}$. If we try to measure the momentum very accurately, then the uncertainty in the position becomes large. The uncertainty principle does not forbid individual precise measurements, however. For example, in principle we could measure the position of an object exactly. But then its momentum would be completely unknown. Thus, although we might know the position of the object exactly at one instant, we could have no idea at all where it would be a moment later. The uncertainties expressed here are inherent in nature, and reflect the best precision theoretically attainable even with the best instruments.

FIGURE 28-5 Thought experiment for observing an electron with a powerful light microscope. At least one photon must scatter from the electron (transferring some momentum to it) and enter the microscope.

UNCERTAINTY PRINCIPLE (position and momentum)

SECTION 28-3 The Heisenberg Uncertainty Principle
807

---

<!-- Page 808 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 808

UNCERTAINTY PRINCIPLE (energy and time)

EXERCISE A Return to the Chapter-Opening Question, page 803, and answer it again now. Try to explain why you may have answered differently the first time.

Another useful form of the uncertainty principle relates energy and time, and we examine this as follows. The object to be detected has an uncertainty in position $\Delta x \approx \lambda$. The photon that detects it travels with speed $c$, and it takes a time $\Delta t \approx \Delta x / c \approx \lambda / c$ to pass through the distance of uncertainty. Hence, the measured time when our object is at a given position is uncertain by about
$$\Delta t \approx \frac{\lambda}{c}$$

Since the photon can transfer some or all of its energy ( $=h f=h c / \lambda$ ) to our object, the uncertainty in energy of our object as a result is
$$\Delta E \approx \frac{h c}{\lambda}$$

The product of these two uncertainties is
$$(\Delta E)(\Delta t) \approx\left(\frac{h c}{\lambda}\right)\left(\frac{\lambda}{c}\right) \approx h .$$

A more careful calculation gives
$$(\Delta E)(\Delta t) \gtrsim \frac{h}{2 \pi}$$

This form of the uncertainty principle tells us that the energy of an object can be uncertain (or can be interpreted as briefly nonconserved) by an amount $\Delta E$ for a time $\Delta t \approx h /(2 \pi \Delta E)$.

The quantity $(h / 2 \pi)$ appears so often in quantum mechanics that for convenience it is given the symbol $\hbar$ ("h-bar"). That is,
$$\hbar=\frac{h}{2 \pi}=\frac{6.626 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s}}{2 \pi}=1.055 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s}$$

By using this notation, Eqs. 28-1 and 28-2 for the uncertainty principle can be written
$$(\Delta x)\left(\Delta p_{x}\right) \gtrsim \hbar$$
and
$$(\Delta E)(\Delta t) \gtrsim \hbar .$$

We have been discussing the position and velocity of an electron as if it were a particle. But it isn't simply a particle. Indeed, we have the uncertainty principle because an electron-and matter in general-has wave as well as particle properties. What the uncertainty principle really tells us is that if we insist on thinking of the electron as a particle, then there are certain limitations on this simplified view-namely, that the position and velocity cannot both be known precisely at the same time; and even that the electron does not have a precise position and momentum at the same time (because it is not simply a particle). Similarly, the energy can be uncertain (or nonconserved) by an amount $\Delta E$ for a time $\Delta t \approx \hbar / \Delta E$.

Because Planck's constant, $h$, is so small, the uncertainties expressed in the uncertainty principle are usually negligible on the macroscopic level. But at the level of atomic sizes, the uncertainties are significant. Because we consider ordinary objects to be made up of atoms containing nuclei and electrons, the uncertainty principle is relevant to our understanding of all of nature. The uncertainty principle expresses, perhaps most clearly, the probabilistic nature of quantum mechanics. It thus is often used as a basis for philosophic discussion.

808
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 809 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 809

EXAMPLE 28-1 Position uncertainty of electron. An electron moves in a straight line with a constant speed $v=1.10 \times 10^{6} \mathrm{~m} / \mathrm{s}$ which has been measured to a precision of $0.10 \%$. What is the maximum precision with which its position could be simultaneously measured?
APPROACH The momentum is $p=m v$, and the uncertainty in $p$ is $\Delta p=0.0010 p$. The uncertainty principle (Eq. 28-1) gives us the smallest uncertainty in position $\Delta x$ using the equals sign.
SOLUTION The momentum of the electron is
$$p=m v=\left(9.11 \times 10^{-31} \mathrm{~kg}\right)\left(1.10 \times 10^{6} \mathrm{~m} / \mathrm{s}\right)=1.00 \times 10^{-24} \mathrm{~kg} \cdot \mathrm{~m} / \mathrm{s} .$$

The uncertainty in the momentum is $0.10 \%$ of this, or $\Delta p=1.0 \times 10^{-27} \mathrm{~kg} \cdot \mathrm{~m} / \mathrm{s}$. From the uncertainty principle, the best simultaneous position measurement will have an uncertainty of
$$\Delta x \approx \frac{\hbar}{\Delta p}=\frac{1.055 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s}}{1.0 \times 10^{-27} \mathrm{~kg} \cdot \mathrm{~m} / \mathrm{s}}=1.1 \times 10^{-7} \mathrm{~m},$$
or 110 nm .
NOTE This is about 1000 times the diameter of an atom.
EXERCISE B An electron's position is measured with a precision of $0.50 \times 10^{-10} \mathrm{~m}$. Find the minimum uncertainty in its momentum and velocity.

EXAMPLE 28-2 Position uncertainty of a baseball. What is the uncertainty in position, imposed by the uncertainty principle, on a $150-\mathrm{g}$ baseball thrown at $(93 \pm 2) \mathrm{mi} / \mathrm{h}=(42 \pm 1) \mathrm{m} / \mathrm{s}$ ?
APPROACH The uncertainty in the speed is $\Delta v=1 \mathrm{~m} / \mathrm{s}$. We multiply $\Delta v$ by $m$ to get $\Delta p$ and then use the uncertainty principle, solving for $\Delta x$.
SOLUTION The uncertainty in the momentum is
$$\Delta p=m \Delta v=(0.150 \mathrm{~kg})(1 \mathrm{~m} / \mathrm{s})=0.15 \mathrm{~kg} \cdot \mathrm{~m} / \mathrm{s}$$

Hence the uncertainty in a position measurement could be as small as
$$\Delta x=\frac{\hbar}{\Delta p}=\frac{1.055 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s}}{0.15 \mathrm{~kg} \cdot \mathrm{~m} / \mathrm{s}}=7 \times 10^{-34} \mathrm{~m} .$$

NOTE This distance is far smaller than any we could imagine observing or measuring. It is trillions of trillions of times smaller than an atom. Indeed, the uncertainty principle sets no relevant limit on measurement for macroscopic objects.

EXAMPLE 28-3 ESTIMATE $\mathbf{J} / \boldsymbol{\psi}$ lifetime calculated. The $\mathrm{J} / \boldsymbol{\psi}$ meson, discovered in 1974, was measured to have an average mass of $3100 \mathrm{MeV} / c^{2}$ (note the use of energy units since $E=m c^{2}$ ) and a mass "width" of $63 \mathrm{keV} / c^{2}$. By this we mean that the masses of different $\mathrm{J} / \psi$ mesons were actually measured to be slightly different from one another. This mass "width" is related to the very short lifetime of the $\mathrm{J} / \psi$ before it decays into other particles. From the uncertainty principle, if the particle exists for only a time $\Delta t$, its mass (or rest energy) will be uncertain by $\Delta E \approx \hbar / \Delta t$. Estimate the $\mathrm{J} / \psi$ lifetime.
APPROACH We use the energy-time version of the uncertainty principle, Eq. 28-2.
SOLUTION The uncertainty of $63 \mathrm{keV} / c^{2}$ in the $\mathrm{J} / \psi$ 's mass is an uncertainty in its rest energy, which in joules is
$$\Delta E=\left(63 \times 10^{3} \mathrm{eV}\right)\left(1.60 \times 10^{-19} \mathrm{~J} / \mathrm{eV}\right)=1.01 \times 10^{-14} \mathrm{~J} .$$

Then we expect its lifetime $\tau(=\Delta t$ using Eq. 28-2) to be
$$\tau \approx \frac{\hbar}{\Delta E}=\frac{1.055 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s}}{1.01 \times 10^{-14} \mathrm{~J}} \approx 1 \times 10^{-20} \mathrm{~s}$$

Lifetimes this short are difficult to measure directly, and the assignment of very short lifetimes depends on this use of the uncertainty principle.

SECTION 28-3 The Heisenberg Uncertainty Principle
809

---

<!-- Page 810 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 810

28-4 Philosophic Implications; Probability versus Determinism

The classical Newtonian view of the world is a deterministic one (see Section 5-8). One of its basic ideas is that once the position and velocity of an object are known at a particular time, its future position can be predicted if the forces on it are known. For example, if a stone is thrown a number of times with the same initial velocity and angle, and the forces on it remain the same, the path of the projectile will always be the same. If the forces are known (gravity and air resistance, if any), the stone's path can be precisely predicted. This mechanistic view implies that the future unfolding of the universe, assumed to be made up of particulate objects, is completely determined.

This classical deterministic view of the physical world has been radically altered by quantum mechanics. As we saw in the analysis of the double-slit experiment (Section 28-2), electrons all treated in the same way will not all end up in the same place. According to quantum mechanics, certain probabilities exist that an electron will arrive at different points. This is very different from the classical view, in which the path of a particle is precisely predictable from the initial position and velocity and the forces exerted on it. According to quantum mechanics, the position and velocity of an object cannot even be known accurately at the same time. This is expressed in the uncertainty principle, and arises because basic entities, such as electrons, are not considered simply as particles: they have wave properties as well. Quantum mechanics allows us to calculate only the probability ${ }^{\dagger}$ that, say, an electron (when thought of as a particle) will be observed at various places. Quantum mechanics says there is some inherent unpredictability in nature. This is very different from the deterministic view of classical mechanics.

Because matter is considered to be made up of atoms, even ordinary-sized objects are expected to be governed by probability, rather than by strict determinism. For example, quantum mechanics predicts a finite (but negligibly small) probability that when you throw a stone, its path might suddenly curve upward instead of following the downward-curved parabola of normal projectile motion. Quantum mechanics predicts with extremely high probability that ordinary objects will behave just as the classical laws of physics predict. But these predictions are considered probabilities, not absolute certainties. The reason that macroscopic objects behave in accordance with classical laws with such high probability is due to the large number of molecules involved: when large numbers of objects are present in a statistical situation, deviations from the average (or most probable) approach zero. It is the average configuration of vast numbers of molecules that follows the so-called fixed laws of classical physics with such high probability, and gives rise to an apparent "determinism." Deviations from classical laws are observed when small numbers of molecules are dealt with. We can say, then, that although there are no precise deterministic laws in quantum mechanics, there are statistical laws based on probability.

It is important to note that there is a difference between the probability imposed by quantum mechanics and that used in the nineteenth century to understand thermodynamics and the behavior of gases in terms of molecules (Chapters 13 and 15). In thermodynamics, probability is used because there are far too many particles to keep track of. But the molecules are still assumed to move and interact in a deterministic way following Newton's laws. Probability in quantum mechanics is quite different; it is seen as inherent in nature, and not as a limitation on our abilities to calculate or to measure.
${ }^{\dagger}$ Note that these probabilities can be calculated precisely, just like predictions of probabilities at rolling dice or dealing cards; but they are unlike predictions of probabilities at sporting events, which are only estimates.

810
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 811 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 811

The view presented here is the generally accepted one and is called the Copenhagen interpretation of quantum mechanics in honor of Niels Bohr's home, since it was largely developed there through discussions between Bohr and other prominent physicists.

Because electrons are not simply particles, they cannot be thought of as following particular paths in space and time. This suggests that a description of matter in space and time may not be completely correct. This deep and far-reaching conclusion has been a lively topic of discussion among philosophers. Perhaps the most important and influential philosopher of quantum mechanics was Bohr. He argued that a space-time description of actual atoms and electrons is not possible. Yet a description of experiments on atoms or electrons must be given in terms of space and time and other concepts familiar to ordinary experience, such as waves and particles. We must not let our descriptions of experiments lead us into believing that atoms or electrons themselves actually move in space and time as classical particles.

28-5 Quantum-Mechanical View of Atoms

At the beginning of this Chapter, we discussed the limitations of the Bohr model of atomic structure. Now we examine the quantum-mechanical theory of atoms, which is a far more complete theory than the old Bohr model. Although the Bohr model has been discarded as an accurate description of nature, nonetheless, quantum mechanics reaffirms certain aspects of the older theory, such as that electrons in an atom exist only in discrete states of definite energy, and that a photon of light is emitted (or absorbed) when an electron makes a transition from one state to another. But quantum mechanics is a much deeper theory, and has provided us with a very different view of the atom. According to quantum mechanics, electrons do not exist in well-defined circular orbits as in the Bohr model. Rather, the electron (because of its wave nature) can be thought of as spread out in space as a "cloud." The size and shape of the electron cloud can be calculated for a given state of an atom. For the ground state in the hydrogen atom, the electron cloud is spherically symmetric, as shown in Fig. 28-6. The electron cloud at its higher densities roughly indicates the "size" of an atom. But just as a cloud may not have a distinct border, atoms do not have a precise boundary or a well-defined size. Not all electron clouds have a spherical shape, as we shall see later in this Chapter.

The electron cloud can be interpreted from either the particle or the wave viewpoint. Remember that by a particle we mean something that is localized in space-it has a definite position at any given instant. By contrast, a wave is spread out in space. The electron cloud, spread out in space as in Fig. 28-6, is a result of the wave nature of electrons. Electron clouds can also be interpreted as probability distributions (or probability density) for a particle. As we saw in Section 28-3, we cannot predict the path an electron will follow (thinking of it as a particle). After one measurement of its position we cannot predict exactly where it will be at a later time. We can only calculate the probability that it will be found at different points. If you were to make 500 different measurements of the position of an electron in a hydrogen atom, the majority of the results would show the electron at points where the probability is high (dark area in Fig. 28-6). Only occasionally would the electron be found where the probability is low. The electron cloud or probability distribution becomes small (or thin) at places, especially far away, but never becomes zero. So quantum mechanics suggests that an atom is not mostly empty space, and that there is no truly empty space in the universe.

FIGURE 28-6 Electron cloud or "probability distribution" for the ground state of the hydrogen atom, as seen from afar. The dots represent a hypothetical detection of an electron at each point: dots closer together represent more probable presence of an electron (denser cloud). The dashed circle represents the Bohr radius $r_{0}$.

SECTION 28-5 Quantum-Mechanical View of Atoms
811

---

<!-- Page 812 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 812

FIGURE 28-7 Quantization of angular momentum direction for $\ell=2$. (Magnitude of $\overrightarrow{\mathbf{L}}$ is $L=\sqrt{6} \hbar$.)

28-6 Quantum Mechanics of the Hydrogen Atom; Quantum Numbers

We now look more closely at what quantum mechanics tells us about the hydrogen atom. Much of what we say here also applies to more complex atoms, which are discussed in the next Section.

Quantum mechanics is a much more sophisticated and successful theory than Bohr's. Yet in a few details they agree. Quantum mechanics predicts the same basic energy levels (Fig. 27-29) for the hydrogen atom as does the Bohr model. That is,
$$E_{n}=-\frac{13.6 \mathrm{eV}}{n^{2}}, \quad n=1,2,3, \cdots,$$
where $n$ is an integer. In the simple Bohr model, there was only one quantum number, $n$. In quantum mechanics, four different quantum numbers are needed to specify each state in the atom:
(1) The quantum number, $n$, from the Bohr model is found also in quantum mechanics and is called the principal quantum number. It can have any integer value from 1 to $\infty$. The total energy of a state in the hydrogen atom depends on $n$, as we saw above.
(2) The orbital quantum number, $\ell$, is related to the magnitude of the angular momentum of the electron; $\ell$ can take on integer values from 0 to $(n-1)$. For the ground state, $n=1, \ell$ can only be zero. ${ }^{\dagger}$ For $n=3, \ell$ can be 0,1 , or 2 . The actual magnitude of the angular momentum $L$ is related to the quantum number $\ell$ by
$$L=\sqrt{\ell(\ell+1)} \hbar$$
(where again $\hbar=h / 2 \pi$ ). The value of $\ell$ has almost no effect on the total energy in the hydrogen atom; only $n$ does to any appreciable extent (but see fine structure below). In atoms with two or more electrons, the energy does depend on $\ell$ as well as $n$, as we shall see.
(3) The magnetic quantum number, $m_{\ell}$, is related to the direction of the electron's angular momentum, and it can take on integer values ranging from $-\ell$ to $+\ell$. For example, if $\ell=2$, then $m_{\ell}$ can be $-2,-1,0,+1$, or +2 . Since angular momentum is a vector, it is not surprising that both its magnitude and its direction would be quantized. For $\ell=2$, the five different directions allowed can be represented by the diagram of Fig. 28-7. This limitation on the direction of $\overrightarrow{\mathbf{L}}$ is often called space quantization. In quantum mechanics, the direction of the angular momentum is usually specified by giving its component along the $z$ axis (this choice is arbitrary). Then $L_{z}$ is related to $m_{\ell}$ by the equation
$$L_{z}=m_{\ell} \hbar .$$

The values of $L_{x}$ and $L_{y}$ are not definite, however. The name for $m_{\ell}$ derives not from theory (which relates it to $L_{z}$ ), but from experiment. It was found that when a gas-discharge tube was placed in a magnetic field, the spectral lines were split into several very closely spaced lines. This splitting, known as the Zeeman effect, implies that the energy levels must be split (Fig. 28-8), and thus that the energy of a state depends not only on $n$ but also on $m_{\ell}$ when a magnetic field is applied-hence the name "magnetic quantum number."
${ }^{\dagger}$ This replaces Bohr theory, which assigned $\ell=1$ to the ground state (Eq. 27-11).

812
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 813 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 813
(4) Finally, there is the spin quantum number, $m_{s}$, which for an electron can have only two values, $m_{s}=+\frac{1}{2}$ and $m_{s}=-\frac{1}{2}$. The existence of this quantum number did not come out of Schrödinger's original wave theory, as did $n, \ell$, and $m_{\ell}$. Instead, a subsequent modification by P. A. M. Dirac (1902-1984) explained its presence as a relativistic effect. The first hint that $m_{s}$ was needed, however, came from experiment. A careful study of the spectral lines of hydrogen showed that each actually consisted of two (or more) very closely spaced lines even in the absence of an external magnetic field. It was at first hypothesized that this tiny splitting of energy levels, called fine structure, was due to angular momentum associated with a spinning of the electron. That is, the electron might spin on its axis as well as orbit the nucleus, just as the Earth spins on its axis as it orbits the Sun. The interaction between the tiny current of the spinning electron could then interact with the magnetic field due to the orbiting charge and cause the small observed splitting of energy levels. (The energy thus depends slightly on $m_{\ell}$ and $\left.m_{s}.\right)^{\dagger}$ Today we consider the picture of a spinning electron as not legitimate. We cannot even view an electron as a localized object, much less a spinning one. What is important is that the electron can have two different states due to some intrinsic property that behaves like an angular momentum, and we still call this property "spin." The two possible values of $m_{s}\left(+\frac{1}{2}\right.$ and $\left.-\frac{1}{2}\right)$ are often said to be "spin up" and "spin down," referring to the two possible directions of the spin angular momentum.
The possible values of the four quantum numbers for an electron in the hydrogen atom are summarized in Table 28-1.

**TABLE 28-1 Quantum Numbers for an Electron**

| Name | Symbol | Possible Values |
| --- | --- | --- |
| Principal | $n$ | $1,2,3, \cdots, \infty$. |
| Orbital | $\ell$ | For a given $n$ : $\ell$ can be $0,1,2, \cdots, n-1$. |
| Magnetic | $m_{\ell}$ | For given $n$ and $\ell: m_{\ell}$ can be $\ell, \ell-1, \cdots, 0, \cdots,-\ell$. |
| Spin | $m_{s}$ | For each set of $n, \ell$, and $m_{\ell}: m_{s}$ can be $+\frac{1}{2}$ or $-\frac{1}{2}$. |

CONCEPTUAL EXAMPLE 28-4 Possible states for $\boldsymbol{n}=\mathbf{3}$. How many different states are possible for an electron with principal quantum number $n=3$ ?

RESPONSE For $n=3, \ell$ can have the values $\ell=2,1,0$. For $\ell=2, m_{\ell}$ can be $2,1,0,-1,-2$, which is five different possibilities. For each of these, $m_{s}$ can be either up or down $\left(+\frac{1}{2}\right.$ or $\left.-\frac{1}{2}\right)$; so for $\ell=2$, there are $2 \times 5=10$ states. For $\ell=1, m_{\ell}$ can be $1,0,-1$, and since $m_{s}$ can be $+\frac{1}{2}$ or $-\frac{1}{2}$ for each of these, we have 6 more possible states. Finally, for $\ell=0, m_{\ell}$ can only be 0 , and there are only 2 states corresponding to $m_{s}=+\frac{1}{2}$ and $-\frac{1}{2}$. The total number of states is $10+6+2=18$, as detailed in the following Table:

| $\boldsymbol{n}$ | $\ell$ | $m_{\ell}$ | $\boldsymbol{m}_{\boldsymbol{S}}$ | $\boldsymbol{n}$ | $\ell$ | $\boldsymbol{m}_{\boldsymbol{\ell}}$ | $\boldsymbol{m}_{\boldsymbol{s}}$ |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 3 | 2 | 2 | $\frac{1}{2}$ | 3 | 1 | 1 | $\frac{1}{2}$ |
| 3 | 2 | 2 | $-\frac{1}{2}$ | 3 | 1 | 1 | $-\frac{1}{2}$ |
| 3 | 2 | 1 | $\frac{1}{2}$ | 3 | 1 | 0 | $\frac{1}{2}$ |
| 3 | 2 | 1 | $-\frac{1}{2}$ | 3 | 1 | 0 | $-\frac{1}{2}$ |
| 3 | 2 | 0 | $\frac{1}{2}$ | 3 | 1 | -1 | $\frac{1}{2}$ |
| 3 | 2 | 0 | $-\frac{1}{2}$ | 3 | 1 | -1 | $-\frac{1}{2}$ |
| 3 | 2 | -1 | $\frac{1}{2}$ | 3 | 0 | 0 | $\frac{1}{2}$ |
| 3 | 2 | -1 | $-\frac{1}{2}$ | 3 | 0 | 0 | $-\frac{1}{2}$ |
| 3 | 2 | -2 | $\frac{1}{2}$ |  |  |  |  |
| 3 | 2 | -2 | $-\frac{1}{2}$ |  |  |  |  |


EXERCISE C An electron has $n=4, \ell=2$. Which of the following values of $m_{\ell}$ are possible: $4,3,2,1,0,-1,-2,-3,-4$ ?

${ }^{\dagger}$ Fine structure is said to be due to a spin-orbit interaction.
SECTION 28-6
813

---

<!-- Page 814 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 814

FIGURE 28-9 Electron cloud, or probability distribution, for $n=2$ states in hydrogen. [The donutshaped orbit in (c) is the sum of two dumbbell-shaped orbits, as in (b), along the $x$ and $y$ axes added together.]

EXAMPLE 28-5 $\boldsymbol{E}$ and $\boldsymbol{L}$ for $\boldsymbol{n}=\mathbf{3}$. Determine (a) the energy and (b) the orbital angular momentum for an electron in each of the hydrogen atom states with $n=3$, as in Example 28-4.
APPROACH The energy of a state depends only on $n$, except for the very small corrections mentioned above, which we will ignore. Energy is calculated as in the Bohr model, $E_{n}=-13.6 \mathrm{eV} / n^{2}$. For angular momentum we use Eq. 28-3.
SOLUTION (a) Since $n=3$ for all these states, they all have the same energy,
$$E_{3}=-\frac{13.6 \mathrm{eV}}{(3)^{2}}=-1.51 \mathrm{eV}$$
(b) For $\ell=0$, Eq. 28-3 gives
$$L=\sqrt{\ell(\ell+1)} \hbar=0 .$$

For $\ell=1$,
$$L=\sqrt{1(1+1)} \hbar=\sqrt{2} \hbar=1.49 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s} .$$

For $\ell=2, L=\sqrt{2(2+1)} \hbar=\sqrt{6} \hbar$.
NOTE Atomic angular momenta are generally given as a multiple of $\hbar(\sqrt{2} \hbar$ or $\sqrt{6} \hbar$ in this case), rather than in SI units.

EXERCISE D What are the energy and angular momentum of the electron in a hydrogen atom with $n=6, \ell=4$ ?

Although $\ell$ and $m_{\ell}$ do not significantly affect the energy levels in hydrogen, they do affect the electron probability distribution in space. For $n=1, \ell$ and $m_{\ell}$ can only be zero and the electron distribution is as shown in Fig. 28-6. For $n=2, \ell$ can be 0 or 1 . The distribution for $n=2, \ell=0$ is shown in Fig. 28-9a, and it is seen to differ from that for the ground state (Fig. 28-6), although it is still spherically symmetric. For $n=2, \ell=1$, the distributions are not spherically symmetric as shown in Figs. 28-9b (for $m_{\ell}=0$ ) and 28-9c (for $m_{\ell}=+1$ or -1 ).

Although the spatial distributions of the electron can be calculated for the various states, it is difficult to measure them experimentally. Most of the experimental information about atoms has come from a careful examination of the emission spectra under various conditions as in Figs. 27-23 and 24-28.
[Chemists refer to atomic states, and especially the shape in space of their probability distributions, as orbitals. Each atomic orbital is characterized by its quantum numbers $n, \ell$, and $m_{\ell}$, and can hold one or two electrons ( $m_{s}=+\frac{1}{2}$ or $\left.m_{s}=-\frac{1}{2}\right) ; s$-orbitals ( $\ell=0$ ) are spherically symmetric, Figs. 28-6 and 28-9a; $p$-orbitals ( $\ell=1$ ) can be dumbbell shaped with lobes, Fig. 28-9b, or donut shaped if combining $m_{\ell}=+1$ and $m_{\ell}=-1$, Fig. 28-9c.]

Selection Rules: Allowed and Forbidden Transitions
Another prediction of quantum mechanics is that when a photon is emitted or absorbed, transitions can occur only between states with values of $\ell$ that differ by exactly one unit:
$$\Delta \ell= \pm 1 .$$

According to this selection rule, an electron in an $\ell=2$ state can jump only to a state with $\ell=1$ or $\ell=3$. It cannot jump to a state with $\ell=2$ or $\ell=0$. A transition such as $\ell=2$ to $\ell=0$ is called a forbidden transition. Actually, such a transition is not absolutely forbidden and can occur, but only with very low probability compared to allowed transitions-those that satisfy the selection rule $\Delta \ell= \pm 1$. Since the orbital angular momentum of an H atom must change by one unit when it emits a photon, conservation of angular momentum tells us that the photon must carry off angular momentum. Indeed, experimental evidence of many sorts shows that the photon can be assigned a spin angular momentum of $1 \hbar$.

814
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 815 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 815

28-7 Multielectron Atoms; the Exclusion Principle

We have discussed the hydrogen atom in detail because it is the simplest to deal with. Now we briefly discuss more complex atoms, those that contain more than one electron. Their energy levels can be determined experimentally from an analysis of their emission spectra. The energy levels are not the same as in the H atom, because the electrons interact with each other as well as with the nucleus. Each electron in a complex atom still occupies a particular state characterized by the quantum numbers $n, \ell, m_{\ell}$, and $m_{s}$. For atoms with more than one electron, the energy levels depend on both $n$ and $\ell$.

The number of electrons in a neutral atom is called its atomic number, $Z$; $Z$ is also the number of positive charges (protons) in the nucleus, and determines what kind of atom it is. That is, $Z$ determines the fundamental properties that distinguish one type of atom from another.

To understand the possible arrangements of electrons in an atom, a new principle was needed. It was introduced by Wolfgang Pauli (1900-1958; Fig. 28-2) and is called the Pauli exclusion principle. It states:

No two electrons in an atom can occupy the same quantum state.
Thus, no two electrons in an atom can have exactly the same set of the quantum numbers $n, \ell, m_{\ell}$, and $m_{s}$. The Pauli exclusion principle forms the basis not only for understanding atoms, but also for understanding molecules and bonding, and other phenomena as well. (See also note at end of this Section.)

Let us now look at the structure of some of the simpler atoms when they are in the ground state. After hydrogen, the next simplest atom is helium with two electrons. Both electrons can have $n=1$, because one can have spin up ( $m_{s}=+\frac{1}{2}$ ) and the other spin down $\left(m_{s}=-\frac{1}{2}\right)$, thus satisfying the exclusion principle. Since $n=1$, then $\ell$ and $m_{\ell}$ must be zero (Table 28-1, page 813). Thus the two electrons have the quantum numbers indicated at the top of Table 28-2.

Lithium has three electrons, two of which can have $n=1$. But the third cannot have $n=1$ without violating the exclusion principle. Hence the third electron must have $n=2$. It happens that the $n=2, \ell=0$ level has a lower energy than $n=2, \ell=1$. So the electrons in the ground state have the quantum numbers indicated in Table 28-2. The quantum numbers of the third electron could also be, say, $\left(n, \ell, m_{\ell}, m_{s}\right)=\left(3,1,-1, \frac{1}{2}\right)$. But the atom in this case would be in an excited state, because it would have greater energy. It would not be long before it jumped to the ground state with the emission of a photon. At room temperature, unless extra energy is supplied (as in a discharge tube), the vast majority of atoms are in the ground state.

We can continue in this way to describe the quantum numbers of each electron in the ground state of larger and larger atoms. The quantum numbers for sodium, with its eleven electrons, are shown in Table 28-2.
EXERCISE E Construct a Table of the ground-state quantum numbers for beryllium, $Z=4$ (like those in Table 28-2).

Figure 28-10 shows a simple energy level diagram where occupied states are shown as up or down arrows $\left(m_{s}=+\frac{1}{2}\right.$ or $-\frac{1}{2}$ ), and possible empty states are shown as a small circle.

**$n=3, \ell=0$**

| TABLE 28-2 Ground-State Quantum Numbers |  |  |  |
| --- | --- | --- | --- |
| Helium, $Z=2$ |  |  |  |
| $\boldsymbol{n}$ | / | $\boldsymbol{m}_{\boldsymbol{\ell}}$ | $\boldsymbol{m}_{\boldsymbol{s}}$ |
| 1 | 0 | 0 | $\frac{1}{2}$ |
| 1 | 0 | 0 | $-\frac{1}{2}$ |
| Lithium, $Z=3$ |  |  |  |
| $\boldsymbol{n}$ | $\ell$ | $\boldsymbol{m}_{\boldsymbol{\ell}}$ | $\boldsymbol{m}_{\boldsymbol{s}}$ |
| 1 | 0 | 0 | $\frac{1}{2}$ |
| 1 | 0 | 0 | $-\frac{1}{2}$ |
| 2 | 0 | 0 | $\frac{1}{2}$ |
| Sodium, $Z=11$ |  |  |  |
| $\boldsymbol{n}$ | $\ell$ | $m_{\ell}$ | $\boldsymbol{m}_{\boldsymbol{S}}$ |
| 1 | 0 | 0 | $\frac{1}{2}$ |
| 1 | 0 | 0 | $-\frac{1}{2}$ |
| 2 | 0 | 0 | $\frac{1}{2}$ |
| 2 | 0 | 0 | $-\frac{1}{2}$ |
| 2 | 1 | 1 | $\frac{1}{2}$ |
| 2 | 1 | 1 | $-\frac{1}{2}$ |
| 2 | 1 | 0 | $\frac{1}{2}$ |
| 2 | 1 | 0 | $-\frac{1}{2}$ |
| 2 | 1 | -1 | $\frac{1}{2}$ |
| 2 | 1 | -1 | $-\frac{1}{2}$ |
| 3 | 0 | 0 | $\frac{1}{2}$ |
$n=2, \ell=1$
$n=2, \ell=0$
$n=1, \ell=0$

Helium ( $\mathrm{He}, Z=2$ )

Lithium (Li, $Z=3$ )
$n=2, \ell=1$
$$n=2, \ell=0$$

Sodium ( $\mathrm{Na}, Z=11$ )

FIGURE 28-10 Energy level diagrams (not to scale) showing occupied states (arrows) and unoccupied states ( ∘ ) for the ground states of He , Li , and Na . Note that we have shown the $n=2, \ell=1$ level of Li even though it is empty.

SECTION 28-7 Multielectron Atoms; the Exclusion Principle
815

---

<!-- Page 816 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 816

**TABLE 28-4
Electron Configuration of Some Elements**

| TABLE 28-3 Value of $\ell$ |  |  |
| --- | --- | --- |
| Value of $\ell$ | Letter Symbol | Maximum Number of Electrons in Subshell |
| 0 | $s$ | 2 |
| 1 | $p$ | 6 |
| 2 | $d$ | 10 |
| 3 | $f$ | 14 |
| 4 | $g$ | 18 |
| 5 | $h$ | 22 |
| ⋮ | ⋮ | ⋮ |

**TABLE 28-4
Electron Configuration of Some Elements**

| $Z$ (Number of Electrons) | Element ${ }^{\dagger}$ | Ground State Configuration (outer electrons) |
| --- | --- | --- |
| 1 | H | $1 s^{1}$ |
| 2 | He | $1 s^{2}$ |
| 3 | Li | $2 s^{1}$ |
| 4 | Be | $2 s^{2}$ |
| 5 | B | $2 s^{2} 2 p^{1}$ |
| 6 | C | $2 s^{2} 2 p^{2}$ |
| 7 | N | $2 s^{2} 2 p^{3}$ |
| 8 | O | $2 s^{2} 2 p^{4}$ |
| 9 | F | $2 s^{2} 2 p^{5}$ |
| 10 | Ne | $2 s^{2} 2 p^{6}$ |
| 11 | Na | $3 s^{1}$ |
| 12 | Mg | $3 s^{2}$ |
| 13 | Al | $3 s^{2} 3 p^{1}$ |
| 14 | Si | $3 s^{2} 3 p^{2}$ |
| 15 | P | $3 s^{2} 3 p^{3}$ |
| 16 | S | $3 s^{2} 3 p^{4}$ |
| 17 | Cl | $3 s^{2} 3 p^{5}$ |
| 18 | Ar | $3 s^{2} 3 p^{6}$ |
| 19 | K | $3 d^{0} 4 s^{1}$ |
| 20 | Ca | $3 d^{0} 4 s^{2}$ |
| 21 | Sc | $3 d^{1} 4 s^{2}$ |
| 22 | Ti | $3 d^{2} 4 s^{2}$ |
| 23 | V | $3 d^{3} 4 s^{2}$ |
| 24 | Cr | $3 d^{5} 4 s^{1}$ |
| 25 | Mn | $3 d^{5} 4 s^{2}$ |
| 26 | Fe | $3 d^{6} 4 s^{2}$ |
${ }^{\dagger}$ Names of elements can be found in Appendix B.

The ground-state configuration for all atoms is given in the Periodic Table, which is displayed inside the back cover of this book, and discussed in the next Section.
[The exclusion principle applies to identical particles whose spin quantum number is a half-integer $\left(\frac{1}{2}, \frac{3}{2}\right.$, and so on), including electrons, protons, and neutrons; such particles are called fermions, after Enrico Fermi who derived a statistical theory describing them. A basic assumption is that all electrons are identical, indistinguishable one from another. Similarly, all protons are identical, all neutrons are identical, and so on. The exclusion principle does not apply to particles with integer spin $(0,1,2$, and so on), such as the photon and $\pi$ meson, all of which are referred to as bosons (after Satyendranath Bose, who derived a statistical theory for them).]
28-8 The Periodic Table of Elements
More than a century ago, Dmitri Mendeleev (1834-1907) arranged the (then) known elements into what we now call the Periodic Table of the elements. The atoms were arranged according to increasing mass, but also so that elements with similar chemical properties would fall in the same column. Today's version is shown inside the back cover of this book. Each square contains the atomic number $Z$, the symbol for the element, and the atomic mass (in atomic mass units). Finally, the lower left corner shows the configuration of the ground state of the atom. This requires some explanation. Electrons with the same value of $n$ are referred to as being in the same shell. Electrons with $n=1$ are in one shell (the K shell), those with $n=2$ are in a second shell (the L shell), those with $n=3$ are in the third (M) shell, and so on. Electrons with the same values of $n$ and $\ell$ are referred to as being in the same subshell. Letters are often used to specify the value of $\ell$ as shown in Table 28-3. That is, $\ell=0$ is the $s$ subshell; $\ell=1$ is the $p$ subshell; $\ell=2$ is the $d$ subshell; beginning with $\ell=3$, the letters follow the alphabet, $f, g, h, i$ and so on. (The first letters $s, p, d$, and $f$ were originally abbreviations of "sharp," "principal," "diffuse," and "fundamental," terms referring to the experimental spectra.)

The Pauli exclusion principle limits the number of electrons possible in each shell and subshell. For any value of $\ell$, there are $2 \ell+1$ possible $m_{\ell}$ values ( $m_{\ell}$ can be any integer from 1 to $\ell$, from -1 to $-\ell$, or zero), and two possible $m_{s}$ values. There can be, therefore, at most $2(2 \ell+1)$ electrons in any $\ell$ subshell. For example, for $\ell=2$, five $m_{\ell}$ values are possible ( $2,1,0,-1,-2$ ), and for each of these, $m_{s}$ can be $+\frac{1}{2}$ or $-\frac{1}{2}$ for a total of $2(5)=10$ states. Table 28-3 lists the maximum number of electrons that can occupy each subshell.

Because the energy levels depend almost entirely on the values of $n$ and $\ell$, it is customary to specify the electron configuration simply by giving the $n$ value and the appropriate letter for $\ell$, with the number of electrons in each subshell given as a superscript. The ground-state configuration of sodium, for example, is written as $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{1}$. This is simplified in the Periodic Table by specifying the configuration only of the outermost electrons and any other nonfilled subshells (see Table 28-4 here, and the Periodic Table inside the back cover).

CONCEPTUAL EXAMPLE 28-6 Electron configurations. Which of the following electron configurations are possible, and which are not: (a) $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{3}$; (b) $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2} 3 p^{5} 4 s^{2}$; (c) $1 s^{2} 2 s^{2} 2 p^{6} 2 d^{1}$ ?

RESPONSE (a) This is not allowed, because too many electrons (three) are shown in the $s$ subshell of the $\mathrm{M}(n=3)$ shell. The $s$ subshell has $m_{\ell}=0$, with two slots only, for "spin up" and "spin down" electrons.
(b) This is allowed, but it is an excited state. One of the electrons from the $3 p$ subshell has jumped up to the $4 s$ subshell. Since there are 19 electrons, the element is potassium.
(c) This is not allowed, because there is no $d(\ell=2)$ subshell in the $n=2$ shell (Table 28-1). The outermost electron will have to be (at least) in the $n=3$ shell.

816
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 817 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 817

EXERCISE F Write the complete ground-state configuration for gallium, with its 31 electrons.

The grouping of atoms in the Periodic Table is according to increasing atomic number, $Z$. It was designed to also show regularity according to chemical properties. Although this is treated in chemistry textbooks, we discuss it here briefly because it is a result of quantum mechanics. See the Periodic Table inside the back cover.

All the noble gases (in column VIII of the Periodic Table) have completely filled shells or subshells. That is, their outermost subshell is completely full, and the electron distribution is spherically symmetric. With such full spherical symmetry, other electrons are not attracted nor are electrons readily lost (ionization energy is high). This is why the noble gases are chemically inert (more on this when we discuss molecules and bonding in Chapter 29). Column VII contains the halogens, which lack one electron from a filled shell. Because of the shapes of the orbits (see Section 29-1), an additional electron can be accepted from another atom, and hence these elements are quite reactive. They have a valence of -1 , meaning that when an extra electron is acquired, the resulting ion has a net charge of $-1 e$. Column I of the Periodic Table contains the alkali metals, all of which have a single outer $s$ electron. This electron spends most of its time outside the inner closed shells and subshells which shield it from most of the nuclear charge. Indeed, it is relatively far from the nucleus and is attracted to it by a net charge of only about $+1 e$, because of the shielding effect of the other electrons. Hence this outer electron is easily removed and can spend much of its time around another atom, forming a molecule. This is why the alkali metals are very chemically reactive and have a valence of +1 . The other columns of the Periodic Table can be treated similarly.

The presence of the transition elements in the center of the Periodic Table, as well as the lanthanides (rare earths) and actinides below, is a result of incomplete inner shells. For the lowest $Z$ elements, the subshells are filled in a simple order: first $1 s$, then $2 s$, followed by $2 p, 3 s$, and $3 p$. You might expect that $3 d(n=3, \ell=2)$ would be filled next, but it isn't. Instead, the $4 s$ level actually has a slightly lower energy than the $3 d$ (due to electrons interacting with each other), so it fills first ( K and Ca ). Only then does the $3 d$ shell start to fill up, beginning with Sc , as can be seen in Table 28-4. (The $4 s$ and $3 d$ levels are close, so some elements have only one $4 s$ electron, such as Cr.) Most of the chemical properties of these transition elements are governed by the relatively loosely held $4 s$ electrons, and hence they usually have valences of +1 or +2 . A similar effect is responsible for the lanthanides and actinides, which are shown at the bottom of the Periodic Table for convenience. All have very similar chemical properties, which are determined by their two outer $6 s$ or $7 s$ electrons, whereas the different numbers of electrons in the unfilled inner shells have little effect.
*28-9 X-Ray Spectra and Atomic Number

The line spectra of atoms in the visible, UV, and IR regions of the EM spectrum are mainly due to transitions between states of the outer electrons. Much of the positive charge of the nucleus is shielded from these electrons by the negative charge on the inner electrons. But the innermost electrons in the $n=1$ shell "see" the full charge of the nucleus. Since the energy of a level is proportional to $Z^{2}$ (see Eq. 27-15), for an atom with $Z=50$, we would expect wavelengths about $50^{2}=2500$ times shorter than those found in the Lyman series of hydrogen (around 100 nm ), or $(100 \mathrm{~nm}) /(2500) \approx 10^{-2}$ to $10^{-1} \mathrm{~nm}$. Such short wavelengths lie in the X-ray region of the spectrum.

*SECTION 28-9 X-Ray Spectra and Atomic Number
817

---

<!-- Page 818 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 818

FIGURE 28-11 Spectrum of X-rays emitted from a molybdenum target in an X-ray tube operated at 50 kV .

FIGURE 28-12 Plot of $\sqrt{1 / \lambda}$ vs. $Z$ for $\mathrm{K}_{\alpha} \mathrm{X}$-ray lines.

X-rays are produced when electrons accelerated by a high voltage strike the metal target inside an X-ray tube (Section 25-11). If we look at the spectrum of wavelengths emitted by an X-ray tube, we see that the spectrum consists of two parts: a continuous spectrum with a cutoff at some $\lambda_{0}$ which depends only on the voltage across the tube, and a series of peaks superimposed. A typical example is shown in Fig. 28-11. The smooth curve and the cutoff wavelength $\lambda_{0}$ move to the left as the voltage across the tube increases. The sharp lines or peaks (labeled $\mathrm{K}_{\alpha}$ and $\mathrm{K}_{\beta}$ in Fig. 28-11), however, remain at the same wavelength when the voltage is changed, although they are located at different wavelengths when different target materials are used. This observation suggests that the peaks are characteristic of the target material used. Indeed, we can explain the peaks by imagining that the electrons accelerated by the high voltage of the tube can reach sufficient energies that, when they collide with the atoms of the target, they can knock out one of the very tightly held inner electrons. Then we explain these characteristic X-rays (the peaks in Fig. 28-11) as photons emitted when an electron in an upper state drops down to fill the vacated lower state. The K lines result from transitions into the K shell $(n=1)$. The $\mathrm{K}_{\alpha}$ line consists of photons emitted in a transition that originates from the $n=2(\mathrm{~L})$ shell and drops to the $n=1(\mathrm{~K})$ shell. On the other hand, the $\mathrm{K}_{\beta}$ line reflects a transition from the $n=3(\mathrm{M})$ shell down to the K shell. An L line is due to a transition into the L shell, and so on.

Measurement of the characteristic X-ray spectra has allowed a determination of the inner energy levels of atoms. It has also allowed the determination of $Z$ values for many atoms, because (as we have seen) the wavelength of the shortest characteristic X-rays emitted will be inversely proportional to $Z^{2}$. Actually, for an electron jumping from, say, the $n=2$ to the $n=1$ level ( $\mathrm{K}_{\alpha}$ line), the wavelength is inversely proportional to $(Z-1)^{2}$ because the nucleus is shielded by the one electron that still remains in the $1 s$ level. In 1914, H. G. J. Moseley (1887-1915) found that a plot of $\sqrt{1 / \lambda}$ vs. $Z$ produced a straight line, Fig. 28-12, where $\lambda$ is the wavelength of the $\mathrm{K}_{\alpha}$ line. The $Z$ values of a number of elements were determined by fitting them to such a Moseley plot. The work of Moseley put the concept of atomic number on a firm experimental basis.

EXAMPLE 28-7 X-ray wavelength. Estimate the wavelength for an $n=2$ to $n=1$ transition in molybdenum ( $Z=42$ ). What is the energy of such a photon?
APPROACH We use the Bohr formula, Eq. 27-16 for $1 / \lambda$, with $Z^{2}$ replaced by $(Z-1)^{2}=(41)^{2}$.
SOLUTION Equation 27-16 gives
$$\frac{1}{\lambda}=\left(\frac{2 \pi^{2} e^{4} m k^{2}}{h^{3} c}\right)(Z-1)^{2}\left(\frac{1}{n^{\prime 2}}-\frac{1}{n^{2}}\right)$$
where $n=2, n^{\prime}=1$, and $k=8.99 \times 10^{9} \mathrm{~N} \cdot \mathrm{~m}^{2} / c^{2}$. We substitute in values:
$$\frac{1}{\lambda}=\left(1.097 \times 10^{7} \mathrm{~m}^{-1}\right)(41)^{2}\left(\frac{1}{1}-\frac{1}{4}\right)=1.38 \times 10^{10} \mathrm{~m}^{-1} .$$

So
$$\lambda=\frac{1}{1.38 \times 10^{10} \mathrm{~m}^{-1}}=0.072 \mathrm{~nm} .$$

This is close to the measured value (Fig. 28-11) of 0.071 nm . Each of these photons would have energy (in eV ) of:
$$E=h f=\frac{h c}{\lambda}=\frac{\left(6.63 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s}\right)\left(3.00 \times 10^{8} \mathrm{~m} / \mathrm{s}\right)}{\left(7.2 \times 10^{-11} \mathrm{~m}\right)\left(1.60 \times 10^{-19} \mathrm{~J} / \mathrm{eV}\right)}=17 \mathrm{keV} .$$

The denominator includes the conversion factor from joules to eV.

818
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 819 -->

GIAN_PPA7_28_803-828v5.1HR_SL.QXD 6/28/16 12:31 PM Page 819

EXAMPLE 28-8 Determining atomic number. High-energy electrons are used to bombard an unknown material. The strongest peak is found for X-rays emitted with an energy of 7.5 keV . Guess what the material is.
APPROACH The highest intensity X-rays are generally for the $\mathrm{K}_{\alpha}$ line (see Fig. 28-11) which occurs when high-energy electrons knock out K shell electrons (the innermost orbit, $n=1$ ) and their place is taken by electrons from the L shell $(n=2)$. We use the Bohr model, and assume the electrons of the unknown atoms ( $Z$ ) "see" a nuclear charge of $Z-1$ (screened by one electron). SOLUTION The hydrogen transition $n=2$ to $n=1$ would yield $E_{\mathrm{H}}=13.6 \mathrm{eV}-3.4 \mathrm{eV}=10.2 \mathrm{eV}$ (see Fig. 27-29 or Example 27-13). Energy of our unknown $E_{Z}$ is proportional to $Z^{2}$ (Eq. 27-15), or rather $(Z-1)^{2}$ because the nucleus is shielded by the one electron in a $1 s$ state (see above), so we can use ratios:
$$\frac{E_{Z}}{E_{\mathrm{H}}}=\frac{(Z-1)^{2}}{1^{2}}=\frac{7500 \mathrm{eV}}{10.2 \mathrm{eV}}=735,$$
so $Z-1=\sqrt{735}=27$, and $Z=28$, which makes it cobalt.
Now we briefly analyze the continuous part of an X-ray spectrum (Fig. 28-11) based on the photon theory of light. When electrons strike the target, they collide with atoms of the material and give up most of their energy as heat (about $99 \%$, so X-ray tubes must be cooled). Electrons can also give up energy by emitting a photon of light: an electron decelerated by interaction with atoms of the target (Fig. 28-13) emits radiation because of its deceleration (Chapter 22), and in this case it is called bremsstrahlung (German for "braking radiation"). Because energy is conserved, the energy of the emitted photon, hf, equals the loss of kinetic energy of the electron, $\Delta \mathrm{KE}=\mathrm{KE}-\mathrm{KE}^{\prime}$, so
$$h f=\Delta \mathrm{KE} .$$

An electron may lose all or a part of its energy in such a collision. The continuous X-ray spectrum (Fig. 28-11) is explained as being due to such bremsstrahlung collisions in which varying amounts of energy are lost by the electrons. The shortest-wavelength X-ray (the highest frequency) must be due to an electron that gives up all its kinetic energy to produce one photon in a single collision. Since the initial kinetic energy of an electron is equal to the energy given it by the accelerating voltage, $V$, then $\mathrm{KE}=e V$. In a single collision in which the electron is brought to rest $\left(\mathrm{KE}^{\prime}=0\right)$, then $\Delta \mathrm{KE}=e V$ and
$$h f_{0}=e V .$$

We set $f_{0}=c / \lambda_{0}$ where $\lambda_{0}$ is the cutoff wavelength (Fig. 28-11) and find
$$\lambda_{0}=\frac{h c}{e V}$$

This prediction for $\lambda_{0}$ corresponds precisely with that observed experimentally. This result is further evidence that X-rays are a form of electromagnetic radiation (light) and that the photon theory of light is valid.

EXAMPLE 28-9 Cutoff wavelength. What is the shortest-wavelength X-ray photon emitted in an X-ray tube subjected to 50 kV ?
APPROACH The electrons striking the target will have a KE of 50 keV . The shortest-wavelength photons are due to collisions in which all of the electron's KE is given to the photon so KE $=e V=h f_{0}$.
SOLUTION From Eq. 28-4,
$$\lambda_{0}=\frac{h c}{e V}=\frac{\left(6.63 \times 10^{-34} \mathrm{~J} \cdot \mathrm{~s}\right)\left(3.0 \times 10^{8} \mathrm{~m} / \mathrm{s}\right)}{\left(1.6 \times 10^{-19} \mathrm{C}\right)\left(5.0 \times 10^{4} \mathrm{~V}\right)}=2.5 \times 10^{-11} \mathrm{~m}$$
or 0.025 nm .
NOTE This result agrees well with experiment, Fig. 28-11.

FIGURE 28-13 Bremsstrahlung photon produced by an electron decelerated by interaction with a target atom.

*SECTION 28-9 X-Ray Spectra and Atomic Number
819

---

<!-- Page 820 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 820

FIGURE 28-14 Fluorescence.

PHYSICS APPLIED
Fluorescence analysis and fluorescent lightbulbs

FIGURE 28-15 When UV light (a range of wavelengths) illuminates these various "fluorescent" rocks, they fluoresce in the visible region of the spectrum.

FIGURE 28-16 (a) Absorption of a photon. (b) Stimulated emission. $E_{\mathrm{u}}$ and $E_{\ell}$ refer to "upper" and "lower" energy states.

(a)

(b)

820
CHAPTER 28

*28-10 Fluorescence and Phosphorescence
When an atom is excited from one energy state to a higher one by the absorption of a photon, it may return to the lower level in a series of two (or more) transitions if there is at least one energy level in between (Fig. 28-14). The photons emitted will consequently have lower energy and frequency than the absorbed photon. When the absorbed photon is in the UV and the emitted photons are in the visible region of the spectrum, this phenomenon is called fluorescence (Fig. 28-15).

The wavelength for which fluorescence will occur depends on the energy levels of the particular atoms. Because the frequencies are different for different substances, and because many substances fluoresce readily, fluorescence is a powerful tool for identification of compounds. It is also used for assaying-determining how much of a substance is present-and for following substances along a natural metabolic pathway in biological organisms. For detection of a given compound, the stimulating light must be monochromatic, and solvents or other materials present must not fluoresce in the same region of the spectrum. Sometimes the observation of fluorescent light being emitted is sufficient to detect a compound. In other cases, spectrometers are used to measure the wavelengths and intensities of the emitted light.

Fluorescent lightbulbs work in a two-step process. The applied voltage accelerates electrons that strike atoms of the gas in the tube and cause them to be excited. When the excited atoms jump down to their normal levels, they emit UV photons which strike a fluorescent coating on the inside of the tube. The light we see is a result of this material fluorescing in response to the UV light striking it.

Materials such as those used for luminous watch dials, and other glow-in-the-dark products, are said to be phosphorescent. When an atom is raised to a normal excited state, it drops back down within about $10^{-8} \mathrm{~s}$. In phosphorescent substances, atoms can be excited by photon absorption to energy levels called metastable, which are states that last much longer because to jump down is a "forbidden" transition (Section 28-6). Metastable states can last even a few seconds or longer. In a collection of such atoms, many of the atoms will descend to the lower state fairly soon, but many will remain in the excited state for over an hour. Hence light will be emitted even after long periods. When you put a luminous watch dial close to a bright lamp, many atoms are excited to metastable states, and you can see the glow for a long time afterward.
28-11 Lasers
A laser is a device that can produce a very narrow intense beam of monochromatic coherent light. (By coherent, we mean that across any cross section of the beam, all parts have the same phase. ${ }^{\dagger}$ ) The emitted beam is a nearly perfect plane wave. An ordinary light source, on the other hand, emits light in all directions (so the intensity decreases rapidly with distance), and the emitted light is incoherent (the different parts of the beam are not in phase with each other). The excited atoms that emit the light in an ordinary lightbulb act independently, so each photon emitted can be considered as a short wave train lasting about $10^{-8} \mathrm{~s}$. Different wave trains bear no phase relation to one another. Just the opposite is true of lasers.

The action of a laser is based on quantum theory. We have seen that a photon can be absorbed by an atom if (and only if) the photon energy $h f$ corresponds to the energy difference between an occupied energy level of the atom and an available excited state, Fig. 28-16a. If the atom is already in the excited state, it may jump down spontaneously (i.e., no stimulus) to the lower state with the emission of a photon. However, if a photon with this same energy strikes the excited atom, it can stimulate the atom to make the transition sooner to the lower state, Fig. 28-16b. This phenomenon is called stimulated emission: not only do we still have the original photon, but also a second one of the same frequency as a result
${ }^{\dagger}$ See also Section 24-3.

---

<!-- Page 821 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39
Page 821

of the atom's transition. These two photons are exactly in phase, and they are moving in the same direction. This is how coherent light is produced in a laser. The name "laser" is an acronym for Light Amplification by Stimulated Emission of Radiation.

Normally, most atoms are in the lower state, so the majority of incident photons will be absorbed. To obtain the coherent light from stimulated emission, two conditions must be satisfied. First, the atoms must be excited to the higher state so that an inverted population is produced in which more atoms are in the upper state than in the lower one (Fig. 28-17). Then emission of photons will dominate over absorption. And second, the higher state must be a metastable state-a state in which the electrons remain longer than usual ${ }^{\dagger}$ so that the transition to the lower state occurs by stimulated emission rather than spontaneously.

Figure 28-18 is a schematic diagram of a laser: the "lasing" material is placed in a long narrow tube at the ends of which are two mirrors, one of which is partially transparent (transmitting perhaps 1 or $2 \%$ ). Some of the excited atoms drop down fairly soon after being excited. One of these is the blue atom shown on the far left in Fig. 28-18. If the emitted photon strikes another atom in the excited state, it stimulates this atom to emit a photon of the same frequency, moving in the same direction, and in phase with it. These two photons then move on to strike other atoms causing more stimulated emission. As the process continues, the number of photons multiplies. When the photons strike the end mirrors, most are reflected back, and as they move in the opposite direction, they continue to stimulate more atoms to emit photons. As the photons move back and forth between the mirrors, a small percentage passes through the partially transparent mirror at one end. These photons make up the narrow coherent external laser beam. (Inside the tube, some spontaneously emitted photons will be emitted at an angle to the axis, and these will merely go out the side of the tube and not affect the narrow width of the main beam.) of the main beam.)

FIGURE 28-18 Laser diagram, showing excited atoms stimulated to emit light.

FIGURE 28-17 Two energy levels for a collection of atoms. Each dot represents the energy state of one atom. (a) A normal situation; (b) an inverted population.

> CAUTION
> Laser: photons have same frequency and direction, and are in phase

In a well-designed laser, the spreading of the beam is limited only by diffraction, so the angular spread is $\approx \lambda / D$ (see Eq. 24-3 or 25-7) where $D$ is the diameter of the end mirror. The diffraction spreading can be incredibly small. The light energy, instead of spreading out in space as it does for an ordinary light source, can be a pencil-thin beam.

Creating an Inverted Population
The excitation of the atoms in a laser can be done in several ways to produce the necessary inverted population. In a ruby laser, the lasing material is a ruby rod consisting of $\mathrm{Al}_{2} \mathrm{O}_{3}$ with a small percentage of aluminum (Al) atoms replaced by chromium (Cr) atoms. The Cr atoms are the ones involved in lasing. In a process called optical pumping, the atoms are excited by strong flashes of light of wavelength 550 nm , which corresponds to a photon energy of 2.2 eV . As shown in Fig. 28-19, the atoms are excited from state $E_{0}$ to state $E_{2}$. The atoms quickly decay either back to $E_{0}$ or to the intermediate state $E_{1}$, which is metastable with a lifetime of about $3 \times 10^{-3} \mathrm{~s}$ (compared to $10^{-8} \mathrm{~s}$ for ordinary levels). With strong pumping action, more atoms can be found in the $E_{1}$ state than are in the $E_{0}$ state. Thus we have the inverted population needed for lasing. As soon as a few atoms in the $E_{1}$ state jump down to $E_{0}$, they emit photons that produce stimulated emission of the other atoms, and the lasing action begins. A ruby laser thus emits a beam whose photons have energy 1.8 eV and a wavelength of 694.3 nm (or "ruby-red" light).
${ }^{\dagger}$ An excited atom may land in such a state and can jump to a lower state only by a so-called forbidden transition (Section 28-6), which is why its lifetime is longer than normal.

FIGURE 28-19 Energy levels of chromium in a ruby crystal. Photons of energy 2.2 eV "pump" atoms from $E_{0}$ to $E_{2}$, which then decay to metastable state $E_{1}$. Lasing action occurs by stimulated emission of photons in transition from $E_{1}$ to $E_{0}$.

SECTION 28-11 Lasers
821

---

<!-- Page 822 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39
Page
822

FIGURE 28-20 Energy levels for He and Ne . He is excited in the electric discharge to the $E_{1}$ state. This energy is transferred to the $E_{3}^{\prime}$ level of the Ne by collision. $E_{3}^{\prime}$ is metastable and decays to $E_{2}^{\prime}$ by stimulated emission.

CAUTION
Laser is not an energy source

In a helium-neon laser ( $\mathrm{He}-\mathrm{Ne}$ ), the lasing material is a gas, a mixture of about $85 \% \mathrm{He}$ and $15 \% \mathrm{Ne}$. The atoms are excited by applying a high voltage to the tube so that an electric discharge takes place within the gas. In the process, some of the He atoms are raised to the metastable state $E_{1}$ shown in Fig. 28-20, which corresponds to a jump of 20.61 eV , almost exactly equal to an excited state in neon, 20.66 eV . The He atoms do not quickly return to the ground state by spontaneous emission, but instead often give their excess energy to a Ne atom when they collide-see Fig. 28-20. In such a collision, the He drops to the ground state and the Ne atom is excited to the state $E_{3}^{\prime}$ (the prime refers to neon states). The slight difference in energy ( 0.05 eV ) is supplied by the kinetic energy of the moving atoms. In this manner, the $E_{3}^{\prime}$ state in Ne-which is metastable-becomes more populated than the $E_{2}^{\prime}$ level. This inverted population between $E_{3}^{\prime}$ and $E_{2}^{\prime}$ is what is needed for lasing.

Very common now are semiconductor diode lasers, also called pn junction lasers, which utilize an inverted population of electrons between the conduction band and the lower-energy valence band (Section 29-9). When an electron jumps down, a photon can be emitted, which in turn can stimulate another electron to make the transition and emit another photon, in phase. The needed mirrors (as in Fig. 28-18) are made by the polished ends of the pn crystal. Semiconductor lasers are used in CD and DVD players (see below), and in many other applications.

Other types of laser include: chemical lasers, in which the energy input comes from the chemical reaction of highly reactive gases; dye lasers, whose frequency is tunable; $\mathrm{CO}_{2}$ gas lasers, capable of high power output in the infrared; and rare-earth solid-state lasers such as the high-power Nd:YAG laser.

The excitation of the atoms in a laser can be done continuously or in pulses. In a pulsed laser, the atoms are excited by periodic inputs of energy. In a continuous laser, the energy input is continuous: as atoms are stimulated to jump down to the lower level, they are soon excited back up to the upper level so the output is a continuous laser beam.

No laser is a source of energy. Energy must be put in, and the laser converts a part of it into an intense narrow beam output.
* Applications

The unique feature of light from a laser, that it is a coherent narrow beam, has found many applications. In everyday life, lasers are used as bar-code readers (at store checkout stands) and in compact disc (CD) and digital video disc (DVD) players. The laser beam reflects off the stripes and spaces of a bar code, or off the tiny pits of a CD or DVD as shown in Fig. 28-21a. The recorded information on a CD or DVD is a series of pits and spaces representing 0s and 1s (or "off" and "on") of a binary code (Section 17-10) that is decoded electronically before being sent to the audio or video system. The laser of a CD player starts reading at the inside of the disc which rotates at about 500 rpm at the start. As the disc rotates, the laser follows the spiral track (Fig. 28-21b), and as it moves outward the disc must slow down because each successive circumference ( $C=2 \pi r$ ) is slightly longer as $r$ increases; at the outer edge, the disc is rotating about 200 rpm . A 1-hour CD has a track roughly 5 km long; the track width is about $1600 \mathrm{~nm}(=1.6 \mu \mathrm{~m})$ and the distance between pits is about 800 nm . DVDs contain much more information.

FIGURE 28-21 (a) Reading a CD (or DVD). The fine beam of a laser, focused even more finely with lenses, is directed at the undersurface of a rotating compact disc. The beam is reflected back from the areas between pits but reflects much less from pits. The reflected light is detected as shown, reflected by a half-reflecting mirror MS. The strong and weak reflections correspond to the 0s and 1s of the binary code representing the audio or video signal. (b) A laser follows the CD track which starts near the center and spirals outward.

822
CHAPTER 28

(b)

---

<!-- Page 823 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 823

Standard DVDs use a thinner track $(0.7 \mu \mathrm{~m})$ and shorter pit length $(400 \mathrm{~nm})$. Blu-ray discs use a "blue" laser with a short wavelength ( 405 nm ) and narrower beam, allowing a narrower track $(0.3 \mu \mathrm{~m})$ that can store much more data for high definition. DVDs can also have two layers, one below the other. When the laser focuses on the second layer, the light passes through the semitransparent surface layer. The second layer may start reading at the outer edge instead of inside. DVDs can also have a single or double layer on both surfaces of the disc.

Lasers are a useful surgical tool. The narrow intense beam can be used to destroy tissue in a localized area, or to break up gallstones and kidney stones. Because of the heat produced, a laser beam can be used to "weld" broken tissue, such as a detached retina, Fig. 28-22, or to mold the cornea of the eye (by vaporizing tiny bits of material) to correct myopia and other eye defects (LASIK surgery). The laser beam can be carried by an optical fiber (Section 23-6) to the surgical point, sometimes as an additional fiber-optic path on an endoscope (again Section 23-6). An example is the removal of plaque clogging human arteries. Lasers have been used to destroy tiny organelles within a living cell by researchers studying how the absence of that organelle affects the behavior of the cell. Laser beams are used to destroy cancerous and precancerous cells; and the heat seals off capillaries and lymph vessels, thus "cauterizing" the wound to prevent spread of the disease.

The intense heat produced in a small area by a laser beam is used for welding and machining metals and for drilling tiny holes in hard materials. Because a laser beam is coherent, monochromatic, narrow, and essentially parallel, lenses can be used to focus the light into even smaller areas. The precise straightness of a laser beam is also useful to surveyors for lining up equipment accurately, especially in inaccessible places.
*28-12 Holography
One of the most interesting applications of laser light is the production of threedimensional images called holograms (see Fig. 28-23). In an ordinary photograph, the film simply records the intensity of light reaching it at each point. When the photograph or transparency is viewed, light reflecting from it or passing through it gives us a two-dimensional picture. In holography, the images are formed by interference, without lenses. A laser hologram is typically made on a photographic emulsion (film). A broadened laser beam is split into two parts by a half-silvered mirror, Fig. 28-24. One part goes directly to the film; the rest passes to the object to be photographed, from which it is reflected to the film. Light from every point on the object reaches each point on the film, and the interference of the two beams allows the film to record both the intensity and relative phase of the light at each point. It is crucial that the incident light be coherent-that is, in phase at all points-which is why a laser is used. After the film is developed, it is placed again in a laser beam and a three-dimensional image of the object is created. You can walk around such an image and see it from different sides as if it were the original object. Yet, if you try to touch it with your hand, there will be nothing material there.
(8)

PHYSICS APPLIED
Medical and other uses of lasers

FIGURE 28-22 Laser being used in eye surgery.

PHYSICS APPLIED
Holography

FIGURE 28-23 An athlete (race-car driver) puts his hand on, or through, a holographic image of himself.

FIGURE 28-24 Making a hologram. Light reflected from various points on the object interferes (at the film) with light from the direct beam.

823

---

<!-- Page 824 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39
Page
824

Volume or white-light holograms do not require a laser to see the image, but can be viewed with ordinary white light (preferably a nearly point source, such as the Sun or a clear bulb with a small bright filament). Such holograms must be made, however, with a laser. They are made not on thin film, but on a thick emulsion. The interference pattern in the film emulsion can be thought of as an array of bands or ribbons where constructive interference occurred. This array, and the reconstruction of the image, can be compared to Bragg scattering of X-rays from the atoms in a crystal (see Section 25-11). White light can reconstruct the image because the Bragg condition ( $m \lambda=2 d \sin \theta$ ) selects out the appropriate single wavelength. If the hologram is originally produced by lasers emitting the three additive primary colors (red, green, and blue), the three-dimensional image can be seen in full color when viewed with white light.

Summary

In 1925, Schrödinger and Heisenberg separately worked out a new theory, quantum mechanics, which is now considered to be the fundamental theory at the atomic level. It is a statistical theory rather than a deterministic one.

An important aspect of quantum mechanics is the Heisenberg uncertainty principle. It results from the wave-particle duality and the unavoidable interaction between an observed object and the observer.

One form of the uncertainty principle states that the position $x$ and momentum $p_{x}$ of an object cannot both be measured precisely at the same time. The products of the uncertainties, $(\Delta x)\left(\Delta p_{x}\right)$, can be no less than $\hbar(=h / 2 \pi)$ :
$$\left(\Delta p_{x}\right)(\Delta x) \gtrsim \hbar .$$

Another form of the uncertainty principle states that the energy can be uncertain (or nonconserved) by an amount $\Delta E$ for a time $\Delta t$, where
$$(\Delta E)(\Delta t) \gtrsim \hbar .$$

According to quantum mechanics, the state of an electron in an atom is specified by four quantum numbers: $n, \ell, m_{\ell}$, and $m_{s}$ :
(1) $n$, the principal quantum number, can take on any integer value $(1,2,3, \cdots)$ and corresponds to the quantum number of the old Bohr model;
(2) $\ell$, the orbital quantum number, can take on values from 0 up to $n-1$;
(3) $m_{\ell}$, the magnetic quantum number, can take on integer values from $-\ell$ to $+\ell$;
(4) $m_{s}$, the spin quantum number, can be $+\frac{1}{2}$ or $-\frac{1}{2}$.

The energy levels in the hydrogen atom depend on $n$, whereas in other atoms they depend on $n$ and $\ell$.

The orbital angular momentum of an atom has magnitude $L=\sqrt{\ell(\ell+1)} \hbar$ and $z$ component $L_{z}=m_{\ell} \hbar$.

When an external magnetic field is applied, the spectral lines are split (the Zeeman effect), indicating that the energy depends also on $m_{\ell}$ in this case.

Even in the absence of a magnetic field, precise measurements of spectral lines show a tiny splitting of the lines called fine structure, whose explanation is that the energy depends very slightly on $m_{\ell}$ and $m_{s}$.

Transitions between states that obey the selection rule $\Delta \ell= \pm 1$ are far more probable than other so-called forbidden transitions.

The arrangement of electrons in multi-electron atoms is governed by the Pauli exclusion principle, which states that no two electrons can occupy the same quantum state-that is, they cannot have the same set of quantum numbers $n, \ell, m_{\ell}$, and $m_{s}$.

As a result, electrons in multi-electron atoms are grouped into shells (according to the value of $n$ ) and subshells (according to $\ell$ ).

Electron configurations are specified using the numerical values of $n$, and using letters for $\ell: s, p, d, f$, etc., for $\ell=0,1,2,3$, and so on, plus a superscript for the number of electrons in that subshell. Thus, the ground state of hydrogen is $1 s^{1}$, whereas that for oxygen is $1 s^{2} 2 s^{2} 2 p^{4}$.

In the Periodic Table, the elements are arranged in horizontal rows according to increasing atomic number (= number of electrons in the neutral atom). The shell structure gives rise to a periodicity in the properties of the elements, so that each vertical column can contain elements with similar chemical properties.

X-rays, which are a form of electromagnetic radiation of very short wavelength, are produced when high-speed electrons strike a target. The spectrum of X-rays so produced consists of two parts, a continuous spectrum produced when the electrons are decelerated by atoms of the target, and peaks representing photons emitted by atoms of the target after being excited by collision with the high-speed electrons. Measurement of these peaks allows determination of inner energy levels of atoms and determination of atomic number $Z$.
[*Fluorescence occurs when absorbed UV photons are followed by emission of visible light, due to the special arrangement of energy levels of atoms of the material. Phosphorescent materials have metastable states (long-lived) that emit light seconds or minutes after absorption of light.]

Lasers produce a narrow beam of monochromatic coherent light (light waves in phase).
[*Holograms are images with a 3-dimensional quality, formed by interference of laser light.]

824
CHAPTER 28 Quantum Mechanics of Atoms

---

<!-- Page 825 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 825

Questions
1. Compare a matter wave $\Psi$ to ( $a$ ) a wave on a string, ( $b$ ) an EM wave. Discuss similarities and differences.
2. Explain why Bohr's theory of the atom is not compatible with quantum mechanics, particularly the uncertainty principle.
3. Explain why it is that the more massive an object is, the easier it becomes to predict its future position.
4. In view of the uncertainty principle, why does a baseball seem to have a well-defined position and speed, whereas an electron does not?
5. Would it ever be possible to balance a very sharp needle precisely on its point? Explain.
6. A cold thermometer is placed in a hot bowl of soup. Will the temperature reading of the thermometer be the same as the temperature of the hot soup before the measurement was made? Explain.
7. Does the uncertainty principle set a limit to how well you can make any single measurement of position? Explain.
8. If you knew the position of an object precisely, with no uncertainty, how well would you know its momentum?
9. When you check the pressure in a tire, doesn't some air inevitably escape? Is it possible to avoid this escape of air altogether? What is the relation to the uncertainty principle?
10. It has been said that the ground-state energy in the hydrogen atom can be precisely known but the excited states have some uncertainty in their values (an "energy width"). Is this consistent with the uncertainty principle in its energy form? Explain.
11. Which model of the hydrogen atom, the Bohr model or the quantum-mechanical model, predicts that the electron spends more time near the nucleus? Explain.
12. The size of atoms varies by only a factor of three or so, from largest to smallest, yet the number of electrons varies from one to over 100. Explain.
13. Excited hydrogen and excited helium atoms both radiate light as they jump down to the $n=1, \ell=0, m_{\ell}=0$ state. Why do the two elements have very different emission spectra?
14. How would the Periodic Table look if there were no electron spin but otherwise quantum mechanics were valid? Consider the first 20 elements or so.
15. Which of the following electron configurations are not allowed: (a) $1 s^{2} 2 s^{2} 2 p^{4} 3 s^{2} 4 p^{2}$; (b) $1 s^{2} 2 s^{2} 2 p^{8} 3 s^{1}$; (c) $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2} 3 p^{5} 4 s^{2} 4 d^{5} 4 f^{1}$ ? If not allowed, explain why.
16. In what column of the Periodic Table would you expect to find the atom with each of the following configurations:
(a) $1 s^{2} 2 s^{2} 2 p^{5}$;
(b) $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2}$;
(c) $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2} 3 p^{6}$;
(d) $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2} 3 p^{6} 4 s^{1}$ ?
17. Why do chlorine and iodine exhibit similar properties?
18. Explain why potassium and sodium exhibit similar properties.
19. Why are the chemical properties of the rare earths so similar? [Hint: Examine the Periodic Table.]
20. The ionization energy for neon $(Z=10)$ is 21.6 eV , and that for sodium $(Z=11)$ is 5.1 eV . Explain the large difference.
21. Why do we expect electron transitions deep within an atom to produce shorter wavelengths than transitions by outer electrons?
22. Does the Bohr model of the atom violate the uncertainty principle? Explain.
23. Briefly explain why noble gases are nonreactive and why alkali metals are highly reactive. (See Section 28-8.)
24. Compare spontaneous emission to stimulated emission.
25. How does laser light differ from ordinary light? How is it the same?
26. Explain how a $0.0005-\mathrm{W}$ laser beam, photographed at a distance, can seem much stronger than a $1000-\mathrm{W}$ street lamp at the same distance.
27. Does the intensity of light from a laser fall off as the inverse square of the distance? Explain.
*28. Why does the cutoff wavelength in Fig. 28-11 imply a photon nature for light?
*29. Why do we not expect perfect agreement between measured values of characteristic X-ray line wavelengths and those calculated using the Bohr model, as in Example 28-7?
*30. How would you figure out which lines in an X-ray spectrum correspond to $\mathrm{K}_{\alpha}, \mathrm{K}_{\beta}, \mathrm{L}$, etc., transitions?

MisConceptual Questions
1. An atom has the electron configuration $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2} 3 p^{6} 4 s^{1}$. How many electrons does this atom have?
(a) 15 .
(b) 19.
(c) 30 .
(d) 46.
2. For the electron configuration of MisConceptual Question 1, what orbital quantum numbers do the electrons have?
(a) 0 .
(d) 0 and 1 and 2 and 3.
(b) 0 and 1 .
(e) 0 and 1 and 2 and 3 and 4.
(c) 0 and 1 and 2 .
3. If a beam of electrons is fired through a slit,
(a) the electrons can be deflected because of their wave properties.
(b) only electrons that hit the edge of the slit are deflected.
(c) electrons can interact with electromagnetic waves in the slit, forming a diffraction pattern.
(d) the probability of an electron making it through the slit depends on the uncertainty principle.
4. What is meant by the ground state of an atom?
(a) All of the quantum numbers have their lowest values $\left(n=1, \ell=m_{\ell}=0\right)$.
(b) The principal quantum number of the electrons in the outer shell is 1 .
(c) All of the electrons are in the lowest energy state, consistent with the exclusion principle.
(d) The electrons are in the lowest state allowed by the uncertainty principle.
5. The Pauli exclusion principle applies to all electrons
(a) in the same shell, but not electrons in different shells.
(b) in the same container of atoms.
(c) in the same column of the Periodic Table.
(d) in incomplete shells.
$(e)$ in the same atom.

MisConceptual Questions
825

---

<!-- Page 826 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 826
6. Which of the following is the best paraphrasing of the Heisenberg uncertainty principle?
(a) Only if you know the exact position of a particle can you know the exact momentum of the particle.
(b) The larger the momentum of a particle, the smaller the position of the particle.
(c) The more precisely you know the position of a particle, the less well you can know the momentum of the particle.
(d) The better you know the position of a particle, the better you can know the momentum of the particle.
(e) How well you can determine the position and momentum of a particle depends on the particle's quantum numbers.
7. Which of the following is required by the Pauli exclusion principle?
(a) No electron in an atom can have the same set of quantum numbers as any other electron in that atom.
(b) Each electron in an atom must have the same $n$ value.
(c) Each electron in an atom must have different $m_{\ell}$ values.
(d) Only two electrons can be in any particular shell of an atom.
(e) No two electrons in a collection of atoms can have the exact same set of quantum numbers.
8. Under what condition(s) can the exact location and velocity of an electron be measured at the same time?
(a) The electron is in the ground state of the atom.
(b) The electron is in an excited state of the atom.
(c) The electron is free (not bound to an atom).
(d) Both (a) and (b).
(e) Never.
9. According to the uncertainty principle,
(a) there is always an uncertainty in a measurement of the position of a particle.
(b) there is always an uncertainty in a measurement of the momentum of a particle.
(c) there is always an uncertainty in a simultaneous measurement of both the position and momentum of a particle.
(d) All of the above.
10. Which of the following is not always a property of lasers?
(a) All of the photons in laser light have the same phase.
(b) All laser photons have nearly identical frequencies.
(c) Laser light moves as a beam, spreading out very slowly.
(d) Laser light is always brighter than other sources of light.
(e) Lasers depend on an inverted population of atoms where more atoms occupy a higher energy state than some lower energy state.

For assigned homework and other learning materials, go to the MasteringPhysics website.

MP)

Problems

28-2 Wave Function, Double-Slit
1. (II) The neutrons in a parallel beam, each having kinetic energy 0.025 eV , are directed through two slits 0.40 mm apart. How far apart will the interference peaks be on a screen 1.0 m away? [Hint: First find the wavelength of the neutron.]
2. (II) Pellets of mass 2.0 g are fired in parallel paths with speeds of $120 \mathrm{~m} / \mathrm{s}$ through a hole 3.0 mm in diameter. How far from the hole must you be to detect a $1.0-\mathrm{cm}-$ diameter spread in the beam of pellets?

28-3 Uncertainty Principle
3. (I) A proton is traveling with a speed of $(8.660 \pm 0.012) \times 10^{5} \mathrm{~m} / \mathrm{s}$. With what maximum precision can its position be ascertained? [Hint: $\Delta p=m \Delta v$.]
4. (I) If an electron's position can be measured to a precision of $2.4 \times 10^{-8} \mathrm{~m}$, how precisely can its speed be known?
5. (I) An electron remains in an excited state of an atom for typically $10^{-8} \mathrm{~s}$. What is the minimum uncertainty in the energy of the state (in eV )?
6. (II) The $Z^{0}$ boson, discovered in 1985 , is the mediator of the weak nuclear force, and it typically decays very quickly. Its average rest energy is 91.19 GeV , but its short lifetime shows up as an intrinsic width of 2.5 GeV . What is the lifetime of this particle? [Hint: See Example 28-3.]
7. (II) What is the uncertainty in the mass of a muon ( $m=105.7 \mathrm{MeV} / c^{2}$ ), specified in $\mathrm{eV} / \mathrm{c}^{2}$, given its lifetime of $2.20 \mu \mathrm{~s}$ ?

826
CHAPTER 28 Quantum Mechanics of Atoms
8. (II) A free neutron ( $m=1.67 \times 10^{-27} \mathrm{~kg}$ ) has a mean life of 880 s . What is the uncertainty in its mass (in kg )?
9. (II) An electron and a 140-g baseball are each traveling $120 \mathrm{~m} / \mathrm{s}$ measured to a precision of $0.065 \%$. Calculate and compare the uncertainty in position of each.
10. (II) A radioactive element undergoes an alpha decay with a lifetime of $12 \mu \mathrm{~s}$. If alpha particles are emitted with $5.5-\mathrm{MeV}$ kinetic energy, find the percent uncertainty $\Delta E / E$ in the particle energy.
11. (II) If an electron's position can be measured to a precision of 15 nm , what is the uncertainty in its speed? Assuming the minimum speed must be at least equal to its uncertainty, what is the electron's minimum kinetic energy?
12. (II) Estimate the lowest possible energy of a neutron contained in a typical nucleus of radius $1.2 \times 10^{-15} \mathrm{~m}$. [Hint: Assume a particle can have an energy as large as its uncertainty.]
13. (III) How precisely can the position of a $5.00-\mathrm{keV}$ electron be measured assuming its energy is known to $1.00 \%$ ?
14. (III) Use the uncertainty principle to show that if an electron were present in the nucleus $\left(r \approx 10^{-15} \mathrm{~m}\right)$, its kinetic energy (use relativity) would be hundreds of MeV . (Since such electron energies are not observed, we conclude that electrons are not present in the nucleus.) [Hint: Assume a particle can have an energy as large as its uncertainty.]

---

<!-- Page 827 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 7/12/16 8:06 PM Page 827

28-6 to 28-8 Quantum Numbers, Exclusion Principle
15. (I) For $n=6$, what values can $\ell$ have?
16. (I) For $n=6, \ell=3$, what are the possible values of $m_{\ell}$ and $m_{s}$ ?
17. (I) How many electrons can be in the $n=5, \ell=3$ subshell?
18. (I) How many different states are possible for an electron whose principal quantum number is $n=4$ ? Write down the quantum numbers for each state.
19. (I) List the quantum numbers for each electron in the ground state of (a) carbon ( $Z=6$ ), (b) aluminum ( $Z=13$ ).
20. (I) List the quantum numbers for each electron in the ground state of oxygen ( $Z=8$ ).
21. (I) Calculate the magnitude of the angular momentum of an electron in the $n=5, \ell=3$ state of hydrogen.
22. (I) If a hydrogen atom has $\ell=4$, what are the possible values for $n, m_{\ell}$, and $m_{s}$ ?
23. (II) If a hydrogen atom has $m_{\ell}=-3$, what are the possible values of $n, \ell$, and $m_{s}$ ?
24. (II) Show that there can be 18 electrons in a " $g$ " subshell.
25. (II) What is the full electron configuration in the ground state for elements with $Z$ equal to (a) 26, (b) 34, (c) 38 ? [Hint: See the Periodic Table inside the back cover.]
26. (II) What is the full electron configuration for (a) silver $(\mathrm{Ag})$, (b) gold (Au), (c) uranium (U)? [Hint: See the Periodic Table inside the back cover.]
27. (II) A hydrogen atom is in the $5 d$ state. Determine (a) the principal quantum number, (b) the energy of the state, (c) the orbital angular momentum and its quantum number $\ell$, and (d) the possible values for the magnetic quantum number.
28. (II) Estimate the binding energy of the third electron in lithium using the Bohr model. [Hint: This electron has $n=2$ and "sees" a net charge of approximately $+1 e$.] The measured value is 5.36 eV .
29. (II) Show that the total angular momentum is zero for a filled subshell.
30. (II) For each of the following atomic transitions, state whether the transition is allowed or forbidden, and why: (a) $4 p \rightarrow 3 p$; (b) $3 p \rightarrow 1 s$; (c) $4 d \rightarrow 2 d$; (d) $5 d \rightarrow 3 s$; (e) $4 s \rightarrow 2 p$.
31. (II) An electron has $m_{\ell}=2$ and is in its lowest possible energy state. What are the values of $n$ and $\ell$ for this electron?
*28-9 X-Rays
*32. (I) What are the shortest-wavelength X-rays emitted by electrons striking the face of a $28.5-\mathrm{kV}$ TV picture tube? What are the longest wavelengths?
*33. (I) If the shortest-wavelength bremsstrahlung X-rays emitted from an X-ray tube have $\lambda=0.035 \mathrm{~nm}$, what is the voltage across the tube?
*34. (I) Show that the cutoff wavelength $\lambda_{0}$ in an X-ray spectrum is given by
$$\lambda_{0}=\frac{1240 \mathrm{~nm}}{V}$$
where $V$ is the X-ray tube voltage in volts.
*35. (I) For the spectrum of X-rays emitted from a molybdenum target (discussed relative to Fig. 28-11), determine the maximum and minimum energy.
*36. (II) Estimate the wavelength for an $n=3$ to $n=2$ transition in iron ( $Z=26$ ).
*37. (II) Use the Bohr model to estimate the wavelength for an $n=3$ to $n=1$ transition in molybdenum ( $Z=42$ ). The measured value is 0.063 nm . Why do we not expect perfect agreement?
*38. (II) A mixture of iron and an unknown material is bombarded with electrons. The wavelengths of the $\mathrm{K}_{\alpha}$ lines are 194 pm for iron and 229 pm for the unknown. What is the unknown material?

28-11 Lasers
39. (II) A laser used to weld detached retinas puts out $25-\mathrm{ms}-$ long pulses of $640-\mathrm{nm}$ light which average $0.68-\mathrm{W}$ output during a pulse. How much energy can be deposited per pulse and how many photons does each pulse contain? [Hint: See Example 27-4.]
40. (II) A low-power laser used in a physics lab might have a power of 0.50 mW and a beam diameter of 3.0 mm . Calculate (a) the average light intensity of the laser beam, and (b) compare it to the intensity of a very powerful light bulb emitting 100-W of light as viewed from 2.0 m .
41. (II) Calculate the wavelength of the $\mathrm{He}-\mathrm{Ne}$ laser (see Fig. 28-20).
42. (II) Estimate the angular spread of a laser beam due to diffraction if the beam emerges through a 3.0 mm -diameter mirror. Assume that $\lambda=694 \mathrm{~nm}$. What would be the diameter of this beam if it struck (a) a satellite 340 km above the Earth, or (b) the Moon? [Hint: See Sections 24-5 and 25-7.]

General Problems
43. An electron in the $n=2$ state of hydrogen remains there on average about $10^{-8}$ s before jumping to the $n=1$ state. (a) Estimate the uncertainty in the energy of the $n=2$ state. (b) What fraction of the transition energy is this? (c) What is the wavelength, and width (in nm ), of this line in the spectrum of hydrogen?
44. What are the largest and smallest possible values for the angular momentum $L$ of an electron in the $n=6$ shell?
45. If an electron's position can be measured to a precision of $2.0 \times 10^{-8} \mathrm{~m}$, what is the uncertainty in its momentum? Assuming its momentum must be at least equal to its uncertainty, estimate the electron's wavelength.
46. The ionization (binding) energy of the outermost electron in boron is 8.26 eV . (a) Use the Bohr model to estimate the "effective charge," $Z_{\text {eff }}$, seen by this electron. (b) Estimate the average orbital radius.

General Problems
827

---

<!-- Page 828 -->

GIAN_PPA7_GE_28_803-828v4.1HR.QXD 26-08-2014 16:39 Page 828
47. Using the Bohr formula for the radius of an electron orbit, estimate the average distance from the nucleus for an electron in the innermost ( $n=1$ ) orbit of a uranium atom $(Z=92)$. Approximately how much energy would be required to remove this innermost electron?
48. Protons are accelerated from rest across 480 V . They are then directed at two slits 0.70 mm apart. How far apart will the interference peaks be on a screen 28 m away?
49. How many electrons can there be in an " $h$ " subshell?
50. (a) Show that the number of different states possible for a given value of $\ell$ is equal to $2(2 \ell+1)$. (b) What is this number for $\ell=0,1,2,3,4,5$, and 6 ?
51. Show that the number of different electron states possible for a given value of $n$ is $2 n^{2}$. (See Problem 50.)
52. A beam of electrons with kinetic energy 45 keV is shot through two narrow slits in a barrier. The slits are a distance $2.0 \times 10^{-6} \mathrm{~m}$ apart. If a screen is placed 45.0 cm behind the barrier, calculate the spacing between the "bright" fringes of the interference pattern produced on the screen.
53. The angular momentum in the hydrogen atom is given both by the Bohr model and by quantum mechanics. Compare the results for $n=2$.
54. The lifetime of a typical excited state in an atom is about 10 ns . Suppose an atom falls from one such excited state to a lower one, and emits a photon of wavelength about 500 nm . Find the fractional energy uncertainty $\Delta E / E$ and wavelength uncertainty $\Delta \lambda / \lambda$ of this photon.
55. A $1300-\mathrm{kg}$ car is traveling with a speed of $(22 \pm 0.22) \mathrm{m} / \mathrm{s}$. With what maximum precision can its position be determined?
56. An atomic spectrum contains a line with a wavelength centered at 488 nm . Careful measurements show the line is really spread out between 487 and 489 nm . Estimate the lifetime of the excited state that produced this line.
57. An electron and a proton, each initially at rest, are accelerated across the same voltage. Assuming that the uncertainty in their position is given by their de Broglie wavelength, find the ratio of the uncertainty in their momentum.
58. If the principal quantum number $n$ were limited to the range from 1 to 6, how many elements would we find in nature?
59. If your de Broglie wavelength were 0.50 m , how fast would you be moving if your mass is 68.0 kg ? Would you notice diffraction effects as you walk through a doorway? Approximately how long would it take you to walk through the doorway?
60. Suppose that the spectrum of an unknown element shows a series of lines with one out of every four matching a line from the Lyman series of hydrogen. Assuming that the unknown element is an ion with $Z$ protons and one electron, determine $Z$ and the element in question.
*61. Photons of wavelength 0.154 nm are emitted from the surface of a certain metal when it is bombarded with highenergy radiation. If this photon wavelength corresponds to the $\mathrm{K}_{\alpha}$ line, what is the element?

Search and Learn
1. Use the uncertainty principle to estimate the position uncertainty for the electron in the ground state of the hydrogen atom. [Hint: Determine the momentum using the Bohr model of Section 27-12 and assume the momentum can be anywhere between this value and zero.] How does this result compare to the Bohr radius?
2. On what factors does the periodicity of the Periodic Table depend? Consider the exclusion principle, quantization of angular momentum, spin, and any others you can think of.
3. Estimate (a) the quantum number $\ell$ for the orbital angular momentum of the Earth about the Sun, and $(b)$ the number of possible orientations for the plane of Earth's orbit.
4. Show that the diffraction spread of a laser beam, $\approx \lambda / D$ (Section 28-11), is precisely what you might expect from the uncertainty principle. See also Chapters 24 and 25. [Hint: Since the beam's width is constrained by the dimension of the aperture $D$, the component of the light's momentum perpendicular to the laser axis is uncertain.]
5. For noble gases, the halogens, and the alkali metals, explain the atomic structure that is common to each group and how that structure explains a common property of the group. (See Section 28-8.)

ANSWERS TO EXERCISES

A: (c).
B: $2.1 \times 10^{-24} \mathrm{~kg} \cdot \mathrm{~m} / \mathrm{s}, 2.3 \times 10^{6} \mathrm{~m} / \mathrm{s}$.
C: $2,1,0,-1,-2$.

D: $-0.38 \mathrm{eV}, \sqrt{20} \hbar$.
E: Add one line to Li in Table 28-2: $2,0,0,-\frac{1}{2}$.
F: $1 s^{2} 2 s^{2} 2 p^{6} 3 s^{2} 3 p^{6} 3 d^{10} 4 s^{2} 4 p^{1}$.

828
CHAPTER 28 Quantum Mechanics of Atoms

---

