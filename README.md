# PHP helper-applications list
### This repository collects some console applications which can be used to help to automate some issues or tasks

#### clean
This application can be used to clean files, which are older than N days

##### Usage:

```php clean /path/to/files 2 1000```

First argument is path to directory to be cleaned

Second argument is number of days during file hasn't been modified and should be removed

Third argument is number of files which application removes per second

#### findspam
This application can be used to find repeated email addresses in a log file.

##### Usage:

```php findspam /path/to/file 1000```

First argument is path to a log file

The second argument is the number of emails that will generate a warning if exceeded.