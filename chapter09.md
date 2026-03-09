# Chapter 9: Static Equilibrium; Elasticity and Fracture

<!-- Page 230 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 230

Our whole built environment, from modern bridges to skyscrapers, has required architects and engineers to determine the forces and stresses within these structures. The object is to keep these structures standing, or "static"-that is, not in motion, especially not falling down.

The study of statics applies equally well to the human body, including balance, the forces in muscles, joints, and bones, and ultimately the possibility of fracture.

Static Equilibrium; Elasticity and Fracture

CONTENTS
9-1 The Conditions for Equilibrium
9-2 Solving Statics Problems
9-3 Applications to Muscles and Joints
9-4 Stability and Balance
9-5 Elasticity; Stress and Strain
9-6 Fracture
*9-7 Spanning a Space: Arches and Domes

CHAPTER-OPENING QUESTION-Guess now!
The diving board shown here is held by two supports at A and B . Which statement is true about the forces exerted on the diving board at $A$ and $B$ ?
(a) $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ is down, $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ is up, and $F_{\mathrm{B}}$ is larger than $F_{\mathrm{A}}$.
(b) Both forces are up and $F_{\mathrm{B}}$ is larger than $F_{\mathrm{A}}$.
(c) $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ is down, $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ is up, and $F_{\mathrm{A}}$ is larger than $F_{\mathrm{B}}$.
(d) Both forces are down and approximately equal.
(e) $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ is down, $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ is up, and they are equal.

In this Chapter, we will study a special case in mechanics-when the net force and the net torque on an object, or system of objects, are both zero. In this case both the linear acceleration and the angular acceleration of the object or system are zero. The object is either at rest, or its center of mass is moving at constant velocity. We will be concerned mainly with the first situation, in which the object or objects are all at rest, or static (= not moving).

The net force and the net torque can be zero, but this does not imply that no forces at all act on the objects. In fact it is virtually impossible to find an object on which no forces act. Just how and where these forces act can be very important, both for buildings and other structures, and in the human body.

Sometimes, as we shall see in this Chapter, the forces may be so great that the object is seriously deformed, or it may even fracture (break)-and avoiding such problems gives this field of statics even greater importance.

230

---

<!-- Page 231 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 23 」

Statics is concerned with the calculation of the forces acting on and within structures that are in equilibrium. Determination of these forces, which occupies us in the first part of this Chapter, then allows a determination of whether the structures can sustain the forces without significant deformation or fracture, subjects we discuss later in this Chapter. These techniques can be applied in a wide range of fields. Architects and engineers must be able to calculate the forces on the structural components of buildings, bridges, machines, vehicles, and other structures, since any material will buckle or break if too much force is applied (Fig. 9-1). In the human body a knowledge of the forces in muscles and joints is of great value for doctors, physical therapists, and athletes.

9-1 The Conditions for Equilibrium
Objects in daily life have at least one force acting on them (gravity). If they are at rest, then there must be other forces acting on them as well so that the net force is zero. A book at rest on a table, for example, has two forces acting on it, the downward force of gravity and the normal force the table exerts upward on it (Fig. 9-2). Because the book is at rest, Newton's second law tells us that the net force on it is zero. Thus the upward force exerted by the table on the book must be equal in magnitude to the force of gravity acting downward on the book. Such an object is said to be in equilibrium (Latin for "equal forces" or "balance") under the action of these two forces.

Do not confuse the two forces in Fig. 9-2 with the equal and opposite forces of Newton's third law, which act on different objects. In Fig.9-2, both forces act on the same object; and they happen to add up to zero.

EXAMPLE 9-1 Straightening teeth. The wire band shown in Fig. 9-3a has a tension $F_{\mathrm{T}}$ of 2.0 N along it. It therefore exerts forces of 2.0 N on the highlighted tooth (to which it is attached) in the two directions shown. Calculate the resultant force on the tooth due to the wire, $F_{\mathrm{R}}$.

FIGURE 9-1 Elevated walkway collapse in a Kansas City hotel in 1981. How a simple physics calculation could have prevented the tragic loss of over 100 lives is considered in Example 9-12.

FIGURE 9-2 The book is in equilibrium; the net force on it is zero.

FIGURE 9-3 Forces on a tooth.
Example 9-1.

APPROACH Since the two forces $F_{\mathrm{T}}$ are equal, their sum will be directed along the line that bisects the angle between them, which we have chosen to be the $y$ axis. The $x$ components of the two forces add up to zero.
SOLUTION The $y$ component of each force is $(2.0 \mathrm{~N})\left(\cos 70^{\circ}\right)=0.68 \mathrm{~N}$ : adding the two together, we get a resultant force $F_{\mathrm{R}}=1.4 \mathrm{~N}$ as shown in Fig. 9-3b. We assume that the tooth is in equilibrium because the gums exert a nearly equal magnitude force in the opposite direction. Actually that is not quite so
PHYSICS APPLIED
Braces for teeth since the objective is to move the tooth ever so slowly.
NOTE If the wire is firmly attached to the tooth, the tension to the right, say, can be made larger than that to the left, and the resultant force would correspondingly be directed more toward the right.

SECTION 9-1 The Conditions for Equilibrium
231

---

<!-- Page 232 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 232

FIGURE 9-4 Example 9-2.

FIGURE 9-5 Although the net force on it is zero, the ruler will move (rotate). A pair of equal forces acting in opposite directions but at different points on an object (as shown here) is referred to as a couple.

232
CHAPTER 9

The First Condition for Equilibrium
For an object to be at rest, Newton's second law tells us that the sum of the forces acting on it must add up to zero. Since force is a vector, the components of the net force must each be zero. Hence, a condition for equilibrium is that
$$\Sigma F_{x}=0, \quad \Sigma F_{y}=0, \quad \Sigma F_{z}=0 .$$

We will mainly be dealing with forces that act in a plane, so we usually need only the $x$ and $y$ components. We must remember that if a particular force component points along the negative $x$ or $y$ axis, it must have a negative sign. Equations $9-1$ represent the first condition for equilibrium.

We saw in Chapter 4 that to solve Problems involving forces, we need to draw a free-body diagram, indicating all the forces on a given object (see Section 4-7).

EXAMPLE 9-2 Chandelier cord tension. Calculate the tensions $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ in the two cords that are connected to the vertical cord supporting the $200-\mathrm{kg}$ chandelier in Fig. 9-4. Ignore the mass of the cords.
APPROACH We need a free-body diagram, but for which object? If we choose the chandelier, the cord supporting it must exert a force equal to the chandelier's weight $m g=(200 \mathrm{~kg})\left(9.80 \mathrm{~m} / \mathrm{s}^{2}\right)=1960 \mathrm{~N}$. But the forces $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ don't get involved. Instead, let us choose as our object the point where the three cords join (it could be a knot). The free-body diagram is then as shown in Fig. 9-4a. The three forces- $\overrightarrow{\mathbf{F}}_{\mathrm{A}}, \overrightarrow{\mathbf{F}}_{\mathrm{B}}$, and the tension in the vertical cord equal to the weight of the $200-\mathrm{kg}$ chandelier-act at this point where the three cords join. For this junction point we write $\Sigma F_{x}=0$ and $\Sigma F_{y}=0$, since the problem is laid out in two dimensions. The directions of $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ are known, since tension in a cord can only be along the cord-any other direction would cause the cord to bend, as already pointed out in Chapter 4. Thus, our unknowns are the magnitudes $F_{\mathrm{A}}$ and $F_{\mathrm{B}}$.
SOLUTION We first resolve $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ into its horizontal ( $x$ ) and vertical ( $y$ ) components. Although we don't know the value of $F_{\mathrm{A}}$, we can write (see Fig. 9-4b) $F_{\mathrm{A} x}=-F_{\mathrm{A}} \cos 60^{\circ}$ and $F_{\mathrm{A} y}=F_{\mathrm{A}} \sin 60^{\circ} . \overrightarrow{\mathbf{F}}_{\mathrm{B}}$ has only an $x$ component. In the vertical direction, we have the downward force exerted by the vertical cord equal to the weight of the chandelier $m g=(200 \mathrm{~kg})(g)$, and the vertical component of $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ upward:
$$\begin{aligned}
\Sigma F_{y} & =0 \\
F_{\mathrm{A}} \sin 60^{\circ}-(200 \mathrm{~kg})(g) & =0
\end{aligned}$$

SO
$$F_{\mathrm{A}}=\frac{(200 \mathrm{~kg}) g}{\sin 60^{\circ}}=(231 \mathrm{~kg}) g=(231 \mathrm{~kg})\left(9.80 \mathrm{~m} / \mathrm{s}^{2}\right)=2260 \mathrm{~N} .$$

In the horizontal direction, with $\Sigma F_{x}=0$,
$$\Sigma F_{x}=F_{\mathrm{B}}-F_{\mathrm{A}} \cos 60^{\circ}=0 .$$

Thus
$$F_{\mathrm{B}}=F_{\mathrm{A}} \cos 60^{\circ}=(231 \mathrm{~kg})(g)(0.500)=(115 \mathrm{~kg}) g=1130 \mathrm{~N} .$$

The magnitudes of $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ determine the strength of cord or wire that must be used. In this case, the cord must be able to support a mass of more than 230 kg .
NOTE We didn't insert the value of $g$, the acceleration due to gravity, until the end. In this way we found the magnitude of the force in terms of $g$ times the number of kilograms (which may be a more familiar quantity than newtons).

EXERCISE A In Example 9-2, $F_{\mathrm{A}}$ has to be greater than the chandelier's weight, $m g$. Why?

The Second Condition for Equilibrium
Although Eqs. 9-1 are a necessary condition for an object to be in equilibrium, they are not always a sufficient condition. Figure $9-5$ shows an object on which the net force is zero. Although the two forces labeled $\overrightarrow{\mathbf{F}}$ add up to give zero net force on the object, they do give rise to a net torque that will rotate the object.

---

<!-- Page 233 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 23\}

Referring to Eq. 8-14, $\Sigma \tau=I \alpha$, we see that if an object is to remain at rest, the net torque applied to it (calculated about any axis) must be zero. Thus we have the second condition for equilibrium: that the sum of the torques acting on an object, as calculated about any axis, must be zero:
$$\Sigma \tau=0 .$$

This condition will ensure that the angular acceleration, $\alpha$, about any axis will be zero. If the object is not rotating initially ( $\omega=0$ ), it will not start rotating. Equations $9-1$ and $9-2$ are the only requirements for an object to be in equilibrium.

We will mainly consider cases in which the forces all act in a plane (we call it the $x y$ plane). In such cases the torque is calculated about an axis that is perpendicular to the $x y$ plane. The choice of this axis is arbitrary. If the object is at rest, then $\Sigma \tau=0$ is valid about any axis. Therefore we can choose any axis that makes our calculation easier. Once the axis is chosen, all torques must be calculated about that axis.

CONCEPTUAL EXAMPLE 9-3 A lever. The bar in Fig. 9-6 is being used as a lever to pry up a large rock. The small rock acts as a fulcrum (pivot point). The force $F_{\mathrm{P}}$ required at the long end of the bar can be quite a bit smaller than the rock's weight $m g$, since it is the torques that balance in the rotation about the fulcrum. If, however, the leverage isn't sufficient, and the large rock isn't budged, what are two ways to increase the lever arm?

RESPONSE One way is to increase the lever arm of the force $F_{\mathrm{p}}$ by slipping a pipe over the end of the bar and thereby pushing with a longer lever arm. A second way is to move the fulcrum closer to the large rock. This may change the long lever arm $R$ only a little, but it changes the short lever arm $r$ by a substantial fraction and therefore changes the ratio of $R / r$ dramatically. In order to pry the rock, the torque due to $F_{\mathrm{P}}$ must at least balance the torque due to $m g$; that is, $m g r=F_{\mathrm{P}} R$ and
$$\frac{r}{R}=\frac{F_{\mathrm{P}}}{m g} .$$

With $r$ smaller, the weight $m g$ can be balanced with less force $F_{\mathrm{P}}$. The ratio $R / r$ is the mechanical advantage of the system. A lever is a "simple machine." We discussed another simple machine, the pulley, in Chapter 4, Example 4-14.

EXERCISE B For simplicity, we wrote the equation in Example 9-3 as if the lever were perpendicular to the forces. Would the equation be valid even for a lever at an angle as shown in Fig. 9-6?

9-2 Solving Statics Problems
The subject of statics is important because it allows us to calculate certain forces on (or within) a structure when some of the forces on it are already known. We will mainly consider situations in which all the forces act in a plane, so we can have two force equations ( $x$ and $y$ components) and one torque equation, for a total of three equations. Of course, you do not have to use all three equations if they are not needed. When using a torque equation, a torque that tends to rotate the object counterclockwise is usually considered positive, whereas a torque that tends to rotate it clockwise is considered negative. (But the opposite convention would be OK too.)

One of the forces that acts on objects is the force of gravity. As we discussed in Section 7-8, we can consider the force of gravity on an object as acting at its center of gravity (CG) or center of mass (CM), which for practical purposes are the same point. For uniform symmetrically shaped objects, the CG is at the geometric center. For more complicated objects, the CG can be determined as discussed in Section 7-8.
CAUTION

Axis choice for $\Sigma \tau=0$ is arbitrary. All torques must be calculated about the same axis.

PHYSICS APPLIED
The lever

FIGURE 9-6 Example 9-3. A lever can "multiply" your force.

PROBLEM SOLVING
$\tau>0$ counterclockwise
$\tau<0$ clockwise

SECTION 9-2 Solving Statics Problems
233

---

<!-- Page 234 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 23 At

There is no single technique for attacking statics problems, but the following procedure may be helpful.
G

