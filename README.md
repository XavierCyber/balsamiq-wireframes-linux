# How to Run Balsamiq Wireframes on Linux

Instructions on how to run Balsamiq Wireframes on Linux, using Wine and Lutris.

### PREREQUISITES

* a mainstream Linux distribution (Ubuntu / Debian / Fedora / Mint), with `curl`, `wine` and `wine32`.
* `lutris` - Lutris makes it easy to install wine-powered applications. You can [download Lutris](https://lutris.net/downloads/) or look at the installation instructions [on Github](https://github.com/lutris/lutris/blob/master/INSTALL.rst).

### INSTALLING BALSAMIQ WIREFRAMES

1. (for lutris 5.8 and following versions) please launch `lutris -i "https://raw.githubusercontent.com/balsamiq/balsamiq-wireframes-linux/master/balsamiq-wireframes-installer.json"`
1. (for lutris version < 5.8) download and launch the installer with `wget https://raw.githubusercontent.com/balsamiq/balsamiq-wireframes-linux/master/bw.yml -O /tmp/bw.yml && lutris -i /tmp/bw.yml` 
1. follow the steps in the Lutris wizard, and voila'!

### LAUNCHING BALSAMIQ WIREFRAMES

Simply launch the app from your application or desktop shortcut shortcut, or from the Lutris panel.

### CURRENT LIMITATIONS

* At the moment the app cannot be used to edit projects hosted on Balsamiq Cloud. You'll have to use a browser instead.
* At the moment export pdf doesn't work if some UTF-8 fonts are present (like emojis and some asian fonts)

If you manage to fix these issues before we do, PRs are welcome! :)
