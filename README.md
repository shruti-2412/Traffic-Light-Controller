# Traffic-Light-Controller

### About the project:  
This project aims to control traffic at a busy square that experiences high traffic flow. It aims to regulate traffic efficiently and reduce congestion at the intersection by implementing a smart traffic light system.  
The intersection has four roads from all directions: East, West, North, and South. Each road has its traffic light pole with three LEDs (Red, Yellow, Green). The traffic lights follow a sequence where only one direction has a green light at a time, while others show red or yellow lights.

### Components Used:
Arduino Uno R3  
Breadboard  
12 LEDs (4 Red, 4 Yellow, 4 Green)  
12 1kΩ resistors  
25 Jumper Wires for Connections 

![image](https://github.com/shruti-2412/Traffic-Light-Controller/assets/99483160/7ac4ddc9-6fe9-42c4-a0a2-b4e57a0c37ef)

### Traffic Light Sequence:  
Green light glows for 10 seconds.  
Yellow light glows for 4 seconds as a transition phase.  
Red light indicates a stop.  

Traffic Flow Control is as follows:  
● Initially, the East direction has a green light, allowing traffic from that direction.  
● After 6 seconds, the Yellow light on the East starts to glow for 4 seconds to signal a transition.  
● Subsequently, the East light turns Red, and the West direction light turns Green, allowing traffic from the West side.  
● This sequence continues in all directions, ensuring smooth traffic flow.  

![image](https://github.com/shruti-2412/Traffic-Light-Controller/assets/99483160/3d428d21-38b4-407d-8f09-bc4e61b93629)

The traffic light controller logic is implemented using Arduino Uno and programmed in C++ language. The Arduino code includes:  
- Defining pin configurations for LEDs and resistors  
- Implementing a traffic light sequence algorithm with appropriate delays for Green and Yellow lights.  
- Controlling the flow of traffic lights based on predefined timings.

![image](https://github.com/shruti-2412/Traffic-Light-Controller/assets/99483160/75eb22d1-64c4-4507-9c9f-31a952e66fe9)

![image](https://github.com/shruti-2412/Traffic-Light-Controller/assets/99483160/f5ffedf9-6e2b-4f1b-8582-900bf61f6f63)

Arduino Uno's flexibility allows for easy prototyping and implementation of various projects. Arduino enables automation in traffic management systems, enhancing efficiency and reducing human intervention. Arduino boards are cost-effective solutions for developing smart systems like traffic light controllers. The Arduino code can be customized and updated as per specific traffic patterns or requirements.  

### Conclusion :  
● The Traffic Light Controller project demonstrates the practical application of Arduino in traffic management systems.  
● This project contributes to safer and smoother urban transportation by efficiently controlling traffic flow and reducing congestion.  
● Arduino's versatility and programmability make it an ideal platform for developing innovative solutions for modern-day challenges like traffic management.  
