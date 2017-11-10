#\#OptOutside

OptOutside allows users to connect with Meetup groups who have similar interests of activities.

It uses [Einstein Intent](https://www.salesforce.com/products/einstein/overview/) to take user input (one word to entire phrases) and figure out their request. 

## Trying it Out...
Fork the project or download the zip file. 

### Install the Pods:
Run `pod install` and make sure to add the keys when prompted (See Below). If you don't currently have cocoapods on your machine, follow the instructions [on their website](https://cocoapods.org

### Keys:
OptOutside doesn't currently have a way to create tokens for the APIs it hits. It uses [Cocoapods-Keys](https://github.com/orta/cocoapods-keys) to store the keys. When you install the projects pods, it will ask you to enter the keys. You should copy and paste these into the console. _Do note: I have had to sometimes run `pod update` a second time adter I added the keys.
 - meetupKey: `5649659726295821a79657a217715`
 - einsteinToken - `NCC3JY33DTLAUB3IHOU2GO27WSRAFPKTWJQ5JGNMABD2QOAUQLTIXUMH5BC37ZWVH5V4GAMWNY2J4RUDJ7UNHWFDLFKDDPW3PR4S4MI`

 ### Open Xcode:
Make sure to open the project using the `OptOutside.xcworkspace` file. Using the `.xcodeproj' file will cause errors. 

In Xcode, click on the top level of the project in the Project Navigator (on the left hand side of xcode). Then under Targets click on OptOutside. In the teams section, set the team to your personal team. 

#
You should now be ready to run the app