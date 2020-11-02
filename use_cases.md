# Use Cases

**Use Case #1: User Login**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|1. User opens app||
||2. Login screen is displayed with a username input, password input, button to login, link to recover password, link for 3rd party authentication|
|3. Input username, password and click button||
||4. Username and password are passed to the database to check for authentification|
||5. If validated system displays **Home Screen**|
||6. else if not validated login screen is persistant|
|7a. User clicks link to rest password ||
||8a. System redisplays **Recover Password Screen**
|7b. User selects 3rd party authentication ||
||8b. System links to 3rd party site and shows 3rd party login screen|
|9b. User logs into 3rd party screen ||
||10b. 3rd party passes validiation to system|
||11b. System displays **Home Screen**|

---
**Use Case #2: Password Reset Verification Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. Displayed with an input for username, email, phone number|
|2. User inputs appropriate information||
||3. System validates information with database|
||4. System sends email recovery link??|
|5. User clicks on link in email??||
||6. System redisplays **Recover Password Screen**

---
**Use Case #3: Recover Password Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. Displayed with a password input, second password input, button to reset password|
|2. User inputs new password in each field and clicks reset button||
||3. System verifies passwords match|
||4. System verifies passwords meet basic security requirements|
||5. New password saved to profile in database|
||6. System redisplays **Login Screen**

---
**Use Case #4: Bottom Menu Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|1. User can select home screen||
||2. System displays **Home Screen** with **Bottom Menu Bar**, **Story Bar** and **Top Menu Bar**|
|3. User can select search bar||
||4. System displays **Search Screen** with **Bottom Menu Bar** and **Top Search Bar**|
|5. User can select create screen||
||6. System displays **Create Screen** with **Bottom Menu Bar**
|7. User can select liked screen||
||8. System displays **Liked Screen** with **Bottom Menu Bar**, **Story Bar** and **Top Menu Bar**|
|9. User can select profile screen||
||10. System displays **Profile Screen** with **Bottom Menu Bar** and **Profile Top Bar**|

---
**Use Case #5: Home Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays last 20 images submitted to application by user and users that the user is following, **Bottom Menu Bar**, **Story Bar**, and **Top Menu Bar**|
|2. User can scroll through feed||
|3. User can pull down to refresh feed||
||4. System refreshes the last 20 images submitted to application by user and users user is following|
|5. User can tap on a submitted image in the feed|
||6. System displays image in **Display Image Screen**|

---
**Use Case #6: Top Menu Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|1. User can select story screen||
||2. System displays **Story Screen**
|3. User can select direct messaging screen||
||4. System displays **Direct Messaging Screen**|
|5. User can select to logout||
||6. System closes user's session in database|
||7. System display **Login Screen**


---
**Use Case #7: Story Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|1. User can select create story screen||
|| 2. System displays **Create Story Screen**|
|3. User can select other user's stories|
||4. System displays **Stories Screen**|

---
**Use Case #8: Display Image Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays image, user's profile image that posted the image (link to user's profile, user's profile name that posted the image (link to user's profile), image's posted date, image's caption, image share button, number of shares, image save button, number of saves, image like button, number of likes, comments made by other users about the image, number of comments, text input window for comment to be added, button to submit comment|
|2. User clicks on share button||
||3. System creates a copy of image into database|
||4. System displays shared image as organic to user's feed|
||5. System adds share to total shares of image
||6. System changes state of share button on user's screen|
|7. User clicks on save button||
||8. System creates an instance of save into database|
||9. System adds save to total saves of image
||10. System changes state of save button on user's screen
|11. User clicks on like button||
||12. System creates an instance of like into database|
||13. System adds like to total likes of image
||14. System changes state of like button on user's screen
|15. User inputs text into input dialog for new comment||
|16. User clicks on submit button||
||17. System scans for 'tagged' users|
||18. System alerts user of new tag|
||19. System creates an instance of comment into database|


