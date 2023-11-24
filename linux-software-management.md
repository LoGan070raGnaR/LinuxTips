# Managing Software on Linux: Installation, Removal, and Updates

**Installing Software:**
To add new software or tools, use the following command:
```bash
sudo apt install bluez
```

**Removing Software:**
To remove software, you can use:
```bash
sudo apt remove bluez
```

However, removing the application may leave behind configuration files. If you want to completely remove everything related to the application, including configuration files, use:
```bash
sudo apt purge bluez
```

**Updating Package Information:**
Periodically, it's essential to update the list of available packages on your system. This ensures you have the latest information. Run:
```bash
sudo apt update
```

**Adding Repository Links:**
To access additional software repositories, you can add their links to the `/etc/apt/sources.list` file. This file contains a list of repositories where your system looks for packages. Be cautious and only add repositories from trusted sources.

**Downloading from GitHub:**
For software hosted on GitHub, you can use the `git` command. For example:

```bash
git clone https://github.com/balle/bluediving.git
```

**Python Package Manager (pip):**
To install Python packages, use:

```bash
sudo apt install python3-pip
```

For example, installing the Shodan Python package:
```bash
sudo pip3 install shodan
```

**Ruby Package Manager:**
For managing Ruby scripts, you can use the `gem` command. For instance:

```bash
sudo gem install modbus-cli
```

**Snap Package Mananger:**
To manage software packages using the Snap package manager, you can use the `snap` command. For example, to install Sublime Text, use the following command:

```bash
sudo snap install sublime-text --classic
```

**Note:**

Always be cautious while managing software, and ensure that you have the necessary permissions to install or remove packages. Regularly updating your package information is good practice to stay current with the available software packages.
