<h1 align="cener">Interns Attendance</h1> 

------
<h2 align="center">OBJECTIVE</h2> 


<p align="center"><b>Calculate the attendance of Interns on the basis question raised by interns in mail.</b>
         
----

<h2 align="center">TEST CASES</h2> 

<h3 style="background-color:DodgerBlue;">Test Case 1</h3>
--To access mail in local system.<br>
**Activity**
--need to Access email Id through script.


**Coding**<br>
### Utility to read email from Gmail Using Python
ORG_EMAIL = "@fosteringlinux.com"<br>
FROM_EMAIL = "rohit.x.barwal" + ORG_EMAIL <br>
FROM_PWD = "password" <br>
SMTP_SERVER = "imap.gmail.com" <br>
SMTP_PORT = 993<br>
def read_email_from_gmail():<br>

**Input**
python3 /mnt/test1.py

**Output**
Access mail Sucessfully

----

**Test Case 2**
--To Search for email ID interns@fosteringlinux.com .<br>
**Activity**
--need to filter  particular email id  on which we are recieving emails from interns.

**Coding**
email_to = msg['to']<br>
print('To: ' + email_to + '\n')<br>

**Output**
Done Sucessfully

----

**Test Case 3**
--search for assignment subject.<br>
**Activity**
--need to filter mail with particular assignment subject.

**Coding**
email_subject = msg['subject']
print('Subject : ' + email_subject + '\n')

**Output**
Done Sucessfully

----

**Test Case 4**<br>
--To search the email by Name.<br>
**Activity**
--need to filter mail by particular name.

**Coding**
email_to = msg['to']<br>
print('To : ' + email_to + '\n')

**Output**
Done Sucessfully

-----

**Test Case 5**<br>
--To search the email by Date.<br>
**Activity**
--need to filter mail by Date wise.

**Coding**
email_Date = msg['Date']<br>
print('Date : ' + email_Date + '\n')

**Output**
Done Sucessfully

-----
        
    
