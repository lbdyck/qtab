# QTAB

Function: Query Active ISPF Open Tables

Syntax: TSO %QTAB

Or place into the ISPF command table thus:

```
Verb: QTAB
Trunc: 0
Action: Select CMD(%QTAB)
Description: Display All Open ISPF Tables
```

# Valid Commands
```
  Find xxx       to find a table with xxx
  REFresh        to refresh the table of open tables
```

# Valid Table Selections
```
  C               Close the table using TBEND
                  - will not close the current QTAB table
                  - may fail if the table isn't open in the
                    current logical screen
  non-blank       Display selected table structure and contents
```
