## PROJECT SPECIFICATION

   7.News App, Stage 2
   
# Layout

Preference Summary:

Settings Activity allows users to see the value of all the preferences right below the preference name, and when the value is changed, the summary updates immediate.

Main Screen:

App contains a main screen which displays multiple news stories

List Item Contents:

The title of the article and the name of the section that it belongs to are required field.

If available, author name and date published should be included. Please note not all responses will contain these pieces of data, but it is required to include them if they are present.

Images are not required.

Layout Best Practices:

The code adheres to all of the following best practices:

* Text sizes are defined in sp
* Lengths are defined in dp
* Padding and margin is used appropriately, such that the views are not crammed up against each other.

# Functionality

Settings Activity:

Settings Activity is accessed from the Main Activity via a Navigation Drawer or from the toolbar menu.

In accordance with Material Design Guidelines, it should be reached via the "Settings" label. Do not use synonyms such as "Options" or "Preferences."

Errors:

The code runs without errors.

API Query:

App queries the content.guardianapis.com API to fetch news stories related to the topic chosen by the user, using either the ‘test’ api key or the student’s key.

The query is narrowed down by the preferences selected by the user in the Settings.

JSON Parsing:

The JSON response is parsed correctly, and relevant information is stored in the app.

Use of Loaders:

Networking operations are done using a Loader rather than an AsyncTask.

External Libraries and Packages:

The intent of this project is to give you practice writing raw Java code using the necessary classes provided by the Android framework; therefore, the use of external libraries for the core functionality will not be permitted to complete this project.

# Code Readability

Readability:

Code is easily readable such that a fellow programmer can understand the purpose of the app.

Naming Conventions:

All variables, methods, and resource IDs are descriptively named such that another developer reading the code can easily understand their function.

Formatting:

The code is properly formatted i.e. there are no unnecessary blank lines; there are no unused variables or methods; there is no commented out code.
The code also has proper indentation when defining variables and methods.

Strings:

All Strings are stored in the strings.xml resource file.

![screenshot_20181014-221802](https://user-images.githubusercontent.com/34723009/46941846-b407e480-d074-11e8-8d2c-9b2121e01086.png)
![screenshot_20181014-221811](https://user-images.githubusercontent.com/34723009/46941850-b8340200-d074-11e8-8f4f-d4a9073f8415.png)
![screenshot_20181014-221820](https://user-images.githubusercontent.com/34723009/46941853-b9652f00-d074-11e8-98de-09e092f2d2b6.png)
![screenshot_20181014-221831](https://user-images.githubusercontent.com/34723009/46941858-bcf8b600-d074-11e8-9472-bbf33882860f.png)
![screenshot_20181014-221918](https://user-images.githubusercontent.com/34723009/46941872-c08c3d00-d074-11e8-96e5-646f4c21df88.png)
