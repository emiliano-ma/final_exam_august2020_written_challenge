## Written submission
Please explain the steps you think are necessary to perform to get a feature done, from an idea to an implemented solution that is running in production. Be as detailed as possible. 

Makee a PR with your submission to this repository.


## Make sure we understand the user idea
By meeting the client and understanding the feature from their perspective.

## Translate the idea into a user story
By writting the user story we make sure that what was understood from the client gets transmitted to the developer that is going to code the feature. 

## As the developer coding the feature
 - Trasnlate the user story into a feature test:
 This test will be the check list of what needs to be done in order complete the feature. When writting the test the developer has the mind focused on what needs to be achived in order to have the working feature and will write a test with the minimum needed to get there. 

- Once starting to write the actual code the test will guide the developer. In this way it is assured that all the minimum necessary conditions get implented while writting only the necessary code for the implementation. If no test was written there is a risk that the developer goes out of scope or even that forgets some important part for the feature to work

Apart from the previous statement, having tests for every implemented feature in an application helps to mantain robust and working code at all times. When working in other features one can still run the automated tests for all the features and make sure the new code gets integrated with no problem into the application code base. 

## CI 
- It is key that from the beginning of the feature (actually from the setup of the application) we have integrated CI. These are services that continuosly check for the code that we are writting and how it integrates with the rest of the code base. All that before we actually integrated into the deployed application. 

## Deployment - Continuous deployment
- When we have completed the implementation and all tests are passing + CI services indicates that our code can be merged without affecting previously deployed code we are in condition to deploy our feature. Merge it into the application code base. 

