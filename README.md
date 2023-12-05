# Hi, I'm Ilya Anshmidt 👋

<img src="https://github.com/anshmidt/anshmidt/assets/12444628/3831d5a2-188b-4536-9293-4814af96251e" width="280"/>

Dedicated Android developer with 6 years of hands-on experience (including 3.5 years of commercial experience). Proficient in Kotlin, Java, Android SDK, and industry best practices. Deep background in test automation. 

Contributor to a high-impact shopping app with 10M+ downloads, collaborating in an international cross-functional team for a leading sportswear company. Played a key role in improving unit test coverage, implementing A/B tests, enhancing analytics, and conducting demos. 
Actively participated in the development of various projects, from real-time messaging services, voice calling apps to a 3D effects video app.

I am a team player and have experience working with people from different countries, cultures and time zones. I'm comfortable working with cross-functional teams, and am able to communicate effectively with both technical and non-technical team members.
<br/><br/>

# My stack
Technologies that i'm most familiar with:
- Languages: Java (7 years), Kotlin (5 years),
- Version Control Systems: Git, SVN,
- Build and Dependency Management: Gradle,
- Dependency Injection: Dagger, Koin,
- Concurrency and Asynchronous Programming: RxJava, Kotlin Coroutines, Kotlin Flow,
- Architecture: MVVM, MVP,
- Frameworks and libraries: Jetpack Compose, Retrofit, Room, Glide, Epoxy, Moxy,
- Continuous Integration and Build Automation: Jenkins,
- Testing Frameworks and Tools: JUnit, Mockito, Mockk, Robolectric, Cucumber, Appium, Selenium, Charles, JMeter
<br/><br/>

# How to reach me
- Email: anshmidt.ilya@gmail.com
- [LinkedIn](https://www.linkedin.com/in/ilya-anshmidt-40201a138/)
<br/><br/>

# My latest personal projects 
## 1. NoteList
[NoteList](https://github.com/anshmidt/NoteList) is an Android app for writing notes and organizing them into lists.
![notelist screenshots](https://user-images.githubusercontent.com/12444628/222925488-abc44943-4e93-4c6f-9f42-9faa32e7f93f.png)

### Key features:
- Minimalist interface allows user to create notes and organize them into a list in a matter seconds
- Notes can have different priorities, so important notes don't get lost and are always on top
- Deleted notes go to the trash, giving users the option to move notes back. Old notes are automatically removed from the trash.
- Data is automatically saved as user types
- Global search allows user to find a note from any list or from the trash
- Options to export entire list to clipboard, and to import multiple notes from clipboard

### Used technologies:
- Jetpack Compose 
- MVVM 
- Kotlin Coroutines
- Kotlin Flow 
- Room 
- Jetpack DataStore 
- Koin
<br/><br/>

## 2. MultiAlarm
[MultiAlarm](https://github.com/anshmidt/multialarm) is an alarm clock app for Android. It is designed to help users who likes to set multiple alarm clocks for waking up in the morning. It provides simple and effective way to manage them all at once.

![multialarm screenshots](https://user-images.githubusercontent.com/12444628/236220779-4f383ccc-a2a8-4774-a21a-d8743cc0a098.png)
<br/><br/>
Unlike most alarm apps, MultiAlarm doesn’t force you to choose between “snooze” and “dismiss” when you've just woken up and only want to stop that annoying thing ringing. It's not possible to accidentally turn off all the alarms when trying to dismiss a ringing alarm.<br/><br/>
Alarms simply ring according to schedule until you turn them off from the main menu.

<img src="https://user-images.githubusercontent.com/12444628/236221916-f7caa908-7436-4c1a-96f9-0a59f7e224f6.gif" width="280"/>

### Used technologies:
- Kotlin
- MVVM
- LiveData
- Data Binding
- Kotlin Flow
- Preferences DataStore
- Koin
- Mockito
- Robolectric
<br/><br/>

## 3. iTunes Albums
[This Android app](https://github.com/anshmidt/iTunesAlbums) displays musical albums from iTunes.

<img src="https://user-images.githubusercontent.com/12444628/74474995-a0ae9880-4eb7-11ea-8929-1bfaf8d76199.png" alt="Screen 1" width="1000"/>


### Key features:
- When user opens the app, a list of suggested albums is displayed.
- User is able to search by album and find any album existing in iTunes.
- On the screen with detailed info about the album user can find a full-size artwork, album price, genre, and list of songs.
- Downloaded images and iTunes server responses are cached.

<img src="https://user-images.githubusercontent.com/12444628/74482886-67c9f000-4ec6-11ea-8648-51a725d7652a.gif" alt="Screen 1" width="280"/>
<br/><br/>

### Used technologies:
- Kotlin
- MVP
- Retrofit
- RxJava
- Dagger
- Glide
<br/><br/> 

## 4. PriceMonitor

[Android app](https://github.com/anshmidt/pricemonitor) for monitoring prices in online stores.

### How does it look:

<img src="https://user-images.githubusercontent.com/12444628/62247221-1193d480-b3ee-11e9-8418-d6378190ad1f.jpg" alt="Screen 1" width="280"/>

### Receiving notification about dropped price:

<img src="https://user-images.githubusercontent.com/12444628/62247025-9df1c780-b3ed-11e9-92ef-0c8640da57fd.gif" alt="Screen 1" width="280"/>

### Key features:
- Prices of the product are scrapped from websites selected by user.
- PriceMonitor sends price requests periodically.
- Data from previous requests is stored in a database.
- Price trends from different stores are displayed on a graph.
- To add a new product, user enters its name and URL. URL is validated, and if it belongs to known online store, the price is retrieved automatically.
- If background service finds out that price has dropped significantly (for example, more than 5%), it shows a notification about dropped price.

### Used technologies:
- Java
- Volley - for HTTP requests
- Room - provides an abstraction layer over SQLite
- WorkManager API - for scheduling requests
- [GraphView by jjoe64](https://github.com/jjoe64/GraphView) - for displaying price trends on a graph
- Dagger 2 - for dependency injection
- TextDrawable - for displaying store icons
- Jsoup - for HTML parsing 


