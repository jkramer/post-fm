## POST.FM

#About

*post-fm* is a Perl script that submits information about your currently played track to Last.FM / Audioscrobbler. It’s primarily made for [http://onion.dynserv.net/~timo/cmus.html](CMUS), a ncurses based music player, but could be used as a general purpose scrobbler with only minor modifications.
License

post-fm is published under the terms of the GNU General Public License (GPL), version 2. The full license can be found [http://www.gnu.org/licenses/gpl.txt](here).

#Prerequisites

The script requires the module LWP::UserAgent, which is usually found in a package called libwww-perl or something similar. Linux/BSD distributions should provide a prebuilt package. Otherwise, install it from [http://www.cpan.org/](CPAN).

#Installation

Simply copy the script to a place where CMUS can find it (~/.cmus/ for example) and make it executable. Then start CMUS and type

	:set status_display_program=/path/to/post-fm

Please note that you have to use the absolute path and that $HOME/... or even ~/... won’t work.

Now open the script with your favorite editor and replace the username and password placeholders at the top with your Last.FM login data.
