# Url-Shortener
# URL Shortener Service – Java + Spring Boot + H2

A simple RESTful service that shortens long URLs, tracks clicks, and redirects users.

## Features
- Accepts long URLs and generates Base62 short codes
- Redirects short URLs to original long links
- Tracks click count for each short URL
- Uses in-memory H2 database
- Swagger UI API documentation

## How to Run
1. Import into Eclipse or IntelliJ as a Maven project
2. Run `UrlShortenerApplication.java`
3. Use `/api/shorten` to shorten and `/api/{code}` to redirect

## H2 Console
- Visit: `http://localhost:8080/h2-console`
- JDBC URL: `jdbc:h2:mem:urlshortener`

## Swagger UI
- Visit: `http://localhost:8080/swagger-ui.html`

## Author
Kona Sahithi – July 2025
