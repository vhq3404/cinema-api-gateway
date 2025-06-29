This project uses [Express Gateway](https://www.express-gateway.io/) to manage and route API requests to various microservices in the movie booking platform.

## Available Scripts

In the project directory (where the Express Gateway is initialized), you can run:

### `npm start`

Runs the API Gateway in development mode on **[http://localhost:8080](http://localhost:8080)**.

All incoming API requests will be routed through this gateway to the appropriate microservices based on the defined endpoints and pipelines in `gateway.config.yml`.

The gateway will reload when you make changes (if `nodemon` or a similar tool is used).  
You may also see logs and routing information directly in the console.
