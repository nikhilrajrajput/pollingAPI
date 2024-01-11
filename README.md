# PollingAPI
This is the polling API project provided by the Coding Ninjas (Backend Skill Test)

## Features
- Create a question
- Add options to a question
- Add a vote to an option of question
- Delete a question → (optional: A question can’t be deleted if one of it’s options has votes)
- Delete an option → (optional: An option can’t be deleted if it has even one vote given to it)
- View a question with it’s options and all the votes given to it

## Required Routes
- /questions/create (To create a question) (POST Request)
- /questions/:id/options/create (To add options to a specific question) (Post Request )
- /questions/:id/delete (To delete a question) (Delete Request)
- /options/:id/delete (To delete an option) (Delete request)
- /options/:id/add_vote (To increment the count of votes) (POST request)
- /questions/:id (To view a question and it’s options) (GET Request)

# API Link
- link-> https://polling-api-ehoj.onrender.com

