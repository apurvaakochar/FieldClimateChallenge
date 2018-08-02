# FieldClimateChallenge (Android)

This challenge is an app to provide the **Auto Login** feature that can be integrated with our existing [FieldClimate](https://play.google.com/store/apps/details?id=com.metos.fieldclimate&hl=en) application. The app uses [OAuth2](https://oauth.net/2/) for authentication. We will provide you with the parameters to make the Authentication Request. We'll give you some tips, but you are welcome to use your logic and give suggestions.

Please fork this repository and commit your code to it. Document/decribe your solution in SOLUTION.md file.
Send us link with your solution repository.

Remember, our goal is not to *compare* and *grade* the projects, but to get to know you better. We care about the quality, not quantity, we don't want you to waste your precious time.

**Auth URL** : https://oauth.fieldclimate.com/authorize
**Access Token URL**: https://oauth.fieldclimate.com/token

### Interface

Two Screens: 

• **Login Screen** with username and password fields and you are welcome to layout it according to your wishes.

• **Home Screen** with the title "Weather" and rest can be left blank.


### Architecture

• We would like you to use an architecture of your own choice. Try to separate **Presentation Logic** from the **Business Logic**.

• The project should be very easy to unit test. The project should have at least one unit test

• Feel free to use any third-party libraries for **Networking** and **JSON Parsing**

### Requirements

• The app should take the user to the Login Screen if the user is not authenticated

• The app should take the user directly to the Home Screen if the user is authenticated

• The validity of *refresh token* is 14 days

• Document your solution in SOLUTION.MD file

**Good luck**!


