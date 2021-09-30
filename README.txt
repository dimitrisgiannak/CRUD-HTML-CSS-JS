                   Assignment : produce web pages with HTML/CSS/JS

 We needed to provide forms for Courses , Trainers , Students , Assignments and each one
had their very own specific fields. Also we needed to implement the functionality CRUD.
Having no database means that each time we reload a page or redirect to another the inputs
will be lost.
 
 Each Trainer , Student , Assignment has his own Course. Assignments also have a relation
of Assignements per Student per Course. The unique "key" for Trainers and Students is their
ID. Assignment and Courses have their title.(we acted like we had a database)
So in order to relate them we will use only those "keys".

 We also needed to add the required validations on all the forms we provided , e.g. size,
input type,valid value etc.

 To make it a bit more realistic we act like we have created a superuser account and we log 
in. We are redirected on the homepage , but only the admin can see the admin button on the 
right top of our homepage. It redirects us to the admin page and there we choose which form
we want to edit , delete.(homepage original template is added in the folder named delex to see 
before and after configurations). We have the option to return to the homepage. We also implemented 
a simple function to show the date top left. 

 We used bootstrap for navigation bars , forms , buttons with some tweaks. Homepage css and js
are on their own folders since the template was not ours. (we tweaked a lot as you can see)
All other pages have either inline or internal css.

 I used vscode to develop the project. If you want to use the same editor you need to download
Live Server extension. I did so because you can see the changes without refreshing the pages.
Since its only HTML files though you can simply double click on register.html file to start.



 

