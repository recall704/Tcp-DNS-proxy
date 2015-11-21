
![Build Status](https://travis-ci.org/henices/Tcp-DNS-proxy.svg?branch=master)




How to use this python script (modify by recall704) ?
-------------------------------
```bash
sudo apt-get install libevent-dev
sudo apt-get install python-pip
sudo pip install gevent
sudo pip install pylru

git clone https://github.com/recall704/Tcp-DNS-proxy.git
cd Tcp-DNS-proxy
cp tcpdns.json.example tcpdns.json
sudo python tcpdns.py -f tcpdns.json -d
```



detail please read [https://github.com/henices/Tcp-DNS-proxy/blob/master/README.md](https://github.com/henices/Tcp-DNS-proxy/blob/master/README.md "https://github.com/henices/Tcp-DNS-proxy/blob/master/README.md")



LICENSE
----------------------

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License 
as published by the Free Software Foundation, either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty
of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see 
http://www.gnu.org/licenses/
