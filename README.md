CSRF_SynchronizerTokenPattern

Cross-site Request Forgery protection in web application( Used SynchronizerTokenPattern )

In this project used Synchronizer Token Pattern to avoid Cross-site Request Forgery protection in a web application. The application consists of a simple login page with hard-coded credentials. Upon login generates CSRF token and store in server side. The Website has an endpoint which accepts HTTPS post requests. The endpoint receives the session cookie and based on the session identifier, return the CSRF token value. The HTML is submitted to the action, on the server side, extract the received CSRF token value and check if it is the correct token issued for the particular session. If the received CSRF token is valid, show a success message. If not show an error message.

Download and Installation
Clone the project to the local Machine
git clone https://github.com/PirashaMaxa123/SSS_Assignment12.git

Run application
Application Implemented Using Eclipse IDE
Appache TomCat Should be Configured(Used Tomcat V8.0)

Login Form URL
http://localhost:10343/SynchronizedTokenPattern/login.jsp

Credentials
UserName :maxa
Password :maxa123
Upon Sceessful login directs to Form

Form URL
http://localhost:10343/SynchronizedTokenPattern/form.jsp

Blog URL : https://pirashapas.blogspot.com/2019/05/it16117006sssassignment1.html
