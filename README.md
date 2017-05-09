# psyrfirstdaypowershell
## 3.Diving into PowerShell
```
$psversiontable
```

## 4. PowerShell Help
```
update-help
```

### 3 Using Help in the PowerShell ISE
put cursor in a command. press F1 to get help.

### 4 Using the About Help Topics
```
help about*
```
```
help about_testdrive -showwindow
```


## 5. Getting Started with PowerShell
### 1 Learning How to Run PowerShell Commands
```
help *eventlog*
```

```
help get-eventlog -Parameter logname
```
example
```
get-eventlog system -newest 5
```
corresponding help
```
help get-eventlog -Parameter newest
```


### 4 Learning How to Use Aliases
```
Get-Alias -Definition get-childitem
get-alias dir
```

### 5 Learning How to Use Show-command
```
show-command get-eventlog
```
