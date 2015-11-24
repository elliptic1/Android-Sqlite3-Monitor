# Android-Sqlite3-Monitor
A command-line tool to view sqlite3 databases on Android devices. The database is copied locally and then a custom script is run that uses sqlite commands.


Prereqs:

1. From the Android SDK: adb, sqlite3


To Use:

1. Set the custom paths in the 'watchdb' file.

2. Chmod 755 watchdb

3. Create a txt file with the same name as your database. This file will contain the sqlite3 commands you want to run.

4. See example.txt.


Extra:

Use a unix tool like 'watch' to keep a real-time display of your database script. For example,

watch -n 1 ./dumpds com.sample.package MyCoolDatabase

Remember that as currently written, the script will be copied from your device on every call.
