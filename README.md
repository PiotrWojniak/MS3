# Simple cooking - easy and quick recipes 

Code Institute - Milestone Project 3

The assumption of the project is to show users how to prepare a meal easily and quickly. The recipes presented on the website contain information about which country they come from, what ingredients we need, a detailed description of how to prepare the dish and what equipment and utensils we need.

# ***Website Showcase***
---
# ***UX***

+ ## Project goals

The aim of the project is to allow users to view and share their own recipes and to present the user with the benefits of the zero west technique.

+ ## User Stories

|    | As a visitor I'd like to: | Respond to the expectation |
-----|---------------------------|----------------------------|
| 1. | Get easy and clear navigation between function | Switch between the functionality is provide by links button located on the top of the web page in navbar.|
| 2. | Find inspiration for meal | The site presents different types of meals with different ingredients in the recipes tab. |
| 3. | Know how to be more ecologically | ecological expectations are presented using zero waste techniques. |
| 4. | View, sort and search for dish idea with out registration | View and search for idea of recipe is provided by clicking button recipe at the top of the page in navbar. <br/>- Users can search and sort the recipe after open the recipe view on the top. <br/>- Searching and sorting is by type, ingredient, country origin. |
| 5. | Create an account to comments and shere my own recipe | Registration if providing by button login/register located in navbar. |
|    | __As a registered user i'd like to:__ | |
| 6. | Add, edit or deleting my recipe. | After logging in to the website, the user can add recipes after clicking the add recipe tab. <br/>- Adding and removing recipes posted by the user is possible after selecting the profile option, which is on the navigation bar. |
| 7. | I would like to make sure that no other user can edit or delete my recipes. | The user may edit and delete recipes only and exclusively added by himself. It is not possible to use these options in other users' recipes. Only Admnin can moderate all data input to eliminate any profanity. |
|   | __As a admin i'd like__ |  |
| 8. | Only the administrator can moderate user input. The purpose of this assumption is to eliminate profanity that may appear in the comments or in the recipes themselves. | Only the administrator can moderate user input. The purpose of this assumption is to eliminate profanity that may appear in the comments or in the recipes themselves. |
| 9. | Admin can add or change categories as needed. | Admin can add or change categories as needed.|

---
# ***Design***

+ Side map
<img src="https://images91.fotosik.pl/495/835d72ca684976fa.png">

### Colours

<img src="https://images92.fotosik.pl/496/d88fb2875b95a555.png">

+ Aero Blue #D6FFDC - Main background color
+ Lemon Yellow Crayola #FFFFB0 - Cards and brand background color
+ Gunmetal #2E3340 - Default font color
+ Duke Blue #0300A3 - Headings color
+ Blood Red #680000 - Navbar, footer, separator brand font colour

### Font
+ Irish growing - to set logo name
+ Roboto Slab - to set as default style
+ Bodoni Moda - to style inside button text and navigation bar menu.

### Wireframe
The wireframe model is created as part of the project planning. Its task is to graphically present the appearance of the application on three different devices: computer - high resolution, tablet - medium resolution, telephone - low resolution. The application will be built on the basis of the created sketch

<details>
   <summary>Home</summary>
   <img src="https://images89.fotosik.pl/496/1c97f88843e4117d.png">
</details>
<details>
   <summary>Zero waste</summary>
   <img src="https://images92.fotosik.pl/496/b5eeade1b3af3097.png">
</details>
<details>
   <summary>Recipes</summary>
   <img src="https://images91.fotosik.pl/495/6665b81495e77f77.png">
</details>
<details>
   <summary>Registration/Login</summary>
   <img src="https://images90.fotosik.pl/495/c5a11a229b49f7d3.png">
</details>
<details>
   <summary>Add recipes</summary>
   <img src="https://images91.fotosik.pl/495/abbc2ee9175d7b15.png">
</details>
<details>
   <summary>Profile</summary>
   <img src="https://images89.fotosik.pl/496/f5b9f0f2bab88b68.png">
</details>
<details>
   <summary>Edit</summary>
   <img src="https://images91.fotosik.pl/495/a21c5e0cc25c8c08.png">
</details>

---
# ***Features***

## Existing features


## Features left to implement
---
# ***Technology***
<details>
   <summary>Languages</summary>

