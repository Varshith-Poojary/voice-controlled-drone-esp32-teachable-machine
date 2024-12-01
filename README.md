# Voice Controlled Drone Using ESP32 and Teachable Machine  

This project integrates ESP32 with Teachable Machine for a voice-controlled drone. The system supports dual-mode operation (voice and manual) and provides real-time responsiveness using WebSocket communication.  

---
## Description:
"Voice-controlled drone project integrating ESP32 for hardware control and a voice recognition model trained on Teachable Machine. The ESP32 code is available in the Voice_controlled_code directory. For connecting the Teachable Machine HTML interface with ESP32, refer to the esp32-teachable-machine-led-websocket repository. Replace the my_model folder in that repository with the folder containing your trained voice recognition model from Teachable Machine."


### System Architecture Overview
<img src="https://github.com/Varshith-Poojary/voice-controlled-drone-esp32-teachable-machine/blob/main/architecture.png" alt="architect" width="800"/>

---
## Components  

The following components are required for building the voice-controlled drone:  

1. **ESP32 Microcontroller**: Dual-core processor with Wi-Fi and Bluetooth capabilities for control and communication.  
2. **MPU6050**: 3-axis accelerometer and gyroscope for orientation and stability.  
3. **BLDC Motors (4)**: Brushless DC motors for drone propulsion.  
4. **Electronic Speed Controllers (ESC) (4)**: To regulate the speed of BLDC motors.  
5. **F450 Drone Frame**: Durable quadcopter frame with a 450mm wheelbase.  
6. **Propellers (4)**: 8x4.5 dimensions for lift generation.  
7. **Li-Po Battery**: 5200mAh, 11.1V for powering the drone.  
8. **Fly Sky FS-i6 Transmitter and Receiver**: For manual control of the drone.  
9. **Additional Accessories**: LED, Jumper wires, connectors, resistors, and a universal board.  

---

## Circuit Diagram  
<img src="https://github.com/Varshith-Poojary/voice-controlled-drone-esp32-teachable-machine/blob/main/circuit.png" alt="Circuit" width="600"/>

---

## Assembly Diagram  

Below is the assembly diagram of the drone:  
<img src="https://github.com/Varshith-Poojary/voice-controlled-drone-esp32-teachable-machine/blob/main/assembly.png" alt="assembly" width="600"/>

---

## Assembly Notes  

1. Place the MPU6050 at the center of the drone frame for accurate orientation sensing.  
2. Mount the ESP32 securely above the MPU6050 for clear communication and wiring.  
3. Attach ESCs and motors to the drone frame's arms, ensuring proper alignment of propellers.  
4. Ensure balanced placement of the Li-Po battery under the frame to maintain the center of gravity.  

---



