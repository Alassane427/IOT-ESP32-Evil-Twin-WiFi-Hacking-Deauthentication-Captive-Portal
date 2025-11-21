[![Github issues](https://img.shields.io/github/issues/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/issues)
[![Github forks](https://img.shields.io/github/forks/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/network/members)
[![Github stars](https://img.shields.io/github/stars/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal/stargazers)
[![Top language](https://img.shields.io/github/languages/top/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)](https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal)

---

## 🧠 Tags

`ESP32` `IoT` `WiFi Hacking` `Deauthentication` `Captive Portal` `Microcontroller Security` `Arduino`

---

---

# 🚨 ESP32 Evil Twin WiFi Hacking | Deauthentication & Captive Portal 🚨

> **Disclaimer:** This project is for **educational purposes only**. Use it responsibly and legally. Unauthorized attacks on networks are illegal in most countries. 🌐🔒

---

![Profile Views](https://komarev.com/ghpvc/?username=aadesh0706&color=blue)  
*Active since*: `September 2024`

**Account From:** `September 2020`

---

### 🎥 **Demo Video**

Check out the demo of this project in action! 🎬  
[![ESP32 Evil Twin WiFi Hacking](https://img.youtube.com/vi/AEb33trYEAY/0.jpg)](https://www.youtube.com/shorts/AEb33trYEAY)  
Click the thumbnail or follow [this link](https://www.youtube.com/shorts/AEb33trYEAY) to watch.

---

### 🎯 **Project Overview**

This repository demonstrates how to execute an **Evil Twin WiFi Hacking** attack using an **ESP32** module. The attack forces users off their legitimate network by sending **deauthentication packets** and lures them into connecting to a fake access point where a **captive portal** captures their WiFi credentials. 

The project leverages **HTML**, **CSS**, and **JavaScript** to build a custom front-end for the captive portal, making it look like a legitimate login page.

---

## 🚀 **Features**
- 🛑 **Deauthentication Attack**: Disconnects devices from their current WiFi network.
- 🌐 **Captive Portal**: A fake login page where users unknowingly enter their WiFi credentials.
- 🎨 **Custom Frontend**: Built using **HTML**, **CSS**, and **JavaScript** for user interaction.
- 📡 **ESP32 Integration**: WiFi hacking on a powerful yet affordable ESP32 module.

---

## 🛠️ **Setup and Installation**

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/aadesh0706/IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal.git
cd IOT-ESP32-Evil-Twin-WiFi-Hacking-Deauthentication-Captive-Portal
```

### 2️⃣ **Install Required Libraries**

Make sure you have the necessary libraries and tools installed to program the ESP32:

- **ESP32 Core for Arduino**: [Install Guide](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)

### 3️⃣ **Upload the Code to ESP32**
1. Open the `esp32_deauth_attack.ino` file in your Arduino IDE.
2. Connect your ESP32 to your computer via USB.
3. Select your ESP32 board from the Tools > Board menu.
4. Click **Upload**.

### 4️⃣ **Customize the Captive Portal**
- The captive portal files are located in the `html/` folder. 🎨
- You can easily edit the design using **HTML**, **CSS**, and **JavaScript** to match your desired look and feel.

---

## ⚡ **How to Run the Attack**

1. **Launch the Deauthentication Attack**: 📶 Force devices off the legitimate WiFi network.
2. **Start the Fake AP**: 🖧 Broadcast your rogue access point.
3. **Use the Captive Portal**: 🌐 When users attempt to reconnect, they are directed to a fake login page.
4. **Capture WiFi Credentials**: 🔐 Credentials entered by users are logged on the ESP32.

---

## 📂 **Files Included**
- `esp32_deauth_attack.ino`: The main code for the deauthentication attack.
- `html/`: Contains all the files for the captive portal (HTML, CSS, JavaScript).
- `README.md`: Overview, setup instructions, and usage information.

---

## 🔗 **How It Works**

1. **Deauthentication Attack**: The ESP32 sends deauth packets to disconnect devices from their original network.
2. **Rogue Access Point**: After being disconnected, the ESP32 broadcasts a rogue AP with a similar name (SSID) to the legitimate one.
3. **Captive Portal**: When users attempt to connect to the rogue AP, they are redirected to a fake login page asking for WiFi credentials.
4. **Credentials Logged**: Any credentials entered are captured and stored on the ESP32.

---

## 💻 **Technologies Used**
- **ESP32**: Low-cost WiFi module.
- **HTML**: Structure for the captive portal.
- **CSS**: Styling for a user-friendly portal interface.
- **JavaScript**: Handles user interactions and form submissions.

---

## 🚧 **Future Improvements**
- 🔒 Add encryption to securely transmit credentials.
- 📊 Create a log file to store captured credentials.
- 🔧 Improve the accuracy of deauthentication attacks.

---

## 👨‍💻 **Contributing**

Want to improve this project? Feel free to fork the repository, make changes, and submit a pull request. Contributions are always welcome! 🛠️

---

## 📝 **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details. 📜

---

## ⚠️ **Disclaimer**

This project is intended for **educational and ethical testing purposes** only. **Do not** use this code to target any WiFi network without explicit permission from the network owner. Always comply with local laws and regulations.

---

### 📦 **Repository Tags**
```
ESP32, Evil Twin, WiFi Hacking, Deauthentication, Captive Portal, HTML, CSS, JavaScript, Cybersecurity, Ethical Hacking, ESP32 WiFi, IoT, WiFi Pentesting
```

---




# Alassane Camara : Notes for CSN150

This project demonstrates how I used an ESP32-CAM to create an Evil Twin Wi-Fi access point that clones an existing Wi-Fi network, displays a fake router firmware update page, and captures password attempts. The ESP32-CAM broadcasts a cloned SSID, forces a captive portal, and logs incorrect passwords through the Serial Monitor.

## Equipment Used

* ESP32-CAM (AI Thinker)
* USB-to-ESP32-CAM adapter board (USB-C)
* Laptop running Arduino IDE
* Smartphone (for testing the Evil Twin and captive portal)

## Tools Used

* Arduino IDE 2.3.6
* ESP32 board package
* Web browser (Safari / Chrome)
* Serial Monitor
* GitHub (forked repository)
* ChatGPT (for guidance)

## Steps I Followed

1. Forked the provided Evil Twin repository to my GitHub.
2. Downloaded the ZIP, extracted it, and opened `NetworkDeAuth.ino` in Arduino IDE.
3. Set **Board → ESP32 Arduino → AI Thinker ESP32-CAM**.
4. Connected the ESP32-CAM using a USB-C adapter board.
5. Selected the correct COM port and uploaded the code.
6. After upload, the ESP32-CAM created its default AP: **WiPhi_34732**.
7. Connected my phone to **WiPhi_34732** using password **d347h320**.
8. Opened `http://192.168.4.1` to access the control panel.
9. Scanned nearby Wi-Fi networks and selected **ALICHE02** to clone.
10. Pressed **Start EvilTwin**, which replaced the default AP with the cloned SSID.
11. Connected my phone to the cloned **ALICHE02** network.
12. The ESP32-CAM forced a **captive portal** showing a fake firmware update failure page.
13. Entered a test password to trigger the “Wrong Password” message.
14. Viewed the Serial Monitor showing password attempts and connection logs.

## Problems / Solutions

### Problem 1 — ESP32-CAM showed "BAD" repeatedly in Serial Monitor

* The ESP32-CAM does not support full monitor mode or packet injection.
* **Solution:** Ignore deauthing features. Only use the Evil Twin AP + captive portal.

### Problem 2 — Only one SSID appeared even after cloning

* Phones collapse multiple SSIDs with the *same name* into one entry.
* **Solution:** After starting the Evil Twin, forget the real network and reconnect.

### Problem 3 — Captive portal did not appear automatically

* Phones sometimes connect without triggering a redirect.
* **Solution:** Manually visited `192.168.4.1` to load the fake login page.

## Final Report

In this project, I successfully created an Evil Twin Wi-Fi network using an ESP32-CAM. After flashing the program, the ESP32-CAM broadcasted a cloned SSID and redirected connected devices to a captive portal that mimicked a router firmware recovery page. This portal collected password attempts and displayed responses such as “Wrong Password.” The Serial Monitor logged attempts as expected. Although deauthentication did not work on the ESP32-CAM, the Evil Twin and credential capture features worked correctly, fulfilling the core requirements of the assignment.

## Screenshots

### 1. Scanned Networks + Selected Target SSID

![evil_Twin_ssids](https://github.com/user-attachments/assets/afd70256-37b0-4e43-b26c-d11ab97d91c5)



### 2. Fake Router Firmware Update Page

![Evil_twinAPRM](https://github.com/user-attachments/assets/80999336-6e49-4050-9df7-a39d00a29a26)


### 3. Wrong Password Submission Page

![evil_twin_wrngpass_wrd](https://github.com/user-attachments/assets/a7d15473-305c-45be-a172-e41f2ace63e1)


### 4. Serial Monitor Logs Showing Attempt

<img width="1920" height="1020" alt="eviltwin pic" src="https://github.com/user-attachments/assets/9b028c8b-98f0-406b-8e69-dafebfe2bc43" />


