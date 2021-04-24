<img align="left" src="https://github.com/DataResearchLabs/my_task_time_tracker/blob/main/img/application_icon.png" width="64px">

# My Task Time Tracker (MTTT) 


**Q: Where is the Source Code?**<br>
A: The source code is part of the download.  It is built into the MyTaskTimeTracker.accdb<br>
<br>
<br>
**Q: How do I access the Source Code?**<br>
A1: Close all forms.  Press F1 key.<br>
A2: Press and hold the Shift-key down while you open (before double-clicking) the MyTaskTimeTracker.accdb. Doing this will preserve full menus, unhide all source objects and give you complete access to all source code and objects.<br>
<br>
<br>
**Q: Why don't you dump the Source Code into text files here in GitHub?**<br>
A: Sure, I could dump the form code, module code, report code, table create sql, table populate sql, query sql, etc. into nice files in clean folders...but to what point?  It's not like Access has easy GitHub plugins.  It's just easier to access the source code the way Access natively meant for it to be accessed.  It would be a lot of extra time and hassle for each minor release to maintain the text file dumps for no purpose other than for a handful of folks to browse it online.  If you really want to browse the source code, just download the ACCDB file.  Apologies if you do not have Access 365 to view it though.<br>
<br>
<br>
**Q: Why on earth would you code something in Access?**<br>
A: Because Microsfot Access is simple...<br>
1: Because it is less work and faster for me to build something as a standalone app then go thru all the effort and extra layers to build and make widely deployable a web app<br>
2: Because out of the box it comes with a rich UI that I do not need to code myself (grids, subforms, export/imports, reports, etc.)<br>
3: Because it is usually already on every desktop (most corporate offices provide Microsoft Access)<br>
4: Because it is standalone/desktop avoiding budget and resource waffling (no need to purchase a webserver, or require a DBA's time, or require IT to deploy and configure it)
5: Because most corporate office security departments block freeware .EXE file downloads nowadays, but Excel and Access are allowed and safe (so long as folks peruse the source code to ensure nothing bad in there).<br>
6: Because there are no external dependencies (just one .ACCDB file to copy-paste-and-run)
7: Because regular people (non-developers) can access and use this source code in Microsoft Access VBA<br>
8: Because it lasts...I have been using some form of this tool since FoxPro in 1993/1994<br>
9: Because the platform is stable and just keeps on working...some days modern tech drives me nuts, all the WASTE due to change-churn...sometimes it is just nice to have a little utility that keeps on working year after year without having to constantly feed it time and attention (although you should periodically back it up so you don't lose data)<br>
<br>
**Opinion**: Industry bias towards Microsoft Access should not blind folks to its strengths.  There is a right time and a right place for Access applications.  This utility is one such instance.
<br>
<br>
**Q: Why was the data and application not split into separate .accdb files?**<br>
A: Yep, used to do that.   Not needed so much anymore because on close the Access database file auto-compacts itself (avoiding the bloating and eventual corruption that used to be so prevalent).  Users will not be in monkeying with code, and the few that do should already know about the occasional need to run Access with /decompile switch to clean code.<br>
So it was a tradeoff decision.  The simplicity of a single file meant not having to reply to help requests when a split database folder moved, or an upgrade occurred, etc.  10-20 years ago I used to have a loader app file that would check for updates, and app file that ran the code, and a data file that was separate and repair/compact-able.  Did not need all that overhead for this small, simple tool.<br>
