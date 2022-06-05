```bash
 docker create --name=coduo -e 'VERSIONSRV=kn-codclassic-large.tar' -e 'DATA_DIR=/codclassic' -e 'GAMETYPE=uo' -v $HOME/cod:/codclassic -p 28960:28960/tcp -p 28960:28960/udp keinnerd/codclassic:latest
 ```
