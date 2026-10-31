# Master Q&Z — تطبيق قابل للتنصيب (PWA)

## 1) نشر التطبيق فـ GitHub Pages (مرة وحدة)
1. دخل لـ github.com ← **New repository** ← سميه مثلا `master-quz` ← **Public** ← Create.
2. **Add file ← Upload files** ← جر جميع الملفات اللي فهاد الدوسي (`index.html`, `manifest.webmanifest`, `sw.js` والدوسي `icons`) ← **Commit changes**.
3. **Settings ← Pages** ← Source: *Deploy from a branch* ← Branch: `main` / `(root)` ← Save.
4. من بعد دقيقة ولا جوج، التطبيق غادي يكون فـ:
   `https://mohamedrezzoug.github.io/master-quz/`

## 2) التنصيب فالحاسوب (Windows / Mac)
- حل الرابط فـ **Chrome** ولا **Edge**.
- ضغط على زر **📲 App installieren** فالصفحة الرئيسية، ولا على أيقونة ⊕ فشريط العنوان ← **Installer**.
- غادي تبان أيقونة فسطح المكتب وفقائمة البرامج، وكيتحل فنافذة ديالو بحال أي برنامج.

## 3) التنصيب فالتليفون
- **Android (Chrome):** حل الرابط ← ⋮ ← **Installer l'application / Zum Startbildschirm hinzufügen**.
- **iPhone (Safari):** حل الرابط ← زر المشاركة ⬆️ ← **Sur l'écran d'accueil / Zum Home-Bildschirm**.

## ملاحظات
- كيخدم **بلا إنترنت** من بعد أول مرة (تحميل PDF أول مرة خاصو الإنترنت).
- **البحث بالصوت 🎤** كيخدم فهاد النسخة (Chrome / Edge / Android).
- البيانات (التقدم، الأخطاء، الملفات…) كتبقى محفوظة فالجهاز. باش تنقلها من جهاز لآخر: **Plan & ECTS ← Sicherung ← Daten kopieren** ومن بعد **Wiederherstellen** فالجهاز الآخر.
- لتحديث التطبيق: بدل `index.html` فـ GitHub بالنسخة الجديدة، والتطبيق كيتحدث بوحدو.
- الـ repository خاصو يكون **Public** باش GitHub Pages يخدم مجانا، يعني أي واحد عندو الرابط يقدر يشوف المحتوى (ما فيه حتى معلومة شخصية، غير جدول الحصص).

## 4) تحويله لملف APK (أندرويد)
1. خاص التطبيق يكون منشور فـ GitHub Pages (الخطوة 1).
2. دخل لـ **https://www.pwabuilder.com** ← لصق الرابط `https://mohamedrezzoug.github.io/master-quz/` ← **Start**.
3. ضغط **Package For Stores** ← **Android** ← **Generate Package**.
4. كيعطيك ملف zip فيه **APK** (للتنصيب المباشر) و **AAB** (لـ Google Play) و **signing key**.
   - احتافظ بملف المفتاح (signing.keystore + كلمة السر) فبلاصة آمنة: خاصك بيه باش تدير أي تحديث من بعد.
5. صيفط الـ APK للتليفون ← حلّو ← اقبل «تثبيت من مصادر غير معروفة» ← تنصيب.

## 5) الآيفون (iPhone / iPad)
- ما كاينش APK فالآيفون. الطريقة هي: حل الرابط فـ **Safari** ← زر المشاركة ⬆️ ← **Sur l'écran d'accueil / Zum Home-Bildschirm** ← Ajouter.
- كتبان أيقونة Master Q&Z فالشاشة، وكيتحل فشاشة كاملة بلا شريط Safari، وكيخدم بلا إنترنت.
- التطبيق كيبين رسالة صغيرة فالآيفون كتشرح هاد الخطوة.
- باش يكون فـ App Store: خاص Mac + Xcode + حساب Apple Developer (99$ فالعام). PWABuilder كيعطي مشروع iOS جاهز ولكن خاصو يتبنى فـ Mac.
