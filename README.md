

# Requirements

- [ ] catchall watch folder (/mnt/blackhole/*.torrent) should work correctly and download to "unsorted"
- [ ]  dynamic watch directories
	- [ ] [remove the torrent from the watch directory once its loaded](https://github.com/rtorrent-community/rtorrent-docs/blob/master/docs/examples/rename2tied.sh)
	- [ ] auto-start watch directory torrents
- [ ] download all torrents to /mnt/processing directory
- [ ] redirect rtorrent daemon logs to STDOUT
- [ ] move completed downloads into dynamic `/mnt/downloads` subdirectories. [1](https://rtorrent-docs.readthedocs.io/en/latest/use-cases.html#versatile-move) [2](https://github.com/rakshasa/rtorrent/wiki/Common-Tasks-in-rTorrent#move-completed-torrents-to-a-fixed-location)
- [ ] DEPOT default user/password authentication for webui
- [ ] auto-labeling by watch folder compatible with flood
- [ ] [scheduling/QoS](http://rtorrent-docs.readthedocs.io/en/latest/use-cases.html#scheduled-bandwidth-shaping)
- [ ] Auto cleanup? Completed torrents that are stopped and older than 2 months?
- [ ] [stop seeding when download is complete](https://github.com/rakshasa/rtorrent/wiki/Common-Tasks-in-rTorrent#move-completed-torrents-to-a-fixed-location)
- [ ] [Performance tuning](https://github.com/rakshasa/rtorrent/wiki/Performance-Tuning)
- [ ] logrotate
- [ ] [better logging. ](https://serverfault.com/questions/599103/make-a-docker-application-write-to-stdout)
- [ ] ensure that deleting a partially downloaded/inprogress torrent will actually delete the associated data
	- [ ] when deleting a torrent we should always delete the .torrent file too
	- [ ] when deleting a torrent, sometimes the download directory is not deleted.

# Themes

- https://github.com/ronggang/transmission-web-control
- https://github.com/endor/kettu
- https://github.com/Secretmapper/combustion
