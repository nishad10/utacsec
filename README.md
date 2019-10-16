<img src="https://pbs.twimg.com/profile_images/887044871445295105/9bQlT5Xi_400x400.jpg" height="50" width="50">
<h1 position="relative">UTA CSEC WEBSITE</h1>

This will be the repo for the website for the Cybersecurity club for the University of Texas at Arlington.

## LIVE
Site is still in development but is live at https://www.utacsec.org/

Any feedback is appreciated.

### Contact
Email- uta.csec@gmail.com

Twitter- https://twitter.com/UTA_CSEC

Discord- https://discord.gg/F9wZjBe

## Boilerplate

The repo was initialized using the boilerplate for MERN from this repo. 

https://github.com/amazingandyyy/mern

Refer to the above repo Readme for a more detailed and general information on deployment, this will only cover dev environment setup, till we have the website in development.

I have made further changes to the initial structure and setup of the code.

## Code structure

The website will be MERN fullstack

> MERN is a fullstack implementation in MongoDB, Expressjs, React/Redux, Nodejs.

React as a base

Redux for state management

Saga or Thunk for middleware

## Installation and setup

### Prerequirements
- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^10.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

NOTE :- You need client and server running concurrently in different terminal session, in order to make them talk to each other

### Clone or download
```terminal
$ git clone https://github.com/nishad10/utacsec.git
$ npm i
```

## Client-side usage(PORT: 3000)
```terminal
$ cd client   // go to client folder
$ npm i       // npm install pacakges
$ npm run dev // run it locally
```

## Server-side usage(PORT: 8000)

### Prepare your secret

run the script at the first level:

(You need to add a JWT_SECRET in .env to connect to MongoDB just add JWT_SECRET=something in .env file)

```terminal
// in the root level
$ echo "JWT_SECRET=YOUR_JWT_SECRET" >> ./server/src/.env
```

### Start

```terminal
$ cd server   // go to server folder
$ npm i       // npm install pacakges
$ npm run dev // run it locally
$ npm run build // this will build the server code to es5 js codes and generate a dist file
```

## Contributing

If you want to help me with this please join the discord so we can talk about it.

Discord- https://discord.gg/F9wZjBe

If you want to add a feature to the website I would appreciate if you follow the code structure we have in place, if you have any questions about the structure of the code feel free to contact me. 

Name- Nishad Aherrao

Email- nishad.aherrao10@gmail.com

## License
[MIT](https://github.com/nishad10/utacsec/blob/master/LICENSE)
