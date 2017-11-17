###Meetup Assignment Class 1

## Name, Date, Time and Topic
PowerShell 101, St. Louis PowerShell User Group.
Thursday, November 16, 2017 @ 6:00pm.

From the meetup website:

"Ken Maglio presenting PowerShell 101 - Getting back to the basics.
Going to be looking at the basics in PowerShell in this session.
Assuming you already know how to open up a windows maching
and launch Powershell, know what the ISE is, and how to run commands.

Topics include:

Help System, Finding Commands, Variable Typing,
Arrays, Hashes, Array of Hashes, Pipleine, Switch,
String Manipulation, String Format, Write-Host vs. Write-Output,
Functions, Advanced Functions, Modules, Importing Modules."

## Brief description of prelimanary research	

As I don't know anything about PowerShell-other than hearing
about it in LaunchCode LC101-I'm going to be searching 
on YouTube to figure out how to launch Powershell, figure out what 
the ISE is, and how to run commands, before I head to this meetup.

## Followup:
Windows Powershell is developed by Microsoft for the purposes of 
task automation and configuration management.  It is based on the 
.NET framework, and it includes a command-line shell and scripting
language.  

ISE stands for Integrated Scripting Environment, and it is a 
graphical user interface that allows one to easily create
different scripts w/o having to type all the commands in
the command line.  

Running commands is just as simple as using the command line, 
and the Windows Powershell appears just like the CLI.


## Questions for Meetup
How is Windows PowerShell more powerful than the command prompt?
Why is it intended to replace the command prompt?

###Basics

##Get-Help
get-help <command>
-examples
-detailed
-full
-online

get-help | more
get-help | less

same as using 'man', for the most part

##Get-Command
get-command <command>
-noun
-verb
-showCommandInfo
-parameterName
-Syntax

#Have to do hunting and pecking, but after you find what you are looking for you can explore the command.

Grammar matters: the difference between knowing your shit and knowing you're shit.  

##Verb-Noun

dont't use more dashes - just don't --- okay 
get-verb is your friend!

e.g. get-help, get-command, get-childitem (ls)

#Good habit, small adjustment.
Beginner: no!  Beyond that: YES!!!

It matters a ton, when we develop functiions and modules.
You can build your own help.


##Running Commands
I don't always use CLI, but when I do, I copy and paste the shit out of everything!

Differences from PoSH vs. ISE (pic on phone)

###Top 10 CmdLets
###Types/Typing
###MagDev Favorites

##Top 10
1. Get-Help
2. Set-ExecutionPolicy  (Get-)




## Next Steps for learning about the topic.
https://www.tutorialspoint.com/operating_system/os_services.htm
https://docs.microsoft.com//en-us/powershell
lmgtfy

