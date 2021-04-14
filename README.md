# express_example

A Node/Express project with Pug as the template engine
------------------------------------------------------

This site is using Node.js with Express Web Server. It implements Routers to provide for code building maintainance thereby achieving separation of concerns (putting codes for routing together).

Pug
---
Pug is a template engine for Node and for the browser.

Error Handling
--------------
Use Express middleware to handle 404 and 500 errors. You can show errors in development but not production.

Routers
-------
Use Express.Router in routes/index.js to seperate the routes from the main app.js. Then use this router in app.js before the app.listen function call.

## Implementation:

1. Set up Express with Pug as template engine
2. Routes in seperate files away from the main app.js file
3. Template inheritance (The index.pug extends the layout.pug

## To test the site locally:

1. Start the Express Server using:
`npm start`

2. With the server running, use the browser to access the app at `http://localhost:3000`

3. Other pages accessible:
    - `http://localhost:3000/about`
    - `http://localhost:3000/contact`
    - `http://localhost:3000/users`
<hr>

## References

1. [expressjs](http://expressjs.com/en/starter/basic-routing.html)
2. [sitepoint](https://www.sitepoint.com/a-beginners-guide-to-pug/)
3. [expressjs](http://expressjs.com/en/guide/using-template-engines.html)