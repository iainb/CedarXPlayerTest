CedarX Player Test
==================

Info
----
This is the CedarXPlayerTest files from the [Mele Ubuntu image](http://rhombus-tech.net/allwinner_a10/hacking_the_mele_a1000/mele_ubuntu_image/) which was released in April 2012. The player should work on other Allwinner A10 devices running Linux.

There is no source available for this player, it is simply a demo of the CedarX decoder in operation.

The libraries included in this repository were missing from the above release.

Sample Media
------------
The sample file included in the image is not included in this repository. Sample media can be found here: http://samplemedia.linaro.org/

Usage
-----
In testing (On a Debian system) only the CedarXPlayerTest-1.4.1 file plays back media. The CedarXPlayerTest script calls this player, the known arguments are as follows:

CedarXPlayerTest <Media File>
