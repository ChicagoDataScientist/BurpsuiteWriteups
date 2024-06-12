up:[[WebSecurityAcademy]]

# Lab: SQL injection UNION

[Click here for lab](https://portswigger.net/web-security/sql-injection/union-attacks/lab-determine-number-of-columns)

First, access the target web page in the Burpsuite Browser

![[Pasted image 20240612150401.png]]

Click on a category to create an sql query. Here, I selected "gifts"

Here is the "gifts" page

![[Pasted image 20240612150517.png]]



![[Pasted image 20240612150920.png]]
You can see the "Gifts" filter from the SQL Query created

RIght click on that and select "send to repeater"
![[Pasted image 20240612151116.png]]

![[Pasted image 20240612151226.png]]

add a tick mark to see if there is an sql injection vulnerability
