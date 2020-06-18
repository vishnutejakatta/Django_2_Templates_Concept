# Django_2_Templates_Concept
We created a seperate folder for templates (html, css, js files) called "Templates". It contains a HTML file.

In the settings.py of Project_1 folder, we modified the DIRS key of TEMPLATES variable. We included the path to the "Templates" folder, so that Django will now look into "Templates" folder for any templates.

Then in views.py of myapp_1, we used the render function to render the HTML file. The rende function here took 2 arguments. The first one is a request object and the second one is the name of the HTML file we want to render.

