twisted-connect-proxy
=====================

Default Twisted does not ship with a CONNECT-enabled HTTP(s) proxy.  This code provides one.

Why a fork?
===========

Add `redirect()` function to replace certain domains with their direct IPs in order to bypass
domain blocking at my university.
