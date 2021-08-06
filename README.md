# MATLAB-Simulink-----DC-motor-Drive-based-on-buck-chopper
DC Drivers considering all the scenarios.
The Drivers are classified as following:
1. DC driver based on a buck chopper
Description:
File 1: With different values of duty cycle for the chopper
1. no-load
2. variable load torque
File2: Correction and non-correction
1. no-load without correction
2. no-load with correction
3. variable load torque without correction
4. variable load torque with correction

2, DC driver based on a half-wave rectifier
Description:
The model could be sub-divided into three main steps:
1. Running for no-load torque with changing thyristor pulses
2. Running for load torque with changing thyristor pulses
3. Running for no-load torque with changing the fire angle of the thyristor for Armature

3. Driver based on Full-wave rectifier
Description:
The model could be run in two ways :
1. Constant Fire angle delay
2 . Changing the firing angle of the rectifier for the armature

4. DC driver based on a Three-Phase full wave rectifier
Description:
The model is divided into two files:
1. Without correction (Gain=1 and integrator = 0)
2. With correction
