# install-openvpn-ubuntu
```
sudo -s
wget -O - https://swupdate.openvpn.net/repos/repo-public.gpg|apt-key add -
echo "deb http://build.openvpn.net/debian/openvpn/<version> <osrelease> main" > /etc/apt/sources.list.d/openvpn-aptrepo.list
```

Change <version> and <osrelease> accordingly.
  
  <b>Where <version> can be one of</b>

stable: stable releases only - no alphas, betas or RCs</br>
testing: latest releases, including alphas/betas/RCs</br>
release/2.3: OpenVPN 2.3 releases</br>
release/2.4: OpenVPN 2.4 releases, including alphas/betas/RCs</br>
release/2.5: OpenVPN 2.5 releases, including alphas/betas/RCs</br>

  <b>and <osrelease> depends your distribution:</b>

wheezy (Debian 7.x)</br>
jessie (Debian 8.x)</br>
stretch (Debian 9.x)</br>
buster (Debian 10.x)</br>
precise (Ubuntu 12.04)</br>
trusty (Ubuntu 14.04)</br>
xenial (Ubuntu 16.04)</br>
bionic (Ubuntu 18.04)</br>
focal (Ubuntu 20.04)</br>
