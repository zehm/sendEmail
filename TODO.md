## v1.56 Release
- [.] Update help message in README (version number at least)
- [x] Fixed base64 encoding issues for authentication
- [x] Detect <!DOCTYPE> in first line as html too
- [x] Command line option to force sending as html (or another content-type)
- [x] Add help message about sending to / from a gmail account
- [ ] Brazilian Portuguese Help for SendMail. Nogueira

## Reported Bugs
- [ ] But it seems that I can't send more than 16 or 17 KB from the STDIN on Windows (2003) with the EXE version.
      Even with -o message-file=... and got the same 17 KB message limitation.

## Feature Ideas
- [ ] A preferences file with default settings?
- [ ] Deliver directly to MX server for domain?
- [ ] Command line option requesting read-receipt
      X-Confirm-Reading-To:
      Disposition-Notification-To: <user@domain.com>
      Return-Receipt-To:
- [ ] Add support for CRAM-MD5 authentication
- [ ] Add a pair of options to add receipt on delivery and on read of sent emails
- [ ] Support for unicode (european) characters in the subject

## More Ideas
- [ ] What about an option to send the same message more than once?
- [ ] How about a delay before sending the message?
- [ ] What about an internal queue for messages that wern't sent?
      Next time it's invoked it could deliver those messages as well.
- [ ] Convert inline documentation to standard perldoc format?
- [ ] Support for pop before smtp?

## Crazy Ideas (not so sure about)
- [ ] Preferences registry settings for the Windows .exe version?
      (several people have said No! use a flat file)
    
