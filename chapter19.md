# Chapter 19: DC Circuits

<!-- Page 526 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 525

This cell phone has an attachment that measures a person's blood sugar level, and plots it over a period of days. All electronic devices contain circuits that are dc, at least in part. The circuit diagram below shows a possible amplifier circuit for an audio output (cell phone ear piece). We have already met two of the circuit elements shown: resistors and capacitors, and we discuss them in circuits in this Chapter. (The large triangle is an amplifier chip containing transistors.) We also discuss how voltmeters and ammeters work, and how measurements affect the quantity being measured.

CONTENTS
19-1 EMF and Terminal Voltage
19-2 Resistors in Series and in Parallel
19-3 Kirchhoff's Rules
19-4 EMFs in Series and in Parallel; Charging a Battery
19-5 Circuits Containing Capacitors in Series and in Parallel
19-6 RC Circuits-Resistor and Capacitor in Series
19-7 Electric Hazards
19-8 Ammeters and VoltmetersMeasurement Affects the Quantity Being Measured

**TABLE 19-1 Symbols for Circuit Elements**

| Symbol | Device |
| --- | --- |
| $\dashv \vdash$ | Battery |
| $\dashv$ or tt | Capacitor |
| - | Resistor |
| - | 
Wire with negligible |
| resistance |  |

526

Circuit 1

Circuit 2

DC Circuits
CHAPTER-OPENING QUESTION-Guess now!
The automobile headlight bulbs shown in the circuits here are identical. The battery connection which produces more light is
(a) circuit 1 .
(b) circuit 2 .
(c) both the same.
(d) not enough information.

Electric circuits are basic parts of all electronic devices from cell phones and TV sets to computers and automobiles. Scientific measurements-whether in physics, biology, or medicine-make use of electric circuits. In Chapter 18, we discussed the basic principles of electric current. Now we apply these principles to analyze dc circuits involving combinations of batteries, resistors, and capacitors. We also study the operation of some useful instruments. ${ }^{\dagger}$

When we draw a diagram for a circuit, we represent batteries, capacitors, and resistors by the symbols shown in Table 19-1. Wires whose resistance is negligible compared with other resistance in the circuit are drawn as straight lines. A ground symbol ( $\frac{\perp}{\equiv}$ or $\frac{\perp}{}$ ) may mean a real connection to the ground, perhaps via a metal pipe, or it may mean a common connection, such as the frame of a car.

For the most part in this Chapter, except in Section 19-6 on $R C$ circuits, we will be interested in circuits operating in their steady state. We won't be looking at a circuit at the moment a change is made in it, such as when a battery or resistor is connected or disconnected, but only when the currents have reached their steady values.
${ }^{\dagger}$ AC circuits that contain only a voltage source and resistors can be analyzed like the dc circuits in this Chapter. However, ac circuits that contain capacitors and other circuit elements are more complicated, and we discuss them in Chapter 21.

---

<!-- Page 527 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 527

19-1 EMF and Terminal Voltage
To have current in an electric circuit, we need a device such as a battery or an electric generator that transforms one type of energy (chemical, mechanical, or light, for example) into electric energy. Such a device is called a source of electromotive force ${ }^{\dagger}$ or of emf. The potential difference between the terminals of such a source, when no current flows to an external circuit, is called the emf of the source. The symbol $\mathscr{E}$ is usually used for emf (don't confuse $\mathscr{E}$ with $E$ for electric field), and its unit is volts.

A battery is not a source of constant current-the current out of a battery varies according to the resistance in the circuit. A battery is, however, a nearly constant voltage source, but not perfectly constant as we now discuss. For example, if you start a car with the headlights on, you may notice the headlights dim. This happens because the starter draws a large current, and the battery voltage drops below its rated emf as a result. The voltage drop occurs because the chemical reactions in a battery cannot supply charge fast enough to maintain the full emf. For one thing, charge must move (within the electrolyte) between the electrodes of the battery, and there is always some hindrance to completely free flow. Thus, a battery itself has some resistance, which is called its internal resistance; it is usually designated $r$.

A real battery is modeled as if it were a perfect emf $\mathscr{E}$ in series with a resistor $r$, as shown in Fig. 19-1. Since this resistance $r$ is inside the battery, we can never separate it from the battery. The two points a and b in Fig. 19-1 represent the two terminals of the battery. What we measure is the terminal voltage $V_{\mathrm{ab}}=V_{\mathrm{a}}-V_{\mathrm{b}}$. When no current is drawn from the battery, the terminal voltage equals the emf, which is determined by the chemical reactions in the battery: $V_{\mathrm{ab}}=\mathscr{E}$. However, when a current $I$ flows from the battery there is an internal drop in voltage equal to Ir. Thus the terminal voltage (the actual voltage applied to a circuit) is
$$V_{\mathrm{ab}}=\mathscr{E}-I r . \quad[\text { current } I \text { flows from battery }] \mathbf{( 1 9 - 1 )}$$

For example, if a $12-\mathrm{V}$ battery has an internal resistance of $0.1 \Omega$, then when 10 A flows from the battery, the terminal voltage is $12 \mathrm{~V}-(10 \mathrm{~A})(0.1 \Omega)=11 \mathrm{~V}$. The internal resistance of a battery is usually small. For example, an ordinary flashlight battery when fresh may have an internal resistance of perhaps $0.05 \Omega$. (However, as it ages and the electrolyte dries out, the internal resistance increases to many ohms.)

EXAMPLE 19-1 Battery with internal resistance. A $65.0 \Omega$ resistor is connected to the terminals of a battery whose emf is 12.0 V and whose internal resistance is $0.5 \Omega$, Fig. 19-2. Calculate (a) the current in the circuit, (b) the terminal voltage of the battery, $V_{\mathrm{ab}}$, and ( $c$ ) the power dissipated in the resistor $R$ and in the battery's internal resistance $r$.
APPROACH We first consider the battery as a whole, which is shown in Fig. 19-2 as an $\operatorname{emf}_{\mathscr{E} \mathscr{E} \text { and internal resistance } r \text { between points } \mathrm{a} \text { and } \mathrm{b} \text {. Then we apply }} V=I R$ to the circuit itself.
SOLUTION (a) From Eq. 19-1, we have $V_{\mathrm{ab}}=\mathscr{E}-I r$. We apply Ohm's law (Eq. 18-2) to this battery and the resistance $R$ of the circuit: $V_{\mathrm{ab}}=I R$. Hence
$$\mathscr{E}-I r=I R$$
or $\mathscr{E}=I(R+r)$. So
$$I=\frac{\mathscr{E}}{R+r}=\frac{12.0 \mathrm{~V}}{65.0 \Omega+0.5 \Omega}=\frac{12.0 \mathrm{~V}}{65.5 \Omega}=0.183 \mathrm{~A} .$$
(b) The terminal voltage is
$$V_{\mathrm{ab}}=\mathscr{E}-I r=12.0 \mathrm{~V}-(0.183 \mathrm{~A})(0.5 \Omega)=11.9 \mathrm{~V} .$$
(c) The power dissipated in $R$ (Eq. 18-6) is
$$P_{R}=I^{2} R=(0.183 \mathrm{~A})^{2}(65.0 \Omega)=2.18 \mathrm{~W},$$
and in the battery's resistance $r$ it is
$$P_{r}=I^{2} r=(0.183 \mathrm{~A})^{2}(0.5 \Omega)=0.02 \mathrm{~W} .$$
${ }^{\dagger}$ The term "electromotive force" is a misnomer-it does not refer to a "force" that is measured in newtons. To avoid confusion, we use the abbreviation, emf.

CAUTION
Why battery voltage isn't perfectly constant

FIGURE 19-1 Diagram for an electric cell or battery.

FIGURE 19-2 Example 19-1.

SECTION 19-1 EMF and Terminal Voltage
527

---

<!-- Page 528 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 528

FIGURE 19-3 (a) Resistances connected in series. (b) Resistances could be lightbulbs, or any other type of resistance. (c) Equivalent single resistance $R_{\text {eq }}$ that draws the same current: $R_{\text {eq }}=R_{1}+R_{2}+R_{3}$.

FIGURE 19-4 (a) Resistances connected in parallel. (b) Resistances could be lightbulbs. (c) The equivalent circuit with $R_{\text {eq }}$ obtained from Eq. 19-4: $\frac{1}{R_{\text {eq }}}=\frac{1}{R_{1}}+\frac{1}{R_{2}}+\frac{1}{R_{3}}$.

(a)

(b)

(c)

Unless stated otherwise, we assume the battery's internal resistance is negligible, and the battery voltage given is its terminal voltage, which we will usually write as $V$ rather than $V_{\mathrm{ab}}$. Do not confuse $V$ (italic) for voltage, with V (not italic) for the volt unit.
19-2 Resistors in Series and in Parallel
When two or more resistors are connected end to end along a single path as shown in Fig. 19-3a, they are said to be connected in series. The resistors could be simple resistors as were pictured in Fig. 18-11, or they could be lightbulbs (Fig. 19-3b), or heating elements, or other resistive devices. Any charge that passes through $R_{1}$ in Fig. 19-3a will also pass through $R_{2}$ and then $R_{3}$. Hence the same current $I$ passes through each resistor. (If it did not, this would imply that either charge was not conserved, or that charge was accumulating at some point in the circuit, which does not happen in the steady state.)

We let $V$ represent the potential difference (voltage) across all three resistors in Fig. 19-3a. We assume all other resistance in the circuit can be ignored, so $V$ equals the terminal voltage supplied by the battery. We let $V_{1}, V_{2}$, and $V_{3}$ be the potential differences across each of the resistors, $R_{1}, R_{2}$, and $R_{3}$, respectively. From Ohm's law, $V=I R$, we can write $V_{1}=I R_{1}, V_{2}=I R_{2}$, and $V_{3}=I R_{3}$. Because the resistors are connected end to end, energy conservation tells us that the total voltage $V$ is equal to the sum of the voltages across each resistor:
$$V=V_{1}+V_{2}+V_{3}=I R_{1}+I R_{2}+I R_{3} . \quad[\text { series }]$$

Now let us determine the equivalent single resistance $R_{\text {eq }}$ that would draw the same current $I$ as our combination of three resistors in series; see Fig. 19-3c. Such a single resistance $R_{\text {eq }}$ would be related to $V$ by
$$V=I R_{\mathrm{eq}} .$$

We equate this expression with Eq. 19-2, $V=I\left(R_{1}+R_{2}+R_{3}\right)$, and find
$$R_{\mathrm{eq}}=R_{1}+R_{2}+R_{3} .$$

When we put several resistances in series, the total or equivalent resistance is the sum of the separate resistances. (Sometimes we call it "net resistance.") This sum applies to any number of resistances in series. Note that when you add more resistance to the circuit, the current through the circuit will decrease. For example, if a $12-\mathrm{V}$ battery is connected to a $4-\Omega$ resistor, the current will be 3 A . But if the $12-\mathrm{V}$ battery is connected to three $4-\Omega$ resistors in series, the total resistance is $12 \Omega$ and the current through the entire circuit will be only 1 A .

Another way to connect resistors is in parallel, so that the current from the source splits into separate branches or paths (Fig.19-4a). Wiring in houses and buildings is arranged so all electric devices are in parallel, as we saw in Chapter 18, Fig. 18-20. With parallel wiring, if you disconnect one device (say, $R_{1}$ in Fig. 19-4a), the current to the other devices is not interrupted. Compare to a series circuit, where if one device (say, $R_{1}$ in Fig. 19-3a) is disconnected, the current is stopped to all others.

In a parallel circuit, Fig. 19-4a, the total current $I$ that leaves the battery splits into three separate paths. We let $I_{1}, I_{2}$, and $I_{3}$ be the currents through each of the resistors, $R_{1}, R_{2}$, and $R_{3}$, respectively. Because electric charge is conserved, the current $I$ flowing into junction A (where the different wires or conductors meet, Fig. 19-4a) must equal the current flowing out of the junction. Thus
$$I=I_{1}+I_{2}+I_{3} .$$

When resistors are connected in parallel, each has the same voltage across it. (Indeed, any two points in a circuit connected by a wire of negligible resistance are at the same potential.) Hence the full voltage of the battery is applied to each resistor in Fig. 19-4a. Applying Ohm's law to each resistor, we have
$$I_{1}=\frac{V}{R_{1}}, \quad I_{2}=\frac{V}{R_{2}}, \quad \text { and } \quad I_{3}=\frac{V}{R_{3}} .$$

Let us now determine what single resistor $R_{\text {eq }}$ (Fig. 19-4c) will draw the same

528
CHAPTER 19 DC Circuits

---

<!-- Page 529 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 529

current $I$ as these three resistances in parallel. This equivalent resistance $R_{\text {eq }}$ must satisfy Ohm's law too:
$$I=\frac{V}{R_{\mathrm{eq}}}$$

We now combine the equations above:
$$\begin{aligned}
I & =I_{1}+I_{2}+I_{3} \\
\frac{V}{R_{\mathrm{eq}}} & =\frac{V}{R_{1}}+\frac{V}{R_{2}}+\frac{V}{R_{3}} .
\end{aligned}$$

When we divide out the $V$ from each term, we have
$$\frac{1}{R_{\mathrm{eq}}}=\frac{1}{R_{1}}+\frac{1}{R_{2}}+\frac{1}{R_{3}}$$

For example, suppose you connect two 4 - $\Omega$ loudspeakers in parallel to a single set of output terminals of an amplifier. The equivalent resistance of the two $4-\Omega$ "resistors" in parallel is
$$\frac{1}{R_{\mathrm{eq}}}=\frac{1}{4 \Omega}+\frac{1}{4 \Omega}=\frac{2}{4 \Omega}=\frac{1}{2 \Omega},$$
and so $R_{\mathrm{eq}}=2 \Omega$. Thus the net (or equivalent) resistance is less than each single resistance. This may at first seem surprising. But remember that when you connect resistors in parallel, you are giving the current additional paths to follow. Hence the net resistance will be less. ${ }^{\dagger}$

Equation 19-3 and 19-4 make good sense. Recalling Eq. 18-3 for resistivity, $R=\rho \ell / A$, we see that placing resistors in series effectively increases the length and therefore the resistance; putting resistors in parallel effectively increases the area through which current flows, thus reducing the overall resistance.

Note that whenever a group of resistors is replaced by the equivalent resistance, current and voltage and power in the rest of the circuit are unaffected.

EXERCISE A You have a $10-\Omega$ and a $15-\Omega$ resistor. What is the smallest and largest equivalent resistance that you can make with these two resistors?

CONCEPTUAL EXAMPLE 19-2 Series or parallel? (a) The lightbulbs in Fig. 19-5 are identical. Which configuration produces more light? (b) Which way do you think the headlights of a car are wired? Ignore change of filament resistance $R$ with current.

RESPONSE (a) The equivalent resistance of the parallel circuit is found from Eq. $19-4,1 / R_{\text {eq }}=1 / R+1 / R=2 / R$. Thus $R_{\text {eq }}=R / 2$. The parallel combination then has lower resistance $(=R / 2)$ than the series combination ( $R_{\text {eq }}=R+R=2 R$ ). There will be more total current in the parallel configuration (2), since $I=V / R_{\text {eq }}$ and $V$ is the same for both circuits. The total power transformed, which is related to the light produced, is $P=I V$, so the greater current in (2) means more light is produced.
(b) Headlights are wired in parallel (2), because if one bulb goes out, the other bulb can stay lit. If they were in series (1), when one bulb burned out (the filament broke), the circuit would be open and no current would flow, so neither bulb would light.

EXERCISE B Return to the Chapter-Opening Question, page 526, and answer it again now. Try to explain why you may have answered differently the first time.
${ }^{\dagger}$ An analogy may help. Consider two identical pipes taking in water near the top of a dam and releasing it at the bottom as shown in the figure to the right. If both pipes are open, rather than only one, twice as much water will flow through. That is, the net resistance to the flow of water will be reduced by half with two equal pipes open, just as for electrical resistors in parallel.

(1) Series

(2) Parallel

FIGURE 19-5 Example 19-2.

SECTION 19-2 Resistors in Series and in Parallel
529

---

<!-- Page 530 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 530

FIGURE 19-6 Example 19-3.

FIGURE 19-7 (a) Circuit for Examples 19-4 and 19-5. (b) Equivalent circuit, showing the equivalent resistance of $290 \Omega$ for the two parallel resistors in (a).

EXAMPLE 19-3 Series and parallel resistors. Two $100-\Omega$ resistors are connected (a) in parallel, and (b) in series, to a 24.0-V battery (Fig. 19-6). What is the current through each resistor and what is the equivalent resistance of each circuit? APPROACH We use Ohm's law and the ideas just discussed for series and parallel connections to get the current in each case. We can also use Eqs. 19-3 and 19-4. SOLUTION (a) Any given charge (or electron) can flow through only one or the other of the two resistors in Fig. 19-6a. Just as a river may break into two streams when going around an island, here too the total current $I$ from the battery (Fig. 19-6a) splits to flow through each resistor, so $I$ equals the sum of the separate currents through the two resistors:
$$I=I_{1}+I_{2} .$$

The potential difference across each resistor is the battery voltage $V=24.0 \mathrm{~V}$. Applying Ohm's law to each resistor gives
$$I=I_{1}+I_{2}=\frac{V}{R_{1}}+\frac{V}{R_{2}}=\frac{24.0 \mathrm{~V}}{100 \Omega}+\frac{24.0 \mathrm{~V}}{100 \Omega}=0.24 \mathrm{~A}+0.24 \mathrm{~A}=0.48 \mathrm{~A} .$$

The equivalent resistance is
$$R_{\mathrm{eq}}=\frac{V}{I}=\frac{24.0 \mathrm{~V}}{0.48 \mathrm{~A}}=50 \Omega .$$

We could also have obtained this result from Eq. 19-4:
$$\frac{1}{R_{\mathrm{eq}}}=\frac{1}{100 \Omega}+\frac{1}{100 \Omega}=\frac{2}{100 \Omega}=\frac{1}{50 \Omega},$$
so $R_{\mathrm{eq}}=50 \Omega$.
(b) All the current that flows out of the battery passes first through $R_{1}$ and then through $R_{2}$ because they lie along a single path, Fig. 19-6b. So the current $I$ is the same in both resistors; the potential difference $V$ across the battery equals the total change in potential across the two resistors:
$$V=V_{1}+V_{2} .$$

Ohm's law gives $V=I R_{1}+I R_{2}=I\left(R_{1}+R_{2}\right)$. Hence
$$I=\frac{V}{R_{1}+R_{2}}=\frac{24.0 \mathrm{~V}}{100 \Omega+100 \Omega}=0.120 \mathrm{~A} .$$

The equivalent resistance, using Eq. 19-3, is $R_{\text {eq }}=R_{1}+R_{2}=200 \Omega$. We can also get $R_{\text {eq }}$ by thinking from the point of view of the battery: the total resistance $R_{\text {eq }}$ must equal the battery voltage divided by the current it delivers:
$$R_{\mathrm{eq}}=\frac{V}{I}=\frac{24.0 \mathrm{~V}}{0.120 \mathrm{~A}}=200 \Omega .$$

NOTE The voltage across $R_{1}$ is $V_{1}=I R_{1}=(0.120 \mathrm{~A})(100 \Omega)=12.0 \mathrm{~V}$, and that across $R_{2}$ is $V_{2}=I R_{2}=12.0 \mathrm{~V}$, each being half of the battery voltage. A simple circuit like Fig. 19-6b is thus often called a simple voltage divider.

EXAMPLE 19-4 Circuit with series and parallel resistors. How much current is drawn from the battery shown in Fig. 19-7a?
APPROACH The current $I$ that flows out of the battery all passes through the $400-\Omega$ resistor, but then it splits into $I_{1}$ and $I_{2}$ passing through the $500-\Omega$ and $700-\Omega$ resistors. The latter two resistors are in parallel with each other. We look for something that we already know how to treat. So let's start by finding the equivalent resistance, $R_{\mathrm{P}}$, of the parallel resistors, $500 \Omega$ and $700 \Omega$. Then we can consider this $R_{\mathrm{P}}$ to be in series with the $400-\Omega$ resistor.
SOLUTION The equivalent resistance, $R_{\mathrm{P}}$, of the $500-\Omega$ and $700-\Omega$ resistors in parallel is
$$\frac{1}{R_{\mathrm{P}}}=\frac{1}{500 \Omega}+\frac{1}{700 \Omega}=0.0020 \Omega^{-1}+0.0014 \Omega^{-1}=0.0034 \Omega^{-1} .$$

This is $1 / R_{\mathrm{P}}$, so we take the reciprocal to find $R_{\mathrm{P}}$.

530
CHAPTER 19 DC Circuits

---

<!-- Page 531 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 531]

