# Enter your MS Teams information

* In **Message**, enter the message to send to the channel. You can also select expressions from the dropdown.
* In **Team ID**, enter or select a team from the dropdown list.
* In **Channel ID**, enter or select a channel from the dropdown list.
* Click **Save and Continue**.

Advanced Settings:

* In **Existing Message ID (if reply),** enter the ID of the message for which to post a reply.
* In **Number of Retries**, enter the number of attempts the Snap makes to perform the selected operation in case of connection failure/unsuccessful attempts.
* In **Retry Interval (seconds)**, enter the time interval in seconds between retry attempts.
* In **Snap Execution**, select one of the three modes in which the Snap executes:
  * _Validate & Execute._ Performs limited execution of the Snap and generates a data preview during Pipeline validation, then performs full execution of the Snap (unlimited records) during Pipeline runtime.
  * _Execute only._ Performs full execution of the Snap during Pipeline execution without generating preview data.
  * _Disabled._ Disables the Snap and all Snaps downstream from it.
