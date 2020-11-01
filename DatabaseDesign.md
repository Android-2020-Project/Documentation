# Instagram Clone  *Database Schema*

* Role(objectId, createdAt, updatedAt, name, users, roles)
* User(objectId, createdAt, updatedAt, username, email, password, emailVerified)
* Post(objectId, createdAt, updatedAt, image, description, user, likes)
* Comments(objectId, createdAt, updatedAt, comment, user, post, likes)

<img src='https://github.com/Android-2020-Project/Documentation/blob/main/DatabaseDesign.png' title='Design ScreenShot' width='' alt='ScreenShot' />

| Role |
| ---- |
| objectId (Primary Key  String  auto-generated)|  
| createdAt (Date)| 
| updatedAt (Date)|  
| name (String)| 
| users (Relation (user))| 
| roles (Relation (role))| 

| User |
| ---- |
| objectId (Primary Key  String  auto-generated)|  
| createdAt (Date)| 
| updatedAt (Date)|  
| username (String)| 
| email (String)| 
| password (Password_string)| 
| emailVerified (boolean)|

| Post |
| ---- |
| objectId (Primary Key  String  auto-generated)|  
| createdAt (Date)| 
| updatedAt (Date)|  
| image (file)| 
| users (Pointer (user))| 
| likes (number)| 

| Comment |
| ---- |
| objectId (Primary Key  String  auto-generated)|  
| createdAt (Date)| 
| updatedAt (Date)|  
| comment (String)| 
| users (Pointer (user))| 
| post (Relation (post))|
| likes (number) |
