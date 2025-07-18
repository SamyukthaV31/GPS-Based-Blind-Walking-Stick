# GPS-Based Smart Walking Stick for the Visually Impaired
A smart, IoT-enabled assistive device designed to help visually impaired individuals navigate safely and independently. This walking stick combines obstacle detection, environmental sensing, real-time object recognition, GPS tracking, and emergency communication.

💡 Features

* **Obstacle Detection**: Ultrasonic sensor alerts the user when obstacles are within 100 cm.
* **Water Detection**: Water level sensor detects wet/slippery surfaces and triggers buzzer alerts.
* **Object Recognition**: ESP32-CAM with FOMO algorithm detects and classifies nearby objects.
* **GPS Tracking**: Tracks user location in real-time using the NEO-6M module.
* **Emergency Alert**: Pressing a button sends the user’s GPS location to a guardian via Twilio SMS.

## 🛠️ Hardware Components

* ESP32-S3 WROOM
* Arduino UNO
* ESP32-CAM (OV2640)
* Ultrasonic Sensor (HC-SR04)
* Water Level Sensor
* GPS Module (NEO-6M)
* Push Button
* Buzzer
* Jumper Wires
* Power Supply

## 📦 Technologies Used

* C/C++ (Arduino)
* Arduino IDE
* Twilio Cloud API
* FOMO Object Detection (Edge Impulse)

## ⚙️ How It Works

1. **Obstacle Detection**: Ultrasonic sensor detects objects; buzzer alerts user.
2. **Water Detection**: Sensor checks for wet surfaces; buzzer beeps accordingly.
3. **Object Recognition**: ESP32-CAM processes visuals using FOMO model.
4. **Emergency Protocol**: On button press, GPS data is sent via Twilio to the guardian’s phone.

## 🔧 Setup Instructions

1. Connect components as per the wiring diagram.
2. Flash Arduino and ESP32-CAM with respective firmware.
3. Set up Wi-Fi credentials and Twilio API credentials in code.
4. Upload FOMO model to ESP32-CAM via Edge Impulse.
5. Power the system and test sensor outputs.

## 📈 Results

* Accurate obstacle detection up to ±3 cm
* Object recognition accuracy: \~85-90%
* GPS accuracy: ±3m in open areas
* Real-time SMS alerts with clickable Google Maps links

## 🧠 Future Improvements

* Enhanced battery life and miniaturized design
* Voice feedback using onboard speaker
* Integration with wearable assistive systems
* Multi-language support for alerts

## 🤝 Contributors

* Ashmita D
* Samyuktha V
* Shri Namrutha S

