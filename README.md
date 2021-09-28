# Awesome-CTS
A curated list of Capture The Signal CTF related stuff

- [CTS home](https://cts.ninja/)
- [CTS Intro](https://github.com/capturethesignal/cts-website/blob/master/bhusa2021/BHArsenal21_cts.pdf), BH2021, USA
- [CTS tools](#CTS-Tools)
  - [CTS client](#CTS-client)
  - [How to run tools](#how-to-run-tools)
  - [CTS server](#CTS-server)
- [Write-ups](#Write-ups)
  - [HWIO2020](#HWIO2020)
  - [HWIO2021](#HWIO2021)
  - [GRUcon 2021](#GRUcon-2021)
  - [Non CTS](#Non-CTS)
- [Software](#Software)
- [Signals](#Signals)
- [Links](#Links)

- - -

## CTS Tools

There are different modes of CTS:
* live, with SDR hardware;
* signals capture via network: simulating SDR hardware via network. In this case you need to install and use CTS client;
* CTS with already recorded signals (iq, wav etc).
 
### CTS client

* [CTS tools](https://github.com/capturethesignal/cts-tools), original, Python2+GNU 3.7
* [CTS tools VM](https://cts.ninja/downloads/)
* [CTS tools](https://github.com/BlackVS/cts-tools), fork, Python3, Tested with Python 3.9
* [CTS Utils](https://github.com/BlackVS/cts-utils), soome additional tools.

### How to run tools
* [Installing tools](cts-tools.md)
* [Receiving signal](cts-get-signal.md)
* [How to run local server](cts-utils.md)
* [How signals are sent from server?](cts-signals.md)

### CTS server
You may run you own server
* [CTS backend](https://github.com/capturethesignal/cts-backend)

## Write-ups

### HWIO2020

* [Digital Security](https://www.digital.security/en/blog/hardweario-capture-signal-write)
* BatchDrake, [part 1](https://batchdrake.github.io/cts/) and [part 2](https://batchdrake.github.io/ctsII/)

### HWIO2021

* [BlackVS](https://github.com/BlackVS/CTFs/tree/master/HWIO2021/CTS)
* [HydraBus](https://hydrabus.com/CTS/HWIO_2021_CTS_Signal5_solution_BVE_10July2021.pdf) + [here](https://hydrabus.com/CTS/)

### GRUcon 2021

TBD

### Non CTS
RF signals challenges from other CTFs
* [Trolling CTF players with gr-paint](https://irrational.net/2019/11/30/trolling-ctf-players-with-gr-paint/)
* [Building a frequency hopping CTF challenge](https://irrational.net/2019/12/02/building-a-frequency-hopping-challenge/)
* [What Lurks Below](https://github.com/mossmann/Writeups/tree/main/Google%20CTF%202020/What%20Lurks%20Below)
* [Signal.dat](https://github.com/leony/CTF/blob/master/Radio%20Frequency/Signal.dat_Writeup.md)
* [Terebeep](https://bolek42.github.io/ctf/2017-PlaidCTF/terebeep/README.html)
* [RF CTF Software Defined Radio Challenges](https://github.com/rfhs/rfhs-wiki/wiki/RF-CTF-SoftwareDefinedRadio-Challenges)
* [Hospital Under Siege 2021: Be still my beating heart](https://ctftime.org/writeup/29131)
* [RF/MOBILE 100](https://gitlab.com/hacklabor/ctf/tmctf-writeup/-/blob/master/RF-Mobile-100/RF-Mobile100.md)


## Software
### CTS used
* [GNU Radio](https://github.com/gnuradio/gnuradio) is a free & open-source software development toolkit that provides signal processing blocks to implement software radios.
* [SigDigger](https://github.com/BatchDrake/SigDigger) is a free digital signal analyzer for GNU/Linux and macOS, designed to extract information of unknown radio signals.
* [Gqrx](https://github.com/gqrx-sdr/gqrx) is an open source software defined radio (SDR) receiver implemented using GNU Radio and the Qt GUI toolkit.
* [URH](https://github.com/jopohl/urh) is a complete suite for wireless protocol investigation with native support for many common Software Defined Radios.
* [inspectrum](https://github.com/miek/inspectrum) is a tool for analysing captured signals, primarily from software-defined radio receivers.
* [Audacity](https://www.audacityteam.org/) is an easy-to-use, multi-track audio editor and recorder for Windows, macOS, GNU/Linux and other operating systems.
* [Swiss Army knife of sound processing programs](http://sox.sourceforge.net/) is a cross-platform (Windows, Linux, MacOS X, etc.) command line utility that can convert various formats of computer audio files in to other formats. It can also apply various effects to these sound files, and, as an added bonus, SoX can play and record audio files on most platforms.


### Other
* [rtl_433](https://github.com/merbanan/rtl_433) is a generic data receiver, mainly for the 433.92 MHz, 868 MHz (SRD), 315 MHz, 345 MHz, and 915 MHz ISM bands.
* [Software By W1HKJ & Associates](http://www.w1hkj.com/)
* [Fast Light Digital Modem Application](https://sourceforge.net/p/fldigi/wiki/Home/)
* [SSTV and HamDRM for Linux](http://users.telenet.be/on4qz/index.html)
* [Ham Radio Software on Centos Linux](http://www.trinityos.com/HAM/CentosDigitalModes/hampacketizing-centos.html#28.qsstv)
* [Dire Wolf](https://github.com/wb2osz/direwolf), Decoded Information from Radio Emissions for Windows Or Linux Fans
* [minimodem ](http://www.whence.com/minimodem/), general-purpose software audio FSK modem  for GNU/Linux systems


## Signals
* [Signal Identification Guide](https://www.sigidwiki.com/wiki/Signal_Identification_Guide)
* [Sights & Sounds](http://www.w1hkj.com/modes/index.htm)
* [Radio Signals Recognition Manual](https://aresvalley.com/artemis/)


### Modulations
* [FSK Demodulation in GNU Radio](https://wirelesspi.com/fsk-demodulation-in-gnu-radio/)
* [Suscan](https://github.com/BatchDrake/suscan), is a realtime DSP processing library. It provides a set of useful abstractions to perform dynamic digital signal analysis and demodulation
* [Manually Decoding ASK PWM Signals from rtl_433 Signal I/Q Sample Files using Universal Radio Hacker](https://github.com/klohner/klohner.github.io/tree/master/SDR/Decoding/Example_2019-01-18)
* [Weak Signal Communication Software](https://physics.princeton.edu//pulsar/K1JT/)
* [wctf-sdr-tools](https://github.com/rfhs/rfctf-sdr-tools), GNU Radio ZMQ Receivers

## Links
### GSM
* [gr-gsm](https://github.com/ptrkrysik/gr-gsm), is a tool for analysing captured signals, primarily from software-defined radio receivers.
* [Osmocom projects](https://osmocom.org/projects)
* [3GPP Message Decoder](https://www.3glteinfo.com/3gpp-message-decoder/), tool to decode GSM, UMTS, LTE, IP messages
 
### DTMF
* [Detect DTMF Tones](http://www.dialabc.com/sound/detect/)
* [DTMF decoder](https://github.com/ribt/dtmf-decoder)
* [DTMF Code](https://www.dcode.fr/dtmf-code)

### Other
* [GNU Radio-Companion Cook Book](https://cdn.hackaday.io/files/1648847054397056/GRC%20Cook%20Book.pdf), Tips, Tricks and Design Patterns
* [RFSec-ToolKit V 2.0](https://github.com/cn0xroot/RFSec-ToolKit), is a collection of Radio Frequency Communication Protocol Hacktools which are from the github platform, and Hacking Tutorial from youtube、blog post, including SDR、2G GSM、3G 、4G LTE 、5G、NFC&RFID、ZigBee and so on.
* [CyberChef - The Cyber Swiss Army Knife](https://gchq.github.io/CyberChef/)
* [dCode](https://www.dcode.fr), is the universal site for decoding messages, cheating on letter games, solving puzzles, geocaches and treasure hunts, etc.
