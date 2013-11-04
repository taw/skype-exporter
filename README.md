skype-exporter
==============

Export your data from Skype (logs, contact lists etc.)

main.db tables
==============

Basic functionality working:

* Accounts
* Contacts

These are empty for me, but very naive converters added:

* Alerts
* LegacyMessages
* SMSes
* VideoMessages

Metadata only, can be ignored:

* DbMeta

Basic converters only, merge them into per-conversation log:

* CallMembers
* Calls
* ChatMembers
* Chats
* ContactGroups
* Conversations
* Participants
* Transfers
* Videos
* Voicemails

Properly converted:

* Messages
