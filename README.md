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

Enter one domain on each line, you may remove the www when adding a new domain, the blacklisting relies on simple substring matching.

Credits
-------

Thanks to https://github.com/Panthro for YourlsWhiteListDomains which was basically all of the code for this.
- https://github.com/Panthro/YourlsWhitelistDomains

Also thanks to https://github.com/LudoBoggio for the YourlsBlacklistIPs plugin which was the base for YourlsWhiteListDomains:
- https://github.com/LudoBoggio/YourlsBlacklistIPs

Changelog
---------

v0.03 Fix some crap code
v0.02 Cosmetic changes
v0.01 Initial code

---

Notice
------

Neither YourlsWhiteListDomains, nor YourlsBlacklistIPs are distributed with licensing or copyright details. I have contacted the authors and will ammend the following on their advice:

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
