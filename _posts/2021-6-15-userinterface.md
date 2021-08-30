---
layout: post
title: Difficult Lessons during Firmware Development
---

<p align="center">With the BeagleBone Black board (BBB), we were not able to use the native LabVIEW user interface capabilities. Instead, with the use of a LabVIEW web service, we began the development of a graphical user interface (GUI) for our system. For the front-end design, Hypertext Markup Language (HTML), JavaScript (JS), and Cascading Style Sheets (CSS) have been used. The front-end interacts with the BBB through web resources (global variables) that had been defined in LabVIEW.  The front-end was split into a couple of web pages. Each web page has its own HTML, JS, and CSS codes as needed, with specific care given to effective visual feedback mechanisms and general user friendliness. The system has been initially tested using the latest versions of the browsers Google Chrome and Microsoft Edge. Further UI development will continue as we receive feedback during internal and external benchtesting. </p>


<div style="text-align:center"><img src="/photos/UI.png" width="600" /></div>
