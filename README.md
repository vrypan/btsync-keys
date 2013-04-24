btsync-keys
===========

A list of public BitTorrent Sync keys.

[BitTorrent Sync](http://labs.bittorrent.com/experiments/sync.html) allows users to sync their folders between machines. 
Each folder has a read-only and a read-write key, and anyone that knows one of the keys can sync with the specific folder.

The "keys.txt" file is the equivelent of the "hosts" file used before DNS was introduced: 
it maps keys to "human friendly" names.

The structure of the file is

    <folder-key> <folder-name> <R|W>

where *folder-key* is the btsync key, *folder-name* is a human readable text string and *R or W* indicates if the key is 
read-only or read-write.

Example:

    RNK7XXLW3LB4JSR7OP7LMKOTZLHEDRIRE vrypan-shared R

Of course, you can sync this folder using BitTorrent Sync. The key is

    RR745RPH5URZVEWS7NSY2KR2V3DKKPBGU
