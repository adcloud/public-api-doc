Adcloud Public Api Documentation
================================

The Adcloud Public Api Documentation serves as a starting point for developers who wish to interact with the adcloud api.

This documentation is constantly updated so please check back for the latest information.


[View the documentation](http://dev.adcloud.com/public-api-doc/ "View the documentation")


Getting Started
---------------

The Adcloud Api is a restful api and as such can be accessed using:

* curl
* https://github.com/jkbr/httpie.git (curl for humans)
* From the Google Chrome browser after installing the  "Postman Rest Client"
* From the Firefox browser after installing the  "RestClient"

### Authentication

The Adcloud api provides access via 2-prong OAuth.

In order to obtain access:

1. you will need to register your interest in accessing the api with support@adcloud.com
2. once registered; you will be provided with a client_id & client_secret
3. the client_id & client_secret are then used to request an "access token" from the api - see: Oauth Documentation
4. this "access token" is this added to every request as a url parameter https://api.adcloud.com/?access_token={{ your_access_token }}