# Ubuntu Graylog

This script sets up a Ubuntu 16.04 virtual machine on your computer (through vagrant).
It then installs the three graylog docker containers into the virtual box. Matryoshka style.

Tested on macOS sierra.

## Prerequisists
- vagrant (tested with virtualbox)
- ansible
- rake

## Instructions

run rake ubuntu_graylog
from your host machine open http://127.0.0.1:9000/


