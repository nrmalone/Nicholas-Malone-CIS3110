# Nicholas Malone - *CIS3110 Project 2*
### [YouTube Demonstration]() <-- Will make a video demonstration ASAP
## Deliverable Requirements
#### 1. Authentication Screen
I used the authentication screen example from [Bootstrap](https://getbootstrap.com/docs/4.4/examples/sign-in/)
#### 2. console.log
Line 69 of [project2.html]() is the console.log() that declares a user authenticated if there is input in both the username and password fields.
#### 3. Set cookie
Upon loading, [project2.html]()'s JavaScript runs checkCookie() and will consequently set a cookie if the user provides a username and password then submits the form.
#### 4. Navigate user
If the user has a cookie proving they are authenticated, window.location.href automatically takes them to an updated version of the landing page from Project 1.
#### 5. Show a 'welcome back' message
The landing page for [project1.html]() runs getCookie('username'); and will post a "Welcome back." alert at the top of the page if they were successfully authenticated and redirected from project2.html.
