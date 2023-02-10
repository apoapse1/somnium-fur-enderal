Installation
============
Somnium makes use of the excellent `Wabbajack <https://www.wabbajack.org/#/>`_ program to make installation as fast and painless as possible.

Pre-Installation
^^^^^^^^^^^^^^^^

There are a few things you will need to make sure to have before you can download and play Somnium. First and foremost, you will need at least **190GB** of free space for the Somnium installation on your Solid State Drive (SSD), and at least **64GB** for the Somnium downloads and **20GB** for Enderal SE. You can either store the latter two on the same SSD or on another "Hard Disk Drive" (HDD) but ensure that Somnium itself is installed on an SSD. To see which of your drives are SSD's and which are HDD's, press Win+R and type ``dfrgui``.

You can delete the contents of the ``downloads`` and Enderal SE folders after Somnium is fully installed, however you will need to redownload all the mods and Enderal when you wish to update the list.

If you are having issues with any step of the installation, please join our `Discord Community <https://discord.com/invite/nAQWr4VmG6>`_, where we will be able to diagnose and help you with your problems.

*The following steps are only needed if you are installing Somnium for the first time. If you are updating Somnium, jump straight to:*

:ref:`Updating reference`

Minimum PC Specs
~~~~~~~~~~~~~~~~

Somnium is not particularly performance-heavy, and can run on relatively low-end PC specs. One of our devs has a GTX1660 GPU and a i5-9400F CPU, and can run Somnium at 1440p with the Medium ENB preset on 30-40 FPS in the exterior. Lowering the resolution to 1080p and choosing the Low ENB preset will improve your performance by a lot. There are other methods available to improve performance as well, please join our discord to inquire about details if your game is struggling.

Somnium also natively suppports most resolution aspect ratios, such as 16:10, widescreen (21:9) or ultra-widescreen (32:9).

Installing Microsoft Visual C++
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can download this from `here <https://aka.ms/vs/16/release/vc_redist.x64.exe>`_.

Installing Newest .NET Framework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can grab this package from `here <https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer>`_.

Full-Installation
^^^^^^^^^^^^^^^^^

With the above packages downloaded, we are ready to install Somnium. Installation is simple. Just follow the below instructions, **allowing each to finish before you move on to the next.**

1. Install Enderal Special Edition
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
First, make sure that your Steam Library is not located in the Program Files folder of your PC. If it is, follow `this guide <https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide>`_ to set it in a different place.

Install the Steam Version of `Enderal Forgotten Stories (Special Edition) <https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition/>`_

Make sure that the language is `set to English <https://help.steampowered.com/en/faqs/view/4984-C127-121D-B3F2>`_.

If Enderal was already installed prior to this, `verify its game files <https://help.steampowered.com/en/faqs/view/0C48-FCBD-DA71-93EB>`_.

2. Install Wabbajack
~~~~~~~~~~~~~~~~~~~~
Create a folder in the base of one of your drives named Wabbajack. For example: ``C:\Wabbajack`` is a safe standard. Do **NOT** create that folder on your Desktop, Downloads or the Program Files folder.

Download `Wabbajack.exe <https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe>`_ and place it inside the folder you just created. Run the .exe inside that folder. 

3. Preparing Wabbajack for the installation
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
3.1. Once Wabbajack is opened, click on the gear icon at the top right and login to your **Nexus Account**. **We absolutely recommend you have a premium subscription active for this account while you download Somnium.** Without a premium account, your download will take significantly longer.
 
3.2. Create a folder named ``WJDownloads`` in the base of your HDD. For example, ``D:\WJDownloads``. You can also create it on your SSD, if you aren't worried about the space it'll take up. And if you ever decide to try out other WJ lists, you can use this download folder for all of them.

3.3. Create a folder named ``Somnium`` in the base of your SSD. For example, ``E:\Somnium`` or ``C:\Games\Somnium``. **We absolutely recommend you install Somnium on your Solid State Drive. Otherwise, your performance will be much worse, and the load times will be significantly higher.**

4. Finally Installing Somnium
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
4.1. Download `Somnium.wabbajack <https://github.com/apoapse1/somnium-fur-enderal/releases/latest/download/Somnium.wabbajack>`_ and run it. Set the ``Download Location`` to the same base folder of your drive that you created in step #3.2. Then set the ``Installation Location`` to the same folder of your drive that you created in step #3.3. Check "Overwrite Installation", and start the installation. This will take a while, so let it run.

If Wabbajack threw an error while installing Somnium, we will be able to fix the issue in our `Discord Community <https://discord.com/invite/nAQWr4VmG6>`_.

