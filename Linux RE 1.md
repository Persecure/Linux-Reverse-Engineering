Linux Reverse Engineering : 1
https://crackmes.one/crackme/5da31ebc33c5d46f00e2c661

![image](https://user-images.githubusercontent.com/93418272/180782516-77403919-6924-4480-ae02-25e7a953c60e.png)

Download and unzip the file (pw : crackmes.one)

Use the file command determine what kind of file it is.

![image](https://user-images.githubusercontent.com/93418272/180782650-db8ad4e9-52f5-456f-a0e6-5c9abd22ca83.png)

ELF is a common standard file format for executable files.
Execute the file.

![image](https://user-images.githubusercontent.com/93418272/180782683-48645118-d062-4fd9-a273-6239c996ace6.png)

Use the strings command to display printable strings in [file(s)] (stdin by default)

![image](https://user-images.githubusercontent.com/93418272/180782706-0d0ca6c0-b236-4bf9-91f6-2ac80f388441.png)

Start up Ghidra and analyze the file. Search for the main function in Symbol tree.

![image](https://user-images.githubusercontent.com/93418272/180782747-1c42e002-81f8-4661-b068-248712e00a74.png)

![image](https://user-images.githubusercontent.com/93418272/180782791-28bc19b2-a24e-4629-94ce-8cebe7ac7503.png)


local_14 = input

iVarl = input will be save to this variable

validate_key = function use to check the right input

Let’s analyze the validate_key function.

![image](https://user-images.githubusercontent.com/93418272/180782849-c25aff71-62d4-42a8-a5ca-a551de02486c.png)

param_1 = local_14 = input

0x4c7 (HEX) = 1223 (Decimal)

validate_key(param_1) 
 {
           return praram_1 % 1223 == 0;
}
Key will be 1223 , or any multiple of 1223 , or 0

Let’s test out the key.

![image](https://user-images.githubusercontent.com/93418272/180782888-7b163adb-1262-4b2d-bb8e-28f8709b9d70.png)


