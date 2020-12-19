# URL Shortener Example using Spring Boot & Redis

This example shows a simple URL Shortener implementation using
- Spring Boot 2.1.0 (Spring Web[MVC] + Spring Data Redis)
- Guava 18.0
- Common Validator 1.6

### URLs
- POST `/rest/url` with body as `long_url_string` - For creating the short url from long url
- GET `/rest/url/{id}` - For retrieving the long URL from short `id`

#Redis Cache

- By default redis cache will connect to localhost:6379

#Docker command to run redis

- docker run --name my-first-redis -p 6379:6379 redis