Statics
1. Choose one object at a time for consideration. Make a careful free-body diagram by showing all the forces acting on that object, including gravity, and the points at which these forces act. If you aren't sure of the direction of a force, choose a direction; if the actual direction of the force (or component of a force) is opposite, your eventual calculation will give a result with a minus sign.
2. Choose a convenient coordinate system, and resolve the forces into their components.
3. Using letters to represent unknowns, write down the equilibrium equations for the forces:
$$\Sigma F_{x}=0$$
and
$$\Sigma F_{y}=0$$
assuming all the forces act in a plane.
4. For the torque equation,
$$\Sigma \tau=0$$
choose any axis perpendicular to the $x y$ plane that might make the calculation easier. (For example, you can reduce the number of unknowns in the resulting equation by choosing the axis so that one of the unknown forces acts through that axis; then this force will have zero lever arm and produce zero torque, and so won't appear in the torque equation.) Pay careful attention to determining the lever arm for each force correctly. Give each torque a + or - sign to indicate torque direction. For example, if torques tending to rotate the object counterclockwise are positive, then those tending to rotate it clockwise are negative.
5. Solve these equations for the unknowns. Three equations allow a maximum of three unknowns to be solved for. They can be forces, distances, or even angles.

PHYSICS APPLIED
Balancing a seesaw

EXAMPLE 9-4 Balancing a seesaw. A board of mass $M=4.0 \mathrm{~kg}$ serves as a seesaw for two children, as shown in Fig. 9-7a. Child A has a mass of 30 kg and sits 2.5 m from the pivot point, P (his center of gravity is 2.5 m from the pivot). At what distance $x$ from the pivot must child B , of mass 25 kg , place herself to balance the seesaw? Assume the board is uniform and centered over the pivot.
APPROACH We follow the steps of the Problem Solving Strategy above. SOLUTION
1. Free-body diagram. We choose the board as our object, and assume it is horizontal. Its free-body diagram is shown in Fig. 9-7b. The forces acting on the board are the forces exerted downward on it by each child, $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$, the upward force exerted by the pivot $\overrightarrow{\mathbf{F}}_{\mathrm{N}}$, and the force of gravity on the board $(=M \overrightarrow{\mathbf{g}})$ which acts at the center of the uniform board.
2. Coordinate system. We choose $y$ to be vertical, with positive upward, and $x$ horizontal to the right, with origin at the pivot.
3. Force equation. All the forces are in the $y$ (vertical) direction, so
$$\begin{array}{r}
\Sigma F_{y}=0 \\
F_{\mathrm{N}}-m_{\mathrm{A}} g-m_{\mathrm{B}} g-M g=0
\end{array}$$
where $F_{\mathrm{A}}=m_{\mathrm{A}} g$ and $F_{\mathrm{B}}=m_{\mathrm{B}} g$.

FIGURE 9-7 (a) Two children on a seesaw, Example 9-4. (b) Free-body diagram of the board.

234
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 235 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 235
4. Torque equation. Let us calculate the torque about an axis through the board at the pivot point, P . Then the lever arms for $F_{\mathrm{N}}$ and for the weight of the board are zero, and they will contribute zero torque about point P . Thus the torque equation will involve only the forces $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$, which are equal to the weights of the children. The torque exerted by each child will be $m g$ times the appropriate lever arm, which here is the distance of each child from the pivot point. $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ tends to rotate the board counterclockwise ( + ) and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ clockwise ( - ), so the torque equation is
$$\begin{aligned}
\Sigma \tau & =0 \\
m_{\mathrm{A}} g(2.5 \mathrm{~m})-m_{\mathrm{B}} g x+M g(0 \mathrm{~m})+F_{\mathrm{N}}(0 \mathrm{~m}) & =0
\end{aligned}$$
or
$$m_{\mathrm{A}} g(2.5 \mathrm{~m})-m_{\mathrm{B}} g x=0,$$
where two terms were dropped because their lever arms were zero.
5. Solve. We solve the torque equation for $x$ and find
$$x=\frac{m_{\mathrm{A}}}{m_{\mathrm{B}}}(2.5 \mathrm{~m})=\frac{30 \mathrm{~kg}}{25 \mathrm{~kg}}(2.5 \mathrm{~m})=3.0 \mathrm{~m}$$

To balance the seesaw, child B must sit so that her CG is 3.0 m from the pivot point. This makes sense: since she is lighter, she must sit farther from the pivot than the heavier child in order to provide torques of equal magnitude.

EXERCISE C We did not need to use the force equation to solve Example 9-4 because of our choice of the axis. Use the force equation to find the force exerted by the pivot.

EXAMPLE 9-5 Forces on a beam and supports. A uniform $1500-\mathrm{kg}$ beam, 20.0 m long, supports a $15,000-\mathrm{kg}$ printing press 5.0 m from the right support column (Fig. 9-8). Calculate the force on each of the vertical support columns.
APPROACH We analyze the forces on the beam (the force the beam exerts on each column is equal and opposite to the force exerted by the column on the beam). We label these forces $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$ in Fig. 9-8. The weight of the beam itself acts at its center of gravity, 10.0 m from either end. We choose a convenient axis for writing the torque equation: the point of application of $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ (labeled P), so $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ will not enter the equation (its lever arm will be zero) and we will have an equation in only one unknown, $F_{\mathrm{B}}$.
SOLUTION The torque equation, $\Sigma \tau=0$, with the counterclockwise direction as positive, gives
$$\Sigma \tau=-(10.0 \mathrm{~m})(1500 \mathrm{~kg}) g-(15.0 \mathrm{~m})(15,000 \mathrm{~kg}) g+(20.0 \mathrm{~m}) F_{\mathrm{B}}=0 .$$

Solving for $F_{\mathrm{B}}$, we find $F_{\mathrm{B}}=(12,000 \mathrm{~kg}) g=118,000 \mathrm{~N}$. To find $F_{\mathrm{A}}$, we use $\Sigma F_{y}=0$, with $+y$ upward:
$$\Sigma F_{y}=F_{\mathrm{A}}-(1500 \mathrm{~kg}) g-(15,000 \mathrm{~kg}) g+F_{\mathrm{B}}=0 .$$

Putting in $F_{\mathrm{B}}=(12,000 \mathrm{~kg}) g$, we find that $F_{\mathrm{A}}=(4500 \mathrm{~kg}) g=44,100 \mathrm{~N}$.

Figure 9-9 shows a uniform beam that extends beyond its support like a diving board. Such a beam is called a cantilever. The forces acting on the beam in Fig. 9-9 are those due to the supports, $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}$, and the force of gravity which acts at the cG, 5.0 m to the right of the right-hand support. If you follow the procedure of the last Example and calculate $F_{\mathrm{A}}$ and $F_{\mathrm{B}}$, assuming they point upward as shown in Fig. 9-9, you will find that $F_{\mathrm{A}}$ comes out negative. If the beam has a mass of 1200 kg and a weight $m g=12,000 \mathrm{~N}$, then $F_{\mathrm{B}}=15,000 \mathrm{~N}$ and $F_{\mathrm{A}}=-3000 \mathrm{~N}$ (see Problem 10). Whenever an unknown force comes out negative, it merely means that the force actually points in the opposite direction from what you assumed. Thus in Fig. 9-9, $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ actually must pull downward (by means of bolts, screws, fasteners, and/or glue). To see why $\overrightarrow{\mathbf{F}}_{\mathrm{A}}$ has to act downward, note that the board's weight acting at the CG would otherwise rotate the board

FIGURE 9-8 A $1500-\mathrm{kg}$ beam supports a $15,000-\mathrm{kg}$ machine. Example 9-5.
clockwise about support B.

PHYSICS APPLIED Cantilever

PROBLEM SOLVING If a force comes out negative

FIGURE 9-9 A cantilever.

SECTION 9-2 Solving Statics Problems
235

---

<!-- Page 236 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 236

EXERCISE D Return to the Chapter-Opening Question, page 230, and answer it again now. Try to explain why you may have answered differently the first time.

FIGURE 9-10 Example 9-6.

Our next Example involves a beam that is attached to a wall by a hinge and is supported by a cable or cord (Fig. 9-10). It is important to remember that a flexible cable can support a force only along its length. (If there were a component of force perpendicular to the cable, it would bend because it is flexible.) But for a rigid device, such as the hinge in Fig. 9-10, the force can be in any direction and we can know the direction only after solving the equations. (The hinge is assumed small and smooth, so it can exert no internal torque on the beam.)

EXAMPLE 9-6 Hinged beam and cable. A uniform beam, 2.20 m long with mass $m=25.0 \mathrm{~kg}$, is mounted by a small hinge on a wall as shown in Fig. 9-10. The beam is held in a horizontal position by a cable that makes an angle $\theta=30.0^{\circ}$. The beam supports a sign of mass $M=28.0 \mathrm{~kg}$ suspended from its end. Determine the components of the force $\overrightarrow{\mathbf{F}}_{\mathrm{H}}$ that the (smooth) hinge exerts on the beam, and the tension $F_{\mathrm{T}}$ in the supporting cable.
APPROACH Figure 9-10 is the free-body diagram for the beam, showing all the forces acting on the beam. It also shows the components of $\overrightarrow{\mathbf{F}}_{\mathrm{T}}$ and a guess for the direction of $\overrightarrow{\mathbf{F}}_{\mathrm{H}}$. We have three unknowns, $F_{\mathrm{H} x}, F_{\mathrm{H} y}$, and $F_{\mathrm{T}}$ (we are given $\theta$ ), so we will need all three equations, $\Sigma F_{x}=0, \Sigma F_{y}=0, \Sigma \tau=0$.
SOLUTION The sum of the forces in the vertical $(y)$ direction is
$$\begin{aligned}
\Sigma F_{y} & =0 \\
F_{\mathrm{H} y}+F_{\mathrm{T} y}-m g-M g & =0 .
\end{aligned}$$

In the horizontal ( $x$ ) direction, the sum of the forces is
$$\begin{aligned}
\Sigma F_{x} & =0 \\
F_{\mathrm{H} x}-F_{\mathrm{T} x} & =0 .
\end{aligned}$$

For the torque equation, we choose the axis at the point where $\overrightarrow{\mathbf{F}}_{\mathrm{T}}$ and $M \overrightarrow{\mathbf{g}}$ act. Then our torque equation will contain only one unknown, $F_{\mathrm{Hy}}$, because the lever arms for $\overrightarrow{\mathbf{F}}_{\mathrm{T}}, M \overrightarrow{\mathbf{g}}$, and $F_{\mathrm{H} x}$ are zero. We choose torques that tend to rotate the beam counterclockwise as positive. The weight $m g$ of the (uniform) beam acts at its center, so we have
$$\begin{aligned}
\Sigma \tau & =0 \\
-\left(F_{\mathrm{H} y}\right)(2.20 \mathrm{~m})+m g(1.10 \mathrm{~m}) & =0 .
\end{aligned}$$

We solve for $F_{\mathrm{H} y}$ :
$$F_{\mathrm{H} y}=\left(\frac{1.10 \mathrm{~m}}{2.20 \mathrm{~m}}\right) m g=(0.500)(25.0 \mathrm{~kg})\left(9.80 \mathrm{~m} / \mathrm{s}^{2}\right)=123 \mathrm{~N} .$$

Next, since the tension $\overrightarrow{\mathbf{F}}_{\mathrm{T}}$ in the cable acts along the cable ( $\theta=30.0^{\circ}$ ), we see from Fig. 9-10 that $\tan \theta=F_{\mathrm{T} y} / F_{\mathrm{T} x}$, or
$$F_{\mathrm{T} y}=F_{\mathrm{T} x} \tan \theta=F_{\mathrm{T} x}\left(\tan 30.0^{\circ}\right) .$$

Equation (i) above gives
$$F_{\mathrm{T} y}=(m+M) g-F_{\mathrm{H} y}=(53.0 \mathrm{~kg})\left(9.80 \mathrm{~m} / \mathrm{s}^{2}\right)-123 \mathrm{~N}=396 \mathrm{~N} .$$

Equations (iv) and (ii) give
$$\begin{array}{l}
F_{\mathrm{T} x}=F_{\mathrm{T} y} / \tan 30.0^{\circ}=396 \mathrm{~N} / \tan 30.0^{\circ}=686 \mathrm{~N} ; \\
F_{\mathrm{H} x}=F_{\mathrm{T} x}=686 \mathrm{~N} .
\end{array}$$

The components of $\overrightarrow{\mathbf{F}}_{\mathrm{H}}$ are $F_{\mathrm{H} y}=123 \mathrm{~N}$ and $F_{\mathrm{H} x}=686 \mathrm{~N}$. The tension in the wire is $F_{\mathrm{T}}=\sqrt{F_{\mathrm{T} x}^{2}+F_{\mathrm{T} y}^{2}}=\sqrt{(686 \mathrm{~N})^{2}+(396 \mathrm{~N})^{2}}=792 \mathrm{~N}^{. \dagger}$
${ }^{\dagger}$ Our calculation used numbers rounded off to 3 significant figures. If you keep an extra digit, or leave the numbers in your calculator, you get $F_{\mathrm{T} y}=396.5 \mathrm{~N}, F_{\mathrm{T} x}=686.8 \mathrm{~N}$, and $F_{\mathrm{T}}=793 \mathrm{~N}$, all within the expected precision of 3 significant figures (Section 1-4).

236
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 237 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 237

Alternate Solution Let us see the effect of choosing a different axis for calculating torques, such as an axis through the hinge. Then the lever arm for $F_{\mathrm{H}}$ is zero, and the torque equation ( $\Sigma \tau=0$ ) becomes
$$-m g(1.10 \mathrm{~m})-M g(2.20 \mathrm{~m})+F_{\mathrm{Ty}}(2.20 \mathrm{~m})=0 .$$

