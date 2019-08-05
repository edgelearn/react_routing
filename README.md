# ReactJS Routing

Run the following command to get a basic ReactJS application setup with Redux:

```
npx create-react-app my-app
cd my-app
yarn start

```

1. Setup Router Package

```
npm install react-router-dom
```

2. Setup Routes

* Create 2 components in separate JS files

* Setup the Router to use / for the App.js and 2 other paths for the 2 components created.

* Try in the browser to confirm that it is working.

3. Use Props for routes

* Modify one of the routes to include an ID as part of the URL

* Display the ID when that route is viewed by getting it from the props.

4. Parsing Query Parameter

* Print the query string in the other component from the props available.

* Install the query-string module

* Use the query-string to get each query parameter separately.

5. Parsing URL Fragment

* Add content to one of the components with several anchor tags

* Install https://github.com/rafrex/react-router-hash-link

* Set it up so that it will do a smooth scroll to the elements

6. Navigating on Link Click

* Modify the Router to have Links for the 3 routes at the top of the page

After you have completed all of the exercises, commit your changes with the following command:

```
git commit -am "ReactJS Routing Examples"
```
