- מערכת ניהול עובדים 
Employees management

תאור הפרויקט
מערכת לניהול העובדים בעסק.
באמצעות המערכת ניתן להכניס עובד חדש,  פרטיו ותנאי העסקתו, וכן שעות עבודתו
בנוסף,יתואמו לעובדים המטלות המוצעות.
 
ישויות 
עובד- פרטי העובד הבסיסיים, והמשתנים מעת לעת (מצב משפחתי, ילדים וכו')
נוכחות – שעות העבודה החודש 
מטלה
לעובד   Routes מיפוי

שליפת רשימת העובדים 
GET https://employees.co.il/employees
שליפת עובד לפי מזהה 
GET https://employees.co.il/employees/1
הוספת עובד
POST https://employees.co.il/employees
עדכון עובד
PUT https://employees.co.il/employees/1
עדכון סטטוס עובד
PUT https://employees.co.il/employees/1/status

לדוחות הנוכחות   Routes מיפוי

     שליפת דוחות הנוכחות 
GET https://employees.co.il/reports
שליפת עובד לפי מזהה העובד 
GET https://employees.co.il/reports/1
הוספת דוח 
POST https://employees.co.il/reports
עדכון דוח
PUT https://employees.co.il/reports/1
מחיקת דוח שגוי
DELETE https://employees.co.il/reports/1
למטלות   Routes מיפוי

שליפת רשימת המטלות 
GET https://employees.co.il/tasks
שליפת המטלה לפי מזהה 
GET https://employees.co.il/tasks/1
הוספת מטלה
POST https://employees.co.il/task
עדכון מטלה
PUT https://employees.co.il/tasks/1
מחיקת מטלה
DELETE https://employees.co.il/tasks/1


