# Theory

<b style="color:blue">DC Machine:</b><br/>

In the dc machine, the field winding is placed on the stator and the armature winding on the rotor. A dc current is passed through the field winding to
produce flux in the machine. Voltage induced in the armature winding is alternating. A mechanical commutator and a brush assembly function as a rectifier or inverter, make the
armature terminal voltage unidirectional.<br/><br>

<div align="center">
<img class="img-fluid"  src="./images/motor1.png" alt=""><br>                  
</div><br>

<br/><b>Application:</b><br/>
Although a dc machine can be operated as either a generator or a motor, at present its use as a generator is limited because of the wide spread use of ac power. The dc machine is extensively
used as a motor in industry. Its speed can be controlled over a wide range with relative ease. Large dc motors (in tens or hundreds of horsepower) are used in machine tools, printing
presses, fans, pumps, hoists, cranes, paper mills, textile mills, rolling mills, and so forth. Additionally, dc motors still dominate as traction motors used in transit cars and locomotives.
Small dc machines (in fractional horsepower rating) are used primarily as control devices—such as tachogenerators for speed sensing and servomotors for positioning and	tracking.
The dc machine definitely plays an important role in industry.<br/>

<br/><b style="color:blue">Speed Control of D.C. Motors:</b><br/>
The term ‘speed control’ stands for intentional speed variation, carried out manually or automatically. Natural speed change due to load, is not included in the term ‘speed control’.
D.C. motors are most suitable for wide range speed control and are, therefore, indispensable for many adjustable speed drives. The speed of a d.c. motor is given by below equation.

$$\omega = \frac{V_t - I_a r_a}{K_a \Phi}$$

where 

$$K_a = \frac{PZ}{2\pi a}$$

Where &omega; = Angular speed of the dc motor<br/>
V<sub>t</sub> = Terminal voltage dc motor<br/>
I<sub>a</sub> = Armature current of dc motor<br/>
r<sub>a</sub> = Armature resistance of dc motor<br/>
P = No of poles<br/>
Z = number of armature conductors<br/>
&phi; is the magnetic flux<br/>

there are basically three methods of speed control and these are :<br/><br/>

(i) Variation of resistance in the armature circuit,<br/>
(ii) Variation of the field flux, <br/>
(iii) Variation of the armature terminal voltage.<br/>

Before describing these methods, it is preferable to define the terms base speed, speed	regulation, speed range, constant power drive and constant torque drive.<br/>

<b>Base Speed:</b><br/>
It is defined as the speed at which a motor runs at rated armature voltage and rated field current. Base speed is equal to the rated speed or nameplate speed of the motor.

<br/><br/><b>Speed regulation:</b><br/>
If the speed-change from no load to full load is &Delta;&omega;<sub>m</sub> then speed regulation is defined as the ratio of &Delta;&omega;<sub>m</sub> to rated speed (or base speed) &omega;<sub>m</sub>
				
The percentage speed regulation = 

$$\frac{\Delta \omega_m}{\omega_m}\times 100$$

<br/><br/><b>Speed range</b><br/>
It is defined as the ratio of the maximum allowable speed to minimum allowable speed of the motor. When the speed range of a motor is specified, it must be mentioned 
whether this speed range is at no-load, full load or a fraction of full load.<br/>

<br/><br/><b>Constant power drive:</b><br/>
If the motor shaft power (shaft torque &times speed) remains constant over a given speed range, the system is called a constant power drive. Note that in constant 
power drive, higher torques are available at lower speeds and lower torques at higher speeds. The motor size is always decided by the highest torque requirement at the lowest speed.

<br/><br/><b>Constant torque drive:</b><br/>
If the motor shaft torque remains constant over a given speed range, the system is called a constant torque drive. Note that in constant torque drive, shaft 
power varies as the speed varies.

<br/><br/><b>Magnetic Braking:</b><br/>
Conventional braking systems in cars and bicycles utilise the friction force between two objects pressed together to slow an object down. By making use of eddy currents,
magnetic braking can be achieved where the electromagnetic force between a magnet and a conductor in motion is used to create a repulsive and slowing force. If a conductor moves
past a stationary magnet, eddy currents will be induced in the conductor by the magnet, according to Faraday’s law of induction. Eddy currents create their own magnetic field that
opposes the original magnetic field of the magnet. This in turn creates a drag force between the magnet and the conductor, which slows the conductor down.
A permanent magnet or an electromagnet can be used to create the magnetic field in a magnetic brake. A big advantage with magnetic braking is the lack of physical contact
between components. A disadvantage with magnetic braking is that when there is no motion between the magnet and conductor,
there is no static force to maintain the conductor at rest. In this case, the magnetic braking system would need to be supplemented by a friction­ based (conventional) braking system
like a hand brake.<br/>

