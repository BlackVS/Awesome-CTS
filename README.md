# Awesome-CTS
A curated list of Capture The Signal CTF related stuff

- [CTS home](https://cts.ninja/)
- [CTS Intro](https://github.com/capturethesignal/cts-website/blob/master/bhusa2021/BHArsenal21_cts.pdf), BH2021, USA
- [CTS tools](#CTS-Tools)
- [CTS client](#CTS-client)
- [CTS server](#CTS-server)
- [Write-ups](#Write-ups)
  - [HWIO2021](#HWIO2021)

- - -

## CTS Tools
There are different modes of CTS:
- live, with SDR hardware;
- CTS with already recodred \*.iq signals;
- capture via netwroks: simulating SDR hardware via network. In the last case you nedd install and use CTS client
 
### CTS client

- [CTS tools](https://github.com/capturethesignal/cts-tools), original, Python2+GNU 3.7
- [CTS tools VM](https://cts.ninja/downloads/)
- [CTS tools](https://github.com/BlackVS/cts-tools), fork, Python3, Tested with Python 3.9
- [CTS Utils](https://github.com/BlackVS/cts-utils), soome additional tools.

### How to run tools
- [Installing tools](cts-tools.md)
- [Receiving signal](cts-get-signal.md)
- [How to run local server](cts-utils.md)
- [How signals are sent from server?](cts-signals.md)

### CTS server
You may run you own server
- [CTS backend](https://github.com/capturethesignal/cts-backend)

## Write-ups

### HWIO201

- [BlackVS](https://github.com/BlackVS/CTFs/tree/master/HWIO2021/CTS)
- [HydraBus](https://hydrabus.com/CTS/HWIO_2021_CTS_Signal5_solution_BVE_10July2021.pdf)
