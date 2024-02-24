# Webapp

Just starting out...

Web servers such as apache don't know how to run python applications. WSGI solves that problem and is between the web server and the python application.

Django is web application framework and provides features to implement web servers, services or whatever it promotes it allows us to create.

Django provides development WSGI server through `manage.py` module. It is not secure recommended for production.

I should use some WSGI server, for example Gunicorn.

The Gunicorn recommends to use Nginx as a reverse proxy server. Why? No clue.

I plan to use local area network setup to allow a limited amount of machines to access the web application. There is no need to allow a global access to the web application. That would make deploying much more difficult as I would not have access to that server machine. The SSH could allow me to hook-in to the server machine and do the deployment... but I think it would need to be connected to the internet. I've gotta think about this.
Hosting is expensive and there are no hosting services that are free and provide enough resources. Each of these approaches has pros and cons. I should evaluate them.
