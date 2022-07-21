# MyPlant-Testing

<h2>Unit tests</h2>

Implemented unit tests with PHPUnit and Codeigniter framework syntax. 

Focused on the methods and functions of individual page models. Specifically then for
Category, Comment, Post and User pages. There are also unit tests for
controller Welcome page of the CodeIgniter framework.

The models are then tested in 2 ways. The first are unit tests checking the return values from database. The second method uses mocking and testing to shield the database
only the function itself. The naming of the tests is based on the pages on which the tests are located
targeted.

<h2>Process/Integration tests</h2>

All process and integration tests are solved using the Selenia framework. 

The tests cover practically all the functionalities that the application offers. In practically all files, we have to log in due to system settings. Therefore, logging in is not mentioned further.
