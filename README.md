This is a report for project called Automating Email Sending.
Lines 1-8 are imports of required libraries.
Lines 10-13 we are creating a logger, setting its level to info to catch all the exceptions.
Lines 14-17 creating a log file and a file handler for the logger.
Lines 18-21 setting up the formatter.
Line 24 start of send_emails function.
Lines 25-29 creating a list of recipients and connecting to an outlook server.
Lines 30-32 Trying to log in to our email made for this project.If it fails, writes to our log file on lines 60-61
Lines 34-55 is a for loop sending one email each iteration,
creating a message(using MIMEMultipart), adding an attachment and encoding it to ASCII and writing to a log file.
Lines 53-56 attaching the attachment to our email and sending it.
Lines 58-60 if something went wrong writing it to a log file.
Line 65 closing the connection.
Lines 69-74 scheduling to a certain time and using a while loop to check whether a scheduled task is pending to run or not.

