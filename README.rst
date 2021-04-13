😎 AI_Dietician_Django 😎

Example project You can check out our example project by cloning the repo and heading into example/ directory.

Documented By- Sandeep Kumar

How to Run this Code? Follow these steps:

Open your terminal in AI_Dietician/ folder which contains requirements.txt file.

Create virtual environment
Steps to create Virtual Environment

Run this command in your Terminal or CMD:- conda create --name AI_Dietician
if any error while running this command install conda from here https://docs.conda.io/en/latest/miniconda.html
It asks [y/n] :- press y on your keyboard
After Creating Virtual Environment Activate it. To Activate run this command:- activate AI_Dietician
Now Virtual Environment is activated in your terminal
After Activating Virtual Environment Install required packages using this command:- pip install -r requirements.txt

Now open your terminal in AI_Dietician/AI_Dietician which contains manage.py file.

now run these following command to migrate database
py manage.py migrate
py manage.py makemigrations
again run:- py manage.py migrate
Now atlast create admin to your app using this command:- py manage.py createsuperuser

It asks some details fill it.

Now it's complete Run this app by starting the server using:- py manage.py runserver

Now server started Open http://127.0.0.1:8000/ in your browser to view the app.

To View Admin panel go to http://127.0.0.1:8000/admin/

In this project we used backend which stores the form. Fill the form and hit submit. The data is stored in database. To view submitted Form go to admin panel. To View Admin panel go to http://127.0.0.1:8000/admin/

If any Queries call or message at +91 8340211161
