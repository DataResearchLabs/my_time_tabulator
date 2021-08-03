<img align="left" src="https://github.com/DataResearchLabs/my_task_time_tracker/blob/main/img/application_icon.png" width="64px">

# My Time Tabulator (MTT) 


<ins>**V4.02.44410  -  2021.08.02**</ins><br>
1. CHANGE - Vertical scrollbar was not properly appearing when task edit screen grew beyond one window.<br>
<br>


<ins>**V4.02.44314  -  2021.04.28**</ins><br>
1. CHANGE - Changed application name to make it more unique so that others can search and find it, and I can track it easier.  Old name = "My Time Tracker", then for about 2 weeks "My Task Time Tracker", and now landed on "My Time Tabulator" on eve of release.<br>
<br>


<ins>**V4.02.44313  -  2021.04.27**</ins><br>
1. CHANGE - Add Report "R06 - Tasks by Category"<br>
2. DEFECT - Fixed long standing bug where task dropdown not updated after user  changes task settings in Edit Tasks screen (unless user clicks filter buttons to reload dropdown data...now is auto-updated.  Also, same fix for Import data feature.  Now dropdowns immediately updated with new data after import.<br>
3. DEFECT - Uggg.  Put the dropdown requery code in the wrong spot...put it inside the loop so run for each table uploaded.  Moved it to proper location at the bottom of wrapper function call AFTER all tables loaded.<br>
<br>


<ins>**V4.02.44311  -  2021.04.25**</ins><br>
1. DEFECT - At "Edit Tasks" dialog, re-enable project selector so can move tasks to other projects if necessary<br>
2. CHANGE - Gannt chart report character flipped back to fixed width font and solid block character and blue color<br>
3. DEFECT - Gannt chart report bar width calc not properly reflect new bar width after widened page<br>
4. DEFECT - Error if open Gannt chart report with no data that goes to log...and is meaningless<br>
5. DEFECT - Replace some of the old buttons with gray backgrounds<br>
<br>


<ins>**V4.02.44310  -  2021.04.24**</ins><br>
1. DEFECT - No longer import PSYS_PropertiesSystem values from old version, just use new release values<br>
2. DEFECT - Set AutoResize = On at forms S08 and S04 because occasionally got in a state of funk where a black empty hole existed on right side of form where vertical scrollbar should go.<br>
3. CHANGE - Turn warnings off when importing old tables in, so not need to click Ok / ignore 20 times.<br>
4. CHANGE - When main form loads, disable the Import button unless all appropriate tables are blank. Isolate check code into new shared function.<br>
5. DEFECT - Report "R05 - Time Card" sorted by Task Name so easier to read, flows smoother left-to-right, top-to-botttom<br>
<br>


<ins>**V4.02.44309  -  2021.04.23**</ins><br>
1. CHANGE - Rename form caption on main time entry to "My Task Time Tracker"<br>
2. DEFECT - If MoveFirst or MoveLast day and DB is empty, was getting invalud use of null but expected msgbox error intercept.<br>
3. DEFECT - Fixed four forms, hitting enter key was moving down to next line on single row entry fields. Bad UX.  Flipped behavior to default so Enter key does not add CRLF.<br>
4. DEFECT - Category and Project drop downs had faulty wiring to db names.  Was not properly working on Task Edit screen.<br>
5. DEFECT - Project dropdown on Task Edit screen at every row is bad design, conflicting with the overarching project dropdown at top of screen.  Grayed out and pushed to right the Project dropdown at each data entry row.<br>
6. DEFECT - When Task Edit screen loads, is not properly defaulting project dropdown to first or last value in list<br>
7. DEFECT - Default task "--BREAK--" was set to IsClosed = "N".  Needed to change to "NA"<br>
8. DEFECT - Time card is empty despite data for the week if you run it from a day containing no data.  Fix = msgbox warning with instructions.<br>
9. DEFECT - Filter detail screen table name mappings were broken.  Corrected metadata in table REF_FFL_xxxx<br>
10. DEFECT - If you click binocular to enable drop down, but then click off drop down, you can never get back to the text box to enter a new name.<br>
FIX: Drop instruction text.  Simplify buttons by changing binocular into "Find Filter" and moving it to bottom toolbar next to Test SQL, move drop down there too.  Click Find, dropdown appears, select from dropdown and form moves to that filter and dropdown disappears.<br>
11. DEFECT - Run Report with filter having single quotes errored.  Intercept the single quotes and replace with two single quotes to escape them when writing out to properties table<br>
12. CHANGE - Flipped alternating backcolor to slightly off-white.  Light blue was too much.<br>
13. DEFECT - "RFPR_Ref_Project" had to be renamed to "REJ_PRJ_Projects" everywhere<br>
14. DEFECT - LIB_Files was missing Option Explicit<br>
15. DEFECT - App icon and DRL logo were all large when pasted in; this made overall file size 2x larger than should be<br>
16. DEFECT - At Import Old Data, do not copy NA category, project, and task...those are part of the default template values<br>
17. DEFECT - Good grief.  Typo cause System Properties not to populate on Import upgrade.  Fixed it.<br>
<br>
<br>


<ins>**V4.02.44306  -  2021.04.20**</ins><br>
1. CHANGE - Rename to "My Task Time Tracker" because that is unique when Googled.  Change filename.  Change 2 Forms, and 0 Reports.<br>
2. DEFECT - Odd, 5 forms are far to the right and squished.  Open and fix each one.  Then change something to force form to save the change.<br>
3. CHANGE - Made a version/build calculator in XL (simple, today's date converted to integer) after "V4.02." so can copy paste.  Changed version format in application to match.<br>
4. DEFECT - Task Status = "O" still used in Edit Task places, but "NA" in all others...fix Edit Task drop down.<br>
5. CHANGE - Make project dropdown on Edit Tasks form wider.<br>
6. DEFECT - If no entries for current day when click timesheet, then the time card flips back to 1/1/1900.<br>
7. CHANGE - UX: Make calculated cells "Rank Order" and "Dur (hr)" be Light Blue font color.<br>
8. DEFECT - Prevent main screen from going smaller than certain size.<br>
9. CHANGE - Make all screens remember previous size, load to that size next open, and resize no further than the minimum.  Also make the About and Report Wizard windows not resizable.<br>
10. CHANGE - Make Application Icon.  Start with Microsoft Access icon (it's the container app).  Then add a stop watch icon from Excel built-in graphics.  Colorize it, resize, etc.<br>
11. CHANGE - Help About to match MTCM.  Add new license text.  Add new app icon.  Shift DRL log to right.  Add new footer section with cartoon me asking for support.<br>
12. DEFECT - Help About when no error log, should not ask whether you want to create a new file.  Check first and prompt happy news, "No error log yet exists."<br>
13. CHANGE - Alter all Edit forms to use friendly names at column headers (spaces not underscores, no abbreviations where possible, etc.)<br>
14. CHANGE - Fix one row in changed table "PRSY_Properties_System": PageFooter text app name now = "My Task Time Tracker"<br>
15. DEFECT - Uggg. Old 1999 code was still looking to replace ".mdb" with ".err" ... should have been trying to replace newer ".accdb".   And, while I was in there, ".err" was also long ago replaced with ".log".   So that About form Error Log button has been double broken for more than a decade.  But, I guess with me the only user, and I never touched that feature, then who cared?  Answer = nobody until now, lol.<br> 
16. DEFECT - Error log caught a copy-paste table name error that was silently occuring and messing up work tables.<br>
17. IGNORE - Did Not Work...Try importing all objects into an empty database file to see if it fixes size issue.<br>
18. CHANGE - Rename all objects.  Big cleanup job.<br>
  + Tables: Facets format with 4-digit unique table abbreviation followed by full table name.<br>
    * MTT_DailyEntry > DEDE_DailyEntry<br>
    * MTT_DailyRollup > DRDR_DailyRollup<br>
    * MTT_Task > TATA_Task<br>
    * REF_Filter > RFFI_Ref_Filter<br>
    * REF_Filter_Detail > RFFD_Ref_Filter_Detail<br>
    * REF_Filter_Field_List > RFFL_Ref_Filter_Field_List<br>
    * REF_Project > RFPR_Ref_Project<br>
    * REF_Properties_System > PRSY_Properties_System<br>
    * REF_Properties_User > PRUS_Properties_User<br>
    * REF_Reports > RFRE_Ref_Reports<br>
    * REF_WBS > RFCA_Ref_Categories<br>
    * WRK_DailyEntry > DEWT_DailyEntryWorkTbl<br>
    * WRK_DailyEntry_RequeryHolding > DERH_DailyEntryRequeryHoldingWorkTbl<br>
  + Queries: Simplify, match to erport names, or to changed table names<br>
    * rpt_R01 > R01<br>
    * rpt_R02 > R02<br>
    * rpt_R03 > R03<br>
    * rpt_R04 > R04<br>
    * rpt_WeeklyTimeCard_1 > R05_1<br>
    * rpt_WeeklyTimeCard_2 > R05_2<br>
    * rpt_WeeklyTimeCard_3 > R05_3<br>
    * rpt_WeeklyTimeCard_4 > R05_4<br>
    * WRK_DailyEntry_1 > DEWT_1<br>
    * WRK_DailyEntry_2 > DEWT_2<br>
    * WRK_DailyEntry_3 > DEWT_3<br>
  + Reports:<br>
    * Time Card > R05 - Time Card<br>
  + Forms: Change over to Screen Numbers like S01, etc.<br>
    * APP_About > S01_About<br>
    * WIZ_Report > S02_Report<br>
    * LIB_Filter > S03_Filter<br>
    * LIB_FilterSub > S03_FilterSub<br>
    * APP_EditProperties > S04_EditProperties<br>
    * APP_EditProjects > S05_EditProjects<br>
    * APP_EditCategories > S06_EditCategories<br>
    * APP_EditTasks > S07_EditTasks<br>
    * APP_EditTasksSub > S07_EditTasksSub<br>
    * APP_TimeSheet > S08_TimeSheet<br>
19. CHANGE - Change out all AutoNumbers to default = dmax() + 1<br> 
    - SKIP - (Table=DRDR_DailyRollup, field=DayTask_ID) because it harms nothing, used for reports to self-join, no easy form to auto-assign, and no issues with it changing during import<br>
    - SKIP - (Table=RFFD_Ref_Filter_Detail, Field=Filter_Detail_ID) because it harms nothing, used for reports to self-join, no easy form to auto-assign, and no issues with it changing during import<br>
    - Table=TATA_Task,  Field=Task_ID  ->  Had to add Form_BeforeUpdate() logic<br>
    - Table=RFFL_Ref_Filter_Field_List,  Field=Field_ID  ->  Simply changed field, this is static ref that I manually update, never user<br>
    - Table=RFFI_Ref_Filter,  Field=Saved_Filter_ID<br> 
20. CHANGE - Moved the task dropdown selector filter (show closed tasks: yes, no, na's) up to the toolbar.  Is cleaner.<br>
21. CHANGE - Reset Tab Index Order on all controls of Main Time Entry screen<br>
22. CHANGE - Make an import data feature.<br>  
    - New button with icon.<br>
    - List the static ref tables in commented out code.<br>
    - Select target file via dialog, default to current ACCDB file location<br>
    - Validation Code Checks (30+) before attempting import<br>
    - Import all non-ref table data, one table at a time<br>
    - Add a Warning Message and Are You Sure<br>
23. Refactor S08_TimeSheet.<br>
    - Make the show closed task buttons taller to match height other buttons same row<br>
    - Make the buttons right aligned during screen resizes<br>
    - Form header with new icon layout (or remove it)<br>
24. Fix RFCA_Ref_Categories field names WBS_ID > Category_ID and WBS_Name > Category<br>
25. Rename all tables one more time, goood lord, but make it final and great this time<br>
    * DERH_DailyEntryRequeryHoldingWorkTbl >> DEFS_DailyEntryForScreen<br>
    * DEWT_DailyEntryWorkTbl >> DETT_DailyEntryTempTbl<br>
    * DRDR_DailyRollup >> DERO_DailyEntryRollup<br>
    * PRSY_Properties_System >> PSYS_PropertiesSystem<br>
    * PRUS_Properties_User >> PUSR_PropertiesUser<br>
    * RFCA_Ref_Categories >> REF_CAT_Categories<br>
    * RFFD_Ref_Filter_Detail >> REF_FID_FilterDetail<br>
    * RFFI_Ref_Filter >> REF_FIL_Filter<br>
    * RFFL_Ref_Filter_Field_Lists >> REF_FFL_FilterFieldLists<br>
    * RFPR_Ref_Projects >> REF_PRJ_Projects<br>
    * RFRE_Ref_Reports >> REF_RPT_Reports<br>
26. Bump Version Number.  Push Release out to GitHub.<br>