<!--<br/><b style="color:blue">Types of DC Motors</b><br/>
Two main types are Shunt motor and series motor.
<br/><b>Shunt Motor</b><br/>

A schematic diagram of a shunt dc motor is shown in Fig. below. The armature circuit and the shunt field circuit are connected across a dc source of fixed voltage V<sub>t</sub>.
An external field rheostat (R<sub>fc</sub>) is used in the field circuit to control the speed of the motor. The motor takes power from the dc source, 
and therefore the current It flows into the machine from the positive terminal of the dc source. As both field circuit and armature circuit are connected to a dc source of fixed
voltage, the connections for separate and shunt excitation are the same. The behavior of the field circuit is independent of the armature circuit.
The governing equations for steady-state operation of the dc motor are as follows:

$$V_t =I_a R_a + E_a$$

$$I_t = I_a +I_f$$

$$E_a = K_a \Phi \omega_m$$

$$= V_t - I_a R_a$$

The armature current I<sub>a</sub> and the motor speed &omega;m depend on the mechanical load connected to the motor shaft.<br/>
<div align="center">
<img class="img-fluid"  src="./images/shmotor_eq.png" alt=""><br>                  
</div><br>-->
<br/><b>Speed Control</b><br/>

There are numerous applications where control of speed is required, as in rolling mills, cranes, hoists, elevators, machine tools, and transit system and locomotive drives.
DC motors are extensively used in many of these applications. Control of the speed of dc motors below and above the base (or rated) speed can easily be achieved.
Besides, the methods of control are simpler and less expensive than those applicable to ac motors. The technology of speed control of dc motors has evolved considerably
over the past quarter-century. In the classical method, a Ward–Leonard system with rotating machines is used for speed control of dc motors. Recently,
solid-state converters have been used for this purpose. In this section, various methods of speed control of dc motors are discussed.<br/>

<br/><b>1. V<sub>t</sub> Control:</b><br/>
In the armature voltage control mode, the motor current I<sub>fm</sub> is kept constant at its rated value. The generator field current I<sub>fg</sub> is changed such that V<sub>t</sub> changes from zero to
its rated value. The speed will change from zero to the base speed. The torque can be maintained constant during operation in this range of speed, as shown in fig. below<br/> 

<br/><b>2.I<sub>f</sub> Control:</b><br/>

The field current control mode is used to obtain speed above the base speed. In this mode, the	armature voltage V<sub>t</sub> remains constant and the motor field current I<sub>fm</sub> is decreased (field
weakening) to obtain higher speeds. The armature current can be kept constant, there by	operating the motor in a constant horsepower mode. The torque obviously decreases as speed
increases, as shown in fig. below.<br/>

<br/><b>3. Armature Resistance Control Method</b><br/>
The armature resistance control is based on the principle that the speed of the motor is directly proportional to the back emf.
So, if the supply voltage and the armature resistance are kept at a constant value, the speed of the motor will be directly proportional to the armature current. 

<div align="center">
<img class="img-fluid"  src="./images/vf_if.png" alt=""><br>                  
</div><br>

Besides these there are other speed control methods like ward leonard system , Solid-state control using choppers and controlled rectifiers etc.

<br/><b>Open loop speed control:</b><br/>

As shown in the below figure, the armature-controlled dc motor is itself a feedback system, where back emf voltage is proportional to the speed of the motor.
The system may be arranged in input-output form such that V<sub>a</sub>(s) is the input and &omega;(s) is the output
The mathematical expression for open loop speed control is,

$$\omega(s) = \frac{\frac{ k_T}{R_a J}}{\frac{L_a}{R_a}s^2 + (1 + \frac{B L_a}{R_a J} )s + \frac{k_T k_b + R_a B}{R_a J}} V_{a}(s)$$

The ratio L<sub>a</sub>/ R<sub>a</sub> is called the motor electric-time constant, which makes the system speed response transfer function second order and is denoted by &tau;<sub>e</sub>.
L<sub>a</sub> in the armature circuit is very small, &tau;<sub>e</sub> is neglected, resulting in the simplified transfer function of the system. Thus, the speed of the motor shaft may be
simplified to
$$\omega(s) = \frac{\frac{k_T}{R_a J}}{s + \frac{k_T k_b + R_a B}{R_a J}}V_a(s)$$

<div align="center">
<img class="img-fluid"  src="./images/dcmol.png" alt=""><br>                  
</div><br>


<br/><b>Closed loop speed control:</b><br/>