4.2. When Wabbajack finishes successfully, navigate to the Somnium installation folder. Inside, you should see a file named ``Somnium Launcher.exe``. Run it and a new window will pop up. Select ``Install Somnium``, click Accept and allow the launcher to finish the final steps of Somnium installation.  **IMPORTANT**. During the final installation process, a fullscreen window will appear asking you to choose the appropriate in-game brightness by following a specific set of instructions. **DO NOT** skip this step or back out of it, it is essential for the optimum Somnium experience. 

4.3. Once this process has completed, paths to ``Gameplay Options`` and ``Graphics Options`` will appear that will allow you to further customize aspects of your gameplay experience. 

     4.3.1. Most fields in ``Graphics Options`` will be either auto-completed based on your computer setup or will be set to defaults. Notably, ensure that the          set resolution matches your monitor resolution.  Here you can also change various options including overall ENB quality and view distance, of which lower options are very useful for players with less powerful setups.  
     
     4.3.2. ``Gameplay Options`` allows players to customize specific areas of the game, including allowing for the introduction to be skipped partly or completely, voice audio files all in German (there is very high quality German voice acting in Enderal), an item selection system based on vanilla Enderal and other options.  

4.4. After you have chosen and applied your preferred options you will be returned back to the main menu, where you can click ``Launch Somnium`` and start playing. Please enjoy your time in Vyn! 

.. _Updating reference:

Updating
^^^^^^^^

If Somnium receives an update, please check the Changelog before doing anything. Any time the Changelog recieves an update, you will be able to see whether the latest update is save-compatible. If it is not, you don't have to do anything prior to updating. If it is, back up the ``Somnium\files\profiles\Somnium\saves`` folder by placing it outside of the Somnium folder. For example, you can keep it in ``D:\SomniumSaves``.

**Wabbajack will delete all files that are not part of the updated modlist when updating! That includes the base Somnium folder.**

This means that any additional mods you have installed on top of Somnium will be deleted. However, your downloads folder will not be touched!

Updating is like installing. Download the latest `Somnium.wabbajack <https://github.com/apoapse1/somnium-fur-enderal/releases/latest/download/Somnium.wabbajack>`_, run it, make sure that you select the same installation and download paths as before and tick the *Overwrite installation* button. Once it's done, complete installation via the launcher as described above. If the update was save-compatible, copy your saves folder back to ``Somnium\files\profiles\Somnium\saves``.

Note that some in-game settings and your game configuration in the launcher will get reset when updating. Make sure to check that!

Problems with Wabbajack
~~~~~~~~~~~~~~~~~~~~~~~

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-trying Wabbajack at least once before posting anything, usually it will complete what it missed the first time. Check the ``overwrite`` box on the install page and Wabbajack will continue where it left off, so you lose no progress. If none of the tips here help, join our `Discord Community <https://discord.com/invite/nAQWr4VmG6>`_ and post a Wabbajack log in #somnium-support. You can find those in the logs folder of the folder where you installed Wabbajack.

* 
  **Could not download X.** Sometimes Wabbajack times out while downloading a few mods.  In this case, you can re-run Wabbajack and start the install again.  If this doesn't work, you can also try a VPN to change your download region.  We recommend ProtonVPN as a good free option.  A third option, if you have Nexus Premium, is to change the CDN (download location) within your profile settings on the Nexus website.
  
* 
  **Could not download X.** If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until Somnium is updated.

* 
  **X is not a whitelisted download.** This can happen when I update the modlist. Check if a new update is available and wait if there is none.

* 
  **Wabbajack could not find my game folder.** Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the `Pre-Installation <#pre-installation>`_ step and ensure you have clean and valid installations of both Skyrim and Enderal SE.

* 
  **Windows is reporting that a virus has been detected.** Windows 10 has started to auto-quarantine the ``usvfs_proxy_x86.exe`` file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false positive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found `here <https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan>`_.

* 
  **Cyclic Redundancy Check error during installation** This could be several things, but the first thing we would recommend is confirming that Wabbajack is not installed in your Documents, Downloads or Program Files folders, then delete the contents of ``%APPDATA%/Local/Wabbajack`` and re-open the app and try again. If this does not resolve the problem, it could be related to drive corruption, and you should run CHKDSK on the drive in question.


Personalizing the Game
~~~~~~~~~~~~~~~~~~~~~~

**There is no MCM customization necessary for Somnium**.  The MCM options for all mods are set automatically to Somnium's standard.

If you are interested in adding/removing some mods from Somnium, feel free to join our Discord, and ask in the #somnium-going-rogue channel. We will try to help you with modifying the game as much as we can.




.. _Wabbajack: https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe

.. _Enderal: Forgotten Stories (Special Edition): https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition/

.. _Somnium: https://github.com/apoapse1/somnium-fur-enderal/releases/latest/download/Somnium.wabbajack 
