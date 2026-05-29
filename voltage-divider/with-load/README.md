# Voltage Divider Circuit with no load

![circuit + waveform](./screenshot.png)

A voltage divider circuit is the most basic circuit using resistors. It is used to step down a higher input voltage to a lower output voltage. 
Input voltage is applied across R1 and R2 in series, but output voltage is taken across R2 only.

The equation for output voltage when no load is attached is given by,

$$Vout = Vin.R2/R1+R2$$

However, in this circuit, a load is attached. When a load RL is attached, it causes the effective resistance of the lower arm to change, and as a result the current drawn from the voltage source changes. Hence we dont get the output voltage we expected. So while calculating the resistances, we must keep these things in mind.

In this circuit, the goal is to step down input voltage of 12 V to output voltage of 3 V. For this, the ratio of resistors must be $Rbottom/R1 = 1/3$. In this example we take $R1 = 3k$ and $Rbottom = 1k$. For Rbottom to be 1k, R2 || RL should be equal to 1k. For simplicity, I have chosen $R2 = 2k$ and $RL = 2k$. Therefore, we get output voltage of 3 V across load resistor RL. 
