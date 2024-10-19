# File Extension Changer

It's as simple as it sounds. Takes some arguments and an optional parameter and does it's magic on your files, possibly recursively.

## Usage

The script(s) take 3 arguments with an optional parameter. They are:

**Arguments**:
1. Directory to which the operation will be performed upon
2. Current file extension
3. New file extensions

**Parameter**
Providing the parameter of `-r` will cause the script to perform the operation recurively into subdirectories. Use with caution.

## Examples

### PowerShell

Without recursion:
`.\Set-NewFileExtension.ps1 "C:\YourDirectory" ".zip" ".dosz"`

With recursion:
`.\Set-NewFileExtension.ps1 "C:\YourDirectory" ".zip" ".dosz" -r`

### Bash

Without recursion:
`./rename_file_extension.sh /path/to/directory .zip .dosz`

With recursion:
`./rename_file_extension.sh -r /path/to/directory .zip .dosz`

##
