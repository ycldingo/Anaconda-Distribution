The instruction is refer to https://docs.anaconda.com/
# Install on Linux (x86 system)
1. Download the Anaconda for Linux from https://www.anaconda.com/distribution/#linux in your browser.

2. Verify data integrity with SHA-256: Open a terminal and type
```javascript
sha256sum /path/filename
```

3. Install Anaconda for Python 3:
```javascript
bash ~/Downloads/Anaconda3-2019.10-Linux-x86_64.sh
```
For Python 2, just run a similar command as
```javascript
bash ~/Downloads/Anaconda3-2019.10-Linux-x86_64.sh
```

4. The installer prompts *In order to continue the installation process, please review the license agreement.*, click to view license terms.

5. Scroll to the bottom of terms and enter `Yes` or click enter to agree. Otherwise, the installation can not start.

6. The installer prompts you to 
    1. click `Enter` to accept the default install location
    2. `CTRL-C` to cancel the installation
    3. specify an alternate installation directory
<br>
It is recommanded to accept the default install location, and do not choose `/usr` for Anaconda installation.

7. After few minutes of waiting, the installation is complete. You will see *Do you wish the installer to initialize Anaconda3 by running conda init*, type `Yes`. (recommand)

8. *Thank you for installing Anaconda 3!* or *Thank you for installing Anaconda 2!*

# Install on macOS
## Graphical install
Download the macOS graphical installer at https://www.anaconda.com/distribution/#macos for the version you want, and follow the similar install procedures as usual. We will focus on the command-line install here since it is much complicated.

## Command-line install
1. Download the command-line installer of your version at https://www.anaconda.com/distribution/#macos in the browser.

2.  Follow the same direction as **Install on Linux**.

# Install on Windows
Download from https://www.anaconda.com/distribution/#windows, for which is graphical installer and is easy to go through with. There are some things needed to be notice:
- Install Anaconda to a directory path that does not contain spaces or unicode characters.
- Do not install as Administrator
- It is suggested to use Anaconda software by opening Anaconda Navigator or the Anaconda Prompt from the Start Menu, so please check the box *Register Anaconda as my default Python 3.7*.



# Verify the installation
1. Show the installed packages and their versions:
```javascript
conda list
```

2. Run Python shell:
```javascript
python
```
   If you successfully install Anaconda, the version information it displays when it starts up will include “Anaconda”. Command `quit()` to exit the Python shell.

3. Open Anaconda-Navigator:
```javascript
anaconda-navigator
```

