<img align="left" src="https://github.com/DataResearchLabs/my_task_time_tracker/blob/main/img/application_icon.png" width="64px">

# My Task Time Tracker (MTTT) 


### Q1: Where is the Source Code?
**A**: The source code is part of the download.  It is built into the MyTaskTimeTracker.accdb<br>
<br>


### Q2: How do I access the Source Code?
**A**: As follows:
* **Method 1**: Close all forms.  Press F1 key.<br>
**- OR -**
* **Method 2**: Press and hold the Shift-key down while you open (before double-clicking) the MyTaskTimeTracker.accdb. Doing this will preserve full menus, unhide all source objects and give you complete access to all source code and objects.<br>
<br>


### Q3: Why don't you dump the Source Code into text files here in GitHub?
**A: Too much effort, too little benefit.**  Sure, I could dump the form code, module code, report code, table create sql, table populate sql, query sql, etc. into nice files in clean folders...but to what point?  Access does not play nicely with soure control since it is not stored as individual text files.  It's just easier to access the source code the way Access natively meant for it to be accessed.<br>
<br>


<a id="whyMicrosoftAccess" class="anchor" href="#whyMicrosoftAccess" aria-hidden="true"> </a>
### Q4: Why on earth would you code something in Access?
**A**: Because Microsoft Access is simple...<br>
* **Rapid Development**: Because it is less work and faster for me to build something as a standalone app then go thru all the effort and extra layers to build and make widely deployable a web app<br>
* **Less Code**: Because out of the box it comes with a rich UI that I do not need to code myself (grids, subforms, export/imports, reports, etc.)<br>
* **Already On Desktops**: Because it is usually already on every corporate desktop (most large companies provide Microsoft Access as aprt of the Office suite)<br>
* **No Budget Battle**: Because it is standalone/desktop avoiding budget and resource waffling (no need to purchase a webserver, or require a DBA's time, or require IT to deploy and configure it)
* **No Security Battle**: Because most corporate office security departments block freeware .EXE file downloads nowadays, but Excel and Access are allowed and safe (so long as folks peruse the source code to ensure nothing bad in there).<br>
* **No Dependencies**: Because there are no external dependencies (just one .ACCDB file to copy-paste-and-run)
* **Democratization**: Because regular people (non-developers) can access and use this source code in Microsoft Access VBA<br>
* **Long Life**: Because it lasts...I have been using some form of this tool since FoxPro in 1993/1994<br>
* **Low Maintenance**: Because the platform is stable and just keeps on working...some days modern tech drives me nuts, all the WASTE due to change-churn...sometimes it is just nice to have a little utility that keeps on working year after year without having to constantly feed it time and attention (although you should periodically back it up so you don't lose data)<br>


**Opinion**: Industry bias towards Microsoft Access should not blind folks to its strengths.  There is a right time and a right place for Access applications.  This utility is one such instance.
<br>
<br>


### Q5: Why was the data and application not split into separate .accdb files?
**A: Not as important as it once was.**  Yep, used to do that.   Less important now though because on closing, the Access database file auto-compacts itself (avoiding the bloating and eventual corruption that used to be so prevalent).  Users will not be in monkeying with code, and the few that do should already know about the occasional need to run Access with /decompile switch to clean code.<br>
So it was a tradeoff decision.  The simplicity of a single file meant not having to reply to help requests when a split database folder moved, or an upgrade occurred, etc.  10-20 years ago I used to have a loader app file that would check for updates, and app file that ran the code, and a data file that was separate and repair/compact-able.  Did not need all that overhead for this small, simple tool.<br>
<br>