We solve this for $F_{\mathrm{T} y}$ and find
$$F_{\mathrm{T} y}=\frac{m}{2} g+M g=(12.5 \mathrm{~kg}+28.0 \mathrm{~kg})\left(9.80 \mathrm{~m} / \mathrm{s}^{2}\right)=397 \mathrm{~N} .$$

We get the same result, within the precision of our significant figures.
NOTE It doesn't matter which axis we choose for $\Sigma \tau=0$. Using a second axis can serve as a check.
* A More Difficult Example-The Ladder

EXAMPLE 9-7 Ladder. A $5.0-\mathrm{m}$-long ladder leans against a wall at a point 4.0 m above a cement floor as shown in Fig. 9-11. The ladder is uniform and has mass $m=12.0 \mathrm{~kg}$. Assuming the wall is frictionless, but the floor is not, determine the forces exerted on the ladder by the floor and by the wall.
APPROACH Figure 9-11 is the free-body diagram for the ladder, showing all the forces acting on the ladder. The wall, since it is frictionless, can exert a force only perpendicular to the wall, and we label that force $\overrightarrow{\mathbf{F}}_{\mathrm{W}}$. The cement floor exerts a force $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ which has both horizontal and vertical force components: $F_{\mathrm{C} x}$ is frictional and $F_{\mathrm{C} y}$ is the normal force. Finally, gravity exerts a force $m g=(12.0 \mathrm{~kg})\left(9.80 \mathrm{~m} / \mathrm{s}^{2}\right)=118 \mathrm{~N}$ on the ladder at its midpoint, since the ladder is uniform.
SOLUTION Again we use the equilibrium conditions, $\Sigma F_{x}=0, \Sigma F_{y}=0$, $\Sigma \tau=0$. We will need all three since there are three unknowns: $F_{\mathrm{W}}, F_{\mathrm{Cx}}$, and $F_{\mathrm{Cy}}$. The $y$ component of the force equation is
$$\Sigma F_{y}=F_{\mathrm{C} y}-m g=0,$$
so immediately we have
$$F_{\mathrm{C} y}=m g=118 \mathrm{~N} .$$

The $x$ component of the force equation is
$$\Sigma F_{x}=F_{\mathrm{C} x}-F_{\mathrm{W}}=0 .$$

To determine both $F_{\mathrm{C} x}$ and $F_{\mathrm{w}}$, we need a torque equation. If we choose to calculate torques about an axis through the point where the ladder touches the cement floor, then $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$, which acts at this point, will have a lever arm of zero and so won't enter the equation. The ladder touches the floor a distance $x_{0}=\sqrt{(5.0 \mathrm{~m})^{2}-(4.0 \mathrm{~m})^{2}}=3.0 \mathrm{~m}$ from the wall (right triangle, $c^{2}=a^{2}+b^{2}$ ). The lever arm for $m g$ is half this, or 1.5 m , and the lever arm for $F_{\mathrm{w}}$ is 4.0 m , Fig. 9-11. The torque equation about the ladder's contact point on the cement is
$$\Sigma \tau=(4.0 \mathrm{~m}) F_{\mathrm{W}}-(1.5 \mathrm{~m}) m g=0 .$$

Thus
$$F_{\mathrm{W}}=\frac{(1.5 \mathrm{~m})(12.0 \mathrm{~kg})\left(9.8 \mathrm{~m} / \mathrm{s}^{2}\right)}{4.0 \mathrm{~m}}=44 \mathrm{~N} .$$

Then, from the $x$ component of the force equation,
$$F_{\mathrm{C} x}=F_{\mathrm{W}}=44 \mathrm{~N} .$$

Since the components of $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ are $F_{\mathrm{C} x}=44 \mathrm{~N}$ and $F_{\mathrm{C} y}=118 \mathrm{~N}$, then
$$F_{\mathrm{C}}=\sqrt{(44 \mathrm{~N})^{2}+(118 \mathrm{~N})^{2}}=126 \mathrm{~N} \approx 130 \mathrm{~N}$$
(rounded off to two significant figures), and it acts at an angle to the floor of
$$\theta=\tan ^{-1}(118 \mathrm{~N} / 44 \mathrm{~N})=70^{\circ} .$$

NOTE The force $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ does not have to act along the ladder's direction because the ladder is rigid and not flexible like a cord or cable (see page 89, Chapter 4).

FIGURE 9-11 A ladder leaning against a wall. Example 9-7. The force $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ that the cement floor exerts on the ladder need not be along the ladder which (unlike a cord) is rigid.

SECTION 9-2 Solving Statics Problems
237

---

<!-- Page 238 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 6/27/16 2:27 PM Page 238

FIGURE 9-12 The biceps (flexor) and triceps (extensor) muscles in the human arm.

PHYSICS APPLIED
Forces in muscles and joints

FIGURE 9-13 Example 9-8, forces on forearm.

(b)

PHYSICS APPLIED
Muscle insertion and lever arm

PHYSICS APPLIED

Forces on the spine, and back pain

9-3 Applications to Muscles and Joints
The techniques we have been discussing for calculating forces on objects in equilibrium can be applied to the human body to study forces on muscles, bones, joints. Generally a muscle is attached, via tendons, to two different bones, as in Fig. 9-12. The points of attachment are called insertions. Two bones are flexibly connected at a joint, such as at the elbow, knee, hip, and shoulder. A muscle exerts a pull when its fibers contract under stimulation by a nerve, but a muscle can not exert a push. Muscles that tend to bring two limbs closer together, such as the biceps muscle in the upper arm (Fig. 9-12), are called flexors; those that act to extend a limb outward, such as the triceps muscle in Fig. 9-12, are called extensors. You use the flexor muscle in the upper arm when lifting an object in your hand; you use the extensor muscle when throwing a ball.

EXAMPLE 9-8 Force exerted by biceps muscle. How much force must the biceps muscle exert when a $5.0-\mathrm{kg}$ ball is held in the hand (a) with the arm horizontal as in Fig. 9-13a, and (b) when the arm is at a $45^{\circ}$ angle as in Fig. 9-13b? The biceps muscle is connected to the forearm by a tendon attached 5.0 cm from the elbow joint. Assume that the mass of forearm and hand together is 2.0 kg and their CG is as shown.
APPROACH The free-body diagram for the forearm is shown in Fig. 9-13; the forces are the weights of the arm and ball, the upward force $\overrightarrow{\mathbf{F}}_{\mathrm{M}}$ exerted by the muscle, and a force $\overrightarrow{\mathbf{F}}_{\text {J }}$ exerted at the joint by the bone in the upper arm (all assumed to act vertically). We wish to find the magnitude of $\overrightarrow{\mathbf{F}}_{\mathrm{M}}$, which can be done using the torque equation and by choosing our axis through the joint so that $\overrightarrow{\mathbf{F}}_{\text {J }}$ contributes zero torque.
SOLUTION (a) We calculate torques about the point where $\overrightarrow{\mathbf{F}}_{\mathrm{J}}$ acts in Fig. 9-13a. The $\Sigma \tau=0$ equation gives
$$(0.050 \mathrm{~m}) F_{\mathrm{M}}-(0.15 \mathrm{~m})(2.0 \mathrm{~kg}) g-(0.35 \mathrm{~m})(5.0 \mathrm{~kg}) g=0 .$$

We solve for $F_{\mathrm{M}}$ :
$$F_{\mathrm{M}}=\frac{(0.15 \mathrm{~m})(2.0 \mathrm{~kg}) g+(0.35 \mathrm{~m})(5.0 \mathrm{~kg}) g}{0.050 \mathrm{~m}}=(41 \mathrm{~kg}) g=400 \mathrm{~N} .$$
(b) The lever arm, as calculated about the joint, is reduced by the factor $\cos 45^{\circ}$ for all three forces. Our torque equation will look like the one just above, except that each term will have its lever arm reduced by the same factor, which will cancel out. The same result is obtained, $F_{\mathrm{M}}=400 \mathrm{~N}$.
NOTE The force required of the muscle $(400 \mathrm{~N})$ is quite large compared to the weight of the object lifted $(=m g=49 \mathrm{~N})$. Indeed, the muscles and joints of the body are generally subjected to quite large forces.
NOTE Forces exerted on joints can be large and even painful or injurious. Using $\Sigma F_{y}=0$ we calculate for this case $F_{\mathrm{J}}=F_{\mathrm{M}}-(2.0 \mathrm{~kg}) g-(5.0 \mathrm{~kg}) g=330 \mathrm{~N}$.

The point of insertion of a muscle varies from person to person. A slight increase in the distance of the joint to the point of insertion of the biceps muscle from 5.0 cm to 5.5 cm can be a considerable advantage for lifting and throwing. Champion athletes are often found to have muscle insertions farther from the joint than the average person, and if this applies to one muscle, it usually applies to all.

As another example of the large forces acting within the human body, we consider the muscles used to support the body (trunk) when you bend forward (Fig. 9-14a). The lowest vertebra on the spinal column (fifth lumbar vertebra) acts as a fulcrum for this bending position. The "erector spinae" muscles in the back that support the trunk act at an effective angle of about $12^{\circ}$ to the axis of the spine. Let us assume the trunk makes an angle of $30^{\circ}$ with the horizontal.

238
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 239 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 239

Figure 9-14b is a simplified schematic drawing showing the forces on the upper body. The force exerted by the back muscles is represented by $\overrightarrow{\mathbf{F}}_{\mathrm{M}}$, the force exerted on the base of the spine at the lowest vertebra is $\overrightarrow{\mathbf{F}}_{\mathrm{V}}$, and $\overrightarrow{\mathbf{w}}_{\mathrm{H}}, \overrightarrow{\mathbf{w}}_{\mathrm{A}}$, and $\overrightarrow{\mathbf{w}}_{\mathrm{T}}$ represent the weights of the head, freely hanging arms, and trunk, respectively. The values shown are approximations. The distances (in cm) refer to a person 180 cm tall, but are approximately in the same ratio of $1: 2: 3$ for an average person of any height, and the result in the following Example is then independent of the height of the person.

EXAMPLE 9-9 Forces on your back. Calculate the magnitude and direction of the force $\overrightarrow{\mathbf{F}}_{\mathrm{V}}$ acting on the fifth lumbar vertebra as represented in Fig. 9-14b.
APPROACH We use the model of the upper body described above and shown in Fig. 9-14b. We can calculate $F_{\mathrm{M}}$ using the torque equation if we take the axis at the base of the spine (point S ); with this choice, the other unknown, $F_{\mathrm{V}}$, doesn't appear in the equation because its lever arm is zero. To figure the lever arms, we need to use trigonometric functions.
SOLUTION For $\overrightarrow{\mathbf{F}}_{\mathrm{M}}$, the lever arm (perpendicular distance from axis to line of action of the force) will be the real distance to where the force acts ( 48 cm ) multiplied by $\sin 12^{\circ}$, as shown in Fig. 9-14c. The lever arms for $\overrightarrow{\mathbf{w}}_{\mathrm{H}}, \overrightarrow{\mathbf{w}}_{\mathrm{A}}$, and $\overrightarrow{\mathbf{w}}_{\mathrm{T}}$ can be seen from Fig. 9-14b to be their respective distances from S times $\sin 60^{\circ}$. $F_{\mathrm{M}}$ tends to rotate the trunk counterclockwise, which we take to be positive. Then $\overrightarrow{\mathbf{w}}_{\mathrm{H}}, \overrightarrow{\mathbf{w}}_{\mathrm{A}}, \overrightarrow{\mathbf{w}}_{\mathrm{T}}$ will contribute negative torques. Thus $\Sigma \tau=0$ gives
$$\begin{array}{l}
(0.48 \mathrm{~m})\left(\sin 12^{\circ}\right)\left(F_{\mathrm{M}}\right)-(0.72 \mathrm{~m})\left(\sin 60^{\circ}\right)\left(w_{\mathrm{H}}\right) \\
\quad-(0.48 \mathrm{~m})\left(\sin 60^{\circ}\right)\left(w_{\mathrm{A}}\right)-(0.36 \mathrm{~m})\left(\sin 60^{\circ}\right)\left(w_{\mathrm{T}}\right)=0 .
\end{array}$$

Solving for $F_{\mathrm{M}}$ and putting in the values for $w_{\mathrm{H}}, w_{\mathrm{A}}, w_{\mathrm{T}}$ given in Fig. 9-14b, we find
$$\begin{aligned}
F_{\mathrm{M}} & =\frac{(0.72 \mathrm{~m})(0.07 w)+(0.48 \mathrm{~m})(0.12 w)+(0.36 \mathrm{~m})(0.46 w)}{(0.48 \mathrm{~m})\left(\sin 12^{\circ}\right)}\left(\sin 60^{\circ}\right) \\
& =2.37 w \approx 2.4 w
\end{aligned}$$
where $w$ is the total weight of the body. To get the components of $\overrightarrow{\mathbf{F}}_{\mathrm{V}}$ we use the $x$ and $y$ components of the force equation (noting that $30^{\circ}-12^{\circ}=18^{\circ}$ ):
$$\Sigma F_{y}=F_{\mathrm{V} y}-F_{\mathrm{M}} \sin 18^{\circ}-w_{\mathrm{H}}-w_{\mathrm{A}}-w_{\mathrm{T}}=0$$
so
$$F_{\mathrm{V} y}=1.38 w \approx 1.4 w,$$
and
$$\Sigma F_{x}=F_{\mathrm{V} x}-F_{\mathrm{M}} \cos 18^{\circ}=0$$
so
$$F_{\mathrm{V} x}=2.25 w \approx 2.3 w,$$
where we keep 3 significant figures for calculating, but round off to 2 for giving the answer. Then
$$F_{\mathrm{V}}=\sqrt{F_{\mathrm{V} x}^{2}+F_{\mathrm{V} y}^{2}}=2.6 w .$$

