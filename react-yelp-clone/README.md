# React Tutorial: Build a Yelp Clone

A lightweight clone of Yelp using React.

## Quickstart

First, clone the repository:

```bash
git clone https://github.com/fullstackreact/react-yelp-clone.git react-yelp-clone
cd react-yelp-clone

# install the dependencies
npm install

# copy configuration (see below)
cp .env.example .env

# start the server
npm start
```

## Configuring the Application

This app uses [dotenv](https://github.com/bkeepers/dotenv) for configuration. In order to configure the application for your own api access, [grab an api token from Google here](https://developers.google.com/maps/documentation/javascript/) and set it in a file called `.env` at the root for a key called `__GAPI_KEY__`.
For instance, say that your gapi key is: `abc123`. Your `.env` file should look like:

```bash
GAPI_KEY=abc123
```

You can also create this file by copying the `.env.example` file at the root:

```bash
cp .env.example .env
```

## Starting the Application

```bash
npm install 
npm start
```

## Libraries We Have Used

This app uses the following technologies:

* [webpack](https://webpack.github.io)
* [postcss](http://postcss.org)
* [hjs-webpack](https://github.com/HenrikJoreteg/hjs-webpack)
* [react.js](http://facebook.github.io/react/)
* [react-router](https://github.com/reactjs/react-router)
* [Google Maps API](https://developers.google.com/maps/)
* [google-maps-react npm](https://github.com/fullstackreact/google-maps-react)
* [enzyme](https://github.com/airbnb/enzyme)
* [chai](http://chaijs.com)
* And much much more

## Running the Tests

The application is built using tests, including the fantastic [enzyme](https://github.com/airbnb/enzyme) and [chai](http://chaijs.com) libraries. To run the tests, use the `npm` test script:

```shell
npm run test
```

Check out the blog post for more information on how this app was built and a complete tutorial on using React to build your own apps.

___

## License
 [MIT](/LICENSE)

