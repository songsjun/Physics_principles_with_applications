# Chapter 8: Rotational Motion

<!-- Page 198 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 198-

You too can experience rapid rotation-if your stomach can take the high angular velocity and centripetal acceleration of some of the faster amusement park rides. If not, try the slower merry-go-round or Ferris wheel. Rotating carnival rides have rotational kinetic energy as well as angular momentum. Angular acceleration is produced by a net torque, and rotating objects have rotational kinetic energy.
C H
8

PT
Rotational Motion
CHAPTER-OPENING QUESTION-Guess now!
A solid ball and a solid cylinder roll down a ramp. They both start from rest at the same time and place. Which gets to the bottom first?
(a) They get there at the same time.
(b) They get there at almost exactly the same time except for frictional differences.
(c) The ball gets there first.
(d) The cylinder gets there first.
(e) Can't tell without knowing the mass and radius of each.

Until now, we have been concerned mainly with translational motion. We discussed the kinematics and dynamics of translational motion (the role of force). We also discussed the energy and momentum for translational motion. In this Chapter we will deal with rotational motion. We will discuss the kinematics of rotational motion and then its dynamics (involving torque), as well as rotational kinetic energy and angular momentum (the rotational analog of linear momentum). Our understanding of the world around us will be increased significantly-from rotating bicycle wheels and compact discs to amusement park rides, a spinning skater, the rotating Earth, and a centrifuge-and there may be a few surprises.

We will consider mainly the rotation of rigid objects about a fixed axis. A rigid object is an object with a definite shape that doesn't change, so that the particles composing it stay in fixed positions relative to one another. Any real object is capable of vibrating or deforming when a force is exerted on it. But these effects are often very small, so the concept of an ideal rigid object is very useful as a good approximation.

198

---

<!-- Page 199 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 199

8-1 Angular Quantities
The motion of a rigid object can be analyzed as the translational motion of the object's center of mass, plus rotational motion about its center of mass (Section 7-8). We have already discussed translational motion in detail, so now we focus on purely rotational motion. By purely rotational motion we mean that all points in the object move in circles, such as the point P in the rotating wheel of Fig. 8-1, and that the centers of these circles all lie on one line called the axis of rotation. In Fig. 8-1 the axis of rotation is perpendicular to the page and passes through point O .

Every point in an object rotating about a fixed axis moves in a circle (shown dashed in Fig. 8-1 for point P ) whose center is on the axis of rotation and whose radius is $r$, the distance of that point from the axis of rotation. A straight line drawn from the axis to any point in the object sweeps out the same angle $\theta$ in the same time interval.

To indicate the angular position of a rotating object, or how far it has rotated, we specify the angle $\theta$ of some particular line in the object (red in Fig. 8-1) with respect to a reference line, such as the $x$ axis in Fig. 8-1. A point in the object, such as P in Fig. 8-1, moves through an angle $\theta$ when it travels the distance $\ell$ measured along the circumference of its circular path. Angles are commonly measured in degrees, but the mathematics of circular motion is much simpler if we use the radian for angular measure. One radian (abbreviated rad) is defined as the angle subtended by an arc whose length is equal to the radius. For example, in Fig. 8-1b, point P is a distance $r$ from the axis of rotation, and it has moved a distance $\ell$ along the arc of a circle. The arc length $\ell$ is said to "subtend" the angle $\theta$. In radians, any angle $\theta$ is given by
$$\theta=\frac{\ell}{r},$$
$[\theta$ in radians $]$ (8-1a)
where $r$ is the radius of the circle, and $\ell$ is the arc length subtended by the angle $\theta$ specified in radians. If $\ell=r$, then $\theta=1 \mathrm{rad}$.

The radian is dimensionless since it is the ratio of two lengths. Nonetheless when giving an angle in radians, we always mention rad to remind us it is not degrees. It is often useful to rewrite Eq. 8-1a in terms of arc length $\ell$ :
$$\ell=r \theta .$$

Radians can be related to degrees in the following way. In a complete circle there are $360^{\circ}$, which must correspond to an arc length equal to the circumference of the circle, $\ell=2 \pi r$. For a full circle, $\theta=\ell / r=2 \pi r / r=2 \pi \mathrm{rad}$. Thus
$$360^{\circ}=2 \pi \mathrm{rad}$$

One radian is then $360^{\circ} / 2 \pi \approx 360^{\circ} / 6.28 \approx 57.3^{\circ}$. An object that makes one complete revolution (rev) has rotated through $360^{\circ}$, or $2 \pi$ radians:
$$1 \mathrm{rev}=360^{\circ}=2 \pi \mathrm{rad} .$$

EXAMPLE 8-1 Bike wheel. A bike wheel rotates 4.50 revolutions. How many radians has it rotated?
APPROACH All we need is a conversion of units using
$$1 \text { revolution }=360^{\circ}=2 \pi \mathrm{rad}=6.28 \mathrm{rad} .$$

SOLUTION
$$4.50 \text { revolutions }=(4.50 \mathrm{rev})\left(2 \pi \frac{\mathrm{rad}}{\mathrm{rev}}\right)=9.00 \pi \mathrm{rad}=28.3 \mathrm{rad}$$

FIGURE 8-1 Looking at a wheel that is rotating counterclockwise about an axis through the wheel's center at O (axis perpendicular to the page). Each point, such as point P , moves in a circular path; $\ell$ is the distance P travels as the wheel rotates through the angle $\theta$.

CAUTION
Use radians in calculating, not degrees

SECTION 8-1 Angular Quantities
199

---

<!-- Page 200 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 200

FIGURE 8-2 (a) Example 8-2. (b) For small angles, arc length and the chord length (straight line) are nearly equal.

FIGURE 8-3 A wheel rotates about its axle from (a) initial position $\theta_{1}$ to (b) final position $\theta_{2}$. The angular displacement is $\Delta \theta=\theta_{2}-\theta_{1}$.

EXAMPLE 8-2 Birds of prey-in radians. A particular bird's eye can just distinguish objects that subtend an angle no smaller than about $3 \times 10^{-4} \mathrm{rad}$. (a) How many degrees is this? (b) How small an object can the bird just distinguish when flying at a height of 100 m (Fig. 8-2a)?
APPROACH For (a) we use the relation $360^{\circ}=2 \pi \mathrm{rad}$. For (b) we use Eq. 8-1b, $\ell=r \theta$, to find the arc length.
SOLUTION (a) We convert $3 \times 10^{-4} \mathrm{rad}$ to degrees:
$$\left(3 \times 10^{-4} \mathrm{rad}\right)\left(\frac{360^{\circ}}{2 \pi \mathrm{rad}}\right)=0.017^{\circ} .$$
(b) We use Eq. 8-1b, $\ell=r \theta$. For small angles, the arc length $\ell$ and the chord length are approximately ${ }^{\dagger}$ the same (Fig. 8-2b). Since $r=100 \mathrm{~m}$ and $\theta=3 \times 10^{-4} \mathrm{rad}$, we find
$$\ell=r \theta=(100 \mathrm{~m})\left(3 \times 10^{-4} \mathrm{rad}\right)=3 \times 10^{-2} \mathrm{~m}=3 \mathrm{~cm} .$$

A bird can distinguish a small mouse (about 3 cm long) from a height of 100 m . That is good eyesight.
NOTE Had the angle been given in degrees, we would first have had to convert it to radians to make this calculation. Equations 8-1 are valid only if the angle is specified in radians. Degrees (or revolutions) won't work.

To describe rotational motion, we make use of angular quantities, such as angular velocity and angular acceleration. These are defined in analogy to the corresponding quantities in linear motion, and are chosen to describe the rotating object as a whole, so they are the same for each point in the rotating object. Each point in a rotating object may also have translational velocity and acceleration, but they have different values for different points in the object.

When an object such as the bicycle wheel in Fig. 8-3 rotates from some initial position, specified by $\theta_{1}$, to some final position, $\theta_{2}$, its angular displacement is
$$\Delta \theta=\theta_{2}-\theta_{1} .$$

The angular velocity (denoted by $\omega$, the Greek lowercase letter omega) is defined in analogy with linear (translational) velocity that was discussed in Chapter 2. Instead of linear displacement, we use the angular displacement. Thus the average angular velocity of an object rotating about a fixed axis is defined as
$$\bar{\omega}=\frac{\Delta \theta}{\Delta t},$$
where $\Delta \theta$ is the angle through which the object has rotated in the time interval $\Delta t$. The instantaneous angular velocity is the limit of this ratio as $\Delta t$ approaches zero:
$$\omega=\lim _{\Delta t \rightarrow 0} \frac{\Delta \theta}{\Delta t} .$$

Angular velocity is generally specified in radians per second (rad/s). Note that all points in a rigid object rotate with the same angular velocity, since every position in the object moves through the same angle in the same time interval.

An object such as the wheel in Fig. 8-3 can rotate about a fixed axis either clockwise or counterclockwise. The direction can be specified with a + or - sign. The usual convention is to choose the angular displacement $\Delta \theta$ and angular velocity $\omega$ as positive when the wheel rotates counterclockwise. If the rotation is clockwise, then $\theta$ would decrease, so $\Delta \theta$ and $\omega$ would be negative.
${ }^{\dagger}$ Even for an angle as large as $15^{\circ}$, the error in making this estimate is only $1 \%$, but for larger angles the error increases rapidly. (The chord is the straight-line distance between the ends of the arc.)

200
CHAPTER 8 Rotational Motion

---

<!-- Page 201 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 20 لم

Angular acceleration (denoted by $\alpha$, the Greek lowercase letter alpha), in analogy to linear acceleration, is defined as the change in angular velocity divided by the time required to make this change. The average angular acceleration is defined as
$$\bar{\alpha}=\frac{\omega_{2}-\omega_{1}}{\Delta t}=\frac{\Delta \omega}{\Delta t},$$
where $\omega_{1}$ is the angular velocity initially, and $\omega_{2}$ is the angular velocity after a time interval $\Delta t$. Instantaneous angular acceleration is defined as the limit of this ratio as $\Delta t$ approaches zero:
$$\alpha=\lim _{\Delta t \rightarrow 0} \frac{\Delta \omega}{\Delta t}$$

Since $\omega$ is the same for all points of a rotating object, Eq. $8-3$ tells us that $\alpha$ also will be the same for all points. Thus, $\omega$ and $\alpha$ are properties of the rotating object as a whole. With $\omega$ measured in radians per second and $t$ in seconds, $\alpha$ has units of radians per second squared ( $\mathrm{rad} / \mathrm{s}^{2}$ ).

Each point or particle of a rotating object has, at any moment, a linear velocity $v$ and a linear acceleration $a$. We can now relate the linear quantities at each point, $v$ and $a$, to the angular quantities, $\omega$ and $\alpha$, for a rigid object rotating about a fixed axis. Consider a point P located a distance $r$ from the axis of rotation, as in Fig. 8-4. If the object rotates with angular velocity $\omega$, any point will have a linear velocity whose direction is tangent to its circular path. The magnitude of that point's linear velocity is $v=\Delta \ell / \Delta t$. From Eq. $8-1 \mathrm{~b}$, a change in rotation angle $\Delta \theta$ (in radians) is related to the linear distance traveled by $\Delta \ell=r \Delta \theta$. Hence
$$v=\frac{\Delta \ell}{\Delta t}=r \frac{\Delta \theta}{\Delta t}$$
or $($ since $\Delta \theta / \Delta t=\omega)$
$$v=r \omega$$

In this very useful Eq. 8-4, $r$ is the distance of a point from the rotation axis and $\omega$ is given in rad/s. Thus, although $\omega$ is the same for every point in the rotating object at any instant, the linear velocity $v$ is greater for points farther from the axis (Fig. 8-5). Note that Eq. 8-4 is valid both instantaneously and on average.

CONCEPTUAL EXAMPLE 8-3 Is the lion faster than the horse? On a rotating carousel or merry-go-round, one child sits on a horse near the outer edge and another child sits on a lion halfway out from the center. (a) Which child has the greater linear velocity? (b) Which child has the greater angular velocity?

RESPONSE (a) The linear velocity is the distance traveled divided by the time interval. In one rotation the child on the outer edge travels a longer distance than the child near the center, but the time interval is the same for both. Thus the child at the outer edge, on the horse, has the greater linear velocity.
(b) The angular velocity is the angle of rotation of the carousel as a whole divided by the time interval. For example, in one rotation both children rotate through the same angle ( $360^{\circ}$ or $2 \pi$ radians). The two children have the same angular velocity.

If the angular velocity of a rotating object changes, the object as a wholeand each point in it-has an angular acceleration. Each point also has a linear acceleration whose direction is tangent to that point's circular path. We use Eq. 8-4 ( $v=r \omega$ ) to see that the angular acceleration $\alpha$ is related to the tangential linear acceleration $a_{\tan }$ of a point in the rotating object by
$$a_{\tan }=\frac{\Delta v}{\Delta t}=r \frac{\Delta \omega}{\Delta t}$$
or (using Eq. 8-3)
$$a_{\tan }=r \alpha .$$

In this equation, $r$ is the radius of the circle in which the particle is moving, and the subscript "tan" in $a_{\tan }$ stands for "tangential."

FIGURE 8-4 A point P on a rotating wheel has a linear velocity $\overrightarrow{\mathbf{v}}$ at any moment.

FIGURE 8-5 A wheel rotating uniformly counterclockwise. Two points on the wheel, at distances $r_{\mathrm{A}}$ and $r_{\mathrm{B}}$ from the center, have the same angular velocity $\omega$ because they travel through the same angle $\theta$ in the same time interval. But the two points have different linear velocities because they travel different distances in the same time interval. Since $v=r \omega$ and $r_{\mathrm{B}}>r_{\mathrm{A}}$, then $v_{\mathrm{B}}>v_{\mathrm{A}}$.

SECTION 8-1 Angular Quantities
201

---

<!-- Page 202 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24
Page 202

FIGURE 8-6 On a rotating wheel whose angular speed is increasing, a point P has both tangential and radial (centripetal) components of linear acceleration. (See also Chapter 5.)

(a)

(b)

The total linear acceleration of a point in the rotating object is the vector sum of two components:
$$\overrightarrow{\mathbf{a}}=\overrightarrow{\mathbf{a}}_{\mathrm{tan}}+\overrightarrow{\mathbf{a}}_{\mathrm{R}},$$
where the radial component, $\overrightarrow{\mathbf{a}}_{\mathrm{R}}$, is the radial or "centripetal" acceleration and its direction is toward the center of the point's circular path; see Fig. 8-6. We saw in Chapter 5 (Eq. 5-1) that a particle moving in a circle of radius $r$ with linear speed $v$ has a radial acceleration $a_{\mathrm{R}}=v^{2} / r$. We can rewrite this in terms of $\omega$ using Eq. 8-4:
$$a_{\mathrm{R}}=\frac{v^{2}}{r}=\frac{(r \omega)^{2}}{r}=\omega^{2} r .$$

Thus the centripetal acceleration is greater the farther you are from the axis of rotation: the children farthest out on a carousel feel the greatest acceleration.

Equations 8-1, 8-4, 8-5, and 8-6 relate the angular quantities describing the rotation of an object to the linear quantities for each point of a rotating object. Table 8-1 summarizes these relationships.

\begin{table}
\captionsetup{labelformat=empty}
\caption{FIGURE 8-7 Examples 8-4 and 8-5. The total acceleration vector is $\overrightarrow{\mathbf{a}}=\overrightarrow{\mathbf{a}}_{\mathrm{tan}}+\overrightarrow{\mathbf{a}}_{\mathrm{R}}$, at $t=8.0 \mathrm{~s}$.}
\begin{tabular}{|l|l|l|l|}
\hline \multicolumn{4}{|l|}{TABLE 8-1 Linear and Rotational Quantities} \\
\hline Linear & Type & Rotational & Relation ${ }^{\ddagger}$ \\
\hline $x$ & displacement & $\theta$ & $x=r \theta$ \\
\hline $v$ & velocity & $\omega$ & $v=r \omega$ \\
\hline $a_{\tan }$ & acceleration & $\alpha$ & $a_{\tan }=r \alpha$ \\
\hline \multicolumn{4}{|l|}{${ }^{\ddagger}$ You must use radians.} \\
\hline
\end{tabular}
\end{table}

EXAMPLE 8-4 Angular and linear velocities. A carousel is initially at rest. At $t=0$ it is given a constant angular acceleration $\alpha=0.060 \mathrm{rad} / \mathrm{s}^{2}$, which increases its angular velocity for 8.0 s . At $t=8.0 \mathrm{~s}$, determine (a) the angular velocity of the carousel, and (b) the linear velocity of a child (Fig. 8-7a) located 2.5 m from the center, point P in Fig. 8-7b.

