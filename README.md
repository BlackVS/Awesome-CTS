# Awesome-CTS
A curated list of Capture The Signal CTF related stuff

- [CTS home](https://cts.ninja/)
- [CTS Intro](https://github.com/capturethesignal/cts-website/blob/master/bhusa2021/BHArsenal21_cts.pdf), BH2021, USA
- [CTS tools](#CTS-Tools)
  - [CTS client](#CTS-client)
  - [CTS server](#CTS-server)
- [Write-ups](#Write-ups)
  - [HWIO2020](#HWIO2020)
  - [HWIO2021](#HWIO2021)
  - [GRUcon 2021](#GRUcon-2021)
  - [Non CTS](#Non_CTS)
- [Software](#Software)
- [Signals](#Signals)
- [Links](#Links)

- - -

## CTS Tools

There are different modes of CTS:
* live, with SDR hardware;
* CTS with already recorded signals (iq, wav etc);
* capture via netwroks: simulating SDR hardware via network. In the last case you nedd install and use CTS client
 
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
* [SiDigger](https://github.com/BatchDrake/SigDigger)
* [Audacity](https://www.audacityteam.org/)
* [Swiss Army knife of sound processing programs](http://sox.sourceforge.net/)
* [gr-gsm](https://github.com/ptrkrysik/gr-gsm)

### Other
* [rtl_433](https://github.com/merbanan/rtl_433), is a generic data receiver, mainly for the 433.92 MHz, 868 MHz (SRD), 315 MHz, 345 MHz, and 915 MHz ISM bands.
* [Software By W1HKJ & Associates](http://www.w1hkj.com/)
* [Fast Light Digital Modem Application](https://sourceforge.net/p/fldigi/wiki/Home/)
* [SSTV and HamDRM for Linux](http://users.telenet.be/on4qz/index.html)
* [Ham Radio Software on Centos Linux](http://www.trinityos.com/HAM/CentosDigitalModes/hampacketizing-centos.html#28.qsstv)
* [Dire Wolf](https://github.com/wb2osz/direwolf), Decoded Information from Radio Emissions for Windows Or Linux Fans
* [minimodem ](http://www.whence.com/minimodem/), general-purpose software audio FSK modem  for GNU/Linux systems

## Signals
* [Signal Identification Guide](https://www.sigidwiki.com/wiki/Signal_Identification_Guide)
* [Sights & Sounds](http://www.w1hkj.com/modes/index.htm)

### Modulations
* [FSK Demodulation in GNU Radio](https://wirelesspi.com/fsk-demodulation-in-gnu-radio/)
* [Suscan](https://github.com/BatchDrake/suscan), is a realtime DSP processing library. It provides a set of useful abstractions to perform dynamic digital signal analysis and demodulation
* [Manually Decoding ASK PWM Signals from rtl_433 Signal I/Q Sample Files using Universal Radio Hacker](https://github.com/klohner/klohner.github.io/tree/master/SDR/Decoding/Example_2019-01-18)
* [Weak Signal Communication Software](https://physics.princeton.edu//pulsar/K1JT/)
* [wctf-sdr-tools](https://github.com/rfhs/rfctf-sdr-tools), GNU Radio ZMQ Receivers

## Links
### GSM
* [gr-gsm](https://github.com/ptrkrysik/gr-gsm)
* [Osmocom projects](https://osmocom.org/projects)
* [3GPP Message Decoder](https://www.3glteinfo.com/3gpp-message-decoder/), tool to decode GSM, UMTS, LTE, IP messages

### Other
[GNU Radio-Companion Cook Book](https://cdn.hackaday.io/files/1648847054397056/GRC%20Cook%20Book.pdf), Tips, Tricks and Design Patterns
