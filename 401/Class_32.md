# Permissions & Postgresql

Understanding DRF Generic Views is crucial for developers building RESTful APIs with Django Rest Framework. They provide a powerful and efficient way to handle common CRUD operations, reducing code duplication and ensuring consistency in API design. By using Generic Views, developers can focus more on the business logic of their APIs rather than writing boilerplate code, leading to faster development cycles and more maintainable codebases.

[DRF Permissions](https://www.django-rest-framework.org/api-guide/permissions/)

[Review SQL Prework](https://codefellows.github.io/common_curriculum/prework/SQL)

[Classy Django REST](http://www.cdrf.co/)

[DRF Generic Views](https://www.django-rest-framework.org/api-guide/generic-views/)


1. What are the key components and purpose of Django Rest Framework (DRF) permissions, and how do they help in securing an API?

DRF permissions control who can access API endpoints and what actions they can perform. They rely on authentication to identify users and provide various permission classes like IsAuthenticated and IsAdminUser. Authorization checks if a user can perform a specific action on an object. Throttling limits the number of requests a user can make. These components work together to secure APIs by allowing only authorized users to access certain endpoints and actions.

2. In SQL, what is the purpose of the SELECT statement, and how would you use it to retrieve all columns from a table called ‘employees’?

The SELECT statement in SQL is used to retrieve data from a database. It is the most commonly used statement in SQL and allows you to specify which columns you want to retrieve and from which table. To retrieve all columns from a table called 'employees', you would use the following SQL query:

`SELECT * FROM employees;`

The * symbol is a wildcard that represents all columns in the specified table. This query would return all rows and columns from the 'employees' table.

3. Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?

DRF Generic Views are pre-built views in Django Rest Framework for common actions like retrieving a list of objects, retrieving a single object, creating, updating, and deleting objects. They reduce code duplication and provide a consistent way to build RESTful APIs.

Example usage:

* ListAPIView: Retrieve a list of objects.
* RetrieveAPIView: Retrieve a single object.
* CreateAPIView: Create a new object.

from rest_framework.generics import ListAPIView, RetrieveAPIView, CreateAPIView
from .models import MyModel
from .serializers import MyModelSerializer

class MyModelListView(ListAPIView):
    queryset = MyModel.objects.all()
    serializer_class = MyModelSerializer

class MyModelRetrieveView(RetrieveAPIView):
    queryset = MyModel.objects.all()
    serializer_class = MyModelSerializer

class MyModelCreateView(CreateAPIView):
    queryset = MyModel.objects.all()
    serializer_class = MyModelSerializer