<br/>DC motors are extensively used in many drives where speed control is desired. In many applications where a constant speed is required, open-loop operation of dc motors may not be
satisfactory. In open-loop operation, if load torque changes, the speed will change too. In a closed-loop system, the speed can be maintained constant by adjusting the motor terminal
voltage as the load torque changes. The basic block diagram of a closed-loop speed control system is shown in fig. below. If an additional load torque is applied, the motor speed
momentarily decreases and the speed error increases, which increases the control signal V<sub>c</sub>. The control signal increases the converter output voltage (the control signal decreases
the firing angle if the converter is a phase-controlled rectifier, or increases the duty ratio if the converter is a chopper). An increase in the motor armature voltage develops
more torque to restore the speed of the motor. The system thus passes through a transient period until the developed torque matches the applied load torque.<br/>

<div align="center">
<img class="img-fluid"  src="./images/cl_cntrl.png" alt=""><br>                  
</div><br>

There are other advantages of closed-loop operation, such as greater accuracy, improved dynamic response, and stability of operation. In a closed-loop system the drive characteristics
can also be made to operate at constant torque or constant horsepower over a certain speed range, a requirement in traction systems. Circuit protection can also be provided
in a closed-loop system. In fact, most industrial drive systems operate as closed-loop feedback systems.<br/>

<div align="center">
<img class="img-fluid"  src="./images/dcmcl.png" alt=""><br>                  
</div><br>

The mathematical expression for closed loop speed control is,

$$\omega(s) = \frac{\frac{k k_T k_g}{R_a J}}{s + (\frac{k_T k_b + R_a B + k_g k_T k}{R_a J})} \omega_{in}(s)$$
assuming L<sub>a</sub> = 0<br/>

Where,

J = Moment of inertia of the motor in kg-m<sup>2</sup><br/>
B = Viscous-friction coefficient of the motor in N-m/rad/sec<br/>
k<sub>g</sub> = Tachogenerator constant<br/>
k = Pre amplifier gain<br/>
k<sub>T</sub> = Motor torque constant<br/>
k<sub>b</sub> = Back emf constant<br/>
R<sub>a</sub> = Armature resistance in &ohm;<br/>
L<sub>a</sub> = Armature inductance in  henry<br/>
V<sub>a</sub> = Applied armature voltage in volts<br/>

<br/><b>Closed loop position control:</b><br/>
To control the position of the motor shaft, the simplest strategy is to use a proportional controller with gain K. The block diagram of the closed-loop system is shown in figure below.
The system is composed of an angular position sensor (usually an encoder or a potentiometer for position applications ). Note that, for simplicity, the input voltage can be scaled 
to a position input &theta;<sub>in</sub>(s) so that the input and output have the same units and scale. Alternatively, the output can be converted into voltage using the sensor gain value. The
closed-loop transfer function in this case becomes

$$\frac{\theta(s)}{\theta_{in}(s)} = \frac{\frac{k k_T k_s}{R_a J}}{s^2 + (\frac{R_a B + k_T k_b}{R_a J})s +\frac{k k_T k_s}{R_a J}}$$

k<sub>s</sub> = Sensor gain<br/>


<b> Some important Formulas:</b><br/>

if V is the supply voltage, E<sub>b</sub> is the back emf produced and I<sub>a</sub>, R<sub>a</sub> are the armature current and armature resistance respectively
then the voltage equation is given by,

$$V = E_b + I_a R_a ----(1)$$ 

we multiply both sides of equation (1) by I<sub>a</sub>

$$V I_a = E_b I_a + I_a^{2} R_a ----(2)$$ 

Now Ia<sup>2</sup>Ra is the power loss due to heating of the armature coil, and the true effective mechanical power that is required to produce the desired torque of DC machine
is given by,

$$p_m = E_b I_a -----------(3)$$

The mechanical power P<sub>m</sub> is related to the electromagnetic torque T<sub>g</sub> as,

$$p_m = T_g \omega -----------(4)$$

Where, &omega; is speed in rad/sec.Now equating equation (3) and (4) we get,

$$E_b I_a = T_g \omega -----------(5)$$

Now for simplifying the torque equation of DC motor we substitute.

$$E_b = \frac{P \phi Z N}{60A} -----------(6)$$ 

Substituting equation (5) and (6) in equation (3), we get:

$$T_g = \frac{P \phi Z I_a}{2\pi A} -----------(7)$$ 

This is the torque equation of DC motor. It can be further simplified as:

$$T_g = K_a \phi I_a$$

where,

$$K_a = \frac{PZ}{2 \pi A}$$ 

Where, P is no of poles,<br/>
&phi; is flux per pole,<br/>
Z is no. of conductors,<br/>
A is no. of parallel paths,<br/>
and N is the speed of the DC motor
						
						
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>								
