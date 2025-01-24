## Lab 01

- Name: Haeden Stein
- Email: stein.51@wright.edu

## Part 1 - GitHub Profile

1. [0HStein0](https://github.com/0HStein0)

## Part 2 - Research

|   Windows     | Linux / Mac |                                Action                               |
| ---           | ---         | ---                                                                 |
| help          | man         |shows a list of commands or detailed help info of a specific command.|
| Get-Location  | pwd         |gets information about the current location or location stack        |
| Get-ChildItem | ls          |lists child items in a directory                                     |
| mkdir         | mkdir       |makes a new directory                                                |
| Set-Location  | cd          |Sets the current working location to a specified location            |
| New-Item      | touch       |creates a new item and allows you to set its new value               |
| Move-Item     | mv          |Moves an item from one location to another                           |
| Copy-Item     | cp          |Copys an item                                                        |
| Remove-Item   | rm          |removes an item                                                      |
| notepad.exe   | vim         |opens notepad                                                        |

## Part 3 - Command Line Navigation

My OS is:
- [x] Windows
- [] Linux
- [] Mac

My Command Line Shell is: Powershell

1. Create a directory named `DirA`: 'mkdir DirA'
2. Create a directory named `Dir B`: 'mkdir DirA'
3. Go into `DirA`: cd DirA
4. Go into `Dir B` from `DirA`: 'cd ../"Dir B"'
5. Return to your user's home directory: 'cd ../'
6. Create a file named `test.txt`: 'New-Item test.txt'
7. Move the file named `test.txt` into `DirA`: 'Move-Item -Path "C:\Users\haede\test.txt" -Destination "C:\Users\haede\DirA"
8. Contents of `test.txt`:'notepad.exe'
```
You are not a pesky bugger
```
9. Make a copy of `test.txt` named `copy.txt` in `DirA`:
10. View the contents of `DirA`: 
11. Make a copy of `test.txt` in `Dir B` named `fodder.txt`:
12. Delete / remove both `fodder.txt` AND `Dir B`:


## Citations

(https://learn.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Management/)
Helped me find out what actions the first three commands performed.


