SCOPE: THE APP CONSUMES DATA FROM A REST API http://uinames.com/api/

BUILT SOLELY WITH JAVACRIPT OOP BY USING ARROW FUNCTIONS, JSON AND ASYNC JAVASCRIPT. IT WORKS BY : SENDING PARAMETERS TO THE REST API ABSED ON THE INFORMATION PROVIDED BY THE USE IN THE HTML FORM, RESULT IS BEING PRINTED FROM THE REST API WITH FETCH API, AJAX AND ASYNC / AWAIT. Optional Parameters Number of names to return, between 1 and 500:

https://uinames.com/api/?amount=25 Limit results to the male or female gender:

https://uinames.com/api/?gender=female Region-specific results:

https://uinames.com/api/?region=germany Require a minimum number of characters in a name:

https://uinames.com/api/?minlen=25 Require a maximum number of characters in a name:

https://uinames.com/api/?maxlen=75 For JSONP, specify a callback function to wrap results in:

https://uinames.com/api/?callback=example Extra Data Additional random data is served to requests passing an ext parameter. However, response times may be slower, especially when requesting larger quantities of data. All photos are hand-picked from unsplash.com (license):

https://uinames.com/api/?ext
{ "name": "John", "surname": "Doe", "gender": "male", "region": "United States", "age": 29, "title": "mr", "phone": "(123) 456 7890", "birthday": { "dmy": "19/06/1987", // day, month, year "mdy": "06/19/1987", // month, day, year "raw": 551062610 // UNIX timestamp }, "email": "john.doe@example.com", "password": "Doe87(!", "credit_card": { "expiration": "12/20", "number": "1234-5678-1234-5678", "pin": 1234, "security": 123 }, "photo": "https://uinames.com/api/photos/male/1.jpg" } Exception handling Error messages have the following format:

{"error":"Region or language not found"}