+ <img src="https://img.icons8.com/color/48/000000/html-5--v1.png"/> [HTML](https://en.wikipedia.org/wiki/HTML) - to creating structure and layout of the webpsite.
+ <img src="https://img.icons8.com/color/48/000000/css3.png"/> [CSS](https://en.wikipedia.org/wiki/CSS) - to styling the HTML.
+ <img src="https://img.icons8.com/color/48/000000/javascript.png"/> [JavaScript](https://en.wikipedia.org/wiki/JavaScript) - to interactive web applications.
+ <img src="https://img.icons8.com/color/48/000000/python.png"/> [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) - to run queries to the database.
</details>
<details>
   <summary>Frameworks, Libraries & Programs</summary>
   
+ <img src="https://images91.fotosik.pl/495/94f9449ae6eadb99.png"/> [Jinja](https://en.wikipedia.org/wiki/Jinja_(template_engine)) - as a templates engine for Python.
+ <img src="https://images92.fotosik.pl/496/ff9586f55010cb7e.png"> [Flask](https://en.wikipedia.org/wiki/Flask_(web_framework)) - Flask running a Python server-baced project and depends on the Jinja template engine and the Werkzeug
+ <img src="https://images92.fotosik.pl/496/0e0b55372d3fa10f.png"> [Werkzeug](https://werkzeug.palletsprojects.com/en/1.0.x/) - to handle various utilities for WSGI applications, it comes with simple-to-use Security features
+ <img src="https://img.icons8.com/color/48/000000/mongodb.png"/> [mongoDB](https://en.wikipedia.org/wiki/MongoDB)  - NoSQL database used for backend database
+ <img src="https://images90.fotosik.pl/495/31f55faa8a7f0f25.png"/> [Materialize](https://materializecss.com/) - Used for responsive design and conforming to the Google material design language. 
+ <img src="https://images91.fotosik.pl/495/ff7e331eae631581.png"> [JQuery](https://en.wikipedia.org/wiki/JQuery) - is a JavaScript library designed to simplify HTML DOM tree traversal and manipulation
+ <img src="https://images90.fotosik.pl/496/0bfff63014e8ea32.png"> [RandomKeygen](https://randomkeygen.com/) - to generate password for flash and session function of flask
+ <img src="https://images90.fotosik.pl/496/9090f1a039521721.png"> [Heroku](https://en.wikipedia.org/wiki/Heroku) - as a deploying cloud platform to supporting several programming languages
+ <img src="https://images91.fotosik.pl/495/349a636c9586126b.png"> [GitHub](https://en.wikipedia.org/wiki/GitHub) - to create and host project
+ <img src="https://images89.fotosik.pl/496/b2208ad81e139641.png"> [Balsamiq](https://en.wikipedia.org/wiki/Balsamiq) - to create wireframes during design process
+ <img src="https://images90.fotosik.pl/496/ded7f996b572ca06.png"> [Favicon](https://favicon.io/logo-generator/) - for logo generator
+ <img src="https://images91.fotosik.pl/495/b1d4fe3fd419b9da.png"> [Google font](https://fonts.google.com/) - for font style.
+ <img src="https://images92.fotosik.pl/496/98be9f646b97e1fa.jpg"> [Visual studio](https://visualstudio.microsoft.com) - console for writing code.
</details>

---
# ***Testing***

### To validate Java Script.
##### Warnings.

### To validate CSS
##### Warnings

### Lighthouse

### Errors and fix

### Bugs and Problems

 ---
# ***Deployment***

## To create a repository:
1. Go to the GitHub web page and login.
2. Click Repository on the right side of the profile.
3. Click New green button on right side.
4. Inside Create a new repository.
   + Choose your repository name.
   + Choose Public that anyone can view the repository or Private and choose who can see and commit in to the repository.
   + Choose the option in Initialize repository and add Readme, .gitignore and license if you not importing from existing repository.
5. Click create repository button on bottom.

## To deploy a website on GitHub Pages, follow these steps:
1. Go to the repository page
2. Click on settings icon in the top of the page
3. Find "GitHub Pages" section
4. Click on the "Source" dropdown menu
5. Select "master branch" option
6. A green success message should appear in the "GitHub Pages" section with the link to the live preview of the project.

## Heroku
---
# ***Credits***
