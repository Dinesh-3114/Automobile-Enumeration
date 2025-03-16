Automobile Enumeration  

Project Overview  
"Automobile Enumeration" is a smart parking management system designed to efficiently track parking slot availability across multiple floors using a React-based frontend and IoT hardware. The system integrates IR sensors and ESP32 to monitor vehicle entry and exit, updating real-time data on a web-based dashboard.  

This project aims to provide a digital solution for parking space management in large facilities such as malls, office complexes, and smart cities. It helps users monitor available parking slots, reduce congestion, and optimize space utilization.  

Key Features  
Real-time Monitoring: Updates parking slot availability instantly  
Multi-Floor Parking System: Supports multiple floors for large parking facilities  
User-Friendly Web Interface: Built using React.js for intuitive navigation  
IoT Integration: Uses ESP32 and IR sensors to track vehicle movement  
Remote Access: Users can check parking availability from anywhere  
Automated Counting: Reduces manual effort with sensor-based vehicle tracking  

Technologies Used  
Frontend: React.js, CSS  
Backend: ESP32 with C++ (Arduino)  
Database: Web-based real-time tracking  
Hardware Components  
ESP32 Microcontroller  
IR Sensors to detect vehicle entry and exit  
WiFi Module for web server communication  

System Architecture  
1. User interacts with the React.js web app to check available parking slots  
2. ESP32 reads IR sensor data when a vehicle enters or exits the parking area  
3. The ESP32 updates the slot availability in the database via WiFi  
4. The React app fetches real-time data and updates the parking status visually  

Output

![image](https://github.com/user-attachments/assets/720813e4-3e68-4b4a-a110-d2af5b5696b6)


![image](https://github.com/user-attachments/assets/d5585f73-cdca-4005-8ab2-2d26e5de53de)