It is a common mistake to forget to take this reciprocal. The units of reciprocal ohms, $\Omega^{-1}$, are a reminder. Thus
$$R_{\mathrm{P}}=\frac{1}{0.0034 \Omega^{-1}}=290 \Omega .$$

This $290 \Omega$ is the equivalent resistance of the two parallel resistors, and is in series with the $400-\Omega$ resistor (see equivalent circuit, Fig. 19-7b). To find the total equivalent resistance $R_{\text {eq }}$, we add the $400-\Omega$ and $290-\Omega$ resistances, since they are in series:
$$R_{\mathrm{eq}}=400 \Omega+290 \Omega=690 \Omega .$$

The total current flowing from the battery is then
$$I=\frac{V}{R_{\mathrm{eq}}}=\frac{12.0 \mathrm{~V}}{690 \Omega}=0.0174 \mathrm{~A} \approx 17 \mathrm{~mA} .$$

NOTE This $I$ is also the current flowing through the $400-\Omega$ resistor, but not through the $500-\Omega$ and $700-\Omega$ resistors (both currents are less-see the next Example).

EXAMPLE 19-5 Current in one branch. What is the current $I_{1}$ through the 500-Ω resistor in Fig. 19-7a?
APPROACH We need the voltage across the 500 - $\Omega$ resistor, which is the voltage between points b and c in Fig. 19-7a, and we call it $V_{\mathrm{bc}}$. Once $V_{\mathrm{bc}}$ is known, we can apply Ohm's law, $V=I R$, to get the current. First we find the voltage across the $400-\Omega$ resistor, $V_{\mathrm{ab}}$, since we know that 17.4 mA passes through it (Example 19-4).
SOLUTION $V_{\mathrm{ab}}$ can be found using $V=I R$ :
$$V_{\mathrm{ab}}=(0.0174 \mathrm{~A})(400 \Omega)=7.0 \mathrm{~V} .$$

The total voltage across the network of resistors is $V_{\mathrm{ac}}=12.0 \mathrm{~V}$, so $V_{\mathrm{bc}}$ must be $12.0 \mathrm{~V}-7.0 \mathrm{~V}=5.0 \mathrm{~V}$. Ohm's law gives the current $I_{1}$ through the 500 - $\Omega$ resistor:
$$I_{1}=\frac{5.0 \mathrm{~V}}{500 \Omega}=1.0 \times 10^{-2} \mathrm{~A}=10 \mathrm{~mA} .$$

This is the answer we wanted. We can also calculate the current $I_{2}$ through the $700-\Omega$ resistor since the voltage across it is also 5.0 V :
$$I_{2}=\frac{5.0 \mathrm{~V}}{700 \Omega}=7 \mathrm{~mA} .$$

NOTE When $I_{1}$ combines with $I_{2}$ to form the total current $I$ (at point c in Fig. 19-7a), their sum is $10 \mathrm{~mA}+7 \mathrm{~mA}=17 \mathrm{~mA}$. This equals the total current $I$ as calculated in Example 19-4, as it should.

CONCEPTUAL EXAMPLE 19-6 Bulb brightness in a circuit. The circuit in Fig. 19-8 has three identical lightbulbs, each of resistance $R$. (a) When switch S is closed, how will the brightness of bulbs A and B compare with that of bulb C ? (b) What happens when switch S is opened? Use a minimum of mathematics.

RESPONSE (a) With switch S closed, the current that passes through bulb C must split into two equal parts when it reaches the junction leading to bulbs A and B because the resistance of bulb A equals that of B . Thus, A and B each receive half of C's current; A and B will be equally bright, but less bright than $\mathrm{C}\left(P=I^{2} R\right)$. (b) When the switch S is open, no current can flow through bulb A , so it will be dark. Now, the same current passes through bulbs B and C , so B and C will be equally bright. The equivalent resistance of this circuit ( $=R+R$ ) is greater than that of the circuit with the switch closed, so the current leaving the battery is reduced. Thus, bulb C will be dimmer when we open the switch, but bulb B will be brighter because it gets more current when the switch is open (you may want to use some mathematics here).

EXERCISE C A $100-\mathrm{W}, 120-\mathrm{V}$ lightbulb and a $60-\mathrm{W}, 120-\mathrm{V}$ lightbulb are connected in two different ways as shown in Fig. 19-9. In each case, which bulb glows more brightly? Ignore change of filament resistance with current (and temperature).

CAUTION
Remember to take the reciprocal

FIGURE 19-8 Example 19-6, three identical lightbulbs. Each yellow circle with $\mathbf{- M}$ - inside represents a lightbulb and its resistance.

FIGURE 19-9 Exercise C.

SECTION 19-2 Resistors in Series and in Parallel
531

---

<!-- Page 532 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 532

FIGURE 19-10 Circuit for Example 19-7, where $r$ is the internal resistance of the battery.

FIGURE 19-11 Currents can be calculated using Kirchhoff's rules.

EXAMPLE 19-7 Analyzing a circuit. A 9.0-V battery whose internal resistance $r$ is $0.50 \Omega$ is connected in the circuit shown in Fig. 19-10a. (a) How much current is drawn from the battery? (b) What is the terminal voltage of the battery? (c) What is the current in the $6.0-\Omega$ resistor?

APPROACH To find the current out of the battery, we first need to determine the equivalent resistance $R_{\text {eq }}$ of the entire circuit, including $r$, which we do by identifying and isolating simple series or parallel combinations of resistors. Once we find $I$ from Ohm's law, $I=\mathscr{E} / R_{\text {eq }}$, we get the terminal voltage using $V_{\mathrm{ab}}=\mathscr{E}-\operatorname{Ir}$. For ( $c$ ) we apply Ohm's law to the 6.0 - $\Omega$ resistor.
SOLUTION (a) We want to determine the equivalent resistance of the circuit. But where do we start? We note that the $4.0-\Omega$ and $8.0-\Omega$ resistors are in parallel, and so have an equivalent resistance $R_{\text {eq } 1}$ given by
$$\frac{1}{R_{\mathrm{eq} 1}}=\frac{1}{8.0 \Omega}+\frac{1}{4.0 \Omega}=\frac{3}{8.0 \Omega} ;$$
so $R_{\text {eq } 1}=2.7 \Omega$. This $2.7 \Omega$ is in series with the 6.0 - $\Omega$ resistor, as shown in the equivalent circuit of Fig. 19-10b. The net resistance of the lower arm of the circuit is then
$$R_{\mathrm{eq} 2}=6.0 \Omega+2.7 \Omega=8.7 \Omega,$$
as shown in Fig. 19-10c. The equivalent resistance $R_{\text {eq } 3}$ of the $8.7-\Omega$ and $10.0-\Omega$ resistances in parallel is given by
$$\frac{1}{R_{\mathrm{eq} 3}}=\frac{1}{10.0 \Omega}+\frac{1}{8.7 \Omega}=0.21 \Omega^{-1},$$
so $R_{\text {eq } 3}=\left(1 / 0.21 \Omega^{-1}\right)=4.8 \Omega$. This $4.8 \Omega$ is in series with the 5.0 - $\Omega$ resistor and the 0.50 - $\Omega$ internal resistance of the battery (Fig. 19-10d), so the total equivalent resistance $R_{\text {eq }}$ of the circuit is $R_{\text {eq }}=4.8 \Omega+5.0 \Omega+0.50 \Omega=10.3 \Omega$. Hence the current drawn is
$$I=\frac{\mathscr{E}}{R_{\mathrm{eq}}}=\frac{9.0 \mathrm{~V}}{10.3 \Omega}=0.87 \mathrm{~A} .$$
(b) The terminal voltage of the battery is
$$V_{\mathrm{ab}}=\mathscr{E}-I r=9.0 \mathrm{~V}-(0.87 \mathrm{~A})(0.50 \Omega)=8.6 \mathrm{~V} .$$
(c) Now we can work back and get the current in the 6.0 - $\Omega$ resistor. It must be the same as the current through the $8.7 \Omega$ shown in Fig. 19-10c (why?). The voltage across that $8.7 \Omega$ will be the emf of the battery minus the voltage drops across $r$ and the 5.0 - $\Omega$ resistor: $V_{8.7}=9.0 \mathrm{~V}-(0.87 \mathrm{~A})(0.50 \Omega+5.0 \Omega)$. Applying Ohm's law, we get the current (call it $I^{\prime}$ )
$$I^{\prime}=\frac{9.0 \mathrm{~V}-(0.87 \mathrm{~A})(0.50 \Omega+5.0 \Omega)}{8.7 \Omega}=0.48 \mathrm{~A} .$$

This is the current through the $6.0-\Omega$ resistor.
19-3 Kirchhoff's Rules
In the last few Examples we have been able to find the currents in circuits by combining resistances in series and parallel, and using Ohm's law. This technique can be used for many circuits. However, some circuits are too complicated for that analysis. For example, we cannot find the currents in each part of the circuit shown in Fig. 19-11 simply by combining resistances as we did before.

To deal with complicated circuits, we use Kirchhoff's rules, devised by G. R. Kirchhoff (1824-1887) in the mid-nineteenth century. There are two rules, and they are simply convenient applications of the laws of conservation of charge and energy.

532
CHAPTER 19 DC Circuits

---

<!-- Page 533 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 53\}

Kirchhoff's first rule or junction rule is based on the conservation of electric charge (we already used it to derive the equation for parallel resistors). It states that
at any junction point, the sum of all currents entering the junction must equal the sum of all currents leaving the junction.
That is, whatever charge goes in must come out. For example, at the junction point a in Fig. 19-11, $I_{3}$ is entering whereas $I_{1}$ and $I_{2}$ are leaving. Thus Kirchhoff's junction rule states that $I_{3}=I_{1}+I_{2}$. We already saw an instance of this in the note at the end of Example 19-5.

Kirchhoff's second rule or loop rule is based on the conservation of energy. It states that
the sum of the changes in potential around any closed loop of a circuit must be zero.

To see why this rule should hold, consider a rough analogy with the potential energy of a roller coaster on its track. When the roller coaster starts from the station, it has a particular potential energy. As it is pulled up the first hill, its gravitational potential energy increases and reaches a maximum at the top. As it descends the other side, its potential energy decreases and reaches a local minimum at the bottom of the hill. As the roller coaster continues on its up and down path, its potential energy goes through more changes. But when it arrives back at the starting point, it has exactly as much potential energy as it had when it started at this point. Another way of saying this is that there was as much uphill as there was downhill.

Similar reasoning can be applied to an electric circuit. We will analyze the circuit of Fig. 19-11 shortly, but first we consider the simpler circuit in Fig. 19-12. We have chosen it to be the same as the equivalent circuit of Fig. 19-7b already discussed. The current in this circuit is $I=(12.0 \mathrm{~V}) /(690 \Omega)=0.0174 \mathrm{~A}$, as we calculated in Example 19-4. (We keep an extra digit in $I$ to reduce rounding errors.) The positive side of the battery, point e in Fig. 19-12a, is at a high potential compared to point d at the negative side of the battery. That is, point e is like the top of a hill for a roller coaster. We follow the current around the circuit starting at any point. We choose to start at point d and follow a small positive test charge completely around this circuit. As we go, we note all changes in potential. When the test charge returns to point d , the potential will be the same as when we started (total change in potential around the circuit is zero). We plot the changes in potential around the circuit in Fig. 19-12b; point d is arbitrarily taken as zero.

As our positive test charge goes from point d , which is the negative or low potential side of the battery, to point e , which is the positive terminal (high potential side) of the battery, the potential increases by 12.0 V . (This is like the roller coaster being pulled up the first hill.) That is,
$$V_{\mathrm{ed}}=+12.0 \mathrm{~V}$$

When our test charge moves from point e to point a , there is no change in potential because there is no source of emf and negligible resistance in the connecting wires.

Next, as the charge passes through the $400-\Omega$ resistor to get to point $b$, there is a decrease in potential of $V=I R=(0.0174 \mathrm{~A})(400 \Omega)=7.0 \mathrm{~V}$. The positive test charge is flowing "downhill" since it is heading toward the negative terminal of the battery, as indicated in the graph of Fig. 19-12b. Because this is a decrease in potential, we use a negative sign:
$$V_{\mathrm{ba}}=V_{\mathrm{b}}-V_{\mathrm{a}}=-7.0 \mathrm{~V}$$

As the charge proceeds from b to c there is another potential decrease ( a "voltage drop") of $(0.0174 \mathrm{~A}) \times(290 \Omega)=5.0 \mathrm{~V}$, and this too is a decrease in potential:
$$V_{\mathrm{cb}}=-5.0 \mathrm{~V}$$

There is no change in potential as our test charge moves from c to d as we assume negligible resistance in the wires.

The sum of all the changes in potential around the circuit of Fig. 19-12 is
$$+12.0 \mathrm{~V}-7.0 \mathrm{~V}-5.0 \mathrm{~V}=0$$

Junction rule (conservation of charge)

Loop rule (conservation of energy)
(a)

FIGURE 19-12 Changes in potential around the circuit in (a) are plotted in (b).
(b)

PROBLEM SOLVING
Be consistent with signs when applying the loop rule

This is exactly what Kirchhoff's loop rule said it would be.

SECTION 19-3 Kirchhoff's Rules
533

---

<!-- Page 534 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 534t

sOLVING

