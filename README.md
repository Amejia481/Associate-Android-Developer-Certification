# Associate Android Developer Certification
All the info and material about the certification that I've collected so far.


### Video Intro
[![IMAGE ALT TEXT](http://img.youtube.com/vi/JoJbQHCvyw0/0.jpg)](https://youtu.be/JoJbQHCvyw0 "Video Title")

### General information
- [Announcement on Google I/O 2016][google_io_announcement]
- [Associate Android Developer certification Specs][certification_specs]
- [Udacity Course Developing Android Apps Covers the Certification Topics][developing_apps_udacity]
- [Associate Android Developer Fast Track][fast_track]

### Certification topics

[Diagram version][diagram]
<img src="https://raw.githubusercontent.com/Amejia481/Associate-Android-Developer-Certification/master/img/android_certification_specs.png" align="center" >


#### Testing and Debugging
- Write and execute a local JVM unit test
  - Getting Started with Testing
    - [Android Developer Training][testing_and_debuggin_getting_started_testing]
    - [Udacity Course Software Testing][testing_and_debuggin_udacity_course]
  - [Bulding Effective Unit Tests][testing_and_debugging_building_effective_unit_test]
  - [Play List Android Testing Patterns][testing_debuggin_play_list_android_testing_patterns]
  - [Android Testing Codelab][testing_and_debugging_testing_codelab]
  - [Android Testing Samples][testing_and_debugging_android_test_samples]
  - [Android Testing Blueprint][testing_and_debugging_android_testing_blue_print]
  - [Intro to testing part 1, @riggaroo][testing_and_debugging_intro_testing_reggaroo]
  - [Intro to testing part 2, @riggaroo][testing_and_debugging_intro_testing_reggaroo_1]
  - [Intro to testing part 3, @riggaroo][testing_and_debugging_intro_testing_reggaroo_3]
- Write and execute a device UI test
  - [Automating User Interface Tests][testing_debuggin_ui_testing]
  - [Espresso][testing_and_debuggin_espresso]
  - [UI Automator][testing_and_debuggin_ui_automator]
  - [Advanced Espresso Google I/O 2016][testing_and_debugging_google_io]
  - [Advanced Android Espresso (Big Android BBQ 2016)][testing_and_debugging_advanced_android_espresso_bbq]
  - [Espresso cheat sheet][testing_and_debugging_espresso_cheat_sheet]
  - [Espresso Serie Caster][testing_and_debugging_espresso_serie_caster]

- Given a problem description, replicate the failure
  - [Experts App Clinic:Best Practices when building apps for billions][testing_and_debugging_experts_app_clinic]
- Use the system log to output debug information
- Debug and fix an application crash (uncaught exception)
- Debug and fix an activity lifecycle issue
- Debug and fix an issue binding data to views

#### Application User Interface (UI) and User Experience (UX)
- Mock up the main screens and navigation flow of the application
- Describe interactions between UI, background task, and data persistence
- Construct a layout using XML or Java code
- Create a custom view class and add it to a layout
- Implement a custom application theme
- Apply a custom style to a group of common widgets
- Define a RecyclerView item list
- Bind local data to a RecyclerView list
- Implement menu-based or drawer navigation
- Localize the application's UI text into one other language
- Apply content descriptions to views for accessibility
- Add accessibility hooks to a custom view

#### Fundamental Application Components
- Describe an application's key functional and nonfunctional requirements
- Create an Activity that displays a layout resource
- Fetch local data from disk using a Loader on a background thread
- Propagate data changes through a Loader to the UI
- Schedule a time-sensitive task using alarms
- Schedule a background task using JobScheduler
- Execute a background task inside of a Service
- Implement non-standard task stack navigation (deep links)
- Integrate code from an external support library

#### Persistent Data Storage
- Define a database schema; include tables, fields, and indices
- Create an application-private database file
- Construct database queries returning single results
- Construct database queries returning multiple results
- Insert new items into a database
- Update or delete existing items in a database
- Expose a database to other applications via Content Provider
  - [How to Use a Content Provider][persistent_data_storage_udacity_how_to_use_content_provider]
- Read and parse raw resources or asset files
- Create persistent preference data from user input
- Toggle application logic based on preference values

#### Enhanced System Integration
- Create an app widget that displays on the device home screen
- Implement a task to update the app widget periodically
- Create and display a notification to the user


[google_io_announcement]:<https://www.youtube.com/watch?v=Yu2oGere_Mc&index=13&list=PLWz5rJ2EKKc8jQTUYvIfqA9lMvSGQWtte>
[certification_specs]:<https://www.udacity.com/google-certifications>
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
[persistent_data_storage_udacity_how_to_use_content_provider]:<https://www.udacity.com/course/how-to-use-a-content-provider--ud258>
[diagram]:<https://coggle.it/diagram/V4zu4UNht0Q0XiTy/0a02ec0ffa8bc95928de4478d1ae1f45a85a8e16cddc07f5180bc9f18b2c63e1>
[developing_apps_udacity]:<https://www.udacity.com/course/ud851>
[fast_track]:<https://www.udacity.com/course/associate-android-developer-fast-track--nd818>
