\# STM32 and Embedded Linux-Based Real-Time Attitude Control and Telemetry System



\## About the Project



This project involves developing a two-axis aircraft model stabilization and telemetry system using an STM32-based real-time control unit and a companion computer running Embedded Linux.



\## System Architecture



\- \*\*STM32 Nucleo-F446RE:\*\* Reading IMU data, calculating roll/pitch angles, PID control, and servo control.

\- \*\*MPU9250:\*\* Acquiring accelerometer and gyroscope data.

\- \*\*2× MG996R Servo:\*\* Actuating the two-axis gimbal mechanism.

\- \*\*Raspberry Pi Zero 2 W:\*\* Telemetry, data logging, and Linux-based monitoring.

\- \*\*Ground Station:\*\* Visualizing actual angles, target angles, and system status on a computer.



\## Development Plan



1\. Setting up the development environment and project infrastructure.

2\. Developing the IMU driver and implementing angle calculations.

3\. Servo control and PID-based stabilization.

4\. Task management using FreeRTOS.

5\. UART communication between STM32 and Raspberry Pi.

6\. Telemetry, data logging, and system testing.



\## Project Objective



To gain practical experience in embedded software, real-time control, sensor processing, communication, and hardware-software integration.



> Note: This project is a desktop prototype designed for educational and demonstration purposes; it is not a real flight control system.

