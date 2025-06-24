# SukoonAI Android App

A native Android application that provides a seamless experience for accessing the [SukoonAI mental health platform](https://sukoon-ai.vercel.app). This app wraps the SukoonAI web application in a native Android container using WebView, providing a more app-like experience while maintaining all the functionality of the web platform.

---

## 📱 Screenshots

> _Add your screenshots here_

---

## 🚀 Features

- Native Android WebView implementation
- Seamless integration with SukoonAI web platform
- Full-screen immersive experience
- Zoom capabilities for better readability
- Offline caching support (if supported by the website)
- Prevents standard browser refresh behavior

---

## 🛠️ How it Works

- The app uses a single `WebView` to load the SukoonAI website.
- JavaScript and DOM storage are enabled for full web functionality.
- The app requests only Internet permissions.
- The WebView is set to fill the entire screen for a native feel.

---

## 🏁 Getting Started

### Prerequisites
- Android Studio (latest recommended)
- Android device or emulator (API 24+)
- Internet connection

### Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/sakshambhatt2005/sukoon-ai-android.git
   ```
2. **Open in Android Studio:**
   - Open Android Studio
   - Select `Open an existing project` and choose this folder
3. **Build and Run:**
   - Connect your Android device or start an emulator
   - Click the Run button

---

## 📂 Project Structure

- `MainActivity.kt`: Main entry point, sets up the WebView
- `activity_main.xml`: Layout containing the WebView
- `AndroidManifest.xml`: Permissions and app configuration

---

## 🔒 Permissions

- `INTERNET`: Required to load web content from SukoonAI

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
- Fork the repo
- Create your feature branch (`git checkout -b feature/AmazingFeature`)
- Commit your changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

**Saksham Bhatt**  
Email: saksham.11214812723@cst.mait.ac.in  
GitHub: [sakshambhatt2005](https://github.com/sakshambhatt2005)

---

_This project is not affiliated with SukoonAI. It is an open-source wrapper for convenience._ 