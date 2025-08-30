![Language](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Platform](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Backend](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

# SkillSeek 📱

SkillSeek is an Android application designed to connect people who **need services** (like plumber, carpenter, painter, cook, etc.) with those who can **offer their skills**.  

It allows users ("hirees") to create profiles, upload their skills, and get discovered by others.  

---

## ✨ Features

- 🔑 **Firebase Authentication** (phone login)
- 👤 **Profile creation** with:
  - Name, Username, Age, Skill
  - Custom skill option ("Write your own")
  - Profile picture upload (Firebase Storage)
- 📸 **Image picker integration** (modern Android `ActivityResultContracts`)
- 🌐 **Internet connectivity checks**
- 📍 **Location permission handling**
- 💾 **Firebase Realtime Database** for storing:
  - Hiree details  
  - Ratings  
  - Service counters
- ✅ Input validation (age checks, required fields)

---

## 📂 Project Structure

app/
├── java/com/helping/skillseek/
│ ├── Hiree_main.java # Main Activity for hiree registration
│ ├── Objects/
│ │ ├── hireeDetails.java
│ │ ├── addCount.java
│ │ └── rateObject.java
│ └── ...
├── res/
│ ├── layout/ # XML layouts
│ ├── drawable/ # Images, icons
│ └── values/ # Colors, strings, styles
└── AndroidManifest.xml


---

## 🚀 Getting Started

### Prerequisites
- Android Studio (latest stable version)
- Firebase project set up with:
  - Firebase Authentication (Phone)
  - Firebase Realtime Database
  - Firebase Storage
- A physical device / emulator with internet

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/shraddhagreddy/SkillSeek.git
   
2.Open the project in Android Studio.
3.Connect your app to Firebase (via Tools > Firebase).
4.Add your google-services.json file under app/.
5.Build & run on an emulator/physical device.


### Future Improvements
1.Add a search & booking system for hiring.
2.Implement user-to-user chat.
3.Add service categories & filtering.
4.Improve UI/UX with Material 3 design.


### Tech Stack
1. Language: Java
2. Framework: Android SDK
3. Backend: Firebase Authentication, Realtime Database, Storage
4. Libraries:
   - CircleImageView for profile pictures
   - Material Components

### Author
Shraddha Reddy  
 [shraddhagreddy@gmail.com](mailto:shraddhagreddy@gmail.com)  
 Always open to collaboration & feedback!



## License
This project is licensed under the [MIT License](LICENSE) © 2025 Shraddha Reddy.

