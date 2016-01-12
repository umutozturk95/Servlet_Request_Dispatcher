In this example, we are validating the password entered by the user. If password is servlet, it will forward the request to the WelcomeServlet, otherwise will show an error message: sorry username or password error!. In this program, we are cheking for hardcoded information. But you can check it to the database also that we will see in the development chapter. In this example, we have created following files:

index.html file: for getting input from the user.
Login.java file: a servlet class for processing the response. If password is servet, it will forward the request to the welcome servlet.
WelcomeServlet.java file: a servlet class for displaying the welcome message.
web.xml file: a deployment descriptor file that contains the information about the servlet.
Also this application is improved by using NetBeans IDE.
