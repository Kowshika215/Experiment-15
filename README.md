## Experiment-15
## The study of the Selenium Web Testing Tool reveals its effectiveness in automating web applications for testing purposes across different browsers and platforms.
## What is Selenium?
JavaScript framework that runs in your web browser Works anywhere JavaScript is supported Hooks for many other languages Java, Ruby, Python Can simulate a user navigating through pages and then assert for specific marks on the pages All you need to really know is HTML to start using it right away

## Selenium IDE
Selenium Integrated Development Environment (IDE) is a Firefox plugin that lets testers to record their actions as they follow the workflow that they need to test. It provides a Graphical User Interface for recording user actions using Firefox which is used to learn and use Selenium, but it can only be used with Firefox browser as other browsers are not supported. However, the recorded scripts can be converted into various programming languages supported by Selenium and the scripts can be executed on other browsers as well.

## Selenium-IDEDownload
Step 1 − Launch Firefox and navigate to the following URL - http://seleniumhq.org/download/. Under the Selenium IDE section, click on the link that shows the current version number as shown below.

<img width="770" height="261" alt="image" src="https://github.com/user-attachments/assets/2c9e3a03-700c-48ab-bb7c-7273f5dac7f8" />

Step 2 − Firefox add-ons notifier pops up with allow and disallow options. User has to allow theinstallation.

<img width="408" height="172" alt="image" src="https://github.com/user-attachments/assets/7a60a64c-e3a4-4585-9a2c-8badefd0c9c9" />

Step 3 − The add-ons installer warns the user about untrusted add-ons. Click 'Install Now'.

<img width="568" height="388" alt="image" src="https://github.com/user-attachments/assets/e07d4095-1b16-4798-b442-352a355cf73a" />

Step 4 − The Selenium IDE can now be accessed by navigating to Tools >>Selenium IDE.

<img width="279" height="91" alt="image" src="https://github.com/user-attachments/assets/0bad659f-a5d0-4f8a-a3a2-b3ffb235bd8f" />

Step 5 − The Selenium IDE can also be accessed directly from the quick access menu bar as shown below.

<img width="508" height="233" alt="image" src="https://github.com/user-attachments/assets/b1395e51-4da7-4ba9-abd9-29ce3724bb30" />

## Selenium IDE Features
This section deals with the features available in Selenium IDE. The following image shows the features of Selenium IDE with the help of a simple tool-tip.

<img width="505" height="354" alt="image" src="https://github.com/user-attachments/assets/e7ce7840-8992-4ce3-823a-833fceb6d2fe" />

The features of the record tool bar are explained below.

<img width="574" height="740" alt="image" src="https://github.com/user-attachments/assets/44d529a7-a468-4c5d-b1af-4bbb2eea2fbf" />

## Creating Selenium IDE Tests
This section deals with how to create IDE tests using recording feature. The following steps are involved in creating Selenium tests using IDE − Recording and adding commands in a test Saving the recorded test Saving the test suite Executing the recorded test RecordingandAdding CommandsinaTest We will use www.ncalculators.com to demonstrate the features of Selenium.

Step 1 − Launch the Firefox browser and navigate to the website - https://www.ncalculators.com/

Step 2 − Open Selenium IDE from the Tools menu and press the record button that is on the top- right corner.

<img width="513" height="236" alt="image" src="https://github.com/user-attachments/assets/21f45b9a-cdeb-4b1f-a5ce-9a9926627b17" />

Step 3 − Navigate to "Math Calculator" >> "Percent Calculator >> enter "10" as number1 and 50 as number2 and click "calculate".

<img width="643" height="219" alt="image" src="https://github.com/user-attachments/assets/abea7ec9-078b-4fa5-a0cc-f0db05cf18fb" />

Step 4 − User can then insert a checkpoint by right clicking on the webelement and select "Show all available commands" >> select "assert text css=b 5"

<img width="647" height="333" alt="image" src="https://github.com/user-attachments/assets/202ba023-9d34-4294-b31d-02c3d0ca0822" />

Step 5 − The recorded script is generated and the script is displayed as shown below.

<img width="649" height="351" alt="image" src="https://github.com/user-attachments/assets/f960002f-a65a-42c2-bac5-9851fd1fbf5f" />

## Saving the Recorded Test
Step 1 − Save the Test Case by navigating to "File" >> "Save Test" and save the file in the location of your choice. The file is saved as .HTML as default. The test can also be saved with an extension htm, shtml, and xhtml.

<img width="627" height="287" alt="image" src="https://github.com/user-attachments/assets/1c85ace0-670f-4e7b-adc7-680e47b7ecfd" />

