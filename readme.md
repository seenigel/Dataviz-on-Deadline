# Data Viz on Deadline
#### Or, "Forget that fancy shit, I'm on deadline and I NEED A MAP AND I NEED IT NOW!"
---

The purpose of this session is to get you up to speed on common (AND FREE) tools that you can use every day to add data visualizations into your reporting.

## Today we're going to learn
1. [JuxtaposeJS](https://juxtapose.knightlab.com/) (For Before/After comparison sliders)
2. [TimelineJS](https://timeline.knightlab.com/) (For interactive timelines)
3. [StorymapJS](https://storymap.knightlab.com) (For timeline-map hybrids)
4. [Quartz Atlas](https://www.theatlas.com/) (For quick charts)
5. [Qzzr](https://www.qzzr.com/) and [Pollcaster](https://www.pollcaster.com/) (For Quizzes and Polls)
6. [Carto](https://carto.com/) (For maps)

## Session Permalink
These notes and the sample data will remain on my github at [https://github.com/seenigel/Dataviz-on-Deadline](https://github.com/seenigel/Dataviz-on-Deadline) for the forseeable future.

## Before we get started
You'll need to to create logins for [Carto](https://carto.com/signup) and [Atlas](https://www.theatlas.com/register).

## JuxtaposeJS
[Juxtapose](https://juxtapose.knightlab.com/) is a very easy to use tool created by the Knightlab that lets you stack images on top of each other to create before/after sliders. 

Using it is easy: Provide hyperlinks to two images (or upload them from Dropbox!), customize the label text for each photo and hit publish. You'll be provided an embed code that you can drop into the CMS.

Go ahead and try it out with these two photos:
* [https://editorial-ny.dnainfo.com/interactives/2016/embed/08/gowanus/img/gowanus-2000.png](https://editorial-ny.dnainfo.com/interactives/2016/embed/08/gowanus/img/gowanus-2000.png)
* [https://editorial-ny.dnainfo.com/interactives/2016/embed/08/gowanus/img/gowanus-2010-14.png](https://editorial-ny.dnainfo.com/interactives/2016/embed/08/gowanus/img/gowanus-2010-14.png)

## TimelineJS

[TimelineJS](https://timeline.knightlab.com/) is another knightlab tool that lets you create interactive timelines that are powered by a Google spreadsheet that (and your editor!!) can go back and edit at any time. 

Example: 
	* [Jamaica Dairy Timeline](https://www.dnainfo.com/new-york/20160826/jamaica/timeline-look-back-at-century-old-elmhurst-dairy-before-it-closes)

Using it is very straightforward: 
* Knightlab gives you a [sample spreadsheet](https://drive.google.com/previewtemplate?id=1pHBvXN7nmGkiG8uQSUB82eNlnL8xHu6kydzH_-eguHQ&mode=public) that you then create a copy of and fill in with your data. 
* When finished, publish document by going to **File** > **Publish to Web**. 
* Copy the URL that's displayed and paste it back into the TimelineJS website. TimelineJS will then give you a preview of your timeline, which you can share with your editor. 
* When satisfied, copy the embed code and paste it into the CMS.

## StorymapJS
Another tool by the Knigtlab (*boy, they sure do make a lot of great data tools*) that can let you create maps that are tied to events. (Think of them as timelines, but with a map behind them.)

Examples:
* [How Chelsea Bomber was Found](https://www.dnainfo.com/new-york/20160919/chelsea/timeline-how-ahman-khan-rahami-was-found)
* [NYPD Shooter Timeline](https://www.dnainfo.com/new-york/20141221/bed-stuy/man-who-killed-nypd-officers-told-bystanders-watch-what-im-going-do)
* [Follow Ebola Patient's Steps](https://www.dnainfo.com/new-york/20141024/west-harlem/timeline-follow-new-york-ebola-patients-steps)

## Atlas
Atlas is a tool created by Quartz that can be used to very easily create bar and line charts using data from Excel or Google Spreadsheets.

## Qzzr and Pollcaster

These are tools that can be used to create Quizzes and single-question polls that look pretty and display live results.

Example: 
* Multi-Option Poll: [Subway Behavior Poll](https://www.dnainfo.com/new-york/20160407/inwood/vote-whats-most-obnoxious-behavior-youve-seen-on-subway)
* This or That Poll: [Daredevil and Hell's Kitchen](https://www.dnainfo.com/new-york/20160325/hells-kitchen-clinton/okay-daredevil-no-one-has-ever-called-hells-kitchen-kitchen)
* Quiz: [How Well Do You Know the Boroughs?](https://www.dnainfo.com/new-york/20160510/st-george/quiz-can-you-recognize-nyc-borough-by-its-shape)

## Carto
*Formerly known as CartoDB*

Carto is a mapping tool that lets you take information from a spreadsheet and very easily put that data on a map for either presentation or analysis.

Carto is a little tricky to wrap your head around becuase it revolves around the two models: **datasets** and **maps**.
* A dataset is the data you've uploaded (say a list of new restuarants or a building developments)
* A map is how you visualize that dataset. You can use a dataset in multple maps.

## Other Tools
* [Batch Geocode](http://findlatitudeandlongitude.com/batch-geocode/)
This is a tool that can turn addresses (which exist for humans) into map coordinates (which are what what maps read.)

Keep in mind when geo-coding, you want to give the geocoder as accurate info as possible. For instance, the address "200 Broadway" could turn up coordinates in Manhattan, Brooklyn, Queens and West New York, NJ. "200 Broadway, NY" could still turn up results in three boroughs. "200 Broadway, New York, NY" will narrow it down to a Manhattan address.



