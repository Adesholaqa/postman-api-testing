#### Restful Booker API Testing (Postman + Postman CLI)



This project contains my API testing work using Postman and Postman CLI, including automated test execution from the command line.







##### Project Structure



**This project includes:**



Postman Collection

(New-Rest-Broker.json)



Postman Environment File

(RestfulBooker.postman\_environment.json)



Automated CLI Execution Command



Assertions for:



Status codes



Response body



Booking details



Authentication



Create / Update / Delete booking







##### Running the API Tests with Postman CLI



1. &nbsp;Install Postman CLI



If you don’t have it installed yet:  npm install -g @postman/cli





2\.     Run the Collection



Use this command to execute the tests:

postman collection run "New-Rest-Broker.json" -e "RestfulBooker.postman\_environment.json"





3\.      Important Notes



Both files must be in the same folder where you run the command.



All variables must be correctly set inside the environment file, not collection variables.



CLI results may differ from Postman UI if:



environment variable is missing



outdated collection was exported



(I fixed these issues during this project.)







4\.       What I Learned



Difference between collection variables and environment variables



Why CLI shows Invalid URI when the base URL is empty



How to export updated Postman files correctly



How to run API tests using Postman CLI













