

لوحة التحكم الرئيسية
## 📖 نظرة (Overview)
هذا المشروع عبارة عن لوحة تحكم تفاعلية (Dashboard) تم إنشاؤها باستخدام **Power BI** لتحليل بيانات مبيعات مطعم بيتزا. تهدف اللوحة إلى تزويد إدارة المطعم برؤى واضحة حول أداء المبيعات، مما يساعد في اتخاذ قرارات استراتيجية لتحسين العمليات وزيادة الأرباح.

**القيمة المضافة من اللوحة:**
- فهم تفضيلات العملاء من حيث أنواع البيتزا الأكثر طلبًا.
- تحديد أوقات الذروة لتحسين توزيع الموظفين وإدارة المخزون.
- التخطيط للحملات التسويقية بناءً على الأشهر والأيام الأكثر مبيعًا.
# Pizza Sales Dashboard — Power BI

An interactive **Power BI** dashboard for analyzing pizza restaurant sales data, designed to provide management with clear insights into sales performance and support strategic decision-making.

---

## 📖 Overview

This project is an interactive **Dashboard** built using **Power BI** to analyze pizza restaurant sales data. The dashboard aims to provide restaurant management with clear insights into sales performance, helping them make strategic decisions to improve operations and increase profits.

**Added Value:**

- Understand customer preferences for the most-ordered pizza types.
- Identify peak hours to optimize staff scheduling and inventory management.
- Plan marketing campaigns based on the best-selling months and days.

---

## 📸 Dashboard Preview

### 📊 Overview
![Overview](images/overview.png)

### 💰 Sales Details
![Sales Details](images/Sales%20details.png)

### ⏰ Order Details by Hour
![Order Details by Hour](images/Order%20details%20by%20hour.png)

### 📅 Monthly Performance
![Monthly Performance](images/Monthly%20performance.png)

### 🎛️ Interactions Panel
![Interactions Panel](images/Interactions%20panel.png)

---

## 🍕 Top-Selling Pizza Types

The dashboard analyzes sales by pizza type to identify the most-ordered and highest-revenue categories.

**Key Findings:**

- **Best-selling pizza by quantity:** Pepperoni.
- **Highest-revenue pizza:** The Greek Pizza.
- **Least-ordered pizza:** Classic.

---

## ⏰ Peak Hours Analysis

Sales data was analyzed by hour to identify time periods with the highest purchase activity.

**Key Findings:**

- **Peak hours:** Between **12:00 PM – 2:00 PM** and **6:00 PM – 9:00 PM**.
- **Lowest-selling hour:** Around **10:00 AM**.
- **Recommendation:** Increase staff during peak hours to reduce waiting time and improve customer experience.

---

## 📅 Monthly Sales Analysis

Sales performance was analyzed across months to identify the most profitable seasonal periods.

**Key Findings:**

- **Best-selling months:** July, August, and December.
- **Lowest-selling months:** January and February.
- **Recommendation:** Launch special offers or seasonal menus during low-sales months to stimulate demand.

---

## 📆 Daily Sales Analysis

Sales were analyzed by day of the week to identify the most and least active days.

**Key Findings:**

- **Best-selling days:** Friday and Saturday.
- **Lowest-selling days:** Monday and Tuesday.
- **Recommendation:** Offer "Day of the Week" promotions such as "Monday Deal" to boost sales on slow days.

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** — Building the data model and visualizations.
- **DAX (Data Analysis Expressions)** — Creating custom measures (e.g., total sales, average order value).
- **Power Query** — Data cleaning and transformation (removing duplicates, handling missing values).
- **Data Source:** Excel / CSV / SQL containing order records.

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository.
2. Open the file using **Power BI Desktop** (version 2023 or later).
3. Explore the dashboard and interact with the filters to gain different insights.

---

## 📁 Project Structure

| File / Folder | Description |
|---|---|
| `pizza.pbix` | Main Power BI project file. |
| `data/pizza_sales.csv` | Sales data (sample). |
| `images/` | Dashboard screenshots. |
| `README.md` | This documentation file. |

---

## ⚠️ Important Notes

