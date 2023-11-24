## snort
Official Website: [snort](https://www.snort.org/)

### Installation steps:

```bash
# Step-1: Download Snort Source Code
wget https://www.snort.org/downloads/snort/snort-x.x.xx.tar.gz
```

- `wget`: Command-line utility for downloading files from the web.

- This command fetches the Snort source code archive (version x.x.xx) from the specified URL and saves it in the current directory.

```bash
# Step-2: Extract the Snort Source Code
tar xvzf snort-x.x.xx.tar.gz
```

- `tar`: Command for manipulating archives.
  - `x`: Extract the archive.
  - `v`: Verbosely list the files processed.
  - `z`: Filter the archive through gzip.
  - `f`: Use archive file specified (in this case, snort-x.x.xx.tar.gz).

- This command extracts the contents of the Snort source code archive into a directory named snort-x.x.xx.

```bash
# Step-3: Change Directory to the Snort Source Code Directory
cd snort-x.x.xx
```

```bash
# Step-4: Configure, Compile, and Install Snort
./configure --enable-sourcefire && make && sudo make install
```

- `./configure`: Script that checks the system for necessary tools and libraries and creates the Makefile.
    -   `--enable-sourcefire`: Flag to enable certain features related to Sourcefire.
- `make`: Command that compiles the source code into executable binaries using the Makefile.
- `make install`: Command that installs the compiled binaries and associated files system-wide with elevated privileges.

### For more details: 

[Info: snort](https://www.geeksforgeeks.org/what-is-snort/)

---------
## aircrack-ng
Official Website: [aircrack-ng](https://www.aircrack-ng.org/)

### For more details:

[Info: aircrack-ng](https://www.geeksforgeeks.org/kali-linux-aircrack-ng/)

----------
## nmap
Official Website: [nmap](https://nmap.org/)

### For more details:
[Info: nmap](https://www.geeksforgeeks.org/nmap-command-in-linux-with-examples/)

----------
## kiterunner

Source Code: [kiterunner](https://github.com/assetnote/kiterunner)

---------
## kali-tweaks

Source Code: [kali-tweaks](https://www.kali.org/tools/kali-tweaks/)

---------
## shodan search engine

Official Website: [shodan](https://www.shodan.io/)

--------
## netcat

Official Website: [netcat](https://nc110.sourceforge.io/)

There are two versions: **netcat-traditional** and **netcat-openbsd**

### For more details: 

`apt-cache show netcat-traditional ` and `apt-cache show netcat-openbsd`

[Info: nc (netcat)](https://www.geeksforgeeks.org/introduction-to-netcat/)

--------
## sed

### For more details:

[Info: sed (stream editor)](https://www.geeksforgeeks.org/sed-command-in-linux-unix-with-examples/)

--------
## dig

### For more details:

[Info: dig (Domain Information Groper)](https://www.geeksforgeeks.org/dig-command-in-linux-with-examples/)

--------
NOTE:

Difference between MySQL and MariaDB

[Info: MySQL and MariaDB](https://www.geeksforgeeks.org/difference-between-mysql-and-mariadb/)

-------
## apache2

Official Website: [apache2](https://httpd.apache.org/)

## nginx

Official Website: [nginx](https://www.nginx.com/)

## lightspeed

Official Website: [lightspeed](https://docs.litespeedtech.com/)

## IIS

Official Website: [IIS](https://www.iis.net/)

[Info: web server](https://www.geeksforgeeks.org/what-is-a-web-server-working-and-architecture/)

--------
## wireshark

Official Website: [wireshark](https://www.wireshark.org/)

---------
## bluez

Official Website: [bluez](http://www.bluez.org/)

---------
## synaptic

Source Code: [synaptic](https://github.com/mvo5/synaptic)

----------
## bluediving

Source Code: [bluediving](https://github.com/balle/bluediving)

----------
## shodan

Official Website: [shodan](https://www.shodan.io/)

----------
## modbus-cli

Source Code: [modbus-cli](https://github.com/tallakt/modbus-cli)

-----------
## sublime-text

Official Website: [sublime-text](https://www.sublimetext.com/)

------------
## OpenSSH

Official Website: [openssh-server](https://www.openssh.com/)

------------
