#initially created here: https://github.com/l-n-s/wireguard-install - but that's a bit outdated currently

#Execute next commands:
```
wget https://raw.githubusercontent.com/l-n-s/wireguard-install/master/wireguard-install.sh -O wireguard-install.sh
bash wireguard-install.sh
rpm -i https://linux.cc.iitk.ac.in/mirror/centos/elrepo/elrepo/el7/x86_64/RPMS/elrepo-release-7.0-8.el7.elrepo.noarch.rpm
rpm -i https://linux.cc.iitk.ac.in/mirror/centos/elrepo/elrepo/el7/x86_64/RPMS/yum-plugin-elrepo-7.5.3-1.el7.elrepo.noarch.rpm
rpm -i https://linux.cc.iitk.ac.in/mirror/centos/elrepo/elrepo/el7/x86_64/RPMS/kmod-wireguard-1.0.20220627-1.el7_9.elrepo.x86_64.rpm
reboot
```
#Then copy /root/client-wg0.conf to your client and import it in TunnlTo
