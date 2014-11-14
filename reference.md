---
layout: page
permalink: /reference/
title: Class Reference
tagline: Mobile Development with iOS
tags: [reference]
---
# Week 2

####Class 4
* [Slides 11/13/14 - Properties, Subclassing, Frameworks, Categories & NSDictionaries](https://docs.google.com/presentation/d/1NCnitdREfOq748VDD4rnCtVX8p2KuDpg7gB1K5yINfw/edit?usp=sharing)

### Current Assignment
Please go over the slides originally scheduled for today (we will go over these as a class still) [Slides 11/13/14 - Properties, Subclassing, Frameworks, Categories & NSDictionaries](https://docs.google.com/presentation/d/1NCnitdREfOq748VDD4rnCtVX8p2KuDpg7gB1K5yINfw/edit?usp=sharing) and watch the following videos.

* [Categories - Treehouse](http://teamtreehouse.com/library/ios-foundations/blocks-and-categories/categories)

* [Nearby Networking with Multipeer connectivity](https://developer.apple.com/videos/enterprise/#15)

####Class 3
* [Slides 11/10/14 - Variables, Methods and more](https://docs.google.com/presentation/d/1OECBtnPFaUFNtPXx55SBDhPsVGlKWU3VxNF5L52C8N4/edit#slide=id.g46d2eb907_15)

###Class 3 Assignment - Using Storyboard, UILabels and NSArrays.

* Create a new project from the “Single View Application” template.

* On the StoryBoard, drag in 3 UILabels, connect each one to your ViewController.h giving each one its own reference name.

* Change the TEXT COLOR and FONT of your UILabels in the StoryBoards Attribute inspector (on the right side of screen) to make them easier to read. Make sure you select which UILabel you want to edit on the StoryBoard so you are changing the correct UILabels attributes.

* In your viewcontroller.h files viewDidLoad method,

    * Add an “int” and initialize with 0
    * Create an NSArray and initialize with the following strings
		  * One
		  * Two
		  * Three

* Assign the text property of each UILabel you connected to one of the strings held in the NSArray using the arrays built in method, [yourArrayName objectAtIndex:myInt]; and your “int” to determine the proper index.

* After assigning the first UILabels text property from the NSArray, you will need to increment your int by 1 for the next label.

* Remember the first index of an Array starts at 0.

* Build to the simulator to verify each UILabel displayed contains one of the words in you array.

* In your projects “Build Settings”, verify that you have set your developer code signing identity and developer provisioning profile.

* Build and test on a real device.


# Week 1