The angle $\theta$ that $F_{\mathrm{V}}$ makes with the horizontal is given by $\tan \theta=F_{\mathrm{V} y} / F_{\mathrm{V} x}=0.61$, so $\theta=32^{\circ}$.
NOTE The force on the lowest vertebra is over $2 \frac{1}{2}$ times the total body weight! This force is exerted by the "sacral" bone at the base of the spine, through the somewhat flexible intervertebral disk. The disks at the base of the spine are clearly being compressed under very large forces. [If the body was less bent over (say, the $30^{\circ}$ angle in Fig. 9-14b becomes $40^{\circ}$ or $50^{\circ}$ ), then the stress on the lower back will be less.]

If the person in Fig. 9-14 has a mass of 90 kg and is holding 20 kg in his hands (this increases $w_{\mathrm{A}}$ to $0.34 w$ ), then $F_{\mathrm{V}}$ is increased to almost four times the person's weight $(3.7 w)$. For this $200-\mathrm{lb}$ person, the force on the disk would be over 700 lb ! With such strong forces acting, it is little wonder that so many people suffer from low back pain at one time or another.

FIGURE 9-14 (a) A person bending over. (b) Forces on the back exerted by the back muscles ( $\overrightarrow{\mathbf{F}}_{\mathrm{M}}$ ) and by the vertebrae ( $\overrightarrow{\mathbf{F}}_{\mathrm{V}}$ ) when a person bends over. (c) Finding the lever $\operatorname{arm}$ for $\overrightarrow{\mathbf{F}}_{\mathrm{M}}$.

SECTION 9-3 Applications to Muscles and Joints
239

---

<!-- Page 240 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 240
9-4 Stability and Balance

An object in static equilibrium, if left undisturbed, will undergo no translational or rotational acceleration since the sum of all the forces and the sum of all the torques acting on it are zero. However, if the object is displaced slightly, three outcomes are possible: (1) the object returns to its original position, in which case it is said to be in stable equilibrium; (2) the object moves even farther from its original position, and it is said to be in unstable equilibrium; or ( 3 ) the object remains in its new position, and it is said to be in neutral equilibrium.

Consider the following examples. A ball suspended freely from a string is in stable equilibrium, for if it is displaced to one side, it will return to its original position (Fig. 9-15a) due to the net force and torque exerted on it. On the other hand, a pencil standing on its point is in unstable equilibrium. If its center of gravity is directly over its tip (Fig.9-15b), the net force and net torque on it will be zero. But if it is displaced ever so slightly as shown-say, by a slight vibration or tiny air current-there will be a torque on it, and this torque acts to make the pencil continue to fall in the direction of the original displacement. Finally, an example of an object in neutral equilibrium is a sphere resting on a horizontal tabletop. If it is moved slightly to one side, it will remain in its new position-no net torque acts on it.

FIGURE 9-15 (a) Stable equilibrium, and (b) unstable equilibrium.

FIGURE 9-16 Equilibrium of a
refrigerator resting on a flat floor.
(a)
(b)

FIGURE 9-17 Humans adjust their posture to achieve stability when carrying loads.

PHYSICS APPLIED
Humans and balance

240
CHAPTER 9

In most situations, such as in the design of structures and in working with the human body, we are interested in maintaining stable equilibrium, or balance, as we sometimes say. In general, an object whose center of gravity (CG) is below its point of support, such as a ball on a string, will be in stable equilibrium. If the CG is above the base of support, we have a more complicated situation. Consider a standing refrigerator (Fig. 9-16a). If it is tipped slightly, it will return to its original position due to the torque on it as shown in Fig. 9-16b. But if it is tipped too far, Fig. 9-16c, it will fall over. The critical point is reached when the CG shifts from one side of the pivot point to the other. When the cg is on one side, the torque pulls the object back onto its original base of support, Fig. 9-16b. If the object is tipped further, the CG goes past the pivot point and the torque causes the object to topple, Fig. 9-16c. In general, an object whose center of gravity is above its base of support will be stable if a vertical line projected downward from the CG falls within the base of support. This is because the normal force upward on the object (which balances out gravity) can be exerted only within the area of contact, so if the force of gravity acts beyond this area, a net torque will act to topple the object.

Stability, then, can be relative. A brick lying on its widest face is more stable than a brick standing on its end, for it will take more of an effort to tip it over. In the extreme case of the pencil in Fig. 9-15b, the base is practically a point and the slightest disturbance will topple it. In general, the larger the base and the lower the cG, the more stable the object.

In this sense, humans are less stable than four-legged mammals, which have a larger base of support because of their four legs, and most also have a lower center of gravity. When walking and performing other kinds of movement, a person continually shifts the body so that its CG is over the feet, although in the normal adult this requires no conscious thought. Even as simple a movement as bending over requires moving the hips backward so that the CG remains over the feet, and you do this repositioning without thinking about it. To see this, position yourself with your heels and back to a wall and try to touch your toes. You won't be able to do it without falling. Persons carrying heavy loads automatically adjust their posture so that the CG of the total mass is over their feet, Fig. 9-17.

---

<!-- Page 241 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 241

9-5 Elasticity; Stress and Strain

In the first part of this Chapter we studied how to calculate the forces on objects in equilibrium. In this Section we study the effects of these forces: any object changes shape under the action of applied forces. If the forces are great enough, the object will break, or fracture, as we will discuss in Section 9-6.

Elasticity and Hooke's Law
If a force is exerted on an object, such as the vertically suspended metal rod shown in Fig. 9-18, the length of the object changes. If the amount of elongation, $\Delta \ell$, is small compared to the length of the object, experiment shows that $\Delta \ell$ is proportional to the force exerted on the object. This proportionality can be written as an equation:
$$F=k \Delta \ell .$$

Here $F$ represents the force pulling on the object, $\Delta \ell$ is the change in length, and $k$ is a proportionality constant. Equation 9-3, which is sometimes called Hooke's law ${ }^{\dagger}$ after Robert Hooke (1635-1703), who first noted it, is found to be valid for almost any solid material from iron to bone-but it is valid only up to a point. For if the force is too great, the object stretches excessively and eventually breaks.

Figure $9-19$ shows a typical graph of applied force versus elongation. Up to a point called the proportional limit, Eq. 9-3 is a good approximation for many common materials, and the curve is a straight line. Beyond this point, the graph deviates from a straight line, and no simple relationship exists between $F$ and $\Delta \ell$. Nonetheless, up to a point farther along the curve called the elastic limit, the object will return to its original length if the applied force is removed. The region from the origin to the elastic limit is called the elastic region. If the object is stretched beyond the elastic limit, it enters the plastic region: it does not return to the original length upon removal of the external force, but remains permanently deformed (such as a bent paper clip). The maximum elongation is reached at the breaking point. The maximum force that can be applied without breaking is called the ultimate strength of the material (actually, force per unit area, as we discuss in Section 9-6).

Young's Modulus
The amount of elongation of an object, such as the rod shown in Fig. 9-18, depends not only on the force applied to it, but also on the material of which it is made and on its dimensions. That is, the constant $k$ in Eq. 9-3 can be written in terms of these factors.

If we compare rods made of the same material but of different lengths and cross-sectional areas, it is found that for the same applied force, the amount of stretch (again assumed small compared to the total length) is proportional to the original length and inversely proportional to the cross-sectional area. That is, the longer the object, the more it elongates for a given force; and the thicker it is, the less it elongates. These findings can be combined with Eq. 9-3 to yield
$$\Delta \ell=\frac{1}{E} \frac{F}{A} \ell_{0}$$
where $\ell_{0}$ is the original length of the object, $A$ is the cross-sectional area, and $\Delta \ell$ is the change in length due to the applied force $F$. $E$ is a constant of proportionality ${ }^{\ddagger}$ known as the elastic modulus, or Young's modulus; its value depends only on the material.
${ }^{\dagger}$ The term "law" applied to this relation is historical, but today it is not really appropriate. First of all, it is only an approximation, and second, it refers only to a limited set of phenomena. Most physicists today prefer to reserve the word "law" for those relations that are deeper and more encompassing and precise, such as Newton's laws of motion or the law of conservation of energy.
${ }^{\ddagger}$ The fact that $E$ is in the denominator, so $1 / E$ is the actual proportionality constant, is merely a convention. When we rewrite Eq. 9-4 to get Eq. 9-5, $E$ is found in the numerator.

FIGURE 9-18 Hooke's law: $\Delta \ell \propto$ applied force.

FIGURE 9-19 Applied force vs. elongation for a typical metal under tension.

SECTION 9-5 Elasticity; Stress and Strain
241

---

<!-- Page 242 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 $14: 42$
Page 242

The value of Young's modulus for various materials is given in Table $9-1$ (the shear modulus and bulk modulus in this Table are discussed later in this Section). Because $E$ is a property only of the material and is independent of the object's size or shape, Eq. 9-4 is far more useful for practical calculation than Eq. 9-3.

**TABLE 9-1 Elastic Moduli**

| Material | Young's Modulus, $\boldsymbol{E} \boldsymbol{(} \mathbf{N} \boldsymbol{/} \mathbf{m}^{\mathbf{2}} \boldsymbol{)}$ | Shear Modulus, $\boldsymbol{G}\left(\mathbf{N} \boldsymbol{/} \mathbf{m}^{\mathbf{2}} \boldsymbol{)}\right.$ | Bulk Modulus, $\boldsymbol{B} \boldsymbol{(} \mathbf{N} \boldsymbol{/} \mathbf{m}^{\mathbf{2}} \boldsymbol{)}$ |
| --- | --- | --- | --- |
| Solids |  |  |  |
| Iron, cast | $100 \times 10^{9}$ | $40 \times 10^{9}$ | $90 \times 10^{9}$ |
| Steel | $200 \times 10^{9}$ | $80 \times 10^{9}$ | $140 \times 10^{9}$ |
| Brass | $100 \times 10^{9}$ | $35 \times 10^{9}$ | $80 \times 10^{9}$ |
| Aluminum | $70 \times 10^{9}$ | $25 \times 10^{9}$ | $70 \times 10^{9}$ |
| Concrete | $20 \times 10^{9}$ |  |  |
| Brick | $14 \times 10^{9}$ |  |  |
| Marble | $50 \times 10^{9}$ |  | $70 \times 10^{9}$ |
| Granite | $45 \times 10^{9}$ |  | $45 \times 10^{9}$ |
| Wood (pine) (parallel to grain) | $10 \times 10^{9}$ |  |  |
| (perpendicular to grain) | $1 \times 10^{9}$ |  |  |
| Nylon | $\approx 3 \times 10^{9}$ |  |  |
| Bone (limb) | $15 \times 10^{9}$ | $80 \times 10^{9}$ |  |
| Liquids |  |  |  |
| Water |  |  | $2.0 \times 10^{9}$ |
| Alcohol (ethyl) |  |  | $1.0 \times 10^{9}$ |
| Mercury |  |  | $2.5 \times 10^{9}$ |
| Gases ${ ^{\dagger}$} |  |  |  |
| Air, $\mathrm{H}_{2}, \mathrm{He}, \mathrm{CO}_{2}$ |  |  | $1.01 \times 10^{5}$ |
${ }^{\dagger}$ At normal atmospheric pressure; no variation in temperature during process.

EXAMPLE 9-10 Tension in piano wire. A $1.60-\mathrm{m}$-long steel piano wire has a diameter of 0.20 cm . How great is the tension in the wire if it stretches 0.25 cm when tightened?
APPROACH We assume Hooke's law holds, and use it in the form of Eq. 9-4, finding $E$ for steel in Table 9-1.
SOLUTION We solve for $F$ in Eq. 9-4 and note that the area of the wire is $A=\pi r^{2}=(3.14)(0.0010 \mathrm{~m})^{2}=3.14 \times 10^{-6} \mathrm{~m}^{2}$. Then
$$\begin{aligned}
F & =E \frac{\Delta \ell}{\ell_{0}} A \\
& =\left(2.0 \times 10^{11} \mathrm{~N} / \mathrm{m}^{2}\right)\left(\frac{0.0025 \mathrm{~m}}{1.60 \mathrm{~m}}\right)\left(3.14 \times 10^{-6} \mathrm{~m}^{2}\right) \\
& =980 \mathrm{~N} .
\end{aligned}$$

NOTE The large tension in all the wires in a piano must be supported by a strong frame.

EXERCISE E Two steel wires have the same length and are under the same tension. But wire A has twice the diameter of wire B . Which of the following is true? (a) Wire B stretches twice as much as wire A . (b) Wire B stretches four times as much as wire A . (c) Wire A stretches twice as much as wire B. (d) Wire A stretches four times as much as wire B. (e) Both wires stretch the same amount.

242
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 243 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 243

Stress and Strain
From Eq. 9-4, we see that the change in length of an object is directly proportional to the product of the object's length $\ell_{0}$ and the force per unit area $F / A$ applied to it. It is general practice to define the force per unit area as the stress:
$$\text { stress }=\frac{\text { force }}{\text { area }}=\frac{F}{A},$$
which has SI units of $\mathrm{N} / \mathrm{m}^{2}$. Also, the strain is defined to be the ratio of the change in length to the original length:
$$\text { strain }=\frac{\text { change in length }}{\text { original length }}=\frac{\Delta \ell}{\ell_{0}},$$
and is dimensionless (no units). Strain is thus the fractional change in length of the object, and is a measure of how much the object has been deformed. Stress is applied to the material by external agents, whereas strain is the material's response to the stress. Equation $9-4$ can be rewritten as
$$\frac{F}{A}=E \frac{\Delta \ell}{\ell_{0}}$$
or
$$E=\frac{F / A}{\Delta \ell / \ell_{0}}=\frac{\text { stress }}{\text { strain }}$$

