# ![Contact Admin](https://imattpro.github.io/logo/search.png "Contact Admin") Contact Admin for phpBB3

phpBB extension that allows guests and/or registered users to either send an email to admins or to either send a PM or make a Post in a designated forum. It also overrides the default contact admin link found on the forum.  A port of the phpBB 3.0.x mod “Contact Board Administration”

Forked by Rob Hills in Jan 2021 (currently [AEVA Forums](https://forums.aeva.asn.au) Webmaster) so we can add a ReCaptcha to the modified Contact form and not have to manually update that every time we upgrade this extension!

[![Build Status](https://github.com/rmcgirr83/contactadmin/workflows/Tests/badge.svg)](https://github.com/rmcgirr83/contactadmin/actions)

## Installation

### 1. clone
Clone (or download and move) the repository into the folder ext/rmcgirr83/contactadmin:

```
cd ~/subdomains/forums.aeva.asn.au/
git clone https://github.com/AEVA-asn-au/contactadmin.git ext/rmcgirr83/contactadmin/
```

### 2. activate
Go to admin panel -> tab customise -> Manage extensions -> enable Contact Admin

Within the Admin panel visit the Extensions tab and choose the settings for the extension.

## Update instructions:
1. Go to you phpBB-Board > Admin Control Panel > Customise > Manage extensions > Contact Admin: disable
2. Delete all files of the extension from ext/rmcgirr83/contactadmin
3. Upload all the new files to the same locations
4. Go to you phpBB-Board > Admin Control Panel > Customise > Manage extensions > Contact Admin: enable
