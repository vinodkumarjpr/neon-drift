NEON DRIFT - APK BANANE KE STEPS

Pehle install karo: Node.js (v18+), Android Studio, JDK 17

1) Terminal is folder mein kholo, phir:
     npm install
     npx cap add android
     npx cap sync android

2) Android Studio kholo:
     npx cap open android
   Gradle sync khatam hone do.

3) APK banao:
     Build > Build Bundle(s) / APK(s) > Build APK(s)
   APK yahan milega:
     android/app/build/outputs/apk/debug/app-debug.apk

4) Apne phone mein APK bhejo aur install karo
   (Settings mein "Install unknown apps" allow karna padega).

Play Store ke liye: appId (com.example.neondrift) apna unique naam karo
aur Build > Generate Signed Bundle se signed AAB banao.
Game badalna ho to www/index.html edit karo, phir: npx cap sync android
