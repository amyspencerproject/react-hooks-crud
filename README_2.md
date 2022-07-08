# Amy's Notes for this Tutorial

## Install
Lots of confusion as to if the react-hooks-crud project folder should be inside of the tutorial folder. Instructions were not clear but it seems weird to me to have a project folder with its own src and node_modules, etc under a folder with the it's own src/ node_modules, etc. Moved it in and out a couple of times and decided to keep it out. So the react-hooks-crud project folder is not in the tutorial folder. 

Also begining to udnerstand that when you do installs in command line there will always be loads of warnings of various levels but unless the install is dead stopped just press forward. Especially because this is just a tutorial.

### Project Structure

- App is the container that has Router & navbar.
– There are 3 items using React hooks: TutorialsList, Tutorial, AddTutorial.
– http-common.js initializes axios with HTTP base Url and headers.
– TutorialDataService has functions for sending HTTP requests to the Apis.


### Create Data Service
In this step a data service is created that uses an axios object to send HTTP requests.

_C_reate: create
_R_etreive: getAll, get
_U_pdate: update
_D_elete: remove, removeAll
and 
FINDER: findByTitle

Call axios (imported as http) get, post, put, delete method corresponding to HTTP Requests: GET, POST, PUT, DELETE to make CRUD Operations.

### Create React Components