APPROACH The angular acceleration $\alpha$ is constant, so we can use $\alpha=\Delta \omega / \Delta t$ (Eq. 8-3a) to solve for $\omega$ after a time $t=8.0 \mathrm{~s}$. With this $\omega$, we determine the linear velocity using Eq. 8-4, $v=r \omega$.
SOLUTION (a) In Eq. 8-3a, $\bar{\alpha}=\left(\omega_{2}-\omega_{1}\right) / \Delta t$, we put $\Delta t=8.0 \mathrm{~s}, \bar{\alpha}= 0.060 \mathrm{rad} / \mathrm{s}^{2}$, and $\omega_{1}=0$. Solving for $\omega_{2}$, we get
$$\omega_{2}=\omega_{1}+\bar{\alpha} \Delta t=0+\left(0.060 \mathrm{rad} / \mathrm{s}^{2}\right)(8.0 \mathrm{~s})=0.48 \mathrm{rad} / \mathrm{s} .$$

During the 8.0 s time interval, the carousel accelerates from $\omega_{1}=0$ to $\omega_{2}=0.48 \mathrm{rad} / \mathrm{s}$.
(b) The linear velocity of the child with $r=2.5 \mathrm{~m}$ at time $t=8.0 \mathrm{~s}$ is found using Eq. 8-4:
$$v=r \omega=(2.5 \mathrm{~m})(0.48 \mathrm{rad} / \mathrm{s})=1.2 \mathrm{~m} / \mathrm{s} .$$

Note that the "rad" has been omitted in the final result because it is dimensionless (and only a reminder)-it is a ratio of two distances, Eq. 8-1a.

EXAMPLE 8-5 Angular and linear accelerations. For the child on the rotating carousel of Example 8-4, determine that child's (a) tangential (linear) acceleration, (b) centripetal acceleration, (c) total acceleration.
APPROACH We use the relations discussed above, Eqs. 8-5 and 8-6.
SOLUTION (a) The child's tangential acceleration is given by Eq. 8-5:
$$a_{\tan }=r \alpha=(2.5 \mathrm{~m})\left(0.060 \mathrm{rad} / \mathrm{s}^{2}\right)=0.15 \mathrm{~m} / \mathrm{s}^{2},$$
and it is the same throughout the $8.0-\mathrm{s}$ acceleration period.
(b) The child's centripetal acceleration at $t=8.0 \mathrm{~s}$ is given by Eq. 8-6:
$$a_{\mathrm{R}}=\frac{v^{2}}{r}=\frac{(1.2 \mathrm{~m} / \mathrm{s})^{2}}{(2.5 \mathrm{~m})}=0.58 \mathrm{~m} / \mathrm{s}^{2} .$$

202
CHAPTER 8 Rotational Motion

---

<!-- Page 203 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 $14: 24$
Page 2037
(c) The two components of linear acceleration calculated in parts (a) and (b) are perpendicular to each other. Thus the total linear acceleration at $t=8.0 \mathrm{~s}$ has magnitude
$$a=\sqrt{a_{\mathrm{tan}}^{2}+a_{\mathrm{R}}^{2}}=\sqrt{\left(0.15 \mathrm{~m} / \mathrm{s}^{2}\right)^{2}+\left(0.58 \mathrm{~m} / \mathrm{s}^{2}\right)^{2}}=0.60 \mathrm{~m} / \mathrm{s}^{2}$$

NOTE The linear acceleration at this chosen instant is mostly centripetal, and keeps the child moving in a circle with the carousel. The tangential component that speeds up the circular motion is smaller.
NOTE The direction of the linear acceleration (magnitude calculated above as $0.60 \mathrm{~m} / \mathrm{s}^{2}$ ) is at the angle $\theta$ shown in Fig. 8-7b:
$$\theta=\tan ^{-1}\left(\frac{a_{\mathrm{tan}}}{a_{\mathrm{R}}}\right)=\tan ^{-1}\left(\frac{0.15 \mathrm{~m} / \mathrm{s}^{2}}{0.58 \mathrm{~m} / \mathrm{s}^{2}}\right)=0.25 \mathrm{rad}$$
so $\theta \approx 15^{\circ}$.

We can relate the angular velocity $\omega$ to the frequency of rotation, $f$. The frequency is the number of complete revolutions (rev) per second, as we saw in Chapter 5. One revolution (of a wheel, say) corresponds to an angle of $2 \pi$ radians, and thus $1 \mathrm{rev} / \mathrm{s}=2 \pi \mathrm{rad} / \mathrm{s}$. Hence, in general, the frequency $f$ is related to the angular velocity $\omega$ by
$$f=\frac{\omega}{2 \pi}$$
or
$$\omega=2 \pi f$$

The unit for frequency, revolutions per second (rev/s), is given the special name the hertz (Hz). That is,
$$1 \mathrm{~Hz}=1 \mathrm{rev} / \mathrm{s}$$

Note that "revolution" is not really a unit, so we can also write $1 \mathrm{~Hz}=1 \mathrm{~s}^{-1}$.
The time required for one complete revolution is called the period $T$, and it is related to the frequency by
$$T=\frac{1}{f}$$

If a particle rotates at a frequency of three revolutions per second, then the period of each revolution is $\frac{1}{3} s$.

EXERCISE A In Example 8-4 we found that the carousel, after 8.0 s , rotates at an angular velocity $\omega=0.48 \mathrm{rad} / \mathrm{s}$, and continues to do so after $t=8.0 \mathrm{~s}$ because the acceleration ceased. What are the frequency and period of the carousel when rotating at this constant angular velocity $\omega=0.48 \mathrm{rad} / \mathrm{s}$ ?

8-2 Constant Angular Acceleration
In Chapter 2, we derived the useful kinematic equations (Eqs. 2-11) that relate acceleration, velocity, distance, and time for the special case of uniform linear acceleration. Those equations were derived from the definitions of linear velocity and acceleration, assuming constant acceleration. The definitions of angular velocity and angular acceleration (Eqs. 8-2 and 8-3) are just like those for their linear counterparts, except that $\theta$ replaces the linear displacement $x$, $\omega$ replaces $v$, and $\alpha$ replaces $a$. Therefore, the angular equations for constant angular acceleration will be analogous to Eqs. 2-11 with $x$ replaced by $\theta, v$ by $\omega$, and $a$ by $\alpha$, and they can be derived in exactly the same way.

SECTION 8-2 Constant Angular Acceleration
203

---

<!-- Page 204 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 $14: 24$
Page 204

We summarize these angular equations here, opposite their linear equivalents, Eqs. 2-11 (for simplicity we choose $\theta_{0}=0$ and $x_{0}=0$ at the initial time $t_{0}=0$ ):

Kinematic equations
for constant
angular acceleration
$\left[x_{0}=0, \theta_{0}=0\right]$

PHYSICS APPLIED
Centrifuge

\begin{tabular}{|l|l|l|}
\hline Angular & Linear & \multirow[b]{2}{*}{[constant $\alpha, a$ ] (8-9a)} \\
\hline $\omega=\omega_{0}+\alpha t$ & $v=v_{0}+a t$ & \\
\hline $\theta=\omega_{0} t+\frac{1}{2} \alpha t^{2}$ & $x=v_{0} t+\frac{1}{2} a t^{2}$ & [constant $\alpha, a$ ] (8-9b) \\
\hline $\omega^{2}=\omega_{0}^{2}+2 \alpha \theta$ & $v^{2}=v_{0}^{2}+2 a x$ & $[$ constant $\alpha, a]$ (8-9c) \\
\hline $\bar{\omega}=\frac{\omega+\omega_{0}}{2}$ & $\bar{v}=\frac{v+v_{0}}{2}$ & [constant $\alpha, a$ ] (8-9d) \\
\hline
\end{tabular}

Note that $\omega_{0}$ represents the angular velocity at $t_{0}=0$, whereas $\theta$ and $\omega$ represent the angular position and velocity, respectively, at time $t$. Since the angular acceleration is constant, $\alpha=\bar{\alpha}$.

EXAMPLE 8-6 Centrifuge acceleration. A centrifuge rotor is accelerated for 30 s from rest to $20,000 \mathrm{rpm}$ (revolutions per minute). (a) What is its average angular acceleration? ( $b$ ) Through how many revolutions has the centrifuge rotor turned during its acceleration period, assuming constant angular acceleration?
APPROACH To determine $\bar{\alpha}=\Delta \omega / \Delta t$, we need the initial and final angular velocities. For (b), we use Eqs. 8-9 (recall that one revolution corresponds to $\theta=2 \pi \mathrm{rad}$ ).
SOLUTION (a) The initial angular velocity is $\omega_{0}=0$. The final angular velocity is
$$\omega=2 \pi f=(2 \pi \mathrm{rad} / \mathrm{rev}) \frac{(20,000 \mathrm{rev} / \mathrm{min})}{(60 \mathrm{~s} / \mathrm{min})}=2100 \mathrm{rad} / \mathrm{s}$$

Then, since $\bar{\alpha}=\Delta \omega / \Delta t$ and $\Delta t=30 \mathrm{~s}$, we have
$$\bar{\alpha}=\frac{\omega-\omega_{0}}{\Delta t}=\frac{2100 \mathrm{rad} / \mathrm{s}-0}{30 \mathrm{~s}}=70 \mathrm{rad} / \mathrm{s}^{2}$$

That is, every second the rotor's angular velocity increases by $70 \mathrm{rad} / \mathrm{s}$, or by $(70 \mathrm{rad} / \mathrm{s})(1 \mathrm{rev} / 2 \pi \mathrm{rad})=11$ revolutions per second.
(b) To find $\theta$ we could use either Eq. 8-9b or 8-9c (or both to check our answer). The former gives
$$\theta=\omega_{0} t+\frac{1}{2} \alpha t^{2}=0+\frac{1}{2}\left(70 \mathrm{rad} / \mathrm{s}^{2}\right)(30 \mathrm{~s})^{2}=3.15 \times 10^{4} \mathrm{rad}$$
where we have kept an extra digit because this is an intermediate result. To find the total number of revolutions, we divide by $2 \pi \mathrm{rad} / \mathrm{rev}$ and obtain
$$\frac{3.15 \times 10^{4} \mathrm{rad}}{2 \pi \mathrm{rad} / \mathrm{rev}}=5.0 \times 10^{3} \mathrm{rev}$$

NOTE Let us calculate $\theta$ using Eq. 8-9c:
$$\theta=\frac{\omega^{2}-\omega_{0}^{2}}{2 \alpha}=\frac{(2100 \mathrm{rad} / \mathrm{s})^{2}-0}{2\left(70 \mathrm{rad} / \mathrm{s}^{2}\right)}=3.15 \times 10^{4} \mathrm{rad}$$
which checks our answer above from Eq. 8-9b perfectly.
8-3 Rolling Motion (Without Slipping)
The rolling motion of a ball or wheel is familiar in everyday life: a ball rolling across the floor, or the wheels and tires of a car or bicycle rolling along the pavement. Rolling without slipping depends on static friction between the rolling object and the ground. The friction is static because the rolling object's point of contact with the ground is at rest at each moment.

Rolling without slipping involves both rotation and translation. There is a simple relation between the linear speed $v$ of the axle and the angular velocity $\omega$ of the rotating wheel or sphere: namely, $v=r \omega$ (where $r$ is the radius) as we now show.

204
CHAPTER 8 Rotational Motion

---

<!-- Page 205 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 205

Figure 8-8a shows a wheel rolling to the right without slipping. At the instant shown, point P on the wheel is in contact with the ground and is momentarily at rest. (If P was not at rest, the wheel would be slipping.) The velocity of the axle at the wheel's center C is $\overrightarrow{\mathbf{v}}$. In Fig. 8-8b we have put ourselves in the reference frame of the wheel-that is, we are moving to the right with velocity $\overrightarrow{\mathbf{v}}$ relative to the ground. In this reference frame the axle C is at rest, whereas the ground and point P are moving to the left with velocity $-\overrightarrow{\mathbf{v}}$ as shown. In Fig. 8-8b we are seeing pure rotation. So we can use Eq. 8-4 to obtain $v=r \omega$, where $r$ is the radius of the wheel. This is the same $v$ as in Fig. 8-8a, so we see that the linear speed $v$ of the axle relative to the ground is related to the angular velocity $\omega$ of the wheel by
$$v=r \omega . \quad \text { [rolling without slipping] }$$

This relationship is valid only if there is no slipping.
EXAMPLE 8-7 Bicycle. A bicycle slows down uniformly from $v_{0}=8.40 \mathrm{~m} / \mathrm{s}$ to rest over a distance of 115 m , Fig. 8-9. Each wheel and tire has an overall diameter of 68.0 cm . Determine (a) the angular velocity of the wheels at the initial instant $(t=0)$; ( $b$ ) the total number of revolutions each wheel rotates before coming to rest; (c) the angular acceleration of the wheel; and (d) the time it took to come to a stop.
APPROACH We assume the bicycle wheels roll without slipping and the tire is in firm contact with the ground. The speed of the bike $v$ and the angular velocity of the wheels $\omega$ are related by $v=r \omega$. The bike slows down uniformly, so the angular acceleration is constant and we can use Eqs. 8-9.
SOLUTION (a) The initial angular velocity of the wheel, whose radius is 34.0 cm , is
$$\omega_{0}=\frac{v_{0}}{r}=\frac{8.40 \mathrm{~m} / \mathrm{s}}{0.340 \mathrm{~m}}=24.7 \mathrm{rad} / \mathrm{s} .$$
(b) In coming to a stop, the bike passes over 115 m of ground. The circumference of the wheel is $2 \pi r$, so each revolution of the wheel corresponds to a distance traveled of $2 \pi r=(2 \pi)(0.340 \mathrm{~m})$. Thus the number of revolutions the wheel makes in coming to a stop is
$$\frac{115 \mathrm{~m}}{2 \pi r}=\frac{115 \mathrm{~m}}{(2 \pi)(0.340 \mathrm{~m})}=53.8 \mathrm{rev}$$
(c) The angular acceleration of the wheel can be obtained from Eq. 8-9c, for which we set $\omega=0$ and $\omega_{0}=24.7 \mathrm{rad} / \mathrm{s}$. Because each revolution corresponds to $2 \pi$ radians of angle, then $\theta=2 \pi \mathrm{rad} / \mathrm{rev} \times 53.8 \mathrm{rev}$ ( $=338 \mathrm{rad}$ ) and
$$\alpha=\frac{\omega^{2}-\omega_{0}^{2}}{2 \theta}=\frac{0-(24.7 \mathrm{rad} / \mathrm{s})^{2}}{2(2 \pi \mathrm{rad} / \mathrm{rev})(53.8 \mathrm{rev})}=-0.902 \mathrm{rad} / \mathrm{s}^{2} .$$
(d) Equation 8-9a or b allows us to solve for the time. The first is easier:
$$t=\frac{\omega-\omega_{0}}{\alpha}=\frac{0-24.7 \mathrm{rad} / \mathrm{s}}{-0.902 \mathrm{rad} / \mathrm{s}^{2}}=27.4 \mathrm{~s} .$$

NOTE When the bike tire completes one revolution, the bike advances linearly a distance equal to the outer circumference ( $2 \pi r$ ) of the tire, as long as there is no slipping or sliding.

Bike as seen from the ground at $t=0$

FIGURE 8-8 (a) A wheel rolling to the right. Its center C moves with velocity $\overrightarrow{\mathbf{v}}$. Point P is at rest at the instant shown. (b) The same wheel as seen from a reference frame in which the axle of the wheel C is at rest-that is, we are moving to the right with velocity $\overrightarrow{\mathbf{v}}$ relative to the ground. Point P , which was at rest in (a), here in (b) is moving to the left with velocity $-\overrightarrow{\mathbf{v}}$ as shown. (See also Section 3-8 on relative velocity.) Thus $v=r \omega$.

SECTION 8-3 Rolling Motion (Without Slipping)
205

---

<!-- Page 206 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 206

FIGURE 8-10 Top view of a door. Applying the same force with different lever arms, $r_{\mathrm{A}}$ and $r_{\mathrm{B}}$. If $r_{\mathrm{A}}=3 r_{\mathrm{B}}$, then to create the same effect (angular acceleration), $F_{\mathrm{B}}$ needs to be three times $F_{\mathrm{A}}$.

FIGURE 8-11 (a) A plumber can exert greater torque using a wrench with a long lever arm. (b) A tire iron too can have a long lever arm.

FIGURE 8-12 (a) Forces acting at different angles at the doorknob. (b) The lever arm is defined as the perpendicular distance from the axis of rotation (the hinge) to the line of action of the force ( $r_{\mathrm{C}}$ for the force $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ ).

206

We have so far discussed rotational kinematics-the description of rotational motion in terms of angular position, angular velocity, and angular acceleration. Now we discuss the dynamics, or causes, of rotational motion. Just as we found analogies between linear and rotational motion for the description of motion, so rotational equivalents for dynamics exist as well.

