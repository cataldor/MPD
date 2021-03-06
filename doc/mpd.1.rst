===
mpd
===

SYNOPSIS
--------

``mpd`` [options] [CONF_FILE]

DESCRIPTION
------------

MPD is a daemon for playing music. Music is played through the configured audio output(s) (which are generally local, but can be remote). The daemon stores info about all available music, and this info can be easily searched and retrieved. Player control, info retrieval, and playlist management can all be managed remotely.

MPD searches for a config file in ``$XDG_CONFIG_HOME/mpd/mpd.conf`` then ``~/.mpdconf`` then ``/etc/mpd.conf`` or uses CONF_FILE.

Read more about MPD at ``<http://www.musicpd.org/>``.

OPTIONS
-------

--help
  Output a brief help message.

--kill
  Kill the currently running mpd session. The pid_file parameter must be specified in the config file for this to work.

--no-daemon
  Don't detach from console.

--stderr
  Print messages stderr.

--verbose
  Verbose logging.

--version
  Print version information.

FILES
-----

~/.mpdconf
  User configuration file.

/etc/mpd.conf
  Global configuration file.

SEE ALSO
--------

mpd.conf(5), mpc(1)

BUGS
----
If you find a bug, please report it at ``<https://github.com/MusicPlayerDaemon/MPD/issues/>``.
