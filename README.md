YourlsBlackListDomains
======================

Plugin for Yourls that disallows blacklisted domains. Further, if YourlsBlacklistIPs is installed it also blacklists the submitter's IP address.

This plugin is intended to be used with YOURLS (cf. http://yourls.org)

It has been tested on YOURLS v1.5.1 and YourlsBlacklistIPs v1.3

Current version is 0.03

Contact : *apelly[ at ]len[ dot ]io*

**INSTALL :**

- In user/plugins, `git clone https://github.com/apelly/YourlsBlacklistDomains.git`
- Go to the plugins administration page and activate the plugin.

**UPDATE :**

- In user/plugins/YourlsBlacklistDomains, `git pull https://github.com/apelly/YourlsBlacklistDomains.git`

**USAGE :**

You will see in the admin section a new admin page where you can manage the blacklist.

Enter one domain on each line, the blacklisting relies on simple substring matching within the whole URL.

If you have [YourlsBlacklistIPs](https://github.com/LudoBoggio/YourlsBlacklistIPs) installed and activated then any IP that attempts to shorten a blacklisted URL will automatically be blacklisted by that plugin too. 

Credits
-------

Thanks to [Panthro](https://github.com/Panthro) for [YourlsWhiteListDomains](https://github.com/Panthro/YourlsWhitelistDomains) which was basically all of the code for this, and for kindly giving permission to puplish under GPL.  
> You are free to fork whatever you want, that's what code is for!  

Also thanks to [LudoBoggio](https://github.com/LudoBoggio) for the [YourlsBlacklistIPs](https://github.com/LudoBoggio/YourlsBlacklistIPs) plugin which was the base for YourlsWhiteListDomains.  

Changelog
---------

v0.03 Fix some crap code  
v0.02 Cosmetic changes  
v0.01 Initial code  

---

Notice
------

Neither YourlsWhiteListDomains, nor YourlsBlacklistIPs are distributed with licensing or copyright details. [Panthro](https://github.com/Panthro) has given explicit permission to use his code. I await a response from [LudoBoggio](https://github.com/LudoBoggio) and will ammend the following on their advice:

**Copyright&copy; (2012) Aaron Pelly**

**License**

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
