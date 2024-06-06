
Jishnu M(0852786)
 created on w/ VS2022 .NET 7


Recreated the ASP .NET MVC Core application
Using .Net 7,no authentication

1325
Accessed the URL and the default works :
https://localhost:7132/
Modified the index.cshtml title to MVC MOVIE by replacing the default title WELCOME

Created README.txt for documentation.



1332
confirmed Part1 of the tutorial is completed, Added a new controller as per the part 2

1350
Commented the default index method which is returning to class view()
Then added new index method and changed the content to This is my default helloworld page...
complied the code and confirmed the changes works:
The URL to confirm
https://localhost:7132/HelloWorld

1400
Added another method called welcome with the content of "This is my welcome page..."
Ran the program, Confirmed the changes works:
The URL to confirm
https://localhost:7132/HelloWorld/welcome


1430
Accessed the Program.cs file and checked the routing section.

1436
Welcome method was updated to include 2 parameters String and an integer

Accessed the URL below and was working fine 

https://localhost:7132/helloworld/welcome?name=Jishnu&numtimes=5

1506

Welcome method was updated again to include 2 parameters with below arguments

 Welcome(string name, int ID = 1)


Made the changes and accessed the below working URL
https://localhost:7132/helloworld/welcome/852786?name=jishnu


2024-05-23

1355
HelloWorld Controller class was edited and replaced the Index code with the code mentioned in the Turorial.

1358
Created a new folder called "HelloWorld" under the Views Folder

1400
A new empty Razer view was created under the Views/HelloWorld folder.
Edited the Index.cshtml and replaced the contents mentioned in the tutorial page.
Accessed the webpage and it was working fine with the changes made.

1422
Navigated to Views/Shared/_Layout.cshtml file to change views and layout pages.
Viewdata section has been modified and below are the details of the modification 
               
               Three events of Mvcmovies was updated to Movie App

Saved the changes and website reflected with the changes made.
https://localhost:7132/helloworld

1440

Navigated to Views/HelloWorld/Index.cshtml and made changes to the "Title" and <h2> section
Changes were made and URL https://localhost:7132/helloworld loaded fine with the changes made.

Below are the changes reflected in the website.

        Browser Title along with the Heading inside the webpage.

1520

Navigated to HelloWorldController page and updated the Welcome method.
Parameters called "name" and "numtimes" were added.

Accessed the URL https://localhost:7132//HelloWorld/Welcome?name=jishnu&numtimes=4  and the website was broken

1529

To add a new model class. I right clicked on "Models" and added a new class called "Movie.cs"
Updated the Models/Movie.cs file with codes in the tutorial page.

1540

Created a new Migration Timestamp
20240606151334_InitialCreate.cs

2024-06-06

0200

Opened the Controllers/MoviesController.cs and reviewd the file as per the documentation and understood that constructor uses Dependency Injection to inject the database context into the controller.

0204

Examined the database from the view menu. 
Accessed the dbo.movie database.

0208

Create a new class named SeedData in the Models folder and added the code from the instructions.
After adding the code I received an error An unhandled exception occurred while processing the request.
Updated the databases and the Website was loading fine.











