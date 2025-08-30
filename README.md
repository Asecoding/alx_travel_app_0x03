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


# Real-World Use Case
In real-world travel or booking platforms like Booking.com or Airbnb, sending booking confirmation emails instantly is critical but should not delay the user experience. Using Celery with RabbitMQ, the email sending process can be offloaded to a background worker, ensuring users receive instant feedback while the system handles notifications asynchronously. This approach is scalable and can also be extended to other time-consuming tasks such as invoice generation, report creation, or SMS notifications.

# 📝 Project Assessment (Hybrid)

Your project will be evaluated primarily through manual reviews. To ensure you receive your full score, please:

- Complete your project on time
- Submit all required files
- Generate your review link
- Have your peers review your work
