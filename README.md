# 🚗 Smart Parking System using ESP32-CAM

Welcome to the Smart Parking System project! This system leverages the ESP32-CAM to create an intelligent parking management solution that integrates image recognition, web server communication, and real-time updates. 

## 🌟 Features

- **📶 WiFi Connectivity**: Seamlessly connects to your network for remote communication.
- **🔒 Secure HTTPS**: Ensures secure communication with your server.
- **📷 Camera Functionality**: Captures images of vehicle number plates for recognition.
- **🕒 Real-Time Clock**: Accurate timekeeping using NTP for Indian Standard Time (IST).
- **🌐 Web Interface**: Live web page displaying real-time status, parking information, and captured images.
- **📤 Image Upload**: Automatically uploads captured images to a remote server.
- **🔄 Dynamic Updates**: Reflects real-time parking status and availability.
- **🚪 Barrier Control**: Operates the parking barrier using a servo motor based on vehicle entry and exit.
- **🔔 Vehicle Detection**: Uses sensors to detect vehicles and manage parking spaces.
- **📜 Parking History**: Logs valid number plates with timestamps for historical reference.

## 🚀 How It Works

1. **Connect to WiFi**: The ESP32-CAM connects to the specified WiFi network.
2. **Initialize Camera**: Configures the camera for capturing images.
3. **Start Web Server**: Sets up a web server to handle client requests.
4. **Update Time**: Uses NTP to fetch and display the current time.
5. **Handle Requests**: Processes image capture and upload based on web interface interactions.
6. **Manage Parking**: Updates parking space availability and logs parking history.
7. **Control Barrier**: Opens and closes the parking barrier using a servo motor based on vehicle detection.

## 🔧 Setup

1. **Configure WiFi**: Update the `ssid` and `password` with your network credentials.
2. **Server Details**: Replace `serverName`, `serverPath`, and `apiKey` with your server information.
3. **Compile and Upload**: Upload the code to your ESP32-CAM using the Arduino IDE.

## 🛠️ Code Overview

- **Libraries**: Includes libraries for NTP, and servo control.
- **WiFi & Server Setup**: Manages connection to WiFi and server details.
- **Camera Configuration**: Initializes and configures the camera settings.
- **Web Server**: Handles client requests and updates the web page.
- **Image Handling**: Captures images, uploads to the server, and processes responses.
- **Barrier Control**: Opens and closes the parking barrier based on vehicle detection.

## 📝 Note

- Ensure to replace placeholder values (e.g., WiFi credentials, server details) with actual data.
- For production, consider implementing proper certificate validation and additional security measures.

## 📬 Contact

For any questions or contributions, feel free to reach out or open an issue on the GitHub repository.

Happy parking! 🚗💨
