# Mobile-App-Login-SignUp-Page (Android Login Screen UI)
 
A modern, responsive, and clean Login / Sign-Up screen UI for Android, built in **Android Studio** using **Java** and **XML**. The project follows Google's **Material Design** guidelines to deliver a smooth user experience.
 
## Features
 
| Feature | Description |
|---------|-------------|
| **Material Design Inputs** | `TextInputLayout` + `TextInputEditText` with floating hints and focused states |
| **Password Toggle** | Built-in end icon (`password_toggle`) to show/hide the password |
| **Social Login Layout** | Circular `CardView` buttons for Google and Facebook login |
| **Responsive Layout** | `RelativeLayout` keeps alignment consistent across screen sizes |
| **Clean UI** | Custom elevation, rounded corners, and proper spacing |
 
## Concepts Demonstrated
 
- Building forms with Material `TextInputLayout` and `TextInputEditText`.
- Password visibility toggle using `app:endIconMode="password_toggle"`.
- Circular image buttons using `CardView` and `CircleImageView`.
- Handling user input in Java and moving between screens after entering credentials.
- Using drawable resources (icons and background wallpaper).
## Project Structure
 
```

java/
  ├── MainActivityTask3.java   # Activity logic for the screen
  └── Task.java                # Activity logic for the screen
layout/
  ├── activity_task.xml        # Login / Sign-Up screen layout
  └── activity_task2.xml       # Second screen layout (shown after entering credentials)
drawable/
  ├── facebook.png             # Facebook login icon
  ├── google.png               # Google login icon
  └── wallpaper.png            # Background wallpaper
```
 
## How It Works
 
1. The app opens on the login screen, which shows the email and password fields along with the Google and Facebook buttons.
2. The user types their credentials; the password can be shown or hidden with the eye icon.
3. After the credentials are entered, the app shows the next screen (see the screenshots below).

## Preview

| Login Screen UI |
| :---: |
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/88e864a4-df6d-4d2e-b91f-269758a71023" />
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/b7998512-0546-48b6-99b0-c9761e93d7ea" />



## After entering credentials:

<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/51ed7142-d459-4e9d-99d6-2de23aadd5c8" />
<img width="702" height="1600" alt="image" src="https://github.com/user-attachments/assets/50a34383-8600-40ca-9243-9b86022b0124" />


---

## Tech Stack & Dependencies
 
- **Language:** Java / XML
- **IDE:** Android Studio
- **UI Components:**
  - [Google Material Components](https://github.com/material-components/material-components-android)
  - `androidx.cardview.widget.CardView`
  - `de.hdodenhof.circleimageview.CircleImageView`
## Requirements
 
- Android Studio (latest stable version recommended)
- Android SDK with an emulator or physical device (API 21+, adjust to your `minSdk`)
- Java 8+
## Getting Started
 
1. Clone the repository:
```bash
   git clone https://github.com/Alveeza-Ilyas/Mobile-App-Login-SignUp-Page.git
```
2. Open **Android Studio**.
3. Select **Open an Existing Project** and choose the cloned folder.
4. Wait for the Gradle sync to finish.
5. Press **Run** (`Shift + F10`) on an emulator or physical device.
## Author
 
**Alveeza Ilyas**
 
