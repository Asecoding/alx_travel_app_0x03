# alx_travel_app_0x03
Setting Up Background Jobs for Email Notifications
# Key Concepts

Asynchronous Task Processing: Running time-consuming tasks in the background.

Message Broker: Middleware (RabbitMQ) used to send and receive task messages between Django and Celery.

Celery Configuration: Setting up celery.py and integrating it into settings.py.

Shared Tasks: Functions decorated with @shared_task for execution by Celery workers.

Email Backend in Django: Configuring SMTP settings for sending automated emails.

# Tools and Libraries

- Django – Backend web framework for building the application.
- Celery – Distributed task queue for background task execution.
- RabbitMQ – Message broker to handle communication between Django and Celery.
- SMTP Email Backend – For sending booking confirmation emails.
