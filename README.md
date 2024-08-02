# Pipe-Commands

For this Assignment you are going to find and run 20 unique Cmdlets, then Pipe those Cmdlets to the Format-List Cmdlet, and then re pipe them to another Cmdlet that changes a value. It is recommended that you watch the lecture on the Pipe Commands  to see how to pipe Cmdlets in your Windows Powershell runtime environment.

In your Windows VM:

Start Powershell and run the cmdlet [Start-transcript]
Run your chosen Cmdlet
Pipe that Cmdlet to the Cmdlet [Format-List] or fl
Re Run your chosen Cmdlet piped to another Cmdlet that changes a value
Repeat for all 20 unique Cmdlets
Run the cmdlet [Stop-transcript]
Go to file location where the .txt is stored
Rename the file to "FirstName-LastName-Assignment6c.txt"
Upload file to this Assignment section before the Deadline
I have linked to Microsoft documentation on how Start-Transcript and Stop-Transcript work below:

Start-Transcript
Link: https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.host/start-transcript?view=powershell-7 (Links to an external site.)

Stop-Transcript
Link: https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.host/stop-transcript?view=powershell-7 (Links to an external site.)

Note: Unless you specify where the file is stored, [Start-Transcript] stores the transcripts in the $Home\My Documents directory as \PowerShell_transcript.<time-stamp>.txt files.
