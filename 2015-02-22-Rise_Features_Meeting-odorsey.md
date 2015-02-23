We're thinking that v1 will be deployed and tested only by Tia, her people, and one other smal group before it's released to the public.

##APIs
* [ActionNetwork](https://actionnetwork.org/docs/v1/events) will be our go-to API. It will nicely handle the bulk of our feature set and the [terms](https://actionnetwork.org/terms) look good because we will own the data.
  * However, we still want to keep an archive of the data just in case something goes wrong. We're thinking [Mongo](http://www.mongodb.org/).
  * @miql made this to test out how creating an event with ActionNetwork would work: https://actionnetwork.org/events/justice-by-any-means-necessary
* Facebook + Instagram + Twitter are essential. 
* [GroupMe](https://dev.groupme.com/docs/v3) or [Twilio](https://www.twilio.com/) for SMS? There's also the possibility of using web sockets. 
  * Or should we just have a stream of notifications that users can subscribe to?
  * [MQTT](http://mqtt.org/) allows for messaging with "small power usage/minimized data packets"
  
##Tools
* We're having issues utilizing Cordova... should we use a different tool? Go Native iOs and Native Android? PhoneGap?
* Ionic Creator has also come out [here](https://creator.ionic.io/)-- it could be used for protoyping. Also has exporting features that work with plain old Ionic installations.

##Features
* "I'm Getting Arrested" may not be a feature that we should worry about now for v1. Same goes for the rating system (organizers will just add that info to the description of the event) and the "Wipe and Burn" feature.
* For the admin side:
  * Create event
  * Count participants
  * Notify users
  * ~~Create task list for protestors~~
* For the user/protestor side:
  * Search for protests (Mongo would be useful for this)
  * Subscribe to a protest
    *From @jacky: "attending an event could require almost nothing; just having a user signed up on the platform and adding them to a list"

##Resources
* We used [this](https://docs.google.com/document/d/1nWyryvSGSqW7Mr0H2yiixPwVKG77755KORni2KxexeE/edit) Google doc as a basic start for discussion on features
* @miql set up a Trello board so that we can layout the features here: https://trello.com/b/QYeWQfGT/rise-features
  
