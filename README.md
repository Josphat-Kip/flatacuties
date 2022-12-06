# Flatacuties
This is building an app used for voting cutest animals among the given five. Local API is used so as to build the frontend for the application.


## Demo

The  gif below serves as an example of how the app should work.

![Demo](assets/demo.gif)



## Setup

To start up, I run the below command to get the backend started:

```sh
json-server --watch db.json
```

 I also need to test the server using the following route in the browser:

[http://localhost:3000/characters](http://localhost:3000/characters)

Next, I open the `index.html` file on the browser so that I run the application.

I also write the code in `src/index.js` file. where the base URL for the API is the one below
[http://localhost:3000](http://localhost:3000).



## Deliverables

1. All characters must be seen in the `did` with aid of `"character-bar`"by using GET request as to get character's data.

2. The clicked character must display its details. 
3. `Form#votes-form` should be submitted and also add number of votes from input field.

