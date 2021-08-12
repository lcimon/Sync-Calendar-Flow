# Sync-Calendar-Flow

This **Power Automate flow** helps to synchronize meetings across two accounts (one-way sync).

When a meeting is added to the Source Outlook Calendar, flow creates a copy of this meeting in the Target Outlook Calendar.

Then send a Teams message to Target account. User can accept, decline or ignore the meeting directly from the Team message. If accepted or declined, flow sends a reply to the original meeting organizer if required.

Flow updates and deletes meetings to keep the Target Calendar up to date.

![image](https://user-images.githubusercontent.com/22662809/128931960-d9435bff-84ba-4c63-a436-2109d2d3f81f.png)

## Installation

1.  Download the included Zip file.
2.  Go to make.powerapps.com 
3.  Click on the Solutions tab
4.  Select the "Import Solution" button
5.  Run through the set up _(refer to [Configuration](#configuration))_
6.  Your solution is ready to use!

## Configuration

| Name | Type | Description |
|---|---|---|
| Office 365 Outlook Source | Connection Reference | Outlook account who received meeting to be synchronized |
| Office 365 Outlook Target | Connection Reference | Outlook account where meetings are copied |
| SyncCalendar-SourceEmail  | Environment Variable | Email of _Source_ account |
| SyncCalendar-TargetEmail  | Environment Variable | Email of _Target_ account |
| SyncCalendar-Prefix       | Environment Variable | Prefix to add in the copied Title meeting |