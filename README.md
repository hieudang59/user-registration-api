# User Registration API Sample

## How to run
- `cd user-registration-api`
- `yarn install`
- Connect a cluster in [Atlas cloud](https://www.mongodb.com/cloud/atlas):
    - Choose your driver version:
        - Driver: Node.js
        - Version: 3.6 or later
    - Get your connection string into your application code
- Update `.env` file to matches your settings, MONGODB_URL is your connection string is got above.
- `yarn start`

## The list of endpoints
- HTTP POST /users — Register users.
- HTTP POST /users/login — Allow users to login.
- HTTP GET / users/me — Get user profile.
- HTTP POST /users/logout —Logout the user
- HTTP post /users/logoutall — Logout from all devices
