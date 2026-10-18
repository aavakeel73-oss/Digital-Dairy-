Chronicle Diary Android project

यह Android Studio/AndroidIDE में खोलने के लिए तैयार WebView project है। इसमें आपकी index.html शामिल है।

मोबाइल पर APK बनाने के चरण:
1. AndroidIDE या Android Studio में इस ZIP को extract करें और ChronicleAndroid folder खोलें।
2. Gradle sync पूरा होने दें (पहली बार इंटरनेट चाहिए; Android SDK और Gradle डाउनलोड होंगे)।
3. Build > Build APK(s) चुनें।
4. APK सामान्यतः app/build/outputs/apk/debug/app-debug.apk में बनेगी।

ध्यान दें:
- इस वातावरण में Android SDK/Gradle उपलब्ध नहीं है, इसलिए यहाँ compiled APK नहीं बनाई गई; यह source project है।
- Google Login/Firebase सुविधाओं के लिए Firebase Console में सही Android app/package configuration और authorized domains की जाँच आवश्यक हो सकती है।
- HTML में बाहरी CDN/Firebase scripts हैं, इसलिए इन सुविधाओं के लिए इंटरनेट चाहिए।
- WebView में ब्राउज़र जैसी background notification/alarms की गारंटी नहीं है; ऐप बंद होने पर reminder बजना सुनिश्चित नहीं है।
