Mail Data Xchange Service
#########################

The Mail Data Xchange Service is a simple service that provides customers
to share files with each other only by using mail.

How does it work? 
#################

Suppose that you want to send an attachment to a person, but the mail server
just blocks the mail, or even worse passes the email, but stips all atachments.

In that case you need to look for alternatives for sending that file.

And here comes the Mail Data Xchange Service! :)

The Mail Data Xchange Service is supposed to work on a mail server, where
it receives it's mails.

What is basically does afterwords is to process the incoming mail, get it's 
attachments and then upload them to a FTP server, so that the customers
may download the files afterwords.

This basically works as a workaround, because you bypass the customer's email
server and thus provide access to the file on a FTP server, where he/she can 
access and get the files.

The Mail Data Xchange Service is configurable, thus allowing you to have as many
as you want services for other customers, call "providers".

I know that this simple README does not explain a lot, but in case you want
to find out more about it just drop me a line at daemon _AT_ unix-heaven _DOT_ org :)

Requirements
############

    - procmailrc
    - lftp
    - formail
    - mpack
    - a mail server :)

More info
#########

Sorry, no time to write any decent documentation about it.

If you are intrested about it, just contact me at daemon _AT_ unix-heaven _DOT_ org

