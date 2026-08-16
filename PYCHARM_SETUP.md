<div dir="rtl">

# מדריך התקנה והגדרת PyCharm

## 📝 מה זה PyCharm ולמה להשתמש בו?

**PyCharm** היא תוכנה לכתיבת קוד Python (עורך קוד מתקדם).

**למה PyCharm ולא Jupyter Notebook?**
- ✅ **Jupyter Notebook** - מעולה ללמידה ולתרגול (מה שהקורס משתמש בו)
- ✅ **PyCharm** - מעולה לפרויקטים גדולים ולעבודה מקצועית

**אתם לא חייבים להשתמש ב-PyCharm!** הקורס בנוי ל-Jupyter Notebook ועובד מצוין איתו.  
המדריך הזה הוא לאלו שרוצים לנסות סביבת פיתוח מקצועית יותר.

---

## 🎯 למי זה מתאים?

✅ **כדאי להתקין PyCharm אם:**
- אתם רוצים לעבור לכתיבת קוד "אמיתי" מחוץ למחברות
- אתם מתכננים לבנות פרויקטים גדולים יותר
- אתם רוצים כלים מתקדמים לבדיקת קוד

❌ **אפשר לדלג אם:**
- אתם עדיין מתחילים (Jupyter יותר פשוט)
- אתם מעדיפים ללמוד דרך מחברות
- אין לכם צורך בכלים מקצועיים עכשיו

---

## 📥 שלב 1: הורדת PyCharm

### 1.1 כנסו לאתר JetBrains

1. פתחו דפדפן (Chrome, Firefox, Edge)
2. היכנסו לכתובת: **https://www.jetbrains.com/pycharm/download**
3. תראו שתי גרסאות:
   - **Professional** (כחול) - בתשלום ₪
   - **Community** (שחור) - **חינמי** ✅

### 1.2 בחרו בגרסה החינמית

1. גללו מטה עד שתראו **"Community"**
2. לחצו על כפתור **"Download"** השחור
3. הקובץ יתחיל להוריד (גודל: ~500MB, לוקח 2-10 דקות תלוי באינטרנט)

