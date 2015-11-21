如何使用 tcpdns.py 脚本 ?
-------------------------------

  
2015-11-21 修改（by recall704）
去掉了依赖python-daemon，直接以程序的 package 方式调用。



### Linux/Mac

 1.    修改本机DNS为127.0.0.1

   ```bash
  $ vi /etc/resolve.conf
  nameserver 127.0.0.1
  ```
 2.    重启网络

  ```bash
  $ sudo /etc/init.d/networking restart
  ```
 3.    运行脚本

  ```bash
  $ sudo python tcpdns.py -f tcpdns.json
  ```

### Windows

 1.    修改本机DNS为127.0.0.1
 
 2.    运行tcpdns.exe


脚本依赖
----------------------------

### libraries
   * [libev] (http://libevent.org/)

### python模块
   * [gevent] (https://github.com/surfly/gevent)
   * [pylru] (https://github.com/jlhutch/pylru)
   * [python-daemon] (https://pypi.python.org/pypi/python-daemon)

### python模块安装

``` bash
  sudo apt-get install libevent-dev
  sudo pip install gevent
  sudo pip install python-daemon
```

LICENSE
----------------------

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License 
as published by the Free Software Foundation, either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty
of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see 
http://www.gnu.org/licenses/
