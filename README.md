<div align="center">
    <img src="static/images/FAK Logo.jpg" alt="For All Kerbalkind Logo" width="800px">
</div>

<div align="center" style="margin-top: 15px;">
    <a href="https://github.com/TheBeardyPenguin/ForAllKerbalkind/releases">
        <img src="https://img.shields.io/github/v/release/TheBeardyPenguin/ForAllKerbalkind" alt="GitHub Release">
    </a>
    <img src="https://img.shields.io/github/stars/TheBeardyPenguin/ForAllKerbalkind" alt="GitHub Stars">
    <img src="https://img.shields.io/github/downloads/TheBeardyPenguin/ForAllKerbalkind/total?logo=github" alt="GitHub Download Count">
</div>

# The ultimate Realism Overhaul modpack
*That's one small install for a Kerbal, one giant modpack for all Kerbalkind!*
<br>

Historically, installing Realism Overhaul (RO) and its career mode Realistic Progression (RP-1) has never been an easy task for anyone who just wants to play a standard KSP-like Career Mode within a realistic setting.

Finding out which part mods and visual overhauls to add only complicates matters further - and this doesn't even account for the fact that many mods are not properly configured or balanced for RO/RP-1.

Whilst options like the *RP-1 Express Installer* were the de-facto standard for a long time, the 2.0 Update for RP-1 made it incredibly difficult to enjoy a "classic" RP-1 career experience without missing out on quality-of-life updates and improvements.

### But no more!