**💡 טיפ:** אם אתם סטודנטים - יש לכם גישה חינמית לגרסת Professional!  
[לחצו כאן למידע](https://www.jetbrains.com/community/education/#students)

---

## 💿 שלב 2: התקנת PyCharm

### 2.1 למשתמשי Windows

1. **מצאו את הקובץ שהורד:**
   - פתחו את תיקיית **Downloads** (הורדות)
   - חפשו קובץ בשם: `pycharm-community-...exe`

2. **הפעילו את ההתקנה:**
   - לחצו פעמיים על הקובץ
   - אם Windows שואל "האם לאפשר?" → לחצו **"כן"**

3. **עקבו אחרי ההתקנה:**
   - לחצו **"Next"** (הבא)
   - בחרו תיקיית התקנה (השאירו ברירת מחדל) → **"Next"**
   - **חשוב!** בחרו באפשרויות הבאות:
     - ☑ Create Desktop Shortcut (צור קיצור דרך בשולחן העבודה)
     - ☑ Add "Open Folder as Project" (הוסף "פתח תיקייה כפרויקט")
     - ☑ Add launchers dir to PATH (הוסף ל-PATH)
   - לחצו **"Next"** → **"Install"**

4. **המתינו להתקנה** (2-5 דקות)

5. **סיום:**
   - לחצו **"Finish"**
   - אם PyCharm לא נפתח אוטומטית, חפשו אותו בשולחן העבודה

### 2.2 למשתמשי Mac

1. **מצאו את הקובץ שהורד:**
   - פתחו **Finder** → **Downloads**
   - חפשו קובץ: `pycharm-community-...dmg`

2. **פתחו את הקובץ:**
   - לחצו פעמיים על קובץ ה-DMG
   - תראו חלון עם אייקון PyCharm

3. **גררו ל-Applications:**
   - גררו את אייקון PyCharm לתיקיית **Applications**
   - המתינו לסיום ההעתקה

4. **פתחו את PyCharm:**
   - פתחו **Launchpad** או **Applications**
   - חפשו **PyCharm** ולחצו עליו
   - אם macOS שואל "האם לפתוח?" → לחצו **"פתח"**

### 2.3 למשתמשי Linux (Ubuntu/Debian)

1. פתחו **Terminal**
2. הקלידו:
```bash
sudo snap install pycharm-community --classic
```
3. הקלידו את הסיסמה שלכם
4. המתינו לסיום ההתקנה
5. פתחו PyCharm מתפריט האפליקציות

---

## ⚙️ שלב 3: הגדרה ראשונית של PyCharm

### 3.1 פתיחה ראשונה

1. **הפעילו את PyCharm** (מהשולחן העבודה או מתפריט Start)

2. **מסך ברוכים הבאים:**
   - אם זו הפעם הראשונה, תראו "Welcome to PyCharm"
   - לחצו **"New Project"** (פרויקט חדש)

### 3.2 יצירת פרויקט ראשון

1. **בחרו מיקום לפרויקט:**
   - בשדה **Location** תראו נתיב כמו:
     - Windows: `C:\Users\YourName\PycharmProjects\pythonProject`
     - Mac: `/Users/YourName/PycharmProjects/pythonProject`
   - **אפשר להשאיר כמו שזה** או לשנות ל-`python-advanced-course`

2. **Python Interpreter (מפרש Python):**
   - תחת **"Python Interpreter"** תראו רשימה נפתחת
   - אם Python מותקן, תראו משהו כמו `Python 3.11` או `Python 3.10`
   - אם לא רואים כלום:
     - לחצו על החץ ליד **"Python Interpreter"**
     - בחרו **"Add Interpreter"** → **"Add Local Interpreter"**
     - PyCharm ינסה למצוא את Python אוטומטית
     - אם זה לא עובד → [עברו לשלב 4 למטה](#-שלב-4-התקנת-python-אם-חסר)

3. **לחצו "Create"** (צור)

4. **PyCharm ייפתח עם הפרויקט החדש!** 🎉

---

## 🐍 שלב 4: התקנת Python (אם חסר)

אם PyCharm לא מצא Python, עשו את זה:

### 4.1 הורידו את Python

1. היכנסו ל: **https://www.python.org/downloads**
2. לחצו על הכפתור הגדול **"Download Python 3.x"**
3. הקובץ יוריד

### 4.2 התקינו את Python

**Windows:**
1. לחצו פעמיים על הקובץ שהורד
2. **חשוב מאוד!** ☑ סמנו **"Add Python to PATH"** למטה
3. לחצו **"Install Now"**
4. המתינו לסיום → **"Close"**

**Mac:**
1. לחצו פעמיים על הקובץ ה-PKG
2. עקבו אחרי ההוראות (Next → Next → Install)
3. הקלידו סיסמה אם נדרש

### 4.3 בדקו שהתקנה עברה

1. פתחו **Command Prompt** (Windows) או **Terminal** (Mac/Linux)
2. הקלידו:
```bash
python --version
```
3. אמור להופיע משהו כמו: `Python 3.11.5`

### 4.4 חזרו ל-PyCharm

1. פתחו PyCharm שוב
2. בחרו **"New Project"**
3. עכשיו Python אמור להופיע ב-**"Python Interpreter"**

---

## 📂 שלב 5: פתיחת קורס Python המתקדם ב-PyCharm

### 5.1 הורידו את הקורס (אם עוד לא)

1. פתחו **Command Prompt** / **Terminal**
2. נווטו לתיקייה שבה אתם רוצים לשמור:
```bash
cd Desktop
```
3. שכפלו את הקורס:
```bash
git clone https://github.com/DorElias/python-advanced-course.git
```

**אין לכם Git?** [לחצו כאן למדריך התקנה מהיר](https://git-scm.com/downloads)

**לא רוצים להתעסק עם Git?**
1. היכנסו ל: https://github.com/DorElias/python-advanced-course
2. לחצו על כפתור ירוק **"Code"**
3. בחרו **"Download ZIP"**
4. חלצו את הקובץ

### 5.2 פתחו את הקורס ב-PyCharm

1. **ב-PyCharm:**
   - **File** → **Open**
   - או מהמסך הראשי: **"Open"**

2. **בחרו בתיקייה:**
   - נווטו לתיקייה `python-advanced-course`
   - לחצו **"OK"**

3. **PyCharm ישאל "Trust Project?"**
   - לחצו **"Trust Project"** (בטח בפרויקט)

4. **המתינו שהפרויקט ייטען** (יכול לקחת דקה)

---

## 🔧 שלב 6: הגדרת Jupyter Notebook ב-PyCharm

הקורס משתמש במחברות Jupyter, אז נגדיר את PyCharm לעבוד איתן:

### 6.1 התקינו Jupyter

1. ב-PyCharm, למטה תראו **"Terminal"** → לחצו עליו
2. הקלידו:
```bash
pip install jupyter notebook
```
3. המתינו לסיום (יכול לקחת דקה)

### 6.2 פתחו מחברת Jupyter

1. בצד שמאל תראו את קבצי הפרויקט
2. פתחו: **content** → **day01** → **1_Review.ipynb**
3. PyCharm ישאל "Install Jupyter Support?" → לחצו **"Install"**
4. המחברת תיפתח!

### 6.3 הריצו תא (Cell) ראשון

1. לחצו על תא קוד ראשון
2. לחצו על כפתור ▶️ (Play) או `Shift + Enter`
3. הקוד ירוץ! 🎉

---

## 🎨 שלב 7: התאמה אישית (אופציונלי)

### 7.1 שינוי ערכת צבעים

1. **File** → **Settings** (Windows/Linux) או **PyCharm** → **Preferences** (Mac)
2. **Appearance & Behavior** → **Appearance**
3. **Theme:** בחרו בין:
   - **Darcula** (כהה - נוח לעיניים)
   - **Light** (בהיר - ברירת מחדל)
   - **High Contrast** (ניגודיות גבוהה)
4. לחצו **"OK"**

### 7.2 שינוי גודל פונט

1. **Settings** → **Editor** → **Font**
2. **Size:** שנו ל-14 או 16 (ברירת מחדל: 13)
3. לחצו **"OK"**

### 7.3 מספרי שורות

1. **Settings** → **Editor** → **General** → **Appearance**
2. ☑ **Show line numbers** (הצג מספרי שורות)
3. לחצו **"OK"**

---

## 🆘 פתרון בעיות נפוצות

### בעיה 1: "Python interpreter not found"

**פתרון:**
1. **File** → **Settings** → **Project** → **Python Interpreter**
2. לחצו על גלגל השיניים ⚙️ → **"Add"**
3. בחרו **"System Interpreter"**
4. PyCharm יחפש Python אוטומטית
5. בחרו את Python שנמצא → **"OK"**

### בעיה 2: "No module named 'pandas'" (או ספרייה אחרת)

**פתרון:**
1. פתחו **Terminal** בתחתית PyCharm
2. הקלידו:
```bash
pip install pandas openpyxl requests
```
3. המתינו לסיום

**או:**
1. **File** → **Settings** → **Project** → **Python Interpreter**
2. לחצו על **+** (פלוס)
3. חפשו `pandas` → **"Install Package"**
4. חזרו על זה עבור `openpyxl`, `requests`

### בעיה 3: Jupyter Notebook לא נפתח

**פתרון:**
1. ודאו ש-Jupyter מותקן:
```bash
pip install jupyter notebook ipykernel
```
2. **File** → **Settings** → **Plugins**
3. ודאו שהתוסף **"Jupyter"** מופעל (יש לו ✓)
4. אם לא, חפשו אותו והתקינו

### בעיה 4: עברית מוצגת הפוך

**פתרון:**
1. **File** → **Settings** → **Editor** → **General**
2. ☑ **Support RTL** (תמיכה בימין-לשמאל)
3. לחצו **"OK"**

### בעיה 5: PyCharm איטי

**פתרון:**
1. **Help** → **Edit Custom VM Options**
2. שנו את השורה:
```
-Xmx2048m
```
ל:
```
-Xmx4096m
```
3. שמרו ואתחלו את PyCharm

---

## ✅ סיכום מהיר - מה עשינו?

1. ✅ הורדנו והתקנו PyCharm Community (חינם)
2. ✅ וידאנו ש-Python מותקן
3. ✅ פתחנו את קורס Python המתקדם
4. ✅ הגדרנו Jupyter Notebook לעבודה במחברות
5. ✅ הרצנו תא קוד ראשון

---

## 📚 משאבים נוספים

- **PyCharm Documentation (תיעוד רשמי):** https://www.jetbrains.com/pycharm/learn
- **קיצורי מקלדת שימושיים:**
  - `Ctrl + /` (Mac: `Cmd + /`) - הערה/ביטול הערה לשורה
  - `Shift + Enter` - הרצת תא ב-Jupyter
  - `Ctrl + D` (Mac: `Cmd + D`) - שכפל שורה
  - `Ctrl + Space` - השלמה אוטומטית
- **וידאו הדרכה:** חפשו ביוטיוב "PyCharm for beginners"

---

## 💡 טיפים אחרונים

1. **Jupyter vs PyCharm:**
   - השתמשו ב-**Jupyter Notebook** ללמידה ותרגול (כמו שהקורס בנוי)
   - עברו ל-**PyCharm** כשאתם בונים פרויקטים גדולים יותר

2. **אל תפחדו לנסות:**
   - PyCharm יש הרבה כפתורים ותפריטים - זה בסדר!
   - התחילו פשוט והדברים יבואו בהדרגה

3. **קהילה:**
   - יש שאלה? חפשו ב-Google: "PyCharm how to..."
   - יש קהילה ענקית שעוזרת!

---

**בהצלחה! אם יש לכם שאלות, אל תהססו לשאול! 🚀**

</div>
