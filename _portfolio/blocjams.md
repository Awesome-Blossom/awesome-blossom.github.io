---
layout: post
title: BlocJams
feature-img: "img/01.png"
thumbnail-path: "img/bloc_jams_bg.jpg"
short-description: BlocJams is a spotify replica for listening to whatever music is available on-site.

---
This is an example of a post which includes a feature image specified in the front matter of the post. The feature image spans the full-width of the page, and is shown with the title on permalink pages.
https://d13yacurqjgara.cloudfront.net/users/3217/screenshots/2030966/blocjams_1x.png
{:.center}
Summary

This project was to apply my fundamental programming skills to web development as Bloc guided me through the BlocJams website. With the help of my mentor, I learned to build BlocJams website by using HTML, CSS, the command line, Git, GitHub, Javascript, and jQuery.
![](/img/bloc_jams_bg.png)

Explanation
BlocJams is a digital music player like Spotify that is used to learn frontend web development. javascript music player using HTML, CSS, Javascript, DOM Scripting, jQuery as well as using external API's such as Buzz library to control the music. It started out with building the home page by just using HTML & CSS. Using HTML & CSS, page structure,  

Problem
Create a basic skeleton home page
Style the page 
Apply the principle of responsiveness of web development 
Create a collection of albums page
Create a page to view individual albums and play it's songs.
Use CSS transitions & DOM scripting to make the album view page dynamic by using JS.
Create events, listeners, & handlers using DOM scripting
Replace static HTMl w/ dynamic JS templates
Handle and execute complex eventsn as well as make them more effeciently by using event delegation/bubbling principles
Structure & style an audio player for individual songs. 
Use a JS library (jQuery) and it's API's to help simplify the code development. 
Refactor the code of Album & collection pages using jQuery. 
Use a third party JS music library to play audio files. 

Solution





{% highlight javascript %}
myApp.directive('myDirective', function() {
    return {
        templateUrl: 'templates/mydirective.html',
        replace: true,
        restrict: 'E'
    };
});
{% endhighlight %}