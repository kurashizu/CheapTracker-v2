# CheapTracker-v2
Compact PCBs for BMI160 and QMC5883L based SlimeVR Tracker.

BMI160 and QMC5883L are chips that provide not bad accuracy for inertial motion tracking and that can be easily found and purchased on Chinese online shopping platforms in a relatively low price.
Compared to BNO0XX chips, this solution is less pricise in terms of magnetometer data. However, unless your mag environment is too bad, QMC5883L is able to be continuously calibrating the yaw data.

Small chassis PCB sized in 40x40mm with all SMD components on one face, top board can be fixed on top of it via 4xM2 copper cylinders;
![9a261899140a476062d572ae4ff6642c](https://github.com/user-attachments/assets/1671dfb4-029b-4634-9b05-9d3a2221aa4e)

This PCB is highly difficult to solder, thermostatic heating platforms that can heat up to 220℃ is a must.
Batteries should be under the size of 4x30x30mm and sticked to the back face of top board;

Check this link for more details:
https://oshwhub.com/kurashizu/cheaptracker-v2

Plus, if you are new to soldering PCBs and only got soldering iron, try my alternative board which uses the same chips as above.
![50fdfb9d095e69f10ef9428d868e6d90](https://github.com/user-attachments/assets/44470f45-6ab3-4efe-a010-ea570b93c051)

This is called CheapTracker-v2m, 'm' here stands for 'modular' meaning only direct-insertion-packaging modules (D1Mini, GY-BMI160, GY-273 and TP4056 charging board), resistors and diodes are mounted.
Please note that this alternative version is sitll pending its feasibility, try at your own risk. It'll be updated on OSHCHub when fully tested.
