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


**Use Case #2: Password Reset Verification Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. Displayed with an input for username, email, phone number|
|2. User inputs appropriate information||
||3. System validates information with database|
||4. System sends email recovery link??|
|5. User clicks on link in email??||
||6. System redisplays **Recover Password Screen**


**Use Case #3: Recover Password Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. Displayed with a password input, second password input, button to reset password|
|2. User inputs new password in each field and clicks reset button||
||3. System verifies passwords match|
||4. System verifies passwords meet basic security requirements|
||5. New password saved to profile in database|
||6. System redisplays **Login Screen**


**Use Case #4: Bottom Menu Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|1. User can select home screen||
||2. System displays **Home Screen** with **Bottom Menu Bar** and **Top Menu Bar**|
|3. User can select search bar||
||4. System displays **Search Screen** with **Bottom Menu Bar** and **Top Search Bar**|
|5. User can select create screen||
||6. System displays **Create Screen** with **Bottom Menu Bar**
|7. User can select liked screen||
||8. System displays **Liked Screen** with **Bottom Menu Bar** and **Top Menu Bar**|
|9. User can select profile screen||
||10. System displays **Profile Screen** with **Bottom Menu Bar** and **Profile Top Bar**|

**Use Case #5: Home Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
||1. System displays last 20 images submitted to application by user and users that the user is following|
|2. User can scroll through feed||
|3. User can pull to refresh feed||
||4. System refreshes the last 20 images submitted to application by user and users user is following|
|5. User can tap on a submitted image in the feed|
||6. System displays image in **Display Image Screen**

**Use Case #6: Top Menu Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|1. User can select create story screen||
|| 2. System displays **Create Story Screen**|
|3. User can select direct messaging screen|
||4. System displays **Direct Messaging Screen**|


**Use Case #7: Display Image Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|




**Use Case #8: Create Story Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|

**Use Case #9: Direct Messaging Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #10: Search Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|


**Use Case #11: Top Search Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|




**Use Case #12: Create Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #13: Liked Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #14: Profile Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #15: Profile Top Bar**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|




**Use Case #16: Additional Functions**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
