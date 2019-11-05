### Test runs

The «Test runs» tab accumulates all the test runs conducted on the project.

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-1.png?raw=true)

The UI of a single test run consists of:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-2.png?raw=true)
* The name of the test run in black font // Jenkins job name (?) in green font
* The environment name
* The platform 
* A brief statistics of the test run (Passed // Failed/Failed with a known issue/ Blockers // Skipped)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-3.png?raw=true)

* The date the test run was started and lower - the duration of the test run

If you click on the test run, you will be redirected to the page with the additional details:

More options menu ⋮ gives the possibility to perform the following actions:
![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-4.png?raw=true)


* Open the test run (you can also open the test run by clicking on the field of it (not on the name)) - the test run would be opened in a new tab
* Copy link - the direct link to the test run is copied to clipboard (every test run is given an index number)
* Mark as reviewed (permissions?), and there’s a field to add comments to

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-5.png?raw=true)

Once you’ve added the comment (not necessary), press the “Mark as reviewed” button
* Send as email

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-6.png?raw=true)

Once you’ve added the recipient(s), press “Send” button.
(INSERT THE SCREENSHOT HOW DOES IT LOOK)
The “R” icon will appear on the test run’s UI

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-7.png?raw=true)
![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-8.png?raw=true)

* Export to Google
(INSERT THE SCREENSHOT HOW DOES IT LOOK)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-9.png?raw=true)

Add the recipient(s) and press “Export” button. The following (clickable?) message would appear:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-10.png?raw=true)

* Export to HTML - The HTML page with the test run automatically downloads to the computer / smartphone:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-11.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-12.png?raw=true)

* Build now

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-13.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-14.png?raw=true)

The following build parameters can be set:
* Branch
* Build priority
* Environment
* Thread count
* ? email list
* Retry count
* ? test run rules
* Fork
* Debug
* Auto screenshot
* Enable video recording
* Rerun failures
* When all the necessary parameters are set, click the “Build” button to start the process.

**Rerun**

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-15.png?raw=true)

Options: rerunning the whole suite or failures only. 

**Delete**
You can delete the whole test run. Confirm your actions in the pop-up (permissions - admin only?)
![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-16.png?raw=true)

Search by test runs

The option of searching by a single or several parameters or a pre-made combination of parameters.

The following filters can be set: 
* by status (passed, failed, skipped, aborted, in progress, queued, unknown (?), none - resets the filter)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-17.png?raw=true)

* by environment (demo, stage, production, etc. none - resets the filter)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-18.png?raw=true)

* by platform (API, chrome, firefox, are there any other?)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-19.png?raw=true)

* by date (a specific date or a filter (today, yesterday, this week, last week, this month, last month, this year, last year) could be set) 

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-20.png?raw=true)

«Clear» button resets all the chosen filters. 

Creating a pre-defined set of search parameters (1 set = ???):
1. Click on the “Plus” icon at the upper-left corner of the page

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-21.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-22.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-23.png?raw=true)

2. Select the name of the search parameter set
3. Choose whether the set would be public (everyone on the project can see/apply it) or private
4. Proceed to the search criteria and choose the needed combination(s) - up to 30 sets at once.

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-24.png?raw=true)

Date:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-25.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-26.png?raw=true)

Env:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-27.png?raw=true)

Value:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-28.png?raw=true)

Job URL:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-29.png?raw=true)

+ value field

By platform:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-30.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-31.png?raw=true)

By project:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-32.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-32.png?raw=true)

By status:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-34.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-35.png?raw=true)

By: test suite:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-36.png?raw=true)

+ value field

Press the “Add” button for every pre-set you create.

5. Once you’re finished with all the necessary criteria, press the “Create” button.

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-37.png?raw=true)

“Cancel” button deletes all the pre-sets you’ve created during the session.
To delete one particular pre-set, click on the “cross” button on it:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-38.png?raw=true)

6. Once the process is complete, a button for this specific set would appear next to the “Create new parameter set” button.

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-39.png?raw=true)


Actions performed with one test run or several test runs simultaneously:

1. Mark the amount of the test runs by ticking them in the box next to every test run:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-40.png?raw=true)

The menu icon will appear in the lower-right corner of the window:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-41.png?raw=true)

Four(4) types of actions can be performed with the several chosen test runs: send as email, abort selected test runs, delete, and rerun:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-42.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-43.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-44.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-45.png?raw=true)

You should confirm the abort / delete/ rerun actions in the pop-up windows:
![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-46.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-47.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-48.png?raw=true)

Sending the test run via email:
Add the recipient(s) and click “Send”

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-49.png?raw=true)

Enter the screenshotted email here

(DOSEN'T WORK)

Test launcher

Overview/purpose

To start the test launcher, go to the upper-right corner of the Test runs page:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-50.png?raw=true)

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-51.png?raw=true)

Search bar _______ : search by the template name is available.
To add templates to the branch, click on the “Gear” icon next to the repo name:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-52.png?raw=true)

To add a new repo, click on the corresponding button in the upper-left area of the window. 
The Github pop-up will appear:

![alt text](https://github.com/APGorobets/mkdocks1/blob/master/images/zbrnn-testruns-53.png?raw=true)

Authorize Zebrunner for the repo to be added.
