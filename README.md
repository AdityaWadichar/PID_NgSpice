# PID Controller circuit

## Aim
To Design and simulate PID Controller circuit using Operational Amplifier in NgSpice software

## Working
Op-amp  as  inverting  amplifier  is  used to calculate  the  proportional  term,  op-amp  as  a  differentiator is  used  to  calculate  the  derivative  term.  An  op-amp  as  an integrator is used to calculate the integral term. The value of K<sub>P</sub>, K<sub>D</sub> & K<sub>I</sub> depends on the respective op-amp gain. These terms are added using an op-amp as summer, followed by an inverting op-amp to compensate for the inversion caused due to the circuit.

## Circuit Diagram
<img src = "Images/PID_circuit.png">
<img src = "Images/pid_full.png">

## Output
<img src = "Images/pid_op.png">
