# IoT Weather Station with NodeMCU ESP8266  

## Overview  

The **IoT Weather Station with NodeMCU ESP8266** is a project that demonstrates how to create a simple online weather station using the NodeMCU ESP8266 (Wemos D1) Wi-Fi development board. This project collects weather data such as **temperature**, **humidity**, **rain**, and **vibration** and displays it on a local website hosted by the NodeMCU.  

---  

## Components Required  

To build the IoT Weather Station, you will need the following components:  

- **NodeMCU ESP8266** board  
- **DHT11** sensor (for temperature and humidity)  
- **Rain sensor**  
- **Vibration sensor**  
- Breadboard  
- Jumper wires  

---  

## Circuit Diagram  

Below is the circuit diagram for setting up the IoT Weather Station. Refer to the image below for the detailed layout:  

![Circuit Diagram](https://github.com/danielchristopher513/IOT_Based_Weather_Station_Using_NodeMCU/blob/main/circuit_diagram.png)  

---  

## Displaying the Data on the Website  

Follow these steps to display weather data on a local website:  

1. **Connect the NodeMCU:** Connect the NodeMCU ESP8266 to your computer using a USB cable.  
2. **Upload the Code:** Open the Arduino IDE, select the correct board and port, and click the upload button to upload the code.  
3. **Ensure Network Connection:** Make sure your laptop or smartphone is connected to the same Wi-Fi network as the NodeMCU.  
4. **Retrieve the IP Address:**  
   - After uploading the code, open the Serial Monitor in the Arduino IDE.  
   - Set the baud rate to `115200`.  
   - Note the IP address displayed in the monitor.  
5. **Access the Website:**  
   - Copy the IP address from the Serial Monitor.  
   - Paste it into your browser’s address bar.  
   - The webpage will display live weather data and refresh automatically every 10 seconds (you can modify this interval in the code).  

---  

## Contribution  

Feel free to fork this repository, suggest improvements, or create a pull request to enhance the project.  

## License  

This project is licensed under the [MIT License](LICENSE).  

---  

### Happy Coding! 🚀  
