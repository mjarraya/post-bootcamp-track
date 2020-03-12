# Architecture

During the course, we have covered two ways of building a full stack application. First, we built multiple-page applications with the MVC pattern, and then we moved on to single-page applications communicating with a REST API.  
As you can imagine, there are other approaches, aiming to tackle different problems.

## GraphQL

GraphQL was engineered at facebook to answer the following problem: say you have a desktop app and a mobile app, both communicating with a server to retrieve data. And we'll assume that the desktop app requires more data from the server than the mobile app (because it can afford to display more content). This means that on requests that are made by the mobile app, a lot of data is unused.  
Instead of duplicating all endpoints (for every version of your application), graphQL will, over a single endpoint, retrieve data based on the fields in the query. Problem solved: you only request the information that you need.  

[graphql.org](https://graphql.org/)  
[GraphQL: The Documentary via Honeypot](https://www.youtube.com/watch?v=783ccP__No8)  
[A Guide to GraphQL in Plain English on freeCodeCamp](https://www.freecodecamp.org/news/a-beginners-guide-to-graphql-60e43b0a41f5/)  
[howtographql](https://www.howtographql.com/)  

## WebSockets

If our application necessitates realtime, for example a game, chat or notifications, we have multiple approaches from HTTP polling to [Server-sent events](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events/Using_server-sent_events) with their [advantages and drawbacks](https://medium.com/platform-engineer/web-api-design-35df8167460). One of these approaches which is very popular for bigger scale projects because of the increased performance it brings is using the WebSocket protocol (instead of HTTP).  

[A Simple Chat App with React, Node and WebSockets](https://blog.bitlabstudio.com/a-simple-chat-app-with-react-node-and-websocket-35d3c9835807)  
[WebSocket Guides on MDN](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API#Guides)  
[socket.io](https://socket.io/)  

## Server-side rendering

The React apps we built (with create-react-app) can be labeled as client-side rendered (CSR). When we make the initial request, we receive a response as an almost empty HTML file and proceed to download our React application. Two main drawbacks stem from this method: first, until the React application is downloaded, the browser isn't displaying anything (remember the HTML that we get from the initial request is almost empty), and because the rendering happens when we've finished downloading the React app, there is nothing for search engines crawlers to index, and the app will perform poorly in terms of SEO.  
Another method is to generate the rendered page on the server, and that is called server-side rendering (or SSR).  

![SSR perfromance benefit](https://miro.medium.com/max/4465/1*CRiH0hUGoS3aoZaIY4H2yg.png)
[The Benefits of SSR over CSR by Walmart Labs](https://medium.com/walmartlabs/the-benefits-of-server-side-rendering-over-client-side-rendering-5d07ff2cefe8)  

## Gatsby

Gatsby.js is a react framework that is meant to be a static site / progressive web app generation. It's very intuitive and a great way to also start dipping your toes into the world of GraphQL. It's Server Side Generated at build time. Which means that it pre-fetches all the necessary data when the website builds.

## Next

Next.js is a React framework whose main features are server rendering and static site generation (see this post about the [JAMstack](https://snipcart.com/blog/jamstack)).

[Next.js](https://nextjs.org)  
[Docs](https://nextjs.org/docs/getting-started)  
[Learn (tutorial to build and deploy your first Next app)](https://nextjs.org/learn/basics/getting-started)  

## Nuxt

Nuxt.js is the same but for [Vue.js](https://vuejs.org/).

[Nuxt.js](https://nuxtjs.org/)  


