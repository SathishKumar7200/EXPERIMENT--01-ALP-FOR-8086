# EXPERIMENT--01-ALP-FOR-8086
Name : Sathish kumar. M

Roll no :212224230256

Date of experiment : 19.08.2025





## Aim:
To Write and execute ALP on fundamental arithmetic and logical operations
## Components required: 
8086  emulator 
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
org 0100h

mov ax,4122h

mov bx,3456h

add ax,bx

ret

## Output 

<img width="1890" height="1058" alt="Screenshot 2025-08-19 091925" src="https://github.com/user-attachments/assets/db55d101-3669-421f-80c7-41de7deac6b8" />

 
## Subtraction   of 8 bit numbers  ALP 
org 0100H

mov ax,4122h

mov bx,3456h 

sub ax,bx

ret

 
## Output  

<img width="1883" height="1073" alt="Screenshot 2025-08-19 092732" src="https://github.com/user-attachments/assets/db5b133e-179d-4930-8b62-70c482cb5cdd" />

## Multiplication alp
org 0100H

mov ax,4122h

mov bx,3456h 

mul bx

ret
 ## Output  

 <img width="1885" height="1070" alt="Screenshot 2025-08-19 092926" src="https://github.com/user-attachments/assets/02a2b843-f56d-463a-b818-eedef533d984" />



## Division alp 

org 0100H

mov ax,4122h

mov bx,3456h 

div bx

ret

## Output

<img width="1893" height="1054" alt="Screenshot 2025-08-19 093108" src="https://github.com/user-attachments/assets/0eb33ab1-2b11-47bc-8e76-8335acedca0c" />

## LOGICAL OPERATION :

org 0100H

mov ax,4122h

mov bx,3456h 

and ax,bx

mov [2000h],ax


mov ax,4122h

mov bx,3456h

or ax,bx

mov [2002h],ax


mov ax,4122h

mov bx,3456h

xor ax,bx

mov [2004h],ax


mov ax,4122h

mov bx,3456h

not ax

mov [2006h],ax


ret

## output:

<img width="1885" height="1077" alt="Screenshot 2025-08-19 093820" src="https://github.com/user-attachments/assets/9ad6fae1-89c8-4d2c-9806-4c30fb5d84f9" />




## Result :
 Thus the program for arithmetric and logical operation excuted successfully .
 








