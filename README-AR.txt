رفيق الحافظ - مشروع Android Studio

طريقة فتح المشروع:
1. فك ضغط ملف ZIP كاملًا.
2. افتح Android Studio.
3. اختر Open.
4. اختر المجلد RafiqAlHafiz (المجلد الذي يحتوي على settings.gradle).
5. انتظر Gradle Sync حتى ينتهي.
6. من القائمة Build اختر Build Bundle(s) / APK(s) ثم Build APK(s).
7. بعد انتهاء البناء اضغط Locate من إشعار Android Studio للعثور على ملف APK.

ملاحظات:
- التطبيق الحالي يغلّف واجهة HTML داخل Android WebView.
- ملف الواجهة موجود في app/src/main/assets/index.html.
- البيانات التجريبية تُحفظ محليًا داخل WebView على الجهاز.
- هذه نسخة أولية للعرض والتجربة، وليست نظامًا سحابيًا حقيقيًا.
- أول مزامنة في Android Studio قد تحتاج إنترنت لتنزيل Gradle ومكونات Android SDK.
- لا يوجد اتصال حالي بقاعدة بيانات Supabase أو تسجيل دخول آمن حقيقي.
