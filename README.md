# SwiftSqliteLocator
Bash script used to locate the sqlite file of the last installed app. 

Should one wish to automatically open the file with a program(I'm using [Datum Free]), replace the last line
```sh
$ open .
```
with
```sh
$ open *.sqlite -a "Datum Free".
```
[Datum Free]: <https://itunes.apple.com/us/app/datum-free/id901631046?mt=12>
