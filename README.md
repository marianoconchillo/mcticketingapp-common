# Common Library for Error Handling and Middleware

This library contains common logic for error handling, middleware and event definitions that can be shared across different services in a microservices architecture. The library is published on NPM and can be downloaded and used by other services.

## Installation

You can install the package using NPM:

`npm install @mcticketingapp/common`

## Error Example

To use the error handling middleware, simply add the following code to your express app:

```Typescript
const { errorHandler } = require('@mcticketingapp/common');
app.use(errorHandler);
```

The error handler middleware will catch any unhandled errors in your express app and return an appropriate response.
