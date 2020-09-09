# URL-Shortener
This is a basic URL shortener app on which i tried my hands on. It has been made with the purpose to shorten long URLs into a condensed form.
In this particular app i have ensured that if the same URL is being tried to shorten, then the condensed URL shown will be the one that was condensed at the beginning. Along  with it i have an admin panel where i can keep a track of which URLs have been shortened by the sers. SOme additional features like sign up and register can also be included.

In order to run this on a local system, steps to follow:

    1. Fork and clone the project
    git clone https://github.com/jatinagg1/URL-Shortener.git 
    
    2. Python and Django installed
    
    3. In the directory of shortener, run
    python manage.py migrate
    
    4. To start the development server
    python manage.py runserver
    
    5. Open localhost:8000 on your browser to view the app.
    
