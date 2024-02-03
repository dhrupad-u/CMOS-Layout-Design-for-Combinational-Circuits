# CMOS-Layout-Design-for-Combinational-Circuits

CMOS Layout Design for Combinational Circuits, using the Micorwind layout design software The layouts are 
optimized to enhance the performance and efficiency of the circuits.

1. 4-bit adder subtractor circuit
   
   A 4-bit Full Adder is designed to generate a 4-bit Sum and is designed by combining four 2-bit Full Adders and as a result shows the
   Four bits output along with the Carry Bit.

   Initial Design:

   1-bit full adder Logic Cicuit:

   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/3489d8b0-6b9a-4311-aef5-bf01b288797b)

   CMOS circuit of a 1-bit Full adder:

   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/65018a59-4b9c-4b0e-b3fb-679c285f0e65)

   CMOS circuit of an Exclusive-OR gate:

   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/c78fa7a6-d768-4801-a0ff-79212589a338)

   Layout Design of a 1-bit Full adder:

   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/3cebb8a3-221e-48b4-97f3-eef02062f483)

   Combining 4 such full adders and XOR-ing them, we can get a 4-bit Full Adder.

   Layout Design of a 4-bit full adder:

   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/d7c3076c-740d-4987-8bd6-482a8b1eb168)

   Simulation Results:

   ![Adder-Subtractor Simulation](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/85a34f48-6f9a-469b-804b-639b205e4986)

3. 4-bit BCD Up-Down Counter:
   
   A BCD counter is one of the 4-bit binary counters, which counts from 0 to a pre-determined count (this case 1001) with an
   applied clock signal. When the count reaches the predetermined count value, it resets all the flip-flops
   and starts to count again from 0. In this case, we use a D-Flip Flop for executing the said logic.

   4-bit BCD Up Down Logic Cicuit:

   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/76e916e9-61e8-4298-84f4-6837841c6682)

   Layout Design of the Counter:

   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/72234a0e-81cc-4d4b-ab94-80d02d2488af)

   Simulation Results:
   ![image](https://github.com/dhrupad-u/Layout-Design-for-Combinational-Circuits/assets/42469685/00b5cbc9-0cea-4d68-94d7-d3f50c4a1295)

This project contain the .MSK files, for both these combinational circuits, which can be opened through the Micorwind Layout Design software.
