### Name :A.NIVETHA

### Roll no :212222230101

# EXPERIMENT--01-ALP-FOR-8086

## Aim:
To Write and execute ALP on fundamental arithmetic and logical operations

## Components required: 

8086  emulator 

## Theory 
Running The Emulator (emu8086) Intro 8086 Microprocessor Emulator, also known as EMU8086, is an emulator of the program 8086 microprocessor. It is developed with a built-in 8086 assembler. This application is able to run programs on both PC desktops and laptops. This tool is primarily designed to copy or emulate hardware. These include the memory of a program, CPU, RAM, input and output devices, and even the display screen. There are instructions to follow when using this emulator. It can be executed into one of the two ways: backward or forward. There are also examples of assembly source code included. With this, it allows the programming of assembly language, reverse engineering, hardware architecture, and creating miniature operating system (OS). The user interface of 8086 Microprocessor Emulator is simple and easy to manage. There are five major buttons with icons and titles included. These are “Load”, “Reload”, “Step Back”, “Single Step”, and “Run”. Above those buttons is the menu that includes “File”, “View”, “Virtual Devices”, “Virtual Drive”, and “Help”. Below the buttons is a series of choices that are usually in numbers and codes. At the leftmost part is an area called “Registers” with an indication of either “H” or “L”. The other side is divided into two, which enables users to manually reset, debug, flag, etc. What is 8086 emulator emu8086 is an emulator of Intel 8086 (AMD compatible) microprocessor with integrated 8086 assembler and tutorials for beginners. Emulator runs programs like the real microprocessor in step-by-step mode. it shows registers, memory, stack, variables and flags.


 ## Running the Emulator :
 
1.	Download and install emu8086 (www.emu8086.com)
  
2.	It is usually installed in C:\EMU8086 subfolder in the “Windows” directory
	
3.	  Run  emu8086 icon (on the desktop or in the c:\EMU8086 folder of window) It has green color 
 
 
4.		write the code for the appropriate program for ADDITION,SUBTRACTION, MULTIPLICATION,  DIVISION operations 

6.	 Compile the program and check for the errors 
7.	Run (once there is no syntax error) 

8.	Click OK to see/view the output of your program on the Emulator screen. 


9.	After running the program, another menu screen will be displayed, where you have the option to “View” symbol table,
	 


![image](https://user-images.githubusercontent.com/36288975/189273263-d65baae9-4b8f-4723-afb3-c0ffa4052b04.png)











9.	Click on emulate to start emulation 








![image](https://user-images.githubusercontent.com/36288975/189273273-9bb36ec1-e2e8-4892-8d35-37707332bfdc.png)








10.	If no errors are found click on run the program and check the status of various flags in the flags tab as shown below 






![image](https://user-images.githubusercontent.com/36288975/189273277-113a2a33-4a40-4ff8-95a5-ecd3a1f504fe.png)







## Programs for arithmetic  operations

## Addition  of 8 bit ALP 
```
org 100h

mov ax,0a123h;
mov bx,0b456h;
add ax,bx;
mov [1234h],ax;

ret
```
## Output  
 ![307847544-c232ca60-be64-4ef8-992e-99fc5588fd14](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/dd54dc21-3dc4-456f-8300-8830328e50c3)

## Subtraction   of 8 bit numbers  ALP 
```
 org 100h

mov ax,0d101h;
mov bx,0c789h;
sub ax,bx;
mov [5678h],ax;

ret
```
## Output  
![307847678-5da92a84-e146-4033-96a6-6421db35165b](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/8f89893c-4708-4ee8-a04b-a3cc45c61612)

## Multiplication alp 
```
org 100h

mov ax,0e112h;
mov bx,0f131h;
mul bx;
mov [9101h],ax;

ret
```
 ## Output  
![307847966-3e24f8c8-de1b-4080-9e53-ce964941320d](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/6838ed32-c1a0-4454-9e96-32a993514217)

## Division alp 
```
org 100h

mov ax,0b161h;
mov bx,0a415h;
div bx;
mov [1121h],ax;

ret
```
## Output  
![307848090-a9a86522-9feb-4e0d-8082-0a21aa27f9a7](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/5143308c-fc0f-46cd-b5a3-dcc0d7e4095c)

### Programs for logical operations 

### AND
```
org 100h
mov bx,1000h;
and bx,1111h;
mov [0040h+02],bx;
ret
```
### Output

![322874623-e82a2b12-23e6-4b22-b667-c2cc559d6be0](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/e98324c7-30d2-4738-951a-bbd98544d1fa)

### OR
```
org 100h
mov ax,[0040h+06];
mov bx,1000h;
or ax,bx;
mov [0040h+02],ax;
ret
```
### Output

![322874925-f9a9afae-50d6-4c69-8a8c-d221667db9ff](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/65a56dcd-a377-4f43-86f5-5330f61064cc)

### NOT
```
org 100h
mov bx,0040h;
mov ax,[bx]; 
not al;
mov [0040h+04],ax;
ret
```
### Output

![322875293-45591835-4640-4b2c-ac50-e370723c3388](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/2c3e21ec-4777-4ba7-aa7e-d67658a62f3d)

### XOR
```
org 100h
mov bx,0040h;
mov ax,[bx]; 
xor ax,bx;
mov [0040h+04],ax;
ret
```
### Output

![322875549-e2595b3a-14e1-42dd-a890-1a44adefe1e8](https://github.com/nivetharajaa/EXPERIMENT--01-ALP-FOR-8086/assets/120543388/cf588bbd-1c85-4d03-8224-2dd352b43634)


## Result :
 The execution of ALP on fundamental arithmetic and logical operations is successfully completed.








