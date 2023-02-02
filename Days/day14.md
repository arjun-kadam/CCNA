# SMTP (Simple Mail Transfer Protocol)
- Mail Push Protocol
- SMTP --> Send Mail To People
- SMTP is used by the client to send email to server.
- SMTP is an application layer protocol.
- It uses **TCP Port 25**
- A few email services like GMail use unoffical TCP port 465 for SMTP.
- SMTP requires each message in 7-bit ASCII Format.

## SMTP Commands

`HELO & EHLO` : Command that initiate a new protocol session between client and server. The EHLO command request then respond with any optional SMTP extension Support.

`MAIL FROM` : command to initiate sending an email message or to identify server.

`RCPT`: Identify intended recieptant.

`DATA`: command indicating the start of transmission of the email message. The last message is "." as a Termination character to signify the end of mail.

`RSET`: Reset the connection if it encounter an error.

`NOOP`: Empty message like ping to check responsiveness of other end.

`QUIT`: Termination of Protocol Session.

## Working Of SMTP

<img src="Images/SMTP1.png?raw=true" alt="SMTP">


**MTA (Message Transfer Protocol):** Responsible for transfering and routing an email message from the sender's computer to the recieptant computer.

## SMTP Codes and their Meaning

`211` - System Status

`214` - Help

`220` - Service Ready

`221` - Service Closing

`421` - Service not available

`450` - Mailbox Not Available

`451` - Command Aborted

`500` - Syntax Error

`554` - Transaction Failed

This Explainative guide about SMTP. On [Day 15](day15.md) we will se about POP3 and IMAP.