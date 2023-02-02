# Lab-1_202001178

Q1. Identify FRs and NFRs:

Functional Requirements:

1.) A web Application that uses HTML 5 technology. 

2.) A database is required in backend of the application to store information and details of each book. A database is also required to store information and details about users like their password, username, borrowing history, etc.

3.) Application must have a login feature which allows login of only members and does not allow login of non-members. This login feature should also have a option of login as administrator and login as library staff.

4.) Application must allow all users including non-members to browse and search through all the books.

5.) Application must allow all members to borrow or return a book. Application must not allow non-members to borrow or return a book.

6.) Application must have a feature to display status of a book like available, not available, booked, etc. 

7.) Application should also have a feature that allows booking of a book while some other member has already borrowed that particular book.

8.) Application must have a feature that allows a member to extend his date of borrowing, if there is no other booking of that book.

9.) Application must have a feature that allows library staff to handle day-to-day transactions easily.

10.) Application must provide admistrative priviledges to the librarian. These previledges allow administrator to have complete control over the system. Admistrator can enter records of newly purchased books and delete records of books that are no longer available for booking.

11.) Confidential information like passwords of users must not be stored in plain text. It must have some encryption.

Non Functional Requirements:

1.) Scalability: Application should be able to handle large amount of users at the same time. Application should have sufficiently large database to handle information of all members and details about all books. 

2.) Performance: Web Application should not be down. It should be accessible from any device within the institute LAN 24 by 7. It should not run when accessed from outside. Borrowing process should be quick. 

3.) Reliability: Application should be reliable. It should not display incorrect details of books. It should not allow borrowing of a particular book to multiple members at the same time. 

4.) Maintainability: Application should not be rigid. Application must allow the librarian to easily add and delete books. 

5.) Flexibility: Web application must be accessible from all devices like mobile, laptops, computers, etc. Application should be compatible with all browsers like chrome, firefox, opera, etc. 

6.) Security: Application should be secure. It must not display personal or login information of members to other users. 

Q2. Identify scope, features and non-functional aspects of the following problem.

Scope: 

Target audience of our project are people who are suffering from disabling hearing loss. This application will help them to recognize key sound events where immediate alert or continual logging is required. 
Project comprises of a mobile application that uses artificial intelligence to identify key sound events. Artificial intelligence should comprise of trained neural networks to identify sounds.
Mobile application must be fast and highly accurate because it is used by our target audience in day to day life to take important desicions in real time. 

Features:

Application should be able to respond to external noise by alerts on screen, using vibrations or using inbuilt flashlight. This is required to gain attention of the user during sounds of interest and alert them. Mobile application should have access to flashlight, vibration sensor and notification panel of the mobile. 

Application should be able to classify external sounds to different levels of priority and generate outputs accordingly. For example, a fire alarm should be classfifed as high priority event whereas a vehicle horn should be classified as medium priority event.

Application should be optimized to satisfy individual needs of each user. This should be done using artificial intelligence tehchnology. For example a traffic police using this application will have different priorities whereas a hospital nurse using this application will have different priorities. For a traffic police only few sounds are important whereas for a nurse all sounds are important. 

Application should have low latency and provide output within seconds.

Non-functional aspects:

Mobile application should be compatible with all operating systems like android, ios, etc. Mobile application should be available on all popular app stores free of cost. 

Mobile application should be accurate and should not provide false alerts. 

Mobile application should be scalable. It should be able to handle large amount of users simultaneously.

Application should use optimum amount of memory and battery. 

