# Electronic-Circuit-Design-Project
we make a variable DC power supply and the main working principle of this project is full wave rectification which is done by bridge configuration. Where we are using 4 diodes and those rectifies the output of the step-down transformer, that step down the 220 AC volts to 24 AC volts. In this circuit we have use capacitor C1 are used to get constant input to the regulator. Moreover, it also helps to reduce the sharp peaks in the output. The 1000 μ F capacitor are used to reduce the noise and ripples produce by the regulators. So that the regulated output has less ripples. We are also using a voltage regulator that gives constant voltage, which gives 6 volts  and it is IC LM317 Voltage regulator. Now the main task is to get variable output and  for this we use Variable resistor 10kΩ to increase the output of the regulator and in  which resistance is variable. So, when we increase or decrease the value of that resistor  the output voltage of the regulator will also change accordingly and we get a range of 1.5V to 22V variable voltage.
# Components:
1- Transformer 240v 50 HZ (24v-2A) 2- 4 diode 1N4007
4- 1000µF/35v capacitor 5- Variable resistor 10kΩ 6- 220 Ω resistor
7- LM317AH IC 
8- Digital Display
# Working:
Transformer + Rectifier + Smoothing: - The smooth DC output has a small ripple.

Transformer + Rectifier + Smoothing + Regulator: - The regulated DC output isvery smooth with no ripple. It is 
suitable for all electronic circuits.

Rectifier:
There are several ways of connecting diodes to make a rectifier 
to convert AC to DC. Thebridge rectifier is the most important 
and it produces full-wave varying DC. A full-wave rectifier can

also be made from just two diodes if a center-tap transformer is 
used, but this method is rarely used .now that diodes are 
cheaper. A single diode can be used as a rectifier but it only 
uses the positive (+) parts of the AC wave to produce half-wave 
varying DC.

Bridge Rectifier:
A bridge rectifier can be made using four individual diodes, 
but it is also available in special packages containing the 
four diodes required. It is called a full-wave rectifierbecause 
it uses all the AC wave (both positive and negative sections).

The Positive Half-cycle. During the positive half cycle of the 
supply,
diodes D1 and D2 conduct in series while diodes D3 and D4 are 
reverse biased and thecurrent flows through the load as shown 
below.

Output of Transformer
 
The Negative Half-cycle During the negative half cycle of 
the supply, diodes D3 andD4 conduct in series, but diodes 
D1 and D2 switch “OFF” as they are now reverse biased. 
The current flowing through the load is the same direction as 
before.

Smoothing (Filter): -
Smoothing is performed by a large value electrolytic capacitor 
connected across the DC supply to act as a reservoir, supplying 
current to the output when the varying DC voltagefrom the 
rectifier is falling. The diagram shows the unsmoothed varying 
DC (dotted line)and the smoothed DC (solid line). The 
capacitor charges quickly near the peak of the varying DC, and 
then discharges as it supplies current to the output.
 
Smoothing is not perfect due to the capacitor voltage falling a little as it discharges, giving a small ripple voltage. For many circuits a ripple 
which is 10% of the supply voltage is satisfactory and the equation 
below gives the required value for the smoothingcapacitor. A larger 
capacitor will give less ripple. The capacitor value must be doubled 
when smoothing half-wave DC
So, in this we concluded that the pulsating DC voltage is applied to the smoothing capacitor. This smoothing capacitor reduces the pulsations in the rectifier DC outputvoltage.
The smooth DC output has a small ripple. It is suitable for most electronics 
circuits.
 
Voltage Regulation (using IC LM317)

Output from the full wave bridge rectifier is fed to a LM317
regulator IC LM317 provides varied voltage from 1.2V to 22V. 
Reference voltage of 1.25 V is maintained at220 ohm Resistor.

The LM317 Voltage Regulator is a 3-terminal adjustable
voltage regulator which can supply an output voltage
adjustable from 1.2V to 22V. It can supply more than 1.5A of load current to a load.
LM317 Pinout
The LM317 Voltage Regulator has 3 pins. Below is the pinout:

Looking from the front of the voltage regulator, the first pin (on the left) is the AdjustablePin, the middle is Vout, and the last pin(on the right) is VIN.

VIN - VIN is the pin which receives the incoming voltage which 
is to be regulated down to aspecified voltage. For example, the
 
input voltage pin can be fed 12V, which the regulator will regulate down to 10V. The input pin receives the incoming, unregulated voltage.
Adjustable - The Adjustable pin (Adj) is the pin which allows for adjustable voltage output. To adjust output, we swap out 
resistor R2 value for a different resistance. Thiscreates 
adjustable voltages.
VOUT - VOUT is the pin which outputs the regulated voltage. For example, the LM317 mayreceive 12V as the input and output a constant 10V as output.

we connect two resistor to the voltage regulator. These resistor determine thevoltage that the voltage regulator adjusts.
