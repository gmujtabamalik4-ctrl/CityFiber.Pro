CityFiber Pro Billing — Android Studio Project

اہم:
- یہ پیکج موجودہ HTML فائل کو Android WebView کے اندر چلاتا ہے۔
- یہ تیار شدہ APK نہیں؛ APK بنانے کے لیے Android Studio اور Android SDK درکار ہیں۔
- موجودہ HTML ڈیٹا localStorage میں محفوظ کرتی ہے، اس لیے ڈیٹا اسی فون پر رہے گا۔ مختلف فونز میں خودکار Sync نہیں ہوگا۔
- Secure Super Admin، Cloud Database اور Cloud Backup اس پیکج میں شامل نہیں؛ ان کے لیے Backend integration ضروری ہے۔

APK بنانے کے مراحل:
1. کمپیوٹر پر Android Studio انسٹال کریں۔
2. ZIP Extract کریں اور Android Studio میں اس کا فولڈر Open کریں۔
3. Gradle Sync مکمل کریں؛ ضرورت ہو تو Android SDK Platform 35 انسٹال کریں۔
4. Build > Build Bundle(s) / APK(s) > Build APK(s) منتخب کریں۔
5. APK عموماً app/build/outputs/apk/debug/app-debug.apk میں ہوگی۔
6. APK فون میں منتقل کر کے انسٹال کریں۔

نوٹ: Debug APK ٹیسٹنگ کے لیے ہے۔ Play Store کے لیے release signing اور security/privacy review درکار ہے۔
