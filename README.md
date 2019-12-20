# Attendance_automation
Attendance automation is the project through which by clicking the picture of attendance sheet leads to the direct entry in the database and excel sheet.


Here,only the classification model is showed.You can integrate this with the app to make the attendance automation.
The image used to make the system has two type of small block based on the type the of block attendance of every student on every day is filled.The way of taking attendance is fixed.

The block is colored if the student is present and the block is blank if the student is absent.

After taking the image of sheet through app,the image can be send to the image processing model.
In this model the image is scanning to remove noise,extracting the relational row for every student,checking the rectangle block for every 
lecture and comparing the type of block to fill the attendance in the database and excel.
