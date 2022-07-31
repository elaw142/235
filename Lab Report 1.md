# Lab Report 1

## _Important Information_

### General



* Not only building a dynamic website but also learning the correct mindset for coding/working as a team
* Ask lots of questions on Piazza
* All resources for labs are on canvas
* Should come to the designated lab and not another one


### Lab marking



* 1% per lab, 8 in total (attendance not mandatory, just the report)
* Submit the report as a PDF by the end of the week
* Will be checked for plagiarism

## _Notes_

### Software versioning



* Proper versioning conventions are essential for clarity and space
* Each digit in the version number represents different things
    * The first digit is the major release version (no backwards compatibility)
    * The second digit is the minor release version, which adds additional features that are backwards compatible
    * The third digit is for bug fixes (should never break backward compatibility)
* We can know which versions of an app are compatible by looking at the version number
* Packages can have dependencies and minimal version requirements
* Important to keep bugs under control when building apps

### IDEs

* In this course, we chose between PyCharm and VS code

     

### Terminal

* Familiarity with terminal commands can make you a better developer as most servers won't have a graphical user interface

### Virtual Environments

* Virtual isolation of the python version and its installed packages
* Having virtual environments set up for projects allows them to be opened and worked on even if the current versions of different packages are not compatible with the versions at the time as it runs off those prior versions
* PyCharm can do the work for you in making virtual environments for your projects
* Conda is both a package manager and environment manager

### Markdown

* An easy markup language
* Used on Github

### Debugging with IDEs

* Breakpoints halt the program at a certain point
* Step into and over to traverse code

## _Tasks_

### General

* Python was already installed
* Installed Conda
* Already had VS code installed and also installed PyCharm
    * Created my HelloWorld project using venv as shown in the lab
    * Installed a package through the terminal as shown in the lab
    * Generated a requirements.txt file as shown in the lab
* Created my Github account: https://github.com/elaw142

### Code Debugging

1. The probability of winning is only 1/100
1. Yes, by inserting a breakpoint at line 51, you can change the guesses to be the same, resulting in a win every time
1. Yes, by inserting the breakpoint at line 51, you can change the computers guess to our guess (in this case, always 42), resulting in a win every time
