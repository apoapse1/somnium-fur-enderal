Installation
============
Somnium is a balanced but hardcore take on the Enderal experience with upgraded environments, improved/replaced assets across almost every game facet and better looking NPCs. Various bug fixes have been made and quality of life features have been included, both in-game and during the installation process.

The mechanics of Somnium have been completely overhauled, chiefly by Enderal Gameplay Overhaul, with extensive further balancing done specifically for this list.

Somnium makes use of the excellent `Wabbajack <https://www.wabbajack.org/#/>`_ program to make installation as fast and painless as possible. We have taken the ease of Wabbajack even further, which means that there are only a few, very easy steps involved in setting up Somnium.  Overall installation instructions are below, with further information detailed after.

#. Install a clean version of **BOTH** Skyrim Special Edition and Enderal Forgotten Stories Special Edition.
#. Install the Wabbajack desktop client from `here <https://github.com/wabbajack-tools/wabbajack/releases>`_.
#. Navigate to Somnium under the *Browse for Modlists* tab.
#. Install Somnium to a new folder outside of ``Program Files``. Be advised that Somnium uses a stock Enderal game folder that is self-contained.
#. When it has finished intalling (which can take a while depending on your internet), navigate to the install location and run ``Install.bat``
#. Start a new game via the ``Play Somnium`` button.


Pre-Installation
^^^^^^^^^^^^^^^^

These steps are only needed if you are installing Somnium for the first time. If you only want to update Somnium, jump straight to `Updating <#updating>`_.

Installing Microsoft Visual C++ Redistributable Package
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from `Microsoft <https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads>`_. Download the x64 version under "Visual Studio 2015, 2017 and 2019". `Direct link <https://aka.ms/vs/16/release/vc_redist.x64.exe>`_ if you can't find it.


Cleaning Skyrim Folders
~~~~~~~~~~~~~~~~~~~~~~~

If you have previously played modded Skyrim or Enderal it is highly recommended to re-install both games cleanly before installing Somnium.
#. Uninstall Skyrim Special Edition and Enderal Forgotten Stories Special Edition within Steam
#. Unsubscribe to all Steam Workshop Mods
#. Delete the ``Skyrim Special Edition`` and ``Enderal Special Edition`` folders found within your steam install location.
#. Delete the ``Skyrim Special Edition`` and ``Enderal Special Edition`` folders found at ``Documents\my games\``_.
#. Delete the ``Skyrim Special Edition`` and ``Enderal Special Edition`` folders found at ``User\appdata\local\``_.


How to install to the correct location
~~~~~~~~~~~~

We need to make sure that Steam won't install the games into the default Program Files Location. This is more complicated, but still not difficult. You should be fine if you follow this `guide
<https://help.steampowered.com/en/faqs/view/4BD4-4528-6B2E-8327>`_ on how to create a Steam Library folder elsewhere. You only need to follow the "How do I change the default installation path for my games?" section. 
  **You do not need to set the new folder to the default install location.** You can if you would like. Simply having a new location is enough.

**Important** If you only have one drive, Steam will not let you move your installation location.  You can still accomplish this however, by first exiting Steam completely and then simply moving your entire Steam folder to a location outside of ``Program Files`` by "drag-and-drop".  Start steam via the executable in the moved folder and it will recognize this as your new install location.

After you have a new Steam Library folder outside of the ``Program Files (x86)`` location, you can install Skyrim and Enderal SE. When you click to install simply select the newly created folder.

Finally, set the game's language to English. Just do it. An english version of Skyrim and Enderal configuration files are necessary to install Somnium.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.


Using Wabbajack
^^^^^^^^^^^^^^^

Preparations
~~~~~~~~~~~~

Grab the latest release of Wabbajack from `here <https://github.com/wabbajack-tools/wabbajack/releases>`_ and place the ``Wabbajack.exe`` file in a *working folder*. This folder **must not** be in *common folders* like your Desktop, Downloads, or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like ``C:/Wabbajack``.

Downloading and Installing
~~~~~~~~~~~~~~~~~~~~~~~~~~

The download and installation process can take a very long time, depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

