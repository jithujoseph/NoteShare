Notes on projects details
=========

#Database TABLES 
#####notetakers
id (bigint 32)(primary), name(varchar 41) , username(varchar 64) , password (varchar 128),  
<br>
#####notes
id (bigint 32)(primary) , course_id(forign key) , notetaker_id(forign key ) , topic , file_link

<br>
#####courses
id (bigint 32)(primary), codename(varchar 10) , name(varchar 41)

<br>
#####students
id (bigint 32)(primary) , name(varchar 41) , username(varchar 64) , password (varchar 128),  

<br>