Thus we see that the strain is directly proportional to the stress, in the linear (elastic) region of Fig. 9-19.

Tension, Compression, and Shear Stress
The rod shown in Fig. 9-20a is said to be under tension or tensile stress. Not only is there a force pulling down on the rod at its lower end, but since the rod is in equilibrium we know that the support at the top is exerting an equal ${ }^{\dagger}$ upward force on the rod at its upper end, Fig. 9-20a. In fact, this tensile stress exists throughout the material. Consider, for example, the lower half of a suspended rod as shown in Fig. 9-20b. This lower half is in equilibrium, so there must be an upward force on it to balance the downward force at its lower end. What exerts this upward force? It must be the upper part of the rod. Thus we see that external forces applied to an object give rise to internal forces, or stress, within the material itself.

Strain or deformation due to tensile stress is but one type of stress to which materials can be subjected. There are two other common types of stress: compressive and shear. Compressive stress is the exact opposite of tensile stress. Instead of being stretched, the material is compressed: the forces act inwardly on the object. Columns that support a weight, such as the columns of a Greek temple (Fig. 9-21), are subjected to compressive stress. Equations $9-4$ and $9-5$ apply equally well to compression and tension, and the values for the modulus $E$ are usually the same.
${ }^{\dagger}$ Or a greater force if the weight of the rod cannot be ignored compared to $F$.

FIGURE 9-21 This Greek temple, in Agrigento, Sicily, built 2500 years ago, shows the post-and-beam construction. The columns are under compression.

SECTION 9-5 Elasticity; Stress and Strain
243

---

<!-- Page 244 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 24 At

FIGURE 9-22 The three types of stress for rigid objects.

Figure 9-22 compares tensile and compressive stresses as well as the third type, shear stress. An object under shear stress has equal and opposite forces applied across its opposite faces. A simple example is a book or brick firmly attached to a tabletop, on which a force is exerted parallel to the top surface. The table exerts an equal and opposite force along the bottom surface. Although the dimensions of the object do not change significantly, the shape of the object does change, Fig.9-22c. An equation similar to Eq. 9-4 can be applied to calculate shear strain:
$$\Delta \ell=\frac{1}{G} \frac{F}{A} \ell_{0}$$
but $\Delta \ell, \ell_{0}$, and $A$ must be reinterpreted as indicated in Fig. 9-22c. Note that $A$ is the area of the surface parallel to the applied force (and not perpendicular as for tension and compression), and $\Delta \ell$ is perpendicular to $\ell_{0}$. The constant of proportionality $G$ is called the shear modulus and is generally one-half to one-third the value of Young's modulus $E$ (see Table $9-1$ ). Figure $9-23$ suggests why $\Delta \ell \propto \ell_{0}$ : the fatter book shifts more for the same shearing force.

FIGURE 9-23 The fatter book (a) shifts more than the thinner book (b) with the same applied shear force.

Volume Change-Bulk Modulus
If an object is subjected to inward forces from all sides, its volume will decrease. A common situation is an object submerged in a fluid. In this case, the fluid exerts a pressure on the object in all directions, as we shall see in Chapter 10. Pressure is defined as force per unit area, and thus is the equivalent of stress. For this situation the change in volume, $\Delta V$, is proportional to the original volume, $V_{0}$, and to the change in the pressure, $\Delta P$. We thus obtain a relation of the same form as Eq. 9-4 but with a proportionality constant called the bulk modulus $B$ :
$$\frac{\Delta V}{V_{0}}=-\frac{1}{B} \Delta P$$
or
$$B=-\frac{\Delta P}{\Delta V / V_{0}} .$$

The minus sign means the volume decreases with an increase in pressure.

244
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 245 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 6/27/16 2:29 PM Page 245

