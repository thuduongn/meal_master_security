# Meal Master Security

## What is your security recommendation? Why did you choose it?
The app uses a public food API that allows users to search and find recipes but does not store or save senstive data in a backend database. Minimizing permissions helps protect users and improve trust in the app.
## Some recommendations may not apply to the project (i.e.: biometric authentication, password policies, etc.)
Recommendation: The making sure that app will use only the required set of permission or functionality.
Reasons: 
-	The app uses public food Api which allows user to search to find the recipe, but it does not store or save the data with backend database.
-	Unused feature or unnecessary permission such as save, camera can lead to safety issues or misunderstanding for users. 
## Who does the recommendation benefit (end-user, developer, etc.)?
End-users: Protects their personal preferences, saved recipes, or other data from unauthorized access.
Developers: Prevents misuse of APIs and ensures data integrity during communication.
## If the recommendation was found somewhere other than the provided checklist, include a link to it. 
The recommendation was found from the Android App Security Checklist under section Platform Interaction:
“The app only requests the minimum set of permissions necessary.”
Link: https://github.com/OWASP/owasp-mastg/blob/master/Document/0x05h-Testing-Platform-Interaction.md#testing-app-permissions-mstg-platform-1
## When would the recommendation have to be implemented (based on how serious the security risk is)?
It should be implemented before deployment, as insecure communication poses a high risk to both app functionality and user trust.
## Why do you think your project needs your recommendation?
Requesting excessive permissions may lead to security concerns, such as unauthorized data access, which could harm user trust. By limiting permissions to what is strictly necessary, the app avoids privacy issues.
## How do you think your recommendation could be applied?
The app would just request users for necessary permissions, not the one that is not needed. It would be best practice to minimize and ask for required permissions only. 
## How feasible would the implementation be?
This recommendation is highly feasible. Reviewing and updating files requires minimal efforts. The team would just need to check carefully for all the permission added in the application and remove the unnecessary one.
