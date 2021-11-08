# ApniDukaan

It is an ecommerce website enabling clients to browse products, add them to the cart, apply discount codes, go through the checkout process, pay with a credit card, and obtain an invoice. 

It has also a recommendation engine to recommend products to the customers, and uses internationalization to offer the site in multiple languages.

# Features Implemented

• Create a product catalog  
• Build a shopping cart using Django sessions  
• Create custom context processors  
• Manage customer orders  
• Configure Celery in your project with RabbitMQ as a message broker  
• Send asynchronous notifications to customers using Celery  
• Monitor Celery using Flower  

# Installation

1. Install `python 3.8.5` and create virtual environment in a project folder by `virtualenv myenv`  
2. Execute `git clone <project remote path>` in the folder    
3. Run `pip install -r requirements.txt` to install all library dependencies  
4. Execute `cd mysite` to enter mysite directory  
5. Execute `python manage.py runserver` to start the django server  
6. The Blog appplication will be running at `http://127.0.0.1:8000/`  
7. The admin site will be running at `http://127.0.0.1:8000/admin` and can be logged in using credentials present in admin_config.ini file
