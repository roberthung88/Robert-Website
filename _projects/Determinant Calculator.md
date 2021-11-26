---
name: Determinant Calculator
tools: [Verilog, Nexys-4 FPGA]
image: /assets/images/515VX+Q7FsL._AC_SX450_.jpg
description: A means of employing hardware to calculate matrix determinants
external_url: 
---
{% include elements/button.html link="https://github.com/roberthung88/EE354_FinalProject" text="GitHub Link" style="outline-dark" size="lg" %}

- Employing an iterative process, designed a **5-state state machine** for calculating matrix determinants using hardware. Code is written in Verilog and loaded onto a **Nexys-4 FPGA board** where users can input desired matrix. Result is deployed on onboard SSDs.  
- Paid special attention to **setup and hold time violations** and tuned the clock accordingly. 
- Tricky to code, as Verilog state machines cannot easily utilize recursive programming, which would otherwise be easy if coded in C++/Python. The tradeoff is speed since hardware is faster. 





