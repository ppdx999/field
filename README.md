This project is work in progress.

# Field

Retrieve data for a specific field.

# Usage

```txt
field <field> [<file>]

FILE:
    The file to retrieve the field from. If not provided, the field is retrieved from the standard input.
```


# Example

```terminal
$ cat data.txt
00001 john@example.com   John_Doe
00002 sherry@example.com Sherry_Berry
00003 ram@example.com    Ram_Singh

$ field 2 data.txt
john@example.com
sherry@example.com
ram@example.com
```
