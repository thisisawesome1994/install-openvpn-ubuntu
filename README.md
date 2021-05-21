# install-openvpn-ubuntu
```
sudo -s
wget -O - https://swupdate.openvpn.net/repos/repo-public.gpg|apt-key add -
echo "deb http://build.openvpn.net/debian/openvpn/<version> <osrelease> main" > /etc/apt/sources.list.d/openvpn-aptrepo.list
```

Change <version> and <osrelease> accordingly.
  
  <b>Where <version> can be one of</b>

stable: stable releases only - no alphas, betas or RCs
testing: latest releases, including alphas/betas/RCs
release/2.3: OpenVPN 2.3 releases
release/2.4: OpenVPN 2.4 releases, including alphas/betas/RCs
release/2.5: OpenVPN 2.5 releases, including alphas/betas/RCs

    <b>and <osrelease> depends your distribution:</b>

wheezy (Debian 7.x)
jessie (Debian 8.x)
stretch (Debian 9.x)
buster (Debian 10.x)
precise (Ubuntu 12.04)
trusty (Ubuntu 14.04)
xenial (Ubuntu 16.04)
bionic (Ubuntu 18.04)
focal (Ubuntu 20.04)
