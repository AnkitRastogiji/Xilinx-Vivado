How to create project in Xilinx Vivado step by step?
steps:
1- Create a project name and choose location then go to next
2- Choose RTl project and choose do not specify sources at this time then go to next
3- Choose family : Artix7 , package : cpg236 and  speed -1 and click on : xc7a35tcpg236-1 ,flip flop : 41600 section then go to next 
4- Finish
5- your create project window will open go to add source and click (add or create design source) go to next
6 - Creat file name , file type choose Verilog or VHDL and file location select ok and finish and desine module ok and yes
7 - Double click on Design Sources and showing your create project double click
8 - Write your project and Ctrl+S (save) update automatically project
9 - RTL ANALYSIS section click (open Elaboration Design)
10 - Open your Elaboration design 
11 - Create Test Beach :- click to add source and choose (add or create simulation sources) goto next 
12 - Creat file name , file type choose Verilog or VHDL and file location select ok and finish and desine module ok and yes
13 - Double click simulation and again double click sim(2) showing your test bench again double click and showing test bench on your project tab
14 - Write your test bench code and Ctrl+S and click RUN SIMULATE again click Run Behavioral Simulation open your simulation waveform check it now and Save it 
15 - And click on Run Synthesis open Launch Runs click ok
16 - Wait Synthesis completed open choose (open Synthesized design) ok and wait and click schmatic tab generate synthesis design 
17 - check your Report_Power wait check report
18 - check IMPLEMENTATION click ok and wait for a moment and okay (open implementation design) and yes 
19 - Automatically  open your Synthesized device design
20 - For save click on File go to constraints save as.. ok automatically save in your project location