---
**Use Case #9: Stories Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays image, user's profile image that posted the image (link to user's profile, user's profile name that posted the image (link to user's profile), image's posted date, image's caption, image share button, number of shares, image save button, number of saves, image like button, number of likes, comments made by other users about the image, number of comments, text input window for comment to be added, button to submit comment|
|2. User clicks on share button||
||3. System creates a copy of image into database|
||4. System displays shared image as organic to user's feed|
||5. System adds share to total shares of image
||6. System changes state of share button on user's screen|
|7. User clicks on save button||
||8. System creates an instance of save into database|
||9. System adds save to total saves of image
||10. System changes state of save button on user's screen
|11. User clicks on like button||
||12. System creates an instance of like into database|
||13. System adds like to total likes of image
||14. System changes state of like button on user's screen
|15. User inputs text into input dialog for new comment||
|16. User clicks on submit button||
||17. System scans for 'tagged' users|
||18. System alerts user of new tag|
||19. System creates an instance of comment into database|


---
**Use Case #10: Direct Messaging Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
**See Messaging Application**


---
**Use Case #11: Search Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|| 1. System displays popular search topics|
|2. User conducts search using **Top Search Bar** ||
||3. System displays search results|

---
**Use Case #12: Top Search Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays input diaglog and submit button|
|2. User types in search parameters ||
|3. User clicks on submit button|
||4. System searches database for results|
||5. System returns results to **Search Screen**|

---
**Use Case #13: Create Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
7.1. Users can take a photo utilizing the phone’s camera
7.2. Users can modify photo by cropping, changing vibrancy, hue, etc.
7.3. Users can ‘tag’ other users within photo
7.4. Users can add a 150 character caption
7.5. Users can ’tag’ other users within caption
7.6. Users can share the image to application
7.7. Users can share an ‘important’ image to application
7.8. Progress bar shows progress of upload

---
**Use Case #14: Liked Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays last 20 images liked by user, **Bottom Menu Bar**, **Story Bar**,  and **Top Menu Bar**|
|2. User can scroll through feed||
|3. User can pull up to retrieve additional images to the feed||
||4. System load an additional 20 images liked by user|
|5. User can tap on a liked image in the feed|
||6. System displays image in **Display Image Screen**|


---
**Use Case #15: Profile Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays the latest 18 images submitted by the user, **Profile Top Bar** and **Story Highlights Bar**|
||1a. System displays the latest 18 images submitted by the selected user, **Profile Top Bar** and **Story Bar**|
|2. User can scroll through feed||
|3. User can pull up to retrieve additional images to the feed||
||4. System load an additional 18 images by user and displays buttons to change feed appearance (grid, list, )|
|5. User can select view of the feed||
|5. User can tap on an image in the feed||
||6. System displays image in **Display Image Screen**|

---
**Use Case #16: Profile Top Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays user profile image, user name, user description, number of posts made by user, number of followers of user, number of users followed by user, log out button, edit profile button
|2. User can select edit profile button||
||3. System displays **Edit Profile Screen**|
|4. User can select logout button||
||5. System closes user's session in database|
||6. System display **Login Screen**
||1a. System displays other user's profile image, user name, user description, number of posts made by user, number of followers of user, number of users followed by user, follow button, message button
|2a. User can select follow button||
||3a. System creates instance of follow in the database|
||4a. System changes state of follow button|
|5a. User can select message button||
||6a. System display **Direct Message Screen**


---
**Use Case #17: Story Highlights Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays button to add story and additional buttons for categories of stories|
|2. User selects any story||
|3. System displays **Create Story Screen**||
|4. If category selected, system will automatically fill category on create story screen load||

---
**Use Case #18: Create Story Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
**See Camera Override Application**

---
**Use Case #19: Edit Profile Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays current information and a profile image selector, input dialog for user name, input dialog for email, input dialog for phone number, input dialog for description, input dialogs for password and pasword validation, and update button|
|2. User can update profile image||
||3. System uploads file from screen and replaces instance database|
|4. User can update user name||
||5. System uploads from screen and replaces instance database|
|6. User can update email||
||7. System uploads from screen and replaces instance database|
|8. User can update phone number||
||9. System uploads from screen and replaces instance database|
|10. User can update description||
||11. System uploads from screen and replaces instance database|
|12. User can update password||
||13. System uploads from screen and validates it meets security requirements|
||14. System replaces instance database|
