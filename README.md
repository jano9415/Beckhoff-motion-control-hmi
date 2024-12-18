# Beckhoff-motion-control-hmi

In this project I use a Beckhoff servo motor to move an axis.
The servo motor can be controlled manually in five different ways.

Home: controlling to the home position.

Jog: controlling forward or backward while pushing the button Jog+ or Jog-

Move with velocity: controlling with a constant velocity forward or backward.

Relative move: controlling with a value forward or backward from the previous position to the new position.

Absolute move: controlling forward or backward to a certain position.

The position of axis is 0 and the drive is enabled. Drive enable is indicated by a green light:
![image](https://github.com/user-attachments/assets/f0c88013-ac3d-479a-a111-934a1e69a3a1)


The axis moves forward with velocity 18 after typing 18 in the velocity input field and clicking Move velocity button:
![image](https://github.com/user-attachments/assets/9876af02-67ce-4887-b857-30ef1e1c34cf)
![image](https://github.com/user-attachments/assets/579ca61b-8a8a-40e2-834d-d0d500688e55)

The axis halts if the Halt motion button is pressed. It is indicated by a yellow light:
![image](https://github.com/user-attachments/assets/2ed2a368-b7d0-4a32-a2de-cb3c65552e8d)

The axis stops if the Stop motion button is pressed. It is indicated by a red light. If it is in stop mode we can't move the axis at all:
![image](https://github.com/user-attachments/assets/475e1039-a82d-47e2-abd6-1ee17b1496f1)


The axis moves from home position to position 164 after typing 164 in the absolute position input field and typing the expected velocity value in absolute velocity input field and clicking Move absolute button:
![image](https://github.com/user-attachments/assets/e5cef4f8-7f3b-4d2d-9461-24e88d23c2ec)
![image](https://github.com/user-attachments/assets/99230947-ccf9-47ff-9eac-d4d62fdf0a4f)
![image](https://github.com/user-attachments/assets/145ceaa1-c27a-43cd-b9e7-4a3bd801047a)
![image](https://github.com/user-attachments/assets/f8809e5a-67f0-4aac-9a48-c14011575b82)


The axis moves from position 164 to position 144 after typing -20 in the relative position input field and typing the expected velocity value in relative velocity input field and clicking the Move relative button:
![image](https://github.com/user-attachments/assets/647c0aee-b7bb-4d3a-9a4d-79efb8ead20c)
![image](https://github.com/user-attachments/assets/cb3074ed-449b-4c7f-9d7f-8bc5b338ed63)
![image](https://github.com/user-attachments/assets/0da8d472-cfd8-47de-8f35-6bedd4cf1988)
![image](https://github.com/user-attachments/assets/8ac0653d-7880-4108-be1c-476c8d8c4321)


