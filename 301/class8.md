# APIs

## Web API Design Best Practices
The more requests, the bigger the load. Therefore, try to avoid "Chatty" web APIs that expose a large number of small resources.

If your data is stored in a relational database, the web API doesn't need to expose each table as a collection of resources.

Finally, it might not be possible to map every operation implemented by a web API to a specific resource.

A web API that implements simple calculator operations such as add and subtract could provide URIs that expose these operations as pseudo resources and use the query string to specify the parameters required.

To do this, the web API should support the Accept-Ranges header for GET requests for large resources.

Versioning enables a web API to indicate the features and resources that it exposes, and a client application can submit requests that are directed to a specific version of a feature or resource.

Each time you modify the web API or change the schema of resources, you add a version number to the URI for each resource.