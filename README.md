Android-Interview-Questions
===========================
### Collaboration Rules
<p>Make sure your question is new and unique - not just rephrasing a previously existing question. If possible, include a link to the solution/topic. Questions should be fairly straightforward and completely technical (no "how many golf balls are in America" questions.) If there is a new topic that you think should be included, then include it!</p>

Topics:
* <a href="#general-developer-questions">General Developer Questions</a>
* <a href="#core-java">Core Java</a>
* <a href="#core-android">Core Android</a>
* <a href="#android-design-and-xml">Android Design and XML</a>
* <a href="#android-networking">Android Networking</a>
* <a href="#databases">Databases</a>

## General Developer Questions
* How familiar you are with the Android and Google Guidelines?
* Describe Test-Driven Development. [[info]](http://en.wikipedia.org/wiki/Test-driven_development)
* Explain unit tests versus functional tests.
* Describe Scrum and Kanban.
* What project management tools have you used?
* How do you ensure that you are working efficiently?
* Do you have basic familiarity with working on the command line i.e. Gradle, Ant, or the Java Compiler?

## Core Java
#### Object-Oriented Programming
* Explain object serialization and how to implement it in Java.
* Explain anonymous classes. [[info]](http://docs.oracle.com/javase/tutorial/java/javaOO/anonymousclasses.html)
* Describe the differences between abstract classes and interfaces. [[info]](http://www.javaworld.com/article/2077421/learn-java/abstract-classes-vs-interfaces.html)
* Explain what a Singleton class is and how to create one in Java [[info]](http://www.javaworld.com/article/2073352/core-java/simply-singleton.html)

#### Data Structures
* What are the use cases and differences of arrays and ArrayLists?
* What are the use cases and differences of a HashSet and a TreeSet?

#### Build Tools
* Have you used any Ant, Maven, Gradle features for you project?

#### Programming Paradigms
* Explain event-driven programming in Java [[info]](http://en.wikibooks.org/wiki/Java_Programming/Event_Handling)

## Core Android
* How does the Android notification system work?
* How can two distinct Android apps interact? (several answers)
* Describe Activities. [[info]](http://developer.android.com/reference/android/app/Activity.html)
* What are the four states of the Activity Lifecycle? [[active/running, paused, stopped, destroyed]](#)
* What are the seven callback methods of an Activity used to perform operations when the Activity transitions between states? [onCreate(), onStart(), onResume(), onPause(), onStop(), onRestart(), onDestroy()]]()
* What are Intents? [[info]](http://developer.android.com/guide/components/intents-filters.html)
* What is an Implicit Intent? [[info]](http://developer.android.com/guide/components/intents-filters.html)
* What is an Explicit Intent? [[info]](http://developer.android.com/guide/components/intents-filters.html)
* Describe three common use cases for using an Intent.
* What is a Service? [[info]](http://developer.android.com/guide/components/services.html)
* What is a Content Provider? [[info]](http://developer.android.com/guide/topics/providers/content-providers.html)
* What is a Fragment? [[info]](http://developer.android.com/guide/components/fragments.html)
* What is ADB?
* What is ANR?

## Android Design and XML
* Explain the differences and similarities of Relative Layout and Linear Layout.
* Explain the differences and similarities of List Views and Grid Views.
* Describe how to implement XML namespaces.
* Explain how to present different styles/drawables for a button depending
on the state of the button (pressed, selected, etc.) using XML (no Java) [[info]](http://developer.android.com/guide/topics/resources/drawable-resource.html#StateList)

## Android Networking
* Have you use an HTTP Library, which, why, did you like it?
* Describe how REST APIs work.
* What are some typical methods of HTTP request/responses? [[GET, POST, PUT, PATCH, DELETE, UPDATE]]()

## Databases
* Why does Android use SQLite?
* What libraries have you used for interacting with databases and why did you choose them?
* What are contract classes? [[info]](http://developer.android.com/training/basics/data-storage/databases.html)
* How do you use the BaseColumns interface to describe your data schema? [[info]](http://developer.android.com/training/basics/data-storage/databases.html)