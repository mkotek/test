
# Video Storage![Build Status](http://devtools1.risevision.com:8080/job/Storage-Client-BranchPush/badge/icon)

## Introduction

The Video Storage Template was created to showcase how a file from Rise Stroage can be levered in a HTML page. A preview of the template can be seen here: http://rise-vision.github.io/content-video-storage/index.html

##Steps to run the Video Storage Template:##

1. Fork or download the entire content-video-storage repository.  
![alt tag](images/readme-step1.jpg)

2. Modify the files within the content-video-storage folder directory to fit your needs (see below on how to modify specific elements).  
![alt tag](images/readme-step2.jpg)

3. Host the entire “content-video-storage” folder directory in rise vision storage or your web hosting service.  
![alt tag](images/readme-step3.jpg)

4. Copy the link to the index.html file where you have it hosted and insert the url into a schedule. (you can also add this link to the url gadget within a presentation)  
![alt tag](images/readme-step4.jpg)


##Directions to Modify the Video Storage Template:##

####Changing the Text Content
Open index.html, the text content is nested within the following div ```<div class="wrapper">```. Modify the h1 tags within this div to meet your needs. The tag line is held by a span tag called ```<span class="tag-line">```.

The style of the quote content is controlled within css/style-main.css. Look for the comment called ```Quote Content```.

####Changing the Video / Text Transitions
The Video Storage Template leverages a jquery plugin called Bigvideo.js to fit-to-fill background video to websites.
The main controls and variables can be changed within 
```js/bigvideo.js``` Detailed documentaion can be found on their github repo:
https://github.com/dfcb/BigVideo.js

A detailed tutorial on how the text and video slideshow were implemented can be seen here: http://tympanus.net/codrops/2012/09/19/fullscreen-video-slideshow-with-bigvideo-js/

####Changing the Videos (rise-storage web component)
All the videos in the Video Storage Template are hosted on Rise Vision Storage https://storage.risevision.com/ using the rise-storage web component. Detailed instructions on how to configure can be found in the github readme: https://github.com/Rise-Vision/web-component-rise-storage

## Built With
actual tools used
- HTML
- CSS
- Javascript
- Jquery
- BigVideo.js
- rise-storage Web Component

Video Storage Template works in conjunction with [Rise Vision](http://www.risevision.com), the [digital signage management application](http://rva.risevision.com/) that runs on [Google Cloud](https://cloud.google.com).

At this time Chrome is the only browser that this project and Rise Vision supports.

## Submitting Issues
If you encounter problems or find defects we really want to hear about them. If you could take the time to add them as issues to this Repository it would be most appreciated. Please Identify the specific template that has the issue and follow the following format where applicable:

**Reproduction Steps**

1. did this
2. then that
3. followed by this (screenshots / video captures always help)

**Expected Results**

What you expected to happen.

**Actual Results**

What actually happened. (screenshots / video captures always help)

## Contributing
All contributions are greatly appreciated and welcome! If you would first like to sound out your contribution ideas please post your thoughts to our [community](http://community.risevision.com), otherwise submit a pull request and we will do our best to incorporate it.

### Suggested Contributions
- Alternative ways to do video transitions
- Auto loop video rotation on timed interval
- i18n Language Support

## Resources
If you have any questions or problems please don't hesitate to join our lively and responsive community at http://community.risevision.com.

If you are looking for user documentation on Rise Vision please see http://www.risevision.com/help/users/

If you would like more information on developing applications for Rise Vision please visit http://www.risevision.com/help/developers/.

 If you have any questions or problems please don't hesitate to join our lively and responsive community at http://community.risevision.com.
 
**Additional Content Templates can be found here: https://github.com/Rise-Vision/content-templates**

**Facilitator**

[Mathew Meiers](https://github.com/mmeiers "Mathew Meiers")
