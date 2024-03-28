<pre>

sudo apt-mark hold tracker
sudo apt-mark hold tracker-extract
sudo apt-mark hold tracker-miner-fs

sudo chmod -x /usr/libexec/tracker-extract-3
sudo chmod -x /usr/libexec/tracker-miner-fs-3

tracker3 reset --filesystem --rss # Clean all database
tracker3 daemon --terminate

Link de referência
https://stackoverflow.com/questions/72827703/how-to-disable-file-indexing-in-ubuntu-22-04-tracker3

</pre>
