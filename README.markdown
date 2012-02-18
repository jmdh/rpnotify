# rpnotify - libnotify song notifications for Radio Paradise

## Description

Displays 'Now Playing' song notifications from Radio Paradise. Useful if
you want to use the Ogg Vorbis or other streams without embedded song
metadata.

## Licence

Permissive: see rpnotify itself for the licence text

## Using

Make sure you have the following installed:

- perl
- a libnotify notification daemon

perl modules:

- Gtk2::Notify
- LWP::UserAgent
- Readonly
- XML::Simple
- Log::Log4perl
- HTML::Entities

Make sure you have a libnotify notification daemon running (most
modern GNU/Linux desktops will have this).

Run the script:

    $ ./rpnotify

Press Ctrl-C to stop it.

## Credits

My thanks go to:

Radio Paradise, of course, for providing such a great selection of tunes.
<http://www.radioparadise.com/>

Michael Howe, for the idea.

## Contact

Feel free to get in touch with the author: Dominic Hargreaves <dom@earth.li>
with suggestions, bug reports or (preferably!) patches. You could also
try the github issue tracker.
