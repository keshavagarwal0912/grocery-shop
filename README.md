# Grocery Shop

Grocery shop is an assignment.

# Screenshots

![image](https://user-images.githubusercontent.com/97944847/200615373-96e903a7-a814-4dac-9d40-6f0943717104.png)
![image](https://user-images.githubusercontent.com/97944847/200615490-b6c22c36-4165-44b2-8b34-075c7d925d1d.png)
![image](https://user-images.githubusercontent.com/97944847/200615623-2b9ac850-0ff9-48a2-b43a-e0cf529e4367.png)
![image](https://user-images.githubusercontent.com/97944847/200615778-528eab6d-bc2d-4a02-89ae-eeef3be133f6.png)
![image](https://user-images.githubusercontent.com/97944847/200616000-835a03f4-d4e4-4a62-980b-5611d10d0df9.png)
![image](https://user-images.githubusercontent.com/97944847/200616116-2e058e4c-d150-4b7e-8182-dbe9211697e1.png)
![image](https://user-images.githubusercontent.com/97944847/200616193-314347c7-2919-450d-bbe9-54abb1a7fc7a.png)


## Tech Stack

| Frontend     | Backend      |
|:-------------|:-------------|
| React        | Node.js      |
| React Router | Express.js   |
| Redux        | MongoDB      |


**Note:** the `master` branch is the current production build. `releases` contain latest deployment tests. `develop` contains all new features and build.

### Client Side

```bash
$ cd client   # go to the client folder
$ npm i       # install packages
$ npm start   # run the client side statically with react-scripts
```

### Server Side

Create a `.env` file in the server directory and insert the following code. Replace the values with your credentials.

```dotenv
# DATABASE CONNECTIVITY
CONNECTION_URL=

# JWT SECTION
JWT_SECRET_KEY =
JWT_AUTH_TTL = 
JWT_CHECKOUT_TTL = 

# EMAIL SECRETS
SENDGRID_KEY = 

# PAYMENT SECRETS
STRIPE_PRIVATE_KEY = 
```

Start the server

```bash
$ cd server   # go to the server folder
$ npm i       # install packages
$ npm start   # start the server
```

