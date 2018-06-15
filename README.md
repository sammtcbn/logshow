# logshow
This repository aims to grep for specific time period in a syslog file.

### Usage
./logshow [logfile] [start date] [start time] [end date] [end time]

### Example 1
./logshow /var/log/syslog 20180615 10:01:02 20180615 12:03:04

### Example 2 - dump result to a file
./logshow /var/log/syslog 20180615 10:01:02 20180615 12:03:04 > mylog
