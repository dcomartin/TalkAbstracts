# Building Self Describing Web APIs

## Abstract

Does your web API expose your database structure and provide GET/POST/PUT/DELETE as way to expose CRUD operations?  Do your clients have to read your documentation to know the control logic/workflow?  HTTP endpoints that represent your database entities couples your consuming clients to the internals of your application, making it much harder to change your API.

In this presentation we're going to learn how to go beyond serializing a database row into json by leveraging hypermedia to write self-describing APIs.