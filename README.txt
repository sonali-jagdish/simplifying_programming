NAME:SONALI JAGDISH
USN:1PI12IS107


Question 4
Consider a share market bazaar where the value of stocks keep going up and down. Write aprogram that asks for a company’s name and it’s share’s cost.
 The program should then usethese inputs and update the entry in the csv file which is in the following format
Company1,ShareValue1
Company2,ShareValue2
Company3,ShareValue3…
Eg:Google,123.45
Facebook,70.42
Apple,480.36
So when a user enters “Facebook,99.2”, the 
share value next to Facebook should be updated to99.2 and the csv file should then read as the following:
Google,123.45
Facebook,99.20
Apple,480.36

We have three members in our team.We were not able to combine 2 logics so we have written 2 codes and so attached 2 files-
i) asn2_4.c 
 This file appends the company name and share value at the end of the file but it doesn't read the text file.
ii)trying.c
 This .c file checks given company name with each line and runs into an infinite loop,but it doesn't append Company,ShareValue if the companyname is not found 
 in the csv file.The function here used is int match(char *x,char*y) which takes 2 strings and returns the position where it is found.
 
We tried to combine them but couldn't find any way to do that.Hence,attached 2 .c files 