To make an object start rotating about an axis clearly requires a force. But the direction of this force, and where it is applied, are also important. Take, for example, an ordinary situation such as the overhead view of the door in Fig. 8-10. If you apply a force $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ perpendicular to the door as shown, you will find that the greater the magnitude, $F_{\mathrm{A}}$, the more quickly the door opens. But now if you apply the same force at a point closer to the hinge-say, $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ in Fig. 8-10-the door will not open so quickly. The effect of the force is less: where the force acts, as well as its magnitude and direction, affects how quickly the door opens. Indeed, if only this one force acts, the angular acceleration of the door is proportional not only to the magnitude of the force, but is also directly proportional to the perpendicular distance from the axis of rotation to the line along which the force acts. This distance is called the lever arm, or moment arm, of the force, and is labeled $r_{\mathrm{A}}$ and $r_{\mathrm{B}}$ for the two forces in Fig. 8-10. Thus, if $r_{\mathrm{A}}$ in Fig. 8-10 is three times larger than $r_{\mathrm{B}}$, then the angular acceleration of the door will be three times as great, assuming that the magnitudes of the forces are the same. To say it another way, if $r_{\mathrm{A}}=3 r_{\mathrm{B}}$, then $F_{\mathrm{B}}$ must be three times as large as $F_{\mathrm{A}}$ to give the same angular acceleration. (Figure 8-11 shows two examples of tools whose long lever arms are very effective.)

The angular acceleration, then, is proportional to the product of the force times the lever arm. This product is called the moment of the force about the axis, or, more commonly, it is called the torque, and is represented by $\tau$ (Greek lowercase letter tau). Thus, the angular acceleration $\alpha$ of an object is directly proportional to the net applied torque $\tau$ :
```
\alpha \propto τ,
```

and we see that it is torque that gives rise to angular acceleration. This is the rotational analog of Newton's second law for linear motion, $a \propto F$.

We defined the lever arm as the perpendicular distance from the axis of rotation to the line of action of the force-that is, the distance which is perpendicular both to the axis of rotation and to an imaginary line drawn along the direction of the force. We do this to take into account the effect of forces acting at an angle. It is clear that a force applied at an angle, such as $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ in Fig. 8-12, will be less effective than the same magnitude force applied perpendicular to the door, such as $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ (Fig. 8-12a). And if you push on the end of the door so that the force is directed at the hinge (the axis of rotation), as indicated by $\overrightarrow{\mathbf{F}}_{\mathrm{D}}$, the door will not rotate at all.

The lever arm for a force such as $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ is found by drawing a line along the direction of $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ (this is the "line of action" of $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ ). Then we draw another line, perpendicular to this line of action, that goes to the axis of rotation and is perpendicular also to it. The length of this second line is the lever arm for $\overrightarrow{\mathbf{F}}_{C}$ and is labeled $r_{\mathrm{C}}$ in Fig. 8-12b. The lever arm for $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ is the full distance from the hinge to the doorknob, $r_{\mathrm{A}}$ (just as in Fig. 8-10). Thus $r_{\mathrm{C}}$ is much smaller than $r_{\mathrm{A}}$.

CHAPTER 8 Rotational Motion

(b)

---

<!-- Page 207 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 207

The magnitude of the torque associated with $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ is then $r_{\mathrm{C}} F_{\mathrm{C}}$. This short lever arm $r_{\mathrm{C}}$ and the corresponding smaller torque associated with $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ are consistent with the observation that $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ is less effective in accelerating the door than is $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ with its larger lever arm. When the lever arm is defined in this way, experiment shows that the relation $\alpha \propto \tau$ is valid in general. Notice in Fig. 8-12 that the line of action of the force $\overrightarrow{\mathbf{F}}_{\mathrm{D}}$ passes through the hinge, and hence its lever arm is zero. Consequently, zero torque is associated with $\overrightarrow{\mathbf{F}}_{\mathrm{D}}$ and it gives rise to no angular acceleration, in accord with everyday experience (you can't get a door to start moving by pushing directly at the hinge).

In general, then, we can write the magnitude of the torque about a given axis as
$$\tau=r_{\perp} F,$$
where $r_{\perp}$ is the lever arm, and the perpendicular symbol $(\perp)$ reminds us that we must use the distance from the axis of rotation that is perpendicular to the line of action of the force (Fig. 8-13a).

An equivalent way of determining the torque associated with a force is to resolve the force into components parallel and perpendicular to the line that connects the axis to the point of application of the force, as shown in Fig. 8-13b. The component $F_{| |}$exerts no torque since it is directed at the rotation axis (its lever arm is zero). Hence the torque will be equal to $F_{\perp}$ times the distance $r$ from the axis to the point of application of the force:
$$\tau=r F_{\perp} .$$

This gives the same result as Eq. $8-10$ a because $F_{\perp}=F \sin \theta$ and $r_{\perp}=r \sin \theta$. Thus
$$\tau=r F \sin \theta$$
in either case. [Note that $\theta$ is the angle between the directions of $\overrightarrow{\mathbf{F}}$ and $r$ (radial line from the axis to the point where $\overrightarrow{\mathbf{F}}$ acts).] We can use any of Eqs. 8-10 to calculate the torque, whichever is easiest.

Because torque is a distance times a force, it is measured in units of $\mathrm{m} \cdot \mathrm{N}$ in SI units, ${ }^{\dagger} \mathrm{cm} \cdot$ dyne in the cgs system, and $\mathrm{ft} \cdot \mathrm{lb}$ in the English system.

EXAMPLE 8-8 Biceps torque. The biceps muscle exerts a vertical force on the lower arm, bent as shown in Figs. 8-14a and b. For each case, calculate the torque about the axis of rotation through the elbow joint, assuming the muscle is attached 5.0 cm from the elbow as shown.

APPROACH The force is given, and the lever arm in (a) is given. In (b) we have to take into account the angle to get the lever arm.
SOLUTION (a) $F=700 \mathrm{~N}$ and $r_{\perp}=0.050 \mathrm{~m}$, so
$$\tau=r_{\perp} F=(0.050 \mathrm{~m})(700 \mathrm{~N})=35 \mathrm{~m} \cdot \mathrm{~N} .$$
(b) Because the arm is at an angle below the horizontal, the lever arm is shorter (Fig. 8-14c) than in part (a): $r_{\perp}=(0.050 \mathrm{~m})\left(\sin 60^{\circ}\right)$, where $\theta=60^{\circ}$ is the angle between $\overrightarrow{\mathbf{F}}$ and $r . F$ is still 700 N , so
$$\tau=(0.050 \mathrm{~m})(0.866)(700 \mathrm{~N})=30 \mathrm{~m} \cdot \mathrm{~N} .$$

The arm can exert less torque at this angle than when it is at $90^{\circ}$. Weight machines at gyms are often designed to take this variation with angle into account.
NOTE In (b), we could instead have used $\tau=r F_{\perp}$. As shown in Fig. 8-14d, $F_{\perp}=F \sin 60^{\circ}$. Then $\tau=r F_{\perp}=r F \sin \theta=(0.050 \mathrm{~m})(700 \mathrm{~N})(0.866)$ gives the same result.
${ }^{\dagger}$ Note that the units for torque are the same as those for energy. We write the unit for torque here as $\mathrm{m} \cdot \mathrm{N}$ (in SI) to distinguish it from energy ( $\mathrm{N} \cdot \mathrm{m}$ ) because the two quantities are very different. The special name joule ( $1 \mathrm{~J}=1 \mathrm{~N} \cdot \mathrm{~m}$ ) is used only for energy (and for work), never for torque.

FIGURE 8-13 Torque $=r_{\perp} F=r F_{\perp}$.

FIGURE 8-14 Example 8-8.

(b)

SECTION 8-4 Torque
207

---

<!-- Page 208 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 208

FIGURE 8-15 Exercise B.

FIGURE 8-16 Only the component of $\overrightarrow{\mathbf{F}}$ that acts in the plane perpendicular to the rotation axis, $\overrightarrow{\mathbf{F}}_{\perp}$, acts to accelerate the wheel about the axis. The component parallel to the axis, $\overrightarrow{\mathbf{F}}_{\|}$, would tend to move the axis itself, which we assume is held fixed.

FIGURE 8-17 A mass $m$ revolving in a circle of radius $r$ about a fixed point C .

EXERCISE B Two forces ( $F_{\mathrm{B}}=20 \mathrm{~N}$ and $F_{\mathrm{A}}=30 \mathrm{~N}$ ) are applied to a meter stick which can rotate about its left end, Fig. 8-15. Force $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ is applied perpendicularly at the midpoint. Which force exerts the greater torque: $F_{\mathrm{A}}, F_{\mathrm{B}}$, or both the same?

When more than one torque acts on an object, the angular acceleration $\alpha$ is found to be proportional to the net torque. If all the torques acting on an object tend to rotate it in the same direction about a fixed axis of rotation, the net torque is the sum of the torques. But if, say, one torque acts to rotate an object in one direction, and a second torque acts to rotate the object in the opposite direction, the net torque is the difference of the two torques. We normally assign a positive sign to torques that act to rotate the object counterclockwise (just as $\theta$ is usually positive counterclockwise), and a negative sign to torques that act to rotate the object clockwise.
* Forces that Act to Tilt the Axis

We have been considering only rotation about a fixed axis, and so we considered only forces that act in a plane perpendicular to the axis of rotation. If there is a force (or component of a force) acting parallel to the axis of rotation, it will tend to tilt the axis of rotation-the component $\overrightarrow{\mathbf{F}}_{\|}$in Fig. 8-16 is an example. Since we are assuming the axis remains fixed in direction, either there can be no such forces or else the axis must be mounted in bearings or hinges that hold the axis fixed. Thus, only a force, or component of a force ( $\overrightarrow{\mathbf{F}}_{\perp}$ in Fig. 8-16), in a plane perpendicular to the axis will give rise to rotational acceleration about the axis.

8-5 Rotational Dynamics; Torque and Rotational Inertia

We discussed in Section 8-4 that the angular acceleration $\alpha$ of a rotating object is proportional to the net torque $\tau$ applied to it:
$$\alpha \propto \sum \tau .$$

We write $\Sigma \tau$ to remind us that it is the net torque (sum of all torques acting on the object) that is proportional to $\alpha$. This corresponds to Newton's second law for translational motion, $a \propto \sum F$. In the translational case, the acceleration is not only proportional to the net force, but it is also inversely proportional to the inertia of the object, which we call its mass, $m$. Thus we wrote $a=\Sigma F / m$. But what plays the role of mass for the rotational case? That is what we now set out to determine. At the same time, we will see that the relation $\alpha \propto \Sigma \tau$ follows directly from Newton's second law, $\Sigma F=m a$.

We first examine a very simple case: a particle of mass $m$ revolving in a circle of radius $r$ at the end of a string or rod whose mass we can ignore compared to $m$ (Fig. 8-17). Consider a force $F$ that acts on the mass $m$ tangent to the circle as shown. The torque that gives rise to an angular acceleration is $\tau=r F$. If we use Newton's second law for linear quantities, $\Sigma F=m a$, and Eq. $8-5$ relating the angular acceleration to the tangential linear acceleration, $a_{\tan }=r \alpha$, then we have
$$\begin{aligned}
F & =m a \\
& =m r \alpha .
\end{aligned}$$

When we multiply both sides of this equation by $r$, we find that the torque
$$\tau=r F=r(m r \alpha),$$
or
$$\tau=m r^{2} \alpha .$$
[single particle] (8-11)
Here at last we have a direct relation between the angular acceleration and the applied torque $\tau$. The quantity $m r^{2}$ represents the rotational inertia of the particle and is called its moment of inertia.

208
CHAPTER 8 Rotational Motion

---

<!-- Page 209 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 209

Now let us consider a rotating rigid object, such as a wheel rotating about a fixed axis (an axle) through its center. We can think of the wheel as consisting of many particles located at various distances from the axis of rotation. We can apply Eq. 8-11 to each particle of the object, and then sum over all the particles. The sum of the various torques is the net torque, $\Sigma \tau$, so we obtain:
$$\Sigma \tau=\left(\Sigma m r^{2}\right) \alpha$$
where we factored out $\alpha$ because it is the same for all the particles of a rigid object. The sum $\sum m r^{2}$ represents the sum of the masses of each particle in the object multiplied by the square of the distance of that particle from the axis of rotation. If we assign each particle a number ( $1,2,3, \ldots$ ), then $\sum m r^{2}= m_{1} r_{1}^{2}+m_{2} r_{2}^{2}+m_{3} r_{3}^{2}+\cdots$. This sum is called the moment of inertia (or rotational inertia) I of the object:
$$I=\Sigma m r^{2}=m_{1} r_{1}^{2}+m_{2} r_{2}^{2}+\cdots .$$

Combining Eqs. 8-12 and 8-13, we can write
$$\sum \tau=I \alpha$$

This is the rotational equivalent of Newton's second law. It is valid for the rotation of a rigid object about a fixed axis. [It is also valid when the object is rotating while translating with acceleration, as long as $I$ and $\alpha$ are calculated about the center of mass of the object, and the rotation axis through the cm doesn't change direction. A ball rolling down a ramp is an example.]

We see that the moment of inertia, $I$, which is a measure of the rotational inertia of an object, plays the same role for rotational motion that mass does for translational motion. As can be seen from Eq. 8-13, the rotational inertia of a rigid object depends not only on its mass, but also on how that mass is distributed with respect to the axis. For example, a large-diameter cylinder will have greater rotational inertia than one of equal mass but smaller diameter, Fig. 8-18. The former will be harder to start rotating, and harder to stop. When the mass is concentrated farther from the axis of rotation, the rotational inertia is greater. For rotational motion, the mass of an object can not be considered as concentrated at its center of mass.

EXAMPLE 8-9 Two weights on a bar: different axis, different I. Two small "weights," of mass 5.0 kg and 7.0 kg , are mounted 4.0 m apart on a light rod (whose mass can be ignored), as shown in Fig. 8-19. Calculate the moment of inertia of the system (a) when rotated about an axis halfway between the weights, Fig. 8-19a, and (b) when rotated about an axis 0.50 m to the left of the $5.0-\mathrm{kg}$ mass (Fig. 8-19b).
APPROACH In each case, the moment of inertia of the system is found by summing over the two parts using Eq. 8-13.
SOLUTION (a) Both weights are the same distance, 2.0 m , from the axis of rotation. Thus
$$\begin{aligned}
I=\Sigma m r^{2} & =(5.0 \mathrm{~kg})(2.0 \mathrm{~m})^{2}+(7.0 \mathrm{~kg})(2.0 \mathrm{~m})^{2} \\
& =20 \mathrm{~kg} \cdot \mathrm{~m}^{2}+28 \mathrm{~kg} \cdot \mathrm{~m}^{2}=48 \mathrm{~kg} \cdot \mathrm{~m}^{2}
\end{aligned}$$
(b) The $5.0-\mathrm{kg}$ mass in now 0.50 m from the axis, and the $7.0-\mathrm{kg}$ mass is 4.50 m from the axis. Then
$$\begin{aligned}
I=\Sigma m r^{2} & =(5.0 \mathrm{~kg})(0.50 \mathrm{~m})^{2}+(7.0 \mathrm{~kg})(4.5 \mathrm{~m})^{2} \\
& =1.3 \mathrm{~kg} \cdot \mathrm{~m}^{2}+142 \mathrm{~kg} \cdot \mathrm{~m}^{2}=143 \mathrm{~kg} \cdot \mathrm{~m}^{2}
\end{aligned}$$

NOTE This Example illustrates two important points. First, the moment of inertia of a given system is different for different axes of rotation. Second, we see in part ( $b$ ) that mass close to the axis of rotation contributes little to the total moment of inertia; here, the $5.0-\mathrm{kg}$ object contributed less than $1 \%$ to the total.

NEWTON'S SECOND LAW FOR ROTATION

FIGURE 8-18 A large-diameter cylinder has greater rotational inertia than one of smaller diameter but equal mass.

FIGURE 8-19 Example 8-9: calculating the moment of inertia.

(a)

(b)
! CAUTION
I depends on axis of rotation and on distribution of mass

SECTION 8-5 Rotational Dynamics; Torque and Rotational Inertia
209

---

<!-- Page 210 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 210

\begin{table}
\captionsetup{labelformat=empty}
\caption{FIGURE 8-20 Moments of inertia for various objects of uniform composition, each with mass $M$.}
\begin{tabular}{|l|l|l|l|l|}
\hline & Object & Location of axis & & Moment of inertia \\
\hline (a) & Thin hoop, radius $R$ & Through center & & $M R^{2}$ \\
\hline (b) & Thin hoop, radius $R$ width $w$ & Through central diameter & & $\frac{1}{2} M R^{2}+\frac{1}{12} M w^{2}$ \\
\hline (c) & Solid cylinder, radius $R$ & Through center & & $\frac{1}{2} M R^{2}$ \\
\hline (d) & Hollow cylinder, inner radius $R_{1}$ outer radius $R_{2}$ & Through center & & $\frac{1}{2} M\left(R_{1}^{2}+R_{2}^{2}\right)$ \\
\hline (e) & Uniform sphere, radius $R$ & Through center & & $\frac{2}{5} M R^{2}$ \\
\hline (f) & Long uniform rod, length $\ell$ & Through center & & $\frac{1}{12} M \ell^{2}$ \\
\hline (g) & Long uniform rod, length $\ell$ & Through end & & $\frac{1}{3} M \ell^{2}$ \\
\hline (h) & Rectangular thin plate, length $\ell$, width $w$ & Through center & & $\frac{1}{12} M\left(\ell^{2}+w^{2}\right)$ \\
\hline
\end{tabular}
\end{table}

