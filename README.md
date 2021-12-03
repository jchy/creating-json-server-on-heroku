# creating-json-server-on-heroku
Steps to create and deploy a json server on heroku from scratch 
### STEP 1: Create a folder on your system
### STEP 2: Clone the following repo on inside that folder : https://github.com/nbkhope/fake-restful-api.git
### STEP 3: Now navigate inside the fake-resful-api folder in your system using terminal
### STEP 4: Now run the following commands in your terminal 
            < heroku login >
            < heroku create app-name-of-your-choice >
            < git push heroku master >
### STEP 5: To add something your databse using VS-CODE navigate inside your fake-resful-api folder 
            -> Add the data in the databse manually 
            -> Now run the following commands 
            -> < git add db.json >
            -> < git commit -m "added new data to db.json file">
            -> < git push heroku master >
