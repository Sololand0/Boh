# بوّح - منصة الاعترافات المجهولة

## كيف تشغل المشروع

1. تحتاج إلى Node.js مثبت على جهازك.
2. افتح الطرفية (Terminal) وادخل إلى مجلد المشروع.
3. شغل الأمر لتثبيت الحزم:
   ```bash
   npm install
   ```
4. شغل السيرفر:
   ```bash
   npm start
   ```
5. افتح ملف `frontend/index.html` في متصفحك لواجهة المستخدم.
6. افتح ملف `admin/admin.html` في متصفحك للوحة الأدمين.

## تعديل رابط API

- في ملفات `frontend/index.html` و `admin/admin.html`، عدل قيمة `API_URL` إلى عنوان السيرفر الخاص بك.
- مثلاً:  
  ```js
  const API_URL = 'http://localhost:5000';
  ```
  أو  
  ```js
  const API_URL = 'https://your-app.herokuapp.com';
  ```

## نشر على Heroku (مثال)

راجع الشرح في المحادثة لكيفية رفع المشروع على Heroku.

