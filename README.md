# Backup
Linux Backup Guides
## Shadowsock-qt5:

     sudo add-apt-repository ppa:hzwhuang/ss-qt5
     sudo apt-get update
     sudo apt-get install shadowsocks-qt5
     
     (windows) https://www.softpedia.com/get/Internet/Servers/Proxy-Servers/Shadowsocks.shtml
## Omega switch rules :

     https://raw.githubusercontent.com/gfwlist/gfwlist/master/gfwlist.txt

## Maxima:
</br>1.configure gcl([read this](https://sourceforge.net/p/wxmaxima/discussion/435775/thread/75627a0b/)): 

     sudo apt-get install gcl
     sudo dpkg-reconfigure gcl
    
</br>2.install maxima(make sure you have deleted all the maxima old versions):[download latest sources files here](https://sourceforge.net/projects/maxima/files/), and then cd in the file:

     ./configure
     sudo make -j8
     sudo make check -j8
     sudo make install -j8
     
 </br>3.install wxmaxima:
 
     sudo add-apt-repository ppa:blahota/wxmaxima
     sudo apt-get update
     sudo apt-get install wxmaxima
     
