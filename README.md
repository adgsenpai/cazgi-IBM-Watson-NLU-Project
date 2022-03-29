# Final Project: Scenario and Review Criteria
# Estimated time needed: 3 hours
You now know how to write server side applications in Node.js using Express.js framework. Additionally, you also know how to write dynamic front end applications using React.js framework. You are now ready to take on the challenge of building your own React.js application.

In this scenario, you have been hired by a research company to finish building a new site that uses IBM Watson services to find sentiments and emotions in text. The application was built using Express.js in the backend and React.js in the frontend application. The previous developer had to take time off due to health reasons and so you are brought in to finish the half done code.

The existing code has been uploaded to a github repository. Your task is to fork the repository to your own Github account and then use the lab environment to finish the requirements. You are then asked to publish the application to IBM Cloud using the Cloud Foundry service.

This project will be graded by your peers who are also completing the course during the same session. This project is worth 20 marksof your total grade, and is distributed as follows:

## Review Criteria –20 marks total
Watson NLU service was created and screenshot confirming the same is saved as watsonnluservice.jpg - 1 pt

Watson NLU credentials were identified and screenshot confirming the same is saved as watsonnlucreds.jpg 1 pt

Code is forked into the learner’s own repo and provided the url - 1 pt

The Watson NLU service was instantiated in sentimentAnalyzeServer/sentimentAnalyzerServer.js using the .env file - 1 pt

The Watson NLU credentials are not hardcoded in the sentimentAnalyzeServer/sentimentAnalyzerServer.js files - 1 pt

The “/url/sentiment“ end point is implemented in the sentimentAnalyzeServer/sentimentAnalyzerServer.js file - 1 pt

The “/url/emotion“ end point is implemented in the sentimentAnalyzeServer/sentimentAnalyzerServer.js file - 1 pt

The “/text/sentiment“ end point is implemented in the sentimentAnalyzeServer/sentimentAnalyzerServer.js file - 1 pt

The “/text/emotion“ end point is implemented in the sentimentAnalyzeServer/sentimentAnalyzerServer.js file - 1 pt

The images submitted are not sample screenshots - 1 pt

Application can be launched with the submitted URL - 1 pt

User can submit URL by clicking the Analyze Sentiment button and get sentiment back - 1 pt

User can submit URL by clicking the Analyze Emotion button and get emotions back - 2 pt

0 pt – no table

1 pt – results shown, but do not display in a table

2 pts – return shown in a table

User can submit Texts by clicking the Analyze Sentiment button and get sentiment back - 1 pt

User can submit Texts by clicking the Analyze Emotion button and get emotions back - 1 pt

User is shown the output of the sentiment analysis in a React component table - 2 pt

0 pt – no table

1 pt – results shown, but do not display in a table

2 pts – return shown in a table

Different sentiments should have different colors - 1 pt

Showing the confidence levels of emotions - 1 pt
