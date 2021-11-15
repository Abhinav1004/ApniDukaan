# ApniDukaan

It is an ecommerce website enabling clients to browse products, add them to the cart, apply discount codes, go through the checkout process, pay with a credit card, and obtain an invoice. 

It has also a recommendation engine to recommend products to the customers, and uses internationalization to offer the site in multiple languages.

# Features Implemented

1. Creating a Product Catalog and a shopping cart using Django Sessions    
2. Managing Customer Orders on the shopping website    
3. Send asynchronous notifications emails to customers using Celery with RabbitMQ as message broker  
4. Monitor Celery messaging queues using Flower  
5. Integrate Payment Gateway to Project  
6. Generate PDF Invoices and send it to customer email
7. Discount Coupons on products
8. Option to translate the web page to another language
9. Recommending Similar Products based on previous purchases


# Installation

### Python Libraries

1. Install `python 3.8.5` and create virtual environment in a project folder by `virtualenv myenv`  
2. Execute `git clone <project remote path>` in the folder    
3. Run `pip install -r requirements.txt` to install all library dependencies  
4. Execute `cd mysite` to enter mysite directory  
5. Execute `python manage.py runserver` to start the django server  
6. The Blog appplication will be running at `http://127.0.0.1:8000/`  
7. The admin site will be running at `http://127.0.0.1:8000/admin` and can be logged in using credentials present in admin_config.ini file


## Other Requirements 

1. Install **RabbitMQ** on your machine using this [Link](https://www.rabbitmq.com/download.html)
2. Install **GetText** on your  machine
    * Ubuntu
        sudo apt-get install -y gettext
