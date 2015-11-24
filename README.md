# Sqlite3-Monitor
A command-line tool to view sqlite3 databases remotely.


Prereqs:

1. From the Android SDK: adb, sqlite3


To Use:

1. Set the custom paths in the dumpdbs file.

2. Set the dumpdbs file executable.

2. Create a txt file with the same name as your database. This file will contain the sqlite3 commands you want to run.


Extra:

Use a tool like 'watch' to keep a real-time display of your database script. For example,

watch -n 1 ./dumpds
