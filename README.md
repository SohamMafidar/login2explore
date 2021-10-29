# **Form Submission in JsonPowerDB** 

JsonPowerDb is a Rest API based Multimode database(supporting Document Db, Key-value Db, RDBMS etc)
http://login2explore.com/jpdb/docs.html

### The DBMS looks like this
![LX1](https://user-images.githubusercontent.com/66075716/139423909-f4c12cc2-3545-47ca-bb15-a69c947348a9.JPG)

### Sample Database
![LX2](https://user-images.githubusercontent.com/66075716/139423949-78979504-44dc-4fb5-97c4-184e328338f8.JPG)

## **Benefits of JBDB**
*It has a very simple way to retrieve data in a JSON format.
*Schema-free, Simple to use database.

### *Released project on (29-10-21)*

Here in this prjoect a simple form is created based on the above sample database.
Common js( a javascript library) is additionaly used to reduce overheads and fast executions.

![LX3](https://user-images.githubusercontent.com/66075716/139427192-25d9e9f1-2452-4e45-8b0c-bd73d0b1d8d4.JPG)


1. User enters his details and the form is then first validated( validateAndGetFormData() function) and converted into a string.
2. A PUT request is generated and the form is submitted ( executeCommandAtGivenBaseUrl function does it)using AJAX.
3. Finally form is reset so that user does not erroneously resubmit the form.
4. A popup is generated telling that the form was submitted corresponding to the connection token, database and relation.



