# Terminal Emulator for Android

*Note:* Terminal Emulator for Android development has ended. I am not
accepting pull requests any more.

Terminal Emulator for Android is a terminal emulator for communicating with the
built-in Android shell. It emulates a reasonably large subset of Digital
Equipment Corporation VT-100 terminal codes, so that programs like "vi", "Emacs"
and "NetHack" will display properly.

This application was previously named "Android Terminal Emulator". Same great
application, just with a new name. (The change was made at the request of the
Android trademark owner.)

This code is based on the "Term" application which is included in the Android
Open Source Project. (Which I also wrote. :-) )

[Download the Terminal Emulator for Android from Google Play](https://play.google.com/store/apps/details?id=jackpal.androidterm)

If you are unable to use the Play Store, you can also
[download from GitHub](https://jackpal.github.io/Android-Terminal-Emulator/)

See [Building](docs/Building.md) for build instructions.

Got questions? Please check out the
[FAQ](http://github.com/jackpal/Android-Terminal-Emulator/wiki/Frequently-Asked-Questions). Thanks!

Please see the
[Recent Updates](http://github.com/jackpal/Android-Terminal-Emulator/wiki/Recent-Updates)
page for recent updates.

*************************

## The following is the README.md of a very old version of the Termux app repository

Termux app
==========
[![Travis build status](https://travis-ci.org/termux/termux-app.svg?branch=master)](https://travis-ci.org/termux/termux-app)
[![Join the chat at https://gitter.im/termux/termux](https://badges.gitter.im/termux/termux.svg)](https://gitter.im/termux/termux)

[Termux](https://termux.com) is an Android terminal app and Linux environment.

* [Termux on Google Play Store](https://play.google.com/store/apps/details?id=com.termux)
* [Termux on F-Droid](https://f-droid.org/repository/browse/?fdid=com.termux)
* [Termux Facebook](https://facebook.com/termux/)
* [Termux Google+ community](http://termux.com/community/)
* [Termux Help](http://termux.com/help/)
* [Termux Twitter](http://twitter.com/termux/)
* [Termux Wiki](https://wiki.termux.com/wiki/)  

Note that this repository is for the app itself (the user interface and the terminal emulation). For the packages installable inside the app, see [termux/termux-packages](https://github.com/termux/termux-packages)

Terminal resources
==================
* [XTerm control sequences](http://invisible-island.net/xterm/ctlseqs/ctlseqs.html)
* [vt100.net](http://vt100.net/)
* [Terminal codes (ANSI and terminfo equivalents)](http://wiki.bash-hackers.org/scripting/terminalcodes)

Terminal emulators
==================
* VTE (libvte): Terminal emulator widget for GTK+, mainly used in gnome-terminal. [Source](https://github.com/GNOME/vte), [Open Issues](https://bugzilla.gnome.org/buglist.cgi?quicksearch=product%3A%22vte%22+), and [All (including closed) issues](https://bugzilla.gnome.org/buglist.cgi?bug_status=RESOLVED&bug_status=VERIFIED&chfield=resolution&chfieldfrom=-2000d&chfieldvalue=FIXED&product=vte&resolution=FIXED).
* iTerm 2: OS X terminal application. [Source](https://github.com/gnachman/iTerm2), [Issues](https://gitlab.com/gnachman/iterm2/issues) and [Documentation](http://www.iterm2.com/documentation.html) (which includes [iTerm2 proprietary escape codes](http://www.iterm2.com/documentation-escape-codes.html)).
* Konsole: KDE terminal application. [Source](https://projects.kde.org/projects/kde/applications/konsole/repository), in particular [tests](https://projects.kde.org/projects/kde/applications/konsole/repository/revisions/master/show/tests), [Bugs](https://bugs.kde.org/buglist.cgi?bug_severity=critical&bug_severity=grave&bug_severity=major&bug_severity=crash&bug_severity=normal&bug_severity=minor&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&product=konsole) and [Wishes](https://bugs.kde.org/buglist.cgi?bug_severity=wishlist&bug_status=UNCONFIRMED&bug_status=NEW&bug_status=ASSIGNED&bug_status=REOPENED&product=konsole).
* hterm: JavaScript terminal implementation from Chromium. [Source](https://github.com/chromium/hterm), including [tests](https://github.com/chromium/hterm/blob/master/js/hterm_vt_tests.js), and [Google group](https://groups.google.com/a/chromium.org/forum/#!forum/chromium-hterm).
* xterm: The grandfather of terminal emulators. [Source](http://invisible-island.net/datafiles/release/xterm.tar.gz).
* Connectbot: Android SSH client. [Source](https://github.com/connectbot/connectbot)
* Android Terminal Emulator: Android terminal app which Termux terminal handling is based on. Inactive. [Source](https://github.com/jackpal/Android-Terminal-Emulator).

