# CNLab-Final-Project

Final project of CNLab course. (40% of the term score)

Computer Networking Laboratory, NTU CSIE.

## Topic

Web-based Monitoring Service

## Important Dates

|Date and Time|Description|
|:------------|:----------|
|5/20 15:20-15:40|Project Proposal Presentation|



## Requirements (goals)

- [x] Construct two normal VMs, say VM1 and VM2.
- [ ] Build a web server on another (the 3rd) VM to display all process info of VM1 and VM2.
- [ ] Users can kill processes of VM1 and VM2 through the admin page of web server.
- [ ] Zombie processes should be killed automatically and display what have been killed on the webpage.

## Useful Links

* [Setup SSH in Linux system](http://docs.oracle.com/cd/E18930_01/html/821-2426/gksja.html#gksrd)
* [Python SSH tools](https://wiki.python.org/moin/SecureShell)
* [Chilkat](https://www.chilkatsoft.com/python.asp)

## Workload Distribution

|Done?|Job|Who?|Description|
|:---:|:--|:---|:----------|
|***YES***|Env setup|Steven|setup VMs, install packages, activate services|
|***NO***|SSH tunnel|Steven|establish ssh connection|
|***NO***|PHP code|S&Ben|render webpages based on templates|
|***NO***|Router monitoring|Everybody|control the flow of router|
|***NO***|JS|Steven|perhaps for some useful function implementations|
|***NO***|HTML templates|Brian|provide all webpage templates|
|***NO***|HTML templates|GDog|provide all webpage templates|
|***NO***|CSS styling|B&G|CSS styling for webpages|
|***NO***|Process Killing|Hank|especially deal with zombies|
|***NO***|Portability|Hank|unix-like system first, and ...|
|***NO***|Debugging|Adam|maintenance issues including debugging|

## Milestones

### Milestone #1

- [ ] Successfully fetch process information.
- [ ] Finish the webpage prototypes for displaying process information.

### Milestone #2

- [ ] Finish the webpage prototypes for administration use.
- [ ] Users are able to kill processes through web GUI.
- [ ] Users are able to add/delete/edit machines that are monitored through web GUI.
- [ ] Automatically kill zombie processes. (tentative)

### Milestone #3

- [ ] Extra Functionality (e.g., CPU usage, Memory usage, Disk usage, etc.)
- [ ] Complete Web GUI.
- [ ] Portability: Linux(must-have), Mac OS X(better-have), Windows(might-have).


