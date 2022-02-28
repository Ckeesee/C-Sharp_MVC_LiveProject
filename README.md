# C-Sharp_MVC_LiveProject

For the last couple weeks of my time at the Tech Academy I had the opportunity to work on a live project with 4 others to create a website using Entity Framework in tandem with a Model-View_Controller (MVC) web application within Visual Studio. I worked on a team to create a theatre website with production members, photos, and sponsor pages. I used C# as the code base but used Razor syntax through the html to execute C# code. I then would style the pages with Bootstrap 4 and CSS based on the client's preferences. Everyone on the project had the chance to work on both front and back end stories over a two week sprint. The sprint was part of an Agile Scrum methodology for the site development as well as we used Azure for DevOps. Azure allowed for the instructors to explain, teach, and use version control through Git.

Below are descriptions of some of the stories/assignments that I worked on with some code snippets and links. I also have some full code files in this repo for the larger functionalities I implemented. 

# Front End Stories

- [Home page Styling](https://github.com/Ckeesee/C-Sharp_MVC_LiveProject/edit/main/README.md#home-page-styling)
- [Organization and layout of the production photos index page](https://github.com/Ckeesee/C-Sharp_MVC_LiveProject/edit/main/README.md#organization-and-layout-of-the-production-photos-index-page)
- [Image Preview](https://github.com/Ckeesee/C-Sharp_MVC_LiveProject/edit/main/README.md#image-preview)

### Home page Styling

![image](https://user-images.githubusercontent.com/6036522/155783777-26de6bd5-e7a0-4914-b1ae-e4a87c393a67.png)

I had the opportunity to help design and structure the home page with links to sponsor pages as well as formatting the production photos and styling the layout using 
Bootstrap 4. 

### Organization and layout of the production photos index page

![image](https://user-images.githubusercontent.com/6036522/155783791-2227dfa9-84e7-4d12-bd32-ba3927a0976e.png)

![image](https://user-images.githubusercontent.com/6036522/156050976-80f90930-356a-48b7-94ca-e33a5a13bf3c.png)

I was tasked with creating and modifying the Index page of all the production photos. I utilized the card format in boostrap as well as the pill boxes for links. Then created a grouping for each production title so that the photos would be displayed together so long as they were titled the same. I utilized the groupby function within Razor and the DisplayFor methods to display all the elements of the database to the Index page. 


### Image Preview

![image](https://user-images.githubusercontent.com/6036522/155783871-4b9906b8-ccc4-43a5-adda-3f9c32569fab.png) 

![image](https://user-images.githubusercontent.com/6036522/156050860-01f33824-add4-4abb-aca9-f37383dd28a4.png)

![image](https://user-images.githubusercontent.com/6036522/156050782-5299892c-5c56-4b9a-a057-6ea26d63d6bd.png)


I am quite proud of the implementation of JavaScript for the image preview during the creation of a production photo entry. By using JavaScript in conjunction with Bootstrap I was able to get the image to preview before being saved to the database as a byte array and have the image scale with the window size using Bootstrap 4.

# Back End Stories

- [Image Conversion to byte array for storage](https://github.com/Ckeesee/C-Sharp_MVC_LiveProject/edit/main/README.md#image-conversion-to-byte-array-for-storage)
- [Entity Framework and CRUD Pages](https://github.com/Ckeesee/C-Sharp_MVC_LiveProject/edit/main/README.md#entity-framework-and-crud-pages)


### Image Conversion to byte array for storage

![image](https://user-images.githubusercontent.com/6036522/156054334-22845577-dfd3-40bd-b72e-00083a7cdb03.png)

Created a method to convert images uploaded by the users, for the production photos, that then allow for the storage of them in the database as a byte array. Then created a method to retrieve the image and convert it back to be displayed on the index and details pages. 

### Entity Framework and CRUD Pages

![image](https://user-images.githubusercontent.com/6036522/156051713-29b980af-26a1-4a9c-8db6-f1c7f58b11d2.png) ![image](https://user-images.githubusercontent.com/6036522/156051849-3fd52897-bd38-4bc6-be35-3fe94632b918.png) ![image](https://user-images.githubusercontent.com/6036522/156051904-001f71f3-b957-4fd2-bdb5-4bab7f7a455e.png)

I used the add on of Entity Framework in Visual Studio for Database CRUD pages creation. Then I modified the create and edit methods and made a database with the specific properties requested by the client with string variables of the title and description and a byte array to store the images.

