Basically extending the documentation for educational purposes.

Universal app - main players on server side:
1. react
2. react-router
3. react-redux

Universal app - Why?

1. SEO
2. Performance
3. Cross device support
4. Same code base
5. Catching current trends ;)

Universal app - How?

1. Handle the initial render when a user (or search engine crawler) first requests our app. When the server receives the request, it        renders the required component(s) into an HTML string, and then sends it as a response to the client. From that point on, the client     takes over rendering duties.
2. Send the state of our app along in our response, so the client can use it as the initial state. if we preload any data before            generating the HTML, we want the client to also have access to this data. Otherwise, the markup generated on the client won’t match      the server markup, and the client would have to load the data again.
3. Create a fresh, new Redux store instance on every request.On the client side, a new Redux store will be created and initialized with     the state provided from the server.
4. Optionally dispatch some actions.
5. Pull the state out of store.
6. Pass the state along to the client.

Check server.js for detailed comments.

# Links:
Universal rect explained

https://ifelse.io/2015/08/27/server-side-rendering-with-react-and-react-router/

https://github.com/reactjs/react-router/blob/master/docs/guides/ServerRendering.md

https://github.com/makeomatic/redux-connect/


## slides
[Salvatore Mazzarino](https://github.com/strvcom/React-Meetup/blob/master/static/SalvatoreMazzarino-React-Meetup.key)

[Daniel Hejl](https://github.com/strvcom/React-Meetup/blob/master/static/DanielHejl-STRV-React.js-meetup.key)
