# THIS DOES NOT WORK ANYMORE!

This project is retired and no longer works as it originally did.

You would have an easier time using a repack from diakov.net. The default language is Russian upon installation, but it's easy to change it back to English from the menu.

Farewell.

#   IDM Activator

###   Activation

---

 - This script applies the registry lock method to activate the Internet Download Manager (IDM).

 - This method requires Internet at the time of activation.

 - IDM updates can be installed directly without having to activate again.

 - If you are still nagged by IDM for activation after running the script, just rerun the script another time.

<br>

###   Reset IDM Activation / Trial

---

 - The Internet Download Manager provides 30 days trial period, you can use this script to reset this Activation / Trial period whenever you want.
 
 - This option also can be used to restore status if in case the IDM reports a fake serial key and other similar errors.

####   OS requirement: Windows 7, 8, 8.1, 10 & 11

<br>

##   How to use it?

###   PowerShell (Windows 10/11)

---

Right-click on the windows start menu and select PowerShell or Terminal.

Copy-paste the below code and press enter:

    iwr -useb https://naeembolchhi.github.io/IDM-Activator/IDMA.ps1 | iex

You will see the activation options, and follow onscreen instructions.

That's all.

<br>

###   CMD as Admin (Windows 7/8/8.1)

---

Download the file with ".cmd" extension from this repo.

Right-click on the file and select "Run as Administrator".

You will see the activation options, and follow onscreen instructions.

That's all.

<br>

###   Troubleshooting

---

   - If any other activator was used to activate IDM previously then make sure to properly uninstall it with that same activator (if there is an option), this is especially important if any registry/firewall block method was used.
     
     - If you're unable to properly remove the older IDM from everywhere (including registry), try using Revo Uninstaller Pro to scan and delete file and registry remnants.

   - Uninstall the IDM from the control panel.

   - Make sure the latest original IDM setup is used for the installation.
     
   - Download IDM: https://www.internetdownloadmanager.com/download.html

   - Now install the IDM and use the activate option in this script if failed then,

     - Disable the windows firewall with the script option, this helps in case of leftover entries of previously used activator (some file patch method also creates firewall entries).

     - Some security programs may block this script, this is false-positive, as long as you downloaded the file from the original post (mentioned below on this page), temporary suspend Antivirus real-time protection, or exclude the downloaded file/extracted folder from scanning.

     - If you are still facing any problems, please create an issue on this repo.

<br>

###   Credits

---

| **Dev** | **Contribution** |
|---|---|
| @Dukun Cabul | Original researcher of this IDM trial reset and activation logic, made an Autoit tool for these methods, IDM\-AIO\_2020\_Final |
|  | nsaneforums\.com/topic/371047\-\-/?do=findComment&comment=1632062 |
| @WindowsAddict | Ported the above Autoit tool to a batch script |
| @AveYo aka @BAU | Snippet to set registry ownership and permission recursively |
|  | pastebin\.com/XTPt0JSC |
| @abbodi1406 | Awesome batch script tricks and help |
| @dbenham | Set buffer height independently of window height |
|  | stackoverflow\.com/a/13351373 |
| @ModByPiash | Added and fixed some missing features |
| @NaeemBolchhi \(Me\) | Improved username generation |
