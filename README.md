
### Link to live Application:   
https://umn4131final.herokuapp.com/  
 
### List of Technologies/API's Used:    
Random quote generator API
 
### Detailed Description of the project:   
- This project is targeted for college students to make their experience of selling and buying textbooks seamless. Also, the website provides the servis of posting events as well as creating new ones. 
- The user can browse all the books and events that have been added by any user. It also shows all the users who have signed up to the website with their contact information. 
- In addition, the user can browse their own books and events with the opportunity to delete the events they created and the books they posted from the website database. Finally, the user can search for events and books based on their categories.
 
 
 
### List of Controllers and their short description:  
`Quote:` This goring to route you the API which gives famous quotations.    
`Profile:` The routing to profile which display users information and the book and events they created  
`Remove_book:` This is meant to help with deleting element from book database    
`Remove_event:` Deletes selected element from event database  
`Login:` Login to the website with your information  
`Signup:` Sign up to the website and check if entries are correct   
`Logout:` This is will left the authentication on the user   
`sellBook:` check if the entered information is correct and save in the database  
`Book:` Display all books posted with their corresponding information.   
`SelectBook:` This is meant to filter book results based on the major  
`Event:` This is where events are being created and stored in the database  
`SelectEvent:` This is meant to filter event results based on the major   
`Dashboard:` This is shown all the users who have signed up to the website with their contact information . 
 
### List of Views and their short description:  
`Base:` This is the base template that all pages in this project inherit from.  
`Book:` Display all the books posted from all users and show their corresponding information.   
`Dashboard:` This is shown all the users who have signed up to the website with their contact information .  
`Event:` This is where events are being created, posted, and stored in the database    
`Index:` This is meant to be the homepage that introduce visitors to the website .   
`Login:` This is where users get authenticated to enter the website .  
`Profile:` Display user’s information and books and events they have created   
`Quote:` This is where the API randomly picks a famous quotation.   
`sellBook:` This patch is dedicated to receiving book’s information from the user and posting it to the database.   
`Signup:` This is were new users get to signed up and add to the database   
 
### List of Tables, their Structure and short description:  
`User:` User table is about saving all information of the users who have signed up to the website. The user table include ( ID, Name, Phone Number, Email, Password)  
`Category:` This table is meant to work as the middleman to link all books and events created to the category they are related to.  
`Event:` Keep track of all events that have been saved for all users. Linking all events to their user’s creator and the category they identify with. The event table include ( ID, Event Name, Owner ID, Details, Time, Place, Category ID)    
`Book:` Keep track of all books that have been added for all users. Linking all books to their user’s seller and the   category they identify with. The book table include ( ID, Title, Details, Price, Seller ID, Posted date, Category ID)    
 
### 10. References/Resources:
https://bulma.io/documentation/layout/hero/  
https://www.w3schools.com/css/css_table.asp   
https://www.youtube.com/watch?v=K0vSCCAM2ss&feature=emb_title  
