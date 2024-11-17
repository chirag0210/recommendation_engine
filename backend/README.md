Code / Directory Structure for the Backend / API server
1. package.json - contains basic project information like author, name, version, 3rd party libraries used, dependencies, packages, etc
2. .env.example - contains list of variables which could be varied based on dev, test, prod environments.
3. app - this folder contains all the business logic
    a. server.ts        -   starts the api server to listen to the incoming request
    b. middleware.ts    -   validates any incoming requests if authentic and authorized
    c. config           -   contains all the static data, like external routes, codes, messages, etc
    d. connector        -   responsible for maintaining continuous connection with database, queues, etc
    e. controller       -   responsible for data validation, action required and response to request handling
    f. entity           -   responsible for all db operations based on models
    g. helpers          -   handles logic to transform data
    h. interface        -   stores the required type of data and objects
    i. middleware       -   different validation and guards are maintained here
    j. models           -   schema for each entity with relationship with different models and pre / post processing methods are defined here
    k. router           -   responsible for maintaining and serving data as per the request
    l. service          -   business logic to serve desired response for each dataset