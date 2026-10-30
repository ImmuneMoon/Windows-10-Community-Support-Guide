# 🤝 Staying on Windows 10: Real Community Support, and What Lite Builds Cost You

*Support dates, prices, and details of third-party builds were checked in October 2026. They change, so confirm them before you rely on them.*

## The Problem
You want to stay on Windows 10 instead of moving to Windows 11, and you'd like the support of a community rather than relying on Microsoft alone. Searching for that turns up "lite" builds such as [Windows X-Lite](https://windowsxlite.com/win10), which promise a smaller, faster Windows. Those aren't the same thing as community support, and they cost more than they first appear to.

## The Short Answer
Real community support for Windows 10 is **people**, not patches. Repair groups, forums, and volunteers will help you back up, set up, and keep an old PC running, for free. They're the best place to start.

1. **Get help from a real community.** Start with **Where to Find Real Community Support**.
2. **Stay on official Windows 10 for now.** Enroll in Extended Security Updates, which run through **October 12, 2027** and can be free.
3. **Slim it down yourself** with reputable tools, keeping your security features on.
4. **Decide what's next before that date.** Linux is the option with a real community behind it.

A lite build can make Windows **smaller**, but only Microsoft can fix the Windows code itself. Most lite builds don't ship their own fixes, and they usually switch off protections to save space and speed. **What You Give Up With Windows X-Lite** shows exactly what that costs.

## First, Check Whether Your PC Can Run Windows 11
It's worth knowing before you commit to staying on Windows 10. The [Windows Install Guide](https://github.com/ImmuneMoon/Windows-Install-Guide) shows how to check with Microsoft's PC Health Check app.

