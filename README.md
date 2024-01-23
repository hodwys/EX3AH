# EX3AH
Link to itch:
[https://m-h-a.itch.io/ex3a]



בחלק א' בחרתי בשינוי "השחקן לא יכול לירות לייזרים בלי הפסקה, אלא חייב לחכות זמן מסוים בין ירייה לירייה הבאה".
בשביל לבצע שינו זה קודם כל הייתי צריכה להוסיף משתנה המגדיר לי את הזמן שאני רוצה לחכות בין היריות, ומשתנה בוליאני האם אני כרגע מחכה או לא.

הוספת המשתנים:
![image](https://github.com/hodwys/EX3AH/assets/92233601/d65eaa64-913d-4c0c-bcb5-88377b2c186f)

לאחר מכן הופסתי פונקציה שכל מטרתה היא לחכות את הזמן המוגדר.

הפונקציה:
![image](https://github.com/hodwys/EX3AH/assets/92233601/7650c0f1-920e-4341-a01a-820d7dfef754)

הפונקציה update מטרתה לראות אם לחצתי את המקש המפעיל את הירייה (יצירת הלייזר).

הפונקציה:
![image](https://github.com/hodwys/EX3AH/assets/92233601/3492a405-90cb-45b8-b31e-2373583f3b67)

ועל מנת לחכות את הזמן המוגדר בין היריות הייתי צריכה להוסיף לפונקציה spawnObject כמה שינויים.

הפונקציה:
![image](https://github.com/hodwys/EX3AH/assets/92233601/eef19150-8708-4d98-9a1a-170a49074bc4)

השינויים:
1. קודם כל אני בודקת אם אני במצב של לחכות או לפעול. 
2. אם אני במצב של לפעול (לא מחכה) אני מבצעת את הפונקציה כרגיל (מיצרת את הלייזר) ואחרי היצירה קוראים לפונקציה wait (לאחר שיצרנו לייזר אנחנו רוצים לחכות) ולבסוף מחזירם את הלייזר שנוצר.
3. אם אני במצב של לחכות אני לא מבצעת כלום אלא רק מחזירה null.

חלק ב':
בחלק זה בחרתי להוסיף גבולות למשחק שהשחקן לא יוכל לגעת בהם וכך מקשה על המשחק, במידה ושחקן התנגש עם הגבולות (קירות) השחקן נעלם והמשחק נגמר.
בקוד הוספתי משתנה של סוג האויב החדש :

![image](https://github.com/hodwys/EX3AH/assets/92233601/87752ea9-107e-4327-8c78-26b6fbcb635a)

בפונקציה של הטריגר בדקתי אם הוא מהסוג שהוספתי ואם כן אז השחקן מושמד.

![image](https://github.com/hodwys/EX3AH/assets/92233601/adb2e258-fc6f-47ae-b191-ec27091e6cec)











