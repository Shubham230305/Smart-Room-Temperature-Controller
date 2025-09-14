# 🌡️ Smart Room Temperature Controller using Arduino  

A **Smart Room Temperature Controller** built with Arduino to automatically maintain a comfortable temperature range (20°C – 25°C). The system uses a temperature sensor to monitor the room and activates a **fan** for cooling or a **heater** for warming when needed. A 16x2 LCD display provides real-time feedback, showing current temperature and system status.

---

## 🔧 Features  
- **Automated Temperature Control:** Turns fan ON when temperature > 25°C, heater ON when temperature < 20°C.  
- **Real-Time Monitoring:** Continuously displays temperature and system status on LCD.  
- **Energy Efficient:** Fan and heater remain OFF when temperature is within range.  
- **User-Friendly:** Easy-to-read display and simple setup.  
- **Versatile Applications:** Can be used in homes, offices, labs, greenhouses, and more.  

---

## 🛠️ Components  
- **Arduino Uno / Nano** – Central microcontroller  
- **Temperature Sensor** (LM35 / DHT11)  
- **Relay Module** – To control fan/heater  
- **Fan / Heater** – For cooling and heating  
- **16x2 LCD Display** – For real-time feedback  
- **Power Supply** – To power Arduino and components  
- Jumper wires, breadboard  

---

## ⚙️ Working Principle  
1. The temperature sensor reads the ambient temperature.  
2. Arduino compares it with the set thresholds (20°C & 25°C).  
3. If temperature > 25°C → Fan is turned ON.  
4. If temperature < 20°C → Heater is turned ON.  
5. If temperature is between 20°C – 25°C → Both remain OFF.  

---

## 🖼️ Circuit Diagram & 🎥 Working Video  

<table>
  <tr>
    <td align="center">
      <b>Circuit Diagram</b><br>
      <img src="https://github.com/Shubham230305/Smart-Room-Temperature-Controller/blob/main/IMAGES%20%26%20VIDEOS/SRTC_Circuit.png" alt="Circuit Diagram" width="400">
    </td>
    <td align="center">
      <b>Working Demo</b><br>
      <a href="https://github.com/Shubham230305/Smart-Room-Temperature-Controller/blob/main/IMAGES%20%26%20VIDEOS/NOT%20Mini%20Project.mp4">
        <img src="https://github.com/Shubham230305/Smart-Room-Temperature-Controller/blob/main/IMAGES%20%26%20VIDEOS/SRTC.png" width="400">
      </a><br>
      <sub>Click the image to watch the video</sub>
    </td>
  </tr>
</table>
