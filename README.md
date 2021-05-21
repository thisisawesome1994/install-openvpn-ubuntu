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

Source: https://community.openvpn.net/openvpn/wiki/OpenvpnSoftwareRepos?__cf_chl_jschl_tk__=397c3e7117179ba74d0ab04e82ff1a1c658bc035-1621633378-0-AVXYMmMUQ4u8Z7fuXErQGLzKt5UPOgN8RZ5HJu-wZiKeOqvqbcm-eMEi9dT5yKhYhaz4JMdx4W4O9Ei9eHbp40UlG9yD2JhevPovVyHDJitCJ-cFIJQ1FtLuGQDrr7sCqDIf2PI5KOQEGk-l-2dZwFoY16ERtPBGHgHkCXThtDl8ztltpeWbWLfw5LCTzjkZMWwQtryykgnuEaFZPN-65XNCDy__TnKCr8YZO0AiRZORPTXCPBPA7tenT9LKaTjAW5Px3wGKfXIOXbuLnRwT1KLEfaMYnADOt80-h4YKTPiJEfj7GzHmCu4u4rfAM-9hHWa6l0_V0TmJllJxcAlAyBAPqr5Cs2JTv81Q31WeAtv43ON-r2iy8GeIPWrQZpjmmh7V5Jh5zKYzBHwfoNmg5R7h_jqJCeDEsM2t__K2U-ki6Q4bXQe150zG1YkF13PnZQ</br>