For most ordinary objects, the mass is distributed continuously, and the calculation of the moment of inertia, $\Sigma m r^{2}$, can be difficult. Expressions can, however, be worked out (using calculus) for the moments of inertia of regularly shaped objects in terms of the dimensions of the objects. Figure 8-20 gives these expressions for a number of solids rotated about the axes specified. The only one for which the result is obvious is that for the thin hoop or ring rotated about an axis passing through its center perpendicular to the plane of the hoop (Fig. 8-20a). For a hoop, all the mass is concentrated at the same distance from the axis, $R$. Thus $\sum m r^{2}=\left(\sum m\right) R^{2}=M R^{2}$, where $M$ is the total mass of the hoop. In Fig. 8-20, we use capital $R$ to refer to the outer radius of an object (in (d) also the inner radius).

When calculation is difficult, $I$ can be determined experimentally by measuring the angular acceleration $\alpha$ about a fixed axis due to a known net torque, $\Sigma \tau$, and applying Newton's second law, $I=\Sigma \tau / \alpha$, Eq. 8-14.
8-6 Solving Problems in Rotational Dynamics

When working with torque and angular acceleration (Eq. 8-14), it is important to use a consistent set of units, which in SI is: $\alpha$ in $\mathrm{rad} / \mathrm{s}^{2} ; \tau$ in $\mathrm{m} \cdot \mathrm{N}$; and the moment of inertia, $I$, in $\mathrm{kg} \cdot \mathrm{m}^{2}$.

210
CHAPTER 8 Rotational Motion

---

<!-- Page 211 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 211
VING

Rotational Motion
1. As always, draw a clear and complete diagram.
2. Choose the object or objects that will be the system to be studied.
3. Draw a free-body diagram for the object under consideration (or for each object, if more than one), showing all (and only) the forces acting on that object and exactly where they act, so you can determine the torque due to each. Gravity acts at the CM of the object (Section 7-8).
4. Identify the axis of rotation and determine the torques about it. Choose positive and negative
directions of rotation (counterclockwise and clockwise), and assign the correct sign to each torque.
5. Apply Newton's second law for rotation, $\Sigma \tau=I \alpha$. If the moment of inertia is not given, and it is not the unknown sought, you need to determine it first. Use consistent units, which in SI are: $\alpha$ in $\mathrm{rad} / \mathrm{s}^{2}$; $\tau$ in $\mathrm{m} \cdot \mathrm{N}$; and $I$ in $\mathrm{kg} \cdot \mathrm{m}^{2}$.
6. Also apply Newton's second law for translation, $\sum \overrightarrow{\mathbf{F}}=m \overrightarrow{\mathbf{a}}$, and other laws or principles as needed.
7. Solve the resulting equation(s) for the unknown(s).
8. Do a rough estimate to determine if your answer is reasonable.

EXAMPLE 8-10 A heavy pulley. A $15.0-\mathrm{N}$ force (represented by $\overrightarrow{\mathbf{F}}_{\mathrm{T}}$ ) is applied to a cord wrapped around a pulley of mass $M=4.00 \mathrm{~kg}$ and radius $R=33.0 \mathrm{~cm}$, Fig. 8-21. The pulley accelerates uniformly from rest to an angular speed of $30.0 \mathrm{rad} / \mathrm{s}$ in 3.00 s . If there is a frictional torque $\tau_{\mathrm{fr}}=1.10 \mathrm{~m} \cdot \mathrm{~N}$ at the axle, determine the moment of inertia of the pulley. The pulley rotates about its center.
APPROACH We follow the steps of the Problem Solving Strategy above. SOLUTION
1. Draw a diagram. The pulley and the attached cord are shown in Fig. 8-21.
2. Choose the system: the pulley.
3. Draw a free-body diagram. The force that the cord exerts on the pulley is shown as $\overrightarrow{\mathbf{F}}_{\mathrm{T}}$ in Fig. 8-21. The friction force acts all around the axle, retarding the motion, as suggested by $\overrightarrow{\mathbf{F}}_{\text {fr }}$ in Fig. 8-21. We are given only its torque, which is what we need. Two other forces could be included in the diagram: the force of gravity $m g$ down and whatever force keeps the axle in place (they balance each other). They do not contribute to the torque (their lever arms are zero) and so we omit them to keep our diagram simple.
4. Determine the torques. The cord exerts a force $\overrightarrow{\mathbf{F}}_{\mathrm{T}}$ that acts at the edge of the pulley, so its lever arm is $R$. The torque exerted by the cord equals $R F_{\mathrm{T}}$ and is counterclockwise, which we choose to be positive. The frictional torque is given as $\tau_{\mathrm{fr}}=1.10 \mathrm{~m} \cdot \mathrm{~N}$; it opposes the motion and is negative.
5. Apply Newton's second law for rotation. The net torque is
$$\Sigma \tau=R F_{\mathrm{T}}-\tau_{\mathrm{fr}}=(0.330 \mathrm{~m})(15.0 \mathrm{~N})-1.10 \mathrm{~m} \cdot \mathrm{~N}=3.85 \mathrm{~m} \cdot \mathrm{~N} .$$

The angular acceleration $\alpha$ is found from the given data that it takes 3.00 s to accelerate the pulley from rest to $\omega=30.0 \mathrm{rad} / \mathrm{s}$ :
$$\alpha=\frac{\Delta \omega}{\Delta t}=\frac{30.0 \mathrm{rad} / \mathrm{s}-0}{3.00 \mathrm{~s}}=10.0 \mathrm{rad} / \mathrm{s}^{2} .$$

Newton's second law, $\Sigma \tau=I \alpha$, can be solved for $I$ which is the unknown: $I=\Sigma \tau / \alpha$.
6. Other calculations: None needed.
7. Solve for unknowns. From Newton's second law,
$$I=\frac{\Sigma \tau}{\alpha}=\frac{3.85 \mathrm{~m} \cdot \mathrm{~N}}{10.0 \mathrm{rad} / \mathrm{s}^{2}}=0.385 \mathrm{~kg} \cdot \mathrm{~m}^{2}$$
8. Do a rough estimate. We can do a rough estimate of the moment of inertia by assuming the pulley is a uniform cylinder and using Fig. 8-20c:
$$I \approx \frac{1}{2} M R^{2}=\frac{1}{2}(4.00 \mathrm{~kg})(0.330 \mathrm{~m})^{2}=0.218 \mathrm{~kg} \cdot \mathrm{~m}^{2} .$$

This is the same order of magnitude as our result, but numerically somewhat less. This makes sense, though, because a pulley is not usually a uniform cylinder but instead has more of its mass concentrated toward the outside edge. Such a pulley would be expected to have a greater moment of inertia than a solid cylinder of equal mass. A thin hoop, Fig. 8-20a, ought to have a greater $I$ than our pulley, and indeed it does: $I=M R^{2}=0.436 \mathrm{~kg} \cdot \mathrm{~m}^{2}$.

FIGURE 8-21 Example 8-10.

PROBLEM SOLVING
Usefulness and power of rough estimates

SECTION 8-6
211

---

<!-- Page 212 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 21¿

Additional Example-a bit more challenging

FIGURE 8-22 Example 8-11. (a) Pulley and falling bucket of mass $m$. This is also the free-body diagram for the pulley. (b) Freebody diagram for the bucket.

212

EXAMPLE 8-11 Pulley and bucket. Consider again the pulley in Example 8-10. But instead of a constant 15.0-N force being exerted on the cord, we now have a bucket of weight $w=15.0 \mathrm{~N}$ (mass $m=w / g=1.53 \mathrm{~kg}$ ) hanging from the cord. See Fig. 8-22a. We assume the cord has negligible mass and does not stretch or slip on the pulley. Calculate the angular acceleration $\alpha$ of the pulley and the linear acceleration $a$ of the bucket. Assume the same frictional torque $\tau_{\mathrm{fr}}=1.10 \mathrm{~m} \cdot \mathrm{~N}$ acts. APPROACH This situation looks a lot like Example 8-10, Fig. 8-21. But there is a big difference: the tension in the cord is now an unknown, and it is no longer equal to the weight of the bucket if the bucket accelerates. Our system has two parts: the bucket, which can undergo translational motion (Fig. 8-22b is its freebody diagram); and the pulley. The pulley does not translate, but it can rotate. We apply the rotational version of Newton's second law to the pulley, $\Sigma \tau=I \alpha$, and the linear version to the bucket, $\Sigma F=m a$.
SOLUTION Let $F_{\mathrm{T}}$ be the tension in the cord. Then a force $F_{\mathrm{T}}$ acts at the edge of the pulley, and we apply Newton's second law, Eq. 8-14, for the rotation of the pulley:
$$I \alpha=\Sigma \tau=R F_{\mathrm{T}}-\tau_{\mathrm{fr}} .$$

Next we look at the (linear) motion of the bucket of mass $m$. Figure 8-22b, the free-body diagram for the bucket, shows that two forces act on the bucket: the force of gravity $m g$ acts downward, and the tension of the cord $F_{\mathrm{T}}$ pulls upward. Applying Newton's second law, $\Sigma F=m a$, for the bucket, we have (taking downward as positive):
$$m g-F_{\mathrm{T}}=m a .$$

[bucket]

Note that the tension $F_{\mathrm{T}}$, which is the force exerted on the edge of the pulley, is not equal to the weight of the bucket ( $=m g=15.0 \mathrm{~N}$ ). There must be a net force on the bucket if it is accelerating, so $F_{\mathrm{T}}<m g$. We can also see this from the last equation above, $F_{\mathrm{T}}=m g-m a$.

To obtain $\alpha$, we note that the tangential acceleration of a point on the edge of the pulley is the same as the acceleration of the bucket if the cord doesn't stretch or slip. Hence we can use Eq. 8-5, $a_{\mathrm{tan}}=a=R \alpha$. Substituting $F_{\mathrm{T}}=m g-m a=m g-m R \alpha$ into the first equation above (Newton's second law for rotation of the pulley), we obtain
$$I \alpha=\Sigma \tau=R F_{\mathrm{T}}-\tau_{\mathrm{fr}}=R(m g-m R \alpha)-\tau_{\mathrm{fr}}=m g R-m R^{2} \alpha-\tau_{\mathrm{fr}} .$$

The unknown $\alpha$ appears on the left and in the second term on the far right, so we bring that term to the left side and solve for $\alpha$ :
$$\alpha=\frac{m g R-\tau_{\mathrm{fr}}}{I+m R^{2}} .$$

The numerator ( $m g R-\tau_{\mathrm{fr}}$ ) is the net torque, and the denominator ( $I+m R^{2}$ ) is the total rotational inertia of the system. With $m g=15.0 \mathrm{~N}(m=1.53 \mathrm{~kg})$ and, from Example 8-10, $I=0.385 \mathrm{~kg} \cdot \mathrm{~m}^{2}$ and $\tau_{\mathrm{fr}}=1.10 \mathrm{~m} \cdot \mathrm{~N}$, then
$$\alpha=\frac{(15.0 \mathrm{~N})(0.330 \mathrm{~m})-1.10 \mathrm{~m} \cdot \mathrm{~N}}{0.385 \mathrm{~kg} \cdot \mathrm{~m}^{2}+(1.53 \mathrm{~kg})(0.330 \mathrm{~m})^{2}}=6.98 \mathrm{rad} / \mathrm{s}^{2} .$$

The angular acceleration is somewhat less in this case than the $10.0 \mathrm{rad} / \mathrm{s}^{2}$ of Example 8-10. Why? Because $F_{\mathrm{T}}(=m g-m a=15.0 \mathrm{~N}-m a)$ is less than the $15.0-\mathrm{N}$ force in Example 8-10. The linear acceleration of the bucket is
$$a=R \alpha=(0.330 \mathrm{~m})\left(6.98 \mathrm{rad} / \mathrm{s}^{2}\right)=2.30 \mathrm{~m} / \mathrm{s}^{2} .$$

NOTE The tension in the cord $F_{\mathrm{T}}$ is less than $m g$ because the bucket accelerates.
8-7 Rotational Kinetic Energy
The quantity $\frac{1}{2} m v^{2}$ is the kinetic energy of an object undergoing translational motion. An object rotating about an axis is said to have rotational kinetic energy. By analogy with translational kinetic energy, we might expect this to be given by the expression $\frac{1}{2} I \omega^{2}$, where $I$ is the moment of inertia of the object and $\omega$ is its angular velocity. We can indeed show that this is true.

CHAPTER 8

---

<!-- Page 213 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 21 ⇒

Consider any rigid rotating object as made up of many tiny particles, each of mass $m$. If we let $r$ represent the distance of any one particle from the axis of rotation, then its linear velocity is $v=r \omega$. The total kinetic energy of the whole object will be the sum of the kinetic energies of all its particles:
$$\begin{aligned}
\mathrm{KE}=\Sigma\left(\frac{1}{2} m v^{2}\right) & =\Sigma\left(\frac{1}{2} m r^{2} \omega^{2}\right) \\
& =\frac{1}{2}\left(\Sigma m r^{2}\right) \omega^{2}
\end{aligned}$$

We have factored out the $\frac{1}{2}$ and the $\omega^{2}$ since they are the same for every particle of a rigid object. Since $\Sigma m r^{2}=I$, the moment of inertia, we see that the kinetic energy of a rigid rotating object is
$$\text { rotational } \mathrm{KE}=\frac{1}{2} I \omega^{2}$$

The units are joules, as with all other forms of energy.
An object that rotates while its center of mass (CM) undergoes translational motion will have both translational and rotational kinetic energy. Equation 8-15 gives the rotational kinetic energy if the rotation axis is fixed. If the object is moving, such as a wheel rolling down a hill, this equation is still valid as long as the rotation axis is fixed in direction. Then the total kinetic energy is
$$\mathrm{KE}=\frac{1}{2} M v_{\mathrm{CM}}^{2}+\frac{1}{2} I_{\mathrm{CM}} \omega^{2},$$
where $v_{\mathrm{CM}}$ is the linear velocity of the center of mass, $I_{\mathrm{CM}}$ is the moment of inertia about an axis through the center of mass, $\omega$ is the angular velocity about this axis, and $M$ is the total mass of the object.

EXAMPLE 8-12 Sphere rolling down an incline. What will be the speed of a solid sphere of mass $M$ and radius $R$ when it reaches the bottom of an incline if it starts from rest at a vertical height $H$ and rolls without slipping? See Fig. 8-23. (Assume sufficient static friction so no slipping occurs: we will see shortly that static friction does no work.) Compare your result to that for an object sliding down a frictionless incline.
APPROACH We use the law of conservation of energy with gravitational potential energy, now including rotational kinetic energy as well as translational KE.
SOLUTION The total energy at any point a vertical distance $y$ above the base of the incline is
$$E=\frac{1}{2} M v^{2}+\frac{1}{2} I_{\mathrm{CM}} \omega^{2}+M g y,$$
where $v$ is the speed of the center of mass, and $M g y$ is the gravitational potential energy. Applying conservation of energy, we equate the total energy at the top ( $y=H, v=0, \omega=0$ ) to the total energy at the bottom ( $y=0$ ):
$$\begin{aligned}
E_{\mathrm{top}} & =E_{\mathrm{bottom}} \\
0+0+M g H & =\frac{1}{2} M v^{2}+\frac{1}{2} I_{\mathrm{CM}} \omega^{2}+0
\end{aligned} \text { [energy conservation] }$$

The moment of inertia of a solid sphere about an axis through its center of mass is $I_{\mathrm{CM}}=\frac{2}{5} M R^{2}$, Fig. 8-20e. Since the sphere rolls without slipping, we have $\omega=v / R$ (recall Fig.8-8). Hence
$$M g H=\frac{1}{2} M v^{2}+\frac{1}{2}\left(\frac{2}{5} M R^{2}\right)\left(\frac{v^{2}}{R^{2}}\right)$$

Canceling the $M$ 's and $R$ 's, we obtain
$$\left(\frac{1}{2}+\frac{1}{5}\right) v^{2}=g H$$
or
$$v=\sqrt{\frac{10}{7} g H}$$
[rolling sphere]
We can compare this result for the speed of a rolling sphere to that for an object sliding down a plane without rotating and without friction, $\frac{1}{2} m v^{2}=m g H$ (see our energy conservation equation above, removing the rotational term). For the sliding object, $v=\sqrt{2 g H}$, which is greater than our result for a rolling sphere ( $2>10 / 7$ ). An object sliding without friction or rotation transforms its initial potential energy entirely into translational kinetic energy (none into rotational kinetic energy), so the speed of its center of mass is greater.
NOTE Our result for the rolling sphere shows (perhaps surprisingly) that $v$ is independent of both the mass $M$ and the radius $R$ of the sphere.

FIGURE 8-23 A sphere rolling down a hill has both translational and rotational kinetic energy. Example 8-12.

PROBLEM SOLVING
Rotational energy adds to other forms of energy to get the total energy which is conserved

SECTION 8-7
213

---

<!-- Page 214 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 214

FIGURE 8-24 Example 8-13.

FIGURE 8-25 A sphere rolling to the right on a plane surface. The point in contact with the ground at any moment, point P , is momentarily at rest. Point A to the left of P is moving nearly vertically upward at the instant shown, and point B to the right is moving nearly vertically downward. An instant later, point B will touch the plane and be at rest momentarily. Thus no work is done by the force of static friction.

