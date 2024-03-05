# Intro to Django

Understanding the differences between Tailwind CSS and Bootstrap CSS matters because it allows developers to choose the framework that best suits their project requirements, development workflow, and design preferences. 

[Getting started with Django](https://www.djangoproject.com/start/)

[How Django Works Behind the Scenes](https://wsvincent.com/how-django-works-behind-the-scenes/)

[What is Tailwind CSS?](https://blog.hubspot.com/website/what-is-tailwind-css)

[What is Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Introduction)

[First Django App - Part 1](https://docs.djangoproject.com/en/4.1/intro/tutorial01/)

[First Django App - Part 2](https://docs.djangoproject.com/en/4.1/intro/tutorial02/)

[Tailwind CSS Django - Flowbite](https://flowbite.com/docs/getting-started/django/)

1. What are the key components of the Django framework, and how do they contribute to building a web application?

1. Models: Define data structure and interact with the database.

2. Views: Handle requests, process data, and return responses.

3. Templates: Generate dynamic HTML for presentation.

4. URL Dispatcher: Maps URLs to views for routing.

5. Forms: Handle user input and data validation.

6. Admin Interface: Automates CRUD operations for managing site content.

2. Explain the role of Django’s MTV (Model-View-Template) architecture and how it handles a typical web request-response cycle.

Django's MTV architecture divides tasks into:

* Model: Handles data interaction.

* View: Processes requests and prepares responses.

* Template: Generates HTML for presentation.

During a request:

* URL dispatcher routes to a view.

* View interacts with models and prepares data.

* Template renders HTML with the data.

* HTML response is sent back to the client.

3. What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?

* Tailwind CSS: Utility-first framework for highly customizable styling directly in HTML.

* Bootstrap CSS: Component-based framework with pre-designed UI components and responsive grid system.

Tailwind focuses on utility classes for flexibility, while Bootstrap offers pre-designed components for rapid development.