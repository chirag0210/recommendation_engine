## File Types
**1. scss**     -   modular css. same file used multiple time will have identity for each element</br>
**2. tsx**      -   optimized html with typescript</br>
**3. ts**       -   typescript</br>
**4. js**       -   simple typescript</br>

## Code / Directory Structure for the Frontend / UI server
1. package.json - contains basic project information like author, name, version, 3rd party libraries used, dependencies, packages, etc
2. .env.example - contains list of variables which could be varied based on dev, test, prod environments.
3. public       - manages all publicly downloadable resources</br>
    a. css              -   generic stylesheets for complete website</br>
    b. images           -   static downloadable content</br>
    c. js               -   internal scripts required for generalized events</br>
4. app - this folder contains all the business logic</br>
**a. components**       -   comprise of holding behavior of multiple elements to deliver a functionality</br>
**b. elements**         -   basic UI atoms, individually holds its own behavior</br>
**c. interface**        -   data objects are stored here</br>
**d. page**             -   handles different page list like home, plp, pdp, srp, etc</br>
**e. index**            -   calls the router for the initial request and serves the required assets</br>
**f. router.ts**        -   responsible for redirecting request to the page as per the request</br>