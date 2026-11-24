SmartPay Android APK Project

এই প্রজেক্টটি একটি Android WebView অ্যাপ। এটি আপনার Render ওয়েবসাইটের সঙ্গে যুক্ত:
https://smartpay-hnf8.onrender.com/

APK তৈরি করার সহজ পদ্ধতি (GitHub দিয়ে):
1. এই ZIP Extract করুন।
2. GitHub-এ নতুন repository তৈরি করুন (যেমন SmartPay-Android)।
3. ZIP-এর ভেতরের সব ফাইল repository-তে Upload করুন। .github ফোল্ডারটিও Upload করতে হবে।
4. GitHub repository-তে Actions tab খুলুন।
5. Build SmartPay APK workflow নির্বাচন করে Run workflow চাপুন।
6. Build শেষ হলে নিচের Artifacts থেকে SmartPay-APK Download করুন।
7. ZIP extract করলে app-debug.apk পাবেন। Android ফোনে Install করুন।

নোট:
- প্রথমবার APK install করার সময় Android-এ "Install unknown apps" অনুমতি দিতে হতে পারে।
- অ্যাপ চালাতে ইন্টারনেট প্রয়োজন।
- এটি আপনার বর্তমান ওয়েবসাইটকে APK-এর মধ্যে দেখায়; ওয়েবসাইটের সার্ভার/ডেটাবেস পরিবর্তন করে না।
- এটি Debug APK; Play Store প্রকাশের জন্য আলাদা signed release build দরকার।

অ্যাপ আইকন:
- SmartPay-এর নতুন নীল, সাদা ও হলুদ ব্র্যান্ড আইকন যুক্ত করা হয়েছে।
- Android launcher icon-এর জন্য mdpi থেকে xxxhdpi পর্যন্ত প্রয়োজনীয় PNG সাইজ রাখা হয়েছে।
- মূল উচ্চ-রেজোলিউশনের আইকন assets/SmartPay_App_Icon.png ফাইলে আছে।
