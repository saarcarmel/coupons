פרוייקט מלווה
מערכת ניהול קופונים

John Bryce

קורס 822
הסבה לתכנות Java
לסביבות
Client, Enterprise
ו-Big Data

סער כרמל
 
 
 
תוכן:

1.	התקנה
2.	שמות משתמשים וסיסמאות
3.	נתוני התחברות ל-DataBase
4.	הנחיות למשתמש
 
1. התקנה
1.	JDK
2.	JRE
3.	Eclipse
4.	MySQL Database
2. שמות משתמשים וסיסמאות
AdminFacade
username - admin
password - 1234
3. נתוני התחברות ל-Database
Relational Database Management System  - MySQL
username - root
password - root
Tables:
1.	Company
2.	Coupon
3.	Customer
Join Tables:
1.	Company_Coupon
2.	Customer_Coupon
 

4. הנחיות למשתמש:
פרוייקט Coupons
חבילה test
קובץ מקור Test.java
קובץ bytecode : Test.class
הקובץ Test.java  מכיל את השיטה main אשר מפעילה את התכנית.
יש להדר את הקובץ Test.java
ולהריץ את הקובץ Test.class
 
פירוט השדות בטבלאות:
1. Company - טבלת חברות
1.	ID - LONG, PK
2.	COMP_NAME - STRING
3.	PASSWORD - STRING
4.	EMAIL - STRING
2. Customer - טבלת לקוחות
1.	ID - LONG, PK
2.	CUST NAME - STRING
3.	PASSWORD - STRING
3. Coupon  - טבלת קופונים
1.	ID - LONG, PK
2.	TITLE - STRING
3.	START_DATE - DATE
4.	END DATE - DATE
5.	AMOUNT - INTEGER
6.	TYPE - ENUM (STRING)
7.	MESSAGE - STRING
8.	PRICE - DOUBLE
9.	IMAGE - STRING
4. Company_Coupon - טבלת חברות-קופונים
1.	COMP_ID - LONG
2.	COMP_ID - LONG
5. Customer_Coupon - טבלת לקוחות-קופונים
1.	CUST_ID - LONG
2.	COMP_ID - LONG
