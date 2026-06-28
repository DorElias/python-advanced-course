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

## ✨ מה בקורס?

- ✅ **24 מחברות Jupyter מלאות** - כל יום כולל 2-3 מחברות + תרגילים
- ✅ **הסברים מפורטים** - טקסט הסבר לפני ואחרי כל קוד
- ✅ **דוגמאות מציאותיות** - שמות משתנים בעברית, בעיות אמיתיות
- ✅ **16+ פרויקטים מעשיים** - כל יום מסתיים בפרויקט משולב
- ✅ **50+ תרגילים** - בדיקת הבנה ותרגול
- ✅ **RTL מלא** - כל הטקסט מעוצב נכון מימין לשמאל

---

## 📚 תוכנית הלימודים

### יום 1: חזרה והיכרות מחודשת ✅
- **1_Review.ipynb** - חזרה על טיפוסי משתנים, רשימות, מילונים, קבצים + מערכת אנשי קשר
- **2_Functions_and_Modules.ipynb** - *args, **kwargs, lambda, מודולים (os, datetime, random) + מערכת ספרייה
- **Summary.ipynb** - 8 תרגילים כולל מערכת הוצאות ותורים

### יום 2: OOP - חזרה מעמיקה ✅
- **1_Classes_Review.ipynb** - Classes, Inheritance + מערכת TODO + מערכת עובדים
- **2_Advanced_OOP.ipynb** - Magic Methods, Properties + מערכת מסעדה
- **Summary.ipynb** - 8 תרגילים כולל מערכת ספרייה ובנקאות

### יום 3: עבודה עם פורמטים - CSV, JSON, Excel ✅
- **1_CSV_Files.ipynb** - DictReader/Writer, סטטיסטיקות + מערכת ניהול מוצרים
- **2_JSON_Files.ipynb** - load/dump, נתונים מקוננים + מערכת הגדרות
- **3_Excel_Files.ipynb** - openpyxl, עיצוב, נוסחאות + מחולל דוחות
- **Summary.ipynb** - 6 תרגילים כולל מערכת מלאי וחשבונית

### יום 4: Requests - תקשורת עם האינטרנט ✅
- **1_Requests_Basics.ipynb** - HTTP basics, GET requests, query parameters
- **2_Working_with_APIs.ipynb** - JSON responses, error handling, APIs ציבוריים
- **Summary.ipynb** - 6 תרגילים כולל מזג אויר והורדת תמונות

### יום 5: SQL בסיסי (SQLite) ✅
- **1_SQLite_Basics.ipynb** - CREATE, INSERT, SELECT, WHERE
- **2_SQL_Advanced.ipynb** - UPDATE, DELETE, JOIN, GROUP BY
- **Summary.ipynb** - תרגילים מעשיים

### יום 6: Pandas - ניתוח נתונים מתקדם ✅
- **1_Pandas_Basics.ipynb** - DataFrame, read_csv/read_excel, basic operations
- **2_Pandas_Analysis.ipynb** - filtering, groupby, merge, pivot tables
- **Summary.ipynb** - תרגילים מקיפים

### יום 7: Email Automation + Threading ✅
- **1_Email_Automation.ipynb** - smtplib, שליחת מיילים עם קבצים מצורפים
- **2_Threading_Basics.ipynb** - threading.Thread, הרצה מקבילית
- **Summary.ipynb** - 3 תרגילים משולבים

### יום 8: פרויקט סיום משולב ✅
- **Final_Project.ipynb** - 3 פרויקטים מפורטים:
  1. מערכת ניהול מכירות (SQL + Excel + Pandas + Email)
  2. מעקב מחירים אוטומטי (API + SQL + Threading)
  3. מערכת עיבוד מיילים (IMAP + SQL + Excel)
- **Summary.ipynb** - המלצות להמשך לימוד ומשאבים

---

## 💻 דרישות מקדימות

### ידע נדרש
- סיום [הקורס הבסיסי](https://github.com/PythonFreeCourse/Notebooks) או ידע שווה ערך
- הבנה של: משתנים, תנאים, לולאות, פונקציות, מחלקות, קבצים

### התקנה

**Python 3.8 ומעלה** - הורידו מ-[python.org](https://www.python.org/downloads/)

בדקו שהתקנה עברה בהצלחה:
```bash
python --version
```

---

## 🚀 איך להתחיל?

### 1. שכפלו את הריפו
```bash
git clone https://github.com/DorElias/python-advanced-course.git
cd python-advanced-course
```

### 2. התקינו את הספריות הנדרשות
```bash
pip install -r requirements.txt
```

הספריות שיותקנו:
- `pandas` - ניתוח נתונים
- `openpyxl` - עבודה עם Excel
- `requests` - תקשורת HTTP
- `notebook` - Jupyter Notebook

### 3. הפעילו את Jupyter
```bash
jupyter notebook
```

### 4. התחילו ללמוד!
פתחו את `content/day01/1_Review.ipynb` והתחילו מיום 1.

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
├── resources/          # קבצי דוגמה (CSV, JSON)
├── requirements.txt    # ספריות נדרשות
├── README.md
└── STATUS.md           # מעקב התקדמות
```

כל תיקיית יום מכילה:
- מחברות לימוד (`.ipynb`)
- תיקיית `images/` עם לוגו הקורס
- קבצי עזר לתרגילים (לפי הצורך)

---

## 💡 טיפים ללמידה

1. **למדו לפי הסדר** - כל יום בנוי על הקודם
2. **תרגלו את הקוד** - הריצו כל דוגמה, נסו לשנות ולראות מה קורה
3. **עשו את התרגילים** - זו הדרך הטובה ביותר ללמוד
4. **בנו משהו משלכם** - קחו פרויקט מהקורס והתאימו לצרכים שלכם
5. **אל תפחדו לטעות** - זה חלק מהתהליך!

---

## 🎯 למי הקורס מתאים?

✅ **מתאים ל:**
- בוגרי הקורס הבסיסי
- אנשי משרד שרוצים לבצע אוטומציה
- מי שעובד עם Excel ורוצה לעבור לקוד
- מי שרוצה לנתח נתונים בצורה מקצועית
- תלמידי תיכון/אקדמיה ברמה מתקדמת

❌ **פחות מתאים ל:**
- מתחילים לחלוטין (תתחילו בקורס הבסיסי)
- מי שמחפש פיתוח אתרים (Flask/Django)
- מי שמחפש Machine Learning מעמיק

---

## 🤝 תרומה

מצאתם טעות? רוצים להוסיף תוכן? נשמח לקבל Pull Requests!

### איך לתרום?
1. עשו Fork לריפו
2. צרו branch חדש (`git checkout -b feature/amazing-feature`)
3. בצעו commit (`git commit -m 'Add amazing feature'`)
4. דחפו ל-branch (`git push origin feature/amazing-feature`)
5. פתחו Pull Request

---

## 📄 רישיון

קורס זה זמין תחת רישיון MIT - ראו קובץ LICENSE לפרטים.

---

## 🙏 תודות

- [לומדים פייתון](https://github.com/PythonFreeCourse/Notebooks) - הקורס הבסיסי המעולה שעליו הקורס הזה בנוי
- הקהילה העברית של Python
- כל התורמים והמשתתפים!

---

**בהצלחה בלימוד! 🐍✨**

</div>
