# CodePath_Week8
# Week 8 Project: Pentesting Live Targets
Time Spent: Around 4 Hours 
Objective: Identify vulnerabilities in three different versions of the Globitek website
##Challenge 1: Username Enumeration
Vulnerability Website Color: Green
Vulnerability Info : If user enters a known username like "jmonroe99" the error message will be in bold however if the user enters a random username then the error message will not be in bold. 
Link to GIF : https://imgur.com/a/ywIFb

##Challenge 2: Insecure Direct Object Reference 
Vulnerability Website Color: Red
Vulnerability Info : When you go to the salesperson page each person has a ID. The range goes from 1 - 9. However if you enter 10 or 11 you will see pages thats not meant for everyone.
Link to GIF : https://imgur.com/a/M4CTX

##Challenge 3: SQL Injection 
Vulnerability Website Color: Blue
Vulnerability Info : When you enter ' OR SLEEP(5)=0--' after the url of a salesperson besides Daron Burke, the site reloads for 5 seconds and redirects you to the first salesperson which is Daron Burke.
Link to GIF : https://imgur.com/a/lzXJk

##Challenge 4: Cross-Site Scripting 
Vulnerability Website Color: Green
Vulnerability Info : When you go on the Contact page and enter <script>alert('Brandon found the XSS!');</script> in the feedback area. Then hit submit, next when you click on feedback the alert will pop up.
Link to GIF : https://imgur.com/a/tfxvf

##Challenge 5: Cross-Site Request Forgery 
Vulnerability Website Color: Red
Vulnerability Info : By using a tool like Burp Suite you can capture a post request and edit it so that its possible to add another user.
Link to GIF : https://imgur.com/a/921ti 

##Challenge 6: Session Hijacking/Fixation
Vulnerability Website Color: Red
Vulnerability Info : By using the "public/hacktools/change_session_id.php". You can load this script to find out the current session ID or to set it to a new one.
Link to GIF : https://imgur.com/a/fR3kC

