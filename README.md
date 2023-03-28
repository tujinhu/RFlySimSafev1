# RFlySimSafev1
RFlySimSafe is an automatic safety test and evaluation platform for UAV autopilot system, based on our previously released high-fidelity HIL simulation 
platform RflySim. RflySimSafe inherits the characteristics of RflySim, uses MATLAB/Simulink as the core programming platform for unmanned system model
design and algorithm development, and uses python as a tool for top-level vision and cluster algorithm development. On this basis, RflysimSafe 
has developed a fault injection interface, introduced open source database software, supports importing drone test cases into the platform, and 
realized fault injection and data analysis throughout the process.


## An example for RFlySimSafe.
A video demonstrating the RFlySimSafe platform by introducing some examples from the paper
[![An example for RFlySimSafe](https://res.cloudinary.com/marcomontalbano/image/upload/v1679997079/video_to_markdown/images/youtube--Abd9i0Ni7SQ-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://youtu.be/Abd9i0Ni7SQ "An example for RFlySimSafe")

## How to use the files.
1. Download and configure the RFlysim platform according to the tutorial of https://rflysim.com/docs/#/en/2_Configuration/SoftwareInstallation
2. Download the source code of RflySimSafe at https://github.com/tujinhu/RflyAutoTest
3. Change the platform path of the RflySimSafe model folder software-in-the-loop and hardware-in-the-loop one-key startup script (RflySimSafe\Model\***\***SITL(HITL).bat): Specifically,
![E:\Tujinhu\Git\RFlySimSafev1\image](image1.png "相对路径演示")

