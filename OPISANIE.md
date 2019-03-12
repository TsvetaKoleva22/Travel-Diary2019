Project Presentation
in compliance with ReactJS Course Project Assignment

The project is a single-page web application created using React.js library for the user interface and a local server build using Node.js and MongoDB for the back-end. It supports error handling and data validation and uses React Toastify to show the corresponding notifications. The client-side routing uses React-router-dom, and the styling is enhanced with the help of Bootstrap.  

The app is a kind of blog system where keen travelers can share their exciting adventures like travels to exotic destinations or amazing discoveries closer to home.  

There are three main parts:  
1. Public part, which is accessible to everyone, without authentication. Every visitor can:  
- view the About page (by clicking the compass logo); 
- view the Home page, with a welcome message, shortcut buttons to the Log in and Register pages and the three most recent adventures (posts); 
- view all available posts by visiting the All Adventures page; 
- view details about each post by clicking its Details button and thus visiting the Details page; 
- log in using the Login page (if he already has an account for our application), or
- register using the Register page 

2. Private part – only for logged in users. After successful registration the user is automatically logged in.  Now he can use the full functionality of the app: 
- view the Home page, About page, All Adventures page and Details page for each post; 
- create new adventure using the Create New Adventure page; 
- view his own posts by going to My Posts page; 
- edit each one of his posts (only his) by clicking the Edit button under the post and visiting the Edit Adventure page;  
- delete any of his posts (again only his) by clicking the Delete button under the post and visiting the Delete Adventure page; 
- logout. 

3. Administrative part - only for admins. When the database is initiated for the first time, the server automatically seeds a user with username Admin, password Admin123 and role Admin. He has the following functions:  
- view the Home page, About page, All Adventures page and Details page for each post; 
- create new categories for the adventures using the Create New Category page; 
- view all created categories in the All Categories page; 
- he can delete any of the posts when he goes to the Details page, if he finds that the post is inappropriate for the app. 
- he cannot create posts or edit the existing ones.  

The app has the following dynamic pages: 
1. Home page - displays a welcome message, shortcut links and the three most recent posts; 
2. All Adventures - shows all available posts, each in a separate container, with its image, title, destination, author and date of creation; 
3. Add Adventure - a form with five fields - 3 input fields for title, imageUrl and destination, a textarea for the description and a select field for the category, with options corresponding to all available categories, created by the admin.   
4. My Posts - shows only the posts of the currently logged in user in a format, similar to the all posts view.  
5. Details - gives detailed info for the selected post, showing the author’s description of the adventure;
6. Edit - a form with four fields, that are prefilled with the current info for the post. It allows the user to change the title, image, destination and/or description of the adventure;
7. Delete - shows the image of the post and a form with two disabled prefilled fields - title and destination. Allows the user to permanently delete his post.  
8. Create Category - for Admin only. A form with one field for the name of the new category. 
9. All Categories - for Admin only. Shows all available categories. 

Additionally the app offers Login page, Register page, About page, Not Found page (if no available route is matched) and a Logout option. 