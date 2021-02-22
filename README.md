# BlueSof - A BLE Keyboard Inspired By Sofle


Flash bootloader
From nrfmicro firmware folder
$ nrfjprog --recover --log
$ nrfjprog -f nrf52 --program firmware/bootloader/pca10056_bootloader-0.2.11_s140_6.1.1.hex --sectorerase

------------------------------------
## Modifications from original Discipline 

- Add numpad on right.
- Move arrow keys 0.25U down and right, similar to 1800 layout. 
- Adjust component layout on top of board, moving ATMega and buttons to the right, adding in more diodes in center. 
- Removed ~, Delete, Page Up, Page Down keys. These will be on alternate layer. 
- Created Digikey version of BOM, found here: https://octopart.com/bom-tool/AgAHKWUi


## ToDo 
- Adjust acrylic foot design to be wider, it looks a little thin. 
- add Via support
- Next order of PCBs: 
	- Adjust #DISCIPLINE logo in space bar area so that it doesn't overlap stablaizer. [Image](./images/knownIssues/Logoplacement.jpg)
	- Omit job number silk screen from vendor.[Plate](./images/knownIssues/plate.jpg) [Main](./images/knownIssues/jobNumMain.jpg) [Bottom](./images/knownIssues/jobNumBottom.jpg) 
	- Improve surface finish on black solder mask, some dark spots. [Image](./images/knownIssues/surfaceFinish.jpg) 
	- Remove drills from FR4 switch plate. [Image](./images/knownIssues/plate.jpg)


## Images

#### Prototype Build
![](./images/SampleBuild/top.jpg)
![](./images/SampleBuild/threequarter.jpg)
![](./images/SampleBuild/side.jpg)
![](./images/SampleBuild/bottom.jpg)
![](./images/SampleBuild/MainPCBs.jpg)
![](./images/SampleBuild/PopulatedBoard.jpg)
![](./images/SampleBuild/PopulatedBoardWithSwitches.jpg)



#### Layout
![](./images/NumDiscipline-layout.jpg)

#### Main PCB
![](./images/NumDiscipline-pcb-front.png)

![](./images/NumDiscipline-pcb-back.png)

![](./images/NumDiscipline-layers.png)

#### FR4 Plate
![](./images/NumDiscipline-plate-front.png)

#### Bottom PCB
![](./images/NumDiscipline-bottom-front.png)

![](./images/NumDiscipline-bottom-back.png)


