btsync-rpm
==========

An RPM spec file to package BTSync for Fedora 21.

To build:

wget -O ~/rpmbuild/SOURCES/bittorrent_sync_x64-1.4.103.tar.gz http://download.getsyncapp.com/endpoint/btsync/os/linux-x64/track/stable
rpmbuild -ba ~/rpmbuild/SPECS/btsync.spec
