# Installl Ubuntu 18.04.1
[install packet follow the book](https://books.google.co.th/books?id=rv1fDwAAQBAJ&pg=PA47&lpg=PA47&dq=practical+contiki+ng&source=bl&ots=6Dw-Ovcnqb&sig=ACfU3U3vpzrCtJ-cmbbWxQPcz8iPeW1B3A&hl=en&sa=X&ved=2ahUKEwjPifzFnb7hAhXXQ30KHW0nC8UQ6AEwBHoECAkQAQ#v=onepage&q=practical%20contiki%20ng&f=false)

[Maybe load this](https://github.com/contiki-os/mspsim)

[Fix error when ant run](https://stackoverflow.com/a/36094658)



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
4. sudo apt-get install ant make gcc gcc-msp430 -y
5. cd /contiki/tools/cooja
6. ant run
