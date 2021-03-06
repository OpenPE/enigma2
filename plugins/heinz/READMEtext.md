NOTE: The easiest way to use this plugin is
by **binding a key to it**, to be able to
invoke it directly from a live stream and/or
"ketchup" stream.

When **invoked during a supported live stream**,
settings can be changed from the EPG screen
using the

 Menu

key.

If **invoked during an unsupported live stream**,
letting the timeout expire will take you to
the setup menu where you can adjust the
settings.

If **invoked during a "ketchup" stream**, the
following keys can be used to control it:

 Left, Right, Up, Down, OK, Back, and Exit

as well as

1 2 3 4 5 6 7 8 9 0

These keys will, respectively:
- rewind the timeline;
- forward the timeline;
- display stream information;
- pause the stream;
- reload the stream at the current/selected
timeline time;
- stop the stream and return to the previous one;
- exit the timeline and continue as is;
- forward the timeline 1..10 minutes.

If **the stream is reloaded without any change to
the timeline**, the stream will go back by
the configured number of minutes (see settings):
this is useful if a stream gets stuck and just a
reload is needed.

From version 6.0.3j, a keymap.xml file (located in
the usual plugins/Heinz directory) is used that
also maps other keys to the relevant actions during
timeline display, for example:

Rewind/PreviousSong, FastForward/NextSong, Info/EPG,
Pause/Play+Pause, Play, and Stop.

Depending on your remote, you might need to edit this
file, namely regarding the mapping of the pause/play/
play+pause keys, or if you just want to map/unmap the
keys you're more comfortable with using. Make sure to
keep a copy of the edited file, as upgrades to newer
versions of the plugin will overwrite it.

From version 6.2.0a, "recording" functionality was
added, that allows one to download content from the
archive into the local drive.

Dev/Testing on OpenATV 6.0, Caveat Emptor.

For new versions with "recording" functionality:

Dev/Testing on OpenATV 6.2, Caveat Emptor.
