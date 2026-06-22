> **ملاحظة:** الكود مغلق المصدر، تم نشر فيديو للمشروع، ويمكن التعرف على مكوناته من خلال الوصف أدناه.
> 
> **ملاحظة 2:** ملف README.md مكتوب بالإنجليزية أولاً ثم بالعربية، يمكنك قراءة النسخة العربية في الأسفل.
> 
> **ملاحظة 3:** قالب المشروع متاح للبيع حاليا و يمكن تعديل عليه في حالة طلب ذلك.

---


**Note:** The code is closed source. A video of the project has been published, and its components can be found in the description below.

**Note 2:** The README.md file is written in English first, then in Arabic. You can read the Arabic version below.

**Note 3:** The project template is currently available for purchase and can be modified upon request.

---



https://github.com/user-attachments/assets/06f18f14-f1bd-4feb-b1b1-2485762c7b56





### بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ

This report covers:

* Project overview
* Key features
* Implementation methods
* Security
* Contacting me

---

### Project Overview

I built a women's clothing store website using:
- HTML, CSS, JavaScript
- Raw PHP (no framework)
- MariaDB as the database

---
### Key Features

The project consists of two parts:

**Part One — Customer Interface:**
- Homepage
- Products page with category filters and search, with the ability to add items directly to the cart
- Shopping cart
- Order completion window and delivery information entry

> Cash on delivery only, making the ordering process simple and fast..

https://github.com/user-attachments/assets/e8a326db-d8e1-498c-887a-3282e1652f4d

**Part Two — Admin Panel:**
This is not visible to the average customer and includes:
- Login page
- Main control panel interface
- Order management page
- Product addition and management page
- Settings page with the ability to temporarily close the site (not shown in the video)
- Account management: Change password and email address, and add new admin accounts. This feature is exclusive to Super Admins (not shown in the video).

https://github.com/user-attachments/assets/475b0808-632d-4774-af1a-a7e974c3c875

---
### Implementation Methods

- Designing a Use Case Diagram to identify system stakeholders (see illustration)
- Designing a Class Diagram and building the database accordingly
  <img width="1920" height="890" alt="Screenshot From 2026-06-22 23-04-27" src="https://github.com/user-attachments/assets/f352d939-3e1e-4bf7-b231-5a9a66236863" />

- Designing interfaces using Figma, starting with wireframes before any software application (see illustration)
  <img width="1912" height="931" alt="Screenshot From 2026-06-22 23-26-18" src="https://github.com/user-attachments/assets/2caa91be-73df-45cf-9710-ad1f9c451217" />
  <img width="1920" height="931" alt="image" src="https://github.com/user-attachments/assets/3c14db49-a0df-4c5a-8c83-e5294fc11e4a" />


- Building the system on the MVC architecture.

---

### Security

- Protection against CSRF attacks
- Protection against XSS and SQL Injection
- A RBAC (Super Admin/Admin) permissions system with permissions limited as much as possible
- Limiting a maximum of 3 requests per 10 minutes (to reduce random requests)

---

- [LinkedIn](https://www.linkedin.com/in/douaa-benchidi-784604411/)
- [Facebook](https://www.facebook.com/unknown.928707)
- [GitHub](https://github.com/db-douae)

---
---

**الترجمة الكاملة باللغة عربية :**

### بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ

**يتناول هذا التقرير:**
*  تعريف بالمشروع
*  الميزات الرئيسية
*  أساليب التنفيذ
*  الأمان
*  وسائل التواصل معي

---

### تعريف بالمشروع

قمت ببناء موقع ويب لبيع الملابس النسائية باستخدام:
- HTML، CSS، JavaScript
- PHP خام (بدون أي إطار عمل)
- MariaDB كقاعدة بيانات

---

### الميزات الرئيسية

يتكون المشروع من جزأين:

**الجزء الأول — واجهة العميل:**
- الصفحة الرئيسية
- صفحة المنتجات مع فلتر الفئات والبحث، مع إمكانية الإضافة المباشرة إلى السلة
- سلة المشتريات
- نافذة إتمام الطلب وإدخال معلومات التوصيل

> الدفع عند الاستلام فقط، مما يجعل عملية الطلب بسيطة وسريعة.

**الجزء الثاني — لوحة التحكم (Admin Panel):**
لا تظهر للمشتري العادي، وتحتوي على:
- صفحة تسجيل الدخول
- واجهة لوحة تحكم رئيسية 
- صفحة إدارة الطلبات
- صفحة إضافة المنتجات وإدارتها
- صفحة الإعدادات مع إمكانية إغلاق الموقع مؤقتاً (لم تعرض في الفيديو)
- إدارة الحسابات: تغيير كلمة المرور والبريد الإلكتروني، وإضافة حسابات admin جديدة، هذه الميزة حكر على الـ Super Admin (لم تُعرض في الفيديو)

---

### أساليب التنفيذ

- تصميم مخطط **Use Case** لتحديد الفاعلين في النظام 
*(صورة توضيحية)*
- تصميم **مخطط الكلاسات** وبناء قاعدة البيانات بناءً عليه 
- تصميم الواجهات على **Figma** بدءاً من الـ Wireframes قبل أي تطبيق برمجي
*(صورة توضيحية)*
- بناء النظام على معمارية **MVC**

---

### الأمان

- حماية من هجمات **CSRF**
- حماية من **XSS** و **SQL Injection**
- نظام صلاحيات **RBAC** (Super Admin / Admin) مع تقليص الصلاحيات قدر الإمكان
_ تحديد 3 طلبات على اكثر خلال 10 دقائق (لتقليل طلبات عشوائية)


---
ملاحظات اضافية:
- قالب المشروع متاح للبيع حاليا و يمكن تعديل عليه في حالة طلب ذلك.

### تواصل معي

- [LinkedIn](https://www.linkedin.com/in/douaa-benchidi-784604411/)
- [Facebook](https://www.facebook.com/unknown.928707)
- [GitHub](https://github.com/db-douae)

---
---



