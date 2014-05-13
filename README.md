spotify_terminal
================
A project to create a simple, but fuctional terminal spotify client for a linux enviorment. 

Dependencies
------------
This program depends on libspotify, a C api develpoed by spotify.

Download from [here](https://developer.spotify.com/technologies/libspotify/#libspotify-downloads)

Build and run
-------------
'make' for building the program. 'make debug' for building the program with debug outputs.

Libspotify howto
----------------
If you have root access, pretty simple. Just extract the tar, go to the folder, and run 
<code>'make install'</code>.

If you don't have root access, you can install libspotify in your home folder. For what i will explain i will
that you installed it to '~/usr/local/lib', with the command
<code>'make install prefix=~/usr/local/lib'</code> 

If you stilled it into the home folder, you have to update some PATHS, if you already haven't

<code>export PKG_CONFIG_PATH=$HOME/local/lib/pkgconfig/</code>

<code>export LD_LIBRARY_PATH=$HOME/local/lib<code>
