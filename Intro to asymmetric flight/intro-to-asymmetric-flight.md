---
marp: true
theme: gaia
class: invert
footer: 'Introduction to asymmetric flight'
--- 

<style>
    table {
        width: 100%;
        text-align: left;
    }
</style>

<!--
_class: lead invert
_footer: ''
-->

# Introduction to asymmetric flight

<!--
As you have seen so far, flying a multi-engine aeroplane under normal circumstances is pretty much the same as flying a single. We have two throttles, two mixture controls, etc., and we can utilise asymmetric thrust to help us taxi, but otherwise it's basically the same.

So here is where we get to the meat of the class rating: dealing with an engine failure in a multi-engine aeroplane.
-->

---

## Aim

*   To learn the impacts of an engine failure on a multi-engine aeroplane
*   To learn the actions required for continued safe flight after an engine failure on a multi-engine aeroplane

---

## Objectives

By the end of this brief you should be able to:

*   Describe the impact of an engine failure on performance
*   Describe the effects of an engine failure on aircraft control
*   List the factors contributing to multi-engine aeroplanes having a "critical engine"
*   Describe the cause of V<sub>MCA</sub> and state the recovery steps <!-- if you encounter V<sub>MCA</sub> roll -->
*   State the recovery steps to maintain best control and performance after an engine failure

---

## Revision

*   What is meant by moment? <!-- The tendency of a force to cause a body to rotate about a specific point or axis. Moment = Force * Arm -->
*   What causes directional stability? <!-- Vertical stabiliser -->
*   What troubleshooting checks do you perform after an engine failure in a single-engine aeroplane? <!-- FMCOST -->

---

## The problem

*   Modern multi-engine aircraft are remarkably capable under many circumstances, but must be flown by a current and proficient pilot to achieve the highest level of safety
*   There are several unique characteristics of multi-engine aircraft, particularly if an engine failure occurs
*   During an engine failure we must deal with two problems:
    *   Loss of **performance**
    *   Loss of **control**

---

<!--
_class: lead invert
-->

# Performance

---

## Performance

*   The most obvious problem is the loss of 50% of our power
*   Does 50% less power mean 50% less performance?
*   Unfortunately, **no**

---

## Performance

*   Remember, climb performance is dictated by _excess_ power
*   A 50% power reduction can reduce climb performance 80 to 90%, sometimes even more
*   Sometimes there is no excess thrust, and climb performance will be **negative**

![bg right:40% contain](./power-available-se.png)

---

## Performance

*   BE76 at sea level on an ISA day:
    *   1250fpm on two engines
    *   230fpm on one engine
*   That's an 82% reduction in climb performance!

![bg right:40% contain](./power-available-se.png)

---

## Performance

*   The climb data displayed in the POH assumes:
    *   Best single-engine rate of climb speed
    *   Feathered propeller (more on this later)
    *   Gear up
    *   Flaps up
*   If any of those factors aren't true, drag <!-- (and therefore thrust required) --> will increase, and performance will decrease **even further**
*   Altitude decreases power available, so the single-engine service ceiling will be significantly lower <!-- than the two-engine service ceiling (so compare the single-engine service ceiling to the terrain you are flying) -->

---

<!--
_class:
_backgroundColor: #fff
-->

## V<sub>YSE</sub>

*   Best rate of climb speed OEI
*   Marked with a blue line on the ASI (85kts in the BE76)
*   Above the single-engine absolute ceiling V<sub>YSE</sub> will yield the minimum rate of sink
*   We generally want to be flying **at or above** blue line speed, particularly when OEI

![bg right:40% contain](./ASI_ME.png)

---

<!--
_class:
_backgroundColor: #fff5df
-->

## Propeller pitch

*   Pitch refers to the angle between the propeller chord line and the plane of rotation of the propeller
*   Variable pitch propellers allow the pitch to be changed so that the pitch angle can be more course or fine depending on the phase of flight, as opposed to fixed pitch propellers where the pitch cannot be changed

![bg right:40% contain](./propeller-pitch.png)

---

<!--
_class:
_backgroundColor: #fff5df
-->

## Propeller pitch

*   Multi-engine aeroplanes' variable pitch propellers allow the pitch to be adjusted to "full feather"
*   Full feather moves the pitch so that the propeller is in-line with the relative airflow, significantly reducing drag
*   If the propeller is not feathered it is "windmilling" and will produce a lot of drag
<!--*   On most GA aircraft there is no "auto feather" system—the pilot will need to manually feather the propeller of the failed engine in the event of an engine failure-->

![bg right:40% contain](./propeller-pitch.png)

---

<!--
_class: lead invert
-->

# Control

---

## Control

