# ESP32-live-camra
ESP32-CAM live Wi-Fi camera that streams real-time video to a web browser. Connect to Wi-Fi, open the IP address, and view the live feed. Ideal for surveillance, robotics, and IoT projects.
# ESP32 Live Camera Streaming

This project turns an ESP32-CAM into a **live Wi-Fi camera** that streams video directly to your browser. It’s a simple, low-cost surveillance and monitoring solution that works without any external server or cloud service.

## 🚀 Features

* Live video streaming over Wi-Fi
* Works on phone, laptop, and desktop browsers
* No cloud required (local network streaming)
* Simple web interface
* Adjustable resolution and quality
* Capture snapshots from browser![Uploading Screenshot 2026-04-18 183551.png…]()

* Lightweight and fast startup

## 🧰 Hardware Required

* ESP32-CAM (AI Thinker or compatible)
* FTDI Programmer / USB-to-TTL
* 5V Power Supply (recommended for stability)
* Jumper wires

## 🔌 Wiring (ESP32-CAM ↔ FTDI)

| ESP32-CAM | FTDI             |
| --------- | ---------------- |
| 5V        | 5V               |
| GND       | GND              |
| U0R       | TX               |
| U0T       | RX               |
| IO0       | GND (for upload) |

⚠️ Remove IO0 from GND after uploading code.

## 📶 How It Works

1. ESP32 connects to your Wi-Fi network
2. Camera server starts automatically
3. Serial monitor shows IP address
4. Open IP in browser
5. View live video stream

Example:

```
http://192.168.1.50
```

## ▶️ Getting Started

1. Install ESP32 board in Arduino IDE
2. Select **AI Thinker ESP32-CAM**
3. Upload the code
4. Open Serial Monitor (115200 baud)
5. Copy IP address
6. Open in browser

## 📸 Use Cases

* Home security camera
* Robot FPV camera
* Door monitoring
* Baby monitor
* Smart IoT projects
* Remote surveillance

## ⚡ Notes

* Use **5V stable power** for best performance
* Works best on **2.4GHz Wi-Fi**
* Streaming quality depends on signal strength

## 📄 License

This project is open-source and free to use for personal and commercial projects.

---

**ESP32 Live Camera — Simple, Fast, and Wireless Video Streaming**
