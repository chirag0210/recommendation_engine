# Code / Directory Structure for the Backend / API server
### 1. package.json - contains basic project information like author, name, version, 3rd party libraries used, dependencies, packages, etc
### 2. .env.example - contains list of variables which could be varied based on dev, test, prod environments.
### 3. app - this folder contains all the business logic
&nbsp;&nbsp;&nbsp;&nbsp;**a. server.ts        -**   starts the api server to listen to the incoming request</br>
&nbsp;&nbsp;&nbsp;&nbsp;**b. middleware.ts    -**   validates any incoming requests if authentic and authorized</br>
&nbsp;&nbsp;&nbsp;&nbsp;**c. config           -**   contains all the static data, like external routes, codes, messages, etc</br>
&nbsp;&nbsp;&nbsp;&nbsp;**d. connector        -**   responsible for maintaining continuous connection with database, queues, etc</br>
&nbsp;&nbsp;&nbsp;&nbsp;**e. controller       -**   responsible for data validation, action required and response to request handling</br>
&nbsp;&nbsp;&nbsp;&nbsp;**f. entity           -**   responsible for all db operations based on models</br>
&nbsp;&nbsp;&nbsp;&nbsp;**g. helpers          -**   handles logic to transform data</br>
&nbsp;&nbsp;&nbsp;&nbsp;**h. interface        -**   stores the required type of data and objects</br>
&nbsp;&nbsp;&nbsp;&nbsp;**i. middleware       -**   different validation and guards are maintained here</br>
&nbsp;&nbsp;&nbsp;&nbsp;**j. models           -**   schema for each entity with relationship with different models and pre / post processing methods are defined here</br>
&nbsp;&nbsp;&nbsp;&nbsp;**k. router           -**   responsible for maintaining and serving data as per the request</br>
&nbsp;&nbsp;&nbsp;&nbsp;**l. service          -**   business logic to serve desired response for each dataset</br>