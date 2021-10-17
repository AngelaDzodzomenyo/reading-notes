# Readings: APIs

## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?

    * Representational State Transfer

2. REST APIs are designed around a ____.

    * architectual approach to designing web services

3. What is an identifer of a resource? Give an example.

    * URI. A page, a book, or a dociment

    [Image](https://danielmiessler.com/images/url-uri-url-miessler-2020.png)

    * All URLs are URIs, but not all URIs are URLs

4. What are the most common HTTP verbs?

    * GET, POST, PUT, PATCH, DELETE

5. What should the URIs be based on?

    * Resource URIs should be based on nouns(the resources) and not verbs (the operations on the resource)

6. Give an example of a good URI.

    * https://myprofile.com/AboutMe

7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

    * Web APIs that expose a large number of small resources. Bad thing bc retrieving large items can increase the latency of a request and incur additional bandwidth costs.

8. What status code does a successful GET request return?

    * Returns HTTP status code 200(OK).

9. What status code does an unsuccessful GET request return?

    * If cannot be found the method should return 404(Not Fiound)

10. What status code does a successful POST request return?

    * HTTP status code 201(Created)

11. What status code does a successful DELETE request return?

    * HTTP status code 204(No Content), indicates that the process has been successfully handled. If not it returns a HTTP 404(Not found)

## Bookmark/Skim

[RegExr](https://regexr.com/) - Pay particular attention to the cheatsheet
[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
[Regex 101](https://regex101.com/)