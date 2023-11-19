# Excel-Raw-Data-to-Dataset.
All changes was made in the Working sheet tab.

- Clarity was absent in the initial raw dataset, necessitating a significant cleaning step to improve comprehension and usage.

- In Excel Project dataset file, i started to clean the data by filtering so i can know what i am dealing with.

- Then I check for duplicates, to avoid any errors.

- The columns Marital Status and Gender, M is repeated. It might be confusing to understand, therefore Ctrl H to find and replace values. In Marital Status M is for Married and S is for single, while in gender column F is for Female and M is for Male, data clearing can be found in the working sheet tab.

-The Income Column, I made sure it was set to currency and removed the decimals.

- I've added a age brackets colume, because the age colume will be confusing when doing pivot tables like shown in pivot table tab.

- In order to make the age more easier to understand, I did the IF Statement on the age brackets column.
 =IF(L2>54, "Old",IF(L2>=31, "Middle Age",IF(L2<31,"Adolescent","Invalid")))  The IF statement states that, the ages over 54 is condidered old, if over 31 til 53 is condsidered Middle age, and if less than 31 is considered Adolescent.

- I added a Nested IF statement on the IF statement above as shown, it means that one IF function inside of another, this allows me to test multiple criteria at once. =IF(L2>=31, "Middle Age",IF(L2<31,"Adolescent","Invalid")) This was the Nested IF Satement.


- Created some pivot tables that makes sense.

- Made sure in the pivot tables the rrowas are in order to avoid any confusion and to make the data more neat.

- In the pivot table tab, as you can see if i didnt do the IF statement on the age bracket then we would have a messy data to deal with. As shown in the last pivot table on the pivot table tab.

- Created a Dashboard for this data set using slicer, and reporting connections to the pivot table. That way this will be the easiest way to understand the data, which you can target people depending on what you desire, Ex: I want to know the income of married people in Europe that have a graduate degree. Then we can use the Slicer tabs to find the answer.



