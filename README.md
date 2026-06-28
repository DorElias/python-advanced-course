# קורס Python מתקדם - לומדים פייתון 2

<div dir="rtl">

## ברוכים הבאים לקורס המתקדם! 🎉

קורס זה מיועד לבוגרי [הקורס הבסיסי](https://github.com/PythonFreeCourse/Notebooks) שרוצים להרחיב את הידע שלהם ולהפוך את פייתון לכלי עבודה יומיומי.

---

## 🎯 מטרת הקורס

להעניק לכם כלים מתקדמים לאוטומציה משרדית ועבודה עם נתונים:
- עבודה עם קבצי Excel, CSV ו-JSON
- תקשורת עם שרתים והורדת נתונים מהאינטרנט
- ניהול מסדי נתונים בסיסי
- ניתוח נתונים עם Pandas
- שליחת מיילים אוטומטית
- הרצת משימות במקביל
- בניית פרויקט אמיתי משולב

---

## 📚 תוכנית הלימודים

### יום 1: חזרה והיכרות מחודשת ✅
- **1_Review.ipynb** - חזרה על טיפוסי משתנים, רשימות, מילונים, קבצים + מערכת אנשי קשר
- **2_Functions_and_Modules.ipynb** - *args, **kwargs, lambda, מודולים (os, datetime, random, collections) + מערכת ספרייה
- **Summary.ipynb** - 8 תרגילים מקיפים כולל מערכת הוצאות ותורים

### יום 2: OOP - חזרה מעמיקה ✅
- **1_Classes_Review.ipynb** - Classes, __init__, Inheritance + מערכת TODO + מערכת עובדים (4 רמות ירושה)
- **2_Advanced_OOP.ipynb** - Magic Methods (__str__, __len__, __add__), Properties, אימות + מערכת מסעדה
- **Summary.ipynb** - 8 תרגילים כולל מערכת ספרייה ומערכת בנקאות

### יום 3: עבודה עם פורמטים - CSV, JSON, Excel ✅
- **1_CSV_Files.ipynb** - DictReader/Writer, סטטיסטיקות, קיבוץ + מערכת ניהול מוצרים
- **2_JSON_Files.ipynb** - load/dump, נתונים מקוננים, המרות + מערכת הגדרות
- **3_Excel_Files.ipynb** - openpyxl, עיצוב, נוסחאות, מספר גליונות + מחולל דוחות
- **Summary.ipynb** - 6 תרגילים כולל מערכת מלאי וחשבונית מעוצבת

### יום 4: Requests - תקשורת עם האינטרנט ✅
- **1_Requests_Basics.ipynb** - HTTP basics, GET requests, query parameters
- **2_Working_with_APIs.ipynb** - JSON responses, error handling, APIs ציבוריים (wttr.in, quotable.io, dog.ceo)
- **Summary.ipynb** - 6 תרגילים כולל מזג אויר, הורדת תמונות, מעקב מטבעות

### יום 5: SQL בסיסי (SQLite) 🔄
- **1_SQLite_Basics.ipynb** - CREATE, INSERT, SELECT, WHERE
- **2_SQL_Advanced.ipynb** - UPDATE, DELETE, JOIN, GROUP BY
- **Summary.ipynb** - תרגילים מעשיים
- *(נוצר על ידי subagent)*

### יום 6: Pandas - ניתוח נתונים מתקדם ⚠️
- **1_Pandas_Basics.ipynb** - DataFrame, read_csv/read_excel, basic operations **(skeleton)**
- **2_Pandas_Analysis.ipynb** - filtering, groupby, merge **(skeleton)**
- **Summary.ipynb** **(skeleton)**

### יום 7: Email Automation + Threading ⚠️
- **1_Email_Automation.ipynb** - smtplib basics **(skeleton)**
- **2_Threading_Basics.ipynb** - threading.Thread **(skeleton)**
- **Summary.ipynb** **(skeleton)**

### יום 8: פרויקט סיום משולב ⚠️
- **Final_Project.ipynb** - 3 אופציות פרויקט **(skeleton)**
- **Summary.ipynb** - המלצות להמשך **(skeleton)**

---

**⚠️ שימו לב:** ימים 6-8 נוצרו כקבצי skeleton עם מבנה בסיסי ודוגמאות קוד. אפשר להרחיב אותם בסשנים נפרדים.

---

## 💻 דרישות מקדימות

### ידע נדרש
- סיום [הקורס הבסיסי](https://github.com/PythonFreeCourse/Notebooks) או ידע שווה ערך
- הבנה של: משתנים, תנאים, לולאות, פונקציות, מחלקות, קבצים

### התקנה

1. **Python 3.8+**
   - הורידו מ-[python.org](https://www.python.org/downloads/)
   - בדקו שהתקנה עברה בהצלחה:
     ```bash
     python --version
     ```

2. **Jupyter Notebook**
   ```bash
   pip install notebook
   ```

3. **ספריות נדרשות**
   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 איך להתחיל?

1. שכפלו את הריפו:
   ```bash
   git clone https://github.com/YourUsername/python-advanced-course.git
   cd python-advanced-course
   ```

2. התקינו ספריות:
   ```bash
   pip install -r requirements.txt
   ```

3. הפעילו Jupyter:
   ```bash
   jupyter notebook
   ```

4. פתחו את `content/day01/` והתחילו ללמוד!

---

## 📖 מבנה הריפו

```
python-advanced-course/
├── content/
│   ├── day01/          # חזרה והיכרות מחודשת
│   ├── day02/          # OOP חזרה מעמיקה
│   ├── day03/          # CSV, JSON, Excel
│   ├── day04/          # Requests ו-APIs
│   ├── day05/          # SQL בסיסי
│   ├── day06/          # Pandas
│   ├── day07/          # Email + Threading
│   └── day08/          # פרויקט סיום
├── resources/          # קבצי דוגמה (CSV, Excel, JSON)
├── requirements.txt    # ספריות נדרשות
└── README.md           # הקובץ הזה
```

---

## 🤝 תרומה

מצאתם טעות? רוצים להוסיף תוכן? נשמח לקבל Pull Requests!

---

## 📞 יצירת קשר

שאלות? הצטרפו לקבוצת [דיסקורד](https://discord.gg/python-il) או פתחו Issue ב-GitHub.

---

## 📄 רישיון

קורס זה זמין תחת רישיון MIT - ראו קובץ LICENSE לפרטים.

---

## 🙏 תודות

- [לומדים פייתון](https://github.com/PythonFreeCourse/Notebooks) - הקורס הבסיסי המעולה
- הקהילה העברית של Python
- כל התורמים והמשתתפים!

---

**בהצלחה! 🐍✨**

</div>