## SavingtheTest Suite
A test suite is a collection of tests that can be executed as a single entity.

Step 1 − Create a test suite by navigating to "File" >> "New Test Suite" as shown below.

<img width="615" height="294" alt="image" src="https://github.com/user-attachments/assets/dc84b546-5bb7-4bdf-aff9-200cb16a5dad" />

Step 2 − The tests can be recorded one by one by choosing the option "New Test Case" from the "File" Menu.

Step 3 − The individual tests are saved with a name along with saving a "Test Suite".

<img width="652" height="293" alt="image" src="https://github.com/user-attachments/assets/40b23e00-049d-4273-a533-a3e94c320758" />

Executingthe RecordedTest The recorded scripts can then be executed either by clicking "Play entire suite" or "Play current test" button in the toolbar.

Step 1 − The Run status can be seen in the status pane that displays the number of tests passed and failed.

Step 2 − Once a step is executed, the user can see the result in the "Log" Pane.

Step 3 − After executing each step, the background of the test step turns "Green" if passed and "Red" if failed as shown below.

<img width="913" height="426" alt="image" src="https://github.com/user-attachments/assets/26587f0e-2316-4a60-9bff-7ff3aa5b3006" />

## Selenium IDE Script Debugging
This section deals with debugging the Selenium IDE script. Debugging is the process of finding and fixing errors in the test script. It is a common step in any script development. To make the process more robust, we can make use a plugin "Power Debugger" for Selenium IDE.

Step 1 − To install Power Debugger for Selenium IDE, navigate to https://addons.mozilla.org/en- US/firefox/addon/power-debugger-selenium-ide/ and click "Add to Firefox" as shown below.

<img width="940" height="498" alt="image" src="https://github.com/user-attachments/assets/4dfc3d56-4370-46d1-8408-4e92e69bc46c" />

Step 2 − Now launch 'Selenium IDE' and you will notice a new icon, "Pause on Fail" on recording toolbar as shown below. Click it to turn it ON. Upon clicking again, itwould be turned "OFF".

<img width="924" height="663" alt="image" src="https://github.com/user-attachments/assets/5a4fdc9f-a216-444e-8e4f-db3c3114df50" />

Step 3 − Users can turn "pause on fail" on or off any time even when the test is running.

Step 4 − Once the test case pauses due to a failed step, you can use the resume/step buttons to continue the test execution. The execution will NOT be paused if the failure is on the last command of any test case.

Step 5 − We can also use breakpoints to understand what exactly happens during the step. To insert a breakpoint on a particular step, "Right Click" and select "Toggle Breakpoint" from the context- sensitive menu.

<img width="917" height="324" alt="image" src="https://github.com/user-attachments/assets/24fa993c-2943-48bb-aeef-0c1b32dfca3b" />

Step 6 − Upon inserting the breakpoint, the particular step is displayed with a pause icon as shown below.

<img width="923" height="576" alt="image" src="https://github.com/user-attachments/assets/ddb352c0-8dc3-4d45-9e86-909a7255973e" />

Step 7 − When we execute the script, the script execution is paused where the breakpoint is inserted. This will help the user to evaluate the value/presence of an element when the execution is inprogress.

<img width="923" height="506" alt="image" src="https://github.com/user-attachments/assets/b02454b4-5c2f-471f-9866-29936224db95" />

## Inserting Verification Points
This section describes how to insert verification points in Selenium IDE.

The test cases that we develop also need to check the properties of a web page. It requires assert and verify commands. There are two ways to insert verification points into the script. To insert a verification point in recording mode, "Right click" on the element and choose "Show all Available Commands" as shown below.

<img width="921" height="520" alt="image" src="https://github.com/user-attachments/assets/bb41102d-1907-4667-89a6-5efa333f3325" />

We can also insert a command by performing a "Right-Click" and choosing "Insert New Command".

<img width="928" height="332" alt="image" src="https://github.com/user-attachments/assets/d93a13c3-1ac5-459b-84f5-ae7f4245da30" />

After inserting a new command, click 'Command' dropdown and select appropriate verification point from the available list of commands as shown below.

<img width="931" height="557" alt="image" src="https://github.com/user-attachments/assets/4591a994-1768-4b22-bbde-2db00623e1c7" />



Given below are the mostly used verification commands that help us check if a particular step has passed or failed.

 verifyElementPresent  assertElementPresent  verifyElementNotPresent  assertElementNotPresent  verifyText  assertText  verifyAttribute  assertAttribute  verifyChecked  assertChecked  verifyAlert  assertAlert  verifyTitle  assertTitle

