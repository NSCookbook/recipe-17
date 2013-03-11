recipe-17
========



Please visit [NSCookbook](http://nscookbook.com) for more information.

###Getting Started

This recipe uses [CocoaPods](http://cocoapods.org) for dependency management. You must install CocoaPods before running the app.

**Install**

* CocoaPods is distributed as a ruby gem, installing it is as easy as running the following commands in the terminal:

````
$ [sudo] gem install cocoapods
$ pod setup
````

* Now you can install the dependencies, first cd to the project root where projectname.xcodeproject lives, then run

````
$ pod install
````

**Make sure to always open the Xcode workspace instead of the project file when building the project or it won't build.**

````
$ open projectname.xcworkspace
````



###License

NSCookbook's source code is available under the MIT license. See the LICENSE file for more info.