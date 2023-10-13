#Brief description of API

##API

An API, or application programming interface, is a collection of rules that allows various apps to communicate with one another. It serves as an intermediary layer for data transfers across systems, allowing businesses to provide their application data and functionality to third-party developers, business partners, and internal departments inside their organisations. An API's definitions and protocols assist businesses in connecting the many various applications they use in day-to-day operations, saving employees time and breaking down walls that impede cooperation and creativity. API documentation serves as an interface for communication between programmes, making application integration easier.

## API Endpoints
  1. postName
     Description: This endpoint is used to add data to the database.
     HTTP Method: POST
  2. printName
     Description: This endpoint is used to display the data fromn the database.
     HTTP Method: GET
  3. updateName
     Description: This endpoint is used to update data from the database.
     HTTP Method: PUT
  4. deleteName
     Description: This endpoint is used to delete data from the database.
     HTTP Method: DELETE

## Request Payload
  1. JSON request payload for postName:
     Structure:
     ```json
       {
         "lname":"necida",
         "fname":"justine"
       }

     Required Fields:
      lname: The last name of the person.
      fname: The first name of the person.

  3. JSON request payload updateName:
      Structure:
     ```json
        {
          "id":1,
          "lname":"necida",
          "fname":"justine"
        }

     Required Fields:
      id: Identifier
      lname: The last name of the person.
      fname: The first name of the person.

  4. JSON request paylod deleteName:
     Structure:
     ```json
       {
         "id": 1
       }

      Required Fields:
      id: Identifier

## Response
  Structure:
  ```json
      {
         "status":"success",
         "data":null
      }

 ## Usage
You can use the API by sending HTTP queries to the appropriate endpoints with your favourite HTTP client or programming language.

## License

## Contributors

https://github.com/Gabbbbb21/Gab.git

## Contact
Information
Include contact
information for inquiries or support.


