# logwatch

## Yet Another Logfile Viewer (YALV), but in full technicolour!

![Screenshot](logwatch.gif)

Highlight keywords in log files in various colours, that are typically used in Log4-configurations (Log4Java, Log4Python, Log4Perl, etc..). The keywords are ERROR, INFO, WARNING, DEBUG, TRACE, SECURITY, FATAL, TODO, TWITTER, and can easily be changed in the script.

## Usage:

`logwatch.sh my_app_logfile.log`

## Installation:

Manually copy `logfile.sh` to `/usr/local/bin`

Optionally create a symlink so that you can just type "logwatch".

`cd /usr/local/bin`

`ln -s logwatch.sh logwatch`

