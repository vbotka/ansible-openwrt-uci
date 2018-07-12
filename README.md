openwrt-uci
===========

[![Build Status](https://travis-ci.org/vbotka/ansible-openwrt-uci.svg?branch=master)](https://travis-ci.org/vbotka/ansible-openwt-uci)

OpenWrt. Set uci config keys. This is just the library module so that other openwrt roles can dependend on it.

REview [https://github.com/lefant/ansible-openwrt] for an example on how it can be used.

Compare: [http://wiki.openwrt.org/doc/uci] and [http://wiki.openwrt.org/doc/techref/uci]


Requirements
------------

Must be kept minimal as this is supposed to run on openwrt embedded
systems. in particular we try get by with plain POSIX shell, using
neither python nor bash in any way. lua could be an option as that
seems to be the openwrt scripting language of choice.


License
-------

[![license](https://img.shields.io/badge/license-BSD-red.svg)](https://www.freebsd.org/doc/en/articles/bsdl-gpl/article.html)


Author Information
------------------

- [Vladimir Botka](https://botka.link)
- Forked from [lefant/ansible-openwrt-uci](https://github.com/lefant/ansible-openwrt-uci) by [Fabian Linzberger](http://e.lefant.net/)


References
----------

[https://github.com/lefant/ansible-openwrt]: https://github.com/lefant/ansible-openwrt
[http://wiki.openwrt.org/doc/uci]: http://wiki.openwrt.org/doc/uci
[http://wiki.openwrt.org/doc/techref/uci]: http://wiki.openwrt.org/doc/techref/uci
[http://e.lefant.net/]: http://e.lefant.net/
