# Guest House Booking System app
Web app which collects user data, writes it to a database and allows it to be edited.

A prototype app developed for a Guest House Booking System. The main purpose of this app is to let the user add, search and edit it  data to the database. Is only a prototype app, the visual appearance of the interface is not the main goal of this app at this point in time. 

The PHP files will need to access MariaDB database. The credentials can be found on your server home page and should be added to the file tma02_mydatabase.php

After adding your credentials to the file you will need to upload all the files to your server.

To add a new record to the database you will have to insert a First Name, Last Name, Email, and a Booking Reference. 

The file TMA02_.js has JavaScript client-side validation which checks if each field has the correct value before sending the data to the database. 

The fields 'First name' and 'Last name' permits only letters, numbers and spaces.

The field Email permits only valid email addresses, which means it must include a '@'. 

THe Booking 'Reference field' must start with a group of three letters, followed by a hyphen and then a four digit number, for example 'ABQ-1432'. All these requirments can be changed using RegExr. For more info visit https://regexr.com/ 

The file tma02_validatedata.php will make extra checks to see if is a valid booking reference. 
For a reference to be valid, the three letter group must be one of ‘ACT’, ‘ABQ’, ‘ ‘BDE’. Anything else is invalid.
Secondly, the first digit may only be 1 or 2. The other digits may be any value 0..9 inclusive.
Again, these requirments can be changed using RegExr. For more info visit https://regexr.com/ 




