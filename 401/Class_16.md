# Serverless Functions

Understanding and utilizing APIs is essential because they enable access to external data and services, promote efficiency, speed up development, enhance user experiences, and provide a competitive edge in modern software development. APIs are fundamental to building versatile and connected applications.

[What is Serverless Computing?](https://www.ibm.com/cloud/learn/serverless)

[venv - Creation of Virtual Environments](https://docs.python.org/3/library/venv.html)

[Vercel - Get Started](https://vercel.com/docs/get-started)

[http.server](https://pymotw.com/3/http.server/index.html)

[Requests](https://requests.readthedocs.io/en/latest/)

[Python & APIs](https://realpython.com/python-api/)

1. What are the key characteristics of serverless computing, and how does it differ from traditional server-based architectures?

* Serverless:

Event-driven and stateless.
Auto-scales automatically.
Pay-as-you-go pricing.
No server management.
Rapid development and deployment.
Short-lived execution.
Vendor lock-in.
Limited resource control.

* Traditional Server-Based:

Typically not event-driven.
Scaling requires manual provisioning.
Continuous server costs.
Requires server management.
Longer development and deployment.
Supports long-running processes.
Lower vendor lock-in.
More resource control.

2. How can one get started with Vercel, and what are the main steps involved in deploying a serverless function using Vercel?

1. Sign up for Vercel.
2. Install Vercel CLI.
3. Write your serverless function in an api folder.
4. Run vercel to deploy.
5. Access your function at the provided URL.
6. Optionally, configure custom domains and continuous deployment in the Vercel dashboard.

3. What are APIs, and how can they be utilized in Python applications to access and manipulate data from external sources?

APIs are sets of rules that allow Python applications to access and manipulate data from external sources. This is done by sending HTTP requests, handling JSON data, and implementing authentication, error handling, and rate limiting. Python libraries like requests and SDKs simplify API integration, making it easier to interact with various services and retrieve or manipulate data.

4. What is the Requests library in Python, and how can it be used to interact with APIs by sending HTTP requests? Can you provide an example of a basic GET request using the Requests library?

The Requests library in Python is a popular and user-friendly library for sending HTTP requests to interact with APIs and web services. It simplifies the process of making HTTP requests and handling responses, allowing you to fetch data from external sources easily. You can use the Requests library to perform GET, POST, PUT, DELETE, and other HTTP methods.

Ghatgpt example: 

import requests

### Define the URL of the API you want to interact with
api_url = "https://jsonplaceholder.typicode.com/posts/1"

### Send a GET request to the API
response = requests.get(api_url)

### Check if the request was successful (HTTP status code 200)
if response.status_code == 200:
    # Parse and work with the JSON response
    data = response.json()
    print("Response Data:")
    print(data)
else:
    # Handle any errors or non-200 status codes
    print(f"Request failed with status code: {response.status_code}")
