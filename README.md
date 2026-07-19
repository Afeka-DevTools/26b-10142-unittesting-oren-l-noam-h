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

## הכנת הפרויקט והרצת הבדיקות

### 1. שכפול הפרויקט למחשב מקומי

  <div dir="rtl">

יש להריץ את הפקודה הבאה בטרמינל -
```bash
git clone https://github.com/Afeka-DevTools/26b-10142-unittesting-oren-l-noam-h.git
```
  
  </div>

  <br />


### 2. התקנת Java

  <div dir="rtl">

יש לעקוב אחר [**המדריך להתקנת JAVA**](/utils/INSTALL_JAVA.md)

  </div>

  <br />

### 3. בניית הפרויקט והרצת הבדיקות

  <div dir="rtl">
חשוב -
יש לפתוח טרמינל מראש בהתאם למערכת ההפעלה -

  <br /> <br />
  
| מערכת הפעלה | טרמינל |
|---|---|
| Windows | Command Prompt - `cmd` |
| Linux / macOS | `git bash` |

<br />

* בטרמינל, יש להיכנס לתיקיית הפרויקט באמצעות הפקודה הבאה -
```bash
cd <project_dir>
```

  <br />

* בניית הפרויקט: יש להריץ את הפקודה הבאה בטרמינל -

```bat
.\gradlew.bat build
```

בנייה מוצלחת תסתיים עם קלט דומה לזה -

```bat
BUILD SUCCESSFUL in Xs
```

  <br />

* הרצת הבדיקות: יש להריץ את הפקודה הבאה בטרמינל -

```bat
.\gradlew.bat test
```

  <br />



* בניית הפרויקט: יש להריץ את הפקודה הבאה בטרמינל -

```bash
./gradlew build
```
בנייה מוצלחת תסתיים עם קלט דומה לזה -

```bat
BUILD SUCCESSFUL in Xs
```

  <br />

* הרצת הבדיקות: יש להריץ את הפקודה הבאה בטרמינל -

```bash
./gradlew test
```

  </div>

  <br />

### 4. דו"ח הבדיקות

  <div dir="rtl">

* יש לפתוח את [דו"ח הבדיקות](/app/build/reports/tests/test/index.html) בדפדפן על מנת לראות את תוצאות הבדיקות

  </div>

</div>
