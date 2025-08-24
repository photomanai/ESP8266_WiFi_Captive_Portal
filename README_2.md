# ESP8266 WiFi Captive Portal - Educational Project

## ⚠️ IMPORTANT WARNING

**This project is prepared ONLY for educational and teaching purposes. Malicious use in real environments is strictly prohibited!**

## 📚 About The Project

This project is developed to learn how captive portal systems work using the ESP8266 microcontroller. It aims to help students gain experience in network security, web technologies, and IoT devices through hands-on learning.

## 🎯 Learning Objectives

- Understanding ESP8266 WiFi capabilities
- Comprehending captive portal technology
- Learning DNS spoofing concepts
- Web server programming
- HTML/CSS form handling
- File system (LittleFS) usage
- Network security awareness

## 🔧 Technical Features

- **Platform**: ESP8266
- **Web Server**: ESP8266WebServer
- **DNS Server**: DNSServer library
- **File System**: LittleFS
- **Interface**: Modern HTML/CSS design
- **Data Storage**: Local file system

## 📋 Requirements

### Hardware
- ESP8266 development board (NodeMCU, Wemos D1 Mini, etc.)
- USB cable
- Computer

### Software
- Arduino IDE
- ESP8266 Arduino Core
- Required libraries:
  - ESP8266WiFi
  - DNSServer
  - ESP8266WebServer
  - LittleFS

## 🚀 Installation

1. **Prepare Arduino IDE**
   - Install ESP8266 board package
   - Add required libraries

2. **Download the code**
   ```bash
   git clone https://github.com/photomanai/ESP8266_WiFi_Captive_Portal
   ```

3. **Upload to ESP8266**
   - Open code in Arduino IDE
   - Select correct board and port
   - Compile and upload

## 💡 How It Works

1. ESP8266 creates an Access Point named "Free WiFi"
2. When users connect to this network, a captive portal page opens
3. When user enters credentials, the system saves them to LittleFS
4. For educational purposes, LED blinks and data is stored

## 🔍 Educational Content

### Security Topics
- How captive portal attacks work
- Risks of connecting to unsecured networks
- Technical details of phishing attacks
- Social engineering techniques

### Technical Concepts
- DNS spoofing mechanism
- HTTP server programming
- Access Point creation
- Embedded web interface design

## ⚖️ Legal Notice and Disclaimer

### 🚫 DISCLAIMER OF LIABILITY

This code and project:

- Is prepared **ONLY FOR EDUCATIONAL PURPOSES**
- Is developed to create awareness about network security
- **Malicious use in real environments is PROHIBITED**
- **Should NOT be used to steal others' data**
- Is intended for controlled learning environments only

### 📝 USER RESPONSIBILITIES

Persons using this code:
- Must comply with local laws and regulations
- Should only use in their own test environments
- Must not test on others' networks without permission
- Should not use obtained information for malicious purposes
- Are responsible for ensuring ethical use

### 🛡️ DEVELOPER RESPONSIBILITY

**As the developer:**
- I am **NOT RESPONSIBLE** for malicious use of this code
- I am **NOT LIABLE** for any damage, legal issues, or consequences arising from misuse of this educational project
- Users are entirely responsible for how they use this code
- I developed this project solely for learning and teaching purposes
- Any use beyond educational scope is at the user's own risk and responsibility

## 🎓 Educational Use

### Recommended Use Cases:
- University network security courses
- Cybersecurity training programs
- IoT security workshops
- Ethical hacking courses
- Technical high school electronics classes
- Security awareness training

### Laboratory Environment:
- Use in isolated test networks
- Do not test with real user data
- Emphasize security awareness to students
- Obtain proper permissions before any testing

## 🔒 Ethical Guidelines

### DO:
- Use in controlled educational environments
- Teach security awareness
- Demonstrate attack vectors for defense
- Obtain explicit permission before testing
- Follow responsible disclosure practices

### DON'T:
- Use against real users without consent
- Deploy in public networks
- Harvest actual credentials
- Use for financial gain
- Ignore local laws and regulations

## 🤝 Contributing

To improve educational content:
1. Fork the repository
2. Add educational materials
3. Enhance security explanations
4. Submit pull requests
5. Focus on educational value

## 📚 Resources

- [ESP8266 Arduino Core Documentation](https://arduino-esp8266.readthedocs.io/)
- [Network Security Fundamentals](https://www.sans.org/)
- [Captive Portal Security](https://owasp.org/)
- [Ethical Hacking Guidelines](https://www.eccouncil.org/)

## 🛠️ Code Structure

```
├── ESP8266_Captive_Portal.ino    # Main Arduino sketch
├── README.md                     # This file
├── LICENSE                       # License file

```

## 🔍 Security Analysis (Educational)

This project demonstrates:
- **DNS Spoofing**: How malicious actors redirect DNS queries
- **Evil Twin Attacks**: Creating fake access points
- **Credential Harvesting**: Collecting user input through fake forms
- **Social Engineering**: Using familiar interfaces to deceive users


---

## ⚠️ FINAL REMINDER

**This project is strictly for educational purposes. The author disclaims all responsibility for any misuse. Users must:**

- ✅ Use only in authorized test environments
- ✅ Obtain explicit permission before testing
- ✅ Comply with all applicable laws
- ✅ Use for learning and teaching only
- ❌ Never use against real users without consent
- ❌ Never use for malicious purposes
- ❌ Never deploy in production environments

**By using this code, you acknowledge that you have read, understood, and agree to these terms and take full responsibility for your actions.**