*   The other problem is maintaining control
*   With one engine failed we have asymmetric thrust
*   What effect will this have? <!-- It creates a yawing moment in the direction of the failed engine -->
*   What is the secondary effect of yaw? <!-- Roll, also in the direction of the failed engine -->
*   If uncorrected, this will develop into a spiral dive

![bg right contain](./asymmetric-thrust.png)

---

## Control

*   In addition to the asymmetric thrust, the failed engine also produces additional drag—exacerbating the problem
*   This drag will be even more significant if the propeller is not feathered
*   How would you fix the yaw? <!-- Rudder in the direction of the live engine -->

![bg right contain](./asymmetric-drag.png)

---

## Propeller slipstream

*   Due to propeller slipstream the wing with the live engine produces more lift
*   In addition to rudder, we need ailerons to correct some roll

![bg right contain](./propeller-slipstream.png)

---

## Engine position

Which of these would produce the biggest yaw moment?

![bg right vertical contain](./asymmetric-drag.png)
![bg contain](./asymmetric-wide.png)

---

## Engine position

Which of these would produce the biggest yaw moment?

$$
\begin{align}
Moment &= Force \times Arm
\end{align}
$$

![bg right vertical contain](./asymmetric-drag.png)
![bg contain](./asymmetric-wide.png)

---

## Critical engine

*   Twins with two clockwise spinning propellers (conventional twins) have a **critical engine**
*   The critical engine is the one which, if it fails, will result in the largest yawing moment
*   Multiple factors combine to make the failure of one engine more critical than the other:
    *   Torque effect
    *   P-factor

---

## Torque effect

*   The tendency for the aircraft to rotate in the opposite direction of the spinning propeller
*   "Equal and opposite" reaction to the action of the propeller spinning
*   For clockwise spinning propellers the torque effect gives a left rolling tendency

![bg right contain](./torque-effect.png)

---

## Torque effect

*   When the left engine fails the torque effect **adds to** the roll tendency from the failed engine
*   When the right engine fails the torque effect **counteracts** the roll tendency from the failed engine
*   Therefore the left engine is the critical engine

![bg right:45% vertical contain](./torque-failed-left.png)
![bg contain](./torque-failed-right.png)

---

## P-factor

*   At higher angles of attack <!-- (slow flight, climbing, etc.) --> the down going blade produces more thrust, offsetting the thrust to one side
*   When the left engine fails the offset thrust is further from the fuselage, thus creating a larger yawing moment

![bg right vertical contain](./p-factor-left.png)
![bg contain](./p-factor-right.png)

---

## P-factor

*   When the right engine fails the offset thrust is closer to the fuselage, creating a smaller yawing moment
*   Again, the left engine is the critical engine

![bg right vertical contain](./p-factor-left.png)
![bg contain](./p-factor-right.png)

---

## Counter-rotating propellers
<!-- 
*   Some aircraft have counter-rotating propellers
*   The right propeller spins counter-clockwise
-->
*   Eliminates additional asymmetry due to torque effect and p-factor—**no critical engine**
*   More expensive due to higher part count and fewer shared parts

![bg right vertical contain](./torque-counter-rotating-props.png)
![bg contain](./p-factor-left-ccw.png)

---

<!--
_class: lead invert
_footer: ''
-->

# Sideslip vs zero-sideslip

---

## Sideslip

*   To maintain track with wings level rudder must be applied towards the live engine
*   This results in a sideslip, creating excess drag and reducing performance
*   Since the wings are level and there is no lateral acceleration the ball will be centred—**the ball is no longer an accurate indicator of slip**

![bg right:33% vertical contain](./sideslip.png)
![bg contain](./turn-and-slip_1.png)

---

## Zero-sideslip

*   A small bank (5°) towards the live engine will create a horizontal component of lift
*   This helps offset the turning tendency toward the dead engine, meaning we can use less rudder
*   The aircraft now is in a zero-sideslip condition, giving us the best single-engine performance

![bg right:33% vertical contain](./zero-sideslip-banked.png)
![bg contain](./turn-and-slip_2.png)

---

## Zero-sideslip

*   The ball will be about half a ball towards the live engine—**again, it is not an accurate indicator of slip**
*   This is called "raising the dead"

![bg right:33% vertical contain](./zero-sideslip-banked.png)
![bg contain](./turn-and-slip_2.png)

---

<!--
_class: lead invert
-->

# V<sub>MCA</sub>

---

## V<sub>MCA</sub>

*   When the left engine fails, which direction will the aircraft yaw?
*   How would you correct this yaw?
*   What happens to rudder authority as IAS reduces?
*   At a certain speed, there is not enough rudder authority to correct the yaw and directional control cannot be maintained <!-- yaw, roll, spiral dive -->
*   This speed is called **V<sub>MCA</sub>**

