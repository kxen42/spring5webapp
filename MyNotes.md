# My Notes on API Design and OpenAPI

Rather than using OAS v3.0.2 that the course covers, I am using OAS v3.1.0.

Most important resources for this repo:
- [brewery_example.yaml](src/main/resources/static/brewery_example.yaml)
- [KCHRISTENSON42_1-springframeworkguruopenapicourse-1.0-oas3.1-resolved.yaml](static/KCHRISTENSON42_1-springframeworkguruopenapicourse-1.0-oas3.1-resolved.yaml)
- [SwaggerHub for this API](https://app.swaggerhub.com/apis/KCHRISTENSON42_1/openapi-brewery/1.0-oas3.1#/default/get_v1_beers__beerId_)


# API Design Guides
[API Guides Portal: Definitions, Examples, and Tutorials to Get Started | Stoplight](https://stoplight.io/guides)

[Introduction  -  REST API Tutorial](https://www.restapitutorial.com/introduction)

[API Development: A Comprehensive Guide to Building Modern APIs](https://www.getambassador.io/blog/api-development-comprehensive-guide#body__7a44950c2ef3)

[Principles of Web API Design: Delivering Value with APIs and Microservices](https://www.oreilly.com/library/view/principles-of-web/9780137355754/) by James Higgingotham. Published December, 2021.

[Richarson Maturity Model](https://restfulapi.net/richardson-maturity-model/)

[Mastering API Architecture
Mastering API Architecture](https://www.oreilly.com/library/view/mastering-api-architecture/9781492090625/) by James Gough, Daniel Bryant, Matthew Auburn. Published October, 2022.

[REST in Practice](https://www.oreilly.com/library/view/rest-in-practice/9781449383312/) by Jim Webber, Savas Parastatidis, Ian Robinson. Published September, 2010.

# Specific Sections of OpenAPI Specification v3.1.0
### Required
[OpenAPI Object](https://spec.openapis.org/oas/latest.html#openapi-object) openapi<br>
[Info Object](https://spec.openapis.org/oas/latest.html#info-object) openapi.info<br>
[Paths Object](https://spec.openapis.org/oas/latest.html#paths-object) openapi.paths<br>
[Server Object](https://spec.openapis.org/oas/latest.html#server-object) openapi.servers<br>

### Optional
[Schema Object](https://spec.openapis.org/oas/latest.html#schema-object)<br>
- [JSON Schema Validation 9.4 "readOnly and "writeOnly"](https://datatracker.ietf.org/doc/html/draft-bhutton-json-schema-validation-00#section-9.4) 
    - readOnly example use is for ID created by service.
    - writeOnly example use is for password provided by client.

# Resources

#### Learning
[Learn OpenAPI Specification (OAS)](https://learn.openapis.org)<br>
[Learn X in Y minutes Where X = YAML](https://learnxinyminutes.com/docs/yaml/)<br>


#### Specifications
[JSON Schema Specification](https://json-schema.org/specification)<br>
[JSON Schema Validation](https://datatracker.ietf.org/doc/html/draft-bhutton-json-schema-validation-00)<br>
[OpenAPI Home](https://www.openapis.org)<br>
[GitHub OpenAPI Specification - OAS](https://github.com/OAI/OpenAPI-Specification/)<br>

#### Tools
[SwaggerHub](http://swagger.io/tools/swaggerhub)<br>
[Stoplight](https://stoplight.io) EDJ used this. "Design, document, and build APIs faster.
"<br>