FIGURE 8-26 Torque $\tau=r F$ does work when rotating a wheel equal to $W=F \Delta \ell=F r \Delta \theta=\tau \Delta \theta$.

214
CHAPTER 8

CONCEPTUAL EXAMPLE 8-13 Which is fastest? Several objects roll without slipping down an incline of vertical height $H$, all starting from rest at the same moment. The objects are a thin hoop (or a plain wedding band), a spherical marble, a solid cylinder (a D-cell battery), and an empty soup can. In addition, a greased box slides down without friction. In what order do they reach the bottom of the incline?

RESPONSE We use conservation of energy with gravitational potential energy plus rotational and translational kinetic energy. The sliding box would be fastest because the potential energy loss $(M g H)$ is transformed completely into translational kinetic energy of the box, whereas for rolling objects the initial potential energy is shared between translational and rotational kinetic energies, and so the speed of the CM is less. For each of the rolling objects we can state that the decrease in potential energy equals the increase in translational plus rotational kinetic energy:
$$M g H=\frac{1}{2} M v^{2}+\frac{1}{2} I_{\mathrm{CM}} \omega^{2} .$$

For all our rolling objects, the moment of inertia $I_{\mathrm{CM}}$ is a numerical factor times the mass $M$ and the radius $R^{2}$ (Fig. 8-20). The mass $M$ is in each term, so the translational speed $v$ doesn't depend on $M$; nor does it depend on the radius $R$ since $\omega=v / R$, so $R^{2}$ cancels out for all the rolling objects. Thus the speed $v$ at the bottom of the incline depends only on that numerical factor in $I_{\mathrm{CM}}$ which expresses how the mass is distributed. The hoop, with all its mass concentrated at radius $R\left(I_{\mathrm{CM}}=M R^{2}\right)$, has the largest moment of inertia; hence it will have the lowest speed and will arrive at the bottom behind the D-cell ( $I_{\mathrm{CM}}=\frac{1}{2} M R^{2}$ ), which in turn will be behind the marble ( $I_{\mathrm{CM}}=\frac{2}{5} M R^{2}$ ). The empty can, which is mainly a hoop plus a thin disk, has most of its mass concentrated at $R$; so it will be a bit faster than the pure hoop but slower than the D-cell. See Fig. 8-24.
NOTE The rolling objects do not even have to have the same radius: the speed at the bottom does not depend on the object's mass $M$ or radius $R$, but only on the shape (and the height of the incline $H$ ).

If there had been little or no static friction between the rolling objects and the plane in these Examples, the round objects would have slid rather than rolled, or a combination of both. Static friction must be present to make a round object roll. We did not need to take friction into account in the energy equation for the rolling objects because it is static friction and does no work-the point of contact of a sphere at each instant does not slide, but moves perpendicular to the plane (first down and then up as shown in Fig. 8-25) as it rolls. Thus, no work is done by the static friction force because the force and the motion (displacement) are perpendicular. The reason the rolling objects in Examples 8-12 and 8-13 move down the slope more slowly than if they were sliding is not because friction slows them down. Rather, it is because some of the gravitional potential energy is converted to rotational kinetic energy, leaving less for the translational kinetic energy.

EXERCISE C Return to the Chapter-Opening Question, page 198, and answer it again now. Try to explain why you may have answered differently the first time.

Work Done by Torque
The work done on an object rotating about a fixed axis, such as the pulleys in Figs. 8-21 and 8-22, can be written using angular quantities. As shown in Fig. 8-26, a force $F$ exerting a torque $\tau=r F$ on a wheel does work $W=F \Delta \ell$ in rotating the wheel a small distance $\Delta \ell$ at the point of application of $\overrightarrow{\mathbf{F}}$. The wheel has rotated through a small angle $\Delta \theta=\Delta \ell / r$ (Eq. 8-1). Hence
$$W=F \Delta \ell=F r \Delta \theta .$$

Because $\tau=r F$, then
$$W=\tau \Delta \theta$$
is the work done by the torque $\tau$ when rotating the wheel through an angle $\Delta \theta$. Finally, power $P$ is the rate work is done:
$$P=W / \Delta t=\tau \Delta \theta / \Delta t=\tau \omega,$$
which is analogous to the translational version, $P=F v$ (see Eq. 6-18).

---

<!-- Page 215 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 215h

8-8 Angular Momentum and Its Conservation

Throughout this Chapter we have seen that if we use the appropriate angular variables, the kinematic and dynamic equations for rotational motion are analogous to those for ordinary linear motion. We saw in the previous Section, for example, that rotational kinetic energy can be written as $\frac{1}{2} I \omega^{2}$, which is analogous to the translational kinetic energy, $\frac{1}{2} m v^{2}$. In like manner, the linear momentum, $p=m v$, has a rotational analog. It is called angular momentum, $L$. For a symmetrical object rotating about a fixed axis through the cm, the angular momentum is
$$L=I \omega$$
where $I$ is the moment of inertia and $\omega$ is the angular velocity about the axis of rotation. The SI units for $L$ are $\mathrm{kg} \cdot \mathrm{m}^{2} / \mathrm{s}$, which has no special name.

We saw in Chapter 7 (Section 7-1) that Newton's second law can be written not only as $\Sigma F=m a$ but also more generally in terms of momentum (Eq. 7-2), $\Sigma F=\Delta p / \Delta t$. In a similar way, the rotational equivalent of Newton's second law, which we saw in Eq. 8-14 can be written as $\Sigma \tau=I \alpha$, can also be written in terms of angular momentum:
$$\Sigma \tau=\frac{\Delta L}{\Delta t},$$
where $\Sigma \tau$ is the net torque acting to rotate the object, and $\Delta L$ is the change in angular momentum in a time interval $\Delta t$. Equation $8-14, \Sigma \tau=I \alpha$, is a special case of Eq. 8-19 when the moment of inertia is constant. This can be seen as follows. If an object has angular velocity $\omega_{0}$ at time $t=0$, and angular velocity $\omega$ after a time interval $\Delta t$, then its angular acceleration (Eq. 8-3) is
$$\alpha=\frac{\Delta \omega}{\Delta t}=\frac{\omega-\omega_{0}}{\Delta t} .$$

Then from Eq. 8-19, we have
$$\Sigma \tau=\frac{\Delta L}{\Delta t}=\frac{I \omega-I \omega_{0}}{\Delta t}=\frac{I\left(\omega-\omega_{0}\right)}{\Delta t}=I \frac{\Delta \omega}{\Delta t}=I \alpha,$$
which is Eq. 8-14.
Angular momentum is an important concept in physics because, under certain conditions, it is a conserved quantity. We can see from Eq. 8-19 that if the net torque $\Sigma \tau$ on an object is zero, then $\Delta L / \Delta t$ equals zero. That is, $\Delta L=0$, so $L$ does not change. This is the law of conservation of angular momentum for a rotating object:

The total angular momentum of a rotating object remains constant if the net torque acting on it is zero.

NEWTON'S SECOND LAW
FOR ROTATION
CONSERVATION OF
ANGULAR MOMENTUM

The law of conservation of angular momentum is one of the great conservation laws of physics, along with those for energy and linear momentum.

When there is zero net torque acting on an object, and the object is rotating about a fixed axis or about an axis through its center of mass whose direction doesn't change, we can write
$$I \omega=I_{0} \omega_{0}=\text { constant. }$$
$I_{0}$ and $\omega_{0}$ are the moment of inertia and angular velocity, respectively, about that axis at some initial time ( $t=0$ ), and $I$ and $\omega$ are their values at some other time. The parts of the object may alter their positions relative to one another, so that $I$ changes. But then $\omega$ changes as well, so that the product $I \omega$ remains constant.

SECTION 8-8 Angular Momentum and Its Conservation
215

---

<!-- Page 216 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 216

FIGURE 8-27 A skater spinning on ice, illustrating conservation of angular momentum: (a) $I$ is large and $\omega$ is small; (b) $I$ is smaller so $\omega$ is larger.

FIGURE 8-28 A diver rotates faster when arms and legs are tucked in than when they are outstretched. Angular momentum is conserved.

FIGURE 8-29 Example 8-14.

Many interesting phenomena can be understood on the basis of conservation of angular momentum. Consider a skater doing a spin on the tips of her skates, Fig. 8-27. She rotates at a relatively low speed when her arms are outstretched; when she brings her arms in close to her body, she suddenly spins much faster. From the definition of moment of inertia, $I=\sum m r^{2}$, it is clear that when she pulls her arms in closer to the axis of rotation, $r$ is reduced for the arms so her moment of inertia is reduced. Since the angular momentum $I \omega$ remains constant (we ignore the small torque due to friction), if $I$ decreases, then the angular velocity $\omega$ must increase. If the skater reduces her moment of inertia by a factor of 2 , she will then rotate with twice the angular velocity.

EXERCISE D When a spinning figure skater pulls in her arms, her moment of inertia decreases; to conserve angular momentum, her angular velocity increases. Does her rotational kinetic energy also increase? If so, where does the energy come from?

A similar example is the diver shown in Fig. 8-28. The push as she leaves the board gives her an initial angular momentum about her center of mass. When she curls herself into the tuck position, she rotates quickly one or more times. She then stretches out again, increasing her moment of inertia which reduces the angular velocity to a small value, and then she enters the water. The change in moment of inertia from the straight position to the tuck position can be a factor of as much as $3 \frac{1}{2}$.

Note that for angular momentum to be conserved, the net torque must be zero; but the net force does not necessarily have to be zero. The net force on the diver in Fig. 8-28, for example, is not zero (gravity is acting), but the net torque about her CM is zero because the force of gravity acts at her center of mass.

EXAMPLE 8-14 Clutch. A simple clutch consists of two cylindrical plates that can be pressed together to connect two sections of an axle, as needed, in a piece of machinery. The two plates have masses $M_{\mathrm{A}}=6.0 \mathrm{~kg}$ and $M_{\mathrm{B}}=9.0 \mathrm{~kg}$, with equal radii $R=0.60 \mathrm{~m}$. They are initially separated (Fig. 8-29). Plate $M_{\mathrm{A}}$ is accelerated from rest to an angular velocity $\omega_{1}=7.2 \mathrm{rad} / \mathrm{s}$ in time $\Delta t=2.0 \mathrm{~s}$. Calculate ( $a$ ) the angular momentum of $M_{\mathrm{A}}$, and ( $b$ ) the torque required to accelerate $M_{\mathrm{A}}$ from rest to $\omega_{1}$. (c) Next, plate $M_{\mathrm{B}}$, initially at rest but free to rotate without friction, is placed in firm contact with freely rotating plate $M_{\mathrm{A}}$, and the two plates then both rotate at a constant angular velocity $\omega_{2}$, which is considerably less than $\omega_{1}$. Why does this happen, and what is $\omega_{2}$ ?
APPROACH We use angular momentum, $L=I \omega$ (Eq. 8-18), plus Newton's second law for rotation, Eq. 8-19.
SOLUTION (a) The angular momentum of $M_{\mathrm{A}}$, a cylinder, is
$$L_{\mathrm{A}}=I_{\mathrm{A}} \omega_{1}=\frac{1}{2} M_{\mathrm{A}} R^{2} \omega_{1}=\frac{1}{2}(6.0 \mathrm{~kg})(0.60 \mathrm{~m})^{2}(7.2 \mathrm{rad} / \mathrm{s})=7.8 \mathrm{~kg} \cdot \mathrm{~m}^{2} / \mathrm{s} .$$
(b) The plate started from rest so the torque, assumed constant, was
$$\tau=\frac{\Delta L}{\Delta t}=\frac{7.8 \mathrm{~kg} \cdot \mathrm{~m}^{2} / \mathrm{s}-0}{2.0 \mathrm{~s}}=3.9 \mathrm{~m} \cdot \mathrm{~N} .$$
(c) Initially, before contact, $M_{\mathrm{A}}$ is rotating at constant $\omega_{1}$ (we ignore friction). When plate B comes in contact, why is their joint rotation speed less? You might think in terms of the torque each exerts on the other upon contact. But quantitatively, it's easier to use conservation of angular momentum, Eq. 8-20, since no external torques are assumed to act. Thus
$$\begin{array}{l}
\text { angular momentum before }=\text { angular momentum after } \\
\qquad I_{\mathrm{A}} \omega_{1}=\left(I_{\mathrm{A}}+I_{\mathrm{B}}\right) \omega_{2}
\end{array}$$

Solving for $\omega_{2}$ we find (after cancelling factors of $R^{2}$ )
$$\omega_{2}=\left(\frac{I_{\mathrm{A}}}{I_{\mathrm{A}}+I_{\mathrm{B}}}\right) \omega_{1}=\left(\frac{M_{\mathrm{A}}}{M_{\mathrm{A}}+M_{\mathrm{B}}}\right) \omega_{1}=\left(\frac{6.0 \mathrm{~kg}}{15.0 \mathrm{~kg}}\right)(7.2 \mathrm{rad} / \mathrm{s})=2.9 \mathrm{rad} / \mathrm{s} .$$

216
CHAPTER 8 Rotational Motion

---

<!-- Page 217 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 217

EXAMPLE 8-15 ESTIMATE Neutron star. Astronomers detect stars that are rotating extremely rapidly, known as neutron stars. A neutron star is believed to form from the inner core of a larger star that collapsed, under its own gravitation, to a star of very small radius and very high density. Before collapse, suppose the core of such a star is the size of our Sun ( $R \approx 7 \times 10^{5} \mathrm{~km}$ ) with mass 2.0 times as great as the Sun, and is rotating at a frequency of 1.0 revolution every 100 days. If it were to undergo gravitational collapse to a neutron star of radius 10 km , what would its rotation frequency be? Assume the star is a uniform sphere at all times, and loses no mass.
APPROACH We assume the star is isolated (no external forces), so we can use conservation of angular momentum for this process.
SOLUTION From conservation of angular momentum, Eq. 8-20,
$$I_{1} \omega_{1}=I_{2} \omega_{2},$$
where the subscripts 1 and 2 refer to initial (normal star) and final (neutron star), respectively. Then, assuming no mass is lost in the process ( $M_{1}=M_{2}$ ),
$$\omega_{2}=\left(\frac{I_{1}}{I_{2}}\right) \omega_{1}=\left(\frac{\frac{2}{5} M_{1} R_{1}^{2}}{\frac{2}{5} M_{2} R_{2}^{2}}\right) \omega_{1}=\frac{R_{1}^{2}}{R_{2}^{2}} \omega_{1} .$$

The frequency $f=\omega / 2 \pi$, so
$$\begin{aligned}
f_{2}=\frac{\omega_{2}}{2 \pi} & =\frac{R_{1}^{2}}{R_{2}^{2}} f_{1} \\
& =\left(\frac{7 \times 10^{5} \mathrm{~km}}{10 \mathrm{~km}}\right)^{2}\left(\frac{1.0 \mathrm{rev}}{100 \mathrm{~d}(24 \mathrm{~h} / \mathrm{d})(3600 \mathrm{~s} / \mathrm{h})}\right) \approx 6 \times 10^{2} \mathrm{rev} / \mathrm{s},
\end{aligned}$$
which is 600 Hz or $(600 \mathrm{rev} / \mathrm{s})(60 \mathrm{~s} / \mathrm{min})=36,000 \mathrm{rpm}$.
8-9 Vector Nature of Angular Quantities

Up to now we have considered only the magnitudes of angular quantities such as $\omega, \alpha$, and $L$. But they have a vector aspect too, and now we consider the directions. In fact, we have to define the directions for rotational quantities. We consider first the angular velocity, $\overrightarrow{\boldsymbol{\omega}}$.

Consider the rotating wheel shown in Fig. 8-30a. The linear velocities of different particles of the wheel point in all different directions. The only unique direction in space associated with the rotation is along the axis of rotation, perpendicular to the actual motion. We therefore choose the axis of rotation to be the direction of the angular velocity vector, $\overrightarrow{\boldsymbol{\omega}}$. Actually, there is still an ambiguity since $\overrightarrow{\boldsymbol{\omega}}$ could point in either direction along the axis of rotation (up or down in Fig. 8-30a). The convention we use, called the right-hand rule, is this: when the fingers of the right hand are curled around the rotation axis and point in the direction of the rotation, then the thumb points in the direction of $\overrightarrow{\boldsymbol{\omega}}$. This is shown in Fig. 8-30b. Note that $\overrightarrow{\boldsymbol{\omega}}$ points in the direction a right-handed screw would move when turned in the direction of rotation. Thus, if the rotation of the wheel in Fig. 8-30a is counterclockwise, the direction of $\overrightarrow{\boldsymbol{\omega}}$ is upward as shown in Fig. 8-30b. If the wheel rotates clockwise, then $\overrightarrow{\boldsymbol{\omega}}$ points in the opposite direction, downward. Note that no part of the rotating object moves in the direction of $\overrightarrow{\boldsymbol{\omega}}$.