Values for the bulk modulus are given in Table 9-1. Since liquids and gases do not have a fixed shape, only the bulk modulus (not the Young's or shear moduli) applies to them.

9-6 Fracture
If the stress on a solid object is too great, the object fractures, or breaks (Fig. 9-24). Table 9-2 lists the ultimate strengths for tension, compression, and shear for a variety of materials. These values give the maximum force per unit area, or stress, that an object can withstand under each of these three types of stress for various types of material. They are, however, representative values only, and the actual value for a given specimen can differ considerably. It is therefore necessary to maintain a safety factor of from 3 to perhaps 10 or more-that is, the actual stresses on a structure should not exceed one-tenth to one-third of the values given in the Table. You may encounter tables of "allowable stresses" in which appropriate safety factors have already been included.

FIGURE 9-24 Fracture as a result of the three types of stress.

**TABLE 9-2 Ultimate Strengths of Materials (force/area)**

| Material |  | Tensile Strength $\boldsymbol{(} \mathbf{N} \boldsymbol{/} \mathbf{m}^{\mathbf{2}} \boldsymbol{)}$ | Compressive Strength $\boldsymbol{(} \mathbf{N} \boldsymbol{/} \mathbf{m}^{\mathbf{2}} \boldsymbol{)}$ | Shear Strength $\boldsymbol{(} \mathbf{N} \boldsymbol{/} \mathbf{m}^{\mathbf{2}} \boldsymbol{)}$ |
| --- | --- | --- | --- | --- |
| Iron, cast |  | $170 \times 10^{6}$ | $550 \times 10^{6}$ | $170 \times 10^{6}$ |
| Steel |  | $500-2500 \times 10^{6}$ | $500 \times 10^{6}$ | $250 \times 10^{6}$ |
| Brass |  | $250 \times 10^{6}$ | $250 \times 10^{6}$ | $200 \times 10^{6}$ |
| Aluminum |  | $200 \times 10^{6}$ | $200 \times 10^{6}$ | $200 \times 10^{6}$ |
| Concrete |  | $2 \times 10^{6}$ | $20 \times 10^{6}$ | $2 \times 10^{6}$ |
| Brick |  |  | $35 \times 10^{6}$ |  |
| Marble |  |  | $80 \times 10^{6}$ |  |
| Granite |  |  | $170 \times 10^{6}$ |  |
| Wood (pine) | (parallel to grain) (perpendicular to grain) | $40 \times 10^{6}$ | $35 \times 10^{6} 10 \times 10^{6}$ | $5 \times 10^{6}$ |
| Nylon |  | $500 \times 10^{6}$ |  |  |
| Bone (limb) |  | $130 \times 10^{6}$ | $170 \times 10^{6}$ |  |

EXAMPLE 9-11 ESTIMATE Breaking the piano wire. The steel piano wire we discussed in Example 9-10 was 1.60 m long with a diameter of 0.20 cm . Approximately what tension force would break it?
APPROACH We set the tensile stress $F / A$ equal to the ultimate tensile strength of steel given in Table 9-2, and we choose the highest value which represents high-carbon steel.
SOLUTION The wire's area is $A=\pi r^{2}$, where $r=0.10 \mathrm{~cm}=1.0 \times 10^{-3} \mathrm{~m}$. Table 9-2 tells us
$$\frac{F}{A}=2500 \times 10^{6} \mathrm{~N} / \mathrm{m}^{2},$$
so the wire would likely break if the force exceeded
$$F=\left(2500 \times 10^{6} \mathrm{~N} / \mathrm{m}^{2}\right)(\pi)\left(1.0 \times 10^{-3} \mathrm{~m}\right)^{2}=8000 \mathrm{~N} .$$

As can be seen in Table 9-2, concrete (like stone and brick) is reasonably strong under compression but extremely weak under tension. Thus concrete can be used as vertical columns placed under compression, but is of little value as a beam because it cannot withstand the tensile forces that result from the inevitable sagging of the lower edge of a beam (see Fig. 9-25).

FIGURE 9-25 A beam sags, at least a little (but is exaggerated here), even under its own weight. The beam thus changes shape: the upper edge is compressed, and the lower edge is under tension (elongated). Shearing stress also occurs within the beam.

SECTION 9-6 Fracture
245

---

<!-- Page 246 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 246

FIGURE 9-26 Steel rods around which concrete is poured for strength.

Reinforced concrete, in which iron rods are embedded in the concrete (Fig.9-26), is much stronger. But the concrete on the lower edge of a loaded beam still tends to crack because it is weak under tension. This problem is solved with prestressed concrete, which also contains iron rods or a wire mesh, but during the pouring of the concrete, the rods or wire are held under tension. After the concrete dries, the tension on the iron is released, putting the concrete under compression. The amount of compressive stress is carefully predetermined so that when loads are applied to the beam, the compression on the lower edge is never allowed to be reduced so far as to put the concrete into tension.

> PHYSICS APPLIED
> A tragic collapse

FIGURE 9-27 Example 9-12.

CONCEPTUAL EXAMPLE 9-12 A tragic substitution. Two walkways, one above the other, are suspended from vertical rods attached to the ceiling of a high hotel lobby, Fig. 9-27a. The original design called for single rods 14 m long, but when such long rods proved to be unwieldy to install, it was decided to replace each long rod with two shorter ones as shown schematically in Fig. 9-27b. Determine the net force exerted by the rods on the supporting pin A (assumed to be the same size) for each design. Assume each vertical rod supports a mass $m$ of each bridge.

RESPONSE The single long vertical rod in Fig. 9-27a exerts an upward force equal to $m g$ on pin A to support the mass $m$ of the upper bridge. Why? Because the pin is in equilibrium, and the other force that balances this is the downward force $m g$ exerted on it by the upper bridge (Fig. 9-27c). There is thus a shear stress on the pin because the rod pulls up on one side of the pin, and the bridge pulls down on the other side. The situation when two shorter rods support the bridges (Fig. 9-27b) is shown in Fig. 9-27d, in which only the connections at the upper bridge are shown. The lower rod exerts a force of $m g$ downward on the lower of the two pins because it supports the lower bridge. The upper rod exerts a force of $2 m g$ on the upper pin (labelled A ) because the upper rod supports both bridges. Thus we see that when the builders substituted two shorter rods for each single long one, the stress in the supporting pin A was doubled. What perhaps seemed like a simple substitution did, in fact, lead to a tragic collapse in 1981 with a loss of life of over 100 people (see Fig. 9-1). Having a feel for physics, and being able to make simple calculations based on physics, can have a great effect, literally, on people's lives.

9-7 Spanning a Space: Arches and Domes
There are a great many areas where the arts and humanities overlap the sciences, and this is especially clear in architecture, where the forces in the materials that make up a structure need to be understood to avoid excessive deformation and collapse. Many of the features we admire in the architecture of the past were introduced not simply for their decorative effect, but for technical reasons. One example is the development of methods to span a space, from the simple beam supported by columns, to arches and domes.

246
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 247 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 247

The first important architectural invention was the post-and-beam (or post-and-lintel) construction, in which two upright posts or columns support a horizontal beam. Before steel was introduced in the nineteenth century, the length of a beam was quite limited because the strongest building materials were then stone and brick. Hence the width of a span was limited by the size of available stones. Equally important, stone and brick, though strong under compression-are very weak under tension and shear; all three types of stress occur in a beam (see Fig. 9-25). The minimal space that could be spanned using stone is shown by the closely spaced columns of the great Greek temples (Fig. 9-21).

The semicircular arch (Figs. 9-28a and b) was introduced by the ancient Romans 2000 years ago. Aside from its aesthetic appeal, it was a tremendous technological innovation. The advantage of the "true" or semicircular arch is that, if well designed, its wedge-shaped stones experience stress which is mainly compressive even when supporting a large load such as the wall and roof of a cathedral.

(a)

(b)

Because the stones are forced to squeeze against one another, they are mainly under compression (see Fig. 9-29). A round arch consisting of many well-shaped stones could span a very wide space. However, because the arch transfers horizontal as well as vertical forces to the supports, considerable buttressing on the sides is needed, as we discuss shortly.

FIGURE 9-29 Stones in a round arch (see Fig. 9-28a) are mainly under compression.

The pointed arch came into use about A.D. 1100 and became the hallmark of the great Gothic cathedrals. It too was an important technical innovation, and was first used to support heavy loads such as the tower and central arch of a cathedral. Apparently the builders realized that, because of the steepness of the pointed arch, the forces due to the weight above could be brought down more nearly vertically, so less horizontal buttressing would be needed. The pointed arch reduced the load on the walls, so there could be more window openings and light. The smaller buttressing needed was provided on the outside by graceful flying buttresses (Fig. 9-30).

The technical innovation of the pointed arch was achieved not through calculation but through experience and intuition; it was not until much later that detailed calculations, such as those presented earlier in this Chapter, came into use.
PHYSICS APPLIED
Architecture: beams, arches, and domes

FIGURE 9-28 (a) Round arches in the Roman Forum, 2000 years old. The one in the background is the Arch of Titus. (b) An arch is used here to good effect for a bridge over a chasm on the California coast.

*SECTION 9-7 Spanning a Space: Arches and Domes
247

---

<!-- Page 248 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 248

FIGURE 9-31 (a) Forces in a round arch, compared (b) with those in a pointed arch.

FIGURE 9-32 Interior of the Pantheon in Rome, built almost 2000 years ago. This view, showing the great dome and its central opening for light, was painted about 1740 by Panini. Photographs do not capture its grandeur as well as this painting does.

FIGURE 9-33 The skyline of Florence, showing Brunelleschi's dome on the cathedral.

To make an accurate analysis of a stone arch is quite difficult in practice. But if we make some simplifying assumptions, we can show why the horizontal component of the force at the base is less for a pointed arch than for a round one. Figure $9-31$ shows a round arch and a pointed arch, each with an $8.0-\mathrm{m}$ span. The height of the round arch is thus 4.0 m , whereas that of the pointed arch is larger and has been chosen to be 8.0 m . Each arch supports a weight of $12.0 \times 10^{4} \mathrm{~N}(=12,000 \mathrm{~kg} \times g)$ which, for simplicity, we have divided into two parts (each $6.0 \times 10^{4} \mathrm{~N}$ ) acting on the two halves of each arch as shown. To be in equilibrium, each of the supports must exert an upward force of $6.0 \times 10^{4} \mathrm{~N}$. For rotational equilibrium, each support also exerts a horizontal force, $F_{\mathrm{H}}$, at the base of the arch, and it is this we want to calculate. We focus only on the right half of each arch. We set equal to zero the total torque calculated about the apex of the arch due to the three forces exerted on that half arch. The torque equation $(\Sigma \tau=0)$ contains three terms: the weight above, the support $F_{\mathrm{V}}$ below, and the horizontal force $F_{\mathrm{H}}$, which for the round arch (see Fig. 9-31a) is
$$-(2.0 \mathrm{~m})\left(6.0 \times 10^{4} \mathrm{~N}\right)+(4.0 \mathrm{~m})\left(6.0 \times 10^{4} \mathrm{~N}\right)-(4.0 \mathrm{~m})\left(F_{\mathrm{H}}\right)=0 .$$

Thus $F_{\mathrm{H}}=3.0 \times 10^{4} \mathrm{~N}$ for the round arch. For the pointed arch, the torque equation is (see Fig. 9-31b)
$$-(2.0 \mathrm{~m})\left(6.0 \times 10^{4} \mathrm{~N}\right)+(4.0 \mathrm{~m})\left(6.0 \times 10^{4} \mathrm{~N}\right)-(8.0 \mathrm{~m})\left(F_{\mathrm{H}}\right)=0 .$$

Solving, we find that $F_{\mathrm{H}}=1.5 \times 10^{4} \mathrm{~N}$-only half as much as for the round arch! From this calculation we can see that the horizontal buttressing force required for a pointed arch is less because the arch is higher, and there is therefore a longer lever arm for this force. Indeed, the steeper the arch, the less the horizontal component of the force needs to be, and hence the more nearly vertical is the force exerted at the base of the arch.

Whereas an arch spans a two-dimensional space, a dome-which is basically an arch rotated about a vertical axis-spans a three-dimensional space. The Romans built the first large domes. Their shape was hemispherical and some still stand, such as that of the Pantheon in Rome (Fig. 9-32), built nearly 2000 years ago.

Fourteen centuries later, a new cathedral was being built in Florence. ${ }^{\dagger}$ It was to have a dome 43 m in diameter to rival that of the Pantheon, whose construction has remained a mystery. The new dome was to rest on a "drum" with no external abutments. Filippo Brunelleschi (1377-1446) designed a pointed dome (Fig. 9-33), since a pointed dome, like a pointed arch, exerts a smaller side thrust against its base. A dome, like an arch, is not stable until all the stones are in place. To support smaller domes during construction, wooden frameworks were used. But no trees big enough or strong enough could be found to span the $43-\mathrm{m}$ space required. Brunelleschi built the dome in horizontal layers, each bonded to the previous one, holding it in place until the last stone of the circle was placed. Each closed ring was then strong enough to support the next layer. An amazing feat. Only in the twentieth century were larger domes built.
${ }^{\dagger}$ Supervised by Arnolfo di Cambio, who wanted a dome but was unable to design it himself. But he was confident that Florentine genius would find a way, given that the ancient Romans had done it with the Pantheon, which still stands.

248
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 249 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 $14: 42$
Page 249

EXAMPLE 9-13 A modern dome. The $1.2 \times 10^{6} \mathrm{~kg}$ dome of the Small Sports Palace in Rome (Fig. 9-34a) is supported by 36 buttresses positioned at a $38^{\circ}$ angle so that they connect smoothly with the dome. Calculate the components of the force, $F_{\mathrm{H}}$ and $F_{\mathrm{V}}$, that each buttress exerts on the dome so that the force acts purely in compression-that is, at a $38^{\circ}$ angle (Fig. 9-34b).

(a)

(b)

FIGURE 9-34 Example 9-13.
(a) The dome of the Small Sports Palace in Rome, built by Pier Luigi Nervi for the 1960 Olympics. (b) The force components each buttress exerts on the dome.

APPROACH We can find the vertical component $F_{\mathrm{V}}$ exerted upward by each buttress because each supports $\frac{1}{36}$ of the dome's weight. We find $F_{\mathrm{H}}$ knowing that the buttress needs to be under compression so $\overrightarrow{\mathbf{F}}=\overrightarrow{\mathbf{F}}_{\mathrm{V}}+\overrightarrow{\mathbf{F}}_{\mathrm{H}}$ acts at a $38^{\circ}$ angle.
SOLUTION The vertical load on each buttress is $\frac{1}{36}$ of the total weight. Thus
$$F_{\mathrm{V}}=\frac{m g}{36}=\frac{\left(1.2 \times 10^{6} \mathrm{~kg}\right)\left(9.8 \mathrm{~m} / \mathrm{s}^{2}\right)}{36}=330,000 \mathrm{~N} .$$

The force must act at a $38^{\circ}$ angle at the base of the dome in order to be purely compressive. Thus
$$\begin{aligned}
\tan 38^{\circ} & =\frac{F_{\mathrm{V}}}{F_{\mathrm{H}}} \\
F_{\mathrm{H}} & =\frac{F_{\mathrm{V}}}{\tan 38^{\circ}}=\frac{330,000 \mathrm{~N}}{\tan 38^{\circ}}=420,000 \mathrm{~N} .
\end{aligned}$$

NOTE For each buttress to exert this $420,000-\mathrm{N}$ horizontal force, a prestressedconcrete tension ring surrounds the base of the buttresses beneath the ground (see Problem 53 and Fig. 9-75).

Summary

An object at rest is said to be in equilibrium. The subject concerned with the determination of the forces within a structure at rest is called statics.

The two necessary conditions for an object to be in equilibrium are (1) the vector sum of all the forces on it must be zero, and (2) the sum of all the torques (calculated about any arbitrary axis) must also be zero. For a two-dimensional problem we can write
$$\Sigma F_{x}=0, \quad \Sigma F_{y}=0, \quad \Sigma \tau=0 . \quad(\mathbf{9}-\mathbf{1}, \mathbf{9}-\mathbf{2})$$

It is important when doing statics problems to apply the equilibrium conditions to only one object at a time.

An object in static equilibrium is said to be in (a) stable, (b) unstable, or (c) neutral equilibrium, depending on whether a slight displacement leads to (a) a return to the original position, (b) further movement away from the original position, or (c) rest in the new position. An object in stable equilibrium is also said to be in balance.

Hooke's law applies to many elastic solids, and states that the change in length of an object is proportional to the
applied force:
$$F=k \Delta \ell .$$

If the force is too great, the object will exceed its elastic limit, which means it will no longer return to its original shape when the distorting force is removed. If the force is even greater, the ultimate strength of the material can be exceeded, and the object will fracture. The force per unit area acting on an object is the stress, and the resulting fractional change in length is the strain.

The stress on an object is present within the object and can be of three types: compression, tension, or shear. The ratio of stress to strain is called the elastic modulus of the material. Young's modulus applies for compression and tension, and the shear modulus for shear. Bulk modulus applies to an object whose volume changes as a result of pressure on all sides. All three moduli are constants for a given material when distorted within the elastic region.
[*Arches and domes are special ways to span a space that allow the stresses to be managed well.]

Summary
249

---

<!-- Page 250 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 250

Questions
1. Describe several situations in which an object is not in equilibrium, even though the net force on it is zero.
2. A bungee jumper momentarily comes to rest at the bottom of the dive before he springs back upward. At that moment, is the bungee jumper in equilibrium? Explain.
3. You can find the center of gravity of a meter stick by resting it horizontally on your two index fingers, and then slowly drawing your fingers together. First the meter stick will slip on one finger, and then on the other, but eventually the fingers meet at the cg. Why does this work?
4. Your doctor's scale has arms on which weights slide to counter your weight, Fig. 9-35. These weights are much lighter than you are. How does this work?

FIGURE 9-35
Question 4.
5. A ground retaining wall is shown in Fig. 9-36a. The ground, particularly when wet, can exert a significant force $F$ on the wall. (a) What force produces the torque to keep the wall upright? (b) Explain why the retaining wall in Fig. 9-36b would be much less likely to overturn than that in Fig. 9-36a.

FIGURE 9-36 Question 5.
6. Can the sum of the torques on an object be zero while the net force on the object is nonzero? Explain.
7. A ladder, leaning against a wall, makes a $60^{\circ}$ angle with the ground. When is it more likely to slip: when a person stands on the ladder near the top or near the bottom? Explain.
8. A uniform meter stick supported at the $25-\mathrm{cm}$ mark is in equilibrium when a $1-\mathrm{kg}$ rock is suspended at the $0-\mathrm{cm}$ end (as shown in Fig. 9-37). Is the mass of the meter stick greater than, equal to, or less than the mass of the rock? Explain your reasoning.

FIGURE 9-37 Question 8.
9. Why do you tend to lean backward when carrying a heavy load in your arms?
10. Figure 9-38 shows a cone. Explain how to lay it on a flat table so that it is in (a) stable equilibrium, (b) unstable equilibrium, (c) neutral equilibrium.

FIGURE 9-38 Question 10.
11. Place yourself facing the edge of an open door. Position your feet astride the door with your nose and abdomen touching the door's edge. Try to rise on your tiptoes. Why can't this be done?
12. Why is it not possible to sit upright in a chair and rise to your feet without first leaning forward?
13. Why is it more difficult to do sit-ups when your knees are bent than when your legs are stretched out?
14. Explain why touching your toes while you are seated on the floor with outstretched legs produces less stress on the lower spinal column than when touching your toes from a standing position. Use a diagram.
15. Which configuration of bricks, Fig. 9-39a or Fig. 9-39b, is the more likely to be stable? Why?

FIGURE 9-39 Question 15. The dots indicate the CG of each brick (assumed uniform). The fractions $\frac{1}{4}$ and $\frac{1}{2}$ indicate what portion of each brick is hanging beyond its support.
16. Name the type of equilibrium for each position of the ball in Fig. 9-40.

FIGURE 9-40 Question 16.
17. Is the Young's modulus for a bungee cord smaller or larger than that for an ordinary rope?
18. Examine how a pair of scissors or shears cuts through a piece of cardboard. Is the name "shears" justified? Explain.
19. Materials such as ordinary concrete and stone are very weak under tension or shear. Would it be wise to use such a material for either of the supports of the cantilever shown in Fig. 9-9? If so, which one(s)? Explain.

250
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 251 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 25 」
MisConceptual Questions
1. A $60-\mathrm{kg}$ woman stands on the very end of a uniform board, of length $\ell$, which is supported one-quarter of the way from one end and is balanced (Fig. 9-41). What is the mass of the board?
(a) 15 kg .
(b) 20 kg .
(c) 30 kg .
(d) 60 kg .
(e) 120 kg .

FIGURE 9-41
MisConceptual
Question 1.
2. When you apply the torque equation $\sum \tau=0$ to an object in equilibrium, the axis about which torques are calculated
(a) must be located at a pivot.
(b) must be located at the object's center of gravity.
(c) should be located at the edge of the object.
(d) can be located anywhere.
3. A uniform beam is hinged at one end and held in a horizontal position by a cable, as shown in Fig. 9-42. The tension in the cable
(a) must be at least half the weight of the beam, no matter what the angle of the cable.
(b) could be less than half the beam's weight for some angles.
(c) will be half the beam's weight for all angles.
(d) will equal the beam's weight for all angles.

FIGURE 9-42
MisConceptual Question 3: beam and cable.
4. A heavy ball suspended by a cable is pulled to the side by a horizontal force $\overrightarrow{\mathbf{F}}$ as shown in Fig. 9-43. If angle $\theta$ is small, the magnitude of the force $F$ can be less than the weight of the ball because:
(a) the force holds up only part of the ball's weight.
(b) even though the ball is stationary, it is not really in equilibrium.
(c) $\overrightarrow{\mathbf{F}}$ is equal to only the $x$ component of the tension in the cable.
(d) the original statement is not true. To move the ball, $\overrightarrow{\mathbf{F}}$ must be at least equal to the ball's weight.

FIGURE 9-43
MisConceptual Question 4.
5. Two children are balanced on opposite sides of a seesaw. If one child leans inward toward the pivot point, her side will (a) rise.
(b) fall.
(c) neither rise nor fall.
6. A $10.0-\mathrm{N}$ weight is suspended by two cords as shown in Fig. 9-44. What can you say about the tension in the two cords?
(a) The tension in both cords is 5.0 N .
(b) The tension in both cords is equal but not 5.0 N .
(c) The tension in cord A is greater than that in cord B .
(d) The tension in cord B is greater than that in cord A .
7. As you increase the force that you apply while pulling on a rope, which of the following is NOT affected?
(a) The stress on the rope.
(b) The strain on the rope.
(c) The Young's modulus of the rope.
(d) All of the above.
(e) None of the above.
8. A woman is balancing on a high wire which is tightly strung, as shown in Fig. 9-45. The tension in the wire is
(a) about half the woman's weight.
(b) about twice the woman's weight.
(c) about equal to the woman's weight.
(d) much less than the woman's weight.
(e) much more than the woman's weight.

FIGURE 9-45
MisConceptual Question 8.
9. A parking garage is designed for two levels of cars. To make more money, the owner decides to double the size of the garage in each dimension (length, width, and number of levels). For the support columns to hold up four floors instead of two, how should he change the columns' diameter?
(a) Double the area of the columns by increasing their diameter by a factor of 2 .
(b) Double the area of the columns by increasing their diameter by a factor of $\sqrt{2}$.
(c) Quadruple the area of the columns by increasing their diameter by a factor of 2 .
(d) Increase the area of the columns by a factor of 8 by increasing their diameter by a factor of $2 \sqrt{2}$.
(e) He doesn't need to increase the diameter of the columns.
10. A rubber band is stretched by 1.0 cm when a force of 0.35 N is applied to each end. If instead a force of 0.70 N is applied to each end, estimate how far the rubber band will stretch from its unstretched length:
(a) 0.25 cm .
(b) 0.5 cm .
(c) 1.0 cm .
(d) 2.0 cm .
(e) 4.0 cm .

MisConceptual Questions
251

---

<!-- Page 252 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 252

For assigned homework and other learning materials, go to the MasteringPhysics website.
MP

Problems

9-1 and 9-2 Equilibrium
1. (I) Three forces are applied to a tree sapling, as shown in Fig. 9-46, to stabilize it. If $\overrightarrow{\mathbf{F}}_{\mathrm{A}}=385 \mathrm{~N}$ and $\overrightarrow{\mathbf{F}}_{\mathrm{B}}=475 \mathrm{~N}$, find $\overrightarrow{\mathbf{F}}_{\mathrm{C}}$ in magnitude and direction.

FIGURE 9-46
Problem 1.
2. (I) Calculate the mass $m$ needed in order to suspend the leg shown in Fig. 9-47. Assume the leg (with cast) has a mass of 15.0 kg , and its CG is 35.0 cm from the hip joint; the cord holding the sling is 78.0 cm from the hip joint.

FIGURE 9-47 Problem 2.
3. (I) A tower crane (Fig. 9-48a) must always be carefully balanced so that there is no net torque tending to tip it. A particular crane at a building site is about to lift a $2800-\mathrm{kg}$ air-conditioning unit. The crane's dimensions are shown in Fig. 9-48b. (a) Where must the crane's $9500-\mathrm{kg}$ counterweight be placed when the load is lifted from the ground? (The counterweight is usually moved automatically via sensors and motors to precisely compensate for the load.) (b) Determine the maximum load that can be lifted with this counterweight when it is placed at its full extent. Ignore the mass of the beam.

(a)

Counterweight $M=9500 \mathrm{~kg}$

(b)

FIGURE 9-48
Problem 3.
4. (I) What is the mass of the diver in Fig. 9-49 if she exerts a torque of $1800 \mathrm{~m} \cdot \mathrm{~N}$ on the board, relative to the left (A) support post?

FIGURE 9-49 Problems 4 and 5.
5. (II) Calculate the forces $F_{\mathrm{A}}$ and $F_{\mathrm{B}}$ that the supports exert on the diving board of Fig. $9-49$ when a $52-\mathrm{kg}$ person stands at its tip. (a) Ignore the weight of the board. (b) Take into account the board's mass of 28 kg . Assume the board's CG is at its center.
6. (II) Figure 9-50 shows a pair of forceps used to hold a thin plastic rod firmly. If the thumb and finger each squeeze with a force $F_{\mathrm{T}}=F_{\mathrm{F}}=11.0 \mathrm{~N}$, what force do the forceps jaws exert on the plastic rod?

FIGURE 9-50
Problem 6.
7. (II) Two cords support a chandelier in the manner shown in Fig. 9-4 except that the upper cord makes an angle of $45^{\circ}$ with the ceiling. If the cords can sustain a force of 1660 N without breaking, what is the maximum chandelier weight that can be supported?
8. (II) The two trees in Fig. 9-51 are 6.6 m apart. A backpacker is trying to lift his pack out of the reach of bears. Calculate the magnitude of the force $\overrightarrow{\mathbf{F}}$ that he must exert downward to hold a $19-\mathrm{kg}$ backpack so that the rope sags at its midpoint by (a) 1.5 m , (b) 0.15 m .

FIGURE 9-51
Problems 8 and 70.
9. (II) A $110-\mathrm{kg}$ horizontal beam is supported at each end. A $320-\mathrm{kg}$ piano rests a quarter of the way from one end. What is the vertical force on each of the supports?
10. (II) Calculate $F_{\mathrm{A}}$ and $F_{\mathrm{B}}$ for the uniform cantilever shown in Fig. 9-9 whose mass is 1200 kg .
11. (II) A $75-\mathrm{kg}$ adult sits at one end of a $9.0-\mathrm{m}-$ long board. His $25-\mathrm{kg}$ child sits on the other end. (a) Where should the pivot be placed so that the board is balanced, ignoring the board's mass? (b) Find the pivot point if the board is uniform and has a mass of 15 kg .

252
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 253 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 25ʒ
12. (II) Find the tension in the two cords shown in Fig. 9-52. Neglect the mass of the cords, and assume that the angle $\theta$ is $33^{\circ}$ and the mass $m$ is 190 kg .

FIGURE 9-52
Problem 12.
13. (II) Find the tension in the two wires supporting the traffic light shown in Fig. 9-53.

FIGURE 9-53
Problem 13.
14. (II) How close to the edge of the $24.0-\mathrm{kg}$ table shown in Fig. $9-54$ can a $66.0-\mathrm{kg}$ person sit without tipping it over?

FIGURE 9-54
Problem 14.
15. (II) The force required to pull the cork out of the top of a wine bottle is in the range of 200 to 400 N . What range of forces $F$ is required to open a wine bottle with the bottle opener shown in Fig. 9-55?

FIGURE 9-55
Problem 15.
16. (II) Calculate $F_{\mathrm{A}}$ and $F_{\mathrm{B}}$ for the beam shown in Fig. 9-56. The downward forces represent the weights of machinery on the beam. Assume the beam is uniform and has a mass of 280 kg .

FIGURE 9-56
Problem 16.
17. (II) Three children are trying to balance on a seesaw, which includes a fulcrum rock acting as a pivot at the center, and a very light board 3.2 m long (Fig. 9-57). Two playmates are already on either end. Boy A has a mass of 45 kg , and boy B a mass of 35 kg . Where should girl C, whose mass is 25 kg , place herself so as to balance the seesaw?

FIGURE 9-57 Problem 17.
18. (II) A shop sign weighing 215 N hangs from the end of a uniform 155-N beam as shown in Fig. 9-58. Find the tension in

FIGURE 9-58
Problem 18.
19. (II) A traffic light hangs from a pole as shown in Fig. 9-59. The uniform aluminum pole AB is 7.20 m long and has a mass of 12.0 kg . The mass of the traffic light is 21.5 kg . Determine (a) the tension in the horizontal massless cable CD, and ( $b$ ) the vertical and horizontal components of the force exerted by the pivot A on the aluminum pole.

FIGURE 9-59
Problem 19.
20. (II) A uniform steel beam has a mass of 940 kg . On it is resting half of an identical beam, as shown in Fig. 9-60. What is the vertical support force at each end?

FIGURE 9-60 Problem 20.

Problems
253

---

<!-- Page 254 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 25 A
21. (II) A $2500-\mathrm{kg}$ trailer is attached to a stationary truck at point B, Fig. 9-61. Determine the normal force exerted by the road on the rear tires at A , and the vertical force exerted on the trailer by the support B .

FIGURE 9-61 Problem 21.
22. (II) A $20.0-\mathrm{m}$-long uniform beam weighing 650 N rests on walls A and B , as shown in Fig. 9-62. (a) Find the maximum weight of a person who can walk to the extreme end D without tipping the beam. Find the forces that the walls $A$ and $B$ exert on the beam when the person is standing: (b) at D ; (c) 2.0 m to the right of A .

FIGURE 9-62 Problem 22.
23. (II) A $0.75-\mathrm{kg}$ sheet is centered on a clothesline as shown in Fig. 9-63. The clothesline on either side of the hanging sheet makes an angle of $3.5^{\circ}$ with the horizontal. Calculate the tension in the clothesline (ignore its mass) on either side of the sheet. Why is the tension so much greater than the weight of the sheet?

FIGURE 9-63
Problem 23.
24. (II) A 172-cm-tall person lies on a light (massless) board which is supported by two scales, one under the top of her head and one beneath the bottom of her feet (Fig. 9-64). The two scales read, respectively, 35.1 and 31.6 kg . What distance is the center of gravity of this person from the bottom of her feet?

FIGURE 9-64 Problem 24.
25. (II) A man doing push-ups pauses in the position shown in Fig. $9-65$. His mass $m=68 \mathrm{~kg}$. Determine the normal force exerted by the floor ( $a$ ) on each hand; ( $b$ ) on each foot.

FIGURE 9-65 Problem 25.
26. (III) Two wires run from the top of a pole 2.6 m tall that supports a volleyball net. The two wires are anchored to the ground 2.0 m apart, and each is 2.0 m from the pole

FIGURE 9-66
Problem 26.
27. (III) A uniform rod AB of length 5.0 m and mass $M=3.8 \mathrm{~kg}$ is hinged at A and held in equilibrium by a light cord, as shown in Fig. 9-67. A load $W=22 \mathrm{~N}$ hangs from the rod at a distance $d$ so that the tension in the cord is 85 N . (a) Draw a free-body diagram for the rod. (b) Determine the vertical and horizontal forces on the rod exerted by the hinge. (c) Determine $d$ from the appropriate torque equation.

FIGURE 9-67
Problem 27.
28. (III) You are on a pirate ship and being forced to walk the plank (Fig. 9-68). You are standing at the point marked C. The plank is nailed onto the deck at point A , and rests on the support 0.75 m away from A . The center of mass of the uniform plank is located at point B . Your mass is 65 kg and the mass of the plank is 45 kg . What is the minimum downward force the nails must exert on the plank to hold it in place?

FIGURE 9-68
Problem 28.

254
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 255 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 255
29. (III) A door 2.30 m high and 1.30 m wide has a mass of 13.0 kg . A hinge 0.40 m from the top and another hinge 0.40 m from the bottom each support half the door's weight (Fig. 9-69). Assume that the center of gravity is at the geometrical center of the door, and determine the horizontal and vertical force components exerted by each hinge on the door.

FIGURE 9-69
Problem 29.

9-3 Muscles and Joints
30. (I) Suppose the point of insertion of the biceps muscle into the lower arm shown in Fig. 9-13a (Example 9-8) is 6.0 cm instead of 5.0 cm ; how much mass could the person hold with a muscle exertion of 450 N ?
31. (I) Approximately what magnitude force, $F_{\mathrm{M}}$, must the extensor muscle in the upper arm exert on the lower arm to hold a $7.3-\mathrm{kg}$ shot put (Fig. 9-70)? Assume the lower arm has a mass of 2.3 kg and its CG is 12.0 cm from the elbow-joint pivot.

FIGURE 9-70
Problem 31.
32. (II) (a) Calculate the magnitude of the force, $F_{\mathrm{M}}$, required of the "deltoid" muscle to hold up the outstretched arm shown in Fig. 9-71. The total mass of the arm is 3.3 kg . (b) Calculate the magnitude of the force $F_{\mathrm{J}}$ exerted by the shoulder joint on the upper arm and the angle (to the horizontal) at which it acts.

FIGURE 9-71 Problems 32 and 33.
33. (II) Suppose the hand in Problem 32 holds an $8.5-\mathrm{kg}$ mass. What force, $F_{\mathrm{M}}$, is required of the deltoid muscle, assuming the mass is 52 cm from the shoulder joint?
34. (II) If 25 kg is the maximum mass $m$ that a person can hold in a hand when the arm is positioned with a $105^{\circ}$ angle at the elbow as shown in Fig. 9-72, what is the maximum force $F_{\mathrm{m}}$ that the biceps muscle exerts on the forearm? Assume the forearm and hand have a total mass of 2.0 kg with a cg that is 15 cm from the elbow, and that the biceps muscle attaches 5.0 cm
from the elbow.

FIGURE 9-72
Problem 34.

\section*{9-4 Stability and Balance}
35. (II) The Leaning Tower of Pisa is 55 m tall and about 7.7 m in radius. The top is 4.5 m off center. Is the tower in stable equilibrium? If so, how much farther can it lean before it becomes unstable? Assume the tower is of uniform composition.
36. (III) Four bricks are to be stacked at the edge of a table, each brick overhanging the one below it, so that the top brick extends as far as possible beyond the edge of the table. (a) To achieve this, show that successive bricks must extend no more than (starting at the top) $\frac{1}{2}, \frac{1}{4}, \frac{1}{6}$, and $\frac{1}{8}$ of their length beyond the one below (Fig. 9-73a). (b) Is the top brick completely beyond the base? (c) Determine a general formula for the maximum total distance spanned by $n$ bricks if they are to remain stable. (d) A builder wants to construct a corbeled arch (Fig. 9-73b) based on the principle of stability discussed in (a) and (c) above. What minimum number of bricks, each 0.30 m long and uniform, is needed if the arch is to span 1.0 m ?

FIGURE 9-73 Problem 36.

Problems
255

---

<!-- Page 256 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 256

9-5 Elasticity; Stress and Strain
37. (I) A nylon string on a tennis racket is under a tension of 275 N . If its diameter is 1.00 mm , by how much is it lengthened from its untensioned length of 30.0 cm ?
38. (I) A marble column of cross-sectional area $1.4 \mathrm{~m}^{2}$ supports a mass of $25,000 \mathrm{~kg}$. (a) What is the stress within the column? (b) What is the strain?
39. (I) By how much is the column in Problem 38 shortened if it is 8.6 m high?
40. (I) A sign (mass 1700 kg ) hangs from the bottom end of a vertical steel girder with a cross-sectional area of $0.012 \mathrm{~m}^{2}$. (a) What is the stress within the girder? (b) What is the strain on the girder? (c) If the girder is 9.50 m long, how much is it lengthened? (Ignore the mass of the girder itself.)
41. (II) One liter of alcohol ( $1000 \mathrm{~cm}^{3}$ ) in a flexible container is carried to the bottom of the sea, where the pressure is $2.6 \times 10^{6} \mathrm{~N} / \mathrm{m}^{2}$. What will be its volume there?
42. (II) How much pressure is needed to compress the volume of an iron block by $0.10 \%$ ? Express your answer in $\mathrm{N} / \mathrm{m}^{2}$, and compare it to atmospheric pressure $\left(1.0 \times 10^{5} \mathrm{~N} / \mathrm{m}^{2}\right)$.
43. (II) A $15-\mathrm{cm}$-long tendon was found to stretch 3.7 mm by a force of 13.4 N . The tendon was approximately round with an average diameter of 8.5 mm . Calculate Young's modulus of this tendon.
44. (II) A steel wire 2.3 mm in diameter stretches by $0.030 \%$ when a mass is suspended from it. How large is the mass?
45. (II) At depths of 2000 m in the sea, the pressure is about 200 times atmospheric pressure ( $1 \mathrm{~atm}=1.0 \times 10^{5} \mathrm{~N} / \mathrm{m}^{2}$ ). By what percentage does the interior space of an iron bathysphere's volume change at this depth?
9-6 Fracture
46. (I) The femur bone in the human leg has a minimum effective cross section of about $3.0 \mathrm{~cm}^{2}\left(=3.0 \times 10^{-4} \mathrm{~m}^{2}\right)$. How much compressive force can it withstand before breaking?
47. (II) (a) What is the maximum tension possible in a $1.00-\mathrm{mm}$-diameter nylon tennis racket string? (b) If you want tighter strings, what do you do to prevent breakage: use thinner or thicker strings? Why? What causes strings to break when they are hit by the ball?
48. (II) (a) What is the minimum cross-sectional area required of a vertical steel cable from which is suspended a $270-\mathrm{kg}$ chandelier? Assume a safety factor of 7.0. (b) If the cable is 7.5 m long, how much does it elongate?
49. (II) Assume the supports of the uniform cantilever shown in Fig. $9-74(m=2900 \mathrm{~kg})$ are made of wood. Calculate the minimum cross-sectional area required of each, assuming a safety factor of 9.0.

FIGURE 9-74
Problem 49.
50. (II) An iron bolt is used to connect two iron plates together. The bolt must withstand shear forces up to about 3300 N. Calculate the minimum diameter for the bolt, based on a safety factor of 7.0.
51. (III) A steel cable is to support an elevator whose total (loaded) mass is not to exceed 3100 kg . If the maximum acceleration of the elevator is $1.8 \mathrm{~m} / \mathrm{s}^{2}$, calculate the diameter of cable required. Assume a safety factor of 8.0.
*9-7 Arches and Domes
*52. (II) How high must a pointed arch be if it is to span a space 8.0 m wide and exert one-third the horizontal force at its base that a round arch would?
*53. (II) The subterranean tension ring that exerts the balancing horizontal force on the abutments for the dome in Fig. 9-34 is 36 -sided, so each segment makes a $10^{\circ}$ angle with the adjacent one (Fig. 9-75). Calculate the tension $F$ that must exist in each segment so that the required force of $4.2 \times 10^{5} \mathrm{~N}$ can be exerted at each corner (Example 9-13).

FIGURE 9-75
Problem 53.

General Problems
54. A woman holds a $2.0-\mathrm{m}$-long uniform $10.0-\mathrm{kg}$ pole as shown in Fig. 9-76. (a) Determine the forces she must exert with each hand (magnitude and direction). To what position

FIGURE 9-76
Problem 54.
55. A cube of side $\ell$ rests on a rough floor. It is subjected to a steady horizontal pull $F$, exerted a distance $h$ above the floor as shown in Fig. 9-77. As $F$ is increased, the block will either begin to slide, or begin to tip over. Determine the coefficient of static friction $\mu_{\mathrm{s}}$ so that (a) the block begins to slide rather than tip; (b) the block begins to tip. [Hint: Where will the normal force on the block act if it tips?]

FIGURE 9-77
Problem 55.

256
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 257 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 257
56. A 50 -story building is being planned. It is to be 180.0 m high with a base 46.0 m by 76.0 m . Its total mass will be about $1.8 \times 10^{7} \mathrm{~kg}$, and its weight therefore about $1.8 \times 10^{8} \mathrm{~N}$. Suppose a $200-\mathrm{km} / \mathrm{h}$ wind exerts a force of $950 \mathrm{~N} / \mathrm{m}^{2}$ over the $76.0-\mathrm{m}$-wide face (Fig. 9-78). Calculate the torque about the potential pivot point, the rear edge of the building (where $\overrightarrow{\mathbf{F}}_{\mathrm{E}}$ acts in Fig. 9-78), and determine whether the building will topple. Assume the total force of the wind acts at the midpoint of the building's face, and that the building is not anchored in bedrock. [Hint: $\overrightarrow{\mathbf{F}}_{\mathrm{E}}$ in Fig. 9-78 represents the force that the Earth would exert on the building in the case where the building would just begin to tip.]

FIGURE 9-78 Forces on a building subjected to wind $\left(\overrightarrow{\mathbf{F}}_{\mathrm{A}}\right)$, gravity ( $m \overrightarrow{\mathbf{g}}$ ), and the force $\overrightarrow{\mathbf{F}}_{\mathrm{E}}$ on the building due to the Earth if the building were just about to tip. Problem 56.
57. A uniform meter stick with a mass of 180 g is supported horizontally by two vertical strings, one at the $0-\mathrm{cm}$ mark and the other at the $90-\mathrm{cm}$ mark (Fig. 9-79). What is the tension in the string (a) at 0 cm ? (b) at 90 cm ?

FIGURE 9-79 Problem 57.
58. There is a maximum height of a uniform vertical column made of any material that can support itself without buckling, and it is independent of the cross-sectional area (why?). Calculate this height for (a) steel (density $7.8 \times 10^{3} \mathrm{~kg} / \mathrm{m}^{3}$ ), and (b) granite (density $2.7 \times 10^{3} \mathrm{~kg} / \mathrm{m}^{3}$ ).

FIGURE 9-81
Problem 60.
59. When a mass of 25 kg is hung from the middle of a fixed straight aluminum wire, the wire sags to make an angle of $12^{\circ}$ with the horizontal as shown in Fig. 9-80. Determine the radius of the wire.
60. A $65.0-\mathrm{kg}$ painter is on a uniform $25-\mathrm{kg}$ scaffold supported from above by ropes (Fig. 9-81). There is a $4.0-\mathrm{kg}$ pail of paint to one side, as shown. Can the painter walk safely to both ends of the scaffold? If not, which end(s) is dangerous, and how close to the end can he approach safely?
61. A $15.0-\mathrm{kg}$ ball is supported from the ceiling by rope A . Rope B pulls downward and to
the side on the ball. If the angle of A to the vertical is $22^{\circ}$ and if B makes an angle of $53^{\circ}$ to the vertical (Fig. 9-82), find the tensions in ropes A and B .

FIGURE 9-82
Problem 61.
62. The roof over a $9.0-\mathrm{m} \times 10.0-\mathrm{m}$ room in a school has a total mass of $13,600 \mathrm{~kg}$. The roof is to be supported by vertical wooden " $2 \times 4 \mathrm{~s}$ " (actually about $4.0 \mathrm{~cm} \times 9.0 \mathrm{~cm}$ ) equally spaced along the $10.0-\mathrm{m}$ sides. How many supports are required on each side, and how far apart must they be? Consider only compression, and assume a safety factor of 12 .
63. A $23.0-\mathrm{kg}$ backpack is suspended midway between two trees by a light cord as in Fig. 9-51. A bear grabs the backpack and pulls vertically downward with a constant force, so that each section of cord makes an angle of $27^{\circ}$ below the horizontal. Initially, without the bear pulling, the angle was $15^{\circ}$; the tension in the cord with the bear pulling is double what it was when he was not. Calculate the force the bear is exerting on the backpack.

General Problems
257

---

<!-- Page 258 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 258
64. Two identical, uniform beams are symmetrically set up against each other (Fig. 9-83) on a floor with which they have a coefficient of friction $\mu_{\mathrm{s}}=0.50$. What is the minimum angle the beams can make with the floor and still not fall?

FIGURE 9-83
Problem 64.
65. A steel rod of radius $R=15 \mathrm{~cm}$ and length $\ell_{0}$ stands upright on a firm surface. A $65-\mathrm{kg}$ man climbs atop the rod. (a) Determine the percent decrease in the rod's length. (b) When a metal is compressed, each atom moves closer to its neighboring atom by exactly the same fractional amount. If iron atoms in steel are normally $2.0 \times 10^{-10} \mathrm{~m}$ apart, by what distance did this interatomic spacing have to change in order to produce the normal force required to support the man? [Note: Neighboring atoms repel each other, and this repulsion accounts for the observed normal force.]
66. A $2.0-\mathrm{m}$-high box with a $1.0-\mathrm{m}$-square base is moved across a rough floor as in Fig. 9-84. The uniform box weighs 250 N and has a coefficient of static friction with the floor of 0.60 . What minimum force must be exerted on the box to make it slide? What is the maximum height $h$ above the floor that this force can be applied without tipping the box over? Note that as the box tips, the normal force

FIGURE 9-84
Problem 66.
and the friction force will act at the lowest corner.
67. A tightly stretched horizontal "high wire" is 36 m long. It sags vertically 2.1 m when a $60.0-\mathrm{kg}$ tightrope walker stands at its center. What is the tension in the wire? Is it possible to increase the tension in the wire so that there is no sag?
68. Parachutists whose chutes have failed to open have been known to survive if they land in deep snow. Assume that a $75-\mathrm{kg}$ parachutist hits the ground with an area of impact of $0.30 \mathrm{~m}^{2}$ at a velocity of $55 \mathrm{~m} / \mathrm{s}$, and that the ultimate strength of body tissue is $5 \times 10^{5} \mathrm{~N} / \mathrm{m}^{2}$. Assume that the person is brought to rest in 1.0 m of snow. Show that the person may escape serious injury.
69. If the left vertical support column in Example 9-5 is made of steel, what is its cross-sectional area? Assume that a safety factor of 3 was used in its design to avoid fracture.
70. The mobile in Fig. 9-85 is in equilibrium. Object B has mass of 0.748 kg . Determine the masses of objects A, C, and D. (Neglect the weights of the crossbars.)

258
CHAPTER 9 Static Equilibrium; Elasticity and Fracture

---

<!-- Page 259 -->

GIAN_PPA7_GE_09_230-259v5.3HR1.QXD 29-08-2014 14:42 Page 259
71. When a wood shelf of mass 6.6 kg is fastened inside a slot in a vertical support as shown in Fig. 9-86, the support exerts a torque on the shelf. (a) Draw a free-body diagram for the shelf, assuming three vertical forces (two exerted by the support slot-explain why). Then calculate ( $b$ ) the magnitudes of the three forces and (c) the torque exerted by the support (about the left end of the shelf).

FIGURE 9-86
Problem 71.
72. A cubic crate of side $s=2.0 \mathrm{~m}$ is top-heavy: its CG is 18 cm above its true center. How steep an incline can the crate rest on without tipping over? [Hint: The normal force would act at the lowest corner.]

Search and Learn
1. Suppose a $65-\mathrm{kg}$ person jumps from a height of 3.0 m down to the ground. (a) What is the speed of the person just before landing (Chapter 2)? (b) Estimate the average force on the person's feet exerted by the ground to bring the person to rest, if the knees are bent so the person's CG moves a distance $d=50 \mathrm{~cm}$ during the deceleration period (Fig. 9-87). [Hint: This force exerted by the ground $\neq$ net force. You may want to consult Chapters 2, 4, and 7, and be sure to draw a careful free-body diagram of the person.] (c) Estimate the decelerating force if the person lands stiff-legged so $d \approx 1.0 \mathrm{~cm}$. (d) Estimate the stress in the tibia (a lower leg bone of area $=3.0 \times 10^{-4} \mathrm{~m}^{2}$ ), and determine whether or not the bone will break if the landing is made with bent legs ( $d=50 \mathrm{~cm}$ ). (e) Estimate the stress and determine if the tibia will break in a stifflegged landing ( $d=1.0 \mathrm{~cm}$ ).

FIGURE 9-87
Search and Learn 1.
2. From what minimum height must a $1.2-\mathrm{kg}$ rectangular brick $15.0 \mathrm{~cm} \times 6.0 \mathrm{~cm} \times 4.0 \mathrm{~cm}$ be dropped above a rigid steel floor in order to break the brick? Assume the brick strikes the floor directly on its largest face, and that the compression of the brick is much greater than that of the steel (that is, ignore compression of the steel). State other simplifying assumptions that may be necessary.
3. Consider a ladder with a painter climbing up it (Fig. 9-88). The mass of the uniform ladder is 12.0 kg , and the mass of the painter is 55.0 kg . If the ladder begins to slip at its base when the painter's feet are $70 \%$ of the way up the length of the ladder, what is the coefficient of static friction between the ladder and the floor? Assume the wall is frictionless.

FIGURE 9-88
Search and Learn 3.

ANSWERS TO EXERCISES
A: $F_{\mathrm{A}}$ also has a component to balance the sideways force $F_{\mathrm{B}}$.
B: Yes: $\cos \theta$ (angle of bar with ground) appears on both sides and cancels out.

C: $F_{\mathrm{N}}=m_{\mathrm{A}} g+m_{\mathrm{B}} g+M g$
$$=(30 \mathrm{~kg}+25 \mathrm{~kg}+4.0 \mathrm{~kg}) g=560 \mathrm{~N} .$$

D: (a).
E: (b).

Search and Learn
259

---

