![image](https://i.ibb.co/st0d159/1.png)


<br/>
Firemate is a tool to help firefighters to speed up their response.

## ❗️  Introduction
The average response time for firefighters in some areas of Tamil Nadu can exceed the recommended standard of 15 minutes, mainly due to delays in receiving timely information about fire incidents. Such delays often result in significant loss of life and property. To address this issue, we developed Firemate, an IoT-based emergency response system designed to speed up firefighter response. The system uses ESP8266, ESP32-CAM, MQ-2 smoke/gas sensor, KY-026 flame sensor, and NEO-6M GPS module to detect fire incidents and transmit real-time data. Firemate aims to help firefighters in Tamil Nadu receive alerts faster and reduce fire-related losses.
<br/>

## 🎯 **Our Goal**

![]<img width="1165" height="671" alt="image" src="https://github.com/user-attachments/assets/ac472e90-0e1a-481a-8e36-580b759c5c95" />
)

**Firemate** aims to address UN Sustainable Development Goals (SDGs) 9. industry, innovation and infrastructure, 11. sustainable cities and communities, and 17. partnerships for the goals. Our overarching goal is make a new innovation to reduce communities loss and make a partnership with firefighter and goverment. 
<br><br>

## 🛠  Project Architecure

![structure](https://i.ibb.co/hm3Crjh/3d363564353730.png)

**Firemate** uses 3 Google Technologies;
- **Firebase** to connect IOT to the app.
  - **Realtime Database** to store the data (status, lat, lon, etc).
  - **Firestore** to save the captured image from ESP32-CAM.
- **Flutter** as the android app.
- And **Google Maps** to show direction to the fire incident.

**Firemate** also uses IOT that utilized ESP8266 as the microcontroller, ESP32-CAM, MQ-2 Smoke/Gas sensor, KY-026 flame sensor and NEO-6M GPS Module, you can check the code and detailed pin connection [here](https://github.com/metot-technologies/firemate-iot). The schematic as shown below.<br/>
![IOT-shcematic](https://i.ibb.co/XCVWC96/schematic.png)


 <br/>

 
 
## 👩🏼‍💻  User Guide
### 01 Home Screen
| Screen                                | Explanation |
|---------------------------------------|-------------------------------------------------------|
|**1) Home Screen** <br/> <br/> <img src="https://i.ibb.co/CJX3n2R/image.png" width="250"/> | Firefighter can see fire incident list that they need to response. <br/> <br/> |
| **2) Selesai Button** <br/> <br/> <img src="https://i.ibb.co/0Bs1YVL/c0a6bec902.gif" width="250"/> | When "Selesai" button clicked, the fire incident will marked as done. |
| **3) Lokasi Button** <br/> <br/> <img src="https://i.ibb.co/Bn3dh9r/Screen-recording-20240503-203513.gif" width="250"/> | When "Lokasi" button clicked, the app will open Google Maps and show the direction to the fire incident location. |
| **4) Preview Image** <br/> <br/> <img src="https://i.ibb.co/mBg8hRB/Screen-recording-20240503-203558.gif" width="250"/> | the image can be viewed to check if there is a true or false notification |

### 02 History Screen
| Screen                                | Explanation |
|---------------------------------------|-------------------------------------------------------|
|<img src="https://i.ibb.co/VJ3Hh6T/image.png" width="250"/> | Firefighter can see history of the fire incident that they already response. &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <br/> <br/> [ User Guide ] <br/>  1. [Lokasi] To open google maps that show direction to the location |
<br/>

## 📲  Execution Method

###  For Android User

1. Download the apk file at [Releases tab](https://github.com/metot-technologies/firemate/releases).
2. Run the apk file on your phone.

### For Dev

1. Clone the project
```sh
git clone https://github.com/metot-technologies/firemate.git
```
2. Navigate to the project directory
```sh
cd firemate
```
3. Install dependencies
```sh
flutter pub get
```
4. Run the app
```sh
flutter run
```
<br/>
