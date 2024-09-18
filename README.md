# Rubber-Ducky-2024
A manual Rubber Ducky with a Arduino UNO

We can use a Arduino UNO to convert it in a Rubber Ducky reprograming his micro-controller ATMega16U2.

For the transformation, I use this proyect: https://github.com/Lacerda53/duckduino. As well I suggest you follow the transformation video https://www.youtube.com/watch?v=W6uGHYBAhHQ&ab_channel=s4vitar (spanish)


## Necessary tools
USB
![image](https://github.com/user-attachments/assets/cbcbc2d2-9cce-4cc7-9f73-98a0b72e250b)

![image](https://github.com/user-attachments/assets/8e565b6a-44b8-47c3-a476-8203bc86eac5)

![image](https://github.com/user-attachments/assets/3672de29-0b20-4413-a282-0ab448f036a1)

![image](https://github.com/user-attachments/assets/2a66df40-738b-4400-bb73-2deada6b5c82)




## Transformaiton
Clone the repositori
![Captura desde 2024-03-24 20-16-14](https://github.com/user-attachments/assets/89ac23ed-2505-45cd-b729-c3b9ef08afde)

Provide execution permision
![Captura desde 2024-03-25 23-18-35](https://github.com/user-attachments/assets/bf88a06f-2c2c-4f05-86f2-4de70875ee28)

Execute the script
![Captura desde 2024-03-25 23-20-04](https://github.com/user-attachments/assets/337c6b71-1731-4c64-8042-7430f910858f)

Plug Arduino with the two pins
![Captura desde 2024-03-25 23-24-51](https://github.com/user-attachments/assets/22f0a2a7-7279-4448-a271-d94bccd21827)

Then disconnect it 
![Captura desde 2024-04-01 19-04-30](https://github.com/user-attachments/assets/2ba20e48-c785-48b8-a558-9ce84dc7a0b1)

Wait 
![Captura desde 2024-04-01 19-29-59](https://github.com/user-attachments/assets/af8fab7a-924f-4767-8e1f-bf0801cbd87f)

Open Arduino IDE and upload the code 
![Captura desde 2024-04-01 19-32-38](https://github.com/user-attachments/assets/e9d610b5-5e7f-4008-8998-fa0095adc0ff)

Once you uploaded the code, connect the two pins again
![Captura desde 2024-04-06 17-59-11](https://github.com/user-attachments/assets/0d273ca3-024c-435a-9bf7-f67f1579a100)

Then remove the ATMega16U2 connected pin
![Captura desde 2024-04-06 17-59-32](https://github.com/user-attachments/assets/53d35e11-c62d-4d81-a5c9-78da7e49f9f9)

Enjoy
![Captura desde 2024-04-06 17-59-48](https://github.com/user-attachments/assets/0822bb8d-681e-417f-ab0d-f927fa7eb585)




Using Arduino UNO to tranform it in a Rubber Ducky we have limitations, we can't use some libraries and we must use Arduino language (C) so the payloads are programmed using the librarie <HIDKeyboard.h> which make it easiest. 
