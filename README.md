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
| 4. | View, sort and search for dish idea with out registration | View and search for idea of recipe is provided by clicking button recipe at the top of the page in navbar. <br/>- Users can search the recipe after open the recipe view on the top. <br/>- Searching by type, ingredient, country origin. |
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

+ ***Navigation Bar***

The navigation bar works as intended. When you press on the website name it brings you directly to the home page. When you press on home it brings you to the home page. When choosing the recipes, it brings you to the recipe page. Log in brings the user to a page where he/she can log in and register brings you to page where you can create an account. After successfully logging in 3 more options will appear in the form of profile, new recipe and log out.

+ ***Home page***

On the home page there is several graphics which can be scrolled up and down. There is also some information describing what the webpage includes. There is also several drop-down texts. When chosen the text will appear and when you press on a different one the pervious one disappears. There is also a link which brings you to the recipe page. 

+ ***Recipe page***

When the recipe page is opened all the available recipes appear. The search bar works as intended and upon typing a keyword matching results will show up. When you hoover over a recipe it is highlighted to indicate it. 
When you press the cook button on a chosen recipe it brings you to a page with all the details of the recipe along with an image of the finished dish. There are also 2 lists one with ingredients and the other with steps. Each list is functional, and each step or ingredient can be ticked off as you go to aid the preparation of a meal. 

+ ***Log In***

In the log in page on can put in his credentials and log into the website. If a field is left blank it will be underlined in red. If incorrect credentials are put in, you will be informed something went wrong and you will be told to check that the details put in are correct. There is also a link that will bring you to the register page if you do not already have an account.  

+ ***Register***
 
In the register page one can create an account by putting in a unique username and password. If a field is left blank it will be highlighted in red to indicate the missing credential. There is also a link that will bring you to the log in page if you already have an account.  

+ ***Profile page***

After successfully logging in the profile page will appear. In profile there will be a list of all the recipes the user has added. From here the user can edit or delete any existing recipes. 

+ ***New Recipe***
 
After logging in the new recipe page will appear. Here the user can add a new recipe to the website. 

+ ***Log out*** 

When the user presses log out it successfully logs the user out and the 3 options from the navigation bar which are only available to users will disappear. 

## Features left to implement
1. In respond to the user needs sorting will be added in the future.
2. In respond to the user needs commenting recipes will be added later.
3. Power user account will be added for full control of editing.
4. Change login and register tab for modal/popup window.
5. Add rating option for recipes.

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
<details>
   <summary>Validation</summary>
   
1. [**To validate Html**](https://validator.w3.org/)
Walidated on Herroku app
   + Warnings:
      - Section lacks heading
   
   + Error 1:
      - Attribute 'target' not allowed on element img. 
      - Attribute 'right' not allowed on element i.
   + Error fix:
     - Bough errors fixed in commit: bae6d01831f4ee205f14553d4515534492b9ba8b

2. [**To validate CSS**](https://jigsaw.w3.org/css-validator/)

   No Error Found.
   
3. [**To validate Js**](https://jshint.com/)
   + Warnings:
      - line 14	'let' is available in ES6 (use 'esversion: 6') or Mozilla JS extensions (use moz).
      - line 15	'let' is available in ES6 (use 'esversion: 6') or Mozilla JS extensions (use moz).
  
      Warnings not affecting functionality

4. [**To validate Python using PEP8**](
   + Errors:
      - E125:80:5:continuation line with same indent as next logical line
      
</details>
<details>
   <summary>Lighthouse</summary>
   
   + Home
<img src="https://images92.fotosik.pl/503/b5c82fc533d320d6.png">

   + Recipes
<img src="https://images89.fotosik.pl/503/75327c2fd5f35593.png">
   
   + View Recipe
<img src="https://images91.fotosik.pl/502/2e67fe261d385602.png">
</details>
<details>
   <summary>Errors and fix</summary>
1. List of Ingreadients, steps and preparation not display correctly - issue fixed in commit:c84b4ed79ab12eec94c8c9b2380fc15c8d32c8c4
2. E125:80:5:continuation line with same indent as next logical line - For future fix
</details>
<details>
   <summary>Bugs and Problems</summary>
</details>

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
1. 404 templates and CSS style was made by Colorlib (https://colorlib.com)
2. Images 
   + recipes
      + Caramelized pear with ice cream - https://www.targislubne.pl/sn/media/foto_artykuly/agnieszka_kowal/karmelizowana_gruszka/strefa_narzeczonych_karmelizowana_gruszka_z_lodami.jpg
      + Spicy Cajun Chicken - https://smaker.pl/przepisy-dania-glowne/przepis-pikantny-kurczak-cajun-obiad-w-30-minut,124711,codziennik-kulinarny.html
      + Pasta with salmon and spinach - https://smaker.pl/przepisy-dania-glowne/przepis-makaron-z-lososiem-i-szpinakiem,109588,mimiwiki.html
3. Thank you to the tutors Alan and Jo for their patient help in solving the problem.
4. Thank you to my mentor Adegbenga Adeye for his help and interest in my project
