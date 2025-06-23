Step 1: Install Prerequisites

npm install -g @ionic/cli

Step 2: Create an Ionic App

ionic start calculator-app blank --type=angular
cd calculator-app

choose standalone

Step 3: Replace Default UI with Your Calculator

<ion-content>
  <!-- Paste your calculator HTML content here inside the <ion-content> -->
</ion-content>
Then move your CSS into home.page.scss and JS into home.page.ts

 Step 4: Add Capacitor and Build for Native

 ionic build
npx cap init calculator com.yourdomain.calculator

 Step 5: Open in Native IDE and Run
 
npx cap add android
# or for iOS (on macOS only)
npx cap add ios

 Want to Deploy as PWA Too?
 
ionic build --prod