If the axis of rotation is fixed, then $\overrightarrow{\boldsymbol{\omega}}$ can change only in magnitude. Thus $\overrightarrow{\boldsymbol{\alpha}}=\Delta \overrightarrow{\boldsymbol{\omega}} / \Delta t$ must also point along the axis of rotation. If the rotation is counterclockwise as in Fig. 8-30a and the magnitude of $\omega$ is increasing, then $\overrightarrow{\boldsymbol{\alpha}}$ points upward; but if $\omega$ is decreasing (the wheel is slowing down), $\overrightarrow{\boldsymbol{\alpha}}$ points downward. If the rotation is clockwise, $\overrightarrow{\boldsymbol{\alpha}}$ points downward if $\omega$ is increasing, and $\overrightarrow{\boldsymbol{\alpha}}$ points upward if $\omega$ is decreasing.
PHYSICS APPLIED Neutron star

FIGURE 8-30 (a) Rotating wheel. (b) Right-hand rule for obtaining the direction of $\overrightarrow{\boldsymbol{\omega}}$.

*SECTION 8-9 Vector Nature of Angular Quantities
217

---

<!-- Page 218 -->

GIAN_PPA7_08_AP_198-229v4.2HR1.1.QXD 7/12/16 11:04 AM Page 218

FIGURE 8-30 (Repeated.)
(a) Rotating wheel. (b) Right-hand rule for obtaining the direction of $\overrightarrow{\boldsymbol{\omega}}$.

FIGURE 8-31 (a) A person standing on a circular platform, initially at rest, begins walking along the edge at speed $v$. The platform, mounted on nearly friction-free bearings, begins rotating in the opposite direction, so that (b) the total angular momentum remains zero ( $\overrightarrow{\mathbf{L}}_{\text {platform }}=-\overrightarrow{\mathbf{L}}_{\text {person }}$ ).

FIGURE 8-32 Example 8-16.

Angular momentum, like linear momentum, is a vector quantity. For a symmetrical object rotating about a symmetry axis (such as a wheel, cylinder, hoop, or sphere), we can write the vector angular momentum as
$$\overrightarrow{\mathbf{L}}=I \overrightarrow{\boldsymbol{\omega}} .$$

The angular velocity vector $\overrightarrow{\boldsymbol{\omega}}$ (and therefore also $\overrightarrow{\mathbf{L}}$ ) points along the axis of rotation in the direction given by the right-hand rule (Fig. 8-30b).

The vector nature of angular momentum can be used to explain a number of interesting (and sometimes surprising) phenomena. For example, consider a person standing at rest on a circular platform capable of rotating without friction about an axis through its center (that is, a simplified merry-go-round). If the person now starts to walk along the edge of the platform, Fig. 8-31a, the platform starts rotating in the opposite direction. Why? One explanation is that the person's foot exerts a force on the platform. Another explanation (and this is the most useful analysis here) is that this is an example of the conservation of angular momentum. If the person starts walking counterclockwise, the person's angular momentum will point upward along the axis of rotation (remember how we defined the direction of $\overrightarrow{\boldsymbol{\omega}}$ using the right-hand rule). The magnitude of the person's angular momentum will be $L=I \omega=\left(m r^{2}\right)(v / r)$, where $v$ is the person's speed (relative to the Earth, not to the platform), $r$ is his distance from the rotation axis, $m$ is his mass, and $m r^{2}$ is his moment of inertia if we consider him a particle (mass concentrated at one point, Eq. 8-11). The platform rotates in the opposite direction, so its angular momentum points downward. If the total angular momentum of the system is initially zero (person and platform at rest), it will remain zero after the person starts walking. That is, the upward angular momentum of the person just balances the oppositely directed downward angular momentum of the platform (Fig. 8-31b), so the total vector angular momentum remains zero. Even though the person exerts a force (and torque) on the platform, the platform exerts an equal and opposite torque on the person. So the net torque on the system of person plus platform is zero (ignoring friction), and the total angular momentum remains constant.

CONCEPTUAL EXAMPLE 8-16 Spinning bicycle wheel. Your physics teacher is holding a spinning bicycle wheel while he stands with feet fixed on a stationary frictionless turntable (Fig. 8-32). What will happen if the teacher suddenly flips the bicycle wheel over so that it is spinning in the opposite direction?

RESPONSE We consider the system of turntable, teacher, and bicycle wheel. The total angular momentum initially is $\overrightarrow{\mathbf{L}}$ vertically upward. That is also what the system's angular momentum must be afterward, since $\overrightarrow{\mathbf{L}}$ is conserved when there is no net torque. Thus, if the wheel's angular momentum after being flipped over is $-\overrightarrow{\mathbf{L}}$ downward, then the angular momentum of teacher plus turntable will have to be $+2 \overrightarrow{\mathbf{L}}$ upward. We can safely predict that the turntable (and teacher) will begin revolving in the same direction the wheel was spinning originally.

EXERCISE E In Example 8-16, what if he moves the axis only $90^{\circ}$ so it is horizontal? (a) The same direction and speed as above; (b) the same as above, but slower; (c) the opposite result.

EXERCISE F Suppose you are standing on the edge of a large freely rotating turntable. If you walk toward the center, ( $a$ ) the turntable slows down; ( $b$ ) the turntable speeds up; (c) its rotation speed is unchanged; (d) the turntable stops; (e) you need to know the walking speed to answer.

One final note: the motion of particles and objects in rotating frames of reference is extremely interesting, though a bit advanced and so is treated at the end of the book in Appendix C.

218
CHAPTER 8 Rotational Motion

---

<!-- Page 219 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 219
Summary

When a rigid object rotates about a fixed axis, each point of the object moves in a circular path. Lines drawn perpendicularly from the rotation axis to various points in the object all sweep out the same angle $\theta$ in any given time interval.

Angles are conventionally measured in radians, where one radian is the angle subtended by an arc whose length is equal to the radius, or
$$\begin{aligned}
2 \pi \mathrm{rad} & =360^{\circ} \\
1 \mathrm{rad} & \approx 57.3^{\circ} .
\end{aligned}$$

Angular velocity, $\omega$, is defined as the rate of change of angular position:
$$\omega=\frac{\Delta \theta}{\Delta t} .$$

All parts of a rigid object rotating about a fixed axis have the same angular velocity at any instant.

Angular acceleration, $\alpha$, is defined as the rate of change of angular velocity:
$$\alpha=\frac{\Delta \omega}{\Delta t} .$$

The linear velocity $v$ and acceleration $a$ of a point located a distance $r$ from the axis of rotation are related to $\omega$ and $\alpha$ by
$$\begin{aligned}
v & =r \omega, \\
a_{\tan } & =r \alpha, \\
a_{\mathrm{R}} & =\omega^{2} r,
\end{aligned}$$
where $a_{\mathrm{tan}}$ and $a_{\mathrm{R}}$ are the tangential and radial (centripetal) components of the linear acceleration, respectively.

The frequency $f$ is related to $\omega$ by
$$\omega=2 \pi f,$$
and to the period $T$ by
$$T=1 / f .$$

If a rigid object undergoes uniformly accelerated rotational motion ( $\alpha=$ constant), equations analogous to those for linear motion are valid:
$$\begin{aligned}
\omega & =\omega_{0}+\alpha t, & \theta & =\omega_{0} t+\frac{1}{2} \alpha t^{2}, \\
\omega^{2} & =\omega_{0}^{2}+2 \alpha \theta, & \bar{\omega} & =\frac{\omega+\omega_{0}}{2} .
\end{aligned}$$

The torque due to a force $\overrightarrow{\mathbf{F}}$ exerted on a rigid object is equal to
$$\tau=r_{\perp} F=r F_{\perp}=r F \sin \theta,$$
where $r_{\perp}$, called the lever arm, is the perpendicular distance from the axis of rotation to the line along which the force acts, and $\theta$ is the angle between $\overrightarrow{\mathbf{F}}$ and $r$.

The rotational equivalent of Newton's second law is
$$\sum \tau=I \alpha,$$
where $I=\Sigma m r^{2}$ is the moment of inertia of the object about the axis of rotation. I depends not only on the mass of the object but also on how the mass is distributed relative to the axis of rotation. For a uniform solid cylinder or sphere of radius $R$ and mass $M, I$ has the form $I=\frac{1}{2} M R^{2}$ or $\frac{2}{5} M R^{2}$, respectively (see Fig. 8-20).

The rotational kinetic energy of an object rotating about a fixed axis with angular velocity $\omega$ is
$$\mathrm{KE}=\frac{1}{2} I \omega^{2} .$$

For an object both translating and rotating, the total kinetic energy is the sum of the translational kinetic energy of the object's center of mass plus the rotational kinetic energy of the object about its center of mass:
$$\mathrm{KE}=\frac{1}{2} M v_{\mathrm{CM}}^{2}+\frac{1}{2} I_{\mathrm{CM}} \omega^{2}$$
as long as the rotation axis is fixed in direction.
The angular momentum $L$ of an object rotating about a fixed rotation axis is given by
$$L=I \omega .$$

Newton's second law, in terms of angular momentum, is
$$\Sigma \tau=\frac{\Delta L}{\Delta t} .$$

If the net torque on an object is zero, $\Delta L / \Delta t=0$, so $L=$ constant. This is the law of conservation of angular momentum for a rotating object.

The following Table summarizes angular (or rotational) quantities, comparing them to their translational analogs.

\begin{tabular}{|l|l|l|}
\hline Translation & Rotation & Connection \\
\hline $x$ & $\theta$ & $x=r \theta$ \\
\hline $v$ & $\omega$ & $v=r \omega$ \\
\hline $a$ & $\alpha$ & $a_{\tan }=r \alpha$ \\
\hline $m$ & I & $I=\Sigma m r^{2}$ \\
\hline F & $\tau$ & $\tau=r F \sin \theta$ \\
\hline $\mathrm{KE}=\frac{1}{2} m v^{2}$ & $\frac{1}{2} I \omega^{2}$ & \\
\hline $p=m v$ & $L=I \omega$ & \\
\hline $W=F d$ & $W=\tau \theta$ & \\
\hline $\Sigma F=m a$ & $\Sigma \tau=I \alpha$ & \\
\hline $\Sigma F=\frac{\Delta p}{\Delta t}$ & $\Sigma \tau=\frac{\Delta L}{\Delta t}$ & \\
\hline
\end{tabular}
[*Angular velocity, angular acceleration, and angular momentum are vectors. For a rigid object rotating about a fixed axis, the vectors $\overrightarrow{\boldsymbol{\omega}}, \overrightarrow{\boldsymbol{\alpha}}$, and $\overrightarrow{\mathbf{L}}$ point along the rotation axis. The direction of $\overrightarrow{\boldsymbol{\omega}}$ or $\overrightarrow{\mathbf{L}}$ is given by the right-hand rule.]

Summary
219

---

<!-- Page 220 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 $14: 24$
Page
220

Questions
1. A bicycle odometer (which counts revolutions and is calibrated to report distance traveled) is attached near the wheel axle and is calibrated for 27 -inch wheels. What happens if you use it on a bicycle with 24 -inch wheels?
2. Suppose a disk rotates at constant angular velocity. (a) Does a point on the rim have radial and/or tangential acceleration? (b) If the disk's angular velocity increases uniformly, does the point have radial and/or tangential acceleration? (c) For which cases would the magnitude of either component of linear acceleration change?
3. Can a small force ever exert a greater torque than a larger force? Explain.
4. Why is it more difficult to do a sit-up with your hands behind your head than when your arms are stretched out in front of you? A diagram may help you to answer this.
5. If the net force on a system is zero, is the net torque also zero? If the net torque on a system is zero, is the net force zero? Explain and give examples.
6. Mammals that depend on being able to run fast have slender lower legs with flesh and muscle concentrated high, close to the body (Fig. 8-33). On the basis of rotational dynamics, explain why this distribution of mass is advantageous.

FIGURE 8-33 Question 6. A gazelle.
7. This book has three symmetry axes through its center, all mutually perpendicular. The book's moment of inertia would be smallest about which of the three? Explain.
8. Can the mass of a rigid object be considered concentrated at its CM for rotational motion? Explain.
9. The moment of inertia of a rotating solid disk about an axis through its CM is $\frac{1}{2} M R^{2}$ (Fig. 8-20c). Suppose instead that a parallel axis of rotation passes through a point on the edge of the disk. Will the moment of inertia be the same, larger, or smaller? Explain why.
10. Two inclines have the same height but make different angles with the horizontal. The same steel ball rolls without slipping down each incline. On which incline will the speed of the ball at the bottom be greater? Explain.
11. Two spheres look identical and have the same mass. However, one is hollow and the other is solid. Describe an experiment to determine which is which.
12. A sphere and a cylinder have the same radius and the same mass. They start from rest at the top of an incline. (a) Which reaches the bottom first? (b)Which has the greater speed at the bottom? (c) Which has the greater total kinetic energy at the bottom? (d) Which has the greater rotational kinetic energy? Explain your answers.
13. Why do tightrope walkers (Fig. 8-34) carry a long, narrow rod?

FIGURE 8-34 Question 13.
14. We claim that momentum and angular momentum are conserved. Yet most moving or rotating objects eventually slow down and stop. Explain.
15. Can the diver of Fig. 8-28 do a somersault without having any initial rotation when she leaves the board? Explain.
16. When a motorcyclist leaves the ground on a jump and leaves the throttle on (so the rear wheel spins), why does the front of the cycle rise up?
17. A shortstop may leap into the air to catch a ball and throw it quickly. As he throws the ball, the upper part of his body rotates. If you look quickly you will notice that his hips and legs rotate in the opposite direction (Fig. 8-35). Explain.

FIGURE 8-35 Question 17. A shortstop in the air, throwing the ball.
*18. The angular velocity of a wheel rotating on a horizontal axle points west. In what direction is the linear velocity of a point on the top of the wheel? If the angular acceleration points east, describe the tangential linear acceleration of this point at the top of the wheel. Is the angular speed increasing or decreasing?
*19. In what direction is the Earth's angular velocity vector as it rotates daily about its axis, north or south?
*20. On the basis of the law of conservation of angular momentum, discuss why a helicopter must have more than one rotor (or propeller). Discuss one or more ways the second propeller can operate in order to keep the helicopter stable.

220
CHAPTER 8 Rotational Motion

---

<!-- Page 221 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 221.
MisConceptual Questions
1. Bonnie sits on the outer rim of a merry-go-round, and Jill sits midway between the center and the rim. The merry-go-round makes one complete revolution every 2 seconds. Jill's linear velocity is:
(a) the same as Bonnie's.
(b) twice Bonnie's.
(c) half of Bonnie's.
(d) one-quarter of Bonnie's.
(e) four times Bonnie's.
2. An object at rest begins to rotate with a constant angular acceleration. If this object rotates through an angle $\theta$ in time $t$, through what angle did it rotate in the time $\frac{1}{2} t$ ?
(a) $\frac{1}{2} \theta$.
(b) $\frac{1}{4} \theta$.
(c) $\theta$.
(d) $2 \theta$.
(e) $4 \theta$.
3. A car speedometer that is supposed to read the linear speed of the car uses a device that actually measures the angular speed of the tires. If larger-diameter tires are mounted on the car instead, how will that affect the speedometer reading? The speedometer
(a) will still read the speed accurately.
(b) will read low.
(c) will read high.
4. The solid dot shown in Fig. 8-36 is a pivot point. The board can rotate about the pivot. Which force shown exerts the largest magnitude torque on the board?
(a) 1000 N

FIGURE 8-36 MisConceptual Question 4.
5. Consider a force $F=80 \mathrm{~N}$ applied to a beam as shown in Fig. 8-37. The length of the beam is $\ell=5.0 \mathrm{~m}$, and $\theta=37^{\circ}$, so that $x=3.0 \mathrm{~m}$ and $y=4.0 \mathrm{~m}$. Of the following expressions, which ones give the correct torque produced by the force $\overrightarrow{\mathbf{F}}$ around point P ?
(a) 80 N .
(b) $(80 \mathrm{~N})(5.0 \mathrm{~m})$.
(c) $(80 \mathrm{~N})(5.0 \mathrm{~m})\left(\sin 37^{\circ}\right)$.
(d) $(80 \mathrm{~N})(4.0 \mathrm{~m})$.
(e) $(80 \mathrm{~N})(3.0 \mathrm{~m})$.
(f) $(48 \mathrm{~N})(5.0 \mathrm{~m})$.
(g) $(48 \mathrm{~N})(4.0 \mathrm{~m})\left(\sin 37^{\circ}\right)$.

FIGURE 8-37
MisConceptual Question 5.
6. Two spheres have the same radius and equal mass. One sphere is solid, and the other is hollow and made of a denser material. Which one has the bigger moment of inertia about an axis through its center?
(a) The solid one.
(b) The hollow one.
(c) Both the same.
7. Two wheels having the same radius and mass rotate at the same angular velocity (Fig. 8-38). One wheel is made with spokes so nearly all the mass is at the rim. The other is a solid disk. How do their rotational kinetic energies compare?
(a) They are nearly the same.
(b) The wheel with spokes has about twice the KE.
(c) The wheel with spokes has higher KE, but not twice as high.
(d) The solid wheel has about twice the KE.
(e) The solid wheel has higher KE, but not twice as high.

