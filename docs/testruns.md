### Test runs

The «Test runs» tab accumulates all the test runs conducted on the project.

![alt text]()

The UI of a single test run consists of:

![alt text]()
* The name of the test run in black font // Jenkins job name (?) in green font
* The environment name
* The platform 
* A brief statistics of the test run (Passed // Failed/Failed with a known issue/ Blockers // Skipped)

![alt text]()
* The date the test run was started and lower - the duration of the test run

If you click on the test run, you will be redirected to the page with the additional details:

* More options menu ⋮ gives the possibility to perform the following actions:
![alt text]()

* Open the test run (you can also open the test run by clicking on the field of it (not on the name)) - the test run would be opened in a new tab
* Copy link - the direct link to the test run is copied to clipboard (every test run is given an index number)
* Mark as reviewed (permissions?), and there’s a field to add comments to

![alt text]()

Once you’ve added the comment (not necessary), press the “Mark as reviewed” button
* Send as email

![alt text]()

Once you’ve added the recipient(s), press “Send” button.
(INSERT THE SCREENSHOT HOW DOES IT LOOK)
The “R” icon will appear on the test run’s UI

![alt text]()
![alt text]()

* Export to Google
(INSERT THE SCREENSHOT HOW DOES IT LOOK)

![alt text]()

Add the recipient(s) and press “Export” button. The following (clickable?) message would appear:

![alt text]()

* Export to HTML - The HTML page with the test run automatically downloads to the computer / smartphone:

![alt text]()

![alt text]()

* Build now

![alt text]()

![alt text]()

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

![alt text]()

Options: rerunning the whole suite or failures only. 

**Delete**
You can delete the whole test run. Confirm your actions in the pop-up (permissions - admin only?)
![alt text]()

Search by test runs

The option of searching by a single or several parameters or a pre-made combination of parameters.

The following filters can be set: 
* by status (passed, failed, skipped, aborted, in progress, queued, unknown (?), none - resets the filter)

![alt text]()

* by environment (demo, stage, production, etc. none - resets the filter)

![alt text]()

* by platform (API, chrome, firefox, are there any other?)

![alt text]()

* by date (a specific date or a filter (today, yesterday, this week, last week, this month, last month, this year, last year) could be set) 

![alt text]()

«Clear» button resets all the chosen filters. 

Creating a pre-defined set of search parameters (1 set = ???):
1. Click on the “Plus” icon at the upper-left corner of the page

![alt text]()

![alt text]()

![alt text]()

2. Select the name of the search parameter set
3. Choose whether the set would be public (everyone on the project can see/apply it) or private
4. Proceed to the search criteria and choose the needed combination(s) - up to 30 sets at once.

![alt text]()

Date:

![alt text]()

![alt text]()

Env:

![alt text]()

Value:

![alt text]()

Job URL:

![alt text]()

+ value field

By platform:

![alt text]()

![alt text]()

By project:

![alt text]()

![alt text]()

By status:

![alt text]()

![alt text]()

By: test suite:

![alt text]()

+ value field

Press the “Add” button for every pre-set you create.

5. Once you’re finished with all the necessary criteria, press the “Create” button.

![alt text]()

“Cancel” button deletes all the pre-sets you’ve created during the session.
To delete one particular pre-set, click on the “cross” button on it:

![alt text]()

6. Once the process is complete, a button for this specific set would appear next to the “Create new parameter set” button.

![alt text]()


Actions performed with one test run or several test runs simultaneously:

1. Mark the amount of the test runs by ticking them in the box next to every test run:

![alt text]()

The menu icon will appear in the lower-right corner of the window:

![alt text]()

Four(4) types of actions can be performed with the several chosen test runs: send as email, abort selected test runs, delete, and rerun:

![alt text]()

![alt text]()

![alt text]()

![alt text]()

You should confirm the abort / delete/ rerun actions in the pop-up windows:
![alt text]()

![alt text]()

![alt text]()

Sending the test run via email:
Add the recipient(s) and click “Send”

![alt text]()

Enter the screenshotted email here

(DOSEN'T WORK)

Test launcher

Overview/purpose

To start the test launcher, go to the upper-right corner of the Test runs page:

![alt text]()

![alt text]()

Search bar _______ : search by the template name is available.
To add templates to the branch, click on the “Gear” icon next to the repo name:

![alt text]()

To add a new repo, click on the corresponding button in the upper-left area of the window. 
The Github pop-up will appear:

![alt text]()

Authorize Zebrunner for the repo to be added.
