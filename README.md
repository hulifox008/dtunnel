dtunnel
=======

Bridge two separated network using DTLS.

This program can bridge two separated network at MAC level. Once bridged, the two networks looks like one network connected together.

- Running as client/server mode. Server side must have a public internet IP.
- A dedicated ethernet interface for client/server. You can actually use the interface used by the system, but any Ethernet frames hit the interface will be forwared. This may not be what you want.
