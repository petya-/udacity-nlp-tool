# Evaluate a news article with Natural Language Processing

This web tool allows users to run Natural Language Processing (NLP) on articles or blogs found on other websites. This will be possbile by using an exciting new api called [Aylien](https://developer.aylien.com) and a simple web interface to interact with their NLP system. This tool gives back pertinent information about the article, like whether the content is subjective (opinion) or objective (fact-based) and whether it is positive, neutral, or negative in tone.

The project is built with:

1. NodeJS and Express
2. SASS
3. Webpack

## Project Setup

Follow the instructions below to setup the project locally.

### Environment Setup

Create a `.env` file from `.env.example` and add populate it with your aylienAPI keys

```bash
copy .env.example .env
```

### Install Dependencies

Run the following command:

```js
npm install
```

### Bundle modules

Run the following command if you want to bundle the modules for production:

```js
npm run build-prod
```

or in development mode:

```js
npm run build-dev
```

### Running the server

Run the following command to run the server:

```js
npm start
```

### Running the tests

Run the following command to run the server:

```js
npm test
```

or run tests in watch mode:

```js
npm run test:watch
```

## Deployment

You can find the api hosted on [Heroku](https://udacity-nlp-tool.herokuapp.com/)

## Udacity Project Requirements:

- [x] Be set up with Webpack, Express, Node, and Sass, and Service Workers

- [x] Have separate dev and prod configurations for Webpack

- [x] Have the developer environment set up with the Webpack dev server

- [x] Have a minimum of one form field

- [x] Make one request to the Aylien API

- [x] Use Sass for styling

- [x] Minify js and styles in the production environment

- [x] Response from the API must be added to the view for a user to see

- [x] Be able to show content offline

- [x] JS files are tested with Jest
