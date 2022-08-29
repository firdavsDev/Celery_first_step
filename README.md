# Celery_first_step
Celery first step project for educations students

#Install RabbitMQ - (message broker)
  sudo apt-get install rabbitmq-server
  sudo systemctl enable rabbitmq-server
  sudo systemctl start/status rabbitmq-server
  sudo systemctl status rabbitmq-server
	


# Run Celery
terminal0: python manage.py runserver
terminal1: celery -A proj worker -l info #command
terminal2: python manage.py shell -> from app1.taks import add ->add.deley(x,y)
