# Python error/event logger:
Easy to use commands to log errors and events in a ./logs dirctory:<br>
<i>log_error(<b>reporting_program_name</b>, <b>error_message</b>)<br>
log_event(<b>reporting_program_name</b>, <b>event_message</b>)</i><br>

<hr>

## Usage and examples:
Place this file in the directory of your python code and<br>
in the code import the module by:<br>
  <i>import loggers</i><br>
<br>
Define the reporting_program_name at the beggining of your program,<br>
when you have to log and error or an event, set the message you want to report in<br>
  <i>error_message = "your error here" or event_message = "your event here"</i><br>
<br>
and use the loggers as follows:<br>
  <i>log_error(reporting_program_name, error_message)<br>
  log_event(reporting_program_name, event_message)</i><br>
<br>
The messages get created in:<br>
<i>./logs/error.log and events.log</i><br>
<br>
Here is how the logs will appear:<br>
<i>2019-11-29 12:25:36 reporting_program_name [ERROR]: your error here<br>
2019-11-29 12:25:36 reporting_program_name [EVENT]: your event here</i><br>
