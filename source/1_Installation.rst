Installation
============
Somnium makes use of the excellent `Wabbajack <https://www.wabbajack.org/#/>`_ program to make installation as fast and painless as possible.

Pre-Installation
^^^^^^^^^^^^^^^^

There are a few things you will need to make sure to have before you can download and play Somnium. First and foremost, you will need at least **190GB** of free space. You can delete the contents of the ``downloads`` folder after it is fully installed to reduce this, however you will need to redownload all the mods when you wish to update the list.

*The following steps are only needed if you are installing Somnium for the first time. If you are updating Somnium, jump straight to* :ref:`Updating-reference-lable`

Installing Microsoft Visual C++
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can download this from `here <https://aka.ms/vs/16/release/vc_redist.x64.exe>`_.

Installing Newest .NET Framework
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

You can grab this package from `here <https://dotnet.microsoft.com/en-us/download/dotnet-framework/thank-you/net48-web-installer>`_.

Full-Installation
^^^^^^^^^^^^^^^^^

With the above packages downloaded, we are ready to install somnium. Installation is simple. Just follow the below instructions, **allowing each to finish before you move on to the next.**

#. Install the Steam Version of `Enderal: Forgotten Stories (Special Edition) <https://store.steampowered.com/app/976620/Enderal_Forgotten_Stories_Special_Edition/>`_. 
#. Install `Wabbajack <https://github.com/wabbajack-tools/wabbajack/releases/latest/download/Wabbajack.exe>`_to the base folder of one of your drives. For example: ``C:\Wabbajack`` is a safe standard. It is best installed on the same drive that you have the game installed.
#. Open Wabbajack and login to your **Nexus Account** via the gear icon at the top right. **We absolutely recommend you have a premium subscription active for this account while you download Somnium.** Without a premium account, your download will take significantly longer.
#. Download `Somnium <https://github.com/apoapse1/somnium-fur-enderal/releases/latest/download/Somnium.wabbajack>` and run this. You can set the ``Installation Location`` to the same base folder of your drive that you downloaded Wabbajack to in step #2. The ``Download Location`` should then fill automatically. If it does not, simply point it to a folder called "downloads" that you can make in the ``C:\Somnium`` location.
#. Allow this installation to run. It will take a while.
#. Navigate to this installation and run ``Setup.bat``
#. Follow the instructions from the command window that appears.
#. Run the new ``Launch Somnium`` button that has ben placed in your directory.

And congrats! You've installed Somnium. You can launch the game through the ``Launch Somnium`` exe file. Be sure to check the rest of the docs for information about Somnium's changes and enjoy your time!

.. _Updating-reference_lable:

Updating
^^^^^^^^

If Somnium receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the updated modlist when updating!**

This means that any additional mods you have installed on top of Somnium will be deleted. However, your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the *Overwrite existing modlist* button.
Note that some in-game settings will get reset when updating. Check them all again!

Problems with Wabbajack
"""""""""""""""""""""""

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-trying Wabbajack at least once before posting anything, usually it will complete what it missed the first time. Check the ``overwrite`` box on the install page and Wabbajack will continue where it left off, so you lose no progress.

* 
  **Could not download X.** Sometimes Wabbajack times out while downloading a few mods.  In this case, you can re-run Wabbajack, check the ``Network Workaround`` box in settings and start the install again.  If this doesn't work, you can also try a VPN to change your download region.  We recommend ProtonVPN as a good free option.
  
* 
  **Could not download X.** If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until Somnium is updated.

* 
  **X is not a whitelisted download.** This can happen when I update the modlist. Check if a new update is available and wait if there is none.

* 
  **Wabbajack could not find my game folder.** Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the `Pre-Installation <#pre-installation>`_ step and ensure you have clean and valid installations of both Skyrim and Enderal SE.

* 
  **Windows is reporting that a virus has been detected.** Windows 10 has started to auto-quarantine the ``usvfs_proxy_x86.exe`` file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found `here <https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan>`_.

* 
  **Cyclic Redundancy Check error during installation** This could be several things, but the first thing we would recommend is confirming that Wabbajack is not installed in your Documents, Downloads or Program Files folders, then delete the contents of ``%APPDATA%/Local/Wabbajack`` and re-open the app and try again. If this does not resolve the problem, it could be related to drive corruption and you should run CHKDSK on the drive in question.


Personalizing the Game
~~~~~~~~~~~~~~~~~~~~~~

**There is no MCM customization necessary for Somnium**.  The MCM options for all mods are set automatically to Somnium's standard.
