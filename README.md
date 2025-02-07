# 🔥 RFID-based Attendance System using NodeMCU 🚀

## Project Overview 🌟

This **RFID-based attendance system** uses **NodeMCU ESP8266** and **MFRC522 RFID Reader** to automate the attendance process. The system logs attendance directly into **Google Sheets** 📊 in **real-time**, making attendance tracking **fast**, **accurate**, and **paperless**.

This project is a simple yet powerful **IoT-based solution** to replace traditional attendance systems, bringing efficiency to the classroom or workplace 🌐.

## Components Used 🛠️

- **NodeMCU ESP8266** 💻  
- **MFRC522 RFID Reader** 🔑  
- **RFID Tags** 🏷️  
- **Jumper Wires** 🔌  
- **Breadboard** 🟩  
- **USB Power Supply** ⚡

## Working ⚙️

1. **RFID Reader**: The **MFRC522 RFID Reader** scans the **RFID tags** and reads the unique ID associated with each tag 🏷️.
2. **NodeMCU ESP8266**: The **NodeMCU** is connected to the internet 🌐 and processes the **RFID tag data**.
3. **Google Sheets API**: The **NodeMCU** sends the student’s **name** and **timestamp** directly to **Google Sheets** 📊, updating the attendance in real-time.
4. **Real-Time Logging**: The data in **Google Sheets** is updated as soon as the RFID tag is scanned, showing the timestamp and student name ⏱️.

## Advantages ✨

- **Instant Attendance Marking**: The system logs attendance as soon as the **RFID tag** is scanned ⚡.
- **Real-Time Data Updates**: Data is sent to **Google Sheets** in real-time, reducing manual entry errors 📝.
- **Cost-Effective**: The system uses affordable hardware and is easy to set up 💡.
- **Automation**: Reduces human effort and increases accuracy with automatic attendance marking 🚀.
- **Scalable**: This system can be expanded to handle more students or integrated with other systems 🌐.

## Important Features 🔑

- **RFID Tags**: Unique ID for each student, ensuring accurate attendance tracking 🏷️.
- **Google Sheets Integration**: Allows easy monitoring and sharing of attendance data 📋.
- **Arduino IDE**: The project can be easily modified using the **Arduino IDE** for customization and improvements ⚙️.
- **Wi-Fi Enabled**: **NodeMCU ESP8266** connects to the internet for real-time data updates 🌐.
- **Easy Setup**: Simple steps to get started and customize the system to your needs 🛠️.

## Tech Stack 💻

- **NodeMCU ESP8266** 💻  
- **MFRC522 RFID Reader** 🔑  
- **Google Sheets API** 🌐📊  
- **Arduino IDE** 🧑‍💻

## Installation and Setup 🧑‍💻

1. **Install Arduino IDE**: If you haven't already, download and install the **Arduino IDE** from [Arduino Website](https://www.arduino.cc/en/software).
2. **Install ESP8266 Board**: 
   - Go to **File** > **Preferences** in the Arduino IDE.
   - Add this URL to the "Additional Boards Manager URLs": `http://arduino.esp8266.com/stable/package_esp8266com_index.json`
   - Go to **Tools** > **Board** > **Boards Manager**, then search for **ESP8266** and install it.
3. **Install Libraries**:  
   Go to **Sketch** > **Include Library** > **Manage Libraries** and install the following:
   - **MFRC522**: For RFID support.
   - **ESP8266WiFi**: For internet connectivity 🌐.
4. **Google Sheets Setup**:
   - Create a **Google Sheets** document 📝 with columns like **Name** and **Timestamp** ⏱️.
   - Follow this [guide](https://developers.google.com/sheets/api/quickstart) to set up the **Google Sheets API** and get your **API keys** 🔑.
   - Use the API key and credentials to connect **NodeMCU** to your **Google Sheets**.

5. **Upload Code**: Upload the provided **Arduino code** to your **NodeMCU** using the Arduino IDE 🔥.

For more details or the **working demo video**, visit my **GitHub Repo**: [GitHub Link](your_github_link_here) 🎥
