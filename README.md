#Recovery CD user guide for WES7P
## 1. Recover system.
* **Touch Screen Calibration** : click five point Calibration
* **Recover OS** : install OS
* **Restart** : restart system
* **Command** : Partition the disk 
	*	diskpart
	*	list disk (check disk number)
	*	select disk x
	*	clean (erase all partition)
	*	cre part pri (create new primary patition)
	*	active (Set to bootable)
	*	assign (Assigns a drive letter)
	*	format quick fs=ntfs
	*	exit
![C:\Users\Administrator\Desktop\SOP/recover.png](C:\Users\Administrator\Desktop\SOP/recover.png)

## 2. Enable administrator account.
* **Start → all programs → Accessories → Command Prompt → run as administrator**
![C:\Users\Administrator\Desktop\SOP/command.png](C:\Users\Administrator\Desktop\SOP/command.png)

* **net user administrator /active:yes**
![C:\Users\Administrator\Desktop\SOP/comm.png](C:\Users\Administrator\Desktop\SOP/comm.png)

## 3. Login off then login to administrator and remove test account.
* **Start → control panel → Add or remove user accounts.**
![C:\Users\Administrator\Desktop\SOP/user.png](C:\Users\Administrator\Desktop\SOP/user.png)

* **Select test account.**
![C:\Users\Administrator\Desktop\SOP/user2.png](C:\Users\Administrator\Desktop\SOP/user2.png)

* **Delete the account → Delete Files → Delete Accounts.**
![C:\Users\Administrator\Desktop\SOP/user3.png](C:\Users\Administrator\Desktop\SOP/user3.png)
![C:\Users\Administrator\Desktop\SOP/user4.png](C:\Users\Administrator\Desktop\SOP/user4.png)
![C:\Users\Administrator\Desktop\SOP/user5.png](C:\Users\Administrator\Desktop\SOP/user5.png)

## 4. Install device driver. (Chipset, Graphic, Network, Audio, Others……)
![C:\Users\Administrator\Desktop\SOP/install.png](C:\Users\Administrator\Desktop\SOP/install.png)

## 5. Check Device Manager.
* **My computer → Manager → Device manager**
![C:\Users\Administrator\Desktop\SOP/check.png](C:\Users\Administrator\Desktop\SOP/check.png)

## 6. Reboot then back up OS. (ex.Ghost)
## 7. Use System Preparation Tool. (sysprep.exe)
* **open Recovery CD → run Sysprep_wes7_20170525.exe**
![C:\Users\Administrator\Desktop\SOP/sysprep1.png](C:\Users\Administrator\Desktop\SOP/sysprep1.png)

* **choose OS**
![C:\Users\Administrator\Desktop\SOP/sysprep2.png](C:\Users\Administrator\Desktop\SOP/sysprep2.png)

* **OS shutdown**
![C:\Users\Administrator\Desktop\SOP/sysprep3.png](C:\Users\Administrator\Desktop\SOP/sysprep3.png)


