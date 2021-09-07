## DIY 3" Quadcopter

![20210612_031531](https://user-images.githubusercontent.com/41247872/132414129-9f696ef7-e17e-4897-9859-c882d4a8e86c.jpg)

A Sub-250g DIY drone. Capable of FPV, 3-4S batteries, with 1407 motors and a 3" toohpick frame. This build came out to be around 248g with the battery.

### Design Constraints

The primary constraint for this project was the weight requirement. When a drone is under 250g, it is subject to less regulation from Transport Canada and is generally safer to fly. I would need to carefully research how much weight each component on the quadcopter weighed. This includes all the functional components and screws.

The configuration I decided on was to use a small frame and build, where the total weight without the battery would be around 70g. This is without any screws or additional wiring so it was a good start. The battery itself was a 4s 1300mAh LiPo battery, coming in at about 150g when fully charged. The controller board was also an All-in-One board, meaning that it had the 4 ESCs, PDB, and FC on the same board. This drastically brought down the weight and complexity of the quadcopter. 

### Mounting hardware

As each component was not standard to the chosen frame, I had to design some lightweight mounting hardware to both secure and protect components. 

For the camera, a box where it could be slipped into was designed and printed in PLA.

![image](https://user-images.githubusercontent.com/41247872/132413087-a1ce06b0-330f-4656-a0dd-3a677531a181.png)

Intial ideas had components being mounted under and over an adapter plate, while the plate was mounted to the frame.

![image](https://user-images.githubusercontent.com/41247872/132412966-1dfbb6e4-3548-44f2-be94-0fbd4d29b2c2.png)
![20210602_174258](https://user-images.githubusercontent.com/41247872/132411525-b0745e54-013c-4a9f-9dcc-3acd94685b12.jpg)

This proved effective for keeping weight down and heat dissipation but left components very vulnerable. I looked for a solution that had the FC and radio reciever enclosed to be protected from crashes and such. I came up with a sort of stacked "cage" that protected the main components. This added about 10g to the final build.

![image](https://user-images.githubusercontent.com/41247872/132413578-e7a08109-38cd-457a-9eeb-fa50962aa33e.png)


After all the sodlering had been done, I also printed out a battery protector, found here: https://www.thingiverse.com/thing:2256553 . The build was completed by early June 2021, and was extensively flown in August 2021. An issue I came across were the solder connections of the motors to the board. These connections came loose during an outdoor crash since they were slightly exposed from the cage.


