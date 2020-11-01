# Use Cases

**Use Case #1: User Login**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
|1. Open app         ||
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


**Use Case #3: Home Screen**
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #3: Search Screen
|Actor(User) Actions |System Reponses|
|--------------------|---------------|




**Use Case #4: Create Screen
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #5: Liked Screen
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #6: Profile Screen
|Actor(User) Actions |System Reponses|
|--------------------|---------------|



**Use Case #7: Full Image Screen
|Actor(User) Actions |System Reponses|
|--------------------|---------------|




**Use Case #8: Profile Screen
|Actor(User) Actions |System Reponses|
|--------------------|---------------|
