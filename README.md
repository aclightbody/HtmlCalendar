# HtmlCalendar
Generates a html file and web page for the desired Gregorian calendar year

1. Download the CalendarModules folder and put it in a local directory that is on the Python path (make sure the folder name is not changed).
2. Open Command line shell (e.g. Command Prompt, Powershell, etc)
3. Run Python from shell. For example type in: py
4. Import the main module: from CalendarModules.CalendarMain import CalMain
5. Run the command for a specific year with the html file name of your choice: CalMain('2000','2000Calendar')
6. An .html file will have been generated into the CalendarModules folder and a web page should have been generated
7. To understand the main module inputs (output below): help(CalMain)

Help on function CalMain in module CalendarModules.CalendarMain:

CalMain(year='2000', filename='Calendar')
    Creates html file and web page containing Gregirian calendar for specified
    year and for the year before and after the specified year. Example input: CalMain('2000', 'Year 2000 Calendar').

    year (string):  integer year above 1583.

    filename (string): name of output html file.

    returns: html file in current directory and opens web page.
