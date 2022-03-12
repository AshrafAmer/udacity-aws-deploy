# Udagram

Udacity Full Stack Nanodegree third project, Deploy udagram Full Stack App to AWS.

## Getting Started

1. Clone this repo locally into the location of your choice.
1. Open a terminal and navigate to the udagram-frontend.
1. run `npm install` or `yarn` to install frontend App dependencies.
1. Navigate to the udagram-api.
1. run `npm install` or `yarn` to install backend server dependencies.
1. copy `.env.example` to `.env` and replace it with correct config data.
1. RUN `yarn start` or `npm run start`.
1. Without closing the terminal in prev step navigate to the udagram-frontend and start the app with `yarn start` or `npm run start`.

The project can run but if missing some information to connect to the database and storage service, it will be crashed.!

### Dependencies

```
- Node v14.15.1 (LTS) or more recent. While older versions can work it is advisable to keep node to latest LTS version

- npm 6.14.8 (LTS) or more recent, Yarn can work but was not tested for this project

- AWS CLI v2, v1 can work but was not tested for this project

- A RDS database running Postgres.

- A S3 bucket for hosting uploaded pictures.

```

## Testing

This project contains two different test suite: unit tests and End-To-End tests(e2e). Follow these steps to run the tests.

1. navigate to `udagram-frontend`
1. run `npm run test`
1. run `npm run e2e`

There are no Unit test on the back-end

### Unit Tests:

Unit tests are using the Jasmine Framework.

### End to End Tests:

The e2e tests are using Protractor and Jasmine.

## Built With

- [Angular](https://angular.io/) - Single Page Application Framework
- [Node](https://nodejs.org) - Javascript Runtime
- [Express](https://expressjs.com/) - Javascript API Framework

## License

Udacity Full Stack Nanodegree Program.
