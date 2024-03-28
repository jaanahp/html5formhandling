**Assignment #1 - HTML5 Forms and Handling Form Input in JavaScript**

Make a web page, which contains a form with according labels and input elements:
```
* Full Name, a required text field with autofocus and placeholder, 60 characters size, max 80 characters
* Password, a required password field, accepts 8-20 characters: a-z, A-Z, 0-9 and following punctuation 
characters _,.-:;?!
* Password again, same specification as above, must match the above field in value
* Gender, required, radio selections, choices: male, female, other
* Hobbies, a checkbox selection (can select zero to many): games, music, sports, TV
* Birth Date, date field
* Height, a range input from 40 to 300 cm. A linked number field showing the numerical value and allow to input exact 
number. In other words both the number field and range field show the same value, changing one will automatically 
change the other.
* Favorite color, standard 24-bit RGB color selector,
* Home Country, selector with Finland as default choice, also include Russia and other Scandinavian countries and 
Baltic countries as possible choices.
* Profession, datalist, with at least 4 predetermined choice e.g. teacher, nurse, plumber and bureaucrat
* Message, a text area, which is required and is by default 6 rows high and 60 columns wide. With placeholder and max 
length for input set to 1000 characters.
```
There should also be a Send button. Pressing the button will validate the form and print out possible error messages if needed.

If everything is valid and all required fields are given, then it a JavaScript function will print out all the input values to an output field.

Use HTML5 form abilities to their fullest extend. Use regular expressions and/or pattern attribute to limit the password to certain length and characters.
