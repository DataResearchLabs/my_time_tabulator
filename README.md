# UNDER CONSTRUCTION FOR THE NEXT WEEK OR TWO <br>
## TODAY IS APRIL 24, 2021
----------------------------------------------------------------------------------------------------


<img align="left" src="https://github.com/DataResearchLabs/my_task_time_tracker/blob/main/img/application_icon.png" width="64px">

# My Task Time Tracker
[![License: CC0](https://img.shields.io/badge/License-CC0-red)](LICENSE "Creative Commons Zero License by DataResearchLabs (effectively = Public Domain")
![current_build Office_365](https://img.shields.io/badge/Access_Version-Office_365-yellow)
[![Latest Release](https://img.shields.io/badge/Latest_Release-4.02.44311-blue)](https://github.com/DataResearchLabs/my_task_time_tracker/tree/main/download)
[![YouTube](https://img.shields.io/badge/YouTube-DataResearchLabs-brightgreen)](http://www.DataResearchLabs.com)


* **What**: A free, lean task and time tracker with a simple user interface and several reports for analysis.<br>
* **When**: Use it daily.  Use it consistently.  It literally takes just 3 to 4 minutes per day.<br>
* **Who**: Built as a standalone tool for individual contributors working from a desktop or laptop computer.<br>
* **Why**: Rollup your time for better estimates, for better performance review discussions, to help optimize where effort gets focused, or just to set expectations for how long a complex thought-work-task takes.<br>
* **How**: Simple, low-tech, minimalist data entry that rolls up your time and tasks into meaningful, actionable reports.<br>
* **Where**: On a desktop or laptop.  **Requires Microsoft Access 365**.  Yep, it is a VBA application, [read here for why](https://github.com/DataResearchLabs/my_task_time_tracker/blob/main/src/SOURCE_CODE.md#whyMicrosoftAccess)
* **Source Code**: is open-source. Either (a) close all forms and press F11, **OR** (b) hold down the Shift-key when you open the application to access ALL source code.
* **License**: Creative Commons Zero, effectively public domain.  Free to use.  Free to copy.  Free to alter.  Free to distribute.<br>
Am happy if you find this tool useful and visit my [YouTube site](http://www.dataresearchlabs.com/) for training and additional tools.<br>



<kbd>
  <img src="img/img_01_showcase_app_features.png" width="1123">
</kbd>
<br>
<br>
<br>


***If you like this tool, be sure to click the "Star" button above in GitHub.***


***Also, be sure to visit or subscribe to our YouTube channel*** www.DataResearchLabs.com!<br>

<br>


## Table of Contents
 - <a href="#introduction">1. Introduction</a>
 - <a href="#installation">2. Installation</a>
 - <a href="#gettingStarted">3. Getting Started, Configure Metadata</a>
 - <a href="#dailyTimeEntry">4. "Daily Time Entry" Sheet</a>
 - <a href="#reports">5. "Reports" Worksheet</a>
 - <a href="#import">6. "Upgrade/Import" Worksheet</a>
 - <a href="#about">7. "About" Worksheet</a>
 - <a href="#advancedTopics">8. Advanced Tips & Tricks</a>
 - <a href="#wrapup">9. Wrap Up</a>


<a id="introduction" class="anchor" href="#introduction" aria-hidden="true"> </a>
### 1. Introduction 
#### 1.1 Ten Reasons Why You Should Track and Analyze Your Time...


1. **Monitoring Value**: If time is more valuable than money, why do so few track it relative to tracking money?

2. **Your Story**: "It is performance review time...what did you accomplish last quarter or last year?"
    * Managers are too busy to notice all the great work you do...so package it up into easily digestable projects, tasks, times, and dates.<br>
    * Sell your work story...because nobody else is going to do it for you.<br>

3. **Red Light - Green Light**: Wouldn't it be nice to tag and rollup all your tasks as:
    * Green Light: What you were hired to do<br>
    * Yellow Light: What can be delegated or packaged for a peer<br>
    * Orange Light: What may be important, but not what you were hired to do<br>
    * Red Light: What wastes time, not what you were hired to do<br>
  Then roll it all up every week to analyze and adjust.<br>
  Besides, wouldn't it be nice to identify activities that are misusing or even wasting your time?<br>
  If you can show that 60% of your week is meetings, it becomes much easier to make the case to curtail them.<br>

4. **Self-Improvement**: by comparing efficiency of similar tasks and projects over time against yourself (bad idea to compare to others, stick to improving yourself).<br>

5. **Scope Creep**: When you monitor where your time is going, you can quickly show the impact of scope creep and course correct earlier<br>

6. **Happiness**: If you are grinding away focusing 100% fo your time on critical tasks with no 5% or 10% creative slow-down time, then you are likely on a path to burn-out.  Use these metrics to make the case for saying "No" more frequently, or to ask for a little bit of R&D time.<br>

7. **Tee-Shirt Baselines**: Rollup project times to establish historical baselines used for preliminary estimates or to counter unrealistic project timelines.<br>

8. **Just Billable Hours?** If you are a consultant, you already track your time for billing hours, **'nuff said, right**?
    * Not quite, because there is value beyond billing hours...<br>
    * You can slice and dice the hours, to see how they rollup to projects, to categories, and how the time flows<br>
  (a 40 hour task does not take 1 week, the hours ebb and flow at different rates, mingling with other tasks and priorities)<br>

9. **Time Boxing**: If you work on agile projects and need to time box certain activities, how do you know when you've hit the limit?<br>

10. **Dial in Your Estimates**: to improve your pipeline...  
    * The construction industry has this down in spades
      * How much does it cost per square foot of building footprint to build a 3 story building with wood beam construction, blah, blah, blah<br>
      * Check out [RS Means](https://psu.pb.unizin.org/app/uploads/sites/138/2019/11/Fig-7-2.png) and their thousands of ways to estimate anything construction related.<br>
      * This accuracy in construction estimates exists only because they track costs AND TIME.
    * Now compare that against the laughable lack of estimating accuracy and depth in the software industry.<br>
      * In construction, labor is ~50% of the cost.<br>
      * In software, labor is like 90%+ of the cost; therefore, tracking time is even more important...yet it is rarely done.<br>  
<br>


#### 1.2 How Best to Track and Analyze Where Your Time Goes...
Use a simple software tool to track and analyze your time.  There are a lot of [excellent online tools](https://clockify.me/best-time-tracking-apps) out there, including Clockify, TogglTrack, Harvest, Hubstaff, RescueTime, TimeDoctor, Timecamp, Timely, and Everhour.   All cost money except for those having a base free option with limited functionality.  Many of these tool work on your cell phone and are accessible from anywhere on the web.  All great features.<br>

So, why would you want to download and use this Microsoft Access application tying you to a PC?  In short, because it is 100% free, simple, full-featured, and emphasizes both the tracking and the analyzing parts of the question.<br>
<br>


<a id="installation" class="anchor" href="#installation" aria-hidden="true"> </a>
### 2. Installation

#### 2.1 Download
To download the "My Task Time Tracker" tool (Microsoft Access 365 ACCDB) from this repository's "/download" folder,
1. [Right-click here then select "Open in New Tab"](https://github.com/DataResearchLabs/my_task_time_tracker/blob/main/download/MyTaskTimeTracker.accdb)
2. Then click the download button
3. Then cilck the 'Open Folder' button (or '...' button) at browser Open File popup
4. Then copy the "MyTaskTimeTracker.accdb" file


#### 2.2 Deploy
1. Identify or create a "parent" folder (referred to as "$" henceforth) somewhere on your computer that is the "root" to house all the test case data files.  For example: "c:\tools\my_task_time_tracker" could be your root folder.
2. Paste a copy of the downloaded "MyTaskTimeTracker.accdb" into the new "$" folder
3. Optionally create a shortcut on your desktop, or your Windows start menu or your system tray for quick access.  If you do, in one of the videos I will walkthru howto customize an icon for that shortcut.
<br>


<a id="gettingStarted" class="anchor" href="#gettingStarted" aria-hidden="true"> </a>
### 3. Getting Started, Configure the Metadata
#### 3.1 First Open / Security Notice
The first time you open MyTaskTimeTracker.accdb, Microsoft Access security is going to pop a warning message that "some active content disabled", meaning that VBA code will not run and thus the application will not function properly.
  * The screenshot below shows the security warning message (blue dot #1).<br>
  * Go ahead and click the "Enable Content" button (blue dot #2) to allow VBA code to execute and open the application with complete functionality.<br>
  * Once done, you will not be asked again, unless you move the MyTaskTimeTracker.accdb file into a different folder.<br>
<img src="img/img_02_first_load_security_prompt.png" width="794">
<br>


#### 3.2 "Landing Page" = Main Form
The "landing page" that first pops up happens to also be the main page where you will do all your time entries and from which you can launch various popup metadata entry forms, run analysis reports, etc.  The form layout is:
<img align="right" src="img/img_03_landing_form_empty.png" width="544">
1. **Form Header**: At blue dot #1 contains the application name, version, and DataResearchLabs logo.  It also contains your company name and your name which we will fill out soon.<br>
2. **Toolbar**: At blue dot #2 contains buttons to perform various actions such as populating metadata (properties, projects, categories, and tasks), or running reports (timecard, tasks by project or category, etc.).
3. **Navigation**: At blue dot #3 contains buttons to move the view around to different days, or to save the current days entries or changes.  There are three left buttons and three right buttons. The "|<<" and "|>>" buttons move all the way to the end (first or last) day.  The "<<" and ">>" buttons move backward or forward one week.  The "<" and ">" buttons move backwards or forwards one day.  The 3.5" floppy disk button saves the daily entries changed below.
4. **Task Filters**:  At blue dot #4 contains three buttons to limit what tasks show up in the TaskName dropdown lists below.  After using this tool for months, you will have any completed tasks (IsClosed="Yes") which you do not want to keep scrolling thru when selecting a task for a time span.
5. **Daily Time Entry**: At blue dot #5 is where you enter your daily tasks and times. 
<br>


#### 3.3 Setup Properties
Before you can enter any tasks and times, you will need to enter metadata.  Start with the Properties metadata:
<img align="right" src="img/img_04_edit_properties.png" width="463">
1. **Open**: Start by clicking the "Properties" button to popup the "Edit Properties" dialog.  This is a simple name-value pair dialog.<br>
2. **Data Entry**: Enter your employer's name at blue dot#1, and your name at blue dot#2.<br>
3. **Close**: Then click the [x] in upper right corner of form to close and return to the main form.  These two values will show up on screens and reports throughout the system.<br>
<br>


#### 3.4 Setup Projects
Next, enter some Project metadata:
<img align="right" src="img/img_05_edit_projects.png" width="508">
1. **Open**: Click the "Projects" button to popup the "Edit Projects" dialog.  This also is a simple name-value pair dialog.<br>
2. **Data Entry**: Enter Project ID's at blue dot#1, and Project Names as blue dot#2.<br>
3. **Naming**: Choose whatever you want for naming conventions (numeric, alpha numeric mix, etc.).<br>
4. **Add More**: Continue to add projects by filling out Project ID's and Names in the "\*" row.<br>
5. **Close**: Then click the [x] in upper right corner of form to close and return to the main form.<br>


**NOTES**:
* You will continually be adding projects over time.<br>
* Tasks (discussed below) all rollup into projects.<br>
* There is only one level of projects, so if you need "epics", be sure to name them with a prefix abbreviation accordingly (eg: "ALPHA: (1) blah blah", "ALPHA: (2) blah blah), or something similar).<br>
* These values show up in the Task Edit page as the drop down filter, and on many reports as a grouping, sorting, and rollup parameter.<br>
* There is a hidden Project "NA" that you cannot edit or remove.  It exists for the task "--BREAK--".<br>
<br>
 

#### 3.5 Setup Categories
Next, enter some Project metadata:
<img align="right" src="img/img_06_edit_categoriesX.png" width="581">
1. **Open**: Click the "Categories" button to popup the "Edit Categories" dialog. This also is a simple name-value pair dialog.<br>
2. **Data Entry**: Enter Category ID's at blue dot#1, and Category names as blue dot#2.<br>
3. **Naming**: Choose whatever categorizations and naming conventions you want (numeric, alpha numeric mix, etc.).<br>
4. **Add More**: Continue to add categories by filling out Cateogry ID's and Names in the "\*" row.<br>
5. **Close**: Then click the [x] in upper right corner of form to close and return to the main form.<br>


**NOTES**:<br>
* You may occasionally add or change categories over time, but they generally are set once and rarely change after that.<br>
* Use whatever categorization convention you want.  They are intended to be a way of analyzing where you can claw back some time on projects, or maybe as a monthly or quarterly self-retrospective.<br>
* This field used to be named WBS for Work-Breakdown-Structure with hieararchy, but was simplified over the years to just a single level list.<br>
* I tend to use:
  * **OH** for Overhead / or **MTG** for Meetings<br>
  * **PROJ** for Project and Task work<br>
  * **OOO** for Out-of-Office (PTO, sick leave, volunteer events, etc.)<br>
* But, I saw an [interesting article in Forbes](https://www.forbes.com/sites/markmurphy/2017/05/28/the-big-reason-why-you-need-to-start-tracking-your-time/?sh=2ba8af983e1d) that suggested tracking your time as:
  * **Green Light** - Good, What you were hired to do<br>
  * **Yellow Light** - Okay, Waht can be delegated or packaged for a peer<br>
  * **Orange Light** - Minimize, What may be important, but no what you were hired to do<br>
  * **Red Light** - Bad, What wastes time, not what you were hired to do<br>
* These values show up in the reports as grouping, sorting, and rollup parameters.<br>
* There is a hidden Category "NA" that you cannot edit or remove.  It exists for the task "--BREAK--".<br>
<br>


#### 3.6 Setup Tasks
Next, enter some Tasks:<br>
<img src="img/img_07_edit_tasks.png" width="617">
1. **Open**: Click the "Tasks" button to popup the "Edit Tasks" dialog.  This is more complex than the edit screesn above because there is a project to filter tasks, and more than just a name-value pair to enter per row.<br>
2. **Project**: Before you start entering task data, be sure you have selected the appropriate parent Project in the drop down at blue dot#1.<br>
3. **Ignore**: the Task ID at blue dot#2.  This is automatically calculated as the max value + 1.  (Used to be AutoNumber, but that caused issues with importing.)<br>
4. **TaskName**: Type in a Task Name at blue dot#3.<br>
5. **Category**: Select a category from the drop down at blue dot#4.<br>
6. **IsClosed**: At blue dot#5, select the task IsClosed status as:
    * "**N**" - When you first add a new task that is not closed
    * "**Y**" - Return here later to close out completed tasks with a "Y" 
    * "**NA**" - For tasks that will never be closed because it is an ongoing task (like a recurring meeting).  
    Typically, when you first add a task, it will start as "Y", then several days or weeks or months later you will return to this screen to flip the IsClosed value to "N".  However, you will have a few tasks that you initially set straight away to "NA" and never return to change.<br>
8. **ProjectID**: You typically just go with the default value in this field, because it is set based on the drop down in blue dot #1.
**However**, there may be times when you want to re-assign a task to a new project, or split tasks from one project out into two projects.  In those cases, just flip the ProjectID values for those tasks you wish to move.<br>
9. **Add More**: Continue to add tasks by filling out cells in the "\*" row.<br>
10. **Close**: When done adding or ediing tasks, click the "Ok" button at blue dot#7  close and return to the main form<br>


**NOTES**:
* You will continually be adding tasks over time.<br>
* You will continually be editign existing tasks at least once to close them out over time.<br>
* Tasks are the lowest level of granularity in the system, and they tie everything together relative to reporting.<br>
* Think through your naming convention on tasks.<br>
  * For example, for 90% of my tasks, they are unique so I just name them something meaningful without too much concern for convention other than consistent labeling of key phases or steps that will repeat across groups of tasks (eg: "design" or "data analysis" or "research" or "coding").
  * However, there are about 10% of tasks that are recurring, things like meetings, or 1x1's, or company retreats, or process improvement reviews.
  * For these I like to bucket them up into generic tasks that span forever, and label them something like:<br>
    * "@T1-MISC: Morning Emails, Update/Fix Computer, etc.",
    * "@T2-NPM: Non-Project Meetings", and <br>
    * "@T3-NPT: Non-Project Training", <br>
* There is a hidden Task "--BREAK--" that you cannot edit or remove.  It exists for marking the start of Lunch time, or the start of a short break, and to mark the end of your work day.  The duration column is never calculated for a "break" row, but the "break" row is used to derive the end date/time of the prior task.  Thus, entering "break" rows is important for the system to properly calculate task durations.<br>



<a id="dailyTimeEntry" class="anchor" href="#dailyTimeEntry" aria-hidden="true"> </a>
### 4. "Daily Time Entry" Sheet
#### 4.1 Select Date
From the main task and time entry screen, the first thing you need to do is select a date.  Today's date is the default, so typically you do not need to change anything.  In the screenshot to the right, the various date selectors are tagged and defined as follows:<br>
<img align="right" src="img/img_08_date_selectors.png" width="257">


* Dot #1 = Jump to first date with time entries<br>
* Dot #2 = Move one week earlier<br>
* Dot #3 = Move one day prior<br>
* Dot #4 = Currently selected day for which tasks and times shown<br>
* Dot #5 = Jump to Today's date<br>
* Dot #6 = Move one day forward<br>
* Dot #7 = Move one week forward<br>
* Dot #8 = Jump to last date with time entries<br>
<br>


#### 4.2 Enter Tasks and Times
##### 4.2.1 First Row of a Day
<img align="right" src="img/img_09_time_entry_before.png" width="521">
<img align="right" src="img/img_10_time_entry_after.png" width="521">


The entry form starts off blank each day.  Go ahead and select a TaskName from the dropdown (blue dot#1) and the current hour and minute will be automatically set.  Go ahead and set it back a couple of hours. 
* **Before=Blank**: The screenshot on top is the initial state.
* **After=Auto-Calc**: Notice in the lower screenshot that the hour and time cells (blue dots#1 and #2) were automatically set to right now.
* **Change=Possible**: You can change the hour and minute dropdown values.
* **Duration=Blank**: Notice that duration (blue dot#3) is blank; that is because it takes both a start **and** an end time to calculate a duration (two tasks).

##### 4.2.2 Second Row of a Day
<img align="right" src="img/img_11_time_entry_row2.png" width="521">


Now, enter a second task and time on the second row, using the current time and hour.
* **Dur=Auto-Calc**: Notice that the Dur (durationin hours) of the first task has now been automatically calculated.  This is because it has a boundary (end time) as established by the second task start time.
* **RankOrd=Auto-Calc**: The Rank Order column on the far left of the grid is also automatically calculated.  Both it and duration are in a lighter blue color, indicating that they are calculated and un-editable by design.
* **24 Hour**: Notice that the time drop down contains the hours 00 thru 23, not 00-12 with AM and PM.  This was in part for efficiency (one less column to enter for each row) and partly to make coding easier.  I originally had AM or PM in a dropdown, but got to the report modifications and realized it was just not worth the complexity and extra effort.  **TIP** - Just add 12 to arrive at the appropriate military time (example: 5PM + 12 = 17-hundred hours; or 10PM +12 = 22-hundred hours).<br>


##### 4.2.3 Special "--BREAK--" Task



#### 4.4 Filter to Hide or Show Tasks in Dropdown



#### 4.5 Save Daily Entry



#### 4.6 Wekly Time Card




<a id="reports" class="anchor" href="#reports" aria-hidden="true"> </a>
### 5. Reports
#### 5.1 Opening Report Wizard
To open the...

#### 5.2 Step 1 - Select Report


#### 5.3 Step 2 - Select Filter



#### 5.4 Run Report



#### 5.5 Build Filters



#### 5.6 "R01 - Rollup by Category" Report Interpetation Guide



#### 5.7 "R02 - Rollup by Project" Report Interpetation Guide



#### 5.8 "R03 - Gannt Chart" Report Interpetation Guide



#### 5.9 "R04 - Task by Project" Report Interpetation Guide




<a id="import" class="anchor" href="#import" aria-hidden="true"> </a>
### 6. Upgrade/Import
#### 6.1 Introduction


<a id="about" class="anchor" href="#about" aria-hidden="true"> </a>
### 7. "About" Worksheet
<img align="right" src="img/img_19_about_screen.png" width="489">
The "About" worksheet accomplishes a few goals. It informs the user...<br>
1. The "application" name and version.<br>
2. Where to watch training videos.<br>
3. Where to find the online docs.<br>
4. That the tool and all documentation are Creative Commons Zero license...effectively Public Domain which means I grant you full and free usage.<br><br>
I hope it helps you in your company and makes you more productive.  I am happy for you if you extend and modify or alter the tool.  Do what you need to do...that's what the About worksheet indicates.  One caveat, please do click the GitHub star button for this project, and visit my YouTube site and subscribe at www.dataresearchlabs.com. <br>


<a id="advancedTopics" class="anchor" href="#advancedTopics" aria-hidden="true"> </a>
### 8. Advanced Tips & Tricks
#### 8.1 Using "Jump Stops" 
<img align="right" src="img/img_20_jump_stops.png" width="284">
"Jump Stops" are just



<a id="wrapup" class="anchor" href="#wrapup" aria-hidden="true"> </a>
### 9. Wrap Up
#### 9.1 Thank You
Thank you very much for reading all the way down to the end of the documentation.  Time is valuable and ever more scarce in today's busy world.  Few people make it this far.  If you did, I hope that means you found value in this tool / spreadsheet / "software".  I hope it makes you and/or your team more productive.  I am happy if you adopt the spreadsheet then change and evolve it to meet your needs.  I am happy if you fork this repository and build your own.  I am happy and would roll-in to the master branch any chanes you might make from which other may benefit. Thank you for your use and support.<br>


#### 9.2 YouTube Training & Resources
If you like this tool, please visit and subscribe to my YouTube site at http://www.dataresearchlabs.com and check out video training for this "product" as well as other related tools and training.<br>


#### 9.3 MTCM History
"My Test Case Manager" has been a work in progress, arriving at version 5.x over the last two plus decades.<br>

* **Ver 1.x** - At some point in 1994 I built my first Time Tracking app in FoxPro for school....<br>
* **Ver 2.x** - In late 1999, I started my first freeware hobby site "pb-sys.com" for Pierce Business Systems (retired in 2003).  Billit vXXX was last deployed in XXXXXXXXXXX.  This version was pretty extensive.  It had many screens, many reports, XXXXXXXXXXXXXXXXXXXXXX.  You can [check it out here on the wayback machine](https://web.archive.org/web/20000611181859/http://www.pb-sys.com/).  XXXXXXXXXXXXXXXXXXXXXXXXXXX.<br>
* **Ver 3.x** - Between 200x and XXXX, for the next 15 years I used some modified and downsized version of Billit, keeping it current in the most recent version of Microsoft Access.  XXXXXXXXXXXXXXXXX  Over the next 10 years, I occasionally modified and used various incarnations of TCMLite for my day job.  In 2013, I used it fairly heavily for about a year at an insurance company to test software.<br>
* **Ver 4.x** - In early 2021, I started my third hobby site; this time not freeware focus but YouTube training focussed.  DataResearchLabs.com is slowly growing and I'd like YouTube viewership and gitHub visit/downloads to grow faster.  XXXXXXXXXXXXXXXXXXXXXXXXXXXXX<br>
<br>



