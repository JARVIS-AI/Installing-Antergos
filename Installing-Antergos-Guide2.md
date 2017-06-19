# Antergos Installation on Lenovo Laptop

#### 1. Requirements 

These are needs for correct and fresh installation of antergos or arch linux on laptops.

1. Backup
2. Laptops ***Better supported laptop not those that eat your brain at all***
3. Fast internet, for get packages from repo that are needs for installation. 
4. Time, make your time free for this please not busy and working with other things for preventing other damages and issues.
5. Happy , make your entire feelings happy for getting good things.

Now ready for next sections.

#### 2. Preparing

As the title mentioned this guide is around the installation of Antergos linux on lenovo laptop like : Ideapad - Thinkpad - IBM Thinkpad - Lenovo New and others ...

> For myself I'm installing Antergos on IBM thinkpad T61 and T61p.

1. At First preparing your full **backup** of your files and data to another computer or storage that not using for this new linux os.
2. After the backup going to be ready download the antergos iso from its site.

    > Better download iso from self site , prevents other issues and problems.

3. Make the iso bootable on 4GB or higher **(Its on you)** flash usb not important **USB3** or **USB2** by tools like :
>1. Rufus **Windows**
>2. Bootable mac **MacOS**
>3. dd Command in terminal **Linux**
 
4. So download tools from their site and install and run it.
> In this guide we use **rufus in windows because its recommended**.

After running rufus , load your flash usb **Please be sure that you choosing right usb for preventing other problems like formating your hards or other storages** and choose **GPT Partition for Newer Laptop** and **MBR for bios setup** also **GPT** use for **UEFI** laptops.

By now we are installing antergos on IBM T61 and T61p, so we choose **BOTH** is **GPT and MBR partitions** you can use this option if your not sure.

Now load your ISO image downloaded from site and **make iso** option and **fast format** and click **Format** , yay. :D

Wait until finished work , now you have bootable antergos linux for installing new os.

#### 3. Pre installation 

Now in this section, we entering setup.

1. Connect usb bootable to your computer or laptop.
2. Turn on your laptop and enter bios setup.

    > In lenovo laptops and most laptops and specialy IBM thinkpad the **F2** is for that but other brands laptops is **F12** or **F8**.
Check every function keyboard to enter bios.

3. After entering, disable **fast boot** , disable **Boot lock** if you have , after that make the boot priority to your flash usb or boot from your connected bootable usb.

4. Now welcome to antergos first step, choose one them :

    - **Boot Graphical installation**

    - **Boot CLI installation**

    - **Boot disabled graphic card installation**


    > First is for **most laptops**
    
    > Second is for **geeks**
    
    > Thirds is for laptops that they are **optimus (Intel + Nvidia)** for exp. And new laptops. (Not IBM thinkpad :D)

5. Now right choose you will be in gnome desktop of **Cnchi** installation that made by Antergos team and developers that this tools change hard **CLI** installation of Arch to **GUI** installation and **E2U** (easy to use).