# Adkill.go - Kill Ads without browser extension for Windows, Linux and Mac -
- Version :1.0
- Author : vaboston
- Release date : 13-02-2017
- licence : GNU GPL V.3

Inspired by  adkill from penthium2 https://github.com/penthium2/adkill).

This script generates a powerful Hosts file for linux, windows and mac by merging 5 lists of advertisement references.
More than 600 000 hosts Banned.
# Usage :
Just run the script or add some options :
- ats : activate blacklist of ad/tracking servers listed in the hpHosts database.
- emd : activate blacklist of malware sites listed in the hpHosts database.
- exp : activate blacklist of exploit sites listed in the hpHosts database.
- fsa : activate blacklist of fraud sites listed in the hpHosts database.
- grm : activate blacklist of sites involved in spam (that do not otherwise meet any other classification criteria) listed in the hpHosts database.
- hfs : activate blacklist of sites spamming the hpHosts forums (and not meeting any other classification criteria) listed in the hpHosts database.
- hjk : activate blacklist of hijack sites listed in the hpHosts database.
- mmt : activate blacklist of sites involved in misleading marketing (e.g. fake Flash update adverts) listed in the hpHosts database.
- pha : activate blacklist of illegal pharmacy sites listed in the hpHosts database.
- psh : activate blacklist of phishing sites listed in the hpHosts database.
- wrz : activate blacklist of warez/piracy sites listed in the hpHosts database.
- all : activate blacklist of all sites listed in the hpHosts database.


Adkill creates ~/public directory then
- backs up original /etc/hosts file named : **hosts-system**


# To Do :
 - garder les anciennes lignes générées par Adkill
