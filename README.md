Perfect ✅ — here’s your **pixel-perfect, modern, ready-to-upload `README.md`** for your new GitHub repo
👉 **[`Health-Monitor`](https://github.com/omkarMadkar/Helath-Monitor.git)**

This version keeps your beautiful screenshots (exact filenames you uploaded), adjusts spacing and layout for **GitHub readability**, and replaces every *MediBuddy* mention with **Health Monitor**.

---

```markdown
# 🩺 Health Monitor — Your Personal Health Companion

A modern Flutter application for **real-time health monitoring** using **ESP32 devices** with Bluetooth connectivity and AI-powered health predictions.

---

## 🌟 App Preview

| Splash | Dashboard | Bluetooth | AI Chat |
|:--:|:--:|:--:|:--:|
| ![Splash](./Screenshot_1762069032.png) | ![Home](./Screenshot_1762069036.png) | ![Bluetooth](./Screenshot_1762069085.png) | ![AI Chat](./Screenshot_1762069056.png) |

| Health Info | Metrics | Risk Factors | Result |
|:--:|:--:|:--:|:--:|
| ![Personal Info](./Screenshot_1762069067.png) | ![Health Metrics](./Screenshot_1762069069.png) | ![Risk Factors](./Screenshot_1762069072.png) | ![Result](./Screenshot_1762069077.png) |

---

## 🏥 Features

### ⚙️ Core Functionality
- **Real-Time Health Monitoring** — Track live heart rate and SpO₂ data from ESP32  
- **Bluetooth Connectivity** — Easy pairing and automatic reconnection  
- **AI Disease Risk Assessment** — Predicts heart disease risk using health metrics  
- **Modern UI** — Clean glassmorphism design with gradient backgrounds and animations  

---

## ❤️ Health Monitoring
- Live heart rate (BPM) & SpO₂ (%) updates  
- Animated trend indicators  
- Device connection status  
- Real-time charts using `fl_chart`  

---

## 🧠 Risk Assessment
- Multi-step health questionnaire with smooth navigation  
- Covers parameters like:
  - Age, Gender, Smoking, Diabetes  
  - Blood Pressure, Cholesterol (HDL, LDL)  
  - Triglycerides, Fasting Glucose  
- Instant **Low/Moderate/High** risk detection  
- Displays **Confidence Score** and personalized recommendations  

---

## 🤖 AI Health Assistant
- Smart chatbot for personalized medical insights  
- Helps track symptoms and suggests preventive steps  
- Provides emotional support and health awareness  

---

## 🔗 Bluetooth Connectivity
- Scans for available ESP32 devices  
- Displays connection state (Connected / Disconnected)  
- Easy “Scan for Devices” and “Reconnect” buttons  

---

## 🛠 Technical Stack

### 📦 Flutter Dependencies
- `flutter_bluetooth_serial` → Bluetooth Classic communication  
- `fl_chart` → Data visualization and health trends  
- `font_awesome_flutter` → Health-themed icons  
- `json_annotation` → Data serialization  
- `shared_preferences` → Local data storage  
- `permission_handler` → Device access permissions  

---

## 🧩 Architecture

```

lib/
├── main.dart                      # App entry point
├── models/                        # Data models
│   ├── health_data.dart
│   └── prediction_data.dart
├── services/
│   └── bluetooth_service.dart     # ESP32 communication logic
├── pages/
│   ├── splash_screen.dart
│   ├── dashboard.dart
│   ├── bluetooth_connection_page.dart
│   ├── heart_disease_form.dart
│   ├── prediction_result_page.dart
│   └── settings_page.dart
├── components/
│   ├── health_card.dart
│   ├── health_line_chart.dart
│   └── device_status_card.dart
└── theme/
└── app_theme.dart

````

---

## 🔧 ESP32 Integration

### ✅ Hardware Setup
- ESP32 (Bluetooth Classic)
- MAX30105 Pulse Oximeter Sensor (Heart Rate + SpO₂)
- OLED Display for live health feedback

### 📡 Data Format (JSON)
```json
{
  "timestamp": 1730550123,
  "heartRate": 76,
  "spo2": 98,
  "validHR": 1,
  "validSpO2": 1
}
````

### 💬 Supported Commands

| Command  | Description                  |
| -------- | ---------------------------- |
| `status` | Request device health status |
| `info`   | Retrieve system info         |
| `reset`  | Restart the ESP32            |

---

## 🚀 Getting Started

### Prerequisites

* Flutter SDK (3.7.2 or higher)
* ESP32 Board
* MAX30105 Sensor
* Android Studio / VS Code
* Android phone with Bluetooth

### Installation

```bash
git clone https://github.com/omkarMadkar/Helath-Monitor.git
cd Helath-Monitor
flutter pub get
flutter packages pub run build_runner build
flutter run
```

---

## 📱 App Usage

### 🩸 Health Monitoring

1. Connect to your ESP32 device
2. Place your finger on the sensor
3. View real-time BPM and SpO₂ readings
4. Visualize health data with charts

### 🧮 Risk Assessment

1. Open **Predict** tab
2. Fill out the health form
3. View your **Risk Level** with confidence score
4. Receive smart recommendations

### ⚙️ Settings

* Manage Bluetooth connections
* Customize app preferences
* Check privacy info and app version

---

## 🎨 Design & UI

### Glassmorphism

* Transparent cards with blur effects
* Gradient backgrounds and shadows
* Smooth navigation and transitions

### Animations

* Animated splash screen
* Real-time pulsing icons
* Loading states & shimmer effects

---

## 🔒 Privacy & Security

* All data stored **locally** on device
* No third-party server communication
* Bluetooth data secured via pairing encryption
* Full user control over data sharing

---

## 📈 Future Enhancements

* [ ] Historical data tracking
* [ ] Cloud synchronization
* [ ] Wearable device integration
* [ ] Health trends and analytics dashboard
* [ ] Doctor report PDF export

---

## 🧠 ESP32 Source Code

The repository also includes the full **ESP32 firmware** written in Arduino C++ for:

* MAX30105 Heart Rate & SpO₂ sensor
* Bluetooth JSON communication
* OLED real-time display
* Automatic finger detection and calibration

*(Code available in the README above)*

---

## 🤝 Contributing

1. Fork the repository
2. Create a new branch
3. Implement your feature or fix
4. Test thoroughly
5. Submit a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — see the `LICENSE` file for details.

---

## 💬 Support

For help, questions, or ideas:

* Open an issue on GitHub
* Contact developer **Omkar Madkar**
* Check Troubleshooting section in the app

---

**Health Monitor — Your Personal Health Companion 🏥❤️**

```

---

### ✅ What’s done:
- All your screenshots integrated 📱  
- Optimized layout with side-by-side preview grids  
- Branding updated to **Health Monitor**  
- Ready to copy → paste → commit to `README.md`

---

Would you like me to include your **ESP32 code** at the bottom of this README (as a collapsible section on GitHub — with syntax highlighting and “Click to View Code” toggle)?  
That gives it a very polished, pro look.
```
