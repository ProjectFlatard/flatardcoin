![Flatardcoin Logo](https://avatars1.githubusercontent.com/u/64924297?s=460&u=dbf4bdaf838e7ac92930917b99acfa0e5051fdc2&v=4)
# Flatardcoin
Flatardcoin is decentralized p2p payment system with close to zero transaction fees and 100% anonimity to support Flat Earth community.

Flatardcoin integration/staging tree
================================

https://www.flatardcoin.com

Copyright (c) 2009 Bitcoin Developers

Copyright (c) 2011 Litecoin Developers

Copyright (c) 2020 Flatardcoin Developers

What is Flatardcoin?
----------------

Flatardcoin is p2p lightening fast payment system with close to zero transaction fee and complete anonymity for Flat Earther Community and all cryptocoin users. It's a lite version of Bitcoin using scrypt as a proof-of-work algorithm with some modifications in code.
 - 1000 coins block reward
 - 10 coins block reward for 1st month
 - 50 coins block reward for 2nd and theird month
 - 100 coins block reward for 3-6 months
 - 500 coins block reward for 6-9 months
 - 1000 coins block reward for 9 months - 4 years
 - Block reward halves every 210240 blocks (approximately every 4 year)
 - 10 minutes block timespan
 - 1MB block soft-limit
 - 50MB block hard-limit
 - 0.00000019 starting difficulty
 - 144 blocks to reset difficulty (approximately every 24hrs)
 - ~10000000000 maximum supply of coins
 - ~100000220 pre-mine coins for bounty and rewards
 - last pre-mine block #23

The rest is the same as Bitcoin.

For more information, as well as an immediately useable, binary version of
the Flatardcoin client sofware, see https://www.flatardcoin.com or http://www.flatardcoin.com.

License
-------

Flatardcoin is released under the terms of the MIT license. See `COPYING` for more
information https://flatardcoin.mit-license.org/ or see http://opensource.org/licenses/MIT.

Development process
-------------------

Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

If it is a simple/trivial/non-controversial change, then one of the Flatardcoin
development team members simply pulls it.

If it is a *more complicated or potentially controversial* change, then the patch
submitter will be asked to start a discussion with the devs and community.

The patch will be accepted if there is broad consensus that it is a good thing.
Developers should expect to rework and resubmit patches if the code doesn't
match the project's coding conventions (see `doc/coding.txt`) or are
controversial.

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/flatardcoin-project/flatardcoin/tags) are created
regularly to indicate new official, stable release versions of Flatardcoin.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test. Please be patient and help out, and
remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write unit tests for new code, and to
submit new unit tests for old code.

Unit tests for the core code are in `src/test/`. To compile and run them:

    cd src; make -f makefile.unix test

Unit tests for the GUI code are in `src/qt/test/`. To compile and run them:

    qmake BITCOIN_QT_TEST=1 -o Makefile.test bitcoin-qt.pro
    make -f Makefile.test
    ./flatardcoin-qt_test




