
The Contiki Operating System
============================

[![Build Status](https://travis-ci.org/contiki-os/contiki.svg?branch=master)](https://travis-ci.org/contiki-os/contiki/branches)

Contiki is an open source operating system that runs on tiny low-power
microcontrollers and makes it possible to develop applications that
make efficient use of the hardware while providing standardized
low-power wireless communication for a range of hardware platforms.

Contiki is used in numerous commercial and non-commercial systems,
such as city sound monitoring, street lights, networked electrical
power meters, industrial monitoring, radiation monitoring,
construction site monitoring, alarm systems, remote house monitoring,
and so on.

For more information, see the Contiki website:

[http://contiki-os.org](http://contiki-os.org)



How to install?(tested ubuntu 18.04.1)
1. git clone https://github.com/PkLearning/contiki.git
2. git submodule update --init
3. sudo apt-get update & sudo apt-get upgrade -y
4. sudo apt-get install ant -y
5. sudo apt-get install make -y
6. sudo apt-get install gcc -y
7. sudo apt-get install gcc-msp430 -y
8. cd /contiki/tools/cooja
9. ant run
