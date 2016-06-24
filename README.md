# Nepal LoadShedding Schedule[WIP]
 
 This is a dirty script written in free time. This script just extract the schedule from the other sites and prints the result in a desirable format. You can pipe the info to conky, dzen2, yabar or dunst. 
Choose your own color for any table elements.

 There's a lot of cleanup needed in this script.


 ![loadshedding](https://cloud.githubusercontent.com/assets/12681896/16272923/474a1ab0-38bf-11e6-9729-c8f46f0d194d.png)
  

When used with the lemonbar and as conky:

![imgur-2016_06_23-16 02 09](https://cloud.githubusercontent.com/assets/12681896/16300200/65d81cee-395e-11e6-90cf-5e24d2ec7270.png)


## How to install: 

1. Clone the repo or download the zip
    `git clone https://github.com/blacpythoz/Nepal-Loadshedding-Schedule.git`
    OR
		`wget https://codeload.github.com/blacpythoz/Nepal-Loadshedding-Schedule/zip/master`

2. Change the directory
		`cd Nepal-Loadshedding-Schedule/`
 
3. Make the script executable
    `chmod +x load`

4. Run the program
    `./load`


## Manual

    usage: load [OPTIONS] [GROUP_NO]

    Info:
    -a [default]        Show all schedule 
    -g [group [1-7]]    Select the groups
    -t [group no]       Show the today schedule
    -C [true/fase]      Toogle the color options
    -h [topics]         Print this text and exit
    -G [Color codes]    Sets the color of the side bar text 
    -d [Color codes]    Sets the foreground color of day text
    -D [Color codes]    Sets the background color of days
    -B [Color codes]    Sets the background color of tables
    -F [Color codes]    Sets the foreground color of tables
    -S [Color codes]    Sets the Selected foreground color of tables
    -U [Color codes]    Sets the underline in the tables data

[COLOR CODES]
      natural = natural
black = 0            red    = 1
green = 2            yellow = 3
blue  = 4            magenta= 5
cyan  = 6            white  = 7

Examples:

`./load -t 4 -d 1`
