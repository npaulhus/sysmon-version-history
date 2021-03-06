# Sysmon-Version-History
An Inofficial Sysmon Version History

## v8.0

Release date: 06.07.2018

Reference: https://twitter.com/markrussinovich/status/1015017015768113152

New Features: 
- Rule tagging

Fixed Bugs:
- command-line truncation report

Known Issues:
- None

## v7.0

Release date: 02.01.2018

Reference: https://twitter.com/markrussinovich/status/948294964378660864

New Features: 
- File version information
- Dump old configuration schema versions

Fixed Bugs: 
- None

Known Issues:
- Some BSOD on Windows 7 x64 upgrades https://twitter.com/Tecko921/status/948588631144452097

## v6.2

Release date: 19.11.2017

Reference: https://www.darkoperator.com/blog/2017/11/24/operational-look-at-sysinternals-sysmon-620-update

New Features: 
- Enhancements in WMI Logging
- Ability to change driver name
- Ability to change service name and service executable name

Fixed Bugs:
- ?

Known Issues:
- None

## v6.1

Release date: 12.09.2017

Reference: https://twitter.com/cyb3rops/status/907690390719004672

New Features: 
- New WMI monitoring event IDs: 19, 20, 21

Fixed Bugs:
- ?

Known Issues:
- Issue with Windows Server 2008 (affects all newer versions of Sysmon) https://social.technet.microsoft.com/Forums/en-US/28325d60-5647-48ec-977b-73608ff2a62a/sysmon-61?forum=windowsinternals

## v6.0

Release date: 17.02.2017

Reference: https://betanews.com/2017/02/17/sysinternals-unveils-sysmon-6-0/

New Features: 
- Named pipe events (ID 17 "Pipe Created" and ID 18 "Pipe Connected")
- Configuration changes logged as separate event
- Dump Sysmons configuration scheme (-s)

Fixed Bugs:
- ?

Known Issues:
- Issue with Windows Server 2008 (affects all newer versions of Sysmon) https://social.technet.microsoft.com/Forums/en-US/28325d60-5647-48ec-977b-73608ff2a62a/sysmon-61?forum=windowsinternals
