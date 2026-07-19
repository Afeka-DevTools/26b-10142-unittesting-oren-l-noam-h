<div dir="rtl">

# התקנת JAVA

**חשוב** - יש לפתוח מראש טרמינל של `git bash`

### 1. לבדוק האם JAVA כבר מותקן

בטרמינל, יש לכתוב את הפקודה הבאה -

```bash
java --version
```

במידה ומוצג מידע בצורה כזו, ניתן לדלג ולהמשיך [בהכנות לשימוש](../README.md)

![Java - Version details](./Java%20-%20Version%20details.png)

**אזהרה** - יש לוודא שהגרסה המותקנת היא **`JDK 21` !** \
במידה והגרסה אינה 21, יש לעקוב אחר המדריך.


בנוסף, במידה ומוצגת שגיאה כזו, יש לעקוב אחר המדריך -

![Java - Error](./Java%20-%20Error.png)

### הורדת JDK
 יש להוריד ולהתקין `JDK 21` לפי מערכת ההפעלה של המחשב  - [**קישור**](https://adoptium.net/temurin/releases?variant=openjdk21&version=21&os=any&arch=any)


### הגדרת משתני סביבה (`JAVA_HOME`, `PATH`)

---

**עבור `Windows`** -
* חפשו בתפריט `עריכת משתני סביבה של המערכת`
* לחצו על `משתני סביבה`
* תחת **'משתני מערכת'** -
    * לחצו על `חדש...`
    * עבור שם המשתנה - כתבו `JAVA_HOME`
    * עבור ערך המשתנה - כתבו את הנתיב לתיקיית ה - JDK: \
    `C:\path\to\jdk\directory`
    * מצאו את המשתנה `PATH` ולחצו על `עריכה...`
    * הוסיפו שורה חדשה עם הערך הבא - `%JAVA_HOME%\bin`

* יש לפתוח **טרמינל חדש**  ולהריץ שוב את [הפקודה לאיתור התקנת Java](#1-בדיקה-האם-מותקן-java-על-המחשב)

---

**עבור `Linux / macOS`**
* בטרמינל, יש לכתוב את הפקודה הבאה -

```bash
which java
# Example Output: /usr/bin/java
```

* בטרמינל, יש לכתוב את הפקודה הבאה יחד עם הקלט מהפקודה הקודמת -

```bash
readlink -f <previous_command_output>
# Example Output: 
# /usr/lib/jvm/java-17-openjdk-amd64/bin/java  
```

* להוסיף את הנתיב כמשתנה מערכת -
    * יש להיכנס לקובץ `/etc/environment` בתור sudo
    
    ```bash
    sudo vi /etc/environment  
    ```

    * יש להוסיף את המשתנה JAVA_HOME יחד עם הפלט מהפקודה הקודמת (הנתיב המלא) בפורמט הבא -

    ```bash
    JAVA_HOME="<previous_command_output>"
    ```

* יש לפתוח **טרמינל חדש**  ולהריץ שוב את [הפקודה לאיתור התקנת Java](#1-בדיקה-האם-מותקן-java-על-המחשב)

</div>