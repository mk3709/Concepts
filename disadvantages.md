# Disadvantages of HTTP

While HTTP is widely used, it has some limitations:

- **Lack of Security**: Without SSL/TLS (HTTPS), HTTP is vulnerable to attacks like man-in-the-middle.
- **Performance Issues**: HTTP can be slow for large data transfers as it doesn’t allow multiplexing or efficient use of connections.
- **Statelessness**: Since each request is independent, HTTP requires additional mechanisms (like cookies, sessions) to maintain state across requests.
