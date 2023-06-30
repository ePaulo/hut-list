# Hut List part 2

## Reserve a hut from the list

### Task

Now you have a list of hubs that are able to be reserved we want a hut's reservation to be linked with the user.

### Pre-req

The expectation will be to write the task in typescript and use react. (The axios library)[https://axios-http.com/docs/intro] should be used to interact with the API and then that response should be stored in react state.

The APIs are made via (JSON server)[https://github.com/typicode/json-server]

### Setup

- run the command "api" to start the JSON server and its APIs
- click the "Format Document once you are happy with the work to format the file

### Tasks

- Fetch the hub list data from the API `/hubs` example `http://localhost:1234/hubs`
- Fetch the profile data from the API `/profile`
- Create a user id in local storage from the profile data to then use it when reserving a hut
- Save the user with the chosen hut when the reserve button is clicked

### Style

Whilst working on the task I would like to see the following:

- a set folder structure for the task
- breakdown of the app component into smaller components

### Bonus

- Create a (custom hook)[https://react.dev/learn/reusing-logic-with-custom-hooks] to encapsulate particular behaviours or business logic
