# نظام حجز الأحداث الذكي
مشروع Django نهائي مع دفع Razorpay، QR codes، ومزامنة التقويم.

## الميزات
- إدارة الأحداث والحجوزات.
- دفع آمن عبر Razorpay.
- إنشاء QR codes للتذاكر.
- مزامنة التقويم (iCal).

## كيفية التشغيل
1. قم بتثبيت المتطلبات: `pip install -r requirements.txt`
2. شغل قاعدة البيانات: `python manage.py migrate`
3. أنشئ مستخدم إداري: `python manage.py createsuperuser`
4. شغل الخادم: `python manage.py runserver`
5. اذهب إلى `http://127.0.0.1:8000`
