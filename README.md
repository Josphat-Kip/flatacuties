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

 The server is tested by visiting the following route in the browser:

[http://localhost:3000/characters](http://localhost:3000/characters)

Then, open the `index.html` file on your browser to run the application.

The code is written in `src/index.js` file. The base URL for the API will be
[http://localhost:3000](http://localhost:3000).


## Deliverables

1. Making sure all characters are seen in the `did` with aid of `"character-bar`". Use Get request to retrieve the characters data


2. Aclicked character will display its details. This is achieved by using character information from previous request or even by making new requests i.e

   ```txt
   GET /characters/:id

   Example Response:
   {
    "id": 1,
    "name": "Mr. Cute",
    "image": "https://thumbs.gfycat.com/EquatorialIckyCat-max-1mb.gif",
    "votes": 0
   }
   ```

3. When the `form#votes-form` is submitted, add the number of votes from
   the input field to the character that is displayed in the `div#detailed-info`.
