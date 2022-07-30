# Reversing ELF
https://tryhackme.com/room/reverselfiles

Tools used : Ghidra & Radare2

## Crackme1

![image](https://user-images.githubusercontent.com/93418272/181863960-b19db1df-36b5-4b00-b245-2c0e522c888c.png)

## Crackme2

![image](https://user-images.githubusercontent.com/93418272/181863971-9e1d0aaf-71f0-4e1c-9bba-d567278a77fb.png)

![image](https://user-images.githubusercontent.com/93418272/181863978-45d1a115-c9c5-462f-ba70-960e75c3a468.png)

![image](https://user-images.githubusercontent.com/93418272/181863986-e6b1bc17-4dc9-4281-8356-f8e0336ecd97.png)

## Crackme3

![image](https://user-images.githubusercontent.com/93418272/181864030-a438e4ca-172e-469f-808b-ccbdd61f3460.png)

![image](https://user-images.githubusercontent.com/93418272/181864034-e5e7c735-8529-4813-ae18-8d0f42dc4bf3.png)

## Crackme4

![image](https://user-images.githubusercontent.com/93418272/181864056-e3d3ecea-3bbf-4530-8611-d244ecfb4fb8.png)

![image](https://user-images.githubusercontent.com/93418272/181864059-9cfb9605-e8ce-4c2a-b5ca-9f2fa0da471e.png)

![image](https://user-images.githubusercontent.com/93418272/181864063-d6720b71-9b5b-4fb2-a2f8-d14f93d97adc.png)

![image](https://user-images.githubusercontent.com/93418272/181864065-2535b2c2-fc27-46fb-8a3b-b4db8e7b627a.png)

![image](https://user-images.githubusercontent.com/93418272/181864073-2005c081-b082-4edd-9a18-43e1c3d602a0.png)

![image](https://user-images.githubusercontent.com/93418272/181864078-33c1d74e-5ca8-4553-bce5-271f242535d0.png)

![image](https://user-images.githubusercontent.com/93418272/181864084-a8fd3f46-53bc-400e-affa-38ce3b5077f4.png)

##Crackme5

![image](https://user-images.githubusercontent.com/93418272/181864091-c971b50b-9694-4a5c-aaa7-0dc20beba41a.png)

Start up radare to debug the code.

![image](https://user-images.githubusercontent.com/93418272/181864102-348f2663-2c51-420b-a756-2fb84c5b1755.png)

The program compares user input (scanf) and sym.strcmp_

![image](https://user-images.githubusercontent.com/93418272/181864112-9261b265-f65e-4d18-bd35-4586bbb2118d.png)

Set up a break point before the comparison at 0x00400829

![image](https://user-images.githubusercontent.com/93418272/181864117-bf1ca9b2-1fb9-4fec-81d3-2f62284472a4.png)

Show the hexdump on both variables one of the variables consists of the password. 

![image](https://user-images.githubusercontent.com/93418272/181864127-0a97ec43-23a4-44ec-87d3-cebeb3c30668.png)

![image](https://user-images.githubusercontent.com/93418272/181864135-047a004c-b39a-4274-b0cd-5bb5e55e7c20.png)

##Crackme6

![image](https://user-images.githubusercontent.com/93418272/181864139-c2218c04-650c-4f67-b95c-8896f334a661.png)

Use Ghidra to view the main function.

![image](https://user-images.githubusercontent.com/93418272/181864150-7d1dec4a-3946-4b33-9035-40c56c774d6d.png)

Inside the main function view the compare_pwd function.

![image](https://user-images.githubusercontent.com/93418272/181864156-b074636e-5909-48bb-8589-5e0edb59cbef.png)

View the my_secure_test function.

![image](https://user-images.githubusercontent.com/93418272/181864166-b459767d-fde5-4646-8e83-ff5271cd6d18.png)

![image](https://user-images.githubusercontent.com/93418272/181864169-7e034a69-6eb0-4f6c-ba90-0b99afc41501.png)

##Crackme7

![image](https://user-images.githubusercontent.com/93418272/181864179-119aad90-dca8-40b1-a623-1c8db4c70d8a.png)

Using the strings command we find a unknown string.

![image](https://user-images.githubusercontent.com/93418272/181864183-e2d94145-b9c9-46a6-8033-0d80320c5a14.png)

Use Ghidra to dissemble the program.

![image](https://user-images.githubusercontent.com/93418272/181864208-bb292e54-54f1-4ca4-9c3d-bf21415ac41d.png)

In the main function we can find an option to give the flag. Convert the hex number to decimal.

![image](https://user-images.githubusercontent.com/93418272/181864223-813688de-8c48-4cfd-b937-9c9adfb2c8ff.png)

##Crackme8

![image](https://user-images.githubusercontent.com/93418272/181864234-87803037-ed6c-415e-b504-3217ac401480.png)

Start up Ghidra to examine the main function of the code.

![image](https://user-images.githubusercontent.com/93418272/181864250-84df4835-7885-4860-bfeb-3e5a5bcdb6ea.png)

Input variable has to be -0x35010ff3 in order to get a flag.

![image](https://user-images.githubusercontent.com/93418272/181864254-0cb57d20-c01c-4236-81e1-b387166feb16.png)
