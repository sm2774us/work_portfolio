# Thinkter-Frontend-Only: A Kotlin React-JS Example

Thinkter is an example of a full-stack Web application built with Kotlin. The backend runs on the JVM, and the browser
front-end uses React. The example implements a very simple microblogging application.

This fork is a stripped down version of Thinkter consisting of the React-JS based front end only.
It may be easier to understand for some of us, and serve as a base for your own projects with a different choice for the backend.

The UI is built with react. [React](https://facebook.github.io/react/). To adapt the React APIs to Kotlin,
it incorporates a set of [wrappers](https://github.com/orangy/thinkter/tree/master/frontend/src/org/jetbrains/react), which
you can also use in your projects and adapt to your needs.

The project is built using webpack and the [Kotlin frontend plugin](https://github.com/kotlin/kotlin-frontend-plugin). 

To run the frontend, use `./gradlew frontend:run`. This will start a webpack server on port 8080. Navigate to http://localhost:8080 
to start using the application.

## Modifications
The project now only consists of the contents of the frontend-sub-directory of the original Thinkter app. The build file has been updated to be self contained. 
The web-pack configuration in the build file has bben changed to remove delegation to the backend. 
Instead a directory for static files has been created, that holds the `index.html` file and the `favicon`. 

## Backend

There is no backend. Backend functionality is mocked in the frontend. But the RPC class is still there and can be connected to
any Rest-backend.

## Future
This is just a study project to help playing with Kotlin and react. Updates are not likely.
