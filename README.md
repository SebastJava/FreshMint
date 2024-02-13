## FreshMint (WORK IN PROGRESS...)
A new skin for the Linux Mint forums. A real daily experience. Not just screenshots... Not just a showcase... It's real ! Install this new skin today and live better !

It works on Firefox, it works on Chrome, and it works on Android. And, one day, it will work everywhere, when the Linux Mint team integrates this code on its own servers... 

**before:**
![FreshMint preview](screenshots/preview-old.png)  

**after:**
![FreshMint preview](screenshots/preview-new.png)

## Installation

#### Prerequisites

The default board style on the forums is **minty**. That's a fork from the standard **prosilver** style. This **FreshMint** here is build directly on top of that standard **prosilver.** It made more sense to build on top of the source code, rather than trying to override an override...

So, you should first set your board style to **prosilver.**

1. [Login](https://forums.linuxmint.com/ucp.php?mode=login&redirect=index.php) or [Register](https://forums.linuxmint.com/ucp.php?mode=register) to the forums.
2. Go to your [User Control Panel](https://forums.linuxmint.com/ucp.php).
3. Click on the **Board preferences** tab and select **prosilver** for your board style.
4. Click on the **Submit** button.

#### Userstyle manager

First, you need a userstyle manager that supports installing UserCSS.

* Stylus for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) or [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) (recommended).
* xStyle for [Firefox](https://addons.mozilla.org/firefox/addon/xstyle/) or [Chrome](https://chrome.google.com/webstore/detail/xstyle/hncgkmhphmncjohllpoleelnibpmccpj).

#### UserCSS file

Open [FreshMint.user.css](https://raw.githubusercontent.com/SebastJava/FreshMint/main/FreshMint.user.css) here in your web browser.

Stylus will open a new tab showing some basic information & options:

* Click on the "Install style" button.
* Click on the "Check for updates" checkbox.

Once installed, you will be redirected to Stylus' editor page with the newly installed/updated UserCSS loaded. Close this if you don't want or need to modify the style.

Now you can see and feel your new https://forums.linuxmint.com

## Troubleshooting

* **Flashing of unstyled content (FOUC):** To avoid this, click on the Stylus Options (gear icon). In the "Advanced" section, turn on the "Instant inject mode".

**For any other problem,** please open a new [issue](https://github.com/SebastJava/FreshMint/issues).