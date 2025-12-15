# grep
- stands for Global Regular Expression Print
- used to search text for patterns
- usage:
    - `grep "hello" notes.txt` : Search inside a file
    - `grep "TODO" *.py` : Search multiple files
    - `grep -i "warning" app.log` : Case-insensitive
    - `grep -n "main" program.c` : Show line numbers
    - `grep -c "success" results.txt` : Count matches
    - `grep -r "password" /etc` : Search through directories and subdirectories:
    - `grep "^ERROR" logfile.txt` : Lines that start with ERROR
    - `grep "done$" logfile.txt` : Lines that end with done
    - `grep "user[0-9]" users.txt` : Matches user1, user2, etc.
    - `grep -E "cat|dog" animals.txt` : finds line that contains cat or dog
    - `grep -v "DEBUG" app.log` : Show lines that do NOT match:

- Variants of grep
    - `grep` - basic regex
    - `egrep` - (or grep -E) - extended regex
    - `fgrep` - (or grep -F) - fixed strings (faster, no regex)

![example of grep](./screenshots/grep-1.png)