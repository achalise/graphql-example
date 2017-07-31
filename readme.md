# Exploring GraphQL

Trying out tuotorial from [GraphQL: Learn by Doing](https://edgecoders.com/graphql-learn-by-doing-part-1-of-3-9b04cadeacfa), 
to understand how it could be used for a Backend for Front End (BFF) solution.



Prerequisites: `npm install --save graphql express express-graphql` - to install `express` and express implementation of `GraphQL`
                `npm install --save babel-cli babel-core babel-loader babel-preset-es2015` - so that we can write our code in ES6, and have it compiled before running it on Node.
                  

Update `scripts` entry in `package.json` to include
`"start": "./node_modules/.bin/babel-node --presets es2015 ./server.js"`
                  
And run it: `npm start`

Now the `GraphiQL` query explorer can be accessed at:
`http://localhost:8888/GraphQL`