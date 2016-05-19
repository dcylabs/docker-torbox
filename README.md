# Quick run 
```
docker run \
 -p 9001:9001 \
 -p 9030:9030 \
 -p 9050:9050 \
 dcylabs/docker-torbox
```
# Specific configuration 
Make your own torrc configuration file and bind it to the container
```
docker run \
 -p 9001:9001 \
 -p 9030:9030 \
 -p 9050:9050 \
 -v torrc:/var/tor/torrc \
 dcylabs/docker-torbox
```
# Using it 
Specify your web browser proxy 
For all scheme
*SOCKS5
*docker.server.url.or.ip
*9050
# Contribute 
* Ask for improvements
* Make pull request 
* As you like :)