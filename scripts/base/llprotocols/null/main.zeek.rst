:tocdepth: 3

base/llprotocols/null/main.zeek
===============================
.. zeek:namespace:: LL_NULL


:Namespace: LL_NULL

Summary
~~~~~~~
Redefinitions
#############
========================================================================== ==================================================================================
:zeek:id:`LLAnalyzer::config_map`: :zeek:type:`vector` :zeek:attr:`&redef` From the Wireshark Wiki: AF_INET6ANALYZER, unfortunately, has different values in
                                                                           {NetBSD,OpenBSD,BSD/OS}, {FreeBSD,DragonFlyBSD}, and {Darwin/Mac OS X}, so an IPv6
                                                                           packet might have a link-layer header with 24, 28, or 30 as the AF_ value.
========================================================================== ==================================================================================


Detailed Interface
~~~~~~~~~~~~~~~~~~

