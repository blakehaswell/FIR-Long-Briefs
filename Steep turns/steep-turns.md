---
marp: true
theme: gaia
class: invert
footer: 'Steep turns'
--- 

<style>
    table {
        width: 100%;
        text-align: left;
    }
</style>

<!--
_class: lead
_footer: ''
-->

# Steep turns

---

## Aim

*   To review the forces in a turn and extra considerations for turns of 45° or more

---

## Motivation

*   Traffic and terrain avoidance
    <!-- Ostensibly this is an emergency manouvre, and it can be important in avoiding traffic or terrain in some circumstances -->
*   Coordination exercise—particularly altitude holding
    <!-- But a lot of this is actually a skill exercise—in an emergency holding an altitude and rolling out on a particular heading aren't so important, but as a training exercise it helps to develop coordination skills -->

---

## Objectives

By the end of this brief you should be able to:

*   Describe the relationship between bank angle and load factor
*   State what limits max angle of bank in low powered and high powered aircraft
*   List the symptoms and describe the recovery from a spiral dive

---

## Lesson overview

Duration: approx 45 mins

*   Load factor
*   Maximum rate and minimum radius turns
*   Spiral dive
*   Side slipping
*   Application
*   Threat and error management
*   Review questions

---

## Revision

*   What happens to the lift force in a turn?
*   What is our configuration for a glide descent?

---

<!--
_class: lead
-->

## Forces during a turn

![h:389](./four-forces_1.png)

<!-- Banking the wings tilts the lift vector -->

---

<!--
_class: lead
-->

## Forces during a turn

![h:389](./four-forces_2.png)

<!-- This creates both a vertical and horizontal component of lift -->
<!-- The horizontal component of lift gives us the centripital force, acting towards the centre of the turn -->
<!-- Hoever, the vertical component of lift < weight -->

---

<!--
_class: lead
-->

## Forces during a turn

![h:389](./four-forces_3.png)

<!-- Therefore, in a turn we must increase the total lift force by increasing angle of attack (in other words, applying a back pressure on the yoke) -->

---

<!--
_class: 
-->

## Load factor

*   Load factor is defined as lift ÷ weight
*   Also known as g-force
    <!-- This is the feeling of being heavy in your seat -->
*   Load factor is a function of angle of bank
*   Load factor also affects stall speed

<!--
$$
Load\ factor = \frac{1}{\cos (Angle\ of\ bank)}
$$
-->

![bg right:57% h:389](./four-forces_3.png)
![bg h:460](./four-forces_steep.png)

---

## Load factor vs stall speed

$$
\begin{align}
New\ stall\ speed &= V_S \times \sqrt{Load\ factor} \\
V_S &= 48kts \\
\\
New\ stall\ speed &= 48 \times \sqrt{Load\ factor}
\end{align}
$$

---

## Load factor vs stall speed

$$
\begin{align}
New\ stall\ speed &= 48 \times \sqrt{Load\ factor}
\end{align}
$$

Bank angle | Load factor | √Load factor | New stall speed
-----------|-------------|--------------|-----------------
30°        | 1.15        | 1.07         | 51kts


---

## Load factor vs stall speed

$$
\begin{align}
New\ stall\ speed &= 48 \times \sqrt{Load\ factor}
\end{align}
$$

Bank angle | Load factor | √Load factor | New stall speed
-----------|-------------|--------------|-----------------
30°        | 1.15        | 1.07         | 51kts
45°        | 1.41        | 1.19         | 57kts


---

## Load factor vs stall speed

$$
\begin{align}
New\ stall\ speed &= 48 \times \sqrt{Load\ factor}
\end{align}
$$

Bank angle | Load factor | √Load factor | New stall speed
-----------|-------------|--------------|-----------------
30°        | 1.15        | 1.07         | 51kts
45°        | 1.41        | 1.19         | 57kts
60°        | 2           | 1.41         | 68kts


---

## Load factor vs stall speed

$$
\begin{align}
New\ stall\ speed &= 48 \times \sqrt{Load\ factor}
\end{align}
$$