Kirchhoff's Rules
1. Label the current in each separate branch of the given circuit with a different subscript, such as $I_{1}, I_{2}, I_{3}$ (see Fig. 19-11 or 19-13). Each current refers to a segment between two junctions. Choose the direction of each current, using an arrow. The direction can be chosen arbitrarily: if the current is actually in the opposite direction, it will come out with a minus sign in the solution.
2. Identify the unknowns. You will need as many independent equations as there are unknowns. You may write down more equations than this, but you will find that some of the equations will be redundant (that is, not be independent in the sense of providing new information). You may use $V=I R$ for each resistor, which sometimes will reduce the number of unknowns.
3. Apply Kirchhoff's junction rule at one or more junctions.
4. Apply Kirchhoff's loop rule for one or more loops: follow each loop in one direction only. Pay careful attention to subscripts, and to signs:
(a) For a resistor, apply Ohm's law; the potential difference is negative (a decrease) if your chosen loop direction is the same as the chosen current direction through that resistor. The potential difference is positive (an increase) if your chosen loop direction is opposite to the chosen current direction.
(b) For a battery, the potential difference is positive if your chosen loop direction is from the negative terminal toward the positive terminal; the potential difference is negative if the loop direction is from the positive terminal toward the negative terminal.
5. Solve the equations algebraically for the unknowns. Be careful with signs. At the end, check your answers by plugging them into the original equations, or even by using any additional loop or junction rule equations not used previously.

PROBLEM SOLVING
Choose current directions arbitrarily

EXAMPLE 19-8 Using Kirchhoff's rules. Calculate the currents $I_{1}, I_{2}$, and $I_{3}$ in the three branches of the circuit in Fig. 19-13 (which is the same as Fig. 19-11).

APPROACH and SOLUTION
1. Label the currents and their directions. Figure 19-13 uses the labels $I_{1}, I_{2}$, and $I_{3}$ for the current in the three separate branches. Since (positive) current tends to move away from the positive terminal of a battery, we choose $I_{2}$ and $I_{3}$ to have the directions shown in Fig. 19-13. The direction of $I_{1}$ is not obvious in advance, so we arbitrarily chose the direction indicated. If the current actually flows in the opposite direction, our answer will have a negative sign.
2. Identify the unknowns. We have three unknowns ( $I_{1}, I_{2}$, and $I_{3}$ ) and therefore we need three equations, which we get by applying Kirchhoff's junction and loop rules.
3. Junction rule: We apply Kirchhoff's junction rule to the currents at point a, where $I_{3}$ enters and $I_{2}$ and $I_{1}$ leave:
$$I_{3}=I_{1}+I_{2} .$$

This same equation holds at point d, so we get no new information by writing an equation for point d .

FIGURE 19-13 Currents can be calculated using Kirchhoff's rules. See Example 19-8.

534
CHAPTER 19 DC Circuits

---

<!-- Page 535 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:00 Page 535
4. Loop rule: We apply Kirchhoff's loop rule to two different closed loops. First we apply it to the upper loop ahdcba. We start (and end) at point a. From a to h we have a potential decrease $V_{\mathrm{ha}}=-\left(I_{1}\right)(30 \Omega)$. From h to d there is no change, but from d to c the potential increases by 45 V : that is, $V_{\mathrm{cd}}=+45 \mathrm{~V}$. From c to a the potential decreases through the two resistances by an amount $V_{\mathrm{ac}}=-\left(I_{3}\right)(40 \Omega+1 \Omega)=-(41 \Omega) I_{3}$. Thus we have $V_{\mathrm{ha}}+V_{\mathrm{cd}}+V_{\mathrm{ac}}=0$, or
$$-30 I_{1}+45-41 I_{3}=0$$
where we have omitted the units (volts and amps) so we can more easily see the algebra. For our second loop, we take the outer loop ahdefga. (We could have chosen the lower loop abcdefga instead.) Again we start at point a, and going to point h we have $V_{\mathrm{ha}}=-\left(I_{1}\right)(30 \Omega)$. Next, $V_{\mathrm{dh}}=0$. But when we take our positive test charge from d to e , it actually is going uphill, against the current-or at least against the assumed direction of the current, which is what counts in this calculation. Thus $V_{\mathrm{ed}}=+I_{2}(20 \Omega)$ has a positive sign. Similarly, $V_{\mathrm{fe}}=+I_{2}(1 \Omega)$. From f to g there is a decrease in potential of 80 V because we go from the high potential terminal of the battery to the low. Thus $V_{\mathrm{gf}}=-80 \mathrm{~V}$. Finally, $V_{\mathrm{ag}}=0$, and the sum of the potential changes around this loop is
$$-30 I_{1}+(20+1) I_{2}-80=0$$

Our major work is done. The rest is algebra.
5. Solve the equations. We have three equations-labeled (i), (ii), and (iii)and three unknowns. From Eq. (iii) we have
$$I_{2}=\frac{80+30 I_{1}}{21}=3.8+1.4 I_{1}$$

From Eq. (ii) we have
$$I_{3}=\frac{45-30 I_{1}}{41}=1.1-0.73 I_{1}$$

We substitute Eqs. (iv) and (v) into Eq. (i):
$$I_{1}=I_{3}-I_{2}=1.1-0.73 I_{1}-3.8-1.4 I_{1}$$

We solve for $I_{1}$, collecting terms:
$$\begin{aligned}
3.1 I_{1} & =-2.7 \\
I_{1} & =-0.87 \mathrm{~A} .
\end{aligned}$$

The negative sign indicates that the direction of $I_{1}$ is actually opposite to that initially assumed and shown in Fig. 19-13. The answer automatically comes out in amperes because our voltages and resistances were in volts and ohms. From Eq. (iv) we have
$$I_{2}=3.8+1.4 I_{1}=3.8+1.4(-0.87)=2.6 \mathrm{~A},$$
and from Eq. (v)
$$I_{3}=1.1-0.73 I_{1}=1.1-0.73(-0.87)=1.7 \mathrm{~A} .$$

This completes the solution.
NOTE The unknowns in different situations are not necessarily currents. It might be that the currents are given and we have to solve for unknown resistance or voltage. The variables are then different, but the technique is the same.

EXERCISE D Write the Kirchhoff equation for the lower loop abcdefga of Example 19-8 and show, assuming the currents calculated in this Example, that the potentials add to zero for this lower loop.

PROBLEM SOLVING
Be consistent with signs when applying the loop rule

PROBLEM SOLVING
$I_{1}$ is in the opposite direction from that assumed in Fig. 19-13

SECTION 19-3 Kirchhoff's Rules
535

---

<!-- Page 536 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 535

FIGURE 19-14 Batteries in series, (a) and (b), and in parallel (c).

FIGURE 19-15 Example 19-9, a jump start.

19-4 EMFs in Series and in Parallel; Charging a Battery
When two or more sources of emf, such as batteries, are arranged in series as in Fig. 19-14a, the total voltage is the algebraic sum of their respective voltages. On the other hand, when a $20-\mathrm{V}$ and a $12-\mathrm{V}$ battery are connected oppositely, as shown in Fig. $19-14 \mathrm{~b}$, the net voltage $V_{\mathrm{ca}}$ is 8 V (ignoring voltage drop across internal resistances). That is, a positive test charge moved from $a$ to $b$ gains in potential by 20 V , but when it passes from b to c it drops by 12 V . So the net change is $20 \mathrm{~V}-12 \mathrm{~V}=8 \mathrm{~V}$. You might think that connecting batteries in reverse like this would be wasteful. For most purposes that would be true. But such a reverse arrangement is precisely how a battery charger works. In Fig. 19-14b, the 20-V source is charging up the $12-\mathrm{V}$ battery. Because of its greater voltage, the $20-\mathrm{V}$ source is forcing charge back into the $12-\mathrm{V}$ battery: electrons are being forced into its negative terminal and removed from its positive terminal.

An automobile alternator keeps the car battery charged in the same way. A voltmeter placed across the terminals of a (12-V) car battery with the engine running fairly fast can tell you whether or not the alternator is charging the battery. If it is, the voltmeter reads 13 or 14 V . If the battery is not being charged, the voltage will be 12 V , or less if the battery is discharging. Car batteries can be recharged, but other batteries may not be rechargeable because the chemical reactions in many cannot be reversed. In such cases, the arrangement of Fig. 19-14b would simply waste energy.

Sources of emf can also be arranged in parallel, Fig. 19-14c, which-if the emfs are the same-can provide more energy when large currents are needed. Each of the cells in parallel has to produce only a fraction of the total current, so the energy loss due to internal resistance is less than for a single cell; and the batteries will go dead less quickly.

EXAMPLE 19-9 Jump starting a car. A good car battery is being used to jump start a car with a weak battery. The good battery has an emf of 12.5 V and internal resistance $0.020 \Omega$. Suppose the weak battery has an emf of 10.1 V and internal resistance $0.10 \Omega$. Each copper jumper cable is 3.0 m long and 0.50 cm in diameter, and can be attached as shown in Fig. 19-15. Assume the starter motor can be represented as a resistor $R_{\mathrm{s}}=0.15 \Omega$. Determine the current through the starter motor (a) if only the weak battery is connected to it, and (b) if the good battery is also connected, as shown in Fig. 19-15.
APPROACH We apply Kirchhoff's rules, but in (b) we will first need to determine the resistance of the jumper cables using their dimensions and the resistivity ( $\rho=1.68 \times 10^{-8} \Omega \cdot \mathrm{~m}$ for copper) as discussed in Section 18-4.
SOLUTION (a) The circuit with only the weak battery and no jumper cables is simple: an emf of 10.1 V connected to two resistances in series, $0.10 \Omega+0.15 \Omega= 0.25 \Omega$. Hence the current is $I=V / R=(10.1 \mathrm{~V}) /(0.25 \Omega)=40 \mathrm{~A}$.
(b) We need to find the resistance of the jumper cables that connect the good battery to the weak one. From Eq. 18-3, each has resistance
$$R_{\mathrm{J}}=\frac{\rho \ell}{A}=\frac{\left(1.68 \times 10^{-8} \Omega \cdot \mathrm{~m}\right)(3.0 \mathrm{~m})}{(\pi)\left(0.25 \times 10^{-2} \mathrm{~m}\right)^{2}}=0.0026 \Omega .$$

Kirchhoff's loop rule for the full outside loop gives
$$\begin{array}{l}
12.5 \mathrm{~V}-I_{1}\left(2 R_{\mathrm{J}}+r_{1}\right)-I_{3} R_{\mathrm{S}}=0 \\
12.5 \mathrm{~V}-I_{1}(0.025 \Omega)-I_{3}(0.15 \Omega)=0
\end{array}$$
since $\left(2 R_{\mathrm{J}}+r\right)=(0.0052 \Omega+0.020 \Omega)=0.025 \Omega$.

536
CHAPTER 19 DC Circuits

---

<!-- Page 537 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 537

The loop rule for the lower loop, including the weak battery and the starter, gives
$$10.1 \mathrm{~V}-I_{3}(0.15 \Omega)-I_{2}(0.10 \Omega)=0 .$$

The junction rule at point B gives
$$I_{1}+I_{2}=I_{3} .$$

We have three equations in three unknowns. From Eq. (iii),
$$I_{1}=I_{3}-I_{2}$$
and we substitute this into Eq. (i):
$$\begin{array}{l}
12.5 \mathrm{~V}-\left(I_{3}-I_{2}\right)(0.025 \Omega)-I_{3}(0.15 \Omega)=0, \\
12.5 \mathrm{~V}-I_{3}(0.175 \Omega)+I_{2}(0.025 \Omega)=0 .
\end{array}$$

Combining this last equation with Eq. (ii) gives
$$12.5 \mathrm{~V}-I_{3}(0.175 \Omega)+\left(\frac{10.1 \mathrm{~V}-I_{3}(0.15 \Omega)}{0.10 \Omega}\right)(0.025 \Omega)=0$$
or
$$I_{3}=\frac{12.5 \mathrm{~V}+2.5 \mathrm{~V}}{(0.175 \Omega+0.0375 \Omega)}=71 \mathrm{~A},$$
quite a bit better than in part (a).
The other currents are $I_{2}=-5 \mathrm{~A}$ and $I_{1}=76 \mathrm{~A}$. Note that $I_{2}=-5 \mathrm{~A}$ is in the opposite direction from what we assumed in Fig. 19-15. The terminal voltage of the weak 10.1-V battery when being charged is
$$V_{\mathrm{BA}}=10.1 \mathrm{~V}-(-5 \mathrm{~A})(0.10 \Omega)=10.6 \mathrm{~V} .$$

NOTE The circuit in Fig. 19-15, without the starter motor, is how a battery can be charged. The stronger battery pushes charge back into the weaker battery.

EXERCISE E If the jumper cables of Example 19-9 were mistakenly connected in reverse, the positive terminal of each battery would be connected to the negative terminal of the other battery (Fig. 19-16). What would be the current $I$ even before the starter motor is engaged (the switch S in Fig. 19-16 is open)? Why could this cause the batteries to explode?

Safety when Jump Starting
Before jump starting a car's weak battery, be sure both batteries are 12 V and check the polarity of both batteries. The following (cautious) procedure applies if the negative ( - ) terminal is ground (attached by a cable to the metal car frame and motor), and the "hot" terminal is positive ( + ) on both batteries, as is the case for most modern cars. The + terminal is usually marked by a red color, often a red cover. The safest procedure is to first connect the hot ( + ) terminal of the weak battery to the hot terminal of the good battery (using the cable with red clamps). Spread apart the handles of each clamp to squeeze the contact tightly. Then connect the black cable, first to the ground terminal of the good battery, and the other end to a clean exposed metal part (i.e., at ground) on the car with the weak battery. (This last connection should preferably be not too close to the battery, which in rare cases might leak $\mathrm{H}_{2}$ gas that could ignite at the spark that may accompany the final connection.) This is safer than connecting directly to the ground terminal. When you are ready to start the disabled car, it helps to have the good car running (to keep its battery fully charged). As soon as the disabled car starts, immediately detach the cables in the exact reverse order (ground cable first).

In the photo of Fig. 19-15, the above procedure is not being followed. Note the safety error: with ground terminals connected, if the red clamp ( +12 V ) touches a metal part (= ground), even if dropped by the person, a short circuit with damaging high electric current can occur (hundreds of amps).

FIGURE 19-16 Exercise E.

SECTION 19-4 EMFs in Series and in Parallel; Charging a Battery
537

---

<!-- Page 538 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 538

FIGURE 19-17 Capacitors in parallel: $C_{\text {eq }}=C_{1}+C_{2}+C_{3}$.

FIGURE 19-18 Capacitors in series:
$\frac{1}{C_{\mathrm{eq}}}=\frac{1}{C_{1}}+\frac{1}{C_{2}}+\frac{1}{C_{3}}$.

\section*{CAUTION}

Formula for capacitors in series resembles formula for resistors in parallel

19-5 Circuits Containing Capacitors in Series and in Parallel

Just as resistors can be placed in series or in parallel in a circuit, so can capacitors (Chapter 17). We first consider a parallel connection as shown in Fig. 19-17. If a battery supplies a potential difference $V$ to points a and b , this same potential difference $V=V_{\mathrm{ab}}$ exists across each of the capacitors. That is, since the lefthand plates of all the capacitors are connected by conductors, they all reach the same potential $V_{\mathrm{a}}$ when connected to the battery; and the right-hand plates each reach potential $V_{\mathrm{b}}$. Each capacitor plate acquires a charge given by $Q_{1}=C_{1} V$, $Q_{2}=C_{2} V$, and $Q_{3}=C_{3} V$. The total charge $Q$ that must leave the battery is then
$$Q=Q_{1}+Q_{2}+Q_{3}=C_{1} V+C_{2} V+C_{3} V .$$

Let us try to find a single equivalent capacitor that will hold the same charge $Q$ at the same voltage $V=V_{\mathrm{ab}}$. It will have a capacitance $C_{\mathrm{eq}}$ given by
$$Q=C_{\mathrm{eq}} V .$$

Combining the two previous equations, we have
$$C_{\mathrm{eq}} V=C_{1} V+C_{2} V+C_{3} V=\left(C_{1}+C_{2}+C_{3}\right) V$$
or
$$C_{\mathrm{eq}}=C_{1}+C_{2}+C_{3} .$$

The net effect of connecting capacitors in parallel is thus to increase the capacitance. Connecting capacitors in parallel is essentially increasing the area of the plates where charge can accumulate (see, for example, Eq. 17-8).

Capacitors can also be connected in series: that is, end to end as shown in Fig. 19-18. A charge $+Q$ flows from the battery to one plate of $C_{1}$, and $-Q$ flows to one plate of $C_{3}$. The regions A and B between the capacitors were originally neutral, so the net charge there must still be zero. The $+Q$ on the left plate of $C_{1}$ attracts a charge of $-Q$ on the opposite plate. Because region A must have a zero net charge, there is $+Q$ on the left plate of $C_{2}$. The same considerations apply to the other capacitors, so we see that the charge on each capacitor plate has the same magnitude $Q$. A single capacitor that could replace these three in series without affecting the circuit (that is, $Q$ and $V$ the same) would have a capacitance $C_{\text {eq }}$ where
$$Q=C_{\mathrm{eq}} V .$$

The total voltage $V$ across the three capacitors in series must equal the sum of the voltages across each capacitor:
$$V=V_{1}+V_{2}+V_{3} .$$

We also have for each capacitor $Q=C_{1} V_{1}, Q=C_{2} V_{2}$, and $Q=C_{3} V_{3}$, so we substitute for $V_{1}, V_{2}, V_{3}$, and $V$ into the last equation and get
$$\frac{Q}{C_{\mathrm{eq}}}=\frac{Q}{C_{1}}+\frac{Q}{C_{2}}+\frac{Q}{C_{3}}=Q\left(\frac{1}{C_{1}}+\frac{1}{C_{2}}+\frac{1}{C_{3}}\right)$$
or
$$\frac{1}{C_{\mathrm{eq}}}=\frac{1}{C_{1}}+\frac{1}{C_{2}}+\frac{1}{C_{3}} .$$