FIGURE 8-38
MisConceptual Question 7.
8. If you used 1000 J of energy to throw a ball, would it travel faster if you threw the ball (ignoring air resistance)
(a) so that it was also rotating?
(b) so that it wasn't rotating?
(c) It makes no difference.
9. A small solid sphere and a small thin hoop are rolling along a horizontal surface with the same translational speed when they encounter a $20^{\circ}$ rising slope. If these two objects roll up the slope without slipping, which will rise farther up the slope?
(a) The sphere.
(b) The hoop.
(c) Both the same.
(d) More information about the objects' mass and diameter is needed.
10. A small mass $m$ on a string is rotating without friction in a circle. The string is shortened by pulling it through the axis of rotation without any external torque, Fig. 8-39. What happens to the angular velocity of the object?
(a) It increases.
(b) It decreases.
(c) It remains the same.

FIGURE 8-39
MisConceptual
Questions 10 and 11.
11. A small mass $m$ on a string is rotating without friction in a circle. The string is shortened by pulling it through the axis of rotation without any external torque, Fig. 8-39. What happens to the tangential velocity of the object?
(a) It increases.
(b) It decreases.
(c) It remains the same.
12. If there were a great migration of people toward the Earth's equator, the length of the day would
(a) increase because of conservation of angular momentum.
(b) decrease because of conservation of angular momentum.
(c) decrease because of conservation of energy.
(d) increase because of conservation of energy.
(e) remain unaffected.
13. Suppose you are sitting on a rotating stool holding a $2-\mathrm{kg}$ mass in each outstretched hand. If you suddenly drop the masses, your angular velocity will
(a) increase.
(b) decrease.
(c) stay the same.

MisConceptual Questions
221

---

<!-- Page 222 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 222

For assigned homework and other learning materials, go to the MasteringPhysics website.
MP

Problems

8-1 Angular Quantities
1. (I) Express the following angles in radians: (a) $45.0^{\circ}$, (b) $60.0^{\circ}$, (c) $90.0^{\circ}$, (d) $360.0^{\circ}$, and (e) $445^{\circ}$. Give as numerical values and as fractions of $\pi$.
2. (I) The Sun subtends an angle of about $0.5^{\circ}$ to us on Earth, 150 million km away. Estimate the radius of the Sun.
3. (I) A laser beam is directed at the Moon, $380,000 \mathrm{~km}$ from Earth. The beam diverges at an angle $\theta$ (Fig. 8-40) of $1.4 \times 10^{-5} \mathrm{rad}$. What diameter spot will
4. (I) The blades in a blender rotate at a rate of 6500 rpm . When the motor is turned off during operation, the blades slow to rest in 4.0 s . What is the angular acceleration as the blades slow down?
5. (II) The platter of the hard drive of a computer rotates at 7200 rpm ( $\mathrm{rpm}=$ revolutions per minute $=\mathrm{rev} / \mathrm{min}$ ). (a) What is the angular velocity ( $\mathrm{rad} / \mathrm{s}$ ) of the platter? (b) If the reading head of the drive is located 3.00 cm from the rotation axis, what is the linear speed of the point on the platter just below it? (c) If a single bit requires $0.50 \mu \mathrm{~m}$ of length along the direction of motion, how many bits per second can the writing head write when it is 3.00 cm from the axis?
6. (II) A child rolls a ball on a level floor 3.5 m to another child. If the ball makes 12.0 revolutions, what is its diameter?
7. (II) (a) A grinding wheel 0.35 m in diameter rotates at 2200 rpm . Calculate its angular velocity in rad/s. (b) What are the linear speed and acceleration of a point on the edge of the grinding wheel?
8. (II) A bicycle with tires 68 cm in diameter travels 9.2 km . How many revolutions do the wheels make?
9. (II) Calculate the angular velocity (a) of a clock's second hand, (b) its minute hand, and (c) its hour hand. State in rad/s. (d) What is the angular acceleration in each case?
10. (II) A rotating merry-go-round makes one complete revolution in 4.0 s (Fig. 8-41). (a) What is the linear speed of a child seated 1.2 m from the center? (b) What is her acceleration (give components)?

FIGURE 8-41
Problem 10.
11. (II) What is the linear speed, due to the Earth's rotation, of a point (a) on the equator, (b) on the Arctic Circle (latitude $66.5^{\circ} \mathrm{N}$ ), and (c) at a latitude of $42.0^{\circ} \mathrm{N}$ ?
12. (II) Calculate the angular velocity of the Earth (a) in its orbit around the Sun, and (b) about its axis.
13. (II) How fast (in rpm) must a centrifuge rotate if a particle 8.0 cm from the axis of rotation is to experience an acceleration of $100,000 g$ 's?
14. (II) A 61-cm-diameter wheel accelerates uniformly about its center from 120 rpm to 280 rpm in 4.0 s . Determine (a) its angular acceleration, and (b) the radial and tangential components of the linear acceleration of a point on the edge of the wheel 2.0 s after it has started accelerating.
15. (II) In traveling to the Moon, astronauts aboard the Apollo spacecraft put the spacecraft into a slow rotation to distribute the Sun's energy evenly (so one side would not become too hot). At the start of their trip, they accelerated from no rotation to 1.0 revolution every minute during a 12 -min time interval. Think of the spacecraft as a cylinder with a diameter of 8.5 m rotating about its cylindrical axis. Determine ( $a$ ) the angular acceleration, and ( $b$ ) the radial and tangential components of the linear acceleration of a point on the skin of the ship 6.0 min after it started this acceleration.
16. (II) A turntable of radius $R_{1}$ is turned by a circular rubber roller of radius $R_{2}$ in contact with it at their outer edges. What is the ratio of their angular velocities, $\omega_{1} / \omega_{2}$ ?

8-2 and 8-3 Constant Angular Acceleration; Rolling
17. (I) An automobile engine slows down from 3500 rpm to 1200 rpm in 2.5 s . Calculate (a) its angular acceleration, assumed constant, and (b) the total number of revolutions the engine makes in this time.
18. (I) A centrifuge accelerates uniformly from rest to $15,000 \mathrm{rpm}$ in 240 s . Through how many revolutions did it turn in this time?
19. (I) Pilots can be tested for the stresses of flying high-speed jets in a whirling "human centrifuge," which takes 1.0 min to turn through 23 complete revolutions before reaching its final speed. (a) What was its angular acceleration (assumed constant), and (b) what was its final angular speed in rpm?
20. (II) A cooling fan is turned off when it is running at $850 \mathrm{rev} / \mathrm{min}$. It turns 1250 revolutions before it comes to a stop. (a) What was the fan's angular acceleration, assumed constant? (b) How long did it take the fan to come to a complete stop?
21. (II) A wheel 31 cm in diameter accelerates uniformly from 240 rpm to 360 rpm in 6.8 s . How far will a point on the edge of the wheel have traveled in this time?
22. (II) The tires of a car make 75 revolutions as the car reduces its speed uniformly from $95 \mathrm{~km} / \mathrm{h}$ to $55 \mathrm{~km} / \mathrm{h}$. The tires have a diameter of 0.80 m . (a) What was the angular acceleration of the tires? If the car continues to decelerate at this rate, (b) how much more time is required for it to stop, and (c) how far does it go?

222
CHAPTER 8 Rotational Motion

---

<!-- Page 223 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 22ʒ
23. (II) A small rubber wheel is used to drive a large pottery wheel. The two wheels are mounted so that their circular edges touch. The small wheel has a radius of 2.0 cm and accelerates at the rate of $7.2 \mathrm{rad} / \mathrm{s}^{2}$, and it is in contact with the pottery wheel (radius 27.0 cm ) without slipping. Calculate (a) the angular acceleration of the pottery wheel, and (b) the time it takes the pottery wheel to reach its required speed of 65 rpm .

8-4 Torque
24. (I) A $52-\mathrm{kg}$ person riding a bike puts all her weight on each pedal when climbing a hill. The pedals rotate in a circle of radius 17 cm . (a) What is the maximum torque she exerts? (b) How could she exert more torque?
25. (II) Calculate the net torque about the axle of the wheel shown in Fig. 8-42. Assume that a friction torque of $0.60 \mathrm{~m} \cdot \mathrm{~N}$ opposes the motion.

FIGURE 8-42 Problem 25.
26. (II) A person exerts a horizontal force of 42 N on the end of a door 96 cm wide. What is the magnitude of the torque if the force is exerted (a) perpendicular to the door and (b) at a $60.0^{\circ}$ angle to the face of the door?
27. (II) Two blocks, each of mass $m$, are attached to the ends of a massless rod which pivots as shown in Fig. 8-43. Initially the rod is held in the horizontal position and then released. Calculate the magnitude and direction of the net torque on this system when it is first released.

FIGURE 8-43 Problem 27.
28. (II) The bolts on the cylinder head of an engine require tightening to a torque of $95 \mathrm{~m} \cdot \mathrm{~N}$. If a wrench is 28 cm long, what force perpendicular to the wrench must the mechanic exert at its end? If the six-sided bolt head is 15 mm across (Fig. 8-44), estimate the force applied near each of the six points by a wrench.

FIGURE 8-44 Problem 28.
29. (II) Determine the net torque on the $2.0-\mathrm{m}$-long uniform beam shown in Fig. 8-45. All forces are shown. Calculate about (a) point C , the CM , and $(b)$ point P at one end.

FIGURE 8-45
Problem 29.

8-5 and 8-6 Rotational Dynamics
30. (I) Determine the moment of inertia of a $10.8-\mathrm{kg}$ sphere of radius 0.648 m when the axis of rotation is through its center.
31. (I) Estimate the moment of inertia of a bicycle wheel 67 cm in diameter. The rim and tire have a combined mass of 1.1 kg . The mass of the hub (at the center) can be ignored (why?).
32. (II) A merry-go-round accelerates from rest to $0.68 \mathrm{rad} / \mathrm{s}$ in 34 s . Assuming the merry-go-round is a uniform disk of radius 7.0 m and mass $31,000 \mathrm{~kg}$, calculate the net torque required to accelerate it.
33. (II) An oxygen molecule consists of two oxygen atoms whose total mass is $5.3 \times 10^{-26} \mathrm{~kg}$ and whose moment of inertia about an axis perpendicular to the line joining the two atoms, midway between them, is $1.9 \times 10^{-46} \mathrm{~kg} \cdot \mathrm{~m}^{2}$. From these data, estimate the effective distance between the atoms.
34. (II) A grinding wheel is a uniform cylinder with a radius of 8.50 cm and a mass of 0.380 kg . Calculate (a) its moment of inertia about its center, and ( $b$ ) the applied torque needed to accelerate it from rest to 1750 rpm in 5.00 s . Take into account a frictional torque that has been measured to slow down the wheel from 1500 rpm to rest in 55.0 s .
35. (II) The forearm in Fig. 8-46 accelerates a $3.6-\mathrm{kg}$ ball at $7.0 \mathrm{~m} / \mathrm{s}^{2}$ by means of the triceps muscle, as shown. Calculate (a) the torque needed, and (b) the force that must be exerted by the triceps muscle. Ignore the mass of the arm.
36. (II) Assume that a $1.00-\mathrm{kg}$ ball is thrown solely by the action of the forearm, which rotates about the elbow joint under the action of the triceps muscle, Fig. 8-46. The ball is accelerated uniformly from rest to $8.5 \mathrm{~m} / \mathrm{s}$ in 0.38 s , at which point it

FIGURE 8-46

Problems 35 and 36. is released. Calculate (a) the angular acceleration of the arm, and (b) the force required of the triceps muscle. Assume that the forearm has a mass of 3.7 kg and rotates like a uniform rod about an axis at its end.

Problems
223

---

<!-- Page 224 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 224
37. (II) A softball player swings a bat, accelerating it from rest to $2.6 \mathrm{rev} / \mathrm{s}$ in a time of 0.20 s . Approximate the bat as a $0.90-\mathrm{kg}$ uniform rod of length 0.95 m , and compute the torque the player applies to one end of it.
38. (II) A small 350 -gram ball on the end of a thin, light rod is rotated in a horizontal circle of radius 1.2 m . Calculate (a) the moment of inertia of the ball about the center of the circle, and (b) the torque needed to keep the ball rotating at constant angular velocity if air resistance exerts a force of 0.020 N on the ball. Ignore air resistance on the rod and its moment of inertia.
39. (II) Calculate the moment of inertia of the array of point objects shown in Fig. 8-47 about (a) the $y$ axis, and (b) the $x$ axis. Assume $m=2.2 \mathrm{~kg}, M=3.4 \mathrm{~kg}$, and the objects are wired together by very light, rigid pieces of wire. The array is rectangular and is split through the middle by the $x$ axis. (c) About which axis would it be harder to accelerate this array?

FIGURE 8-47 Problem 39.
40. (II) A potter is shaping a bowl on a potter's wheel rotating at constant angular velocity of $1.6 \mathrm{rev} / \mathrm{s}$ (Fig. 8-48). The friction force between her hands and the clay is 1.5 N total. (a) How large is her torque on the wheel, if the diameter of the bowl is 9.0 cm ? (b) How long would it take for the potter's wheel to stop if the only torque acting on it is due to the potter's hands? The moment of inertia of the wheel and the bowl is $0.11 \mathrm{~kg} \cdot \mathrm{~m}^{2}$.

FIGURE 8-48
Problem 40.
41. (II) A 0.72-m-diameter solid sphere can be rotated about an axis through its center by a torque of $10.8 \mathrm{~m} \cdot \mathrm{~N}$ which accelerates it uniformly from rest through a total of 160 revolutions in 15.0 s . What is the mass of the sphere?
42. (II) Let us treat a helicopter rotor blade as a long thin rod, as shown in Fig. 8-49. (a) If each of the three rotor helicopter blades is 3.75 m long and has a mass of 135 kg , calculate the moment of inertia of the three rotor blades about the axis of rotation. (b) How much torque must the motor apply to bring the blades from rest up to a speed of $6.0 \mathrm{rev} / \mathrm{s}$ in 8.0 s ?

FIGURE 8-49
Problem 42.
43. (II) To get a flat, uniform cylindrical satellite spinning at the correct rate, engineers fire four tangential rockets as shown in Fig. 8-50. Suppose that the satellite has a mass of 3600 kg and a radius of 4.0 m , and that the rockets each add a mass of 250 kg . What is the steady force required of each rocket if the satellite is to reach 32 rpm in 5.0 min , starting from rest?

FIGURE 8-50
Problem 43.
44. (III) Two blocks are connected by a light string passing over a pulley of radius 0.15 m and moment of inertia $I$. The blocks move (towards the right) with an acceleration of $1.00 \mathrm{~m} / \mathrm{s}^{2}$ along their frictionless inclines (see Fig. 8-51). (a) Draw free-body diagrams for each of the two blocks and the pulley. (b) Determine $F_{\mathrm{TA}}$ and $F_{\mathrm{TB}}$, the tensions in the two parts of the string. (c) Find the net torque acting on the pulley, and determine its moment of inertia, $I$.

FIGURE 8-51 Problem 44.

224
CHAPTER 8 Rotational Motion

---

<!-- Page 225 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 225
45. (III) An Atwood machine consists of two masses, $m_{\mathrm{A}}=65 \mathrm{~kg}$ and $m_{\mathrm{B}}=75 \mathrm{~kg}$, connected by a massless inelastic cord that passes over a pulley free to rotate, Fig. 8-52. The pulley is a solid cylinder of radius $R=0.45 \mathrm{~m}$ and mass 6.0 kg . (a) Determine the acceleration of each mass. (b) What \% error would be made if the moment of inertia of the pulley is ignored? [Hint: The tensions $F_{\mathrm{TA}}$ and $F_{\mathrm{TB}}$ are not equal. We discussed the Atwood machine in Example 4-13, assuming $I=0$ for the pulley.]

FIGURE 8-52 Problem 45.
Atwood machine.

8-7 Rotational Kinetic Energy
46. (I) An automobile engine develops a torque of $265 \mathrm{~m} \cdot \mathrm{~N}$ at 3350 rpm . What is the horsepower of the engine?
47. (I) A centrifuge rotor has a moment of inertia of $3.25 \times 10^{-2} \mathrm{~kg} \cdot \mathrm{~m}^{2}$. How much energy is required to bring it from rest to 8750 rpm ?
48. (I) Calculate the translational speed of a cylinder when it reaches the foot of an incline 7.20 m high. Assume it starts from rest and rolls without slipping.
49. (II) A bowling ball of mass 7.25 kg and radius 10.8 cm rolls without slipping down a lane at $3.10 \mathrm{~m} / \mathrm{s}$. Calculate its total kinetic energy.
50. (II) A merry-go-round has a mass of 1440 kg and a radius of 7.50 m . How much net work is required to accelerate it from rest to a rotation rate of 1.00 revolution per 7.00 s ? Assume it is a solid cylinder.
51. (II) A ball of radius $r$ rolls on the inside of a track of radius $R$ (see Fig. 8-53). If the ball starts from rest at the vertical edge of the track, what will be its speed when it reaches the lowest point of the track, rolling without slipping?

