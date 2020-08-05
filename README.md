## AboutMe

The AboutMe app is a demo app that shows information about a person. 
* Name
* Settable Nickname
* An image
* Scrollable information

This app demonstrates the following views and techniques:
* LinearLayout
* TextView
* EditText
* ImageView
* ScrollView
* Setting multiple click handlers programmatically
* Using data binding for views to improve perforkance and eliminate findViewById

### Screenshots

![Screenshot1](About%20Me/screenshots/AboutMeScreenshots.png)



## Dice Roller

Dice Roller is a simple app that rolls a six sided die.


### Screenshots

![Screenshot1](/Dice%20Roller/screenshots/screen0.png) ![Screenshot1](/Dice%20Roller/screenshots/screen1.png)


## Guess It!

Guess It is a word guessing app you can play with one or more friends. To play, hold the device in landscape, facing away from you with your thumbs on the **Skip** and **Got It** buttons. Your friends can then give you clues to help you guess the word. 

If you get the word right, press **Got It**. If you're stuck, press **Skip**. The game runs for a minute and then shows you your score.


### Screenshots

![Screenshot 0](/Guess%20a%20Word/screenshots/screen0.png) ![Screenshot 1](/Guess%20a%20Word/screenshots/screen1.png) ![Screenshot 2](/Guess%20a%20Word/screenshots/screen2.png)



## MarsRealEstate

MarsRealEstate is a simple demo app using ViewModel & LiveData with Retrofit, Glide and Moshi in Kotlin.

This app demonstrates the following views and techniques:

* [Retrofit](https://square.github.io/retrofit/) to make api calls to an HTTP web service
* [Moshi](https://github.com/square/moshi) which handles the deserialization of the returned JSON to Kotlin data objects 
* [Glide](https://bumptech.github.io/glide/) to load and cache images by URL.
  
It leverages the following components from the Jetpack library:

* [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel)
* [LiveData](https://developer.android.com/topic/libraries/architecture/livedata)
* [Data Binding](https://developer.android.com/topic/libraries/data-binding/) with binding adapters
* [Navigation](https://developer.android.com/topic/libraries/architecture/navigation/) with the SafeArgs plugin for parameter passing between fragments

### Screenshots

![Screenshot 1](/Mars%20Real%20Estate/screenshots/screen_1.png)
![Screenshot 2](/Mars%20Real%20Estate/screenshots/screen_2.png)
![Screenshot 3](/Mars%20Real%20Estate/screenshots/screen_3.png)


## RecyclerViewExample

In this app was used a RecyclerView that displays a list of cards in a vertical scrolling list using the Kotlin programming language on Android. The RecyclerView is a more efficient and more flexible version of the older ListView.

### Screenshots

![Screenshot 1](/RecyclerViewExample/screenshots/screen_0.jpg)

## SleepQualityTracker

The SleepQualityTracker app is a demo app that helps you collect information about your sleep. 
* Start time
* End time
* Quality
* Time slept

This app demonstrates the following views and techniques:
* Room database
* DAO
* Coroutines

It also uses and builds on the following techniques from previous lessons:
* Transformation map
* Data Binding in XML files
* ViewModel Factory
* Using Backing Properties to protect MutableLiveData
* Observable state LiveData variables to trigger navigation

### Screenshots

![Screenshot1](/SleepTracker/screenshots/sleep_quality_tracker_start.png)
![Screenshot2](/SleepTracker/screenshots/sleep_quality_tracker_stop.png)
![Screenshot3](/SleepTracker/screenshots/sleep_quality_tracker_quality.png)


## Trivia App

The Android Trivia application is an application that asks the user trivia questions about Android development.  It makes use of the Navigation component within Jetpack to move the user between different screens.  Each screen is implemented as a Fragment.
The app navigates using buttons, the Action Bar, and the Navigation Drawer.
Since students haven't yet learned about saving data or the Android lifecycle, it tries to eliminate bugs caused by configuration changes. 

### Screenshots

![Screenshot1](/Trivia%20App/screenshots/screen_1.png)