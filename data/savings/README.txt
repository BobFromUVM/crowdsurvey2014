SurveyData.csv: contains survey data with missing values represented as empty string

*First row of file contains question IDs, "Savings" represents response variable question
*First column of file represents data for response variable question: "How much money do you have in your bank account?"


MeanSubstitution.csv: contains data with missing values replaced with mean value for question

*First row of file contains question IDs, "Savings" represents response variable question
*First column of file represents data for response variable question: "How much money do you have in your bank account?"


questions.csv: contains information about questions in the survey

*First column displays the question ID
*Second column displays the question text
*Third column displays the type of question response (numerical or choices)
*Fourth column displays the date the question was posted by a user


users.csv: contains information about survey users

*First column displays the user ID
*Second column displays the user's personal savings (always in U.S. dollars)
*Third column displays the user's chosen currency (does not indicate currency of previous column)
*Fourth column displays the date that the user was created
*Fifth column displays whether the user was displayed points and a scoreboard
*Sixth column displays whether the user subscribed to the survey


answers.csv: contains information about survey responses

*First column displays the response ID
*Second column displays the user ID of user who provided response
*Third column displays the question ID of the question answered
*Fourth column displays the date that the response was created
*Fifth column displays the actual response to the question

