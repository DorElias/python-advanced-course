# הוראות ייבוא מבחן הכניסה ל-Microsoft Forms

## 📋 קובץ מוכן: `entrance-exam-forms.csv`

---

## 🚀 איך לייבא ל-Microsoft Forms?

### שיטה 1: יצירה ידנית (מומלץ - הכי פשוט)

Microsoft Forms לא תומך בייבוא CSV ישיר. הדרך הטובה ביותר:

1. **כנסו ל-Microsoft Forms:**
   - עברו ל-[forms.office.com](https://forms.office.com)
   - לחצו על **+ New Form** או **+ New Quiz**

2. **העתיקו שאלה-שאלה מהמסמך הזה:**

---

## 📝 השאלות (להעתקה)

### שאלה 1
**מה יודפס בקוד הבא?**

```python
numbers = [10, 20, 30, 40, 50]
print(numbers[2])
```

- [ ] 10
- [ ] 20
- [x] 30 ✅
- [ ] 40

---

### שאלה 2
**איזו פונקציה מחזירה את האורך של רשימה?**

- [ ] size(list)
- [ ] length(list)
- [x] len(list) ✅
- [ ] count(list)

---

### שאלה 3
**מה התוצאה של הקוד הבא?**

```python
x = [1, 2, 3]
y = x
y.append(4)
print(x)
```

- [ ] [1, 2, 3]
- [x] [1, 2, 3, 4] ✅
- [ ] [4]
- [ ] שגיאה

---

### שאלה 4
**איך ניגשים לערך במילון?**

```python
person = {"name": "דני", "age": 25}
```

- [ ] person[0]
- [ ] person.name
- [x] person["name"] ✅
- [ ] person->name

---

### שאלה 5
**מה יקרה בקוד הבא?**

```python
def greet(name):
    return "שלום " + name

result = greet("שרה")
```

- [ ] יודפס שלום שרה
- [x] result יכיל את המחרוזת "שלום שרה" ✅
- [ ] שגיאה - חסר print
- [ ] result יהיה None

---

### שאלה 6
**איך קוראים קובץ טקסט בפייתון?**

- [x] file = open("data.txt", "r") ✅
- [ ] file = read("data.txt")
- [ ] file = load("data.txt")
- [ ] file = import("data.txt")

---

### שאלה 7
**מה יודפס בקוד הבא?**

```python
for i in range(3):
    print(i)
```

- [ ] 1 2 3
- [x] 0 1 2 ✅
- [ ] 0 1 2 3
- [ ] 1 2

---

### שאלה 8
**איך בודקים אם מפתח קיים במילון?**

```python
data = {"city": "תל אביב", "temp": 28}
```

- [x] "city" in data ✅
- [ ] data.has("city")
- [ ] data.contains("city")
- [ ] exists(data, "city")

---

### שאלה 9
**מה הבעיה בקוד הבא?**

```python
class Car:
    def __init__(color):
        self.color = color
```

- [x] חסר self בפרמטרים של __init__ ✅
- [ ] color צריך להיות self.color
- [ ] חסר return
- [ ] שם המחלקה צריך להיות באותיות קטנות

---

### שאלה 10
**מה יחזיר הקוד הבא?**

```python
numbers = [1, 2, 3, 4, 5]
result = [x * 2 for x in numbers if x > 2]
print(result)
```

- [ ] [2, 4, 6, 8, 10]
- [x] [6, 8, 10] ✅
- [ ] [3, 4, 5]
- [ ] [4, 6, 8]

---

## ⚙️ הגדרות מומלצות ב-Forms:

1. **סוג טופס:** Quiz (חידון)
2. **ציון עובר:** 7/10 (70%)
3. **הגדרות:**
   - ☑ Shuffle questions (ערבב שאלות)
   - ☑ Show results immediately (הצג תוצאות מיד)
   - ☑ Show correct answers (הצג תשובות נכונות)

---

## 🎯 הגדרת ציונים אוטומטית:

1. בכל שאלה לחצו על **"..."** → **Math**
2. הגדירו **Points: 1** לכל שאלה
3. סמנו את התשובה הנכונה (מסומנת ב-✅ למעלה)

---

## 📊 שיתוף הטופס:

לאחר יצירה:
1. לחצו על **Share**
2. בחרו **Anyone with the link can respond**
3. העתיקו את הלינק ושלחו למועמדים

---

## 💡 טיפ: ייבוא מהיר

אם בכל זאת רוצים לייבא אוטומטית:
- Microsoft Forms לא תומך בייבוא CSV
- אפשר להשתמש ב-**Power Automate** לאוטומציה
- או להשתמש ב-**Google Forms** (תומך ייבוא) ואז לייצא

---

**זמן יצירה משוער:** ~10 דקות (העתקה ידנית)

בהצלחה! 🚀
