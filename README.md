# conky-apt-mail

# Description:

To "Conky-all" equal to or less version 1.9.0-4
Tested on Ubuntu Trusty and Ubuntu Xenial.

Conky calendar+available mail+up-to-date information available using bash and pl scripts recovered slightly on the Internet and processed:
Calendar.sh by Mobilediesel
Debupdate.sh by DarthWound
Pop3.pl by Avalanche
Package Installation:
gawk (GNU awk, a pattern scanning and processing language)
remind (sophisticated calendar and alarm program)
ncal (bsdmainutils)
curl (command line tool for transferring data with URL syntax)
SoX (complete tools for sound processing)
libsox-fmt-mp3 (MP2 and MP3 library for SoX)
yad (Dialog)
ccrypt (file encryption)
libappconfig-perl (appconfig module)
mpg123 (audio player for MPEG layer 1/2/3)
libfile-homedir-perl (Perl module to find directories of users across platforms)
Fonts "Droid Sans Mono Bold" "Corporate Mono Bold Extra"
The "calendrier" folder is copied to the folder "~/conky".
The ".conkyrc" are copied to your Home folder.
It is also necessary to create a file ".reminders" in your Home folder.
"debupdate.sh" only works if the verification updates are done automatically in your system.
Synaptic and Thunderbird must be started with the files tunderbird and sinaptic in the "calendrier" folder.
You can copy these files in "/usr/local/bin".
You must also set in the file "pop3.pl" (except V6) our mailbox with your username and password.
Refresh the date at midnight + 2 seconds.
The start of conky is through the "calendriermailapt.sh" file located in the folder "~/conky/calendrier/launchers."
"calendriermailapt.sh", which you can copy in "usr/local/bin" is a rocker launcher to stop or start viewing three conky (version, calendar and mailapt)
"mail_apt_data_panel" (which I put on my personal system autorun) is a rocker launcher to stop or start "conkyrc_mail_apt_data" (which allows the search for new packages and new mail every 3600 seconds.

# Credits to
jbaseb
