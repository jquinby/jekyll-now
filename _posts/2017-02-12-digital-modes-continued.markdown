---
layout: post
title: Digital modes, continued
---
So the DIY digital modes cable seems to be a success. I've been working JT65 on 20m and 40m, including one 3000 mile QSO with a station in Alaska. That's my longest DX yet, and pretty amazing on only 5 watts. The full BOM for the interface ran about $20: some stereo plugs, a USB soundcard about the size of my thumb, and a mini-DIN adapter to connect to the radio itself. I already have a serial cable in there for rig control.

There was quite a bit of trial and error at first, and I ended up resoldering the mini DIN plug after I began suspecting that my initial run had introduced a short, confirmed with a multimeter. With that out of the way, it was a little more flailing to get rig control and decoding working at the same time. Oh, and to throw an extra twist in, I was alternating between Windows and Linux VMs for all of this.

Where I finally landed: as much as I want to rely on Linux 100% for my amateur radio stuff, the apps running in Windows (an early version of HRD, WSJT-X, and JT65-HF) have been rock solid, no issues whatsoever. They'll run all day without freezing. I've tried old and new versions of WSJTX on Ubuntu, and it won't run for more than a few minutes without freezing up. Running fldigi ends up cranking the CPU way up. HRD + Digital Master runs fine, though the UI is a bit on the complex side.

Some of this flailing would be from running everything in VMs. I'm eyeballing some dedicated hardware for this.  I also need to see about switching out the quick/dirty choke on the antenna with something a little more substantial. At 5 watts of power, I'm getting moire patterns on monitor. At higher power, the wifi hub craps out and both monitors turn off completely.
