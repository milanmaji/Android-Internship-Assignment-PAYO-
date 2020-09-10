# Android Internship Assignment (My Application)
## Overview:
"My Application" is an Android app, developed using Android Studio IDE with JAVA. This app has these features-

### 1. Signup screen:
In signup screen you can create an account. To fillup the signup form you must provide first name, last name, email,
password, confirm password, mobile number, and address. Then click "SIGNUP" button to create account. I use local database "SQLit Database"  to store data.
If you have already an account you can goto login screen by click "ALREADY HAVE ACCOUNT? LOGIN" button.
Note: Signup basic validations are implemented on the form.Password should be at least 6 character long.

### 2. Login screen:
You can login into this application using previously registered email id and password in login screen. If you are new then create an account by click button "NEW USER? SIGNUP".
When you click "LOGIN" button 1st check email already registered or not. If already registered then matching password. When login succesfully you redirect to Home Screen.
Login basic validations are implemented on this form.

### 3. Home screen:
In Home screen you show some user list which have an image, name and email by calling API (https: //reqres. in/api/users?page=1). When scroll down get more users data if available . This list is sorted by first name & last name of users. You can delete the user from user list By long click on list iteam. When long click on list iteam confirmation dialog will appear.

### 4. My Profile:
You show your registered information on "My Profile" that is present in the left side drawer ( hamburger menu) with the " My
profile" menu. At the buttom  a "logout" button present. On click on the logout button, the user should be redirected to
the login form.

