Basically extending the documentation for educational purposes.

Universal app - Why?

1. SEO
2. Performance
3. Cross device support
4. Same code base

Universal app - How?

1. Handle the initial render when a user (or search engine crawler) first requests our app.
2. Send the state of our app along in our response, so the client can use it as the initial state.
3. Create a fresh, new Redux store instance on every request.
4. Optionally dispatch some actions.
5. Pull the state out of store.
6. and then pass the state along to the client.

Check server.js for detailed comments.

# React-Meetup

https://github.com/reactjs/react-router/blob/master/docs/guides/ServerRendering.md

https://github.com/makeomatic/redux-connect/


## slides
[Salvatore Mazzarino](https://github.com/strvcom/React-Meetup/blob/master/static/SalvatoreMazzarino-React-Meetup.key)

[Daniel Hejl](https://github.com/strvcom/React-Meetup/blob/master/static/DanielHejl-STRV-React.js-meetup.key)
