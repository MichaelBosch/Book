# Web API

The Web API integration point exposes scripts through a url.

The url will look something like the following:
http://remotesitecore/-/script/v2/master/homeanddescendants?user=admin&password=b

Here's the url broken down:

* **API Version** - Specifies which service is being requested.
  * v2 - This is the service that executes scripts stored in the integration point library.
* **Database** - Specifies which database contains the script.
  * master - This database requires the credentials to be provided.
* **Script** - Specifies the name of the script contained in the database.
  * homeanddescendants - Replace this name with whatever your script is called in the Web API library.
* **Query String Parameters** - Specifies the additional bits of data for use by the web service.
  * user and password - Authenticates the request and in most cases will be needed. If the script is published to the *web* database the credentials are not required.
  * scriptArguments - The PowerShell hashtable containing the query string parameters.

**Note:** Examples included in the following modules
* Getting Started

### Security

The integration point can be completely disabled through configuration as described [here](security.md) for Restfulv2.

### References

* Watch Adam present this and much more on Sitecore! Experienced [here][1].

[1]: https://vimeo.com/134196432