Bank angle | Load factor | √Load factor | New stall speed
-----------|-------------|--------------|-----------------
30°        | 1.15        | 1.07         | 51kts
45°        | 1.41        | 1.19         | 57kts
60°        | 2           | 1.41         | 68kts
75°        | 3.86        | 1.96         | 94kts

<!-- 
Structural limits: 4.4Gs no flaps, 3.5Gs with flaps
What speed do we cruise at? 85kts. Do you think you could sustain 94kts in a 75 degree turn? Probably not, so we'll actually stall before we cause structural damage (assuming you don't yank on the controls at high speed). In a low powered aircraft the stall speed will be the limiting factor. In a high powered aircraft the structural limits become the limiting factor.

Max structural AoB = 76 degrees with no flaps @ Vs 100kts
                   = 73 degrees with full flaps @ Vs 89kts

Max AoB with stall speed @ 85 = 71 degrees
-->

---

## Maximum rate/minimum radius turns

*   **Rate of turn**
    *   How quickly the aircraft changes heading (in degrees per second)
*   **Radius of turn**
    *   The size of the circle the aircraft flies during a turn

---

## Maximum rate of turn

*   Occurs when the aircraft makes the largest heading change over a given period of time
*   Achieved at **high angle of bank** and **low airspeed**
*   We use 60° AoB and full throttle

<!-- 60° AoB gives us good performance while maintaining some margin above the stall -->

---

## Minimum radius of turn

*   Occurs when the aircraft flies the smallest possible circle
*   Achieved at a **high angle of bank** and **low airspeed**
*   We use 65–70kts, 10° flaps, and 45° AoB

<!-- What's the difference? Mostly the difference is one of emphasis—what do we want to achieve?

Let's think about why we might want to achieve minimum radius. Terrain. If you're flying down a canyon, and you realise the only way out is to turn back, then you probably don't have much room below you. You might not want to generate a high G loading or sink rate so close to the ground in fear that we will stall or otherwise lose control of our altitude. A stage or two of stage of flaps and a 45 degree turn at 65kts will be much easier to control, give you a much bigger margin over the stall, and get you 90% of the performance. -->

<!--
Formula for turn radius = V^2 / 11.26 * tan(AoB)
-->

---

## Spiral dive

*   A steep descending turn in which airspeed, rate of descent, and load factor are all **increasing rapidly**
    *   Rapid loss of altitude
    *   Risk of structural damage
*   Often due to **poorly managed steep turn** or **disorientation in IMC**
*   **Symptoms:** high and rapidly increasing airspeed, increasing load factor
*   **Recovery:** power idle, wings level, gently ease out of the dive, re-introduce power once at a normal cruising speed

<!--
Error: trying to pull out of the dive before wings level. This just increases the load factor, increasing the risk of structural damage or an accelerated stall.
-->

---

## Slipping

*   "Crossed controls"
*   Using rudder opposite to the aileron input
*   Increases drag, and therefore descent rate
    *   Useful to lose altitude quickly in a forced landing
    *   Check the POH—some aircraft are prohibited from slipping with flaps, or may have control buffet when slipping with flaps
*   Push the nose forward to keep airspeed up—a stall in this configuration will likely lead to a spin

<!--
*   Power to idle—any thrust defeats the purpose
*   Full rudder—the idea is to lose altitude so put the maximum cross-section into the wind as possible
*   Right rudder will give you better forward visibility
-->

---

## Application

---

## Threat and error management

Threat | Error | UAS | Countermeasure
-------|-------|-----|---------------
Disorientation | Eyes inside | Spiral dive, loss of SA | Eyes outside, horizon as reference
Spiral dive | Incorrect recovery technique | Structural damage | Power idle, wings level, ease out of dive

---

## Review questions

*   What happens to load factor as bank angle is increased in a level turn?
*   What is the load factor in a 60° level turn?
*   What happens to stall speed as load factor increases?
*   Why can high-powered aircraft sustain steeper turns than low-powered aircraft?
*   What are the main symptoms of a spiral dive?
*   What is the recovery procedure for a spiral dive?

---

## Objectives

You should now be able to:

*   Describe the relationship between bank angle, load factor, and stall speed
*   State what limits max angle of bank in low powered and high powered aircraft
*   List the symptoms and describe the recovery from a spiral dive
