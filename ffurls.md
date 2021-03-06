---
layout: main
---

[<- Back](./)

## [](#ffurls)ffurls
[Go to the project](https://github.com/freeprogs/ffurls)

#### [](#desc)Description

Saves tabs opened in Firefox to a file in some format.

It takes Firefox file with actual configuration of opened tabs and
windows, finds titles and urls there and saves these pairs to a file
in a selected format.

#### [](#example)Example

1) You have opened tabs, but you want to watch them after some work.

[![](./assets/images/ffurls/screen-mini-ffurls-browser.png)](./assets/images/ffurls/screen-ffurls-browser.png)

2) Make your own settings of the program configuration

The configuration in /usr/local/etc/ffurls.conf for all users in the operating system is

[![](./assets/images/ffurls/screen-mini-ffurls-configetc.png)](./assets/images/ffurls/screen-ffurls-configetc.png)

You create the config file ~/.ffurls.conf in your home directory

[![](./assets/images/ffurls/screen-mini-ffurls-confighome.png)](./assets/images/ffurls/screen-ffurls-confighome.png)

This file replaces some settings from the general config.

3) You open a console and run the shell-script with a parameter for the output format.

[![](./assets/images/ffurls/screen-mini-ffurls-console.png)](./assets/images/ffurls/screen-ffurls-console.png)

If you run the shell-script without parameters the program uses default settings from the config file.

4) Then after some work you open the Downloads folder.

[![](./assets/images/ffurls/screen-mini-ffurls-manager.png)](./assets/images/ffurls/screen-ffurls-manager.png)

5) You open the file with saved tabs.

Text format.

[![](./assets/images/ffurls/screen-mini-ffurls-textfile.png)](./assets/images/ffurls/screen-ffurls-textfile.png)

Html format.

[![](./assets/images/ffurls/screen-mini-ffurls-htmlfile.png)](./assets/images/ffurls/screen-ffurls-htmlfile.png)

Emacs-org format.

[![](./assets/images/ffurls/screen-mini-ffurls-orgfile.png)](./assets/images/ffurls/screen-ffurls-orgfile.png)

Now you can open this tabs again and edit files for watched links.

---

You can save tabs many times (new files will increment names) and rename output files to more convenient names.
