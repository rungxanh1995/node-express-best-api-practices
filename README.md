# REST API Best Practices - JS, Node, Express

## About
A sample demo project, portraying some best practices in designing and maintaining a backend API.

Stopped before the part `Group associated resources together (logical nesting)`.

For detailed info, refer to the [original tutorial post](https://www.freecodecamp.org/news/rest-api-design-best-practices-build-a-rest-api/).

## Architecture
3 Layer Architecture: `(Router)` <-> `Controller` <-> `Service` <-> `Data Access`

Illustration below
![architecture](screenshots/layers.png)

## Prominent Concepts
* Separation of concerns w/ different architecture layers
* Versioning of routes
* Throwing and handling errors
* Easy-to-understand error message

## Getting Started
1. Clone the repo
2. Open Terminal at root level and run: `npm install`
3. Start the server with `npm run dev`
