# EXPERIMENT--01-ALP-FOR-8086
# Name : NIRUDHI.A  212224223003
# Date of experiment : 31/01/2026





## Aim: To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 8086  emulator 
## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
1.	Download and install emu8086 (www.emu8086.com) It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
2.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
3.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

4.	 Compile the program and check for the errors 
5.	Run (once there is no syntax error) 

6.	Click OK to see/view the output of your program on the Emulator screen. 


7.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
8.	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
MOV AX, 5782H
MOV BX, 23ABH
ADD AX, BX
MOV [3001H],AX
HLT

```

## Output  
![cbf87768-57d1-4140-8c2b-b1465713362d](https://github.com/user-attachments/assets/1b8eefe3-987b-4c9f-8301-8d7bdf44524d)

 
## Subtraction   of 8 bit numbers  ALP 
```
MOV AX, 5782H
MOV BX, 23ABH
SUB AX,BX
MOV [3003H],AX
HLT

```
 
## Output 
![cbb32ecd-16be-49bd-91af-7074bff3e13a](https://github.com/user-attachments/assets/2eb20c5b-0598-48ad-80c4-e02de158093f)


## Multiplication alp 
```
MOV AX, 5782H
MOV BX, 23ABH
MUL BX
MOV [3005H],AX
MOV [3007H],DX
HLT

```
 ## Output  
![8767d8b3-606e-429a-a2d3-a52b8850dc59](https://github.com/user-attachments/assets/0a2728a5-3214-4bdc-b9a0-9ffba36dde55)


## Division alp 
```MOV AX, 5782H
MOV BX, 23ABH
DIV BX
MOV [3009H],AX
MOV [300BH],DX
HLT

```

## Output  
![8c78532d-058a-455f-bccb-daa022ab06cd](https://github.com/user-attachments/assets/ab04c72d-686f-4ba1-a780-8cd2f14184a6)


## Result 

 Thus the execution for ALP on fundamental arithmetic and logical operations in done on 8086 microprocessor.
 








