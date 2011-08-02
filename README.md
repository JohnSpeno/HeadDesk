Head Desk
=========

This is my exploration day project. It's a proposal for a different model of
support that should be applicable to any and all of our services.

Requirements
------------

1. a modern, usable web based help desk software package (**not remedy**),
2. a support email account on an IMAP server,
3. one or more support staff members.
4. an out of band communications channel (IM, face2face, drums, etc).

Set Up
------

Setting up the email account requires these steps:

* Create a folder with the name of each staff member in the support email's IMAP account.
* Configure access to the support email account for each staff member.

Setting up the help desk software requires these steps:

* Set up help desk software package such that it collects mail from the support email account.
* Configure help desk software such that it sends mail from the address of the support email account.
* Create accounts for each support staff member in the help desk software.
* Have each staff member customize their account such that notes sent from the
help desk system include their name in the "signature" or in the From address
(the actual from address should be left as the support account's address).

And don't forget to set up the OOB communictions medium for all support staff.

Usage
-----

When a staff member is on duty, they activate their access to the support email
inbox in their IMAP client. Messages in the account's inbox are processed
oldest first. For each message processed, the staff member takes the
appropriate actions required for support. Any communication required to provide
support are created and sent directly from the help desk software itself. As
each mail message is processed, the staff member moves the mail from the IMAP
inbox to the folder which has their name in the IMAP account.

Messages sent from the help desk software include an identifier in the subject
line of the message. When customers reply to messages from the help desk
software, those messages are received in the support email account with the
identifier in the subject line. The help desk software will consolidate all
messages for each identifier together such that the entire correspondence is
kept together.

Any work that is performed by support staff that isn't explicity communicated
to the customer from the request should be recorded in the request page it
relates to. In this way, other staff members are aware of exactly what has
happened in case they are called in for help.

If mail arrives in the inbox and it does not contain the request identifier in
its subject, then it should be forwarded to the existing request.

Assignment
----------

If a support request needs to be handled by someone other than the current
support person, then the request should be assigned to that other person in the
help desk software. This should generate a mail to the assigned staff member
alerting them of the request.

Multiple Staff Members
----------------------

In order for multiple support staff members to be processing the inbox, then
need to establish a protocol of who is handling which messages. This should be
worked out using the OOB communications medium.

