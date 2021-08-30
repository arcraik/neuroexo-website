---
layout: post
title: Difficult Lessons during Firmware Development
---

<p align="justify">Moving to the BeagleBone processing unit with the LINX LabVIEW toolkit is an important step towards making the NeuroExo cost effective, but it does not come without its set of challenges. One such challenge is in obtaining a constant sampling frequency. This is crucial for EEG signal analysis as the processing pipeline requires spectral (or frequency) analysis. However, with the LINX LabVIEW toolkit, the SPI communication tools (the protocol designed for our amplifier) require the system to send data to receive data. While the amplifier was designed to send signals at a constant sampling frequency, it requires a single command, rather than a command for every set of EEG samples. To achieve a constant sampling frequency, we instead sample at a varying rate and then interpolate the time points we need for our application. </p>


<div style="text-align:center"><img src="/photos/hardmods.png" width="600" height="300" /></div>
