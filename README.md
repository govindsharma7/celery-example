Install RabbitMQ

Install Celery and project and run the Celery worker

    $ virtualenv venv
    $ source venv/bin/activate
    $ pip install -r requirements.txt
    $ cd myproj
    $ celery worker --app=myproj -l info
