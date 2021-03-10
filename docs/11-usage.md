# Usage
This is a basic walkthrough the API.

## Prerequisites
You need an __username__, a __password__ and the __endpoint uris__ to authenticate yourself.

## Initiliazing the API
```java
new Api(
  new URI("https://dev-cloud.acronis.com/fc/api/v1"),
  new URI("https://dev-cloud.acronis.com/api/2/idp"),
  "username",
  "password"
);
```