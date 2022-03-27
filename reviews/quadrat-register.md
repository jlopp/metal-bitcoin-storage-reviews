---
layout: page
title: Quadrat Register Review
permalink: /reviews/quadrat-register/
nowrap: true
---
Quadrat Register P + Protective Tube P can be purchased at <a href="https://qreg.tech/">q-reg.tech</a>. Made of stainless 304 grade german steel; as far as claims I only see the web site state that it's secure against x-ray spying.

## Setup

This one's an oddball, as it came with no actual assembly instructions. There were several pages of instructions about setting up the "two factor" encoding scheme, but none about actually putting the pieces of the device together. Thankfully it was fairly intuitive; I figured out pretty quickly that each tile was notched so that you could keep them all on the rail in the correct orientation. However, I was confused as to why there were only 6 spacer tiles; I guess you could just use a blank (unpunched) tile as a spacer. But then as I neared the end I realized that if you want to store a 24 word seed phrase with the first 4 characters of each word as a separate tile, you won't have room to use spacers and you won't be able to read the tiles without removing them from the rail. However, this problem could be solved by just assigning an entire BIP39 word to a given tile encoding. Given such a setup you could potentially store 4 complete 24 word seed phrases in this one device.

<img src="../../img/devices/quadrat_register_new.jpeg" />

## Heat Stress Test

The tube opened effortlessly and none of the tiles were out of place or had lost any data.

<img src="../../img/devices/quadrat_register_hot.jpeg" />
<br/>
<img src="../../img/devices/quadrat_register_heat.jpeg" />

## Corrosion Stress Test

No acid entered the tube; even if it had I would expect no data loss.

<img src="../../img/devices/quadrat_register_acid.jpeg" />

## Crush Stress Test

Performed admirably - the only result from 20 tons of force being applied was a tiny mark on the tube. This is the best result by any device with this crush test.

<img src="../../img/devices/quadrat_register_crush.jpeg" />
