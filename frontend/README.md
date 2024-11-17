## File Types
**1. scss**     -   modular css. same file used multiple time will have identity for each element</br>
**2. tsx**      -   optimized html with typescript</br>
**3. ts**       -   typescript</br>
**4. js**       -   simple typescript</br>

## Code / Directory Structure for the Frontend / UI server
&nbsp;&nbsp;**1. package.json** - contains basic project information like author, name, version, 3rd party libraries used, dependencies, packages, etc
&nbsp;&nbsp;**2. .env.example** - contains list of variables which could be varied based on dev, test, prod environments.
&nbsp;&nbsp;**3. public**       - manages all publicly downloadable resources</br>
&nbsp;&nbsp;&nbsp;&nbsp;***a. css***              -   generic stylesheets for complete website</br>
&nbsp;&nbsp;&nbsp;&nbsp;***b. images***           -   static downloadable content</br>
&nbsp;&nbsp;&nbsp;&nbsp;***c. js***               -   internal scripts required for generalized events</br>
&nbsp;&nbsp;**4. app** - this folder contains all the business logic</br>
&nbsp;&nbsp;&nbsp;&nbsp;***a. components***       -   comprise of holding behavior of multiple elements to deliver a functionality</br>
&nbsp;&nbsp;&nbsp;&nbsp;***b. elements***         -   basic UI atoms, individually holds its own behavior</br>
&nbsp;&nbsp;&nbsp;&nbsp;***c. interface***        -   data objects are stored here</br>
&nbsp;&nbsp;&nbsp;&nbsp;***d. page***             -   handles different page list like home, plp, pdp, srp, etc</br>
&nbsp;&nbsp;&nbsp;&nbsp;***e. index***            -   calls the router for the initial request and serves the required assets</br>
&nbsp;&nbsp;&nbsp;&nbsp;***f. router.ts***        -   responsible for redirecting request to the page as per the request</br>