# دفاع الدبابات — نسخة أندرويد

## الطريقة 1: تشغيل فوري (بدون APK)
1. ارفع مجلد `www` على أي استضافة HTTPS (GitHub Pages / Netlify).
2. افتح الرابط في Chrome على الأندرويد ← ⋮ ← «تثبيت التطبيق».
   يعمل بملء الشاشة وبدون إنترنت.

## الطريقة 2: ملف APK
```
npm install
npm run android      # يفتح Android Studio
```
ثم Build ← Build APK(s). يتطلب Node.js و Android Studio.

## تشغيل محلي للتجربة
افتح `www/index.html` مباشرة في Chrome.
