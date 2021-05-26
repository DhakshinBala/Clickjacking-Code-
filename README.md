# Clickjacking-Code-
This the code used for checking the clickjacking vulnerability in the websites

Step 1 : Fix the target website 
Step 2 : Get the URL of the website 
Step 3 : Paste the URL in the iframe section in the below code 
Step 4 : Save it as a HTML file
Step 5 : Open the HTML file , if it is vulnerable then the site will be visible in your html file.



<html>
<head>
<title>Clickjacking test page</title>
</head>
<body>
<p>YOUR WEBSITE IS VULNERABLE</p>
<iframe src="ENTER THE URL THAT IS TO BE TESTED " width="900" height="600"></iframe>
</body>
</html>
