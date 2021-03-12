---
layout: post
title: Difficult Lessons during Firmware Development
---

<p>Low cost commercial translation of research is not an easy task as the system integration of various hardware and, at-times open-source, software may lead to conflicts. We selected LINX LabVIEW toolkit
so that we could reduce recoding efforts by using our previously written LabVIEW code on the BeagleBone Black. However, this specific toolkit was developed initially as an open-source framework, extensive testing across
processing boards just does not exist. For these reasons, certain port restrictions were not immediately evident when we initially designed the amplifier circuit. Rather than write firmware in a different language such as C, which carries
with it significant compiling issues for the BeagleBone Black, we opted to form temporary hardware connections, which allowed us to bypass the restrictions. These changes allowed us to correctly configure and communicate with the
amplifier in LabVIEW. Our next step is tweaking the configuration of the amplifier and full system bench testing.</p>


<div style="text-align:center"><img src="/photos/hardmods.png" width="600" height="300" /></div>
