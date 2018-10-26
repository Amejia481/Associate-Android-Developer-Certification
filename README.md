# Associate Android Developer Certification
All the info and material about the certification that I've collected so far.

## Google has Updated their Courses and every other material below are very necessary to cover, the only new thing is Android Architecture Components.

**Scrolldown to  the last page to see the Updated Materials**

**Pull Requests are welcome!**

#### Checkboxes
Feel free to make a fork and fill out the checkboxes as you go! 

A checkbox in the editor will look like "[ ]". You just need to put an x instead of a space to check it off, like "[x]"! 

Thanks to [Daita](https://github.com/vdaita) for this contribution.

### Video Intro
[![IMAGE ALT TEXT](http://img.youtube.com/vi/GY5Olv1_dB4/0.jpg)](https://youtu.be/GY5Olv1_dB4 "Video Title")

### General information
- [Announcement on Google I/O 2016][google_io_announcement]
- [Associate Android Developer certification Specs][certification_specs]
- [Udacity Course Developing Android Apps Covers the Certification Topics][developing_apps_udacity]
- [Associate Android Developer Fast Track][fast_track]
- [Android Developer Fundamentals](https://developers.google.com/training/courses/android-fundamentals)

### Certification topics

[Diagram version][diagram]
<img src="https://raw.githubusercontent.com/Amejia481/Associate-Android-Developer-Certification/master/img/android_certification_specs.png" align="center" >


#### Testing and Debugging
>Writing tests to verify that the application's logic and user interface are performing as expected, and executing those tests using the developer tools. Candidates should be able to analyze application crashes, and find common bugs such as layout errors and memory leaks. This includes working with the debuggers to step through application code and verify expected behavior.


- Write and execute a local JVM unit test
  - [ ] [[Fragmented Podcast] Episode 78 Ten Testing Strategies with Michael Bailey](http://fragmentedpodcast.com/episodes/78/) 
  - [ ] [[Fragmented Podcast] Episode 7 Jake Wharton on Testing, SqlBrite, NotRxAndroid, RxJava and Much More](http://fragmentedpodcast.com/episodes/7/) 
  - [ ] Getting Started with Testing 
    - [ ] [Android Developer Training][testing_and_debuggin_getting_started_testing]
    - [ ] [Udacity Course Software Testing][testing_and_debuggin_udacity_course]
    - [ ] [Treehouse Testing in Android Course][treehouse_testing_course]
  - [ ] [Bulding Effective Unit Tests][testing_and_debugging_building_effective_unit_test]
  - [ ] [Play List Android Testing Patterns][testing_debuggin_play_list_android_testing_patterns]
  - [ ] [Android Testing Codelab][testing_and_debugging_testing_codelab]
  - [ ] [Android Testing Samples][testing_and_debugging_android_test_samples]
  - [ ] [Android Testing Blueprint][testing_and_debugging_android_testing_blue_print]
  - [ ] [Intro to testing part 1, @riggaroo][testing_and_debugging_intro_testing_reggaroo]
  - [ ] [Intro to testing part 2, @riggaroo][testing_and_debugging_intro_testing_reggaroo_1]
  - [ ] [Intro to testing part 3, @riggaroo][testing_and_debugging_intro_testing_reggaroo_3]
- [ ] Write and execute a device UI test
  - [ ] [[Fragmented Podcast] Episodeo 78 Ten Testing Strategies with Michael Bailey](http://fragmentedpodcast.com/episodes/78/)
  - [ ] [Automating User Interface Tests][testing_debuggin_ui_testing]
  - [ ] [Espresso][testing_and_debuggin_espresso]
  - [ ] [UI Automator][testing_and_debuggin_ui_automator]
  - [ ] [Advanced Espresso Google I/O 2016][testing_and_debugging_google_io]
  - [ ] [Advanced Android Espresso (Big Android BBQ 2016)][testing_and_debugging_advanced_android_espresso_bbq]
  - [ ] [Espresso cheat sheet][testing_and_debugging_espresso_cheat_sheet]
  - [ ] [Espresso Serie Caster][testing_and_debugging_espresso_serie_caster]
  - [ ] [[Udacity Course] Advanced Android App Development Lesson: Espresso](https://www.udacity.com/course/advanced-android-app-development--ud855)

- [ ] Given a problem description, replicate the failure
  - [ ] [Experts App Clinic:Best Practices when building apps for billions][testing_and_debugging_experts_app_clinic]
- [ ] Use the system log to output debug information
     - [ ] [[Android Developer Site] Write and View Logs with Logcat](https://developer.android.com/studio/debug/am-logcat.html)
     - [ ] [ [Udacity Developing Android Apps] Logging](https://youtu.be/i8CELIzOXCs)
- [ ] Debug and fix an application crash (uncaught exception)
   - [ ] [[Android Developer Site] Debug your App](https://developer.android.com/studio/debug/index.html)
- [ ] Debug and fix an activity lifecycle issue
   - [ ] [[Android Developer Site] Debug your App](https://developer.android.com/studio/debug/index.html)
- [ ] Debug and fix an issue binding data to views
    - [ ] [[Android Developer Site] Debug your App](https://developer.android.com/studio/debug/index.html)

#### Application User Interface (UI) and User Experience (UX)
>Implementation of the visual and navigational components of an application's design. This includes constructing layouts–using both XML and Java code–that consist of the standard framework UI elements as well as custom views. Candidates should have a working knowledge of using view styles and theme attributes to apply a consistent look and feel across an entire application. Understanding of how to include features that expand the application's audience through accessibility and localization may also be required.

- [ ] [[Fragmented Podcast] Episode 071: UI UX development with GDE Raveesh](http://fragmentedpodcast.com/episodes/71/) 

- [ ] Mock up the main screens and navigation flow of the application
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Completing the UI - Accessibility](https://www.udacity.com/course/new-android-fundamentals--ud851)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Completing the UI - Polishing the UI](https://www.udacity.com/course/new-android-fundamentals--ud851)
   - [ ] [[Code Labs Android] Using ConstraintLayout to design your views
](https://codelabs.developers.google.com/codelabs/constraint-layout/#0)
  
- [ ] Describe interactions between UI, background task, and data persistence
- [ ] Construct a layout using XML or Java code
  - [ ] [ [Techotopia] Creating an Android User Interface in Java Code](http://www.techotopia.com/index.php/Creating_an_Android_User_Interface_in_Java_Code)
- [ ] Create a custom view class and add it to a layout
  - [ ] [[Team Treehouse Course] Custom Views in Android](https://teamtreehouse.com/library/custom-views-in-android)
- [ ] Implement a custom application theme
  - [ ] [[Android Developer Page] Styles and Themes](https://developer.android.com/guide/topics/ui/themes.html)
  - [ ] [[CodePath* Page] Developing Custom Theme](https://guides.codepath.com/android/Developing-Custom-Themes)
  - [ ] [[Android Studio Page] Design App Themes with Theme Editor](https://developer.android.com/studio/write/theme-editor.html)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Polishing the UI - Styles and Themes](https://www.udacity.com/course/new-android-fundamentals--ud851)
- [ ] Apply a custom style to a group of common widgets
  - [ ] [[Android Developer Page] Styles and Themes](https://developer.android.com/guide/topics/ui/themes.html)
  
- [ ] Define a RecyclerView item list
  - [ ] [[Android Developer Site] Recycler View](https://developer.android.com/guide/topics/ui/layout/recyclerview.html)
  - [ ] [[CodePath* ] Using Recycler View](https://guides.codepath.com/android/using-the-recyclerview)
  - [ ] [[Treehouse Course] Android Lists and Adapters](https://teamtreehouse.com/library/android-lists-and-adapters)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: RecyclerView](https://www.udacity.com/course/new-android-fundamentals--ud851)
- [ ] Bind local data to a RecyclerView list
  - [ ] [[Android Developer Site] Recycler View](https://developer.android.com/guide/topics/ui/layout/recyclerview.html)
  - [ ] [[CodePath* ] Using Recycler View](https://guides.codepath.com/android/using-the-recyclerview)
  - [ ] [[Treehouse Course] Android Lists and Adapters](https://teamtreehouse.com/library/android-lists-and-adapters)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: RecyclerView](https://www.udacity.com/course/new-android-fundamentals--ud851)
- [ ] Implement menu-based or drawer navigation
  - [ ] [[Android Developers Page] Creating a Navigation Drawer][ui_ux_android_page_creating_drawer]
  - [ ] [[Android Developers Blog] Android Design Support Library Navigation View][ui_ux_android_developer_blog_navigation_view]
  - [ ] [[Team Treehouse Blog] How to Add a Navigation Drawer in Android][ui_ux_team_treehouse_blog_navigation_drawer]
  - [ ] [[Antonio Leiva Blog] Design Support Library (I): Navigation View][ui_ux_navigation_view]
  - [ ] [[Android Development Patterns] Episode 8 Navigation Drawer, DrawerLayout, and NavigationView](https://www.youtube.com/watch?v=DkT0vS14Um0&feature=youtu.be&list=PLWz5rJ2EKKc-lJo_RGGXL2Psr8vVCTWjM)
  - [ ] [[Udacity Course] Advanced Android App Development Lesson: Fragments](https://www.udacity.com/course/advanced-android-app-development--ud855)
  - [ ] [[Android Developer Page] Fragments](https://developer.android.com/guide/components/fragments.html) 
- [ ] Localize the application's UI text into one other language
  - [ ] [[Android Developer Page] Localizing with Resources](https://developer.android.com/guide/topics/resources/localization.html)
  - [ ] [[Android Developer Page] Supporting Different Languages and Cultures](https://developer.android.com/training/basics/supporting-devices/languages.html)
   - [ ] [[Treehouse Course] Localization in Android](https://teamtreehouse.com/library/localization-in-android)
    - [ ] [[Android Developer Page] Localization checklist](https://developer.android.com/distribute/best-practices/launch/localization-checklist.html)
  - [ ] [[Android Developer Page] NumberFormat](https://developer.android.com/reference/java/text/NumberFormat.html)
  - [ ] [[Android Developer Page] DateFormat](https://developer.android.com/reference/java/text/DateFormat.html)
- [ ] Apply content descriptions to views for accessibility
   - [ ]  [[Android Developer Page] Accessibility](https://developer.android.com/guide/topics/ui/accessibility/index.html)
   - [ ] [[Udacity Course] Developing Android Apps Lesson: Completing the UI - Accessibility](https://www.udacity.com/course/new-android-fundamentals--ud851)
- [ ] Add accessibility hooks to a custom view
    - [ ] [[Android Developer Page] Building Accessible Custom Views](https://developer.android.com/guide/topics/ui/accessibility/custom-views.html)

#### Fundamental Application Components
>Understanding of Android's top-level application components ([Activity](https://www.youtube.com/playlist?list=PLWy8DQlwJkdw5GZHEj4ZhR4cayR-ou6Hh), [Service](https://www.youtube.com/playlist?list=PLWy8DQlwJkdzW-dHvL1py-vyF6vYEmDmw), [Broadcast Receiver](https://www.youtube.com/playlist?list=PLWy8DQlwJkdwtBDTpP3tsjx0wXhR2shOq), [Content Provider](https://www.youtube.com/playlist?list=PLWy8DQlwJkdy2_bBHMQgGyrN4784K3Go0)) and the lifecycle associated with each one. Candidates should be able to describe the types of application logic that would be best suited for each component, and whether that component is executing in the foreground or in the background. This includes strategies for determining how and when to execute background work.
- [ ] Describe an application's key functional and nonfunctional requirements
- [ ] Create an Activity that displays a layout resource
- [ ] [Schedule a time-sensitive task using alarms](https://github.com/firebase/firebase-jobdispatcher-android)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Background Tasks](https://www.udacity.com/course/new-android-fundamentals--ud851)
- [ ] Schedule a background task using [JobScheduler](https://www.youtube.com/playlist?list=PLWy8DQlwJkdw_gbIbmGs4wplosYZn3kAm)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Background Tasks](https://www.udacity.com/course/new-android-fundamentals--ud851)
- [ ] Execute a background task inside of a [Service](https://www.youtube.com/playlist?list=PLWy8DQlwJkdzW-dHvL1py-vyF6vYEmDmw)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Background Tasks](https://www.udacity.com/course/new-android-fundamentals--ud851)
  - [ ] [[Android Performance Patterns] Season 4 Episode 6 Service Performance Patterns](https://www.youtube.com/watch?v=NJsq0TU0qeg)
  - [ ] [[Android Developer Page] Services](https://developer.android.com/guide/components/services.html)
  - [ ] [[Android Developer Page] Creating a Background Service](https://developer.android.com/training/run-background-service/create-service.html)
- [ ] Implement non-standard task stack navigation (deep links)
   -  [ ] [[Android Developer Page] Enabling Deep Links for Apps content](https://developer.android.com/training/app-indexing/deep-linking.html)
   -  [ ] [[Team Treehouse Course] Deep Links](https://teamtreehouse.com/library/deep-links)
   -  [ ] [[Jayway Blog] The Browseable Category](https://blog.jayway.com/2009/09/24/the-browsable-category-revealed/)
- [ ] Integrate code from an external support library
  - [ ] [[Udacity Course] Advanced Android App Development Lesson: Libraries](https://www.udacity.com/course/advanced-android-app-development--ud855)

#### Persistent Data Storage
>Determining appropriate use cases for local [persisted data](https://www.youtube.com/playlist?list=PLWy8DQlwJkdzafwjoVUcx9283oIbJQvFC), and designing solutions to implement data storage using files, preferences, and databases. This includes implementing strategies for bundling static data with applications, caching data from remote sources, and managing user-generated private data. Candidates should also be able to describe platform features that allow applications to store data securely and share that data with other applications in a secure manner.

- [ ] Define a database schema; include tables, fields, and indices
  - [ ] [[Android Developers Page]  Saving Data in SQL Databases][db_android_guide_database]
  - [ ] [[Udacity Course]  Data Storage][db_udacity]
  - [ ] [[Team Treehouse] Android Data Persistence][db_treehouse_data_persistence]
- [ ] Create an application-private database file
- [ ] Construct database queries returning single results
  - [ ] [[Android Developers Page] Read Information from a Database][db_android_guide_database_read]
- [ ] Construct database queries returning multiple results
  - [ ] [[Android Developers Page]  Read Information from a Database][db_android_guide_database_read]
- [ ] Insert new items into a database
  - [ ] [[Android Developers Page]  Put Information into a Database][db_android_guide_database_write]
- [ ] Update or delete existing items in a database
  - [ ] [[Android Developers Page]  Update a Database][db_android_guide_database_update]
  - [ ] [[Android Developers Page]  Delete Information from a Database][db_android_guide_database_delete]
- [ ] Expose a database to other applications via [Content Provider](https://www.youtube.com/playlist?list=PLWy8DQlwJkdy2_bBHMQgGyrN4784K3Go0)
  - [ ] [[Udacity Course] How to Use a Content Provider][persistent_data_storage_udacity_how_to_use_content_provider]
  - [ ] [[Udacity Course]  Data Storage Lesson 3: Introduction To Content Providers][db_udacity]
- [ ] Read and parse raw resources or asset files
  - [ ] [[Team Treehouse] Android Data Persistence][db_treehouse_data_persistence]
- [ ] Create persistent preference data from user input
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Preferences](https://www.udacity.com/course/new-android-fundamentals--ud851)
- [ ] Toggle application logic based on preference values
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Preferences](https://www.udacity.com/course/new-android-fundamentals--ud851)
#### Enhanced System Integration
>Extending applications to integrate with interfaces outside the core application experience through notifications and app widgets. This includes displaying information to the user through these elements and keeping that information up to date. Candidates should also understand how to provide proper navigation from these external interfaces into the application's main task, including appropriate handling of deep links.

- [ ] Create an app widget that displays on the device home screen
  - [ ] [[Android Developers docs] about Widget][android_developers_about_widget]
  - [ ] [[TreeHouse Workshop] Widgets ][treehouse_widget_workshop]
  - [ ] [[Udacity Course] Advanced Android App Development Lesson: Widgets](https://www.udacity.com/course/advanced-android-app-development--ud855)
  - [ ] [[Android Development Patterns] Season 2 Episode 2 Your app, their home screen: Widgets](https://www.youtube.com/watch?v=crsmPedDyoU)
- [ ] Implement a task to update the app widget periodically
  - [ ] [[Android Developers Page] Widget][android_developers_about_widget]
  - [ ] [[TreeHouse Workshop] Widgets ][treehouse_widget_workshop]
  - [ ] [[Udacity Course] Advanced Android App Development Lesson: Widgets](https://www.udacity.com/course/advanced-android-app-development--ud855)
- [ ] Create and display a notification to the user
  - [ ] [[Android Developer Page] Building a Notification](https://developer.android.com/training/notify-user/build-notification.html)
  - [ ] [[Udacity Course] Developing Android Apps Lesson: Background Tasks](https://www.udacity.com/course/new-android-fundamentals--ud851)

[google_io_announcement]:<https://www.youtube.com/watch?v=Yu2oGere_Mc&index=13&list=PLWz5rJ2EKKc8jQTUYvIfqA9lMvSGQWtte>
[certification_specs]:<https://www.udacity.com/google-certifications>


<!--( BEGINNING Testing and Debugging)--> 

[testing_and_debuggin_getting_started_testing]:<https://developer.android.com/training/testing/start/index.html>
[testing_and_debugging_android_testing_blue_print]:<https://github.com/googlesamples/android-testing-templates>
[testing_and_debugging_testing_codelab]:<https://codelabs.developers.google.com/codelabs/android-testing/#1>
[testing_and_debugging_building_effective_unit_test]:<https://developer.android.com/training/testing/unit-testing/index.html>
[testing_and_debugging_android_test_samples]:<https://github.com/googlesamples/android-testing>
[testing_debuggin_ui_testing]:<https://developer.android.com/training/testing/ui-testing/index.html>
[testing_and_debuggin_espresso]:<https://google.github.io/android-testing-support-library/docs/espresso/index.html>
[testing_and_debuggin_ui_automator]:<https://google.github.io/android-testing-support-library/docs/uiautomator/index.html>
[testing_and_debugging_google_io]:<https://www.youtube.com/watch?v=isihPOY2vS4&index=29&list=PLWz5rJ2EKKc8jQTUYvIfqA9lMvSGQWtte>
[testing_debuggin_play_list_android_testing_patterns]:<https://www.youtube.com/watch?v=W8LJjfkTKik&list=PLWz5rJ2EKKc-6HWg_jyP0U1zrVLHn65b2>
[testing_and_debugging_advanced_android_espresso_bbq]:<https://www.youtube.com/watch?v=hfoAC9gdC74&list=PLWz5rJ2EKKc_HyE1QX9heAgTPdAMqc50z&index=6>
[testing_and_debugging_experts_app_clinic]:<https://www.youtube.com/watch?v=Fhj7IIsAgyE&index=61&list=PLWz5rJ2EKKc8jQTUYvIfqA9lMvSGQWtte>
[testing_and_debugging_intro_testing_reggaroo]:<https://riggaroo.co.za/introduction-automated-android-testing/>
[testing_and_debugging_intro_testing_reggaroo_1]:<https://riggaroo.co.za/automated-android-testing-part-2-setup/>
[testing_and_debugging_intro_testing_reggaroo_3]:<https://riggaroo.co.za/introduction-android-testing-part3/>
[testing_and_debugging_espresso_cheat_sheet]:<https://google.github.io/android-testing-support-library/docs/espresso/cheatsheet/>
[testing_and_debugging_espresso_serie_caster]:<https://caster.io/series/espresso>
[testing_and_debuggin_udacity_course]:<https://www.udacity.com/course/software-testing--cs258>
[treehouse_testing_course]:<https://teamtreehouse.com/library/testing-in-android>

<!--( END Testing and Debugging)-->

[persistent_data_storage_udacity_how_to_use_content_provider]:<https://www.udacity.com/course/how-to-use-a-content-provider--ud258>
[diagram]:<https://coggle.it/diagram/V4zu4UNht0Q0XiTy/0a02ec0ffa8bc95928de4478d1ae1f45a85a8e16cddc07f5180bc9f18b2c63e1>
[developing_apps_udacity]:<https://www.udacity.com/course/ud851>
[fast_track]:<https://www.udacity.com/course/associate-android-developer-fast-track--nd818>
[ui_ux_team_treehouse_blog_navigation_drawer]:<http://blog.teamtreehouse.com/add-navigation-drawer-android>

<!--(BEGINNING Application User Interface (UI) and User Experience (UX))-->

<!--(BEGINNING Persistent Data Storage)-->
  [db_android_guide_database]:<https://developer.android.com/training/basics/data-storage/databases.html>
  [db_android_guide_database_read]:<https://developer.android.com/training/basics/data-storage/databases.html#ReadDbRow>
  [db_android_guide_database_write]:<https://developer.android.com/training/basics/data-storage/databases.html#WriteDbRow>
  [db_android_guide_database_update]:<https://developer.android.com/training/basics/data-storage/databases.html#UpdateDbRow>
  [db_android_guide_database_delete]:<https://developer.android.com/training/basics/data-storage/databases.html#DeleteDbRow>
  [db_udacity]:<https://in.udacity.com/course/android-basics-data-storage--ud845/>
  [db_treehouse_data_persistence]:<https://teamtreehouse.com/library/android-data-persistence/>
<!--(END Persistent Data Storage)-->

[android_developers_about_widget]:<https://developer.android.com/guide/topics/appwidgets/index.html>
[treehouse_widget_workshop]:<https://teamtreehouse.com/library/android-widgets>
[ui_ux_android_page_creating_drawer]:<https://developer.android.com/training/implementing-navigation/nav-drawer.html>
[ui_ux_android_developer_blog_navigation_view]:<https://android-developers.googleblog.com/2015/05/android-design-support-library.html>
[ui_ux_navigation_view]:<https://antonioleiva.com/navigation-view/>

<!--(END Application User Interface (UI) and User Experience (UX))-->
# Updated Materials
<!-- Update the Contents under to the new one -->
#### App Data and Files (Android Architecture Components)
>Android architecture components are part of Android Jetpack. They are a collection of libraries that help you design robust, testable, and maintainable apps. Start with classes for managing your UI component lifecycle and handling data persistence.
 - [Build an App with Architecture Components (GDD India '17)](https://www.youtube.com/watch?v=BofWWZE1wts)

- Manage your app's lifecycle with ease. New  [lifecycle-aware components](https://developer.android.com/topic/libraries/architecture/lifecycle)  help you manage your activity and fragment lifecycles. Survive configuration changes, avoid memory leaks and easily load data into your UI.

 
- [ ] Use LiveData to build data objects that notify views when the underlying database changes
  -  [Top Architecture Components LiveData and Lifecycle](https://www.youtube.com/watch?v=juyGXCvjWyw)
  - [droidcon NYC 2017 - ViewModels, LiveData and Lifecycles, oh my!](https://www.youtube.com/watch?v=SlZVYkhoSq8) 
  -  [Team TreehouseData Persistence with Room](https://teamtreehouse.com/library/data-persistence-with-room)
  - [When and why to use Android LiveData @SearsIsrael](https://medium.com/sears-israel/when-and-why-to-use-android-livedata-93d7dd949138)
  - [Android Developers BackStage Episode 72: Architecture Components 1 - Lifecycle
](https://androidbackstage.blogspot.com/2017/06/episode-72-architecture-components-1.html)
-  ViewModel Stores UI-related data that isn't destroyed on app rotations. Note it doesn't replace savedInstanceState
   
-  Room is an a SQLite object mapping library. Use it to Avoid boilerplate code and easily convert SQLite table data to Java objects. Room provides compile time checks of SQLite statements and can return RxJava, Flowable and LiveData observables.
 [Android Developers Page](https://developer.android.com/training/data-storage/room/accessing-data)
  
- [ ] Insert with @Insert DAO (Database Access Objects)
  - [Insert into your Database Table](https://developer.android.com/training/data-storage/room/accessing-data#convenience-insert)
  - [Android Developers BackStage Episode 73: Architecture Components 2 - Persistence](https://androidbackstage.blogspot.com/2017/07/episode-73-architecture-components-2.html)
- [ ] Update or delete existing items in a database Using DAO (Database Access Objects)
  - [Update information in your Database](https://developer.android.com/training/data-storage/room/accessing-data#convenience-update)
  - [Delete information in your Database](https://developer.android.com/training/data-storage/room/accessing-data#convenience-delete)  
  - [Android Developers BackStage Episode 73: Architecture Components 2 - Persistence](https://androidbackstage.blogspot.com/2017/07/episode-73-architecture-components-2.html)

- [Android Repository Pattern using RX & Room @Corebuild](https://medium.com/corebuild-software/android-repository-pattern-using-rx-room-bac6c65d7385)

- [Room with a View - Android Codelab](https://codelabs.developers.google.com/codelabs/android-room-with-a-view/#0)
- [Build an App with Architecture Components- Android Codelab](https://codelabs.developers.google.com/codelabs/build-app-with-arch-components/index.html?index=..%2F..%2Findex#0)

- [Android Architecture Components-Paging Libary](https://developer.android.com/topic/libraries/architecture/paging/)
   - [Introduction to Paging Libary](https://www.youtube.com/watch?v=QVMqCRs0BNA)
  - [Architecture Components - Introduction (Google I/O '17)](https://www.youtube.com/watch?v=FrteWKKVyzI)
  - [Android Jetpack: manage infinite lists with RecyclerView and Paging (Google I/O '18)](https://www.youtube.com/watch?v=BE5bsyGGLf4)
  - [Android Jetpack: what's new in Architecture Components (Google I/O '18)](https://www.youtube.com/watch?v=pErTyQpA390)
  - [Data Persistence with Room-TeamTreehouse
](https://teamtreehouse.com/library/data-persistence-with-room)
  - [Udacity has Updated their Course and also added Architecutre Components Course also](https://in.udacity.com/course/new-android-fundamentals--ud851)
  
  Thanks to [Pheonix73](https://github.com/Pheonix73) to contributing this section.
 ### My Advice is to Keep Learning and Looking for Materials that will help you become an Awesome Android Developerand take the exam!!!

# License

    Copyright 2016 Arturo Mejia

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
