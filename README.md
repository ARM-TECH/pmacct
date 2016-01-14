[![Build Status](https://travis-ci.org/pmacct/pmacct.svg?branch=master)](https://travis-ci.org/pmacct/pmacct)

DOCUMENTATION
=============

- Online:
  * pmacct wiki: http://wiki.pmacct.net/
  * GitHub: https://github.com/pmacct/pmacct/

- Distribution tarball:
  * ChangeLog: History of features version by version 
  * CONFIG-KEYS: Available configuration directives explained
  * QUICKSTART: Examples, command-lines, quickstart guides
  * FAQS: FAQ document
  * INSTALL: basic installation guide
  * docs/: Miscellaneous internals, UNIX signals, SQL triggers documents 
  * examples/: Sample pmacct and 3rd party tools configurations; sample maps
  * sql/: SQL schemas for various pmacct tables; IPv6 and 64bit counters hacks 

#BUILDING#

- Build GitHub code:
  * git clone -b 1.5.3 https://github.com/pmacct/pmacct.git
  * cd pmacct
  * bin/fix_autotools_timestamps.sh
  * ./configure *[check-out available configure knobs via ./configure --help]* 
  * make
  * make install *[with super-user permission]*
