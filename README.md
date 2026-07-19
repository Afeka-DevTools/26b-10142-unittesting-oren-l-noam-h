<div dir="rtl">

# כלי פיתוח - מטלה #2 (LLM, Unit Testing, Java)

## חברי הצוות + חלוקת הבדיקות

</div>

<div dir="rtl">

### אורן לוי -
| # | פונקציה שנבדקה |
|--- | --- |
| 1 | `App.add()` |
| 2 | `App.isPrime()`  |
| 3 | `App.reverse()` |
| 4 | `App.factorial()` |
| 5 |  `App. isPalindrome()` |

### ניקיטה קויפמן -
| # | פונקציה שנבדקה |
|--- | --- |
| 1 | `App.fibonacciUpTo()` |
| 2 | `App.charFrequency()`  |
| 3 | `App.isAnagram()` |

### נועם הרמבם -
| # | פונקציה שנבדקה |
|--- | --- |
| 1 | `App.average()` |
| 2 | `App.filterEvens()`  |
| 3 | `App.mostCommonWord()` |

</div>

---

<div dir="rtl">

### 1. שכפול הפרויקט למחשב מקומי
יש להריץ את הפקודה הבאה בטרמינל -
```bash
git clone https://github.com/Afeka-DevTools/26b-10142-unittesting-oren-l-noam-h.git
```

</div>

<div dir="rtl">

### 2. התקנת Java 
יש לעקוב אחר [**המדריך להתקנת JAVA**](/utils/INSTALL_JAVA.md)

</div>

<div dir="rtl">

### 3. בניית הפרויקט והרצת הבדיקות

**עבור `Windows`** -
* יש לפתוח טרמינל של Command Prompt (`cmd`)

* בטרמינל, יש להיכנס לתיקיית הפרויקט באמצעות הפקודה הבאה -
```bash
cd <project_dir>
```

* בניית הפרויקט: יש להריץ את הפקודה הבאה בטרמינל -

```bat
.\gradlew.bat build
```

בנייה מוצלחת תסתיים עם קלט דומה לזה -

```bat
BUILD SUCCESSFUL in Xs
```

* הרצת הבדיקות: יש להריץ את הפקודה הבאה בטרמינל -

```bat
.\gradlew.bat test
```

**עבור `Linux / macOS`** -

* בניית הפרויקט: יש להריץ את הפקודה הבאה בטרמינל -

```bash
./gradlew build
```
בנייה מוצלחת תסתיים עם קלט דומה לזה -

```bat
BUILD SUCCESSFUL in Xs
```

* הרצת הבדיקות: יש להריץ את הפקודה הבאה בטרמינל -

```bash
./gradlew test
```

</div>

<div dir="rtl">

### 4. דו"ח הבדיקות

* יש לפתוח את [דו"ח הבדיקות](/app/build/reports/tests/test/index.html) בדפדפן על מנת לראות את תוצאות הבדיקות

```
app/build/reports/tests/test/index.html
```

</div>