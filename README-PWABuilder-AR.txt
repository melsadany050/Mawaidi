# مواعيدي — حزمة PWA جديدة بأيقونات مختلفة

## محتويات الحزمة
- ملفات جذر المستودع: `index.html` و`manifest.json` و`service-worker.js` ومجلد `icons/`.
- مجلد `www/` يحتوي نسخة النشر نفسها.
- أيقونات جديدة كليًا بألوان أزرق/بنفسجي مع تقويم وساعة وعلامة إنجاز، بالمقاسات 192 و512 ونسخة maskable.
- ملف `mawaidi-new-icon-1024.png` للأيقونة الأصلية عالية الدقة.

## طريقة رفعها إلى GitHub Pages
1. افتح مستودع `Mawaidi` على GitHub.
2. ارفع محتويات هذا المجلد إلى جذر المستودع (وليس المجلد الأب).
3. وافق على استبدال `index.html` والملفات السابقة، وأضف/استبدل مجلد `icons`.
4. انتظر انتهاء GitHub Pages deployment.
5. تحقق من الروابط: `https://melsadany050.github.io/Mawaidi/manifest.json` و`https://melsadany050.github.io/Mawaidi/service-worker.js` و`https://melsadany050.github.io/Mawaidi/icons/icon-512.png`.
6. افتح https://www.pwabuilder.com/ وأدخل `https://melsadany050.github.io/Mawaidi/` ثم راجع الفحص واختر Android لإنتاج الحزمة.

## ملاحظات مهمة
- تم الحفاظ على كود التطبيق الأصلي داخل `index.html`، مع إضافة تهيئة PWA فقط وتحديث الأيقونات.
- التخزين المحلي في التطبيق يظل على الجهاز نفسه ولا يزامن المواعيد تلقائيًا بين الهواتف.
- التخزين المؤقت يوفر App Shell للعمل بعد أول زيارة ناجحة؛ لا يعني ذلك أن كل موارد الإنترنت الخارجية متاحة دون اتصال.
- لا يحتوي هذا الملف على APK جاهز؛ PWABuilder ينشئ حزمة Android بعد نشر الموقع وفحصه.
