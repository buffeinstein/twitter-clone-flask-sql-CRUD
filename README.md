# project5twitterclone
A project to test out Flask! This project is called "Twitter Clone" 

**TOTAL: 34.5/40 pts**

I've completed these tasks: 

**1) Create a Home page - 5 pts**
- a link to this page should always be visible in your menu, whether the user is logged in or not logged in
- this route displays all the messages in the system
- the messages should be ordered chronologically with the most recent message at the top
- each message should include the user account that created it, the time of creation, and the message contents. time of creation doesn't have decimal points in it - **0.5 pts**
- at least one message must contain a single quote ' and a double quote "
- 

**2) Create a Log-in page - 5 pts**
- a link to this page should only be visible in your menu if the user is not logged in
- this route will present a form for the user to enter their username/password; the password box must not display the user's password as they are typing it in
- you must display appropriate error messages if the user enters an incorrect username/password
- after a user successfully logs in, you must automatically redirect them to the homepage

**3) Log out - 5 pts**
- a link to this page should only be visible if the user is logged in
- this route will delete the cookies that the log in form creates, logging the user out

**4) Create new user accounts - 6 pts**
- a link to this page should only be visible in your menu if the user is not logged in
- if the user attempts to create an account that already exists, they should get an appropriate error message
- the user should be prompted to enter their password twice; if the passwords do not match, they should get an appropriate error message
- Automatically log a user into a newly created user account, and redirect the user to the home page (instead of the create user page) - **3 pts**

**5) Create a message - 5 pts**
- a link to this page should only be visible in your menu if the user is logged in
- the user must be able to enter whatever message body they want, but you will also need to store the user id of the user that created a message and the time the message was created
- you will only get credit for this route if the message correctly shows up on the home route after creation

**6) Allow changing the password after creating an account. You must have a password reset form that forces the user to type in their old password and a new password twice - 3 pts**

**7) Styled these pages with HTML/CSS - 3 pts**
