
***

# 🩺 MediBuddy – Health Monitoring App

A modern Flutter application for **real-time health monitoring** using an ESP32-based IoT health sensor.  
Connect via Bluetooth to capture vitals like **Heart Rate (BPM)** and **SpO₂**, get live data visualizations, risk analysis, and a sleek glassmorphism UI.

***

## 🌟 Features

### 🧠 Core
- Real-time health monitoring from ESP32 sensors
- Bluetooth connectivity and auto-reconnect
- Disease risk assessment based on medical parameters
- Elegant UI with glassmorphism and animations

### ❤️ Health Monitoring
- Live BPM & SpO₂ display
- Real-time line charts for vitals
- Device connection status with battery level
- Responsive layout for phones and tablets

### 🔍 Risk Assessment
- Multi-step heart disease prediction form
- Inputs: age, gender, smoking, BP, cholesterol, diabetes, chest pain, HDL/LDL/TG, fasting glucose
- Instant risk score and recommendations

### 🎨 UI Design
- Splash screen with logo animation
- Dashboard with modular cards
- Bluetooth pairing/connection page
- Settings for preferences and device management

***

## 🖼️ App Screenshots

Below are some highlights of MediBuddy UI and hardware integration:

### Splash Screen

![Splash Screen](android/app/src/main/res/S



### Dashboard – Health Metrics

![Dashboard Health Metrics](android/app/src/main/res/Screenshot_ Device Connection

![Bluetooth Device Connect](android/app/src/main/res/Screenshot_ Disease Risk Assessment (Risk Factors)

![Risk Factors Step](android/app/src/main/res/Screenshot_ Assessment – Personal Information Step

![Personal Info Step](android/app/src/main/res/Screenshot_ – Health Metrics Step

![Health Metrics](android/app/src/main/res/Screenshot_ Assessment – Result (Low Risk)

![Risk Assessment Result](android/app/src/main/res/Screenshot_ & Predict Step

![Review Your Information](android/app/src/main/res/Screenshot_ Health Assistant Chat

![AI Health Assistant](android/app/src/main/res/Screenshot_32 Hardware Setup

![ESP32 Health Monitor Setup](android/app/src/main/res/image Tech Stack

### ⚙️ Flutter Dependencies
```yaml
dependencies:
  flutter_bluetooth_serial: ^0.4.0
  fl_chart: ^0.64.0
  font_awesome_flutter: ^10.4.0
  json_annotation: ^4.8.1
  shared_preferences: ^2.2.0
  permission_handler: ^11.0.0
```

***

## 📁 App Structure

```bash
lib/
├─ main.dart
├─ models/
│  ├─ health_data.dart
│  └─ prediction_data.dart
├─ services/
│  └─ bluetooth_service.dart
├─ pages/
│  ├─ splash_screen.dart
│  ├─ bluetooth_connection_page.dart
│  ├─ dashboard.dart
│  ├─ heart_disease_form.dart
│  ├─ prediction_result_page.dart
│  └─ settings_page.dart
├─ components/
│  ├─ health_card.dart
│  ├─ health_line_chart.dart
│  └─ device_status_card.dart
└─ theme/
   └─ app_theme.dart
```
***

## 🔌 ESP32 Integration

### 🧠 Hardware Features

* Sensor: MAX30105 Heart Rate & SpO₂ sensor
* Communication: Bluetooth Classic (Serial)
* Display: 128×64 OLED screen
* Data Format: JSON packets sent to app

### 📡 Sample JSON Data

```json
{
  "timestamp": 1724567890,
  "heartRate": 78,
  "spo2": 97,
  "validHR": 1,
  "validSpO2": 1
}
```

### 🛠️ Supported Commands

| Command  | Description                     |
| -------- | ------------------------------- |
| `status` | Returns current sensor readings |
| `info`   | Returns device info JSON        |
| `reset`  | Reboots ESP32 device            |

***

## 🚀 Getting Started

1. Clone the repository  
2. Navigate to the project directory  
3. Install dependencies:
    ```bash
    flutter pub get
    ```
4. Generate JSON serialization code:
    ```bash
    flutter packages pub run build_runner build
    ```
5. Run the app:
    ```bash
    flutter run
    ```

### ESP32 Setup
1. Flash the ESP32 firmware
2. Set Bluetooth name to **ESP32-Health-Pro**
3. Power on ESP32 → open MediBuddy → tap **Scan Devices**
4. Connect and start monitoring!

***

## 🗂️ Adding Screenshots/Images

1. Place all screenshot images in your Android project at:  
   ```
   android/app/src/main/res/
   ```
2. Use the following file names (as shown above):
   - `Screenshot_1762069032.jpg` (Splash Screen)
   - `Screenshot_1762069036.jpg` (Dashboard)
   - `Screenshot_1762069040.jpg` (Bluetooth Device Connect)
   - `Screenshot_1762069072.jpg` (Risk Factors)
   - `Screenshot_1762069067.jpg` (Personal Info Step)
   - `Screenshot_1762069069.jpg` (Health Metrics Step)
   - `Screenshot_1762069085.jpg` (Risk Assessment Result)
   - `Screenshot_1762069077.jpg` (Review Information)
   - `Screenshot_1762069056.jpg` (AI Assistant Chat)
   - `image.jpg` (ESP32 Setup)
3. Reference these in your README as shown above using the markdown image syntax:
   ```
   ![Alt Text](android/app/src/main/res/FILENAME.jpg)
   ```
   Where `FILENAME.jpg` is replaced with each actual screenshot/hardware image filename.

***

## 📜 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

***

## 💬 Support

* Open an issue on [GitHub Issues](https://github.com/omkarMadkar/Helath-Monitor/issues)
* Email the dev team
* Refer to the Troubleshooting section above

***

## 🧭 Credits

Developed with ❤️ by **Omkar Madkar**  
👨‍💻 [GitHub Profile](https://github.com/omkarMadkar)

***