## SynchronizationPoints
During script execution, the application might respond based on server load, hence it is required for the application and script to be in sync. Given below are few a commands that we can use to ensure that the script and application are in sync.

waitForAlertNotPresent

waitForAlertPresent

waitForElementPresent

waitForElementNotPresent

waitForTextPresent

waitForTextNotPresent

waitForPageToLoad

waitForFrameToLoad

## Selenium Pattern Matching
□ This section deals with how to work with regular expressions using IDE. Like locators, patterns are a type of parameter frequently used by Selenium. It allows users to describe patterns with the help of special characters. Many a time, the text that we would like to verify are dynamic; in that case, pattern matching is very useful.

Pattern matching is used with all the verification point commands - verifyTextPresent, verifyTitle, verifyAlert, assertConfirmation, verifyText, and verifyPrompt. There are three ways to define a pattern −

Globbing

Globbing

regular expressions, and exact patterns.

Most techies who have used file matching patterns in Linux or Windows while searching for a certain file type like *.doc or *.jpg. would be familiar with term "globbing"

Globbing in Selenium supports only three special characters: *, ?, and [ ].

• * − matches any number of characters.

• ? − matches a single character.

□ [ ] − called a character class, lets you match any single character found within the brackets. [0- 9] matches any digit.

To specify a glob in a Selenium command, prefix the pattern with the keyword 'glob:'. For example, if you would like to search for the texts "tax year 2013" or "tax year 2014", then you can use the golb "tax year *" as shown below.

However the usage of "glob:" is optional while specifying a text pattern because globbing patterns are the default in Selenium.

<img width="928" height="332" alt="image" src="https://github.com/user-attachments/assets/91e96dac-c331-48ae-8a1d-595919828efb" />

ExactPatterns Patterns with the prefix 'exact:' will match the given text as it is. Let us say, the user wants an exact match with the value string, i.e., without the glob operator doing its work, one can use the 'exact' pattern as shown below. In this example the operator '*' will work as a normal character rather than apattern- matching wildcard character.

<img width="879" height="286" alt="image" src="https://github.com/user-attachments/assets/994e6e3a-9010-462a-aeff-019fc73becc0" />

## RegularExpressions
Regular expressions are the most useful among the pattern matching techniques available. Selenium supports the complete set of regular expression patterns that Javascript supports. Hence the users are no longer limited by *, ? and [] globbing patterns.

To use RegEx patterns, we need to prefix with either "regexp:" or "regexpi:". The prefix "regexpi" is case- insensitive. The glob: and the exact: patterns are the subsets of the Regular Expression patterns. Everything that is done with glob: or exact: can be accomplished with the help of RegExp.

## Example
For example, the following will test if an input field with the id 'name' contains the string 'tax year', 'Tax Year', or 'tax Year'

<img width="797" height="253" alt="image" src="https://github.com/user-attachments/assets/983d6985-247f-4ecf-b1fe-57e77e1e414c" />

## Selenium User Extensions
The Java script that allows users to customize or add new functionality.

It is easy to extend Selenium IDE by adding customized actions, assertions, and locator-strategies. It is done with the help of JavaScript by adding methods to the Selenium object prototype. On startup, Selenium will automatically look through the methods on these prototypes, using name patterns to recognize which ones are actions, assertions, and locators.

Let us add a 'while' Loop in Selenium IDE with the help of JavaScript.

Step 1 − To add the js file, first navigate to https://github.com/darrenderidder/sideflow/blob/master/sideflow.js and copy the script and place save it as 'sideflow.js' in your local folder as shown below

<img width="716" height="185" alt="image" src="https://github.com/user-attachments/assets/598bb92a-b4e3-4d71-9cfe-f4785909694b" />

Step 2 − Now launch 'Selenium IDE' and navigate to "Options" >> "Options" as shown below.

<img width="945" height="270" alt="image" src="https://github.com/user-attachments/assets/f162fd3e-c64a-4628-adc8-aa01fdfa2d4b" />

Step 3 − Click the 'Browse' button under 'Selenium Core Extensions' area and point to the js file that we have saved in Step 1.

<img width="805" height="314" alt="image" src="https://github.com/user-attachments/assets/9bbd0c57-363e-4afa-a48b-f85a06f98e2e" />

Step 4 − Restart Selenium IDE.

Step 5 − Now you will have access to a few more commands such as "Label", "While" etc.

Step 6 − Now we will be able to create a While loop within Selenium IDE and it will execute as shown below.

<img width="941" height="424" alt="image" src="https://github.com/user-attachments/assets/562d2443-e0d9-4952-bf21-34f4bdb74d64" />

## Result:
Thus, the study of selenium web testing tool is conducted and the results were noted.
