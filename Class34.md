# Question one:
- Separate Settings Modules
- Use Environment Variables
- Secure Sensitive Information
- tilize Settings Overrides
- Manage Django Applications
- Version Control and Collaboration
# Question two :
The White Noise library is designed to efficiently serve static files in Django applications. It works as a middleware that integrates with Django's HTTP handling process and provides optimized static file serving capabilities. Here's how White Noise contributes to the efficient serving of static files in a Django application:

Simplified Configuration: White Noise simplifies the configuration process for serving static files. It automatically takes care of aspects like setting appropriate HTTP headers, compressing files, and handling cache control.

Efficient File Serving: White Noise uses efficient caching techniques to serve static files. It caches compressed versions of static files, reducing the amount of data that needs to be transmitted over the network and improving overall performance.

Integration with WSGI Servers: White Noise integrates seamlessly with WSGI servers commonly used with Django, such as Gunicorn or uWSGI. This allows for efficient static file serving in production environments.

# Question three:
CORS is a security mechanism that controls access to resources (such as APIs or web fonts) on a web page from different domains. It prevents web pages hosted on one domain from making requests to resources on another domain, unless the other domain explicitly allows it. CORS helps protect against cross-site scripting (XSS) and cross-site request forgery (CSRF) attacks.