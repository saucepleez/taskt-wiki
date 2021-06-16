<!--TITLE: Automation Commands -->
<!-- SUBTITLE: an overview of available commands in taskt. -->
## Automation Commands
| Command Group   	| Command Name 	|  Command Description	|
| ---                | ---           | ---                   |
|Dictionary Commands|[Add Dictionary Item](/automation-commands/dictionary-commands/add-dictionary-item-command)|This command Adds a key and value to a existing Dictionary|
|Loop Commands|[Begin Loop](/automation-commands/loop-commands/begin-loop-command)|This command allows you to evaluate a logical statement to determine if the statement is true. The following actions will repeat continuously until that statement becomes false|
|Loop Commands|[Begin Multi Loop](/automation-commands/loop-commands/begin-multi-loop-command)|This command allows you to evaluate a logical statement to determine if the statement is true. The following actions will repeat continuously until that statement becomes false|
|Dictionary Commands|[Create Dictionary](/automation-commands/dictionary-commands/create-dictionary-command)|This command created a DataTable with the column names provided|
|If Commands|[Begin Multi If](/automation-commands/if-commands/begin-multi-if-command)|This command allows you to evaluate a logical statement to determine if the statement is true.|
|Folder Operation Commands|[Create Folder](/automation-commands/folder-operation-commands/create-folder-command)|This command creates a folder in a specified destination|
|Folder Operation Commands|[Delete Folder](/automation-commands/folder-operation-commands/delete-folder-command)|This command deletes a folder from a specified destination|
|Excel Commands|[Split Range By Column](/automation-commands/excel-commands/split-range-by-column-command)|This command gets text from a specified Excel Range and splits it into separate ranges by column.|
|Excel Commands|[Write Row](/automation-commands/excel-commands/write-row-command)|This command writes a DataRow to an excel sheet starting from the given cell address.|
|File Operation Commands|[File Extraction](/automation-commands/file-operation-commands/file-extraction-command)||
|DataTable Commands|[Get DataRow](/automation-commands/datatable-commands/get-datarow-command)|This command allows you to get a DataRow from a DataTable|
|DataTable Commands|[Get DataRow Count](/automation-commands/datatable-commands/get-datarow-count-command)|This command allows you to get the datarow count of a DataTable|
|DataTable Commands|[Get DataRow Value](/automation-commands/datatable-commands/get-datarow-value-command)|This command allows you to get a DataRow Value from a DataTable|
|File Operation Commands|[Get Files](/automation-commands/file-operation-commands/get-files-command)|This command returns a list of file paths from a specified location|
|Folder Operation Commands|[Get Folders](/automation-commands/folder-operation-commands/get-folders-command)|This command returns a list of folder directories from a specified location|
|Data Commands|[Get List Count](/automation-commands/data-commands/get-list-count-command)|This command allows you to get the item count of a List|
|Data Commands|[Get List Item](/automation-commands/data-commands/get-list-item-command)|This command allows you to get an item from a List|
|Folder Operation Commands|[Move/Copy Folder](/automation-commands/folder-operation-commands/move-copy-folder-command)|This command moves a folder to a specified destination|
|Loop Commands|[Next Loop](/automation-commands/loop-commands/next-loop-command)|This command enables user to break and exit from the current loop|
|Outlook Commands|[Delete Outlook Emails](/automation-commands/outlook-commands/delete-outlook-emails-command)|This command allows you to delete emails with outlook|
|Outlook Commands|[Send Outlook Email](/automation-commands/outlook-commands/send-outlook-email-command)|This command allows you to send emails with outlook|
|Regex Commands|[Get Regex Matches](/automation-commands/regex-commands/get-regex-matches-command)|This command allows you to loop through an Excel Dataset|
|Dictionary Commands|[Get Dictionary Item](/automation-commands/dictionary-commands/get-dictionary-item-command)|This command allows you to loop through an Excel Dataset|
|DataTable Commands|[Add DataRow](/automation-commands/datatable-commands/add-datarow-command)|This command allows you to add a datarow to a DataTable|
|Variable Commands|[New Variable](/automation-commands/variable-commands/new-variable-command)|This command allows you to explicitly add a variable if you are not using **Set Variable* with the setting **Create Missing Variables** at runtime.|
|If Commands|[Begin If](/automation-commands/if-commands/begin-if-command)|This command allows you to evaluate a logical statement to determine if the statement is true.|
|Loop Commands|[Loop Continuously](/automation-commands/loop-commands/loop-continuously-command)|This command allows you to repeat actions continuously.  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Loop Commands|[Loop Excel Dataset](/automation-commands/loop-commands/loop-excel-dataset-command)|This command allows you to loop through an Excel Dataset|
|Loop Commands|[Loop List](/automation-commands/loop-commands/loop-list-command)|This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Loop Commands|[Loop Number Of Times](/automation-commands/loop-commands/loop-number-of-times-command)|This command allows you to repeat actions several times (loop).  Any 'Begin Loop' command must have a following 'End Loop' command.|
|Window Commands|[Activate Window](/automation-commands/window-commands/activate-window-command)|This command activates a window and brings it to the front.|
|Misc Commands|[Get Clipboard Text](/automation-commands/misc-commands/get-clipboard-text-command)|This command allows you to get text from the clipboard.|
|Misc Commands|[Set Clipboard Text](/automation-commands/misc-commands/set-clipboard-text-command)|This command allows you to set text to the clipboard.|
|DataTable Commands|[Create DataTable](/automation-commands/datatable-commands/create-datatable-command)|This command created a DataTable with the column names provided|
|Database Commands|[Execute Database Query](/automation-commands/database-commands/execute-database-query-command)|This command allows you to perform a database query and apply the result to a dataset|
|Database Commands|[Define Database Connection](/automation-commands/database-commands/define-database-connection-command)|This command allows you to define a connection to an OLEDB data source|
|Error Handling Commands|[Catch Exception](/automation-commands/error-handling-commands/catch-exception-command)|This command allows you to define actions that should occur after encountering an error.|
|Data Commands|[Math Calculation](/automation-commands/data-commands/math-calculation-command)|This command allows you to perform a math calculation and apply it to a variable.|
|Error Handling Commands|[End Try](/automation-commands/error-handling-commands/end-try-command)|This command specifies the end of a try/catch block.|
|Excel Commands|[Append Cell](/automation-commands/excel-commands/append-cell-command)|Append input to last row of sheet into the first cell.|
|Excel Commands|[Append Row](/automation-commands/excel-commands/append-row-command)|Append to last row of sheet.|
|Excel Commands|[Get Range](/automation-commands/excel-commands/get-range-command)|This command gets text from a specified Excel Range.|
|Excel Commands|[Get Range As Datatable](/automation-commands/excel-commands/get-range-as-datatable-command)|This command gets text from a specified Excel Range and put it into a DataTable.|
|Dictionary Commands|[Load Dictionary](/automation-commands/dictionary-commands/load-dictionary-command)|This command Reads a Config file and stores it into a Dictionary.|
|Excel Commands|[Write Range](/automation-commands/excel-commands/write-range-command)|This command writes a datatable to an excel sheet starting from the given cell address.|
|Error Handling Commands|[Finally](/automation-commands/error-handling-commands/finally-command)|This command specifies execution that should occur whether or not an error occured|
|Misc Commands|[Encryption Command](/automation-commands/misc-commands/encryption-command-command)|This command handles text encryption|
|Outlook Commands|[Forward Outlook Emails](/automation-commands/outlook-commands/forward-outlook-emails-command)|This command allows you to forward emails with outlook|
|Outlook Commands|[Get Outlook Emails](/automation-commands/outlook-commands/get-outlook-emails-command)|This command allows you to get emails and attachments with outlook|
|Outlook Commands|[Move/Copy Outlook Emails](/automation-commands/outlook-commands/move-copy-outlook-emails-command)|This command allows you to move/copy emails with outlook|
|Outlook Commands|[Reply To Outlook Emails](/automation-commands/outlook-commands/reply-to-outlook-emails-command)|This command allows you to reply to emails with outlook|
|Data Commands|[Parse JSON Model](/automation-commands/data-commands/parse-json-model-command)|This command allows you to parse a JSON object into a list.|
|Remote Commands|[Remote API](/automation-commands/remote-commands/remote-api-command)|This command allows you to execute automation against another taskt Client.|
|Remote Commands|[Remote Task](/automation-commands/remote-commands/remote-task-command)|This command allows you to execute a task remotely on another taskt instance|
|DataTable Commands|[Filter DataTable](/automation-commands/datatable-commands/filter-datatable-command)|This command allows you filter a DataTable into a new Datatable|
|DataTable Commands|[Remove DataRow](/automation-commands/datatable-commands/remove-datarow-command)|This command allows you remove specified data rows.|
|Folder Operation Commands|[Rename Folder](/automation-commands/folder-operation-commands/rename-folder-command)|This command renames a folder at a specified destination|
|Web Browser Commands|[Switch Browser Frame](/automation-commands/web-browser-commands/switch-browser-frame-command)|This command allows you to create a new Selenium web browser session which enables automation for websites.|
|Engine Commands|[Set Engine Preference](/automation-commands/engine-commands/set-engine-preference-command)|This command allows you to set preferences for engine behavior.|
|Error Handling Commands|[Throw Exception](/automation-commands/error-handling-commands/throw-exception-command)|This command allows you to throw an exception error.|
|Error Handling Commands|[Try](/automation-commands/error-handling-commands/try-command)|This command allows embedding commands and will automatically move to the 'catch' handler|
|Data Commands|[Parse Dataset Row](/automation-commands/data-commands/parse-dataset-row-command)|This command allows you to parse a dataset row column into a variable.|
|Engine Commands|[Show Engine Context](/automation-commands/engine-commands/show-engine-context-command)|This command allows you to show a message to the user.|
|NLG Commands|[Generate NLG Phrase](/automation-commands/nlg-commands/generate-nlg-phrase-command)|This command pauses the script for a set amount of time specified in milliseconds.|
|NLG Commands|[Set NLG Parameter](/automation-commands/nlg-commands/set-nlg-parameter-command)|This command allows you to define a NLG parameter|
|IE Browser Commands|[Find Browser](/automation-commands/ie-browser-commands/find-browser-command)|This command allows you to find and attach to an existing IE web browser session.|
|System Commands|[OS Variable](/automation-commands/system-commands/os-variable-command)|This command allows you to exclusively select a system/environment variable|
|Engine Commands|[Get BotStore Data](/automation-commands/engine-commands/get-botstore-data-command)|This command allows you to get data from tasktServer.|
|Window Commands|[Close Window](/automation-commands/window-commands/close-window-command)|This command closes an open window.|
|Misc Commands|[Add Code Comment](/automation-commands/misc-commands/add-code-comment-command)|This command allows you to add an in-line comment to the script.|
|Misc Commands|[Show Message](/automation-commands/misc-commands/show-message-command)|This command allows you to show a message to the user.|
|Data Commands|[Parse JSON Array](/automation-commands/data-commands/parse-json-array-command)|This command allows you to parse a JSON Array into a list.|
|NLG Commands|[Create NLG Instance](/automation-commands/nlg-commands/create-nlg-instance-command)|This command pauses the script for a set amount of time specified in milliseconds.|
|API Commands|[Execute REST API](/automation-commands/api-commands/execute-rest-api-command)|This command allows you to show a message to the user.|
|IE Browser Commands|[Close Browser](/automation-commands/ie-browser-commands/close-browser-command)|This command allows you to close the associated IE web browser|
|Web Browser Commands|[Close Browser](/automation-commands/web-browser-commands/close-browser-command)|This command allows you to close a Selenium web browser session.|
|IE Browser Commands|[Create Browser](/automation-commands/ie-browser-commands/create-browser-command)|This command allows you to create a new IE web browser session.|
|Web Browser Commands|[Get Browser Info](/automation-commands/web-browser-commands/get-browser-info-command)|This command allows you to navigate a Selenium web browser session to a given URL or resource.|
|Web Browser Commands|[Switch Browser Window](/automation-commands/web-browser-commands/switch-browser-window-command)|This command allows you to create a new Selenium web browser session which enables automation for websites.|
|Web Browser Commands|[Create Browser](/automation-commands/web-browser-commands/create-browser-command)|This command allows you to create a new Selenium web browser session which enables automation for websites.|
|Window Commands|[Move Window](/automation-commands/window-commands/move-window-command)|This command moves a window to a specified location on screen.|
|Window Commands|[Resize Window](/automation-commands/window-commands/resize-window-command)|This command resizes a window to a specified size.|
|Programs/Process Commands|[Run Custom Code](/automation-commands/programs-process-commands/run-custom-code-command)|This command allows you to run C# code from the input|
|Programs/Process Commands|[Run Script](/automation-commands/programs-process-commands/run-script-command)|This command allows you to run a script or program and wait for it to exit before proceeding.|
|IE Browser Commands|[Element Action](/automation-commands/ie-browser-commands/element-action-command)|This command allows you to manipulate (get or set) elements within the HTML document of the associated IE web browser.  Features an assisting element capture form|
|Web Browser Commands|[Element Action](/automation-commands/web-browser-commands/element-action-command)|This command allows you to close a Selenium web browser session.|
|Web Browser Commands|[Execute Script](/automation-commands/web-browser-commands/execute-script-command)|This command allows you to execute a script in a Selenium web browser session.|
|Web Browser Commands|[Navigate Back](/automation-commands/web-browser-commands/navigate-back-command)|This command allows you to navigate backwards in a Selenium web browser session.|
|Web Browser Commands|[Navigate Forward](/automation-commands/web-browser-commands/navigate-forward-command)|This command allows you to navigate forward a Selenium web browser session.|
|IE Browser Commands|[Navigate to URL](/automation-commands/ie-browser-commands/navigate-to-url-command)|This command allows you to navigate a IE web browser session to a given URL or resource.|
|Web Browser Commands|[Navigate to URL](/automation-commands/web-browser-commands/navigate-to-url-command)|This command allows you to navigate a Selenium web browser session to a given URL or resource.|
|Web Browser Commands|[Refresh](/automation-commands/web-browser-commands/refresh-command)|This command allows you to refresh a Selenium web browser session.|
|Window Commands|[Set Window State](/automation-commands/window-commands/set-window-state-command)|This command sets a target window's state.|
|Misc Commands|[Send SMTP Email](/automation-commands/misc-commands/send-smtp-email-command)|This command allows you to send email using SMTP protocol.|
|Programs/Process Commands|[Start Process](/automation-commands/programs-process-commands/start-process-command)|This command allows you to start a program or a process.|
|System Commands|[Launch Remote Desktop](/automation-commands/system-commands/launch-remote-desktop-command)|This command allows you to stop a program or a process.|
|System Commands|[Environment Variable](/automation-commands/system-commands/environment-variable-command)|This command allows you to exclusively select a system/environment variable|
|Data Commands|[Modify Variable](/automation-commands/data-commands/modify-variable-command)|This command allows you to trim a string|
|System Commands|[System Action](/automation-commands/system-commands/system-action-command)|This command allows you to perform an account action|
|Engine Commands|[Stopwatch](/automation-commands/engine-commands/stopwatch-command)|This command allows you to stop a program or a process.|
|Programs/Process Commands|[Stop Process](/automation-commands/programs-process-commands/stop-process-command)|This command allows you to stop a program or a process.|
|Variable Commands|[Add To Variable](/automation-commands/variable-commands/add-to-variable-command)|This command allows you to modify variables.|
|Variable Commands|[Set Variable Index](/automation-commands/variable-commands/set-variable-index-command)|This command allows you to modify variables.|
|Window Commands|[Wait For Window To Exist](/automation-commands/window-commands/wait-for-window-to-exist-command)|This command waits for a window to exist.|
|Input Commands|[Prompt for HTML Input](/automation-commands/input-commands/prompt-for-html-input-command)|Allows the entry of data into a web-enabled form|
|Input Commands|[Send Advanced Keystrokes](/automation-commands/input-commands/send-advanced-keystrokes-command)|Sends advanced keystrokes to a targeted window|
|Input Commands|[Send Keystrokes](/automation-commands/input-commands/send-keystrokes-command)|Sends keystrokes to a targeted window|
|Input Commands|[Send Mouse Click](/automation-commands/input-commands/send-mouse-click-command)|Simulates mouse clicks.|
|Input Commands|[Send Mouse Move](/automation-commands/input-commands/send-mouse-move-command)|Simulates mouse movements|
|Misc Commands|[Sequence Command](/automation-commands/misc-commands/sequence-command-command)|Command that groups multiple actions|
|Input Commands|[Click UI Item](/automation-commands/input-commands/click-ui-item-command)|This command clicks an item in a Thick Application window.|
|Input Commands|[Get UI Item](/automation-commands/input-commands/get-ui-item-command)|This command gets text from a Thick Application window|
|Input Commands|[UI Automation](/automation-commands/input-commands/ui-automation-command)|Combined implementation of the ThickAppClick/GetText command but includes an advanced Window Recorder to record the required element.|
|Input Commands|[Prompt for Input](/automation-commands/input-commands/prompt-for-input-command)|Sends keystrokes to a targeted window|
|Database Commands|[Run Query](/automation-commands/database-commands/run-query-command)|This command selects data from a database and applies it against a dataset|
|Data Commands|[Date Calculation](/automation-commands/data-commands/date-calculation-command)|This command allows you to build a date and apply it to a variable.|
|Loop Commands|[End Loop](/automation-commands/loop-commands/end-loop-command)|This command signifies the exit point of looped (repeated) actions.  Required for all loops.|
|Excel Commands|[Activate Sheet](/automation-commands/excel-commands/activate-sheet-command)|This command allows you to activate a specific worksheet in a workbook|
|Excel Commands|[Add Workbook](/automation-commands/excel-commands/add-workbook-command)|This command adds a new Excel Workbook.|
|Excel Commands|[Close Excel Application](/automation-commands/excel-commands/close-excel-application-command)|This command allows you to close Excel.|
|Excel Commands|[Create Excel Application](/automation-commands/excel-commands/create-excel-application-command)|This command opens the Excel Application.|
|Excel Commands|[Create Dataset](/automation-commands/excel-commands/create-dataset-command)|This command gets a range of cells and applies them against a dataset|
|Excel Commands|[Delete Cell](/automation-commands/excel-commands/delete-cell-command)|This command allows you to delete a specified cell in Excel|
|Excel Commands|[Delete Row](/automation-commands/excel-commands/delete-row-command)|This command allows you to delete a specified row in Excel|
|Excel Commands|[Get Cell](/automation-commands/excel-commands/get-cell-command)|This command gets text from a specified Excel Cell.|
|Excel Commands|[Get Last Row Index](/automation-commands/excel-commands/get-last-row-index-command)|This command allows you to find the last row in a used range in an Excel Workbook.|
|Excel Commands|[Go To Cell](/automation-commands/excel-commands/go-to-cell-command)|This command moves to a specific cell.|
|Excel Commands|[Open Workbook](/automation-commands/excel-commands/open-workbook-command)|This command opens an Excel Workbook.|
|Excel Commands|[Run Macro](/automation-commands/excel-commands/run-macro-command)|This command runs a macro.|
|Excel Commands|[Save Workbook As](/automation-commands/excel-commands/save-workbook-as-command)|This command allows you to save an Excel workbook.|
|Excel Commands|[Save Workbook](/automation-commands/excel-commands/save-workbook-command)|This command allows you to save an Excel workbook.|
|Excel Commands|[Set Cell](/automation-commands/excel-commands/set-cell-command)|This command sets the value of a cell.|
|Loop Commands|[Exit Loop](/automation-commands/loop-commands/exit-loop-command)|This command signifies the current loop should exit and resume work past the point of the current loop.|
|Data Commands|[Format Data](/automation-commands/data-commands/format-data-command)|This command allows you to apply formatting to a string|
|Data Commands|[Get Word Count](/automation-commands/data-commands/get-word-count-command)|This command allows you to parse a JSON object into a list.|
|Data Commands|[Get Word Length](/automation-commands/data-commands/get-word-length-command)|This command allows you to retrieve the length of a string or variable.|
|Data Commands|[Log Data](/automation-commands/data-commands/log-data-command)|This command logs data to files.|
|Data Commands|[Parse JSON Item](/automation-commands/data-commands/parse-json-item-command)|This command allows you to parse a JSON object into a list.|
|Data Commands|[PDF Extraction](/automation-commands/data-commands/pdf-extraction-command)||
|Data Commands|[RegEx Extraction](/automation-commands/data-commands/regex-extraction-command)|This command allows you to perform advanced string formatting using RegEx.|
|Data Commands|[Replace Text](/automation-commands/data-commands/replace-text-command)|This command allows you to replace text|
|Data Commands|[Split Text](/automation-commands/data-commands/split-text-command)|This command allows you to split a string|
|Data Commands|[Substring](/automation-commands/data-commands/substring-command)|This command allows you to trim a string|
|Data Commands|[Text Extraction](/automation-commands/data-commands/text-extraction-command)|This command allows you to perform advanced string extraction.|
|File Operation Commands|[Delete File](/automation-commands/file-operation-commands/delete-file-command)|This command deletes a file from a specified destination|
|If Commands|[Else](/automation-commands/if-commands/else-command)|This command declares the seperation between the actions based on the 'true' or 'false' condition.|
|If Commands|[End If](/automation-commands/if-commands/end-if-command)|This command signifies the exit point of If actions.  Required for all Begin Ifs.|
|Engine Commands|[Error Handling](/automation-commands/engine-commands/error-handling-command)|This command specifies what to do  after an error is encountered.|
|API Commands|[Execute DLL](/automation-commands/api-commands/execute-dll-command)|This command processes an HTML source object|
|API Commands|[HTTP Result Query](/automation-commands/api-commands/http-result-query-command)|This command processes an HTML source object|
|API Commands|[HTTP Request](/automation-commands/api-commands/http-request-command)|This command downloads the HTML source of a web page for parsing|
|Image Commands|[Image Recognition](/automation-commands/image-commands/image-recognition-command)|This command attempts to find an existing image on screen.|
|File Operation Commands|[Move/Copy File](/automation-commands/file-operation-commands/move-copy-file-command)|This command moves a file to a specified destination|
|Image Commands|[Perform OCR](/automation-commands/image-commands/perform-ocr-command)|This command allows you to covert an image file into text for parsing.|
|Engine Commands|[Pause Script](/automation-commands/engine-commands/pause-script-command)|This command pauses the script for a set amount of time specified in milliseconds.|
|Text File Commands|[Read Text File](/automation-commands/text-file-commands/read-text-file-command)|This command reads text data into a variable|
|File Operation Commands|[Rename File](/automation-commands/file-operation-commands/rename-file-command)|This command renames a file at a specified destination|
|Task Commands|[Run Task](/automation-commands/task-commands/run-task-command)|This command runs tasks.|
|Image Commands|[Take Screenshot](/automation-commands/image-commands/take-screenshot-command)|This command takes a screenshot and saves it to a location|
|Engine Commands|[Set Engine Delay](/automation-commands/engine-commands/set-engine-delay-command)|This command allows you to set delays between execution of commands in a running instance.|
|Task Commands|[Stop Current Task](/automation-commands/task-commands/stop-current-task-command)|This command stops the current task.|
|Engine Commands|[Upload BotStore Data](/automation-commands/engine-commands/upload-botstore-data-command)|This command allows you to upload data to a local tasktServer bot store|
|Variable Commands|[Set Variable](/automation-commands/variable-commands/set-variable-command)|This command allows you to modify variables.|
|File Operation Commands|[Wait For File](/automation-commands/file-operation-commands/wait-for-file-command)|This command waits for a file to exist at a specified destination|
|Word Commands|[Add Document](/automation-commands/word-commands/add-document-command)|This command adds a new Word Document.|
|Word Commands|[Append DataTable](/automation-commands/word-commands/append-datatable-command)|This command appends a datatable to a word document.|
|Word Commands|[Append Image](/automation-commands/word-commands/append-image-command)|This command appends an image to a word document.|
|Word Commands|[Append Text](/automation-commands/word-commands/append-text-command)|This command appends text to a word document.|
|Word Commands|[Close Word Application](/automation-commands/word-commands/close-word-application-command)|This command allows you to close Word.|
|Word Commands|[Create Word Application](/automation-commands/word-commands/create-word-application-command)|This command creates a Word Application.|
|Word Commands|[Export To PDF](/automation-commands/word-commands/export-to-pdf-command)|This command allows you to export a Word document to a PDF.|
|Word Commands|[Open Document](/automation-commands/word-commands/open-document-command)|This command opens an Word Document.|
|Word Commands|[Read Document](/automation-commands/word-commands/read-document-command)|This command allows you to save a Word document.|
|Word Commands|[Replace Text](/automation-commands/word-commands/replace-text-command)|This command allows you to replace text in a Word document.|
|Word Commands|[Save Document As](/automation-commands/word-commands/save-document-as-command)|This command allows you to save an Word document.|
|Word Commands|[Save Document](/automation-commands/word-commands/save-document-command)|This command allows you to save a Word document.|
|DataTable Commands|[Write DataRow Value](/automation-commands/datatable-commands/write-datarow-value-command)|This command allows you to write a Value to a DataRow|
|Text File Commands|[Write Text File](/automation-commands/text-file-commands/write-text-file-command)|This command writes specified data to a text file|
This page was generated on 06/16/21 10:47 午後


## Help
[Open/Report an issue on GitHub](https://github.com/saucepleez/taskt/issues/new)
[Ask a question on Gitter](https://gitter.im/taskt-rpa/Lobby)
