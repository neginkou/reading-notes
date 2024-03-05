# Django REST Framework & Docker

Understanding the differences between Django and Django REST framework matters because it helps developers choose the right tool for building their web applications. Django is suitable for full-stack web development, while Django REST framework is more focused on building APIs. Knowing when and how to use each framework can lead to more efficient and effective development workflows.

[Beginner’s Guide to Docker](https://wsvincent.com/beginners-guide-to-docker/)

[Django for APIs - Library Website](https://djangoforapis.com/library-website-and-api/)

[Beginner’s Guide to Django REST Framework](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)

1. What are the key components of a Docker container, and how do they help streamline the development and deployment of applications? 

Docker containers consist of images (templates with everything needed to run),
 a runtime (engine to manage containers), Dockerfiles (instructions for building images), registries (to store and share images), networking (for communication), volumes (to persist data), and orchestration tools (to manage and scale applications). They streamline development and deployment by providing a consistent environment, simplifying packaging and distribution, improving scalability, and simplifying deployment.

2. Describe the primary steps involved in building a library website using Django, including essential components like models, views, and templates.

* Models: Define models for books, authors, and categories.
* Views: Create views to handle user requests and interact with models.
* Templates: Design HTML templates to display pages using Django's template language.
* URLs: Define URL patterns to map URLs to views in the URLconf.
* Static Files: Manage static files like CSS and JavaScript.
* Admin Interface: Optionally, use Django's admin interface to manage data.
* Authentication: Implement user authentication for security.
* Deployment: Deploy the Django application to a web server.

3. Can you explain the primary differences between Django and Django REST framework?

Django is a full-stack web framework for building web applications, while Django REST framework (DRF) is an extension for building APIs. DRF adds features like serializers for data conversion, API views for handling requests, and built-in support for authentication and permissions.