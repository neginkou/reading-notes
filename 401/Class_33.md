# Authentication & Production Server

Understanding why Django's built-in runserver is not suitable for production and knowing alternative server options is crucial for deploying Django applications securely and efficiently. Using the right server setup can ensure that your application is robust, scalable, and able to handle the demands of a production environment.

[JSON Web Tokens](https://jwt.io/introduction/)

[DRF JWT Authentication](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)

[Django Runserver Is Not Your Production Server White Noise](https://build.vsupalov.com/django-runserver-in-production/)

[JWT with DRF](https://www.youtube.com/watch?v=Fhcn2qx-4VQ)

[Gunicorn](https://gunicorn.org/)

[Django Migrations Primer](https://realpython.com/django-migrations-a-primer/)

1. What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?

JWTs are used for secure data transmission in web development, especially for authentication. They consist of three parts: header, payload, and signature. The header specifies the token type and signing algorithm. The payload contains the data. The signature is used to verify the token's authenticity.

2. How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?

JWT authentication with Django REST Framework involves configuring a JWT authentication backend, generating and sending JWTs in requests, verifying JWTs on the server side, and handling token expiration and refresh. Clients include the JWT in the `Authorization` header to access protected endpoints.

3. Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?

Django's built-in `runserver` is not suitable for production due to security and performance limitations. For production, consider using Gunicorn, uWSGI, or Docker with Kubernetes for scalability and robustness. Apache or Nginx can be used as reverse proxies.