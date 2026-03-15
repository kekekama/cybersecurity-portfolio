There are a total of 5 sublevels.

# LEVEL 1 - NAND

Now the NAND gate does the opposite of the AND gate.

In this level there are 2 relays (switches), one default off and the other default on.
There are 3 input: a,b and V(power, always 1)

To solve this exercise I first connected the power V to the input relay(default on), because without a (0) and b (0) I can have the output equal to 1.

After that it is time to set the control part, I connected another relay(default off) with the control part and this relay is correlated with a (input) and b (control).
Now it works.

![level 1](images/01_01.png)

# LEVEL 2 - INVERT

This level talks about how to create an inverter component.
It is simpler, I just have to connected the both inputs of the NAND gate to a single input.
So, with input 0 a NAND 0-0 the output was 1, and with input 1 the output is 0.

![level 2](images/01_02.png)

# LEVEL 3 - AND

Here I have to create and AND, I have an inverter and a NAND.
So it is easy, I know NAND is AND NOT, and with an inverter I get AND NOT NOT, which is AND.

![level 3](images/01_03.png)

