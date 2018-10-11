<!--TITLE: Automation Commands -->
<!-- SUBTITLE: an overview of available commands in taskt. -->
## Automation Commands
| Command Group   	| Command Name 	|  Command Description	|
| ---                | ---           | ---                   |
|IE Browser Commands|[Create Browser](/automation-commands/ie-browser-commands/create-browser-command)|This command allows you to create a new IE web browser session.|
|IE Browser Commands|[Find Browser](/automation-commands/ie-browser-commands/find-browser-command)|This command allows you to find and attach to an existing IE web browser session.|
|IE Browser Commands|[Navigate](/automation-commands/ie-browser-commands/navigate-command)|This command allows you to navigate the associated IE web browser to a URL.|
|IE Browser Commands|[Close Browser](/automation-commands/ie-browser-commands/close-browser-command)|This command allows you to close the associated IE web browser|
|IE Browser Commands|[Element Action](/automation-commands/ie-browser-commands/element-action-command)|This command allows you to manipulate (get or set) elements within the HTML document of the associated IE web browser.  Features an assisting element capture form|
|Web Browser Commands|[Create Browser](/automation-commands/web-browser-commands/create-browser-command)|This command allows you to create a new Selenium web browser session which enables automation for websites.|
|Web Browser Commands|[Navigate to URL](/automation-commands/web-browser-commands/navigate-to-url-command)|This command allows you to navigate a Selenium web browser session to a given URL or resource.|
|Web Browser Commands|[Navigate Forward](/automation-commands/web-browser-commands/navigate-forward-command)|This command allows you to navigate forward a Selenium web browser session.|
|Web Browser Commands|[Navigate Back](/automation-commands/web-browser-commands/navigate-back-command)|This command allows you to navigate backwards in a Selenium web browser session.|
|Web Browser Commands|[Refresh](/automation-commands/web-browser-commands/refresh-command)|This command allows you to refresh a Selenium web browser session.|
|Web Browser Commands|[Close Browser](/automation-commands/web-browser-commands/close-browser-command)|This command allows you to close a Selenium web browser session.|
|Web Browser Commands|[Element Action](/automation-commands/web-browser-commands/element-action-command)|This command allows you to close a Selenium web browser session.|
|Misc Commands|[Pause Script](/automation-commands/misc-commands/pause-script-command)|This command pauses the script for a set amount of time specified in milliseconds.|
|Misc Commands|[Error Handling](/automation-commands/misc-commands/error-handling-command)|This command specifies what to do  after an error is encountered.|
|Misc Commands|[Add Code Comment](/automation-commands/misc-commands/add-code-comment-command)|This command allows you to add an in-line comment to the script.|
|Misc Commands|[Show Message](/automation-commands/misc-commands/show-message-command)|This command allows you to show a message to the user.|
|Misc Commands|[Send SMTP Email](/automation-commands/misc-commands/send-smtp-email-command)|This command allows you to send email using SMTP protocol.|
|Window Commands|[Activate Window](/automation-commands/window-commands/activate-window-command)|This command activates a window and brings it to the front.|
|Window Commands|[Move Window](/automation-commands/window-commands/move-window-command)|This command moves a window to a specified location on screen.|
|Window Commands|[Resize Window](/automation-commands/window-commands/resize-window-command)|This command resizes a window to a specified size.|
|Window Commands|[Close Window](/automation-commands/window-commands/close-window-command)|This command closes an open window.|
|Window Commands|[Set Window State](/automation-commands/window-commands/set-window-state-command)|This command sets a target window's state.|
|Window Commands|[Wait For Window To Exist](/automation-commands/window-commands/wait-for-window-to-exist-command)|This command waits for a window to exist.|
|Programs/Process Commands|[Start Process](/automation-commands/programs-process-commands/start-process-command)|This command allows you to start a program or a process.|
|Programs/Process Commands|[Stop Process](/automation-commands/programs-process-commands/stop-process-command)|This command allows you to stop a program or a process.|
|Programs/Process Commands|[Run Script](/automation-commands/programs-process-commands/run-script-command)|This command allows you to run a script or program and wait for it to exit before proceeding.|
|Programs/Process Commands|[Run Custom Code](/automation-commands/programs-process-commands/run-custom-code-command)|This command allows you to run C# code from the input|
|Clipboard Commands|[Get Text](/automation-commands/clipboard-commands/get-text-command)|This command allows you to get text from the clipboard.|
|Input Commands|[Send Keystrokes](/automation-commands/input-commands/send-keystrokes-command)|Sends keystrokes to a targeted window|
|Input Commands|[Send Mouse Move](/automation-commands/input-commands/send-mouse-move-command)|Simulates mouse movements|
|Misc Commands|[Sequence Command](/automation-commands/misc-commands/sequence-command-command)|Command that groups multiple actions|
|Input Commands|[Send Mouse Click](/automation-commands/input-commands/send-mouse-click-command)|Simulates mouse clicks.|
|Input Commands|[Click UI Item](/automation-commands/input-commands/click-ui-item-command)|This command clicks an item in a Thick Application window.|
|Input Commands|[Get UI Item](/automation-commands/input-commands/get-ui-item-command)|This command gets text from a Thick Application window|
|Input Commands|[UI Automation](/automation-commands/input-commands/ui-automation-command)|Combined implementation of the ThickAppClick/GetText command but includes an advanced Window Recorder to record the required element.|
|Database Commands|[Run Query](/automation-commands/database-commands/run-query-command)|This command selects data from a database and applies it against a dataset|
|Loop Commands|[Loop Continuously](/automation-commands/loop-commands/loop-continuously-command)|This command allows you to repeat actions continuously.  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Loop Commands|[Loop Number Of Times](/automation-commands/loop-commands/loop-number-of-times-command)|This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Loop Commands|[Loop List](/automation-commands/loop-commands/loop-list-command)|This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Loop Commands|[Loop Excel Dataset](/automation-commands/loop-commands/loop-excel-dataset-command)|This command allows you to loop through an Excel Dataset|
|Loop Commands|[End Loop](/automation-commands/loop-commands/end-loop-command)|This command signifies the exit point of looped (repeated) actions.  Required for all loops.|
|Loop Commands|[Exit Loop](/automation-commands/loop-commands/exit-loop-command)|This command signifies the current loop should exit and resume work past the point of the current loop.|
|Excel Commands|[Create Excel Application](/automation-commands/excel-commands/create-excel-application-command)|This command opens the Excel Application.|
|Excel Commands|[Open Workbook](/automation-commands/excel-commands/open-workbook-command)|This command opens an Excel Workbook.|
|Excel Commands|[Add Workbook](/automation-commands/excel-commands/add-workbook-command)|This command adds a new Excel Workbook.|
|Excel Commands|[Go To Cell](/automation-commands/excel-commands/go-to-cell-command)|This command moves to a specific cell.|
|Excel Commands|[Set Cell](/automation-commands/excel-commands/set-cell-command)|This command sets the value of a cell.|
|Excel Commands|[Get Cell](/automation-commands/excel-commands/get-cell-command)|This command gets text from a specified Excel Cell.|
|Excel Commands|[Run Macro](/automation-commands/excel-commands/run-macro-command)|This command runs a macro.|
|Excel Commands|[Get Last Row](/automation-commands/excel-commands/get-last-row-command)|This command allows you to find the last row in a used range in an Excel Workbook.|
|Excel Commands|[Close Application](/automation-commands/excel-commands/close-application-command)|This command allows you to close Excel.|
|Excel Commands|[Activate Sheet](/automation-commands/excel-commands/activate-sheet-command)|This command allows you to activate a specific worksheet in a workbook|
|Excel Commands|[Delete Row](/automation-commands/excel-commands/delete-row-command)|This command allows you to delete a specified row in Excel|
|Excel Commands|[Delete Cell](/automation-commands/excel-commands/delete-cell-command)|This command allows you to delete a specified cell in Excel|
|Excel Commands|[Create Dataset](/automation-commands/excel-commands/create-dataset-command)|This command gets a range of cells and applies them against a dataset|
|Data Commands|[Set Variable](/automation-commands/data-commands/set-variable-command)|This command allows you to modify variables.|
|Data Commands|[Date Calculation](/automation-commands/data-commands/date-calculation-command)|This command allows you to build a date and apply it to a variable.|
|Data Commands|[Format Data](/automation-commands/data-commands/format-data-command)|This command allows you to apply formatting to a string|
|Data Commands|[Substring](/automation-commands/data-commands/substring-command)|This command allows you to trim a string|
|Data Commands|[Split](/automation-commands/data-commands/split-command)|This command allows you to split a string|
|Data Commands|[Replace](/automation-commands/data-commands/replace-command)|This command allows you to replace text|
|Data Commands|[RegEx Extraction](/automation-commands/data-commands/regex-extraction-command)|This command allows you to perform advanced string formatting using RegEx.|
|Data Commands|[Text Extraction](/automation-commands/data-commands/text-extraction-command)|This command allows you to perform advanced string extraction.|
|Data Commands|[Log Data](/automation-commands/data-commands/log-data-command)|This command logs data to files.|
|If Commands|[Begin If](/automation-commands/if-commands/begin-if-command)|This command allows you to evaluate a logical statement to determine if the statement is true.|
|If Commands|[End If](/automation-commands/if-commands/end-if-command)|This command signifies the exit point of If actions.  Required for all Begin Ifs.|
|If Commands|[Else](/automation-commands/if-commands/else-command)|This command declares the seperation between the actions based on the 'true' or 'false' condition.|
|Image Commands|[Perform OCR](/automation-commands/image-commands/perform-ocr-command)|This command allows you to covert an image file into text for parsing.|
|Image Commands|[Take Screenshot](/automation-commands/image-commands/take-screenshot-command)|This command takes a screenshot and saves it to a location|
|Image Commands|[Image Recognition](/automation-commands/image-commands/image-recognition-command)|This command attempts to find an existing image on screen.|
|WebAPI Commands|[HTTP Request](/automation-commands/webapi-commands/http-request-command)|This command downloads the HTML source of a web page for parsing|
|WebAPI Commands|[HTTP Result Query](/automation-commands/webapi-commands/http-result-query-command)|This command processes an HTML source object|
|Task Commands|[Stop Current Task](/automation-commands/task-commands/stop-current-task-command)|This command stops the current task.|
|Task Commands|[Run Task](/automation-commands/task-commands/run-task-command)|This command runs tasks.|
|Text File Commands|[Write To File](/automation-commands/text-file-commands/write-to-file-command)|This command writes specified data to a text file|
|Text File Commands|[Read Text File](/automation-commands/text-file-commands/read-text-file-command)|This command reads text data into a variable|
|File Operation Commands|[Move/Copy File](/automation-commands/file-operation-commands/move-copy-file-command)|This command moves a file to a specified destination|
|File Operation Commands|[Delete File](/automation-commands/file-operation-commands/delete-file-command)|This command deletes a file from a specified destination|
|File Operation Commands|[Rename File](/automation-commands/file-operation-commands/rename-file-command)|This command moves a file to a specified destination|
|File Operation Commands|[Wait For File](/automation-commands/file-operation-commands/wait-for-file-command)|This command waits for a file to exist at a specified destination|
This page was generated on 10/11/18 06:14 PM


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
