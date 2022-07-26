# Blogging-WebSite
A Blogging Website Created using Angular

This project is an online blogging application website, which is capable of sharing view of different users on central matter and write comments with ease and free of cost. The aim is to provide users an interactive platform to blog and for organizations to automate their manual counterparts by the help of this Application, so that they can interact with their customers effectively. This website allows users to perform basic CRUD operations on Blogs and contains a fully-fledged text editor to style the blogs appropriately. The Tech-Stack of the project contains HTML, SCSS, JavaScript, TypeScript, Bootstrap & Angular in Front-End and Node-js & Google Firebase as Back-End as well as Database.

![image](https://user-images.githubusercontent.com/64099806/181011721-47f19e06-7da9-49ab-bbaa-64f16e12de2f.png)

**This comprises of the following properties: -**
1.	A cloud Database that stores the information of the users and their blogs.
2.	An online website that provides the ability to write or read blog between different users, this website is connected to the central database to fetch and store all       data. 
3.  Google Authentication for users
4.	Authenticated users can create their profiles and can post blogs and comments.
5.	Visitors can see the blogs and comments of all users.
6.	Website includes a bar containing links to all social media platforms, If visitor likes the post and wants to share the blog they can click on the icon of platform to   share on.
7.	Website also have a fully integrated text editor to make blogs attractive.
8.	Paginator module to define Number of blogs to be displayed on the screen.
9.	Administrators can Delete blogs and comments and can also edit the blogs.

**COMPONENTS & SERVICES**
1.	Author-profile: Creates author profile and shows that.
2.	Blog: Uploads and Fetch the blogs to and from the server using HTTP GET & POST methods.
3.	Blog-card: Renders each blog as a card on the canvas.
4.	Blog-editor: Provides blog editing facility using ClassicEditor.
5.	Comments: Posts and fetches the comments for the blog from backend.
6.	Home: Provides a boiler plate for the layout and act as router outlet for all components.
7.	Nav-bar: Renders Navigation Bar on each component and dynamically updates the bar.
8.	Paginator: Renders blog cards on the page according to parameters.
9.	Scroller: Scrolls to the top of the page.
10.	Social share: Provides a social share bar with links to all social media platforms to share a blog.
