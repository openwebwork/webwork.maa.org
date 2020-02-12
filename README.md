# webwork.maa.org
Information about the webwork.maa.org server.

The current use of this repo is to track the migration of webwork.maa.org to test1.webwork.maa.org.
 
Applications which are managed on webwork.maa.org include
* MediaWiki
* Moodle (which powers the WeBWorK forums)
* Request Tracker (RT) which manages tickets for setting up courses and other maintenance
* Mailman -- which hosts the development list [ww-devel] and the bug report list [ww-bugs]
* Bugzilla -- which hosts the bug reports

Important infrastructure
* postfix (sendmail replacement) -- used by bugzilla, mediawiki (and also moodle?)
* certificates -- so that the mail is not bounced by post offices.

Other applications which are for now managed separately on other boxes are 
* WeBWorK installation sites, managed with Google spreadsheet and google maps hosted on TWP's google drive
* The POD documentation currently maintained on demo.webwork.rochester.edu
