# IdentiFruit App
**A smart, AI-powered mobile application designed to identify fruits instantly from your camera.**


## Key Features
- **Real-time Fruit Recognition**: Point your camera at any fruit, and the AI model will identify it instantly.
- **High Accuracy AI Model**: Powered by a custom-trained machine learning model for accurate classification.
- **Offline Mode**: Identify fruits even without an internet connection using on-device processing.
- **User-Friendly Interface**: Clean, intuitive, and responsive design for seamless navigation.

## 🛠️ Tech Stack
### Frontend
![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) 
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white) 
![XML](https://img.shields.io/badge/XML-00599C?style=for-the-badge&logo=xml&logoColor=white)

### AI / Machine Learning
![TensorFlow Lite](https://img.shields.io/badge/TensorFlow_Lite-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white) 
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) 
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) 

### Tools & DevOps
![Android Studio](https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## Prerequisites
Ensure you have the following installed on your local machine:
- **Android Studio** (Flamingo or later recommended)
- **Java Development Kit (JDK)** 17 or higher
- An Android device or Emulator (running API level 24+)

## Installation
Follow these steps to get the project up and running locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/IdentiFruit-App.git
   ```
2. **Open the project:**
   Launch Android Studio, select "Open an existing project", and choose the `IdentiFruit-App` directory.
3. **Sync Gradle dependencies:**
   Wait for Android Studio to index the project and sync all required Gradle files.

## 💻 Scripts/Commands
Since this is an Android project, we use Gradle wrapper commands:

| Command | Description |
|---------|-------------|
| `./gradlew assembleDebug` | Build the debug APK |
| `./gradlew installDebug` | Install the debug APK on a connected device |
| `./gradlew test` | Run local unit tests |
| `./gradlew lint` | Run code quality checks |

## 📁 Project Structure
```text
IdentiFruit-App/
├── app/                     # Main application module
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/        # Java source code (Activities, Fragments, Models)
│   │   │   ├── res/         # Resources (Layouts, Drawables, Values)
│   │   │   ├── assets/      # TFLite AI models and labels
│   │   │   └── AndroidManifest.xml # App configuration
│   ├── build.gradle.kts     # App-level Gradle configuration
├── gradle/                  # Gradle wrapper files
├── build.gradle.kts         # Project-level Gradle configuration
├── settings.gradle.kts      # Project settings and module configurations
└── README.md                # Project documentation
```

## 📄 License
This project is licensed under the [MIT License](LICENSE).

---

## 👥 Our Team
<div style="font-family: Arial, sans-serif; line-height: 1.6;">
  <p><strong>Xymond Louisse Alcazar</strong> - Developer</p>
  <p><strong>Jon Delvic Calub</strong> - Frontend Developer</p>
  <p><strong>Renz Dadpaas</strong> - Developer</p>
  <p><strong>Carl Espartinas</strong> - Developer</p>
  <p><strong>Edison Malasan</strong> - AI Model Developer</p>
  <p><strong>Jhorone Roxas</strong> - Developer</p>
</div>
