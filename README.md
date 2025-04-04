# Vaidya-Healthcare
# A Group Project By Student of IIIT Sri City.
GROUP 41
MEMBERS - 
ANMOL SINGH
SUDEEP GANGWAR
GULSHAN KUMAR
NITIGYA JOSHI
ARYAN VERMA

Steps to run on production environment : 
- go to the client folder
- run "npm run build"
- after build is successful
- go back to root folder
- run "npm start"
- go to "http://localhost:80"


deployed link => https://vaidya-healthcare.azurewebsites.net/

github repo link -> https://github.com/rex2828/Vaidya-Healthcare

We are using mongodb and redis as databases : 
- to host an instance of mongodb -> go to mongodb.com -> create new database of mongoose -> get connection string -> change it in .env file
- to host a redis instance -> go to redislabs.com -> create a free redis instance with azure -> get connection credentials -> go to cache.js and change the credentials
