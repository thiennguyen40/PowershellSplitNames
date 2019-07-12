# PowershellSplitNames
Powershell function to split Distinguished Name into Name and Domain 

Requires variable to be RegEx'ed
  $regName = [RegEx]::Escape($VARIABLE)

Change $Name -replace"@\\{DistinguishedName=CN=" if necessary 
