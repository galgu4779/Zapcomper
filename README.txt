ZapCompare Android App (WebView scraper)
--------------------------------------

THIS IS A MINIMAL AND UNOFFICIAL PROJECT SCAFFOLD.
It uses a WebView to load zap.co.il pages and injects javascript to extract offers.
Because scraping websites may violate Terms of Service, use responsibly.

How to build:
1. Install Android Studio on your computer (Windows/Mac/Linux).
2. Open the project (folder ZapCompareApp) in Android Studio.
3. Let Gradle sync. You may need to install an Android SDK (API 33).
4. Connect an Android device (or use emulator) and run the app, or Build -> Build Bundle(s) / APK(s) -> Build APK(s).
5. The generated APK will be available via Android Studio (or app/build/outputs/apk).

Notes:
- The app relies on WebView rendering, so it runs JavaScript and extracts data in the phone itself.
- If zap.co.il changes their structure, the JS extractors may need tweaking.
- For production use, add error handling, progress UI, better parsing, and respect robots.txt and ToS.
