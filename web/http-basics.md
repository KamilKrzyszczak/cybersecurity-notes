# HTTP Basics for Web Security

## Why it exists
HTTP is the foundation of communication between clients and web applications.

## How it works
Client sends a request → server processes it → server returns a response.
HTTP is stateless by design.

## OSI Layer
Layer 7 – Application.

## Security relevance
Most web vulnerabilities exist because of improper handling of user input,
authentication, sessions, and headers.

## Real-world HTTP requests
Modern browsers send many additional headers related to
security, context and optimization (e.g. Sec-Fetch-*, Sec-CH-UA).
Understanding these headers is important for analyzing
real-world web traffic and security issues.

## HTTP versions in practice
While modern browsers often use HTTP/2, tools like Burp Suite
may display or resend requests as HTTP/1.1.
From a security perspective, the attack surface remains the same.

## Tools / Commands
- Browser DevTools
- curl
- Burp Suite

## Key takeaways
Understanding HTTP is essential before using tools like Burp Suite
or learning OWASP Top 10.