Notice that the equivalent capacitance $C_{\text {eq }}$ is smaller than the smallest contributing capacitance. Notice also that the forms of the equations for capacitors in series or in parallel are the reverse of their counterparts for resistance. That is, the formula for capacitors in series resembles the formula for resistors in parallel.

538
CHAPTER 19 DC Circuits

---

<!-- Page 539 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 538

EXAMPLE 19-10 Equivalent capacitance. Determine the capacitance of a single capacitor that will have the same effect as the combination shown in Fig. 19-19a. Take $C_{1}=C_{2}=C_{3}=C$.
APPROACH First we find the equivalent capacitance of $C_{2}$ and $C_{3}$ in parallel, and then consider that capacitance in series with $C_{1}$.
SOLUTION Capacitors $C_{2}$ and $C_{3}$ are connected in parallel, so they are equivalent to a single capacitor having capacitance
$$C_{23}=C_{2}+C_{3}=C+C=2 C .$$

This $C_{23}$ is in series with $C_{1}$, Fig. 19-19b, so the equivalent capacitance of the entire circuit, $C_{\text {eq }}$, is given by
$$\frac{1}{C_{\mathrm{eq}}}=\frac{1}{C_{1}}+\frac{1}{C_{23}}=\frac{1}{C}+\frac{1}{2 C}=\frac{3}{2 C} .$$

Hence the equivalent capacitance of the entire combination is $C_{\text {eq }}=\frac{2}{3} C$, and it is smaller than any of the contributing capacitances, $C_{1}=C_{2}=C_{3}=C$.

EXERCISE F Consider two identical capacitors $C_{1}=C_{2}=10 \mu \mathrm{~F}$. What are the smallest and largest capacitances that can be obtained by connecting these in series or parallel combinations? (a) $0.2 \mu \mathrm{~F}, 5 \mu \mathrm{~F}$; (b) $0.2 \mu \mathrm{~F}, 10 \mu \mathrm{~F}$; (c) $0.2 \mu \mathrm{~F}, 20 \mu \mathrm{~F}$; (d) $5 \mu \mathrm{~F}$, $10 \mu \mathrm{~F}$; (e) $5 \mu \mathrm{~F}, 20 \mu \mathrm{~F}$; (f) $10 \mu \mathrm{~F}, 20 \mu \mathrm{~F}$.

EXAMPLE 19-11 Charge and voltage on capacitors. Determine the charge on each capacitor in Fig. 19-19a of Example 19-10 and the voltage across each, assuming $C=3.0 \mu \mathrm{~F}$ and the battery voltage is $V=4.0 \mathrm{~V}$.
APPROACH We have to work "backward" through Example 19-10. That is, we find the charge $Q$ that leaves the battery, using the equivalent capacitance. Then we find the charge on each separate capacitor and the voltage across each. Each step uses Eq. 17-7, $Q=C V$.
SOLUTION The $4.0-\mathrm{V}$ battery behaves as if it is connected to a capacitance $C_{\text {eq }}=\frac{2}{3} C=\frac{2}{3}(3.0 \mu \mathrm{~F})=2.0 \mu \mathrm{~F}$. Therefore the charge $Q$ that leaves the battery, by Eq. 17-7, is
$$Q=C V=(2.0 \mu \mathrm{~F})(4.0 \mathrm{~V})=8.0 \mu \mathrm{C} .$$

From Fig. 19-19a, this charge arrives at the negative plate of $C_{1}$, so $Q_{1}=8.0 \mu \mathrm{C}$. The charge $Q$ that leaves the positive plate of the battery is split evenly between $C_{2}$ and $C_{3}$ (symmetry: $C_{2}=C_{3}$ ) and is $Q_{2}=Q_{3}=\frac{1}{2} Q=4.0 \mu \mathrm{C}$. Next, the voltages across $C_{2}$ and $C_{3}$ have to be the same. The voltage across each capacitor is obtained using $V=Q / C$. So
$$\begin{array}{l}
V_{1}=Q_{1} / C_{1}=(8.0 \mu \mathrm{C}) /(3.0 \mu \mathrm{~F})=2.7 \mathrm{~V} \\
V_{2}=Q_{2} / C_{2}=(4.0 \mu \mathrm{C}) /(3.0 \mu \mathrm{~F})=1.3 \mathrm{~V} \\
V_{3}=Q_{3} / C_{3}=(4.0 \mu \mathrm{C}) /(3.0 \mu \mathrm{~F})=1.3 \mathrm{~V} .
\end{array}$$

19-6 $\boldsymbol{R} \boldsymbol{C}$ Circuits-Resistor and Capacitor in Series
Capacitor Charging
Capacitors and resistors are often found together in a circuit. Such $\boldsymbol{R} \boldsymbol{C}$ circuits are common in everyday life. They are used to control the speed of a car's windshield wipers and the timing of traffic lights; they are used in camera flashes, in heart pacemakers, and in many other electronic devices. In $R C$ circuits, we are not so interested in the final "steady state" voltage and charge on the capacitor, but rather in how these variables change in time.
(a)
(b)

FIGURE 19-19
Examples 19-10 and 19-11.
PROBLEM SOLVING
Remember to take the reciprocal

SECTION 19-6 $R C$ Circuits-Resistor and Capacitor in Series
539

---

<!-- Page 540 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 540

↓ caution
Don't confuse e for exponential with e for electron charge

FIGURE 19-20 After the switch S closes in the $R C$ circuit shown in (a), the voltage $V_{\mathrm{C}}$ across the capacitor increases with time as shown in (b), and the current through the resistor decreases with time as shown in (c).

A simple $R C$ circuit is shown in Fig. 19-20a. When the switch S is closed, current immediately begins to flow through the circuit. Electrons will flow out from the negative terminal of the battery, through the resistor $R$, and accumulate on the upper plate of the capacitor. And electrons will flow into the positive terminal of the battery, leaving a positive charge on the other plate of the capacitor. As charge accumulates on the capacitor, the potential difference across it increases ( $V_{\mathrm{C}}=Q / C$ ), and the current is reduced until eventually the voltage across the capacitor equals the emf of the battery, $\mathscr{E}$. There is then no further current flow, and no potential difference across the resistor. The potential difference $V_{\mathrm{C}}$ across the capacitor, which is proportional to the charge on it ( $V_{\mathrm{C}}=Q / C$, Eq. 17-7), thus increases in time as shown in Fig. 19-20b. The shape of this curve is a type of exponential, and is given by the formula ${ }^{\dagger}$
$$V_{\mathrm{C}}=\mathscr{E}\left(1-e^{-t / R C}\right),$$
where we use the subscript C to remind us that $V_{\mathrm{C}}$ is the voltage across the capacitor and is given here as a function of time $t$. [The constant $e$, known as the base for natural logarithms, has the value $e=2.718 \cdots$. Do not confuse this $e$ with $e$ for the charge on the electron.]

We can write a similar formula for the charge $Q\left(=C V_{\mathrm{C}}\right)$ on the capacitor:
$$Q=Q_{0}\left(1-e^{-t / R C}\right),$$
where $Q_{0}$ represents the maximum charge.
The product of the resistance $R$ times the capacitance $C$, which appears in the exponent, is called the time constant $\tau$ of the circuit:
$$\tau=R C .$$

The time constant is a measure of how quickly the capacitor becomes charged. [The units of $R C$ are $\Omega \cdot \mathrm{F}=(\mathrm{V} / \mathrm{A})(\mathrm{C} / \mathrm{V})=\mathrm{C} /(\mathrm{C} / \mathrm{s})=\mathrm{s}$.] Specifically, it can be shown that the product $R C$ gives the time required for the capacitor's voltage (and charge) to reach $63 \%$ of the maximum. This can be checked ${ }^{\ddagger}$ using any calculator with an $e^{x}$ key: $e^{-1}=0.37$, so for $t=R C$, then $\left(1-e^{-t / R C}\right)=\left(1-e^{-1}\right)=(1-0.37)=0.63$. In a circuit, for example, where $R=200 \mathrm{k} \Omega$ and $C=3.0 \mu \mathrm{~F}$, the time constant is $\left(2.0 \times 10^{5} \Omega\right)\left(3.0 \times 10^{-6} \mathrm{~F}\right)=$ 0.60 s . If the resistance is much smaller, the time constant is much smaller and the capacitor becomes charged much more quickly. This makes sense, because a lower resistance will retard the flow of charge less. All circuits contain some resistance (if only in the connecting wires), so a capacitor can never be charged instantaneously when connected to a battery.

Finally, what is the voltage $V_{\mathrm{R}}$ across the resistor in Fig. 19-20a? The imposed battery voltage is $\mathscr{E}$, so
$$V_{\mathrm{R}}=\mathscr{E}-V_{\mathrm{C}}=\mathscr{E}\left(1-1+e^{-t / R C}\right)=\mathscr{E} e^{-t / R C} .$$

This is called an exponential decay. The current $I$ flowing in the circuit is that flowing through the resistor and is also an exponential decay:
$$I=\frac{V_{\mathrm{R}}}{R}=\frac{\mathscr{E}}{R} e^{-t / R C} .$$

When the switch of the circuit in Fig. 19-20a is closed, the current is largest at first because there is no charge on the capacitor to impede it. As charge builds on the capacitor, the current decreases in time. That is exactly what Eq. 19-7d and Fig. 19-20c tell us.
${ }^{\dagger}$ The derivation uses calculus.
${ }^{\ddagger}$ More simply, since $e=2.718 \cdots$, then $e^{-1}=1 / e=1 / 2.718=0.37$. Note that $e$ is the inverse operation to the natural logarithm $\ln : \ln (e)=1$, and $\ln \left(e^{x}\right)=x$.

540
CHAPTER 19 DC Circuits

---

<!-- Page 541 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 541]

EXAMPLE 19-12 $\boldsymbol{R} \boldsymbol{C}$ circuit, with emf. The capacitance in the circuit of Fig. 19-20a is $C=0.30 \mu \mathrm{~F}$, the total resistance is $R=20 \mathrm{k} \Omega$, and the battery emf is 12 V . Determine (a) the time constant, (b) the maximum charge the capacitor could acquire, (c) the time it takes for the charge to reach $99 \%$ of this value, and (d) the maximum current.
APPROACH We use Fig. 19-20 and Eqs. 19-7a, b, c, and d.
SOLUTION (a) The time constant is $R C=\left(2.0 \times 10^{4} \Omega\right)\left(3.0 \times 10^{-7} \mathrm{~F}\right)= 6.0 \times 10^{-3} \mathrm{~s}=6.0 \mathrm{~ms}$.
(b) The maximum charge would occur when no further current flows, so $Q_{0}=C^{\mathscr{C}}=\left(3.0 \times 10^{-7} \mathrm{~F}\right)(12 \mathrm{~V})=3.6 \mu \mathrm{C}$.
(c) In Eq. 19-7b, we set $Q=0.99 C^{\circ}$ :
$$0.99 C \mathscr{E}=C \mathscr{E}\left(1-e^{-t / R C}\right),$$
or
$$e^{-t / R C}=1-0.99=0.01 \text {. }$$

We take the natural logarithm of both sides (Appendix A-8), recalling that $\ln e^{x}=x$ :
$$\frac{t}{R C}=-\ln (0.01)=4.6$$
so
$$t=4.6 R C=(4.6)\left(6.0 \times 10^{-3} \mathrm{~s}\right)=28 \times 10^{-3} \mathrm{~s}$$
or 28 ms (less than $\frac{1}{30} \mathrm{~s}$ ).
(d) The current is a maximum at $t=0$ (the moment when the switch is closed) and there is no charge yet on the capacitor ( $Q=0$ ):
$$I_{\max }=\frac{\mathscr{C}}{R}=\frac{12 \mathrm{~V}}{2.0 \times 10^{4} \Omega}=600 \mu \mathrm{~A} .$$

Capacitor Discharging
The circuit just discussed involved the charging of a capacitor by a battery through a resistance. Now let us look at another situation: a capacitor is already charged to a voltage $V_{0}$ and charge $Q_{0}$, and it is then allowed to discharge through a resistance $R$ as shown in Fig. 19-21a. In this case there is no battery. When the switch S is closed, charge begins to flow through resistor $R$ from one side of the capacitor toward the other side, until the capacitor is fully discharged. The voltage across the capacitor decreases, as shown in Fig. 19-21b. This "exponential decay" curve is given by
$$V_{\mathrm{C}}=V_{0} e^{-t / R C},$$
where $V_{0}$ is the initial voltage across the capacitor. The voltage falls $63 \%$ of the way to zero (to $0.37 V_{0}$ ) in a time $\tau=R C$. Because the charge $Q$ on the capacitor is $Q=C V$ (and $Q_{0}=C V_{0}$ ), we can write
$$Q=Q_{0} e^{-t / R C}$$
for a discharging capacitor, where $Q_{0}$ is the initial charge.
The voltage across the resistor will have the same magnitude as that across the capacitor at any instant, but the opposite sign, because there is zero applied emf: $V_{\mathrm{C}}+V_{\mathrm{R}}=0$ so $V_{\mathrm{R}}=-V_{\mathrm{C}}=-V_{0} e^{-t / R C}$. A graph of $V_{\mathrm{R}}$ vs. time would just be Fig. 19-21b upside down. The current $I=V_{\mathrm{R}} / R=-\left(V_{0} / R\right) e^{-t / R C}=-I_{0} e^{-t / R C}$. The current has its greatest magnitude at $t=0$ and decreases exponentially in time. (The current has a minus sign because in Fig. 19-21a it flows in the opposite direction as compared to the current in Fig. 19-20a.)

FIGURE 19-21 For the $R C$ circuit shown in (a), the voltage $V_{\mathrm{C}}$ across the capacitor decreases with time $t$, as shown in (b), after the switch S is closed at $t=0$. The charge on the capacitor follows the same curve since $Q \propto V_{\mathrm{C}}$.

(a)

(b)

SECTION 19-6 $R C$ Circuits-Resistor and Capacitor in Series
541

---

<!-- Page 542 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 542

EXAMPLE 19-13 A discharging $\boldsymbol{R} \boldsymbol{C}$ circuit. If a charged capacitor, $C=35 \mu \mathrm{~F}$, is connected to a resistance $R=120 \Omega$ as in Fig. 19-21a, how much time will elapse until the voltage falls to $10 \%$ of its original (maximum) value?
APPROACH The voltage across the capacitor decreases according to $V_{\mathrm{C}}=V_{0} e^{-t / R C}$. We set $V_{\mathrm{C}}=0.10 V_{0}\left(10 \%\right.$ of $\left.V_{0}\right)$, but first we need to calculate $\tau=R C$.
SOLUTION The time constant for this circuit is given by
$$\tau=R C=(120 \Omega)\left(35 \times 10^{-6} \mathrm{~F}\right)=4.2 \times 10^{-3} \mathrm{~s} .$$

After a time $t$ the voltage across the capacitor will be
$$V_{\mathrm{C}}=V_{0} e^{-t / R C} .$$

We want to know the time $t$ for which $V_{\mathrm{C}}=0.10 V_{0}$. We substitute into the above equation
$$0.10 V_{0}=V_{0} e^{-t / R C}$$
so
$$e^{-t / R C}=0.10 .$$

The inverse operation to the exponential $e$ is the natural $\log$, ln. Thus
$$\ln \left(e^{-t / R C}\right)=-\frac{t}{R C}=\ln 0.10=-2.3 .$$

Solving for $t$, we find the elapsed time is
$$t=2.3(R C)=(2.3)\left(4.2 \times 10^{-3} \mathrm{~s}\right)=9.7 \times 10^{-3} \mathrm{~s}=9.7 \mathrm{~ms} .$$

NOTE We can find the time for any specified voltage across a capacitor by using $t=R C \ln \left(V_{0} / V_{\mathrm{C}}\right)$.

FIGURE 19-22 Example 19-14.

PHYSICS APPLIED
Sawtooth voltage

PHYSICS APPLIED
Blinking flashers

FIGURE 19-23 (a) An $R C$ circuit, coupled with a gas-filled tube as a switch, can produce (b) a repeating "sawtooth" voltage.

542
CHAPTER 19

---

<!-- Page 543 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 543 D

The intermittent windshield wipers of a car can also use an $R C$ circuit. The $R C$ time constant, which can be changed using a multi-positioned switch for different values of $R$ with fixed $C$, determines the rate at which the wipers come on.
EXERCISE G A typical turn signal flashes perhaps twice per second, so its time constant is on the order of 0.5 s . Estimate the resistance in the circuit, assuming a moderate capacitor of $C=1 \mu \mathrm{~F}$.

