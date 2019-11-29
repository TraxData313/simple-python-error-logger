# Python error/event logger:
Easy to use commands to log errors and events in a ./logs dirctory:<br>
`log_error(reporting_program_name, error_message)`<br>
`log_event(reporting_program_name, event_message)`

<br>

## Usage and examples:
- Place this file in the directory of your python code and in the code import the module by:<br>
  `import loggers`

- Define the reporting_program_name at the beggining of your program, when you have to log and error or an event, set the message you want to report in <i>error_message = "your error here" or event_message = "your event here"</i> and use the loggers as follows:<br>
  `log_error(reporting_program_name, error_message)`<br>
  `log_event(reporting_program_name, event_message)`

- The messages get created in:<br>
`./logs/error.log and events.log`

- Here is how the logs will appear:<br>
`2019-11-29 12:25:36 reporting_program_name [ERROR]: your error here`<br>
`2019-11-29 12:25:36 reporting_program_name [EVENT]: your event here`
