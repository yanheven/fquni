fquni
=====

unidirectional proxy

on client:
sudo ./proxy-down.sh ; sudo ./proxy-up.sh x.x.x.x
tail -f /tmp/fquni.log

on server:
python fquni_server.py

why nfqueue? because Android does not support -t TTL --ttl-set

License
=======
 
MIT
