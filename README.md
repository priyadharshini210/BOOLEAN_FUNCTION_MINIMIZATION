# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: P.PRIYADHARSHINI RegisterNumber: 212223240128
*/
```
library IEEE;
use IEEE.STD_LOGIC_1164.ALL;

entity booleanexp is 
    Port ( INO1 : in STD_LOGIC;    --- OR gate input
	        INO2 : in STD_LOGIC;    --- OR gate input
			  OO  : out STD_LOGIC);   --- OR gate output
end booleanexp;

architecture Behavioral of booleanexp is 
begin
OO <= INO1 or INO2;   --- 2 input OR gate
end Behavioral;
```
![image](https://github.com/priyadharshini210/BOOLEAN_FUNCTION_MINIMIZATION/assets/148514638/a92d279a-b25a-48d2-82b4-6f2b95599e0d)

**RTL realization**
![314511805-70420e12-71c5-4c16-9e5b-68107063fdaa (1)](https://github.com/priyadharshini210/BOOLEAN_FUNCTION_MINIMIZATION/assets/148514638/a04dfaa6-e78c-4dbc-a394-b11cec55df29)

**Output:**
![image](https://github.com/priyadharshini210/BOOLEAN_FUNCTION_MINIMIZATION/assets/148514638/1810f925-3f4d-442f-a736-fb57b9cdee62)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

