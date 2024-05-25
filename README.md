# International Space University 

## Introduction

## Hardware

### Nooelec NESDR

The [Nooelec NESDR](https://www.nooelec.com/store/sdr/sdr-receivers/nesdr-mini-plus.html) gives us the ability to receiver radio signals from the local area. Examples of such signals are FM radio, aircraft information, and 

The receiver is sensitive to radio signals in the 25 MHz to 1750 MHz range (corresponding to wavelengths between 12 meters and 17 centimeters).

## Software

### SDR++

In order to utilise the power of the Software Defined Radio (SDR) we need to install some software. The first of these is [SDR++](https://www.sdrpp.org/), which is a lightweight way of interacting with the antenna that we have attached to out laptops. Installation should be fairly simple on all platforms (Windows, MacOS, Linux) and full details can be found [here](https://www.sdrpp.org/manual.pdf). This software will give a clear view of what signals are being detected by the SDR, and at which frequency they are found at. To install this software click the "Download Latest Nightly Build" button and select the version corresponding to the make of your laptop.

### Homebrew (MacOS only!)

[Brew](https://brew.sh/) is a package manager from MacOS which allows you to easily install other pieces of software (such as Dump1090 and GNU radio, see below). On MacOS install brew by running `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)` in your terminal.

### Dump1090

To install Dump1090 either:

1. If you are running a MacOS system and you have installed homebrew you can easily install Dump1090 using the command `brew install dump1090-mutability` in your terminal.

2. On Windows...

### GNU Radio

To install GNU radio either:

1. If you are running a MacOS system and you have installed homebrew you can run `brew install gnuradio` in your terminal.

## The Local Radio Environment

### FM Radio

The frequency modulation (FM) radio band is between 88 MHz and 108 MHz. The signals you find in this band have encoded within them nearby radio station transmissions.

### Aircraft Telemetry (ADS-B: Automatic Dependent Surveillance–Broadcast)

Ocurring at 1090 MHz, these transmissions include important safety information from aircraft, including their position, identification, and bearing. This information is automatically broadcast by all aircraft and assists with situational awareness. Also used for communications from e.g. fire departments, police, etc. 