An important medical use of an $R C$ circuit is the electronic heart pacemaker, which can make a stopped heart start beating again by applying an electric stimulus through electrodes attached to the chest. The stimulus can be repeated at the normal heartbeat rate if necessary. The heart itself contains pacemaker cells, which send out tiny electric pulses at a rate of 60 to 80 per minute. These signals induce the start of each heartbeat. In some forms of heart disease, the natural pacemaker fails to function properly, and the heart loses its beat. Such patients use electronic pacemakers which produce a regular voltage pulse that starts and controls the frequency of the heartbeat. The electrodes are implanted in or near the heart (Fig. 19-24), and the circuit contains a capacitor and a resistor. The charge on the capacitor increases to a certain point and then discharges a pulse to the heart. Then it starts charging again. The pulsing rate depends on the time constant $R C$.

19-7 Electric Hazards
Excess electric current can overheat wires in buildings and cause fires, as discussed in Section 18-6. Electric current can also damage the human body or even be fatal. Electric current through the human body can cause damage in two ways: (1) heating tissue and causing burns; (2) stimulating nerves and muscles, and we feel a"shock." The severity of a shock depends on the magnitude of the current, how long it acts, and through what part of the body it passes. A current passing through vital organs such as the heart or brain is especially damaging.

A current of about 1 mA or more can be felt and may cause pain. Currents above 10 mA cause severe contraction of the muscles, and a person may not be able to let go of the source of the current (say, a faulty appliance or wire). Death from paralysis of the respiratory system can occur. Artificial respiration can sometimes revive a victim. If a current above about 80 to 100 mA passes across the torso, so that a portion passes through the heart for more than a second or two, the heart muscles will begin to contract irregularly and blood will not be properly pumped. This condition is called ventricular fibrillation. If it lasts for long, death results. Strangely enough, if the current is much larger, on the order of 1 A, death by heart failure may be less likely, ${ }^{\dagger}$ but such currents can cause serious burns if concentrated through a small area of the body.

It is current that harms, but it is voltage that drives the current. The seriousness of an electric shock depends on the current and thus on the applied voltage and the effective resistance of the body. Living tissue has low resistance because the fluid of cells contains ions that can conduct quite well. However, the outer layer of skin, when dry, offers high resistance and is thus protective. The effective resistance between two points on opposite sides of the body when the skin is dry is on the order of $10^{4}$ to $10^{6} \Omega$. But when the skin is wet, the resistance may be $10^{3} \Omega$ or less. A person who is barefoot or wearing thin-soled shoes will be in good contact with the ground, and touching a 120-V line with a wet hand can result in a current
$$I=\frac{120 \mathrm{~V}}{1000 \Omega}=120 \mathrm{~mA}$$

As we saw, this could be lethal.
${ }^{\dagger}$ Larger currents apparently bring the entire heart to a standstill. Upon release of the current, the heart returns to its normal rhythm. This may not happen when fibrillation occurs because, once started, it can be hard to stop. Fibrillation may also occur as a result of a heart attack or during heart surgery. A device known as a defibrillator (described in Section 17-9) can apply a brief high current to the heart, causing complete heart stoppage which is often followed by resumption of normal beating.
PHYSICS APPLIED
Windshield wipers on "intermittent"

> PHYSICS APPLIED
> Heart pacemaker

FIGURE 19-24 Electronic batterypowered pacemaker can be seen on the rib cage in this X-ray (color added).
PHYSICS APPLIED
Dangers of electricity

SECTION 19-7 Electric Hazards
543

---

<!-- Page 544 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 544t

FIGURE 19-25 You can receive a shock when the circuit is completed.

Keep one hand in your pocket when other touches electricity

PHYSICS APPLIED
Grounding and shocks

You can get a shock by becoming part of a complete circuit. Figure 19-25 shows two ways the circuit might be completed when you accidentally touch a "hot" electric wire-"hot" meaning a high potential relative to ground such as 120 V (normal U.S. household voltage) or 240 V (many other countries). The other wire of building wiring is connected to ground-either by a wire connected to a buried conductor, or via a metal water pipe into the ground. The current in Fig. 19-25a passes from the high-voltage wire through you to ground through your bare feet, and back along the ground (a fair conductor) to the ground terminal of the source. If you stand on a good insulator-thick rubber-soled shoes or a dry wood floor-there will be much more resistance in the circuit and much less current through you. If you stand with bare feet on the ground, or in a bathtub, there is lethal danger because the resistance is much less and the current greater. In a bathtub (or swimming pool), not only are you wet, which reduces your resistance, but the water is in contact with the drain pipe (typically metal) that leads to the ground. It is strongly recommended that you not touch anything electrical when wet or in bare feet. The use of non-metal pipes would be protective.

