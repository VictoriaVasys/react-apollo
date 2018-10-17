# React + Apollo + Prisma Tutorial (Local Docker DB)

This is the sample project that belongs to the [React & Apollo Tutorial](https://www.howtographql.com/react-apollo/0-introduction/) on How to GraphQL.

## Running the App

### 1. Clone repository

```sh
git clone https://github.com/Joshwani/react-apollo/
```

### 2. Install dependencies & Deploy the Prisma database API

```sh
cd react-apollo/server
npm install
cd database
docker-compose up -d
prisma deploy
```

### 3. Start the server

To start the server, all you need to do is execute the `start` script by running the following command inside the `server` directory:

```sh
npm start
```

> **Note**: If you want to interact with the GraphQL APIs inside a [GraphQL Playground](https://github.com/graphcool/graphql-playground), you can also run `yarn dev`.

### 4. Run the app

Now that the server is running, you can start the app as well. The commands need to be run in a new terminal tab/window inside the root directory `react-apollo` (because the current tab is blocked by the process running the server):

```sh
npm install
npm start
```

You can now open your browser and use the app on `http://localhost:3000`.
