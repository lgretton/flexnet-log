# flexnet-log

*flexnet-log* is a FlexNET log sanitiser.

FlexNET logs are in a particularly useless format for ease of analysis. flexnet-log takes a 
FlexNET log file as its input and outputs sanitised log entries in a format that can be 
analysed a lot more easily.

Use `flexnet-log --man` to read the program's documentation.

## DEPENDENCIES

* Perl 5.010
* Date::Manip
* File::Slurp
* Getopt::Long
* Pod::Usage
* Time::localtime

## AUTHOR

Liam Gretton <liam.gretton@gmail.com>

https://github.com/lgretton/flexnet-log