In Fig. 19-25b, a person touches a faulty "hot" wire with one hand, and the other hand touches a sink faucet (connected to ground via the pipe or even by water in a non-metal pipe). The current is particularly dangerous because it passes across the chest, through the heart and lungs. A useful rule: if one hand is touching something electrical, keep your other hand in your back pocket (don't use it!), and wear thick rubber-soled shoes. Also remove metal jewelry, especially rings (your finger is usually moist under a ring).

You can come into contact with a hot wire by touching a bare wire whose insulation has worn off, or from a bare wire inside an appliance when you're tinkering with it. (Always unplug an electrical device before investigating its insides!) ${ }^{\dagger}$ Also, a wire inside a device may break or lose its insulation and come in contact with the case. If the case is metal, it will conduct electricity. A person could then suffer a severe shock merely by touching the case, as shown in Fig. 19-26b. To prevent

FIGURE 19-26 (a) An electric oven operating normally with a 2-prong plug. (b) A short to a metal case which is ungrounded, causing a shock. (c) A short to the case which is grounded by a 3-prong plug; almost no current goes through the person.
an accident, metal cases are supposed to be connected directly to ground by a separate ground wire. Then if a "hot" wire touches the grounded case, a short circuit to ground immediately occurs internally, as shown in Fig. 19-26c, and most of the current passes through the low-resistance ground wire rather than through the person. Furthermore, the high current should open a fuse or circuit breaker. Grounding a metal case is done by a separate ground wire connected to the third (round) prong of a 3-prong plug. Never cut off the third prong of a plug-it could save your life. A three-prong plug, and an adapter, are shown in Figs. 19-27a and b.
${ }^{\dagger}$ Even then you can get a bad shock from a capacitor that hasn't been discharged until you touch it.

FIGURE 19-27 (a) A 3-prong plug, and (b) an adapter (white) for oldfashioned 2-prong outlets-be sure to screw down the ground tab (green color in photo).

544
CHAPTER 19 DC Circuits

(b)

---

<!-- Page 545 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 545

Safe Wiring
Why is a third wire needed? The 120 V is carried by the other two wires-one hot ( 120 V ac), the other neutral, which is itself grounded. The third "dedicated" ground wire with the round prong may seem redundant. But it is protection for two reasons: (1) It protects against internal wiring that may have been done incorrectly or is faulty as discussed above, Fig. 19-26. (2) The neutral wire carries the full normal current ("return" current from the hot 120 V ) and it does have resistance-so there can be a voltage drop along the neutral wire, normally small; but if connections are poor or corroded, or the plug is loose, the resistance could be large enough that you might feel that voltage if you touched the neutral wire some distance from its grounding point.

Some electrical devices come with only two wires, and the plug's two prongs are of different widths; the plug can be inserted only one way into the outlet so that the intended neutral (wider prong) in the device is connected to neutral in the wiring (Fig. 19-28). For example, the screw threads of a lightbulb are meant to be connected to neutral (and the base contact to hot), to avoid shocks when changing a bulb in a possibly protruding socket. Devices with 2-prong plugs do not have their cases grounded; they are supposed to have double electric insulation (or have a nonmetal case). Take extra care anyway.

The insulation on a wire may be color coded. Hand-held meters (Section 19-8) may have red (hot) and black (ground) lead wires. But in a U.S. house, the hot wire is often black (though it may be red), whereas white is neutral and green (or bare) is the dedicated ground, Fig. 19-29. But beware: these color codes cannot always be trusted.
[In the U.S., three wires normally enter a house: two hot wires at 120 V each (which add together to 240 V for appliances or devices that run on 240 V ) plus the grounded neutral (carrying return current for the two hot wires). See Fig. 19-29. The "dedicated" ground wire (non-current carrying) is a fourth wire that does not come from the electric company but enters the house from a nearby heavy stake in the ground or a buried metal pipe. The two hot wires can feed separate $120-\mathrm{V}$ circuits in the house, so each $120-\mathrm{V}$ circuit inside the house has only three wires, including the dedicated ground.]

Normal circuit breakers (Sections 18-6 and 20-7) protect equipment and buildings from overload and fires. They protect humans only in some circumstances, such as the very high currents that result from a short, if they respond quickly enough. Ground fault circuit interrupters (GFCI or GFI), described in Section 21-9, are designed to protect people from the much lower currents ( 10 mA to 100 mA ) that are lethal but would not throw a 15-A circuit breaker or blow a 20-A fuse.

Another danger is leakage current, by which we mean a current along an unintended path. Leakage currents are often "capacitively coupled." For example, a wire in a lamp forms a capacitor with the metal case; charges moving in one conductor attract or repel charge in the other, so there is a current. Typical electrical codes limit leakage currents to 1 mA for any device, which is usually harmless. It could be dangerous, however, to a hospital patient with implanted electrodes, due to the absence of the protective skin layer and because the current can pass directly through the heart. Although 100 mA may be needed to cause heart fibrillation when entering through the hands and spreading out through the body (very little of it actually passing through the heart), but as little as 0.02 mA can cause fibrillation when passing directly to the heart. Thus, a "wired" patient is in considerable danger from leakage current even from as simple an act as touching a lamp.

Finally, don't touch a downed power line (lethal!) or even get near it. A hot power line is at thousands of volts. A huge current can flow along the ground from the point where the high-voltage wire touches the ground. This current is great enough that the voltage between your two feet could be large and dangerous. Tip: stand on one foot, or run so only one foot touches the ground at a time.

CAUTION
Necessity of third (ground) wire

FIGURE 19-28 A polarized
2-prong plug.

↑ CAUTION
Black wire may be either ground or hot. Beware!

FIGURE 19-29 Four wires entering a typical house. The color codes for wires are not always as shown here-be careful!

SECTION 19-7 Electric Hazards
545

---

<!-- Page 546 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 545

FIGURE 19-30 (a) An analog multimeter. (b) An electronic digital meter measuring voltage at a circuit breaker.

PHYSICS APPLIED
Ammeters use shunt resistor in parallel

FIGURE 19-31 An ammeter is a galvanometer in parallel with a (shunt) resistor with low resistance, $R_{\text {sh }}$.

19-8 Ammeters and Voltmeters-Measurement Affects the Quantity Being Measured

Measurement is a fundamental part of physics, and is not as simple as you might think. Measuring instruments can not be taken for granted; their results are not perfect and often need to be interpreted. As an illustration of measurement "theory" we examine here how electrical quantities are measured using meters. We also examine how meters affect the quantity they attempt to measure.

An ammeter measures current, and a voltmeter measures potential difference or voltage. Each can be either: (1) an analog meter, which displays numerical values by the position of a pointer that can move across a scale (Fig. 19-30a); or (2) a digital meter, which displays the numerical value in numbers (Fig. 19-30b). We now examine how analog meters work.

An analog ammeter or voltmeter, in which the reading is by a pointer on a scale (Fig. 19-30a), uses a galvanometer. A galvanometer works on the principle of the force between a magnetic field and a current-carrying coil of wire; it is straightforward to understand and will be discussed in Chapter 20. For now, we only need to know that the deflection of the needle of a galvanometer is proportional to the current flowing through it. The full-scale current sensitivity of a galvanometer, $I_{\mathrm{m}}$, is the electric current needed to make the needle deflect full scale, typically about $50 \mu \mathrm{~A}$.

A galvanometer whose sensitivity $I_{\mathrm{m}}$ is $50 \mu \mathrm{~A}$ can measure currents from about $1 \mu \mathrm{~A}$ (currents smaller than this would be hard to read on the scale) up to $50 \mu \mathrm{~A}$. To measure larger currents, a resistor is placed in parallel with the galvanometer. An analog ammeter, represented by the symbol • $\oplus \cdot$, consists of a galvanometer ( ⋅ - G-) in parallel with a resistor called the shunt resistor, as shown in Fig. 19-31. ("Shunt" is a synonym for "in parallel.") The shunt resistance is $R_{\mathrm{sh}}$, and the resistance of the galvanometer coil is $r$. The value of $R_{\mathrm{sh}}$ is chosen according to the full-scale deflection desired; $R_{\mathrm{sh}}$ is normally very small-giving an ammeter a very small net resistance-so most of the current passes through $R_{\text {sh }}$ and very little ( $\lesssim 50 \mu \mathrm{~A}$ ) passes through the galvanometer to deflect the needle.

EXAMPLE 19-15 Ammeter design. Design an ammeter to read 1.0 A at full scale using a galvanometer with a full-scale sensitivity of $50 \mu \mathrm{~A}$ and a resistance $r=30 \Omega$. Check if the scale is linear.
APPROACH Only $50 \mu \mathrm{~A}\left(=I_{\mathrm{G}}=0.000050 \mathrm{~A}\right)$ of the $1.0-\mathrm{A}$ current passes through the galvanometer to give full-scale deflection. The rest of the current ( $I_{R}=0.999950 \mathrm{~A}$ ) passes through the small shunt resistor, $R_{\mathrm{sh}}$, Fig. 19-31. The potential difference across the galvanometer equals that across the shunt resistor (they are in parallel). We apply Ohm's law to find $R_{\text {sh }}$.
SOLUTION Because $I=I_{\mathrm{G}}+I_{R}$, when $I=1.0 \mathrm{~A}$ flows into the meter, we want $I_{R}$ through the shunt resistor to be $I_{R}=0.999950 \mathrm{~A}$. The potential difference across the shunt is the same as across the galvanometer, so
$$I_{R} R_{\mathrm{sh}}=I_{\mathrm{G}} r .$$

Then
$$R_{\mathrm{sh}}=\frac{I_{\mathrm{G}} r}{I_{R}}=\frac{\left(5.0 \times 10^{-5} \mathrm{~A}\right)(30 \Omega)}{(0.999950 \mathrm{~A})}=1.5 \times 10^{-3} \Omega,$$
or $0.0015 \Omega$. The shunt resistor must thus have a very low resistance and most of the current passes through it.

Because $I_{\mathrm{G}}=I_{R}\left(R_{\mathrm{sh}} / r\right)$ and ( $R_{\mathrm{sh}} / r$ ) is constant, we see that the scale is linear (needle deflection is proportional to $I_{\mathrm{G}}$ ). If the current $I \approx I_{R}$ into the meter is half of full scale, 0.50 A , the current to the galvanometer will be $I_{\mathrm{G}}=I_{R}\left(R_{\mathrm{sh}} / r\right)=(0.50 \mathrm{~A})\left(1.5 \times 10^{-3} \Omega\right) /(30 \Omega)=25 \mu \mathrm{~A}$, which would make the needle deflect halfway, as it should.

An analog voltmeter ( ⋅ (V) ⋅ ) consists of a galvanometer and a resistor $R_{\text {ser }}$ connected in series, Fig. 19-32. $R_{\text {ser }}$ is usually large, giving a voltmeter a high internal resistance.

546

PHYSICS APPLIED Voltmeters use series resistor

CHAPTER 19 DC Circuits

---

<!-- Page 547 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 547

EXAMPLE 19-16 Voltmeter design. Using a galvanometer with internal resistance $r=30 \Omega$ and full-scale current sensitivity of $50 \mu \mathrm{~A}$, design a voltmeter that reads from 0 to 15 V . Is the scale linear?
APPROACH When a potential difference of 15 V exists across the terminals of our voltmeter, we want $50 \mu \mathrm{~A}$ to be passing through it so as to give a full-scale deflection.
SOLUTION From Ohm's law, $V=I R$, we have (Fig. 19-32)
$$15 \mathrm{~V}=(50 \mu \mathrm{~A})\left(r+R_{\text {ser }}\right),$$
so
$$R_{\text {ser }}=(15 \mathrm{~V}) /\left(5.0 \times 10^{-5} \mathrm{~A}\right)-r=300 \mathrm{k} \Omega-30 \Omega \approx 300 \mathrm{k} \Omega .$$

Notice that $r=30 \Omega$ is so small compared to the value of $R_{\text {ser }}$ that it doesn't influence the calculation significantly. The scale will again be linear: if the voltage to be measured is 6.0 V , the current passing through the voltmeter will be $(6.0 \mathrm{~V}) /\left(3.0 \times 10^{5} \Omega\right)=2.0 \times 10^{-5} \mathrm{~A}$, or $20 \mu \mathrm{~A}$. This will produce two-fifths of full-scale deflection, as required $(6.0 \mathrm{~V} / 15.0 \mathrm{~V}=2 / 5)$.

How to Connect Meters
Suppose you wish to determine the current $I$ in the circuit shown in Fig. 19-33a, and the voltage $V$ across the resistor $R_{1}$. How exactly are ammeters and voltmeters connected to the circuit being measured?

Because an ammeter is used to measure the current flowing in the circuit, it must be inserted directly into the circuit, in series with the other elements, as shown in Fig. 19-33b. The smaller its internal resistance, the less it affects the circuit.

A voltmeter is connected "externally," in parallel with the circuit element across which the voltage is to be measured. It measures the potential difference between two points. Its two wire leads (connecting wires) are connected to the two points, as shown in Fig. 19-33c, where the voltage across $R_{1}$ is being measured. The larger its internal resistance ( $R_{\text {ser }}+r$, Fig. 19-32), the less it affects the circuit being measured.

Effects of Meter Resistance
It is important to know the sensitivity of a meter, for in many cases the resistance of the meter can seriously affect your results. Consider the following Example.
EXAMPLE 19-17 Voltage reading vs. true voltage. An electronic circuit has two $15-\mathrm{k} \Omega$ resistors, $R_{1}$ and $R_{2}$, connected in series, Fig. 19-34a. The battery voltage is 8.0 V and it has negligible internal resistance. A voltmeter has resistance of $50 \mathrm{k} \Omega$ on the $5.0-\mathrm{V}$ scale. What voltage does the meter read when connected across $R_{1}$, Fig. 19-34b, and what error is caused by the meter's finite resistance?
APPROACH The meter acts as a resistor in parallel with $R_{1}$. We use parallel and series resistor analyses and Ohm's law to find currents and voltages.
SOLUTION The voltmeter resistance of $50,000 \Omega$ is in parallel with $R_{1}=15 \mathrm{k} \Omega$, Fig. 19-34b. The net resistance $R_{\text {eq }}$ of these two is
$$\frac{1}{R_{\mathrm{eq}}}=\frac{1}{50 \mathrm{k} \Omega}+\frac{1}{15 \mathrm{k} \Omega}=\frac{13}{150 \mathrm{k} \Omega} ;$$
so $R_{\text {eq }}=11.5 \mathrm{k} \Omega$. This $R_{\text {eq }}=11.5 \mathrm{k} \Omega$ is in series with $R_{2}=15 \mathrm{k} \Omega$, so the total resistance is now $26.5 \mathrm{k} \Omega$ (not the original $30 \mathrm{k} \Omega$ ). Hence the current from the battery is
$$I=\frac{8.0 \mathrm{~V}}{26.5 \mathrm{k} \Omega}=3.0 \times 10^{-4} \mathrm{~A}=0.30 \mathrm{~mA} .$$

Then the voltage drop across $R_{1}$, which is the same as that across the voltmeter, is $\left(3.0 \times 10^{-4} \mathrm{~A}\right)\left(11.5 \times 10^{3} \Omega\right)=3.5 \mathrm{~V}$. [The voltage drop across $R_{2}$ is $\left(3.0 \times 10^{-4} \mathrm{~A}\right)\left(15 \times 10^{3} \Omega\right)=4.5 \mathrm{~V}$, for a total of 8.0 V .] If we assume the meter is accurate, it reads 3.5 V . In the original circuit, without the meter, $R_{1}=R_{2}$ so the voltage across $R_{1}$ is half that of the battery, or 4.0 V . Thus the voltmeter, because of its internal resistance, gives a low reading. It is off by 0.5 V , or more than $10 \%$.
NOTE Often the sensitivity of a voltmeter is specified on its face as, for example, $10,000 \Omega / \mathrm{V}$. Then on a $5.0-\mathrm{V}$ scale, the voltmeter would have a resistance given by $(5.0 \mathrm{~V})(10,000 \Omega / \mathrm{V})=50,000 \Omega$. The meter's resistance depends on the scale used.

FIGURE 19-32 A voltmeter is a galvanometer in series with a resistor with high resistance, $R_{\text {ser }}$.

FIGURE 19-33 Measuring current and voltage.

(b)

(c)

Correcting for meter resistance

FIGURE 19-34 Example 19-17.

(a)

(b)

SECTION 19-8 547

---

<!-- Page 548 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 548

↑ CAUTION
Measurements affect the quantity being measured

Example 19-17 illustrates how seriously a meter can affect a circuit and give a misleading reading. If the resistance of a voltmeter is much higher than the resistance of the circuit, however, it will have little effect and its readings can be more accurate, at least to the manufactured precision of the meter, which for analog meters is typically $3 \%$ to $4 \%$ of full-scale deflection. Even an ammeter can interfere with a circuit, but the effect is minimal if its resistance is much less than that of the circuit as a whole. For both voltmeters and ammeters, the more sensitive the galvanometer, the less effect it will have on the circuit. [A 50,000-Ω/V meter is far better than a $1000-\Omega / V$ meter.]

Whenever we make a measurement on a circuit, to some degree we affect that circuit (Example 19-17). This is true for other types of measurement as well: when we make a measurement on a system, we affect that system in some way. On a temperature measurement, for example, the thermometer can exchange heat with the system, thus altering the temperature it is measuring. It is important to be able to make needed corrections, as we saw in Example 19-17.

Other Meters
The meters described above are for direct current. A dc meter can be modified to measure ac (alternating current, Section 18-7) with the addition of diodes (Chapter 29), which allow current to flow in one direction only. An ac meter can be calibrated to read rms or peak values.

Voltmeters and ammeters can have several series or shunt resistors to offer a choice of range. Multimeters can measure voltage, current, and resistance. Sometimes a multimeter is called a VOM (Volt-Ohm-Meter or Volt-Ohm-Milliammeter).

An ohmmeter measures resistance, and must contain a battery of known voltage connected in series to a resistor ( $R_{\text {ser }}$ ) and to an ammeter which contains a shunt $R_{\mathrm{sh}}$ (Fig. 19-35). The resistor whose resistance is to be measured completes the circuit, and must not be connected in a circuit containing a voltage source. The needle deflection of the meter is inversely proportional to the resistance. The scale calibration depends on the value of its series resistor, which is changeable in a multimeter. Because an ohmmeter sends a current through the device whose resistance is to be measured, it should not be used on very delicate devices that could be damaged by the current.

Digital Meters
Digital meters (see Fig. 19-30b) are used in the same way as analog meters: they are inserted directly into the circuit, in series, to measure current (Fig. 19-33b), and connected "outside," in parallel with the circuit, to measure voltage (Fig. 19-33c).

The internal construction of digital meters is very different from analog meters. First, digital meters do not use a galvanometer, but rather semiconductor devices (Chapter 29). The electronic circuitry and digital readout are more sensitive than a galvanometer, and have less effect on the circuit to be measured. When we measure dc voltages, a digital meter's resistance is very high, commonly on the order of $10 \mathrm{M} \Omega$ to $100 \mathrm{M} \Omega\left(10^{7}-10^{8} \Omega\right)$, and doesn't change significantly when different voltage scales are selected. A $100-\mathrm{M} \Omega$ digital meter draws very little current when connected across even a $1-\mathrm{M} \Omega$ resistance.

The precision of digital meters is exceptional, often one part in $10^{4}(=0.01 \%)$ or better. This precision is not the same as accuracy, however. A precise meter of internal resistance $10^{8} \Omega$ will not give accurate results if used to measure a voltage across a $10^{8}-\Omega$ resistor-in which case it is necessary to do a calculation like that in Example 19-17.

548
CHAPTER 19 DC Circuits

---

<!-- Page 549 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 549
Summary

A device that transforms another type of energy into electrical energy is called a source of emf. A battery behaves like a source of emf in series with an internal resistance. The emf is the potential difference determined by the chemical reactions in the battery and equals the terminal voltage when no current is drawn. When a current is drawn, the voltage at the battery's terminals is less than its emf by an amount equal to the potential decrease Ir across the internal resistance.

When resistances are connected in series (end to end in a single linear path), the equivalent resistance is the sum of the individual resistances:
$$R_{\mathrm{eq}}=R_{1}+R_{2}+\cdots .$$

In a series combination, $R_{\text {eq }}$ is greater than any component resistance.

When resistors are connected in parallel, it is the reciprocals that add up:
$$\frac{1}{R_{\mathrm{eq}}}=\frac{1}{R_{1}}+\frac{1}{R_{2}}+\cdots$$

In a parallel connection, the net resistance is less than any of the individual resistances.

Kirchhoff's rules are useful in determining the currents and voltages in circuits. Kirchhoff's junction rule is based on conservation of electric charge and states that the sum of all currents entering any junction equals the sum of all currents leaving that junction. The second, or loop rule, is based on conservation of energy and states that the algebraic sum of the changes in potential around any closed path of the circuit must be zero.

When capacitors are connected in parallel, the equivalent capacitance is the sum of the individual capacitances:
$$C_{\mathrm{eq}}=C_{1}+C_{2}+\cdots$$

When capacitors are connected in series, it is the reciprocals that add up:
$$\frac{1}{C_{\mathrm{eq}}}=\frac{1}{C_{1}}+\frac{1}{C_{2}}+\cdots$$

When an $\boldsymbol{R} \boldsymbol{C}$ circuit containing a resistance $R$ in series with a capacitance $C$ is connected to a dc source of emf, the voltage across the capacitor rises gradually in time characterized by an exponential of the form ( $1-e^{-t / R C}$ ), where the time constant
$$\tau=R C$$
is the time it takes for the voltage to reach $63 \%$ of its maximum value.

A capacitor discharging through a resistor is characterized by the same time constant: in a time $\tau=R C$, the voltage across the capacitor drops to $37 \%$ of its initial value. The charge on the capacitor, and the voltage across it, decrease as $e^{-t / R C}$.

Electric shocks are caused by current passing through the body. To avoid shocks, the body must not become part of a complete circuit by allowing different parts of the body to touch objects at different potentials. Commonly, shocks are caused by one part of the body touching ground ( $V=0$ ) and another part touching a nonzero electric potential.

An ammeter measures current. An analog ammeter consists of a galvanometer and a parallel shunt resistor that carries most of the current. An analog voltmeter consists of a galvanometer and a series resistor. An ammeter is inserted into the circuit whose current is to be measured. A voltmeter is external, being connected in parallel to the element whose voltage is to be measured. Digital meters have greater internal resistance and affect the circuit to be measured less than do analog meters.

Questions
1. Explain why birds can sit on power lines safely, even though the wires have no insulation around them, whereas leaning a metal ladder up against a power line is extremely dangerous.
2. Discuss the advantages and disadvantages of Christmas tree lights connected in parallel versus those connected in series.
3. If all you have is a $120-\mathrm{V}$ line, would it be possible to light several 6-V lamps without burning them out? How?
4. Two lightbulbs of resistance $R_{1}$ and $R_{2}\left(R_{2}>R_{1}\right)$ and a battery are all connected in series. Which bulb is brighter? What if they are connected in parallel? Explain.
5. Household outlets are often double outlets. Are these connected in series or parallel? How do you know?
6. With two identical lightbulbs and two identical batteries, explain how and why you would arrange the bulbs and batteries in a circuit to get the maximum possible total power to the lightbulbs. (Ignore internal resistance of batteries.)
7. If two identical resistors are connected in series to a battery, does the battery have to supply more power or less power than when only one of the resistors is connected? Explain.
8. You have a single $60-\mathrm{W}$ bulb lit in your room. How does the overall resistance of your room's electric circuit change when you turn on an additional 100-W bulb? Explain.
9. Suppose three identical capacitors are connected to a battery. Will they store more energy if connected in series or in parallel?
10. When applying Kirchhoff's loop rule (such as in Fig. 19-36), does the sign (or direction) of a battery's emf depend on the direction of current through the battery? What about the terminal voltage?

FIGURE 19-36
Question 10.
11. Different lamps might have batteries connected in either of the two arrangements shown in Fig. 19-37. What would be the advantages of each scheme?

FIGURE 19-37
Question 11.
(a)

(b)
12. For what use are batteries connected in series? For what use are they connected in parallel? Does it matter if the batteries are nearly identical or not in either case?

Questions
549

---

<!-- Page 550 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 550
13. Can the terminal voltage of a battery ever exceed its emf? Explain.
14. Explain in detail how you could measure the internal resistance of a battery.
15. In an $R C$ circuit, current flows from the battery until the capacitor is completely charged. Is the total energy supplied by the battery equal to the total energy stored by the capacitor? If not, where does the extra energy go?
16. Given the circuit shown in Fig. 19-38, use the words "increases," "decreases," or "stays the same" to complete the following statements:
(a) If $R_{7}$ increases, the potential difference between A and E $\_\_\_\_$ . Assume no resistance in (A) and \&,
(b) If $R_{7}$ increases, the potential difference between A and E $\_\_\_\_$ . Assume (A) and $\mathscr{E}$ have resistance.
(c) If $R_{7}$ increases, the voltage drop across $R_{4}$ $\_\_\_\_$ .
(d) If $R_{2}$ decreases, the current through $R_{1}$
(e) If $R_{2}$ decreases, the current through $R_{6}$ $\_\_\_\_$ .
(f) If $R_{2}$ decreases, the current through $R_{3}$ $\_\_\_\_$ .
(g) If $R_{5}$ increases, the voltage drop across $R_{2}$
(h) If $R_{5}$ increases, the voltage drop across $R_{4}$ $\_\_\_\_$
(i) If $R_{2}, R_{5}$, and $R_{7}$ increase, $\mathscr{E}(r=0)$ $\_\_\_\_$ .

FIGURE 19-38 Question 16. $R_{2}, R_{5}$, and $R_{7}$ are variable resistors (you can change their resistance), given the symbol -
17. Design a circuit in which two different switches of the type shown in Fig. 19-39 can be used to operate the same lightbulb from opposite sides of a room.

FIGURE 19-39
Question 17.
18. Why is it more dangerous to turn on an electric appliance when you are standing outside in bare feet than when you are inside wearing shoes with thick soles?
19. What is the main difference between an analog voltmeter and an analog ammeter?
20. What would happen if you mistakenly used an ammeter where you needed to use a voltmeter?
21. Explain why an ideal ammeter would have zero resistance and an ideal voltmeter infinite resistance.
22. A voltmeter connected across a resistor always reads less than the actual voltage (i.e., when the meter is not present). Explain.
23. A small battery-operated flashlight requires a single $1.5-\mathrm{V}$ battery. The bulb is barely glowing. But when you take the battery out and check it with a digital voltmeter, it registers 1.5 V . How would you explain this?

MisConceptual Questions

(a)

(b)

(c)

(d)
1. In which circuits shown in Fig. 19-40 are resistors connected in series?

FIGURE 19-40 MisConceptual Question 1.
2. Which resistors in Fig. 19-41 are connected in parallel?
(a) All three.
(b) $R_{1}$ and $R_{2}$.
(c) $R_{2}$ and $R_{3}$.
(d) $R_{1}$ and $R_{3}$.
(e) None of the above.

FIGURE 19-41
MisConceptual Question 2.
3. A $10,000-\Omega$ resistor is placed in series with a $100-\Omega$ resistor. The current in the $10,000-\Omega$ resistor is 10 A . If the resistors are swapped, how much current flows through the $100-\Omega$ resistor?
(a) $>10$ A.
$(b)<10 \mathrm{~A}$.
(c) 10 A .
(d) Need more information about the circuit.
4. Two identical $10-\mathrm{V}$ batteries and two identical $10-\Omega$ resistors are placed in series as shown in Fig. 19-42. If a $10-\Omega$ lightbulb is connected with one end connected between the batteries and other end between the resistors, how much current will flow through the lightbulb?
(a) 0 A .
(b) 1 A .
(c) 2 A .
(d) 4 A .

FIGURE 19-42 MisConceptual Question 4.

550
CHAPTER 19 DC Circuits

---

<!-- Page 551 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 55ユ
5. Which resistor shown in Fig. 19-43 has the greatest current going through it? Assume that all the resistors are equal.
(a) $R_{1}$.
(d) $R_{5}$.
(b) $R_{1}$ and $R_{2}$.
(e) All of them the same.
(c) $R_{3}$ and $R_{4}$.

FIGURE 19-43
MisConceptual Question 5.
6. Figure $19-44$ shows three identical bulbs in a circuit. What happens to the brightness of bulb A if you replace bulb B with a short circuit?
(a) Bulb A gets brighter.
(b) Bulb A gets dimmer.
(c) Bulb A's brightness does not change.
(d) Bulb A goes out.

FIGURE 19-44
MisConceptual Question 6.
7. When the switch shown in Fig. 19-45 is closed, what will happen to the voltage across resistor $R_{4}$ ? It will
(a) increase.
(b) decrease.
(c) stay the same.

FIGURE 19-45
MisConceptual Questions 7 and 8.
8. When the switch shown in Fig. 19-45 is closed, what will happen to the voltage across resistor $R_{1}$ ? It will
(a) increase.
(b) decrease.
(c) stay the same.
9. As a capacitor is being charged in an $R C$ circuit, the current flowing through the resistor is
(a) increasing.
(c) constant.
(b) decreasing.
(d) zero.
10. For the circuit shown in Fig. 19-46, what happens when the switch S is closed?
(a) Nothing. Current cannot flow through the capacitor.
(b) The capacitor immediately charges up to the battery emf.
(c) The capacitor eventually charges up to the full battery emf at a rate determined by $R$ and $C$.
(d) The capacitor charges up to a fraction of the battery emf determined by $R$ and $C$.
(e) The capacitor charges up to a fraction of the battery emf determined by $R$ only.

FIGURE 19-46
MisConceptual Question 10.
11. The capacitor in the circuit shown in Fig. 19-47 is charged to an initial value $Q$. When the switch is closed, it discharges through the resistor. It takes 2.0 seconds for the charge to drop to $\frac{1}{2} Q$. How long does it take to drop to $\frac{1}{4} Q$ ?
(a) 3.0 seconds.
(b) 4.0 seconds.
(c) Between 2.0 and 3.0 seconds.
(d) Between 3.0 and 4.0 seconds.
(e) More than 4.0 seconds.

FIGURE 19-47
MisConceptual Question 11.
12. A resistor and a capacitor are used in series to control the timing in the circuit of a heart pacemaker. To design a pacemaker that can double the heart rate when the patient is exercising, which statement below is true? The capacitor
(a) needs to discharge faster, so the resistance should be decreased.
(b) needs to discharge faster, so the resistance should be increased.
(c) needs to discharge slower, so the resistance should be decreased.
(d) needs to discharge slower, so the resistance should be increased.
(e) does not affect the timing, regardless of the resistance.
13. Why is an appliance cord with a three-prong plug safer than one with two prongs?
(a) The 120 V from the outlet is split among three wires, so it isn't as high a voltage as when it is only split between two wires.
(b) Three prongs fasten more securely to the wall outlet.
(c) The third prong grounds the case, so the case cannot reach a high voltage.
(d) The third prong acts as a ground wire, so the electrons have an easier time leaving the appliance. As a result, fewer electrons build up in the appliance.
(e) The third prong controls the capacitance of the appliance, so it can't build up a high voltage.
14. When capacitors are connected in series, the effective capacitance is $\_\_\_\_$ the smallest capacitance; when capacitors are connected in parallel, the effective capacitance is $\_\_\_\_$ the largest capacitance.
(a) greater than; equal to.
(d) equal to; less than.
(b) greater than; less than.
(e) equal to; equal to.
(c) less than; greater than.
15. If ammeters and voltmeters are not to significantly alter the quantities they are measuring,
(a) the resistance of an ammeter and a voltmeter should be much higher than that of the circuit element being measured.
(b) the resistance of an ammeter should be much lower, and the resistance of a voltmeter should be much higher, than those of the circuit being measured.
(c) the resistance of an ammeter should be much higher, and the resistance of a voltmeter should be much lower, than those of the circuit being measured.
(d) the resistance of an ammeter and a voltmeter should be much lower than that of the circuit being measured.
(e) None of the above.

MisConceptual Questions
551

---

<!-- Page 552 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 552
For assigned homework and other learning materials, go to the MasteringPhysics website.
MP

Problems

19-1 Emf and Terminal Voltage
1. (I) Calculate the terminal voltage for a battery with an internal resistance of $0.900 \Omega$ and an emf of 6.00 V when the battery is connected in series with (a) a $71.0-\Omega$ resistor, and (b) a $710-\Omega$ resistor.
2. (I) Four $1.50-\mathrm{V}$ cells are connected in series to a $12.0-\Omega$ lightbulb. If the resulting current is 0.45 A , what is the internal resistance of each cell, assuming they are identical and neglecting the resistance of the wires?
3. (II) What is the internal resistance of a $12.0-\mathrm{V}$ car battery whose terminal voltage drops to 8.8 V when the starter motor draws 95 A ? What is the resistance of the starter?

19-2 Resistors in Series and Parallel
[In these Problems neglect the internal resistance of a battery unless the Problem refers to it.]
4. (I) A $650-\Omega$ and an $1800-\Omega$ resistor are connected in series with a $12-\mathrm{V}$ battery. What is the voltage across the $1800-\Omega$ resistor?
5. (I) Three $45-\Omega$ lightbulbs and three $65-\Omega$ lightbulbs are connected in series. (a) What is the total resistance of the circuit? (b) What is the total resistance if all six are wired in parallel?
6. (II) Suppose that you have a $580-\Omega$, a $790-\Omega$, and a $1.20-\mathrm{k} \Omega$ resistor. What is (a) the maximum, and (b) the minimum resistance you can obtain by combining these?
7. (II) How many $10-\Omega$ resistors must be connected in series to give an equivalent resistance to five $100-\Omega$ resistors connected in parallel?
8. (II) Design a "voltage divider" (see Example 19-3) that would provide one-fifth ( 0.20 ) of the battery voltage across $R_{2}$, Fig. 19-6. What is the ratio $R_{1} / R_{2}$ ?
9. (II) Suppose that you have a $9.0-\mathrm{V}$ battery and wish to apply a voltage of only 3.5 V . Given an unlimited supply of $1.0-\Omega$ resistors, how could you connect them to make a "voltage divider" that produces a $3.5-\mathrm{V}$ output for a $9.0-\mathrm{V}$ input?
10. (II) Three $1.70-\mathrm{k} \Omega$ resistors can be connected together in four different ways, making combinations of series and/or parallel circuits. What are these four ways, and what is the net resistance in each case?
11. (II) A battery with an emf of 12.0 V shows a terminal voltage of 11.8 V when operating in a circuit with two lightbulbs, each rated at 4.0 W (at 12.0 V ), which are connected in parallel. What is the battery's internal resistance?
12. (II) Eight identical bulbs are connected in series across a 120-V line. (a) What is the voltage across each bulb? (b) If the current is 0.45 A , what is the resistance of each bulb, and what is the power dissipated in each?
13. (II) Eight bulbs are connected in parallel to a $120-\mathrm{V}$ source by two long leads of total resistance $1.4 \Omega$. If 210 mA flows through each bulb, what is the resistance of each, and what fraction of the total power is wasted in the leads?
14. (II) A close inspection of an electric circuit reveals that a $480-\Omega$ resistor was inadvertently soldered in the place where a $350-\Omega$ resistor is needed. How can this be fixed without removing anything from the existing circuit?
15. (II) Eight $7.0-\mathrm{W}$ Christmas tree lights are connected in series to each other and to a $120-\mathrm{V}$ source. What is the resistance of each bulb?
16. (II) Determine (a) the equivalent resistance of the circuit shown in Fig. 19-48, (b) the voltage across each resistor, and (c) the current through each resistor.

FIGURE 19-48
Problem 16.
17. (II) A $75-\mathrm{W}, 120-\mathrm{V}$ bulb is connected in parallel with a $25-\mathrm{W}, 120-\mathrm{V}$ bulb. What is the net resistance?
18. (II) (a) Determine the equivalent resistance of the "ladder" of equal 175-Ω resistors shown in Fig. 19-49. In other words, what resistance would an ohmmeter read if connected between points A and B ? (b) What is the current through each of the three resistors on the left if a $50.0-\mathrm{V}$ battery is connected between points A and B ?

FIGURE 19-49
Problem 18.
19. (II) What is the net resistance of the circuit connected to the battery in Fig. 19-50?

FIGURE 19-50
Problems 19 and 20.
20. (II) Calculate the current through each resistor in Fig. 19-50 if each resistance $R=3.25 \mathrm{k} \Omega$ and $V=12.0 \mathrm{~V}$. What is the potential difference between points A and B ?
21. (III) Two resistors when connected in series to a $120-\mathrm{V}$ line use one-fourth the power that is used when they are connected in parallel. If one resistor is $4.8 \mathrm{k} \Omega$, what is the resistance of the other?
22. (III) Three equal resistors ( $R$ ) are connected to a battery as shown in Fig. 19-51. Qualitatively, what happens to (a) the voltage drop across each of these resistors, (b) the current flow through each, and (c) the terminal voltage of the battery, when the switch S is opened, after having been closed for a long time? (d) If the emf of the battery is 9.0 V , what is its terminal voltage when the switch is closed if the internal resistance $r$ is $0.50 \Omega$ and $R=5.50 \Omega$ ? (e) What is the terminal voltage when the switch is open?

FIGURE 19-51
Problem 22.

552
CHAPTER 19 DC Circuits

---

<!-- Page 553 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 55.
23. (III) $\mathrm{A} 2.5-\mathrm{k} \Omega$ and a $3.7-\mathrm{k} \Omega$ resistor are connected in parallel; this combination is connected in series with a $1.4-\mathrm{k} \Omega$ resistor. If each resistor is rated at 0.5 W (maximum without overheating), what is the maximum voltage that can be applied across the whole network?
24. (III) Consider the network of resistors shown in Fig. 19-52. Answer qualitatively: (a) What happens to the voltage across each resistor when the switch S is closed? ( $b$ ) What happens to the current through each when the switch is closed? (c) What happens to the power output of the battery when the switch is closed? (d) Let $R_{1}=R_{2}=R_{3}=R_{4}=155 \Omega$ and $V=22.0 \mathrm{~V}$. Determine the current through each resis-

FIGURE 19-52
Problem 24.
tor before and after closing the switch. Are your qualitative predictions confirmed?

19-3 Kirchhoff's Rules
25. (I) Calculate the current in the circuit of Fig. 19-53, and show that the sum of all the voltage changes around the circuit is zero.

FIGURE 19-53
Problem 25.
26. (II) Determine the terminal voltage of each battery in Fig. 19-54.

FIGURE 19-54
Problem 26.
27. (II) For the circuit shown in Fig. 19-55, find the potential difference between points a and b. Each resistor has $R=160 \Omega$ and each battery is 1.5 V .

FIGURE 19-55
Problem 27.
28. (II) Determine the magnitudes and directions of the currents in each resistor shown in Fig. 19-56. The batteries have emfs of $\mathscr{E}_{1}=9.0 \mathrm{~V}$ and $\mathscr{E}_{2}=12.0 \mathrm{~V}$ and the resistors have values of $R_{1}=25 \Omega, R_{2}=68 \Omega$, and $R_{3}=35 \Omega$. (a) Ignore internal resistance of the batteries. (b) Assume each battery has internal resistance $r=1.0 \Omega$.

FIGURE 19-56
Problem 28.

FIGURE 19-58
Problem 30.
29. (II) (a) What is the potential difference between points a and d in Fig. 19-57 (similar to Fig. 19-13, Example 19-8), and ( $b$ ) what is the terminal voltage of each battery?

FIGURE 19-57
Problem 29.
30. (II) Calculate the magnitude and direction of the currents in each resistor of Fig. 19-58.
31. (II) Determine the magnitudes and directions of the currents through $R_{1}$ and $R_{2}$ in Fig. 19-59.

FIGURE 19-59
Problems 31 and 32.
32. (II) Repeat Problem 31, now assuming that each battery has an internal resistance $r=1.4 \Omega$.
33. (III) (a) A network of five equal resistors $R$ is connected to a battery $\mathscr{E}$ as shown in Fig. 19-60. Determine the current $I$ that flows out of the battery. (b) Use the value determined for $I$ to find the single resistor $R_{\text {eq }}$ that is equivalent to the five-resistor network.
34. (III) (a) Determine the currents $I_{1}, I_{2}$, and $I_{3}$ in Fig. 19-61. Assume the internal resistance of each battery is $r=1.0 \Omega$. (b) What is the terminal voltage of the $6.0-\mathrm{V}$ battery?

FIGURE 19-61
Problems 34 and 35.
35. (III) What would the current $I_{1}$ be in Fig. 19-61 if the 12-Ω resistor is shorted out (resistance $=0$ )? Let $r=1.0 \Omega$.

Problems
553

---

<!-- Page 554 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 554t

19-4 Emfs Combined, Battery Charging
36. (II) Suppose two batteries, with unequal emfs of 2.00 V and 3.00 V , are connected as shown in Fig. 19-62. If each internal resistance is $r=0.350 \Omega$, and $R=4.00 \Omega$, what is the voltage across the resistor $R$ ?

FIGURE 19-62
Problem 36.
37. (II) A battery for a proposed electric car is to have three hundred 3-V lithium ion cells connected such that the total voltage across all of the cells is 300 V . Describe a possible connection configuration (using series and parallel connections) that would meet these battery specifications.

19-5 Capacitors in Series and Parallel
38. (I) (a) Six $4.8-\mu \mathrm{F}$ capacitors are connected in parallel. What is the equivalent capacitance? (b) What is their equivalent capacitance if connected in series?
39. (I) A $3.00-\mu \mathrm{F}$ and a $4.00-\mu \mathrm{F}$ capacitor are connected in series, and this combination is connected in parallel with a $2.00-\mu \mathrm{F}$ capacitor (see Fig. 19-63). What is the net capacitance?
40. (II) If 21.0 V is applied across the whole network of Fig. 19-63, calculate (a) the voltage across each capacitor and ( $b$ ) the charge on each capacitor.

FIGURE 19-63
Problems 39 and 40.
41. (II) The capacitance of a portion of a circuit is to be reduced from 2900 pF to 1200 pF . What capacitance can be added to the circuit to produce this effect without removing existing circuit elements? Must any existing connections be broken to accomplish this?
42. (II) An electric circuit was accidentally constructed using a $7.0-\mu \mathrm{F}$ capacitor instead of the required $16-\mu \mathrm{F}$ value. Without removing the $7.0-\mu \mathrm{F}$ capacitor, what can a technician add to correct this circuit?
43. (II) Consider three capacitors, of capacitance 3200 pF , 5800 pF , and $0.0100 \mu \mathrm{~F}$. What maximum and minimum capacitance can you form from these? How do you make the connection in each case?
44. (II) Determine the equivalent capacitance between points a and b for the combination of capacitors shown in Fig. 19-64.

FIGURE 19-64
Problem 44.
45. (II) What is the ratio of the voltage $V_{1}$ across capacitor $C_{1}$ in Fig. 19-65 to the voltage $V_{2}$ across capacitor $C_{2}$ ?

FIGURE 19-65
Problem 45.
46. (II) A $0.50-\mu \mathrm{F}$ and a $1.4-\mu \mathrm{F}$ capacitor are connected in series to a $9.0-\mathrm{V}$ battery. Calculate (a) the potential difference across each capacitor and (b) the charge on each. (c) Repeat parts ( $a$ ) and ( $b$ ) assuming the two capacitors are in parallel.
47. (II) A circuit contains a single $250-\mathrm{pF}$ capacitor hooked across a battery. It is desired to store four times as much energy in a combination of two capacitors by adding a single capacitor to this one. How would you hook it up, and what would its value be?
48. (II) Suppose three parallel-plate capacitors, whose plates have areas $A_{1}, A_{2}$, and $A_{3}$ and separations $d_{1}, d_{2}$, and $d_{3}$, are connected in parallel. Show, using only Eq. 17-8, that Eq. 19-5 is valid.
49. (II) Two capacitors connected in parallel produce an equivalent capacitance of $35.0 \mu \mathrm{~F}$ but when connected in series the equivalent capacitance is only $4.8 \mu \mathrm{~F}$. What is the individual capacitance of each capacitor?
50. (III) Given three capacitors, $C_{1}=2.0 \mu \mathrm{~F}$, $C_{2}=1.5 \mu \mathrm{~F}$, and $C_{3}=3.0 \mu \mathrm{~F}$, what arrangement of parallel and series connections with a $12-\mathrm{V}$ battery will give the minimum voltage drop across the $2.0-\mu \mathrm{F}$ capacitor? What is the minimum voltage drop?
51. (III) In Fig. 19-66, suppose $C_{1}=C_{2}=C_{3}=C_{4}=C$. (a) Determine the equivalent capacitance between points a and b. (b) Determine the charge on each capacitor and the potential difference across each in terms of $V$.

FIGURE 19-66
Problem 51.

19-6 $\boldsymbol{R} \boldsymbol{C}$ Circuits
52. (I) Estimate the value of resistances needed to make a variable timer for intermittent windshield wipers: one wipe every $15 \mathrm{~s}, 8 \mathrm{~s}, 4 \mathrm{~s}, 2 \mathrm{~s}, 1 \mathrm{~s}$. Assume the capacitor used is on the order of $1 \mu \mathrm{~F}$. See Fig. 19-67.

FIGURE 19-67
Problem 52.

554
CHAPTER 19 DC Circuits

---

<!-- Page 555 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 555
53. (II) Electrocardiographs are often connected as shown in Fig. 19-68. The lead wires to the legs are said to be capacitively coupled. A time constant of 3.0 s is typical and allows rapid changes in potential to be recorded accurately. If $C=3.0 \mu \mathrm{~F}$, what value must $R$ have? [Hint: Consider each leg as a separate circuit.]
54. (II) In Fig. 19-69 (same as Fig. 19-20a), the total resistance is $15.0 \mathrm{k} \Omega$, and the battery's emf is 24.0 V . If the time constant is measured to be $18.0 \mu \mathrm{~s}$, calculate (a) the total capacitance of the circuit and (b) the time it takes for the voltage across the resistor to reach 16.0 V after the switch is closed.

FIGURE 19-69
Problem 54.
55. (II) Two $3.8-\mu \mathrm{F}$ capacitors, two $2.2-\mathrm{k} \Omega$ resistors, and a $16.0-\mathrm{V}$ source are connected in series. Starting from the uncharged state, how long does it take for the current to drop from its initial value to 1.50 mA ?
56. (II) The $R C$ circuit of Fig. 19-70 (same as Fig. 19-21a) has $R=8.7 \mathrm{k} \Omega \quad$ and $\quad C=3.0 \mu \mathrm{~F}$. The capacitor is at voltage $V_{0}$ at $t=0$, when the switch is closed. How long does it take the capacitor to discharge to $0.25 \%$ of its initial voltage?

FIGURE 19-70
Problem 56.
57. (III) Consider the circuit shown in Fig. 19-71, where all resistors have the same resistance $R$. At $t=0$, with the capacitor $C$ uncharged, the switch is closed. (a) At $t=0$, the three currents can be determined by analyzing a simpler, but equivalent, circuit. Draw this simpler circuit and use it to find the values of $I_{1}, I_{2}$, and $I_{3}$ at $t=0$. (b) At $t=\infty$, the currents can be determined by analyzing a simpler, equivalent circuit. Draw this simpler circuit and implement it in finding the values of $I_{1}, I_{2}$, and $I_{3}$ at $t=\infty$. (c) At $t=\infty$, what is the potential difference across the capacitor?

FIGURE 19-71
Problem 57.
58. (III) Two resistors and two uncharged capacitors are arranged as shown in Fig. 19-72. Then a potential difference of 24 V is applied across the combination as shown. (a) What is the potential at point a with switch S open? (Let $V=0$ at the negative terminal of the source.) (b) What is the potential at point $b$ with the switch open? (c) When the switch is closed, what is the final potential of point b ? (d) How much charge flows through the switch S after it is closed?

FIGURE 19-72
Problem 58.

19-8 Ammeters and Voltmeters
59. (I) (a) An ammeter has a sensitivity of $35,000 \Omega / \mathrm{V}$. What current in the galvanometer produces full-scale deflection? (b) What is the resistance of a voltmeter on the $250-\mathrm{V}$ scale if the meter sensitivity is $35,000 \Omega / \mathrm{V}$ ?
60. (II) An ammeter whose internal resistance is $53 \Omega$ reads 5.25 mA when connected in a circuit containing a battery and two resistors in series whose values are $720 \Omega$ and $480 \Omega$. What is the actual current when the ammeter is absent?
61. (II) A milliammeter reads 35 mA full scale. It consists of a $0.20-\Omega$ resistor in parallel with a $33-\Omega$ galvanometer. How can you change this ammeter to a voltmeter giving a full-scale reading of 25 V without taking the ammeter apart? What will be the sensitivity ( $\Omega / \mathrm{V}$ ) of your voltmeter?
62. (II) A galvanometer has an internal resistance of $32 \Omega$ and deflects full scale for a $55-\mu \mathrm{A}$ current. Describe how to use this galvanometer to make (a) an ammeter to read currents up to 25 A , and ( $b$ ) a voltmeter to give a full-scale deflection of 250 V .
63. (III) A battery with $\mathscr{E}=12.0 \mathrm{~V}$ and internal resistance $r=1.0 \Omega$ is connected to two $7.5-\mathrm{k} \Omega$ resistors in series. An ammeter of internal resistance $0.50 \Omega$ measures the current, and at the same time a voltmeter with internal resistance $15 \mathrm{k} \Omega$ measures the voltage across one of the $7.5-\mathrm{k} \Omega$ resistors in the circuit. What do the ammeter and voltmeter read? What is the \% "error" from the current and voltage without meters?
64. (III) What internal resistance should the voltmeter of Example 19-17 have to be in error by less than 5\%?
65. (III) Two $9.4-\mathrm{k} \Omega$ resistors are placed in series and connected to a battery. A voltmeter of sensitivity $1000 \Omega / \mathrm{V}$ is on the $3.0-\mathrm{V}$ scale and reads 1.9 V when placed across either resistor. What is the emf of the battery? (Ignore its internal resistance.)
66. (III) When the resistor $R$ in Fig. 19-73 is $35 \Omega$, the highresistance voltmeter reads 9.7 V . When $R$ is replaced by a $14.0-\Omega$ resistor, the voltmeter reading drops to 8.1 V . What are the emf and internal resistance of the battery?

FIGURE 19-73
Problem 66.

Problems
555

---

<!-- Page 556 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 555

General Problems
67. Suppose that you wish to apply a $0.25-\mathrm{V}$ potential difference between two points on the human body. The resistance is about $1800 \Omega$, and you only have a $1.5-\mathrm{V}$ battery. How can you connect up one or more resistors to produce the desired voltage?
68. A three-way lightbulb can produce $50 \mathrm{~W}, 100 \mathrm{~W}$, or 150 W , at 120 V . Such a bulb contains two filaments that can be connected to the 120 V individually or in parallel (Fig. 19-74). (a) Describe how the connections to the two filaments are made to give each of the three wattages. (b) What must be the resistance of each filament?

FIGURE 19-74
Problem 68.
69. What are the values of effective capacitance which can be obtained by connecting four identical capacitors, each having a capacitance $C$ ?
70. Electricity can be a hazard in hospitals, particularly to patients who are connected to electrodes, such as an ECG. Suppose that the motor of a motorized bed shorts out to the bed frame, and the bed frame's connection to a ground has broken (or was not there in the first place). If a nurse touches the bed and the patient at the same time, the nurse becomes a conductor and a complete circuit can be made through the patient to ground through the ECG apparatus. This is shown schematically in Fig. 19-75. Calculate the current through the patient.

FIGURE 19-75 Problem 70.
71. Suppose that a person's body resistance is $950 \Omega$ (moist skin). (a) What current passes through the body when the person accidentally is connected to 120 V ? (b) If there is an alternative path to ground whose resistance is $25 \Omega$, what then is the current through the body? (c) If the voltage source can produce at most 1.5 A , how much current passes through the person in case (b)?
72. One way a multiple-speed ventilation fan for a car can be designed is to put resistors in series with the fan motor. The resistors reduce the current through the motor and make it run more slowly. Suppose the current in the motor is 5.0 A when it is connected directly across a $12-\mathrm{V}$ battery. (a) What series resistor should be used to reduce the current to 2.0 A for low-speed operation? (b) What power rating should the resistor have? Assume that the motor's resistance is roughly the same at all speeds.
73. A Wheatstone bridge is a type of "bridge circuit" used to make measurements of resistance. The unknown resistance to be measured, $R_{x}$, is placed in the circuit with accurately known resistances $R_{1}, R_{2}$, and $R_{3}$ (Fig. 19-76). One of these, $R_{3}$, is a variable resistor which is adjusted so that when the switch is closed momentarily, the ammeter (A) shows zero current flow. The bridge is then said to be balanced. (a) Determine $R_{x}$ in terms of $R_{1}, R_{2}$, and $R_{3}$. (b) If a Wheatstone bridge is "balanced" when $R_{1}=590 \Omega$, $R_{2}=972 \Omega, \quad$ and $R_{3}=78.6 \Omega$, what is the value of the unknown resistance?

FIGURE 19-76
Problem 73.
Wheatstone bridge.
74. The internal resistance of a $1.35-\mathrm{V}$ mercury cell is $0.030 \Omega$, whereas that of a $1.5-\mathrm{V}$ dry cell is $0.35 \Omega$. Explain why three mercury cells can more effectively power a $2.5-\mathrm{W}$ hearing aid that requires 4.0 V than can three dry cells.
75. How many $\frac{1}{2}-\mathrm{W}$ resistors, each of the same resistance, must be used to produce an equivalent $3.2-\mathrm{k} \Omega, 3.5-\mathrm{W}$ resistor? What is the resistance of each, and how must they be connected? Do not exceed $P=\frac{1}{2} \mathrm{~W}$ in each resistor.
76. A solar cell, 3.0 cm square, has an output of 350 mA at 0.80 V when exposed to full sunlight. A solar panel that delivers close to 1.3 A of current at an emf of 120 V to an external load is needed. How many cells will you need to create the panel? How big a panel will you need, and how should you connect the cells to one another?

556
CHAPTER 19 DC Circuits

---

<!-- Page 557 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 557
77. A power supply has a fixed output voltage of 12.0 V , but you need $V_{\mathrm{T}}=3.5 \mathrm{~V}$ output for an experiment. (a) Using the voltage divider shown in Fig. 19-77, what should $R_{2}$ be if $R_{1}$ is $14.5 \Omega$ ? (b) What will the terminal voltage $V_{\mathrm{T}}$ be if you connect a load to the $3.5-\mathrm{V}$ output, assuming the load has a resistance of $7.0 \Omega$ ?

FIGURE 19-77
Problem 77.
78. A battery produces 40.8 V when 8.40 A is drawn from it, and 47.3 V when 2.80 A is drawn. What are the emf and internal resistance of the battery?
79. In the circuit shown in Fig. 19-78, the $33-\Omega$ resistor dissipates 0.80 W . What is the battery voltage?

FIGURE 19-78
Problem 79.
80. For the circuit shown in Fig. 19-79, determine (a) the current through the $16-\mathrm{V}$ battery and (b) the potential difference between points a and b , $V_{\mathrm{a}}-V_{\mathrm{b}}$.

FIGURE 19-79
Problem 80.
81. The current through the $20-\Omega$ resistor in Fig. 19-80 does not change whether the two switches $S_{1}$ and $S_{2}$ are both open or both closed. Use this clue to determine the value of the unknown resistance $R$.

FIGURE 19-80 Problem 81.

(a)

(b)
82. (a) A voltmeter and an ammeter can be connected as shown in Fig. 19-81a to measure a resistance $R$. If $V$ is the voltmeter reading, and $I$ is the ammeter reading, the value of $R$ will not quite be $V / I$ (as in Ohm's law) because some current goes through the voltmeter. Show that the actual value of $R$ is
$$\frac{1}{R}=\frac{I}{V}-\frac{1}{R_{\mathrm{V}}},$$
where $R_{\mathrm{V}}$ is the voltmeter resistance. Note that $R \approx V / I$ if $R_{\mathrm{V}} \gg R$. (b) A voltmeter and an ammeter can also be connected as shown in Fig. 19-81b to measure a resistance $R$. Show in this case that
$$R=\frac{V}{I}-R_{\mathrm{A}},$$
where $V$ and $I$ are the voltmeter and ammeter readings and $R_{\mathrm{A}}$ is the resistance of the ammeter. Note that $R \approx V / I$ if $R_{\mathrm{A}} \ll R$.

FIGURE 19-81
Problem 82.
83. The circuit shown in Fig. 19-82 uses a neon-filled tube as in Fig. 19-23a. This neon lamp has a threshold voltage $V_{0}$ for conduction, because no current flows until the neon gas in the tube is ionized by a sufficiently strong electric field. Once the threshold voltage is exceeded, the lamp has negligible resistance. The capacitor stores electrical energy, which can be released to flash the lamp. Assume that $C=0.150 \mu \mathrm{~F}$, $R=2.35 \times 10^{6} \Omega, V_{0}=90.0 \mathrm{~V}$, and $\mathscr{E}=105 \mathrm{~V}$. (a) Assuming the circuit is hooked up to the emf at time $t=0$, at what time will the light first flash? (b) If the value of $R$ is increased, will the time you found in part (a) increase or decrease? (c) The flashing of the lamp is very brief. Why? (d) Explain what happens after the lamp flashes for the first time.

FIGURE 19-82
Problem 83.
84. In Fig. 19-83, let $V=10.0 \mathrm{~V}$ and $C_{1}=C_{2}=C_{3}=25.4 \mu \mathrm{~F}$. How much energy is stored in the capacitor network (a) as shown, (b) if the capacitors were all in series, and (c) if the capacitors were all in parallel?

FIGURE 19-83
Problem 84.

General Problems
557

---

<!-- Page 558 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 558
85. A $12.0-\mathrm{V}$ battery, two resistors, and two capacitors are connected as shown in Fig. 19-84. After the circuit has been connected for a long time, what is the charge on each capacitor?

FIGURE 19-84 Problem 85.
86. How much energy must a $24-\mathrm{V}$ battery expend to charge a $0.45-\mu \mathrm{F}$ and a $0.20-\mu \mathrm{F}$ capacitor fully when they are placed (a) in parallel, (b) in series? (c) How much charge flowed from the battery in each case?
87. Two capacitors, $C_{1}=2.2 \mu \mathrm{~F}$ and $C_{2}=1.2 \mu \mathrm{~F}$, are connected in parallel to a $24-\mathrm{V}$ source as shown in Fig. 19-85a. After they are charged they are disconnected from the source and from each other, and then reconnected directly to each other with plates of opposite sign connected together (see Fig. 19-85b). Find the charge on each capacitor and the potential across each after equilibrium is established (Fig. 19-85c).

(a) Initial configuration.

(b) At the instant of reconnection only.

FIGURE 19-85
Problem 87.
(c) Later, after charges move.
89. The performance of the starter circuit in a car can be significantly degraded by a small amount of corrosion on a battery terminal. Figure 19-87a depicts a properly functioning circuit with a battery ( $12.5-\mathrm{V}$ emf, $0.02-\Omega$ internal resistance) attached via corrosion-free cables to a starter motor of resistance $R_{\mathrm{S}}=0.15 \Omega$. Sometime later, corrosion between a battery terminal and a starter cable introduces an extra series resistance of only $R_{\mathrm{C}}=0.10 \Omega$ into the circuit as suggested in Fig. 19-87b. Let $P_{0}$ be the power delivered to the starter in the circuit free of corrosion, and let $P$ be the power delivered to the circuit
with corrosion. Determine the ratio $P / P_{0}$.

FIGURE 19-87
Problem 89.
90. The variable capacitance of an old radio tuner consists of four plates connected together placed alternately between four other plates, also connected together (Fig. 19-88). Each plate is separated from its neighbor by 1.6 mm of air. One set of plates can move so that the area of overlap of each plate varies from $2.0 \mathrm{~cm}^{2}$ to $9.0 \mathrm{~cm}^{2}$. (a) Are these seven capacitors connected in series or in parallel? (b) Determine the range of capacitance values.
88. The switch S in Fig. 19-86 is connected downward so that capacitor $C_{2}$ becomes fully charged by the battery of voltage $V_{0}$. If the switch is then connected upward, determine the charge on each capacitor after the switching.

FIGURE 19-86
Problem 88.
91. A $175-\mathrm{pF}$ capacitor is connected in series with an unknown capacitor, and as a series combination they are connected to a $25.0-\mathrm{V}$ battery. If the $175-\mathrm{pF}$ capacitor stores 125 pC of charge on its plates, what is the unknown capacitance?
92. In the circuit shown in Fig. 19-89, $C_{1}=1.0 \mu \mathrm{~F}, C_{2}=2.0 \mu \mathrm{~F}$, $C_{3}=2.4 \mu \mathrm{~F}$, and a voltage $V_{\mathrm{ab}}=24 \mathrm{~V}$ is applied across points a and b . After $C_{1}$ is fully charged, the switch is thrown to the right. What is the final charge and potential difference on each capacitor?

FIGURE 19-89
Problem 92.

558
CHAPTER 19 DC Circuits

---

<!-- Page 559 -->

GIAN_PPA7_GE_19_526-559v4.1HR1.QXD 26-08-2014 16:01 Page 559

Search and Learn
1. Fill in the Table below for a combination of two unequal resistors of resistance $R_{1}$ and $R_{2}$. Assume the electric potential on the low-voltage end of the combination is $V_{\mathrm{A}}$ volts and the potential at the high-voltage end of the combination is $V_{\mathrm{B}}$ volts. First draw diagrams.

| Property | Resistors in Series | Resistors in Parallel |
| --- | --- | --- |
| Equivalent resistance |  |  |
| Current through equivalent resistance |  |  |
| Voltage across equivalent resistance |  |  |
| Voltage across the pair of resistors |  |  |
| Voltage across each resistor | $$\begin{array}{l}
V_{1}= |  |
| V_{2}=
\end{array}$$ | $$\begin{array}{l}
V_{1}= |  |
| V_{2}=
\end{array}$$ |  |  |
| Voltage at a point between the resistors |  | Not applicable |
| Current through each resistor | $$\begin{array}{l}
I_{1}= |  |
| I_{2}=
\end{array}$$ | $$\begin{array}{l}
I_{1}= |  |
| I_{2}=
\end{array}$$ |  |  |

2. Cardiac defibrillators are discussed in Section 17-9. (a) Choose a value for the resistance so that the $1.0-\mu \mathrm{F}$ capacitor can be charged to 3000 V in 2.0 seconds. Assume that this 3000 V is $95 \%$ of the full source voltage. (b) The effective resistance of the human body is given in Section 19-7. If the defibrillator discharges with a time constant of 10 ms , what is the effective capacitance of the human body?
3. The circuit shown in Fig. 19-90 is a primitive 4-bit digital-to-analog converter (DAC). In this circuit, to represent each digit ( $2^{n}$ ) of a binary number, a " 1 " has the $n^{\text {th }}$ switch closed whereas zero (" 0 ") has the switch open. For example, 0010 is represented by closing switch $n=1$, while all other switches are open. Show that the voltage $V$ across the $1.0-\Omega$ resistor for the binary numbers 0001, 0010, 0100, and 1001 (which in decimal represent 1, 2, 4, 9) follows the pattern that you expect for a 4-bit DAC. (Section 17-10 may help.)

FIGURE 19-90
Search and Learn 3.

ANSWERS TO EXERCISES

A: $6 \Omega$ and $25 \Omega$.
B: (b).
C: (a) $60-\mathrm{W}$ bulb; (b) $100-\mathrm{W}$ bulb. [Can you explain why?
In (a), recall $P=I^{2} R$.]
D: $41 I_{3}-45+21 I_{2}-80=0$.
E: 180 A ; this high current through the batteries could cause them to become very hot (and dangerous-possibly exploding): the power dissipated in the weak battery would be $P=I^{2} r=(180 \mathrm{~A})^{2}(0.10 \Omega)=3200 \mathrm{~W}!$

F: ( $e$ ).
$\mathbf{G}: \approx 500 \mathrm{k} \Omega$.

Search and Learn
559

---

