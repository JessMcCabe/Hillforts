# Hillforts

Application Concept
Develop an application supporting an explorationof Hillforts
Users are archaeology students.
App should contain a list of Hillforts they have been assigned to visit.
Users visit site, take photos + notes which augment the information on the illfort provided by the app.
Students can add additional Hillforts - which may be uncharted

# Setup requirements.

Once you have imported the code to android developer studio you will need to update googlemapsapi.xml with your own API Key. 
 <string name="google_maps_key" templateMergeStrategy="preserve" translatable="false">YOUR_KEY_HERE</string>
 
# AVD

Built on Pixel 3 API 25

# Persistence
Local persistance. Hillfort and User objects are persisted to local JSON files
I have created users and hillforts to pre-load to the app, please add user.json and hillforts.json to the device file in /data/data/org.wit.hillforts/files/
If you do not pre-load the data, please begin by signing up first.
