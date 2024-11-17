## File Types
1. scss -   modular css. same file used multiple time will have identity for each elemen
**2. tsx**      -   optimized html with typescript
**3. ts**       -   typescript
**4. js**       -   simple typescript

## Code / Directory Structure for the Frontend / UI server
## 1. package.json - contains basic project information like author, name, version, 3rd party libraries used, dependencies, packages, etc
## 2. .env.example - contains list of variables which could be varied based on dev, test, prod environments.
## 3. public       - manages all publicly downloadable resources
###    a. css              -   generic stylesheets for complete website
###    b. images           -   static downloadable content
###    c. js               -   internal scripts required for generalized events
## 3. app - this folder contains all the business logic
###    a. components       -   comprise of holding behavior of multiple elements to deliver a functionality
###    b. elements         -   basic UI atoms, individually holds its own behavior
###    c. interface        -   data objects are stored here
###    d. page             -   handles different page list like home, plp, pdp, srp, etc
###    e. index            -   calls the router for the initial request and serves the required assets
###    f. router.ts        -   responsible for redirecting request to the page as per the request