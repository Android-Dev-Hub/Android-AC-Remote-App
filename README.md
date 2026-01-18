# Android AC Remote App 📱❄️

A simple Android application to control Air Conditioner using IR Blaster or Smart WiFi module.  
This app works like a real AC remote on your phone.

---
## Features 🚀

- Turn AC ON / OFF  
- Change Temperature  
- Control Fan Speed  
- Change Mode (Cool, Heat, Dry, Fan)  
- Simple and Clean UI  
- Works with IR Blaster phones  
- Can be extended for WiFi AC

---
## Screenshots 📷

Add your app screenshots here.

---
## Requirements 🛠

- Android Studio  
- Minimum Android 5.0  
- Phone with IR Blaster (for IR feature)  
- Kotlin / Java  
- XML Layout

---
## Installation 📥

1. Clone this repository

```bash
git clone https://github.com/yourusername/Android-AC-Remote-App.git
```

## 🧠 How It Works

1. App sends IR signal using phone IR blaster  
2. AC receives same code as real remote  
3. For WiFi AC → commands sent via local network  
4. Each button mapped with HEX IR code  

---

## 🛠 Requirements

- Android Studio  
- Minimum Android 5.0  
- Phone with IR Blaster (for IR feature)  
- Kotlin / Java  
- XML Layout  

---
## 📂 Project Structure

```
app/
 ├── java/
 │   ├── MainActivity
 │   ├── IrManager
 │   ├── WifiManager
 │   └── Models
 ├── res/
 │   ├── layout
 │   ├── drawable
 │   └── values
```
## 🔐 Permissions

```xml
<uses-permission android:name="android.permission.TRANSMIT_IR" />
<uses-permission android:name="android.permission.INTERNET" />
```

---
## 🧪 Usage

- Open App  
- Select AC Brand  
- Press Power ON  
- Set Temperature  
- Change Mode  

---
## ⚙ Future Improvements

- Add WiFi AC support  
- Voice control  
- Auto temperature schedule  
- Multiple AC profiles  
- Google Assistant integration  

---
## 🤝 Contributing

1. Fork the repo  
2. Create new branch  
3. Add features  
4. Submit Pull Request  

---
## 🐞 Troubleshooting

- App not working → Check IR support  
- No response → Select correct brand  
- WiFi issue → Same network required  

---

## ⚠ Disclaimer

This app works only with supported devices.  
Use on your own AC equipment only.

---
