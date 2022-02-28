# C-Sharp_MVC_LiveProject

For the last couple weeks of my time at the Tech Academy I had the opportunity to work on a live project with 4 others to create a website using Entity Framework as well as MVC and Visual Studio. I worked on a team to create a theatre website with producion members,photos, sponsor pages, and much more. The code base was C# but used razor through the html to excute C# code as well as Bootstrap and CSS to style the pages based on the client's preferences.

Below are descriptions of some of the stories/assignments that I worked on with some code snippets and links. I also have some full code files in ths rep for the larger funcionalites I implemented. 

# Front End Stories

Home page Styling

![image](https://user-images.githubusercontent.com/6036522/155783777-26de6bd5-e7a0-4914-b1ae-e4a87c393a67.png)

I had the opportunity to help design and structure the home page with links to sponsor pages as well as formating the produciton phtotos and styling the layout using 
Bootstrap 4. 

Organization and layout of the production photos index page

![image](https://user-images.githubusercontent.com/6036522/155783791-2227dfa9-84e7-4d12-bd32-ba3927a0976e.png)

![image](https://user-images.githubusercontent.com/6036522/156050976-80f90930-356a-48b7-94ca-e33a5a13bf3c.png)


Image Preview

![image](https://user-images.githubusercontent.com/6036522/155783871-4b9906b8-ccc4-43a5-adda-3f9c32569fab.png) 

![image](https://user-images.githubusercontent.com/6036522/156050860-01f33824-add4-4abb-aca9-f37383dd28a4.png)

![image](https://user-images.githubusercontent.com/6036522/156050782-5299892c-5c56-4b9a-a057-6ea26d63d6bd.png)


On the Creation page allowed the preview of the image to be uploaded using JavaScript

# Back End Stories

Image Conversion to byte array for storage

![image](https://user-images.githubusercontent.com/6036522/156054334-22845577-dfd3-40bd-b72e-00083a7cdb03.png)

Created a method to convert images uploaded by the users for the produciton photos that then allow for the storage of them in the database as a byte array. Then created a method to retrive the image and convert it back to be displayed on the index and details pages. 

Entity Framework and CRUD Pages

![image](https://user-images.githubusercontent.com/6036522/156051713-29b980af-26a1-4a9c-8db6-f1c7f58b11d2.png) ![image](https://user-images.githubusercontent.com/6036522/156051849-3fd52897-bd38-4bc6-be35-3fe94632b918.png) ![image](https://user-images.githubusercontent.com/6036522/156051904-001f71f3-b957-4fd2-bdb5-4bab7f7a455e.png)




Utlizing Entity Framework for Database CRUD pages and modifying the properties to create a database with different variables from byte arrays to titles and descriptions.

