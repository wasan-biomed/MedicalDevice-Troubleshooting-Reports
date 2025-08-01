# تقرير حادث – جهاز الموجات فوق الصوتية (Ultrasound)

- تاريخ الحادث: 12-05-2024  
- اسم الجهاز: جهاز الموجات فوق الصوتية – GE Logiq P5  
- الرقم التسلسلي: US-112780-Z  
- القسم: وحدة السونار – الطابق الثاني

---

## وصف المشكلة

عند تشغيل الجهاز، تعمل الشاشة والإعدادات بشكل طبيعي،  
لكن **لا تظهر أي صورة** على الشاشة أثناء استخدام المسبار (Probe)، وتبقى الشاشة سوداء.

---

## الفحص الأولي

- تم التأكد من أن المسبار متصل بشكل صحيح بمنفذ الجهاز  
- تم تجربة مسبارين مختلفين (Convex وLinear) → نفس المشكلة  
- تم إعادة تشغيل الجهاز عدة مرات → المشكلة مستمرة  
- لا تظهر أي رسائل خطأ على الواجهة

---

## تحليل السبب الجذري (Root Cause Analysis)

باستخدام أدوات الصيانة، تبيّن أن **وحدة توليد الإشارة (Beamformer Board)** لا تُخرج أي نبضات إلى المجسات.  
تم اكتشاف **خلل في دائرة التشغيل** الداخلية، مع ملاحظة ارتفاع درجة حرارة في اللوحة،  
ما يدل على **عطل في مكونات الطاقة**، تحديدًا في أحد المكثفات.

---

## الإجراء التصحيحي المتخذ (Fix Applied)

- تم فتح الغطاء الخلفي للجهاز وفحص وحدة Beamformer  
- تم استبدال **مكثف محترق (100μF / 25V)** على اللوحة الرئيسية  
- تم تنظيف موقع التلف وإعادة اللحام بدقة  
- بعد التركيب، تم تنفيذ اختبار ذاتي (Self-Test) → النتيجة ناجحة  
- تم اختبار الجهاز باستخدام Phantom → الصورة طبيعية

---

## الإجراء الوقائي (Preventive Action)

- إدخال وحدة Beamformer ضمن **جدول فحص حراري دوري**  
- التوصية بتشغيل الجهاز في بيئة جيدة التهوية، مع إضافة تبريد عند الاستخدام المكثف  
- تقديم طلب لتوفير **لوحة Beamformer احتياطية** ضمن مخزون الصيانة

---

## المهندس المسؤول

- الاسم: وسن قصي حسن  
- اعتماد المشرف: [توقيع]  
- موعد الصيانة القادم: 12-06-2024
