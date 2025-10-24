**Code can be reviewed upon request, hidden for academic integrity*
# Cozy Thoughts SocialMedia Platform
A website for posting, sharing, and liking cozy thoughts

Developed from scratch with a full-stack web development process, secure backend design, and user-friendly operations.

## Author:
Hady Kotifani

## Overview
"Cozy Thoughts" is a social media platform that allows users to share short text posts (up to 200 characters), view others' posts, and like them.
The website allows for user authentication, post management, and persistent data storage using a MySQL database.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript, PUG
- **Backend:** Node.js with Express framework
- **Database:** MySQL
- **Relevant Concepts:** Routing, HTTP protocol, server-client communication
- **Other**: *Postman* for testing routing and ensuring that the proper HTTP request method is returned

## Features

### Posting
- Users can create text posts (up to 200 characters when logged in
- Posts are displayed in chronological order by default
- Posts can be sorted by newest or most liked
- Pagination with 10 posts per page
- Users can like posts
- Users can edit or delete their own posts
- Post retains information about date posted, author, number of likes, etc.
- Colors of posts alternate

### User Account Features
- Create, log in, and log out of user accounts
- Login status is tracked on the server-side and displayed on the home page
- Logging in or creating an account automatically switches the active session
- Logging out redirects to the login page
- Posts are associated with the user who created them
- Non-logged-in users can only view posts

### Security
- SQL queries are formatted to prevent SQL injections
- Session management only allows authenticated users to create and modify posts

## Website Images

### **Figure 1**: Homepage
![Homepage.png](/Images/Homepage.png)
The Homepage of the website from a guest user*

---

### **Figure 2**: Create Account
![CreateAccount.png](/Images/CreateAccount.png)
*Account creation page*

---

### **Figure 3**: Post Page 
![Postpage.png](/Images/Postpage.png)
*A logged-in user can create posts here*

---

### **Figure 4**: Gallery
![Gallery.png](/Images/Gallery.png)
*A gallery to see all user-created posts. A user may sort the post by total amount of likes or by most recently created. A user can like, post or edit, and delete their own posts*

---

### **Figure 5**: Edit Post
![Edit.png](/Images/Edit.png)
*A user can edit their own post within the gallery and commit it after changes are made*

---

### **Figure 6**: Pagination
![PageSystem.png](/Images/PageSystem.png)
*The pagination system is shown at the bottom, for demo purposes, only 3 posts can be seen on one page at a time (the default is 10)*

---

### **Figure 7:** Username Display
![Current_User.png](/Images/Current_User.png)
*The user's username can be seen in the upper-left-hand corner of the home page when the user is logged in*

---

### **Figure 8:** Logout
![LogOutPage.png](/Images/LogOutPage.png)
*The user has the option to log out when they are complete with their session*
