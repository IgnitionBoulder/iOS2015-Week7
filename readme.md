# Spark iOS 2015 Week 7
Repository for the seventh week of Fall 2015 Spark iOS curriculum and assignments

## Homework

It's time to start your final project. You'll have 3 weeks (4, if you include Thanksgiving week) to complete an app. **We will continue to have lectures and you are still expected to attend class.** Lectures will be shortened to leave extra time for project help from the teachers.

### Timeline
* *November 12*
	* Present an app idea. This should take no longer than 2 minutes per person.
	* After the presentations, you can optionally form a group with 1 other person.
* *November 17*
	* Have your initial app repo created. Make sure to include a __.gitignore__ file to minimize cruft that is stored in the repo.
	* Be able to describe to one of the teachers the screens, layout and flow of your app. This doesn't need to be perfect, but put some thought into how your app will actually work, beyond just the idea phase.
* December 1
	* Have a working prototype of your app ready to demo to a teacher
	* Spend the next week polishing and fixing bugs
* December 8
	* Have a completed app ready
	* Final bug fixes and tweaks
* December 10
	* Last day of class
	* Present a 5-10 minute demo of your app


## Week 7: Storing Data

### Section 1: NSUserDefaults
Use NSUserDefaults for storing small, configuration types of data such as user preferences and configuration items.

#### Resources
- [How to use NSUserDefaults](https://www.hackingwithswift.com/example-code/system/how-to-save-user-settings-using-nsuserdefaults)
- [NSUserDefaults Class Reference](https://developer.apple.com/library/mac/documentation/Cocoa/Reference/Foundation/Classes/NSUserDefaults_Class/)

### Section 2: PList Serialization
Use serialization for storing a set of data of the same type where you'll need access to all of the data at the same time. For example, serializing an array or a dictionary.

#### Resources
- [Writing files to the documents directory](https://thatthinginswift.com/writing-documents-directory-swift/)

### Section 3: NSCoding
Use NSCoding to serialize custom objects or object graphs.

#### Resources
- [Archives and Serializations Programming Guide](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/Archiving/Archiving.html#//apple_ref/doc/uid/10000047i)
- [NSHipster - NSCoding](http://nshipster.com/nscoding/)
- [NSCoding example](https://developer.apple.com/library/prerelease/ios/referencelibrary/GettingStarted/DevelopiOSAppsSwift/Lesson10.html)

### Section 4: Core Data
Use Core Data when you need full database functionality, including queries and partial loading of your data set.

#### Resources
- [Core Data Programming Guide](https://developer.apple.com/library/ios/documentation/Cocoa/Conceptual/CoreData/index.html)
- [NSHipster - Core Data Libraries and Utilities](http://nshipster.com/core-data-libraries-and-utilities/)

### Section 5: Alternative Datastores
Many other third party data stores exist beyond Core Data. Each has their pros and cons.

#### Resources
- [YapDatabase](https://github.com/yapstudios/YapDatabase)
- [Realm](https://realm.io/)
- [Parse](https://parse.com/)