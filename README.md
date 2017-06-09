# Recovery CD user guide for WES7P
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
![image/recover.png](image/recover.png)

## 2. Enable administrator account.
* **Start → all programs → Accessories → Command Prompt → run as administrator**
![image/command.png](image/command.png)

* **net user administrator /active:yes**
![image/comm.png](image/comm.png)

## 3. Login off then login to administrator and remove test account.
* **Start → control panel → Add or remove user accounts.**
![image/user.png](image/user.png)

* **Select test(user) account to delete .**
![image/user2.png](image/user2.png)

* **Delete the account → Delete Files → Delete Accounts.**
![image/user3.png](image/user3.png)
![image/user4.png](image/user4.png)
![image/user5.png](image/user5.png)

## 4. Install device driver. (Chipset, Graphic, Network, Audio, Others……)
![image/install.png](image/install.png)

## 5. Check Device Manager.
* **My computer → Manager → Device manager**
![image/check.png](image/check.png)

## 6. Reboot then back up OS. (ex.Ghost)
## 7. Use System Preparation Tool. (sysprep.exe)
* **open Recovery CD → run Sysprep_wes7_20170525.exe**
![image/sysprep1.png](image/sysprep1.png)

* **Select the current environment**
![image/sysprep2.png](image/sysprep2.png)

* **Computer system shutdown**
![image/sysprep3.png](image/sysprep3.png)