* **If your PC qualifies:** Moving to Windows 11 is the simplest way to stay fully supported, and you won't need this guide. It's a free upgrade for a qualifying Windows 10 PC, and a PC that's already activated should normally activate Windows 11 by itself once it's online, as long as you install the same edition.
* **If your PC doesn't qualify:** Your realistic choices are to stay on Windows 10 with ESU through October 2027, or try Linux. Tools like Rufus can force Windows 11 onto a PC that doesn't qualify, but [Microsoft warns](https://support.microsoft.com/windows/0b2dc4a2-5933-4ad4-9c09-ef0a331518f1) those PCs may malfunction and aren't guaranteed updates, including security updates.

The rest of this guide is for staying on Windows 10.

## Where to Find Real Community Support
The best starting point is the [End of Windows 10 toolkit](https://therestartproject.org/end-of-windows-10-toolkit-for-repair-groups/) from The Restart Project, a UK repair charity. It's written for community repair groups, and it's useful because it has nothing to sell you. It doesn't mention modified builds at all. It calls Microsoft's ESU the safest way to stay on Windows 10, and it doesn't recommend running Windows 10 unsupported if you aren't technical.

| What you need | Where to go |
|---|---|
| **Someone to help in person** | [Repair Cafés](https://www.repaircafe.org/en/) are free volunteer events in many countries. Some help with PCs, so check what your local one covers first. The toolkit also describes End of 10 parties held by repair groups. |
| **Answers online** | The [Restarters forum](https://talk.restarters.net/) has a section on Windows 10's end of support, and volunteers there have worked through these same decisions. |
| **A way off Windows 10** | The [End of 10](https://endof10.org/) campaign helps people move old PCs to Linux. |
| **Help with Linux** | Local Linux user groups run by volunteers. The toolkit lists UK groups, and other countries have their own. |
| **A new home for the PC** | Computer reuse groups can pass on a PC you no longer need. The toolkit lists UK options. |

Much of the toolkit's local information is for the UK, but the advice applies anywhere.

### What to Bring to a Repair Event
1. The PC, plus its charger or power cable.
2. An external drive or USB stick for your backup.
3. A list of the apps you can't live without. It decides which options will work for you.
4. Your Microsoft account login, if you have one. Type it in yourself rather than handing it to anyone.

### The Option With a Real Community Behind It
The toolkit's main recommendation is **Linux**. This is what community support really looks like: the system itself is built and patched by its own community and maintainers, and it's still getting security updates long after Windows 10 stops.

* **Linux Mint** and **Zorin OS** are the two [the toolkit](https://therestartproject.org/end-of-windows-10-toolkit-for-repair-groups/) names for newcomers. See [linuxmint.com](https://linuxmint.com/) and [zorin.com/os](https://zorin.com/os/).
* **Try it first.** You can run Linux from a USB drive without changing anything on your PC. The [Linux Install Guide](https://github.com/ImmuneMoon/Linux-Install-Guide) walks through it.
* **Still need Windows for one app?** The toolkit suggests dual-booting, with Linux for daily use and Windows 10 only for that app.

## Where Windows 10 Stands Right Now
Regular support ended on October 14, 2025. These are the ways to keep getting security fixes:

| Option | Fixes until | Cost | The catch |
|---|---|---|---|
| **Official 22H2 with [consumer ESU](https://www.microsoft.com/windows/extended-security-updates)** | October 12, 2027 | Free with settings sync, 1,000 Microsoft Rewards points, or $30 | Needs a Microsoft account with administrator rights. |
| **[0patch](https://0patch.com/pricing.html) on official 22H2** | No end date on its pricing page | €24.95 a year for Pro. Its Free plan only has selected fixes, and 0patch says post-support Windows 10 patches need a paid license. | Small third-party fixes, and not a full replacement for Windows Update. |
| **[IoT Enterprise LTSC 2021](https://learn.microsoft.com/en-us/lifecycle/products/windows-10-iot-enterprise-ltsc-2021)** | January 2032 | Sold through device-maker channels | Not a normal retail product, so there's no simple way for a home user to license it. |
| **[Enterprise LTSC 2021](https://learn.microsoft.com/en-us/lifecycle/products/windows-10-enterprise-ltsc-2021)** | January 2027 | Business volume licensing | Almost over, and not for home users. |

> **Older articles are wrong about ESU.** Many still say consumer ESU ended on October 13, 2026. Microsoft extended it a full year, and its [ESU page](https://www.microsoft.com/windows/extended-security-updates) now says October 12, 2027.

## Stay on Windows 10 the Safe Way
A repair group can help with any of these steps.

1. **Back up first.** Work through **Before You Start** in the [Remove an Old Windows Install guide](https://github.com/ImmuneMoon/Remove-Old-Windows-Install-Keep-Your-Files).
2. **Get Windows 10 from Microsoft.** The [Windows Install Guide](https://github.com/ImmuneMoon/Windows-Install-Guide) walks through the official Media Creation Tool. Choose the same edition you had (Home or Pro). A PC that was already activated on Windows 10 will normally reactivate by itself once it's online.
3. **Install it.** Follow the [Windows Install Guide](https://github.com/ImmuneMoon/Windows-Install-Guide), with the old drive unplugged as described in Step 1 of the removal guide.
4. **Update it fully.** Go to **Settings** > **Update & Security** > **Windows Update** and keep clicking **Check for updates** until nothing new appears. ESU requires this.
5. **Enroll in ESU.** Sign in with a Microsoft account that has administrator rights. Then, on the same **Windows Update** page, click **Enroll now** and choose an option.
6. **Slim it down.** Create a restore point first (see **Tool Walkthroughs**), then:
   * Uninstall apps you don't use in **Settings** > **Apps**.
   * Press `Ctrl + Shift + Esc` to open Task Manager, go to the **Startup** tab, right-click anything you don't need at startup, and choose **Disable**.
   * Reduce telemetry and ads with O&O ShutUp10++ (see **Tool Walkthroughs**).
   * **Never turn off Windows Update, Defender, or SmartScreen.** They're what keep this approach safe.
7. **Finish the old drive.** Continue from **Step 2** of the removal guide to clear the old install and keep your files.
8. **Set a reminder for 2027.** Before October 12, 2027, decide what comes next: Linux, Windows 11, or 0patch. A PC with no security fixes shouldn't stay on the internet.

## Tool Walkthroughs

### Create a Restore Point
A restore point lets you undo system changes if something goes wrong.

1. Open the Start menu, type `Create a restore point`, and open it.
2. On the **System Protection** tab, select your `C:` drive.
3. If **Protection** says **Off**, click **Configure**, choose **Turn on system protection**, and click **OK**.
4. Click **Create**, give it a name you'll recognize, and click **Create** again.

### O&O ShutUp10++
This free tool turns off telemetry, ads, and similar settings in one place. It only changes settings, and you can undo them.

1. Download it from the [O&O website](https://www.oo-software.com/en/shutup10) and open it. There's nothing to install.
2. Click **Yes** if asked to create a restore point. If it doesn't ask, go to **Actions** > **Create a system restoration point**.
3. Go to **Actions** > **Apply only recommended settings** and confirm.
4. Restart the PC.
5. Run it again after big Windows updates, since they can reset some settings.

To undo your changes, use the **Undo** options in the **Actions** menu. Stick with the recommended settings. The others can turn off things you need, including updates.

### 0patch
0patch fixes security holes in memory, without changing your Windows files. Windows 10 patches after end of support need a paid **Pro** license. Make sure Windows is fully updated first, because 0patch builds on Microsoft's latest updates.

1. Create an account at [0patch Central](https://central.0patch.com/) and activate it using the link in your email.
2. Buy a Pro license from your 0patch Central account.
3. Download the 0patch Agent from [0patch.com](https://0patch.com/) and install it.
4. Open **0patch Console**, then enter your account email and password to link the PC to your account.
5. That's it. Patches now apply by themselves, and you don't need to keep the console open.

### VirtualBox
VirtualBox runs a PC inside a window, so you can test a Windows build without touching your real install. The steps below are for testing a lite build.

1. Download **VirtualBox** for Windows hosts from [virtualbox.org](https://www.virtualbox.org/wiki/Downloads) and install it, accepting the defaults.
2. Open it and click **New**.
3. Give the virtual machine a name, and pick your ISO under **ISO Image**.
4. Turn off unattended installation. Depending on your version, uncheck **Install OS Using Unattended Installation** or check **Skip Unattended Installation**.
5. Set the hardware. About 4 GB for **Base Memory**, 2 **Processors**, and 64 GB for **Disk Size** is plenty. Don't assign more than half of your PC's processor threads.
6. Finish the wizard, select the new machine in the list, and click **Start**.
7. Install Windows in the window as normal.
8. Don't set up **Shared Folders** or a shared clipboard. They connect the test PC to your real one.

When you're done, right-click the machine and choose **Remove** to delete it.

### Autoruns
Autoruns is a free Microsoft tool that lists everything set to start with Windows, which is where unwanted software tends to hide.

1. Download [Autoruns](https://learn.microsoft.com/en-us/sysinternals/downloads/autoruns) and extract the zip file.
2. Right-click `Autoruns64.exe` and choose **Run as administrator**, then accept the license.
3. In the **Options** menu, turn on **Hide Signed Microsoft Entries**. This hides normal Windows items, so what's left is what was added.
4. Press `F5` to refresh, then look through the **Logon**, **Scheduled Tasks**, and **Services** tabs.
5. Search online for anything you don't recognize.
6. If you need to turn something off, uncheck its box instead of deleting it. You can check it again if that causes a problem.

## How Lite Builds Actually Work
A builder takes Microsoft's Windows image, strips out components, changes settings, and packages the result for download. How much you have to trust the builder depends on which kind you use:

| Type | Examples | What you're trusting |
|---|---|---|
| **Prebuilt ISO** | Windows X-Lite, Tiny10 | Everything. You can't see what was changed inside the image. |
| **Script applied to an official install** | Playbooks such as AtlasOS | The script, which you can read. Windows itself still comes from Microsoft. |
| **Tweaks on an official install** | O&O ShutUp10++ | Very little. You choose settings on a normal copy of Windows. |

Further down that table, you have less to take on faith. Support can also disappear: AtlasOS, one of the best-known projects, [dropped Windows 10](https://docs.atlasos.net/faq/general-faq/windows-10-vs-11/) when Microsoft ended support for it.

## What You Give Up With Windows X-Lite
This covers **Optimum 10 Pro v6**, the newest Windows 10 release on the site, based on the project's own [edition page](https://windowsxlite.com/Optimum10ProV6), [guides](https://windowsxlite.com/guides), and [update page](https://windowsxlite.com/W10updates). In exchange, you get a very small install of about 4.7 GB and fewer things running in the background.

### The Biggest Loss: About a Year of Security Fixes
* The v6 install is build **19045.5968**, from mid-2025.
* The project's newest update pack is **KB5066791 from October 2025**, build 19045.6456. Its update page doesn't mention ESU.
* Microsoft has kept releasing fixes through ESU. The [October 2026 update](https://www.it-connect.fr/windows-10-kb5126657-mise-a-jour-esu/) reached build **19045.7807**.

Every security hole fixed in that gap stays open on a PC that stops at the project's last pack. These are often flaws that attackers already know about. To close the gap, you'd need ESU, which means turning several things back on (see **If You Still Choose a Lite Build**), and the project doesn't say whether that works.

### What Else Is Gone or Switched Off
| What's lost | What it does for you | Can you get it back? |
|---|---|---|
| **Automatic updates** | Installs fixes without you having to remember. Paused by default until the year 3000, and the project recommends leaving them paused. | Yes, with **Resume Updates** in Settings. |
| **SmartScreen** | Warns you about dangerous downloads, unknown apps, and phishing sites. | Removed, and the project lists no way to restore it. |
| **User Account Control (UAC)** | Stops programs changing your system without your permission. With it off, malware has one less barrier. | Yes, with the project's registry file and a restart. You need this before signing in to a Microsoft account. |
| **Windows Defender** | Your built-in antivirus. | Choose the **Defender On** version when you install. The **Defender Off** version doesn't protect you. |
| **BitLocker** | Keeps your files private if the PC is lost or stolen. | Yes, through `services.msc`, according to the project's guides. |
| **Microsoft Store and built-in apps** | Installs and updates apps such as Calculator and Photos. | The Store has an installer in the Extras folder. You'd reinstall the apps yourself. |
| **Edge** | The built-in browser. | An installer is included, and any other browser works. |
| **File indexing** | Makes searching for files fast. | Not covered in the guides. Search still works, but slower. |
| **Hibernation** | Saves your session when a laptop's battery runs low. | Not covered in the guides. |
| **Power throttling** | Limits background apps to save laptop battery. | Not covered in the guides. |
| **Printing and Windows Firewall** | Your printer, and blocking unwanted network connections. | The guides give **Print Spooler On** and **Windows Firewall On** shortcuts, so check both after installing. |
| **Windows Ink, Error Reporting, Cortana** | Pen features, crash reports, and the voice assistant. | Most people won't miss these. |

### What You Lose Beyond the Features
* **A file you can verify.** Microsoft's copy comes straight from Microsoft. The v6 page has no file hash, and the download is on pixeldrain, a third-party file host.
* **A known source.** The site is credited to one name, FBConan, and calls its builds completely safe and clean. That's the project's own claim. No independent security review could be found. This doesn't mean the builds are infected, only that nobody outside the project has verified them.
* **Normal repair tools.** [DISM and SFC](https://github.com/ImmuneMoon/DISM-SFC-CHKDSK-Windows-Repair-Guide) expect a complete Windows, so they may not fix a stripped-down one.
* **Official support, and any guarantee of a future.** Microsoft doesn't support modified Windows, and a project can stop at any time.

### What the Project Does Well
It's fair to say that X-Lite handles some things better than others. It says its builds aren't pre-activated and don't include toolkits, because those can hide malware. It offers a Defender On version, and its update packs link to Microsoft's own download servers. You still need your own Windows license.

Some of what it removes is also worth removing: ads, telemetry, and unused apps. You can do most of that on an official install while keeping everything in the tables above (see **Stay on Windows 10 the Safe Way**).

## Other Risks of Lite Builds
These apply to any modified Windows, not just X-Lite:

1. **You have to trust the builder completely.** Nobody can fully check what's inside a Windows image, and antivirus tools can't do it for you. In June 2023, [Doctor Web](https://news.drweb.com/show/?i=14712) reported unofficial Windows 10 builds on torrent sites that hid crypto-stealing malware in the EFI partition, where antivirus rarely looks. Those builds came from torrent uploaders and aren't connected to any project named in this guide, but they show what a modified image can do.
2. **Things can break.** Apps may depend on something that was removed. X-Lite's own guides say its Ultralight builds can't be updated at all.
3. **Older editions may not qualify for ESU.** ESU needs version 22H2. One [third-party wiki](https://crustywindo.ws/Windows_X-Lite_%22Vanadium%22) describes X-Lite's Vanadium edition as based on version 1909, which wouldn't qualify.
4. **Activation cracks.** Lite builds are often paired with these, and they're a common way to get malware. Don't use them.

## If You Still Choose a Lite Build
Nothing here makes a modified build safe. These steps limit the damage if something is wrong with it.

1. **Decide what this PC won't be used for.** Don't use it for banking, your main email, a password manager, taxes, or work. Do those on your phone or another device.
2. **Choose carefully.** Use a 22H2 Optimum release with **Defender On**. Avoid Defender Off and Ultralight builds.
3. **Download only from the link on the project's own page.** Avoid reuploads and torrents.
4. **Check the file.** Open the Start menu, type `cmd`, and open **Command Prompt**. Then get the file's hash:
   ```cmd
   certutil -hashfile "C:\Users\You\Downloads\build.iso" SHA256
   ```
   Compare it with the project's published hash if there is one. A matching hash only proves the file wasn't changed after the builder made it. It doesn't prove the build is clean.
5. **Try it in a virtual machine first.** Set it up in VirtualBox (see **Tool Walkthroughs**) and run the checks in part 8.
6. **Unplug every other drive.** Your drive of kept files stays disconnected until this build has passed. Keep a backup that isn't attached to this PC at all.
7. **Install it, then turn the protections back on.** Use the [Windows Install Guide](https://github.com/ImmuneMoon/Windows-Install-Guide) to write the file to your USB drive. Then:
   * Run the project's UAC On file and restart.
   * Run the **Windows Firewall On** and **Windows Update Service On** shortcuts.
   * Click **Resume Updates** in Windows Update. Ignore the project's advice to leave updates paused.
8. **Check it before you trust it.** If it fails any of these, wipe it and use **Stay on Windows 10 the Safe Way** instead.

   | Check | How | To pass |
   |---|---|---|
   | Version | Press `Windows Key + R` and run `winver` | Version 22H2 |
   | Updates | **Settings** > **Update & Security** > **Windows Update** | Finds and installs updates |
   | Antivirus | **Windows Security** > **Virus & threat protection** | Defender is present and running |
   | ESU | The same **Windows Update** page | **Enroll now** appears, and you can finish enrolling |
   | Surprises | Autoruns (see **Tool Walkthroughs**) | Nothing unfamiliar that you can't explain |

   The ESU check is the one that matters most. If you can't enroll, this PC stays stuck at the project's last update pack.
9. **Only then reconnect your other drives,** and continue with the removal guide.
10. **Be ready to wipe it.** Keep your official USB drive and your backups. If anything seems wrong, reinstall from official media and delete **all** the partitions on the drive, including the EFI partition, so nothing can hide there.

## Things That Don't Make It Safer
* **A clean VirusTotal scan.** Scanners check for known threats, and most can't look through an entire Windows image. A clean result proves very little.
* **Lots of views or good comments.** Popularity doesn't tell you what's in the image, and most viewers would never notice a quiet infection.
* **"I've used it for years with no problems."** Good malware doesn't announce itself.
* **Leaving updates paused to keep things stable.** This trades a small annoyance for permanent exposure.
* **A VPN.** It protects your connection, not your operating system.

## Quick Checklist
- [ ] Checked whether my PC can run Windows 11
- [ ] Found a local repair group or asked on the Restarters forum
- [ ] Backed up my files
- [ ] Downloaded Windows 10 from Microsoft
- [ ] Installed it with other drives unplugged
- [ ] Updated fully and enrolled in ESU
- [ ] Slimmed it down, with Windows Update, Defender, and SmartScreen left on
- [ ] Cleared the old install using the removal guide
- [ ] Tried Linux from a USB drive
- [ ] Set a reminder to decide what's next before October 12, 2027

**Using a lite build anyway:**
- [ ] Read **What You Give Up With Windows X-Lite**
- [ ] Chose a 22H2 Optimum release with Defender On
- [ ] Tested it in a virtual machine
- [ ] Unplugged all other drives for the install
- [ ] Turned UAC, the firewall, and updates back on
- [ ] Enrolled in ESU, or wiped it and went back to official Windows
- [ ] Kept banking, email, and passwords off this PC
- [ ] No activators
