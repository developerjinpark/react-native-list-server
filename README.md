# Mock Authentication Server
This is a simple mock auth server. You can POST to any endpoint and it will act as a login.

There is only one user with username: `username` and password: `password`.
There is no way to add new users.

## Installation
- Install dependencies with `yarn add`
- Run the server with `yarn start`
- Visit [http://localhost:8000](http://localhost:8000)
  - You can optionally declare a `PORT` env variable to override the default port: `PORT=12345 yarn start`
