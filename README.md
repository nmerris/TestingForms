# TestingForms

This web app sets up a simple form that allows a user to enter an id and a username.
This data is then routed to the appropriate method in MainController.java.
Thymeleaf is used to marshall the data to a Greeting object, where it is automagically stored in
fields that correspond to special parameters in the html file.  The data is then sent back from 
the server to the web page, again using Thymeleaf, where it is displayed.
