# About
This is my personal powershell script to remove bloat from windows 10

## What does it remove? 
This powershell script removes unnecessary apps that are installed by default and it removes onedrive.

## How do I run this script? 
1) Download the .zip file on the main page of the GitHub and extract the .zip file to your desired location
2) Once extracted, open [PowerShell](https://docs.microsoft.com/en-us/powershell/scripting/overview?view=powershell-5.1) (or [PowerShell ISE](https://docs.microsoft.com/en-us/powershell/scripting/windows-powershell/ise/introducing-the-windows-powershell-ise?view=powershell-7)) as an Administrator
3) Enable PowerShell execution
<code>Set-ExecutionPolicy Unrestricted -Force</code>
4) On the prompt, change to the directory where you extracted the files:
  e.g. - `cd c:\temp`
5) Next, to run either script, enter in the following:
  e.g. - `.\rmbloat.ps1`
  
  Remember this script **NEEDS** to be run as admin in order to function properly.
