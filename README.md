# Qucs library set for Russian components

## Description

This repo contains library set for Qucs http://qucs.sourceforge.net and Qucs-S https://ra3xdh.github.io circuit simulators. The foolowing components are presented:

 - `AudioIC.lib` different audio amplifier ICs like LM386, TDA2030 etc.
 - `BJT_exteneded.lib` extended BJT library
 - `Diodes_Schottky` Schottky diodes models
 - `RusDiodes.lib` Russian diodes and Zener diodes
 - `RusBJT_Part1.lib` `RusBJT_Part2.lib` Russian bipolar transistors
 - `RusJFET.lib` Russian junction field-effect transistors (JFETs)
 - `RusComparator.lib` K521SA3 comparator
 - `OpAmp_140.lib` 140-series Russian opamps
 - `OpAmps_544.lib` 544-series Russian opamps
 - `OpAmps.lib` different popular opamps
 - `Comparator.lib` LM339 comparator and others
 - `Tubes.lib` different vacuum tubes for audio amplifiers (models provided by @olegkapitonov ). This library works with Qucs-S only
 - `BF998.lib` BF998 and BF998R double gate MOSFET. This library works with Qucs-S only
 - `PhotovoltaicRelays.lib` Photovoltaic relays. This library works with Qucs-S only
 - `Crystals.lib` -- Quartz crystals backported from PSpice; this library doesn't reflect the measurements and cannot be used for filters design; see https://github.com/ra3xdh/qucs_s/issues/1037

## Installation

To install libraries copy them all into system Qucs library directory. For example to the `$QUCSDIR/share/qucs/library` on Linux. `$QUCSDIR` is the Qucs installation root (for example `/usr/local`). For Qucs-S default libraries location is `/usr/share/qucs_s/library`. If you are using AppImage or have no root access to your system, copy the libraries to the user libraries directory `$HOME/.qucs/user_lib`

Regards, 
Vadim Kuznetsov

