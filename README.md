# Sync-Calendar-Flow

This **Power Automate flow** helps to synchronize meetings across two accounts (one-way sync).

When a meeting is added to the Source Outlook Calendar, flow creates a copy of this meeting in the Target Outlook Calendar.

Then send a Teams message to Target account. User can accept, decline or ignore the meeting directly from the Team message. If accepted or declined, flow sends a reply to the original meeting organizer if required.

Flow updates and deletes meetings to keep the Target Calendar up to date.

## Installation

1.  Download the included Zip file.
2.  Go to make.powerapps.com 
3.  Click on the Solutions tab
4.  Select the "Import Solution" button
5.  Run through the set up: _Source_ must be the account to sync with the _Target_ account.
6.  Your solution is ready to use!