As featured in the [Multiplayer YouTube series of the same name](https://www.youtube.com/playlist?list=PL7TVzn8CoIqnZE7fxcAix46pxWzx0nWf3), the **For All Kerbalkind** modpack aims to make installing a stable, balanced, and content-rich classic RO/RP-1 experience a *small step*, rather than a *giant leap*.

<br>

---


# Installation
<div align=center>
<img src = "static\images\ReadMe.png" width=400 height=400>
</div>

> [!CAUTION]
> If you decide to deviate from this guide in any way, ***we will not be able to provide support***.

---

### 1) Prepare a clean installation of Kerbal Space Program 1.12.5 (Latest Version)
Prepare your install by copying/cloning a **clean** **KSP 1.12.5** installation to a **new** folder.<br>You do not need to roll back to any specific older version to install this modpack.

- **Steam:** Copy it from the install directory
  - Default Windows Path: **``C:\Program Files\Steam\steamapps\common\Kerbal Space Program\``**
- **GOG Galaxy:** Copy it from the install directory
  - Default Windows Path: **``C:\Program Files\GOG Galaxy\Games\Kerbal Space Program\``**
- **Epic Games:** Copy it from the install directory
  - Default Windows Path: **``C:\Program Files\Epic Games\KerbalSpaceProgram\``**
- **Standalone:** Download and extract the standalone ZIP-File.

> [!IMPORTANT]
> ### This needs to be a CLEAN/UNMODIFIED "stock" KSP 1.12.5 installation!
> 
> This means that any existing KSP install where you may have previously had mods is <ins>NOT</ins> supported, as it may include leftover files which can cause issues.
> 
> Completely re-download/re-install the game if you do not have a "clean" install of KSP available to copy for this.

Make sure you give your new installation folder a suitable name.
Your final installation folder and executable should now be something like ``...\Games\KSP_ForAllKerbalkind\KSP_x64.exe``.


### 2) [Download the latest release of CKAN](https://github.com/KSP-CKAN/CKAN/releases/latest)
You can place it inside your newly created KSP directory, but it can also be run from anywhere.


### 3) [Download the latest release of this modpack](https://github.com/TheBeardyPenguin/ForAllKerbalkind/releases/latest)
*The latest release can also be found on the right-hand side of this page.*

Download it and extract the contents of the ZIP-File into a temporary location. We will need them later.


### 4) Run CKAN and Configure allowed game versions
Run CKAN, then ensure that you have the correct KSP instance targeted by going to
<br>
``File -> Manage game instances -> New game instance -> Add instance to CKAN``
<br>
and selecting the **``KSP_x64.exe``** file inside your new KSP directory.

Afterwards, go to ``Settings -> Compatible game versions`` and **🗹 tick/select** the following game versions:
- 1.12
- 1.11
- 1.10
- 1.9
- 1.8
- 1.0

> [!NOTE]
> The **🗹 ticks/selections** we made above disable CKAN's version compatibility checking!<br>If you plan on adding your own mods via CKAN after finishing this install guide, pay attention to the compatible KSP versions to avoid problems.

### 5) Install the FAK Modpack CKAN File
In CKAN, go to ``File -> Install from .ckan`` and then select the **``ForAllKerbalkind.ckan``** file you extracted from the Modpack ZIP-File.

> [!CAUTION]
> **Do <ins>NOT</ins> select any** of CKAN's "Recommendations", "Suggestions" or "Supported By" mods. This is extremely important, and failure to do so **will** break the installation.

After pressing Continue, the installation will begin. It will take a while to download and install all the mods.<br>**Wait until this has finished before proceeding with the next step.**


### 6) [Install RP-1 v1.13.2.2](https://github.com/KSP-RO/RP-1/releases/download/v1.13.2.2/RP-1-v1.13.2.2.zip)
Download and extract the *contents* of the ZIP-File's **``GameData``** folder into the **``GameData``** folder in your KSP directory.

> [!NOTE]
> *RP-1 has to be installed manually as CKAN prevents you installing this specific version due to CKAN dependency handling, despite it working perfectly.*


### 7) [Install Raiz's MAKS Spaceplane](https://www.dropbox.com/s/9a03cltqmga0uqq/MAKS.zip?dl=1)
*Adds Soviet "MAKS" (Multipurpose Aerospace System) spaceplane parts.*

Download and extract the *contents* of the ZIP-File's **``GameData``** folder into the **``GameData``** folder in your KSP directory.


### 8) [Install GuilioDondi's Space Shuttle System Fork](https://github.com/giuliodondi/Space-Shuttle-System-realistic-aerodynamics/releases/latest)
*Adds NASA "Space Shuttle" parts with considerably improved aerodynamic modeling.*

Download and extract the *contents* of the ZIP-File's **``GameData``** folder into the **``GameData``** folder within in your KSP directory.

> [!NOTE]
> *You will be prompted to replace some files relating to **RealismOverhaul** - this is normal. Agree and let it replace those files.*


### 9) [Install mcd0uble's HL-20 Parts](https://github.com/mcd0uble/HL20/archive/refs/heads/master.zip)
*Adds parts and a model for the NASA "HL-20" Lifting-body spaceplane.<br>These are currently used to create a working MiG-105/Spiral Spaceplane - an actual HL-20 Personnel Launch System config might be made later down the line.*

Download and extract the *contents* of the ZIP-File's **``GameData``** folder into the **``GameData``** folder in your KSP directory.


### 10) [Install Harrier Jump Jet Parts Pack](https://spacedock.info/mod/2863/Harrier%20Jump%20Jet%20Parts%20Pack/download)
*Adds parts that allow for the constructions of a Harrier/Yak-38/Do-31 type V/STOL "Jump Jet" aircraft.*

Download and extract the *contents* of the ZIP-File's **``GameData``** folder into the **``GameData``** folder in your KSP directory.


### 11) [Install BluedogDB's LRV](https://spacedock.info/mod/442/Bluedog%20Design%20Bureau/download)
*Adds a much better Lunar Roving Vehicle than the default one included in RO.*

Download, extract the ZIP-File to a temporary location, and then **delete <ins>everything</ins>** except for the **``Gamedata\Bluedog_DB\Parts\Apollo\LRV``** folder.

Afterwards, copy the **``Bluedog_DB``** folder into the **``GameData``** folder in your KSP directory.

> [!TIP]
> *To make future updates/reinstalls easier, we recommend keeping this stripped BDB folder somewhere for later.*


### 12) [Install Ven's Stock Revamp Antenna](https://github.com/Kerbas-ad-astra/Stock-Revamp/releases/latest)
*Adds an excellent Soviet-style antenna model.*

Download, extract the ZIP-File to a temporary location, and then **delete <ins>everything</ins>** except for the **``GameData\VenStockRevamp\Squad\Parts\ScienceParts``** folder.

Afterwards, copy the **``VenStockRevamp``** folder into the **``GameData``** folder in your KSP directory.

> [!TIP]
> *To make future updates/reinstalls easier, we recommend keeping this stripped VenStockRevamp folder somewhere for later.*


### 13) Suppress Kerbinside Version Error
*Removes an annoying pop-up warning.*

Go to **``GameData\KerbinSideRemastered``** and delete **``MiniAVC.dll``**. This is perfectly safe, as **MiniAVC** is just a Version Checker.


### 14) [Install Blackrack's TUFX Profile](https://drive.usercontent.google.com/u/0/uc?id=1zCqxMuG4nyQJlpVshsWkiyCdSi-1Wswj&export=download)
*Adds a post-processing profile that works great with the **Deferred** mod that is packaged with the modpack.*

Download and copy the file into the **``GameData``** folder in your KSP directory.


### 15) First KSP Launch

> [!IMPORTANT]
> ### Launching the game at this stage is <ins>**REQUIRED**</ins> for some files to properly generate and save to the cache!

Run the **``KSP_x64.exe``** in your KSP directory (or launch the game through CKAN) and ensure you can reach the main menu with all the install steps that were done so far.

- Ignore RP-1 complaining that you are using a Legacy Version - that is intentional. Dismiss this warning by clicking "Don't show again".
- Accept KSP Community Fixes' **PNG Caching Optimization** pop-up by clicking "Yes".

> [!NOTE]
> *The game may take a long time to load. This is normal, and only the case for the first launch.*

If the game keeps crashing or gets stuck on an endless loading screen, you have most likely gone wrong somewhere. If that is the case, restart from **Step 1** and make sure you haven't missed anything.


### 16) OPTIONAL - [Install Mouse Aim Flight](https://legacy.curseforge.com/kerbal/ksp-mods/mouse-aim-flight/download/2884916)
*Adds improved mouse-based flight controls, useful for piloting aircraft.*

Download and extract the *contents* of the ZIP-File's **``GameData``** folder into the **``GameData``** folder in your KSP directory.


### 17) OPTIONAL - [Install Ballisticfox's RSS Reborn](https://github.com/RSS-Reborn/RSS-Reborn/wiki/Installation)
**Only recommended for powerful computers with a minimum of 16 GB of RAM, a fair amount of SSD Storage Space, and a good GPU**.

Adds incredible planet textures, clouds, and weather effects. RSS Reborn is usable with or without [Blackrack's Raymarched Volumetric Clouds](https://www.patreon.com/blackrack/posts).

[Download the Automatic RSS Reborn Installer](https://github.com/drobie22/RSS-Reborn-Installer/releases/latest), place it in your KSP directory and run it.

> [!WARNING]
> Make sure you select the correct KSP Directory, e.g. ``...\Games\KSP_ForAllKerbalkind\``.

If you have **Blackrack's Raymarched Volumetric Clouds**, select its ZIP file when prompted and RSS Reborn will ***automatically*** install it for you.

**Enable** "Recommended Community Visual Settings" when prompted, and tick **all** boxes *except* for adding TUFX, as the modpack has already done that for you.

Change the **Earth** textures to **16k** and leave everything else as default.
> [!CAUTION]
> **Higher resolutions will eat tens of GB of memory and cause our custom Kerbal Konstructs bases to not display properly.** It is up to you if you want to see the individual blades of grass at Cape Canaveral with <10 FPS, but we do not recommend going above 16k for performance and stability reasons.


### 18) Install the For All Kerbalkind Modpack Files
Copy the contents of the **``GameData``** folder in the For All Kerbalkind modpack folder into the **``GameData``** folder in your KSP directory, and overwrite any conflicts.

Fixes several bugs, tweaks the tech tree and balance, and adds RO/RP-1 support for mods, custom spacesuits, gold sun visor, bases, flags, and more!


### 19) Prune various unused parts
Boot up the game, create a new save, and head into the **VAB**. Click the icon of two crossed brooms in the bottom right to open **Janitor's Closet**. Click **Export/Import**, then **Import**, then **``For All Kerbalkind.prnlst``**. The correct directory should open by default - if you can't see the file, navigate to your KSP Directory, then **``GameData/JanitorsCloset/PluginData``**.

After selecting the file, click the brooms icon again, then **PermaPrune**. This prevents the hundreds of unused mod parts from being loaded, **dramatically improving load times and reducing memory usage**.

This process is easily reversible if necessary. It will take a few minutes, so be patient.


### 20) Select the TUFX profile
Launch a basic vessel, such as a cockpit, to get to the *Flight* scene. **This needs to be a real launch, and <ins>NOT</ins> a KCT simulation.**

Once loaded click on the TUFX button in the Toolbar, select the "**Blackrack_TUFX**" profile in the list, and then  **exit to the Space Center** so the settings save (don't revert, as this will also revert your change).


### 21) Hide non-RP0 parts
Create a new empty folder in your KSP directory's **``GameData``** folder and name it **``NoNonRP0``**.

This will hide all parts that cannot be pruned but are not configured for RO/RP-1 or are otherwise useless, to declutter your editor and tech tree.


### 22) Play the game!
If everything has been set up correctly and works, you should now be able to start playing!

> [!TIP]
> **Consider making a backup of your installation at this point.**
> 
> If you find yourself adding additional mods or updating to a newer (minor) version of the FAK Modpack later down the line, having the ability to quickly go back to a "known to work" install can save you a **lot** of time!

---

## Check out the Series!

<div align="center">
    <table>
        <tr>
            <td align="center">
                <p><strong>The Beardy Penguin</strong></p>
                <a href="https://www.youtube.com/@TheBeardyPenguin" target="_blank">
                    <img src="static/images/Rocketeer.png" alt="Beardy-channel" width="250" height="250">
                </a>
                <p>Kaputnik Design Bureau</p>
                <p>(USSR)</p>
            </td>
            <td align="center">
                <p><strong>N9 Gaming</strong></p>
                <a href="https://www.youtube.com/@N9GamingOfficial" target="_blank">
                    <img src="static/images/2022Logo.png" alt="N9-channel" width="250" height="250">
                </a>
                <p>The Astral Foundation</p>
                <p>(USA)</p>
            </td>
            <td align="center">
                <p>　</p>
                <p><strong>Carnasa</strong></p>
                <a href="https://www.youtube.com/@Carnasa" target="_blank">
                    <img src="static/images/PatreonTier4.png" alt="Carnasa-channel" width="250" height="250">
                </a>
                <p>Commonwealth Space Commission</p>
                <p>(Europe & British Commonwealth)</p>
            </td>
            <td align="center">
                <p><strong>Calvin Maclure</strong></p>
                <a href="https://www.youtube.com/@CalvinMaclure" target="_blank">
                    <img src="static/images/CalvinMaclure.png" alt="Calvin-channel" width="250" height="250">
                </a>
                <p>China National Space Administration</p>
                <p>(China)</p>
            </td>
        </tr>
    </table>
</div>

## Discord

If you've followed the ReadMe and still need more help, come along to one of our Discord Servers:

### [Beardy's Discord](https://discord.gg/VNUARRswWX)

### [N9's Discord](https://discord.gg/n9gaming)

### [Carnasa's Discord](https://discord.gg/cYeXTeNBe8)
