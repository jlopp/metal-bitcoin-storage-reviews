---
layout: page
title: Cypherwheel Review
permalink: /reviews/cypherwheel/
nowrap: true
---
Cypherwheel can be purchased at <a href="https://cyphersafe.io/product/cypherwheel/">cyphersafe.io</a>. Claims to be:
<ul>
	<li>Fireproof up to 2000°F</li>
	<li>Rust proof</li>
	<li>Waterproof</li>
</ul>

## Setup

This is a unique device for sure; you can see a <a href="https://www.youtube.com/watch?v=T5EjHHiKQwM">video of the setup process here</a>. While you have to slide the tiles along rails, the rail system is very different from the cryptosteel style. The tolerances on Cypherwheel are much lower, which is a good thing in my opinion as it means tiles are less likely to move around. The downside is that it takes a lot more effort to get them into place. Expect 1 to 2 minutes per 4 letter word, meaning it can easily take you an hour to fill the whole wheel. One neat feature is that each word has its own one-way "lock" that can't be undone once you've pushed it into place. One thing I don't think is necessary is the supplied set of tweezers, as they are too large to help slide the tiles to the left - I very quickly switched to using the center punch to push the tiles.

<img src="../../img/devices/cypherwheel_new.jpeg" />

## Heat Stress Test

No visible damage, however the covers are stuck and don't rotate, making it impossible to read the seed. Cyphersafe told me ahead of time that if I encountered problems with the cover, it would be fairly easy to pry it off. I'm going to wait until after the other tests are completed to do that, as I have no reason to believe that the seed phrase has been compromised. When shaking the device I couldn't hear any tiles rattling around, so I don't think they came loose.

<img src="../../img/devices/cypherwheel_hot.jpeg" />
<br/>
<img src="../../img/devices/cypherwheel_heat.jpeg" />

## Corrosion Stress Test

This one yielded another interesting result. You may recall that after the heat test I couldn't rotate the wheels. Well, the acid appears to have dissolved the hub around which they rotated, so both of the wheels came off. Cyphersafe believes that the corrosion resistance of the hub could be improved by switching from 416 to 304 stainless steel.

Oddly enough, while there was some data loss it was somewhat minimal and followed a pattern. About half of the words lost their last letter, but ONLY the last letter. So while this is partial data loss, I wouldn't consider it catastrophic - sufficient data remains that you could write some software to brute force the seed phrase. Cyphersafe also believes that this issue can be resolved by moving the locking divot further away from the tile and switching to 304 stainless steel which will result in the "wall" it creates being thicker and harder to corrode.

<img src="../../img/devices/cypherwheel_acid.jpeg" />

## Crush Stress Test

I was able to get the wheel to bend slightly, a millimeter or so, but not enough to cause additional data loss.

<img src="../../img/devices/cypherwheel_crush1.jpeg" />
<br/>
<img src="../../img/devices/cypherwheel_crush2.jpeg" />
