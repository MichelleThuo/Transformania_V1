Transformania_V1
-----------------------------------------------------------

Transformania is an Android application that utilizes Firebase ML Kit to translate text in real-time between multiple languages.

### Prerequisites

*   Android Studio (Latest Version) - [https://developer.android.com/studio/intro](https://developer.android.com/studio/intro)
    
*   An active Google Cloud Platform (GCP) project with Firebase enabled - [https://console.firebase.google.com/](https://console.firebase.google.com/)
    

### Setting Up the Project

1.  **Clone the Repository:**
    
    *   Open a terminal window and navigate to your desired project directory.
        
    *   git clone https://.git Use code [with caution.](/faq#coding)content\_copy
        
2.  **Download Dependencies:**
    
    *   Open the project in Android Studio.
        
    *   Wait for Gradle to sync the project dependencies.
        
    *   If prompted, click "Download missing dependencies" to download any required libraries.
        
3.  **Configure Firebase:**
    
    *   In the Firebase console ([https://console.firebase.google.com/](https://console.firebase.google.com/)), navigate to your project settings.
        
    *   Go to the "Project settings" section and enable the "Firebase ML Kit" service.
        
    *   Create a new Android app within your project and download the google-services.json file.
        
    *   Copy the downloaded google-services.json file to the app module folder within your project (usually located at app/google-services.json).
        

### Running the App

1.  **Connect an Android Device or Launch Emulator:**
    
    *   Ensure you have a physical Android device connected with developer options enabled, or launch an Android emulator within Android Studio.
        
2.  **Run the App:**
    
    *   Click the green "Run" button (play triangle icon) on the Android Studio toolbar.
        
    *   Select your connected device or emulator as the deployment target.
        
    *   The app will be compiled and installed on the chosen target. Once the installation is complete, the app will launch.
        

### Additional Notes

*   This project utilizes Firebase ML Kit for language translation. Ensure you have a valid Firebase project set up and configured as mentioned above.
    
