# 3proxycfg

```
wget https://github.com/z3APA3A/3proxy/archive/0.8.12.tar.gz
tar zxf 0.8.12.tar.gz
cd 3proxy-0.8.12
ln -s Makefile.Linux Makefile
sed -ie "s|/usr/local|/usr/local/3proxy|g" Makefile
sed -ie "s|\$(DESTDIR)\$(prefix)/etc/3proxy|\$(DESTDIR)\$(prefix)/etc/|g" Makefile
make && make install
ln -s /usr/local/3proxy/bin/3proxy /usr/local/bin/3proxy
```
