# CODTECH-Task2

Name: Ommi Sravani

Company:CODTECH IT SOLUTIONS.

ID:CT6WDS661

Domain:VLSI

Duration:June to August 2024.

Mentor:Muzammil Ahmed.

**Overview of the project**

Project:FINITE STATE MACHINE (FSM) DESIGN.

TOOL USED:EDA Playground.

Objective:The objective of this task is to Design FSMs using Verilog or VHDL in the VLSI software environment. Write testbenches to test different states and transitions of the FSM. Simulate the FSM behavior and verify its correctness.

/* fsm */

inputs: clock - An input signal that drives the FSM

Output: light - A 3-bit output signal representing the state of the lamps.

A Finite State Machine (FSM) is a mathematical model of computation used to design sequential logic circuits. FSMs are characterized by a finite number of states, transitions between these states, and actions. 

There are two types of FSMs:

1.Moore state machine: A Finite state machine is said to be Moore state machine, if outputs depend only on present states.

2.Mealy state machine: A Finite state machine is said to be Melay state machine, if outputs depend on both present inputs and present states.

Verilog module defines a finite state machine(FSM) that is cyclic lamp where the state changes from RED --> GREEN --> YELLOW --> RED

In state s0, the GREEN lamp is ON, and the FSM transitions to s1.

In state s1, the YELLOW lamp is ON, and the FSM transitions to s2.

In state s2, the RED lamp is ON, and the FSM transitions back to s0.


![fsm_waveform](https://github.com/user-attachments/assets/477a0952-3dac-47ba-8b59-29789acbf6b6)