#. Open Wabbajack, browse for Somnium in the Wabbajack client, and click to download it.  
#. Set the installation folder to somewhere that is not affected by UAC (Please do not put it in Documents, Program Files, or Desktop. Put it somewhere easy like ``C:/Modlists/Somnium``\ ). The downloads path should automatically fill in the installation path, but this can be changed if needed.
#. Click the Go/Begin button.
#. Wait for Wabbajack to finish.
#. If you run into any issues, see the next section. If the installation is successful, proceed to `Post-Installation <#post-installation>`_.

Problems with Wabbajack
"""""""""""""""""""""""

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-trying Wabbajack at least once before posting anything, usually it will complete what it missed the first time. Check the ``overwrite`` box on the install page and Wabbajack will continue where it left off, so you lose no progress.

* 
  **Could not download X.** Sometimes Wabbajack times out while downloading a few mods.  In this case, you can re-run Wabbajack, check the ``Network Workaround`` box in settings and start the install again.  If this doesn't work, you can also try a VPN to change your download region.  We recommend ProtonVPN as a good free option.
  
* 
  **Could not download X.** If a mod updated and the old files got deleted, it is impossible to download them. In this case, just wait until I update Somnium.

* 
  **X is not a whitelisted download.** This can happen when I update the modlist. Check if a new update is available and wait if there is none.

* 
  **Wabbajack could not find my game folder.** Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the `Pre-Installation <#pre-installation>`_ step and ensure you have clean and valid installations of both Skyrim and Enderal SE.

* 
  **Windows is reporting that a virus has been detected.** Windows 10 has started to auto-quarantine the ``usvfs_proxy_x86.exe`` file from the latest version of Mod Organizer 2, saying a threat has been detected. This is a known false postive confirmed by the MO2 Devs. You can fix this by adding an exemption for MO2 Folder to your Antivirus. Example for Windows Defender can be found `here <https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan>`_.

* 
  **Cyclic Redundancy Check error during installation** This could be several things, but the first thing we would recommend is confirming that Wabbajack is not installed in your Documents, Downloads or Program Files folders, then delete the contents of ``%APPDATA%/Local/Wabbajack`` and re-open the app and try again. If this does not resolve the problem, it could be related to drive corruption and you should run CHKDSK on the drive in question.



Final Steps
""""""""""""""""""""""

#. Navigate to the Somnium installation location and double-click on ``Install.bat``.  This will create the necessary paths to the game folders.
#. Double-click ``Play Somnium``.  It may take a minute or two for ENB files to load so just be patient. 
#. Click ``New Game`` to start your adventure.


ENB Presets
""""""""""""""""
*
  **Somnium ENB Selector** *(Defaults to PLACERHOLDER ENB)* Right-clicking and selecting Reinstall Mod on the Somnium ENB Selector will allow you to choose between several included ENB options with various quality presets.

Please note that if you have your Wabbajack Downloads folder outside of the ``<Somnium Install>/downloads`` path, you will need to go to your downloads folder, copy the Somnium ENB Selector and Somnium UI Customizer .7z files to your ``<Somnium Install>/downloads`` folder before you can Reinstall them in MO2 and use the FOMOD.

Alternatively, you can change the Somnium Mod Organizer 2 Downloads directory by clicking the "Configure settings and workarounds" button in Mod Organizer 2 (it looks like a screw and wrench crossed over eachother) and changing the Downloads directory to whatever you selected when installing Somnium in Wabbajack.**


Personalizing the Game
~~~~~~~~~~~~~~~~~
Please note that, by default, Somnium has German voice-over with English subtitles.  This is both to preserve the original vision of Enderal and because the German voice acting is top notch.  If you prefer English audio, uncheck the ``German Voice Files`` mod in the left pane of Mod Organizer 2.

**There is no MCM customization necessary for Somnium**.  The MCM options for all mods are set automatically to Somnium's standard. This section below this details options to personalize your game if you are not happy with some of the default settings or hotkeys.

#. **Placeholder** Placeholder text


Updating
^^^^^^^^

If Somnium receives an update, please check the Changelog before doing anything. Always back up your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the updated modlist when updating!**

This means that any additional mods you have installed on top of Somnium will be deleted. However, your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the *Overwrite existing modlist* button.
Note that some in-game settings will get reset when updating. Check them all again!

Finished
^^^^^^^^

Congratulations! You've completed the Somnium setup, and you are ready to play. The next several sections will explain what Somnium is and does, as well as provide support.
