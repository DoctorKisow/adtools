# Active Directory Tools

**adtools** - A script to manage SSO (Single Sign-On) for Linux workstations and servers.<br />
Version: 3.00.01<br />
Copyright &copy; 2014-2019, Matthew R. Kisow, D.Sc. <matthew.kisow@kisow.org><br />

## Tasks
- [ ] Function "check_installed" better checking required to eliminate the need for an installation flag file.
- [ ] Function "write_configuration" set flags when checking changes to /etc/pam.d files and write information out to post install log file.
- [ ] Function "interactive_config" test entered data for "basic" error checking.
- [ ] Function "show_config" cleanup output formatting.

## Installation
1. Following the instructions for your distribution, install git.
2. Using the _git clone_ command, clone **adtools** from this repository into the root home directory.
```shell
		cd /root
		git clone https://github.com/DoctorKisow/adtools.git
```
3. Using the _chmod +x_ command, make the **adtools** script executable.
```shell
		chmod +x adtools
```
4. Using the _bash_ command, initialize the **adtools** configuration file by using the -I switch.
```shell
		./adtools -I
```

## Script Notes
By typing _./adtools_ with no options, or _./adtools -h_ you can get help.

## Warning
Do not use this script in a _PRODUCTION_ enviornment with out testing and validating it first.
This script has been tested using Ubuntu 14.04.5 and Ubuntu 16.04.4.

## License
License (GPL v3.0)

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
