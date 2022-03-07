משום מה לא הסתדר לי בריפו הקודם עם השינויים אז אם יש צורך לראות את ההסטוריה של העבודה שלי 
זה הניסיונות הקודמים

![image](https://user-images.githubusercontent.com/62290677/157093501-5dc81461-515d-4655-b03f-e65ed5a432f8.png)

- https://github.com/dolev146/cpp-ex1.git
- https://github.com/dolev146/cpp-first-exercise-matress.git



<div dir="rtl" lang="he">

# יצרני השטיחים

כיתבו תוכנית העוזרת למנהל המפעל לתכנן את השטיחים שלו!  
פירוט מדוייק של קלטים ופלטים נמצא כאן:
https://codegolf.stackexchange.com/questions/241219/mat-printing-matrix

כדי לראות איך הפונקציה אמורה לעבוד, ראו בקובץ
[Demo.cpp](Demo.cpp)
המצורף.

בשלב א עליכם לכתוב את הקבצים הדרושים כך שהפקודות הבאות יעבדו ללא שגיאות קימפול:

<div dir='ltr'>

    make demo
    ./demo
	make test
    ./test

</div>

עליכם לכתוב את  הקבצים הבאים:

* mat.hpp - כותרות לפונקציות שבתכנית.
* mat.cpp - מימוש בסיסי של הפונקציות - לא חייב להיות מלא - צריך רק להתקמפל.
* Test.cpp - בדיקות-יחידה בפורמט doctest. יש לכתוב בדיקות מפורטות ולהתייחס למקרי קצה.
   * ניתן לראות דוגמה לבדיקות בקובץ TestExample.cpp, אבל יש לכתוב הרבה בדיקות נוספות.
   * במטלות בקורס זה אנחנו כותבים את הבדיקות לפני המימוש, ולכן רוב הבדיקות ייכשלו וזה בסדר - המימוש המלא ייכתב בחלק ב של המטלה.

מומלץ לוודא שהפקודה הבאה רצה ללא אזהרות (כדי להריץ יש להתקין את  clang-tidy):

<div dir='ltr'>

    make tidy

</div>

שימו לב:
אין לשנות קבצים קיימים, אלא רק להוסיף קבצים חדשים.
מערכת הבדיקה האוטומטית מעתיקה מחדש את כל הקבצים הקיימים על-גבי הפתרון שאתם מגישים,
ולכן כל שינוי שתעשו בקבצים הקיימים יימחק.

</div>