- The data used in this project is **sample data** for educational purposes and skill demonstration only.
- Visualizations can be modified and new measures can be added based on business needs.
- The dashboard is designed to be compatible with desktop devices and large displays.


# أنواع البيتزا الأكثر مبيعاً (Top-Selling Pizza Types)
تركز اللوحة على تحليل المبيعات حسب نوع البيتزا لتحديد الأصناف الأكثر طلبًا والتي تحقق أعلى إيرادات.


**النتائج الرئيسية:**
- **البيتزا الأكثر مبيعاً من حيث الكمية:** [Pepperoni]
- **البيتزا الأعلى إيراداً:** [ The Greek Pizza]
- **البيتزا الأقل طلباً:** [classic]



# تحليل أوقات الذروة (Peak Hours Analysis)
تم تحليل بيانات المبيعات حسب الساعة لتحديد الفترات الزمنية التي تشهد أعلى إقبال على الشراء.



**النتائج الرئيسية:**
- **أوقات الذروة القصوى:** بين الساعة [12:00 - 14:00] ظهراً و [18:00 - 21:00] مساءً.
- **أقل ساعات مبيعاً:** [الفترة الساعة 10:00 صباحاً].
- **التوصية:** زيادة عدد الموظفين خلال أوقات الذروة لتقليل زمن الانتظار وتحسين تجربة العملاء.



#تحليل المبيعات الشهرية (Monthly Sales Analysis)
تم تحليل أداء المبيعات على مدار الأشهر لتحديد الفترات الموسمية الأكثر ربحية.


**النتائج الرئيسية:**
- **الأشهر الأعلى مبيعاً:** [الأشهر: يوليو، أغسطس، ديسمبر].
- **الأشهر الأقل مبيعاً:** [الأشهر:يناير، فبراير].
- **التوصية:** إطلاق عروض خاصة أو قوائم موسمية خلال الأشهر الأقل مبيعاً لتحفيز الطلب.



# تحليل المبيعات اليومية (Daily Sales Analysis)
تم تحليل المبيعات حسب أيام الأسبوع لتحديد الأيام الأكثر والأقل نشاطاً.


**النتائج الرئيسية:**
- **الأيام الأعلى مبيعاً:** [الأيام، مثل: الجمعة والسبت].
- **الأيام الأقل مبيعاً:** [الأيام، مثل: الإثنين والثلاثاء].
- **التوصية:** تقديم عروض "يوم الأسبوع" مثل "عرض الاثنين" لزيادة المبيعات في الأيام الضعيفة.



## 🛠️ الأدوات والتقنيات المستخدمة (Tools & Technologies)
- **Power BI Desktop** - لبناء نموذج البيانات والتصورات.
- **DAX (Data Analysis Expressions)** - لإنشاء المقاييس المخصصة (مثل إجمالي المبيعات، متوسط قيمة الطلب).
- **Power Query** - لتنظيف البيانات وتحويلها (إزالة التكرارات، معالجة القيم المفقودة).
- **مصدر البيانات:** [Excel / CSV / SQL] يحتوي على سجلات الطلبات.






# كيفية استخدام المشروع (How to Use)
1.  قم بتحميل ملف `.pbix` من هذا المستودع.
2.  افتح الملف باستخدام **Power BI Desktop** (الإصدار 2023 أو أحدث).
3.  استعرض لوحة التحكم وتفاعل مع الفلاتر للحصول على رؤى مختلفة.



# هيكل المشروع (Project Structure)
| الملف/المجلد | الشرح |
| :--- | :--- |
| `Pizza.pbix` | ملف المشروع الرئيسي |
| `data/pizza_sales.csv` | بيانات المبيعات (عينة) |
| `images/` | لقطات شاشة للوحة التحكم |
| `README.md` | هذا الملف التوضيحي |


# ملاحظات إضافية
- البيانات المستخدمة في هذا المشروع هي بيانات تجريبية لأغراض تعليمية وعرض المهارات.
- يمكن تعديل التصورات وإضافة مقاييس جديدة حسب احتياجات العمل.
- تم تصميم لوحة التحكم لتكون متوافقة مع الأجهزة المكتبية وشاشات العرض الكبيرة.

