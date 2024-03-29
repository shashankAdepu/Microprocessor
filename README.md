# EE312-Microprocessor-Project

This is an 8-bit microprocessor that is designed to implement a set of 16 instructions as per the project specifications.</br>

## Project specifications
![image](https://github.com/PuttaSravankumarReddy/EE312-Microprocessor-Project/assets/109052077/6fb0466f-80e3-4c68-a232-1f594bf53ab9)



The whole microprocessor design is divided into 5 parts:
<ul>
  <li>Instruction Memory</li>
  <li>Control Unit(CU)</li>
  <li>Data Memory</li>
  <li>Arithmetic Logic Unit(ALU)</li>
  <li>Multiplexers(MUX)</li>
</ul>

## Working of microprocessor:
<ul>
  <li>User writes the instructions to the instruction memory which will be fetched by the Control unit later on.</li>
  <li>User provides input to Data memory which is required for performing the operation after the control unit decodes the instruction.</li>
  <li>Control unit fetches instructions one-by-one and decodes them to perform operations.</li>
  <li>Now, the Control unit performs operations on the data present in the data memory with the help of ALU.</li>
  <li>Once the operation is finished in the ALU, then the required result will be obtained as the output.</li>
</ul>

## Input handling:
<ul>
<li>As mentioned in the question, a sign extension is used for handling the inputs.</li>
<li>Because the provided input is of either 2 bits or 4 bits but we need an 8-bit input based on the register size. So, we used a 6-bit sign extension in the case of 2-bit input and a 4-bit sign extension in the case of 4-bit input.</li>
<li>Eg: 01 input is taken as 00000001 and 1001 input is taken as 11111001.</li>
</ul>
</br>


