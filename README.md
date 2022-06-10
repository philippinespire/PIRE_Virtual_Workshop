# PIRE_Vitual_Workshop

The purpose of this repository is to instruct biologists in Regular expressions, basic UNIX, how to interface with the Old Dominion University High Performance Computing Cluster, how to execute SLURM commands and how to use Git and GitHub.

The documents in this repository are written in [Markdown](https://www.markdownguide.org/basic-syntax/#links).

All work done is for the [Philippines PIRE Project](https://sites.wp.odu.edu/PIRE/), [On GitHub](https://github.com/philippinespire/Welcome-README), [NSF Award #1743711](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1743711).  This workshop is hosted by Dr. Kent Carpenter of Old Dominion University.

Participation in the workshop is by invitation only.  Please contact your host or mentor with any questions regarding participation.

![](https://github.com/Getterrobog/DipterygonotusBalteatus/blob/main/PPP_logo.png)

***

## Schedule

The workshop will be from Monday to Thursday from 9:00 AM (EDT) to 5:00 PM (EDT):
Day 1 - Computer set up and Regular expressions (Mon)
Day 2 - Intro to UNIX shell (Tue)
Day 3 - Intro to HPC cluster (Wed)
Day 4 - Intro to Git and Github (Thur)

The Schedule for the workshop can be viewed [here](https://docs.google.com/spreadsheets/d/1VwhTJZql1L0DfKxAIalrXDcO3_hNNWzep8dWDNKu4kw/edit?usp=sharing)

All sessions will be delivered via zoom.  Please contact your host or mentor if you did not receive a zoom link.

***

## Materials

We will use the following resources:

[Practical Computing for Biologists \(Haddock and Dunn, 2011\)](https://drive.google.com/drive/folders/1_0ZLpuIhvQ9zdhIs8rdyuszqsdxqJh9H?usp=sharing), also see the [website](https://practicalcomputing.org/)

[Old Dominion University High Performance Computing cluster](https://wiki.hpc.odu.edu/)

[Software Carpentry for the Unix Shell](https://swcarpentry.github.io/shell-novice/)

[Software Carpentry for the Git](https://swcarpentry.github.io/git-novice/)

[Code Refinery for Git](https://coderefinery.github.io/git-intro/)

***

## Workshop Facilitators

[Dr. Dan Barshis, Old Dominion University] (https://sites.wp.odu.edu/barshis-lab/)

Dr. Wirawan Purwanto, Old Dominion University

Dr. Eric Garcia, Old Dominion University

Mr. Ivan R. Lopez, Old Dominion University

***

## Pre workshop instructions

Please let the facilitator know which operating system you use and version prior to the workshop via email.
 
Please install the following software:
 
#### MAC:
- [BBEdit](https://www.barebones.com/products/bbedit/)
- Git -  install Git for Mac by downloading and running the most recent "mavericks" installer from [this list](http://sourceforge.net/projects/git-osx-installer/files/). Because this installer is not signed by the developer, you may have to right click (control click) on the .pkg file, click Open, and click Open on the pop up window. After installing Git, there will not be anything in your /Applications folder, as Git is a command line program.

Please see the [tutorial video](https://youtu.be/9LQhwETCdwY).

#### Windows:
- [Notepad++](https://notepad-plus-plus.org/)
- The Bash Shell – This will provide you with both Git and Bash in the Git Bash program.
	1. Download the Git for Windows [installer](https://gitforwindows.org/).
	2. Run the installer and follow the steps below:
		1. Click on "Next" four times (two times if you've previously installed Git). You don't need to change anything in the Information, location, components, and start menu screens.
		2. From the dropdown menu, "Choosing the default editor used by Git", select "Use the Nano editor by default" (NOTE: you will need to scroll up to find it) and click on "Next".
		3. On the page that says "Adjusting the name of the initial branch in new repositories", ensure that "Let Git decide" is selected. This will ensure the highest level of compatibility for our lessons.
		4. Ensure that "Git from the command line and also from 3rd-party software" is selected and click on "Next". (If you don't do this Git Bash will not work properly, requiring you to remove the Git Bash installation, re-run the installer and to select the "Git from the command line and also from 3rd-party software" option.)
		5. Select "Use bundled OpenSSH".
		6. Ensure that "Use the native Windows Secure Channel Library" is selected and click on "Next".
		7. Ensure that "Checkout Windows-style, commit Unix-style line endings" is selected and click on "Next".
		8. Ensure that "Use Windows' default console window" is selected and click on "Next".
		9. Ensure that "Default (fast-forward or merge) is selected and click "Next"
		10. Ensure that "Git Credential Manager" is selected and click on "Next".
		11. Ensure that "Enable file system caching" is selected and click on "Next".
		12. Click on "Install".
		13. Click on "Finish" or "Next".
	3. If your "HOME" environment variable is not set (or you don't know what this is):
		1. Open command prompt (Open Start Menu then type cmd and press Enter)
		2. Type the following line into the command prompt window exactly as shown:
			setx HOME "%USERPROFILE%"
		3. Press Enter, you should see SUCCESS: Specified value was saved.
		4. Quit command prompt by typing exit then pressing Enter

Please see the [tutorial video](https://youtu.be/339AEqk9c-8).

***