FIGURE 8-53 Problem 51.
52. (II) A rotating uniform cylindrical platform of mass 220 kg and radius 5.5 m slows down from $3.8 \mathrm{rev} / \mathrm{s}$ to rest in 16 s when the driving motor is disconnected. Estimate the power output of the motor (hp) required to maintain a steady speed of $3.8 \mathrm{rev} / \mathrm{s}$.
53. (II) Two masses, $m_{\mathrm{A}}=32.0 \mathrm{~kg}$ and $m_{\mathrm{B}}=38.0 \mathrm{~kg}$, are connected by a rope that hangs over a pulley (as in Fig. 8-54). The pulley is a uniform cylinder of radius $R=0.311 \mathrm{~m}$ and mass 3.1 kg . Initially $m_{\mathrm{A}}$ is on the ground and $m_{\mathrm{B}}$ rests 2.5 m above the ground. If the system is released, use conservation of energy to determine the speed of $m_{\mathrm{B}}$ just before it strikes the ground. Assume the pulley bearing is frictionless.

FIGURE 8-54
Problem 53.
54. (III) A $1.80-\mathrm{m}$-long pole is balanced vertically with its tip on the ground. It starts to fall and its lower end does not slip. What will be the speed of the upper end of the pole just before it hits the ground? [Hint: Use conservation of energy.]

8-8 Angular Momentum
55. (I) What is the angular momentum of a $0.270-\mathrm{kg}$ ball revolving on the end of a thin string in a circle of radius 1.35 m at an angular speed of $10.4 \mathrm{rad} / \mathrm{s}$ ?
56. (I) (a) What is the angular momentum of a $2.8-\mathrm{kg}$ uniform cylindrical grinding wheel of radius 28 cm when rotating at 1300 rpm ? (b) How much torque is required to stop it in 6.0 s?
57. (II) A person stands, hands at his side, on a platform that is rotating at a rate of $0.90 \mathrm{rev} / \mathrm{s}$. If he raises his arms to a horizontal position, Fig. 8-55, the speed of rotation decreases to $0.60 \mathrm{rev} / \mathrm{s}$. (a) Why? (b) By what factor has his moment of inertia changed?

FIGURE 8-55
Problem 57.

Problems
225

---

<!-- Page 226 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 226
58. (II) A nonrotating cylindrical disk of moment of inertia $I$ is dropped onto an identical disk rotating at angular speed $\omega$. Assuming no external torques, what is the final common angular speed of the two disks?
59. (II) A diver (such as the one shown in Fig. 8-28) can reduce her moment of inertia by a factor of about 3.5 when changing from the straight position to the tuck position. If she makes 2.0 rotations in 1.5 s when in the tuck position, what is her angular speed ( $\mathrm{rev} / \mathrm{s}$ ) when in the straight position?
60. (II) A figure skater can increase her spin rotation rate from an initial rate of 1.0 rev every 1.5 s to a final rate of $2.5 \mathrm{rev} / \mathrm{s}$. If her initial moment of inertia was $4.6 \mathrm{~kg} \cdot \mathrm{~m}^{2}$, what is her final moment of inertia? How does she physically accomplish this change?
61. (II) (a) What is the angular momentum of a figure skater spinning at $3.0 \mathrm{rev} / \mathrm{s}$ with arms in close to her body, assuming her to be a uniform cylinder with a height of 1.5 m , a radius of 15 cm , and a mass of 48 kg ? (b) How much torque is required to slow her to a stop in 4.0 s , assuming she does not move her arms?
62. (II) A person of mass 75 kg stands at the center of a rotating merry-go-round platform of radius 3.0 m and moment of inertia $820 \mathrm{~kg} \cdot \mathrm{~m}^{2}$. The platform rotates without friction with angular velocity $0.95 \mathrm{rad} / \mathrm{s}$. The person walks radially to the edge of the platform. (a) Calculate the angular velocity when the person reaches the edge. (b) Calculate the rotational kinetic energy of the system of platform plus person before and after the person's walk.
63. (II) A 4.2-m-diameter merry-go-round is rotating freely with an angular velocity of $0.80 \mathrm{rad} / \mathrm{s}$. Its total moment of inertia is $1360 \mathrm{~kg} \cdot \mathrm{~m}^{2}$. Four people standing on the ground, each of mass 65 kg , suddenly step onto the edge of the merry-go-round. (a) What is the angular velocity of the merry-go-round now? (b) What if the people were on it initially and then jumped off in a radial direction (relative to the merry-go-round)?
64. (II) A uniform horizontal rod of mass $M$ and length $\ell$ rotates with angular velocity $\omega$ about a vertical axis through its center. Attached to each end of the rod is a small mass $m$. Determine the angular momentum of the system about the axis.
65. (II) A uniform disk turns at $3.3 \mathrm{rev} / \mathrm{s}$ around a frictionless central axis. A nonrotating rod, of the same mass as the disk and length equal to the disk's diameter, is dropped onto the freely spinning disk, Fig. 8-56. They then turn together around the axis with their centers superposed. What is the angular frequency in rev/s of the combination?

FIGURE 8-56
Problem 65.
66. (III) An asteroid of mass $1.0 \times 10^{5} \mathrm{~kg}$, traveling at a speed of $35 \mathrm{~km} / \mathrm{s}$ relative to the Earth, hits the Earth at the equator tangentially, in the direction of Earth's rotation, and is embedded there. Use angular momentum to estimate the percent change in the angular speed of the Earth as a result of the collision.
*8-9 Angular Quantities as Vectors
67. (III) Suppose a $65-\mathrm{kg}$ person stands at the edge of a $5.5-\mathrm{m}$ diameter merry-go-round turntable that is mounted on frictionless bearings and has a moment of inertia of $1850 \mathrm{~kg} \cdot \mathrm{~m}^{2}$. The turntable is at rest initially, but when the person begins running at a speed of $4.0 \mathrm{~m} / \mathrm{s}$ (with respect to the turntable) around its edge, the turntable begins to rotate in the opposite direction. Calculate the angular velocity of the turntable.

General Problems
68. A merry-go-round with a moment of inertia equal to $1260 \mathrm{~kg} \cdot \mathrm{~m}^{2}$ and a radius of 2.5 m rotates with negligible friction at $1.70 \mathrm{rad} / \mathrm{s}$. A child initially standing still next to the merry-go-round jumps onto the edge of the platform straight toward the axis of rotation, causing the platform to slow to $1.35 \mathrm{rad} / \mathrm{s}$. What is her mass?
69. A $1.6-\mathrm{kg}$ grindstone in the shape of a uniform cylinder of radius 0.20 m acquires a rotational rate of $24 \mathrm{rev} / \mathrm{s}$ from rest over a $6.0-\mathrm{s}$ interval at constant angular acceleration. Calculate the torque delivered by the motor.
70. On a $12.0-\mathrm{cm}$-diameter audio compact disc (CD), digital bits of information are encoded sequentially along an outward spiraling path. The spiral starts at radius $R_{1}=2.5 \mathrm{~cm}$ and winds its way out to radius $R_{2}=5.8 \mathrm{~cm}$. To read the digital information, a CD player rotates the CD so that the player's readout laser scans along the spiral's sequence of bits at a constant linear speed of $1.25 \mathrm{~m} / \mathrm{s}$. Thus the player must accurately adjust the rotational frequency $f$ of the CD as the laser moves outward. Determine the values for $f$ (in units of rpm) when the laser is located at $R_{1}$ and when it is at $R_{2}$.

226
CHAPTER 8 Rotational Motion

---

<!-- Page 227 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 227
71. A hollow cylinder (hoop) is rolling on a horizontal surface at speed $v=3.0 \mathrm{~m} / \mathrm{s}$ when it reaches a $15^{\circ}$ incline. (a) How far up the incline will it go? (b) How long will it be on the incline before it arrives back at the bottom?
72. A cyclist accelerates from rest at a rate of $1.00 \mathrm{~m} / \mathrm{s}^{2}$. How fast will a point at the top of the rim of the tire (diameter $=68.0 \mathrm{~cm}$ ) be moving after 2.25 s ? [Hint: At any moment, the lowest point on the tire is in contact with the ground and is at rest-see Fig. 8-57.]
73. Suppose David puts a $0.60-\mathrm{kg}$ rock into a sling of length 1.5 m and begins whirling the rock in a nearly horizontal circle, accelerating it from rest to a rate of 75 rpm after 5.0 s . What is the torque required to achieve this feat, and where does the torque come from?
74. Bicycle gears: (a) How is the angular velocity $\omega_{\mathrm{R}}$ of the rear wheel of a bicycle related to the angular velocity $\omega_{\mathrm{F}}$ of the front sprocket and pedals? Let $N_{\mathrm{F}}$ and $N_{\mathrm{R}}$ be the number of teeth on the front and rear sprockets, respectively, Fig. 8-58. The teeth are spaced the same on both sprockets and the rear sprocket is firmly attached to the rear wheel. (b) Evaluate the ratio $\omega_{\mathrm{R}} / \omega_{\mathrm{F}}$ when the front and rear sprockets have 52 and 13 teeth, respectively, and (c) when they have 42 and 28 teeth.
76. Determine the angular momentum of the Earth (a) about its rotation axis (assume the Earth is a uniform sphere), and (b) in its orbit around the Sun (treat the Earth as a particle orbiting the Sun).
77. A wheel of mass $M$ has radius $R$. It is standing vertically on the floor, and we want to exert a horizontal force $F$ at its axle so that it will climb a step against which it rests (Fig. 8-60). The step has height $h$, where $h<R$. What minimum force $F$ is needed?

FIGURE 8-60 Problem 77.
78. If the coefficient of static friction between a car's tires and the pavement is 0.65 , calculate the minimum torque that must be applied to the $66-\mathrm{cm}$-diameter tire of a $1080-\mathrm{kg}$ automobile in order to "lay rubber" (make the wheels spin, slipping as the car accelerates). Assume each wheel supports an equal share of the weight.
79. A $4.00-\mathrm{kg}$ mass and a $3.00-\mathrm{kg}$ mass are attached to opposite ends of a very light $42.0-\mathrm{cm}$-long horizontal rod (Fig. 8-61). The system is rotating at angular speed $\omega=5.60 \mathrm{rad} / \mathrm{s}$ about a vertical axle at the center of the rod. Determine (a) the kinetic energy KE of the system, and (b) the net force on each mass.

FIGURE 8-61 Problem 79.
80. A small mass $m$ attached to the end of a string revolves in a circle on a frictionless tabletop. The other end of the string passes through a hole in the table (Fig. 8-62). Initially, the mass revolves with a speed $v_{1}=2.4 \mathrm{~m} / \mathrm{s}$ in a circle of radius $r_{1}=0.80 \mathrm{~m}$. The string is then pulled slowly through the hole so that the radius is reduced to $r_{2}=0.48 \mathrm{~m}$. What is the speed, $v_{2}$, of the mass now?

FIGURE 8-62
Problem 80.

General Problems
227

---

<!-- Page 228 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 14:24 Page 228
81. A uniform rod of mass $M$ and length $\ell$ can pivot freely (i.e., we ignore friction) about a hinge attached to a wall, as in Fig. 8-63. The rod is held horizontally and then released. At the moment of release, determine (a) the angular acceleration of the rod, and ( $b$ ) the linear acceleration of the tip of the rod. Assume that the force of gravity acts at the center of mass of the rod, as shown. [Hint: See Fig. 8-20g.]

FIGURE 8-63
Problem 81.
82. Suppose a star the size of our Sun, but with mass 8.0 times as great, were rotating at a speed of 1.0 revolution every 9.0 days. If it were to undergo gravitational collapse to a neutron star of radius 12 km , losing $\frac{3}{4}$ of its mass in the process, what would its rotation speed be? Assume the star is a uniform sphere at all times. Assume also that the thrownoff mass carries off either (a) no angular momentum, or (b) its proportional share $\left(\frac{3}{4}\right)$ of the initial angular momentum.
83. A large spool of rope rolls on the ground with the end of the rope lying on the top edge of the spool. A person grabs the end of the rope and walks a distance $\ell$, holding onto it, Fig. 8-64. The spool rolls behind the person without slipping. What length of rope unwinds from the spool? How far does the spool's center of mass move?

FIGURE 8-64
Problem 83.
84. The Moon orbits the Earth such that the same side always faces the Earth. Determine the ratio of the Moon's spin angular momentum (about its own axis) to its orbital angular momentum. (In the latter case, treat the Moon as a particle orbiting the Earth.)
85. Most of our Solar System's mass is contained in the Sun, and the planets possess almost all of the Solar System's angular momentum. This observation plays a key role in theories attempting to explain the formation of our Solar System. Estimate the fraction of the Solar System's total angular momentum that is possessed by planets using a simplified model which includes only the large outer planets with the most angular momentum. The central Sun (mass $1.99 \times 10^{30} \mathrm{~kg}$, radius $6.96 \times 10^{8} \mathrm{~m}$ ) spins about its axis once every 25 days and the planets Jupiter, Saturn, Uranus, and Neptune move in nearly circular orbits around the Sun with orbital data given in the Table below. Ignore each planet's spin about its own axis.

\begin{tabular}{lccc}
\hline Planet & \begin{tabular}{c} 
Mean Distance from \\
Sun $\left(\times \mathbf{1 0}^{\mathbf{6}} \mathbf{~ k m}\right)$
\end{tabular} & \begin{tabular}{c} 
Orbital Period \\
$($ Earth Years $)$
\end{tabular} & \begin{tabular}{c} 
Mass \\
$\left(\times \mathbf{1 0}^{\mathbf{2 5}} \mathbf{k g}\right)$
\end{tabular} \\
\hline Jupiter & 778 & 11.9 & 190 \\
Saturn & 1427 & 29.5 & 56.8 \\
Uranus & 2870 & 84.0 & 8.68 \\
Neptune & 4500 & 165 & 10.2 \\
\hline
\end{tabular}
86. Water drives a waterwheel (or turbine) of radius $R=3.0 \mathrm{~m}$ as shown in Fig. 8-65. The water enters at a speed $v_{1}=7.0 \mathrm{~m} / \mathrm{s}$ and exits from the waterwheel at a speed $v_{2}=3.8 \mathrm{~m} / \mathrm{s}$. (a) If 85 kg of water passes through per second, what is the rate at which the water delivers angular momentum to the waterwheel? (b) What is the torque the water applies to the waterwheel? (c) If the water causes the waterwheel to make one revolution every 5.5 s , how much power is delivered to the wheel?

FIGURE 8-65
Problem 86.

228
CHAPTER 8 Rotational Motion

---

<!-- Page 229 -->

GIAN_PPA7_GE_08_198-229v4.3HR2.QXD 29-08-2014 $14: 24$
Page 220

Search and Learn
1. Why are Eqs. 8-4 and 8-5 valid for radians but not for revolutions or degrees? Read Section 8-1 and follow the derivations carefully to find the answer.
2. Total solar eclipses can happen on Earth because of amazing coincidences: for one, the sometimes near-perfect alignment of Earth, Moon, and Sun. Secondly, using the information inside the front cover, calculate the angular diameters (in radians) of the Sun and the Moon, as seen from Earth, and then comment.
3. Two uniform spheres simultaneously start rolling (from rest) down an incline. One sphere has twice the radius and twice the mass of the other. (a) Which reaches the bottom of the incline first? (b) Which has the greater speed there? (c) Which has the greater total kinetic energy at the bottom? Explain your answers.
4. Model a figure skater's body as a solid cylinder and her arms as thin rods, making reasonable estimates for the dimensions. Then calculate the ratio of the angular speeds for a spinning skater with outstretched arms, and with arms held tightly against her body. Check Sections 8-5 and 8-8.
5. One possibility for a low-pollution automobile is for it to use energy stored in a heavy rotating flywheel. Suppose such a car has a total mass of 1100 kg , uses a uniform cylindrical flywheel of diameter 1.50 m and mass 270 kg , and should be able to travel 350 km without needing a flywheel "spinup." (a) Make reasonable assumptions (average frictional retarding force on car $=450 \mathrm{~N}$, thirty acceleration periods from rest to $95 \mathrm{~km} / \mathrm{h}$, equal uphill and downhill, and that energy can be put back into the flywheel as the car goes downhill), and estimate what total energy needs to be stored in the flywheel. (b) What is the angular velocity of the flywheel when it has a full "energy charge"? (c) About how long would it take a $150-\mathrm{hp}$ motor to give the flywheel a full energy charge before a trip?
*6. A person stands on a platform, initially at rest, that can rotate freely without friction. The moment of inertia of the person plus the platform is $I_{\mathrm{P}}$. The person holds a spinning bicycle wheel with its axis horizontal. The wheel has moment of inertia $I_{\mathrm{W}}$ and angular velocity $\omega_{\mathrm{W}}$. What will be the angular velocity $\omega_{\mathrm{P}}$ of the platform if the person moves the axis of the wheel so that it points (a) vertically upward, (b) at a $60^{\circ}$ angle to the vertical, (c) vertically downward? (d) What will $\omega_{\mathrm{P}}$ be if the person reaches up and stops the wheel in part (a)? See Sections 8-8 and 8-9.

ANSWERS TO EXERCISES

A: $f=0.076 \mathrm{~Hz} ; T=13 \mathrm{~s}$.
B: $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$.
C: (c).

D: Yes; she does work to pull in her arms.
E: (b).
F: (b).

Search and Learn
229

---

