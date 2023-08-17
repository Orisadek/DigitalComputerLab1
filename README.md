# DigitalComputerLab1
This project implements a system which include MSP430 microcontroller and based on Simple FSM.
with each button press we enter a state:

PB0 (state1) 

        show on leds the values of array with latency of 0.5 sec between each number in the array.

PB1 (state2) 

        light one led and shift it from right to left with latency of 0.5 sec between each shift.

PB2 (state3) 

        create PWM signal in leg P2.7 with frequncey of 4kHz and Duty Cycle of 75%
        this is the only state which allow shift in state while still in the current one.

Real Time assignemt : add state4 as follows
				
PB3 (state4)

        print on leds the ascii value of each char in string with latency of 250 ms

state0 

        state0 is sleep mode (LPM0) and every state except state3 returning to sleep after the state ends.
FSM:

<img width="361" alt="image" src="https://github.com/Orisadek/DigitalComputerLab1/assets/43981934/d3ceb60b-15a5-4d10-8bdf-be536c73fcaf">


