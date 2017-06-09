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
![C:\Users\Administrator\Desktop\SOP/image/recover.png](C:\Users\Administrator\Desktop\SOP/image/recover.png)

## 2. Enable administrator account.
* **Start → all programs → Accessories → Command Prompt → run as administrator**
![C:\Users\Administrator\Desktop\SOP/image/command.png](C:\Users\Administrator\Desktop\SOP/image/command.png)

* **net user administrator /active:yes**
![C:\Users\Administrator\Desktop\SOP/image/comm.png](C:\Users\Administrator\Desktop\SOP/image/comm.png)

## 3. Login off then login to administrator and remove test account.
* **Start → control panel → Add or remove user accounts.**
![C:\Users\Administrator\Desktop\SOP/image/user.png](C:\Users\Administrator\Desktop\SOP/image/user.png)

* **Select test account.**
![C:\Users\Administrator\Desktop\SOP/image/user2.png](C:\Users\Administrator\Desktop\SOPimage//user2.png)

* **Delete the account → Delete Files → Delete Accounts.**
![C:\Users\Administrator\Desktop\SOP/image/user3.png](C:\Users\Administrator\Desktop\SOP/image/user3.png)
![C:\Users\Administrator\Desktop\SOP/image/user4.png](C:\Users\Administrator\Desktop\SOP/image/user4.png)
![C:\Users\Administrator\Desktop\SOP/image/user5.png](C:\Users\Administrator\Desktop\SOP/image/user5.png)

## 4. Install device driver. (Chipset, Graphic, Network, Audio, Others……)
![C:\Users\Administrator\Desktop\SOP/image/install.png](C:\Users\Administrator\Desktop\SOP/image/install.png)

## 5. Check Device Manager.
* **My computer → Manager → Device manager**
![C:\Users\Administrator\Desktop\SOP/image/check.png](C:\Users\Administrator\Desktop\SOP/image/check.png)

## 6. Reboot then back up OS. (ex.Ghost)
## 7. Use System Preparation Tool. (sysprep.exe)
* **open Recovery CD → run Sysprep_wes7_20170525.exe**
![C:\Users\Administrator\Desktop\SOP/sysprep1.png](C:\Users\Administrator\Desktop\SOP/image/sysprep1.png)

* **choose OS**
![C:\Users\Administrator\Desktop\SOP/image/sysprep2.png](C:\Users\Administrator\Desktop\SOP/image/sysprep2.png)

* **OS shutdown**
![C:\Users\Administrator\Desktop\SOP/image/sysprep3.png](C:\Users\Administrator\Desktop\SOP/image/sysprep3.png)