![bg right:33% contain](./asymmetric-drag.png)

---

<!--
_class:
_backgroundColor: #fff
-->

## V<sub>MCA</sub>

*   Minimum speed (in the air) where directional control can be maintained with OEI
*   Indicated by the red line on the ASI (65kts in the BE76)

![bg right contain](./ASI_ME.png)

---

## V<sub>MCA</sub>

*   Measured under the following (pessimistic) conditions:
    *   Critical engine failed + windmilling
    *   Operating engine at takeoff power
    *   Most rearward CG <!-- Why is V<sub>MCA</sub> measured with most rearward CG? -->
    *   Gear up <!-- Why is V<sub>MCA</sub> measured with gear up? -->
    *   Flaps set for takeoff
    *   Maximum 5° AoB towards the live engine <!-- Zero-sideslip condition is the only positive thing going for V<sub>MCA</sub> -->

---

## V<sub>MCA</sub>

*   Loss of directional control occurs when OEI at high power and low airspeed
*   Therefore, how would you recover?
    *   Power idle
    *   Lower the nose
    *   As speed builds above V<sub>YSE</sub>, gently pull into a climbing attitude and increase power

---

# In summary

*   Attention to both **performance** and **control** is crucial for safe one-engine inoperative (OEI) flight
*   The performance and redundancy of a multi-engine plane is a safety advantage only to a trained and proficient pilot

---

<!--
_class: lead invert
-->

# Application

---

## Recognition

*   Best indicator is yaw in the direction of the failed engine
    *   Apply rudder to counteract the yaw
    *   "Dead leg, dead engine"
    *   Verify with throttle

![bg right contain](./asymmetric-thrust.png)

---

## Recognition

*   Engine indications are not normally helpful
    *   Manifold pressure, RPM, oil T&Ps, CHT, and fuel flow will read normally or drop slowly
    *   EGT will drop

![bg right contain](./asymmetric-thrust.png)

---

## "The drill"

<!-- *   Maintain control with rudder & aileron, pitch for blue line or to hold altitude -->
*   Mix up
*   Pitch up
*   Power up
*   Gear up
*   Flap up
*   Identify—"dead leg, dead engine"
*   Verify & flag
*   Fix or feather

---

## Fix or feather?

*   **Height critical** 
    *   If in the circuit area or on an instrument approach:
        *   Feather the failed engine
        *   Land

---

## Fix or feather?

*   **Not height critical**
    *   Try and troubleshoot using **FMCOST**
    *   If the engine cannot be restarted:
        *   Identify
        *   Verify & flag
        *   Feather
        *   Complete the securing engine checklist (FMMM)
        *   Reduce power to look after the live engine when safe to do so
        *   Land

<!-- Once engine secure, land as soon as possible -->

---

## Simulating engine failure

*   Instructor will bring power to idle or fail the engine with mixture and say "simulated engine failure"
*   We will not be feathering propellers in training—bring the propeller on the failed engine back to your instructors fingers and they will simulate the feathered propeller by setting "zero thrust"
*   If your instructor doesn't say "simulated engine failure" then the failure is real, but you will still perform exactly the same procedures unless your instructor intervenes by saying "my controls"

---

## Threat and error management

*   Continue flying the aeroplane—maintain at or above blue line speed
*   Memorise "the drill"
*   Don't rush—slow is smooth, smooth is fast
    *   An engine failure isn't the only cause of sudden yaw
    *   Too many pilots have feathered or shut down a perfectly good engine because they've rushed or made assumptions
    *   **VERIFY WITH THROTTLE**

---

## Threat and error management

*   Remember, we will not be feathering the propeller
*   Monitor engine temperatures and pressures—reduce power to look after the live engine when safe to do so
*   Maintain your lookout, despite the high workload

---

## Review questions

*   What is the immediate effect on control when an engine fails?
*   What percentage of climb performance can you expect when operating on a single engine?
*   List two reasons why one of the engines would be the "critical engine"
*   Why does V<sub>MCA</sub> occur?
*   How would you recover if you began to enter a V<sub>MCA</sub> roll?
*   What steps will you take if an engine failure occurs?

---

## Objectives

You should now be able to:

*   Describe the impact of an engine failure on performance
*   Describe the effects of an engine failure on aircraft control
*   List the factors contributing to multi-engine aeroplanes having a "critical engine"
*   Describe the cause of V<sub>MCA</sub> and state the recovery steps <!-- if you encounter V<sub>MCA</sub> roll -->
*   State the recovery steps to maintain best control and performance after an engine failure

