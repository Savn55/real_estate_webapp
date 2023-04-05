# Real Estate WebApp 
[App](http://www.savnproperties.site)

Welcome to the Real Estate WebApp, a Django-based platform for managing property listings and user queries. With this app, users can browse available properties, search for listings based on various criteria, and contact the assigned realtor for more information or to schedule a viewing. Users can also create accounts to save their favorite properties and manage their queries in a personalized dashboard.

## Technologies
The Real Estate WebApp is built using the following technologies:

<p>
<img src="https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54"/>
<img src="https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/django-%23092E20.svg?style=flat&logo=django&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS-239120?&style=flat&logo=css3&logoColor=white"/>
<img src="https://img.shields.io/badge/HTML-239120?style=flat&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white"/>
  
</p>

In addition, the following libraries were used:

* Pillow (for image handling)
* Gunicorn (for deployment)
* Nginx (for deployment)

## Deployment
</br>
The Real Estate WebApp is deployed using the cloud platform [Digital Ocean](www.digitalocean.com), with a domain name from [Namecheap](www.namecheap.com). This ensures that the app is accessible from anywhere with an internet connection.

## Features
The Real Estate WebApp offers a range of features to make property browsing and management as easy as possible:

* Browse available properties without logging in
* Create an account to save favorite properties and manage queries
* Search for properties based on keywords, city, state, bedrooms, bathrooms, and garage
* Contact assigned realtor directly from the property listing
* Personalized dashboard for managing queries and saved properties

## Getting started
To get started with the Real Estate WebApp, you'll need to have Python, Django, and PostgreSQL installed on your local machine. Once you've downloaded the source code, follow these steps:

* Create a virtual environment and activate it
* Install the required dependencies using pip install -r requirements.txt
* Create a PostgreSQL database for the app
* Set the DATABASE_URL environment variable to the database URL
* Run the migrations using python manage.py migrate
* Create a superuser using python manage.py createsuperuser
* Start the server using python manage.py runserver
* Once the server is running, you can access the app in your web browser at http://localhost:8000/.

## Acknowledgement
I want to thank [Brad Traversey](https://github.com/bradtraversy) for this wonderful project. I learnt many cool ideas and your thought process to create such project from beginning to end. There were definitely challenges on finishing this project however, community and google helped me to overcome those challenges.   
