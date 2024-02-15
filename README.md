## FreshMint
A new skin for the Linux Mint forums. A real daily experience. Not just screenshots... Not just a showcase... It's real ! Try this new skin today and start living better !

It works on Firefox and Chrome. On your Linux Mint system and on your Android phone or tablet as well. 

**before:**
![FreshMint preview](screenshots/preview-old.png)  

**after:**
![FreshMint preview](screenshots/preview-new.png)

## Installation

#### Userstyle manager

First, you need a userstyle manager that supports installing UserCSS.

* Stylus for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/) or [Chrome](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) (recommended).
* xStyle for [Firefox](https://addons.mozilla.org/firefox/addon/xstyle/) or [Chrome](https://chrome.google.com/webstore/detail/xstyle/hncgkmhphmncjohllpoleelnibpmccpj).

#### UserCSS file

Next, open [FreshMint.user.css](https://raw.githubusercontent.com/SebastJava/FreshMint/main/FreshMint.user.css) here in your web browser.

Stylus will then open a new tab showing some basic information & options:

* Click on the "Install style" button.
* Click on the "Check for updates" checkbox.

Once installed, you will be redirected to Stylus editor page with the newly installed/updated UserCSS loaded. Close this if you don't want or need to modify the style.

**Now you can see and feel your new [Linux Mint Forums](https://forums.linuxmint.com) !**

#### A better start (optional)

The default board style on the forums is **Minty**. That's a fork from the standard **Prosilver** style. This **FreshMint** here is build directly on top of that **Prosilver** source.

**If you are in a hurry, don't worry and just skip this step.** All the `colors.css` got duplicated, so this FreshMint should look the same on both Minty and Prosilver. But if you want to make sure everything is 100% accurate, please switch to Prosilver before installing FreshMint on top of it.

<details>
<summary>Click here to switch to Prosilver</summary>

1. [Login](https://forums.linuxmint.com/ucp.php?mode=login&redirect=index.php) or [Register](https://forums.linuxmint.com/ucp.php?mode=register) to the forums.
2. Go to your [User Control Panel](https://forums.linuxmint.com/ucp.php).
3. Click on the **Board preferences** tab and select **prosilver** for your board style.
4. Click on the **Submit** button.
</details>

## Compare !
You can compare using screenshots:

![](screenshots/Minty-vs-FreshMint.png)

You can also instantly switch between the old and the new. Click on the Stylus icon, then click on the FreshMint checkbox:

![](screenshots/Stylus-on-off.png)

## Experiment with colors and styles !

This theme is based on UserCSS. There are some variables you can instantly try and see. Click on the Stylus icon, then click on the FreshMint gear icon:

![](screenshots/Stylus-configure.png)

You will then get a control panel where you can instantly change some CSS variables:

![](screenshots/Stylus-UserCSS-config.png)

## Everything got redesigned

The page header is the first thing people will see and thus it is very important. Extra care was taken on this page header. But there is much more than this here. Everything was looked at and readjusted.

* a communicative design
* sufficient contrasts
* colors that echo the main website

And then the extra coding was reduced to very little. So it shouldn't pose too much trouble when the time comes to update the phpBB engine.

## Troubleshooting

* **Flashing of unstyled content (FOUC):** To avoid this, click on the Stylus Options (gear icon). In the "Advanced" section, turn on the "Instant inject mode".

**For any other problem,** please open a new [issue](https://github.com/SebastJava/FreshMint/issues).