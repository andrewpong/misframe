---
title: Ampless
date: "2012-09-03"
url: /ampless
---


<img src="https://media.tumblr.com/4868e27c915ebd069f9ca55ce9cca599/tumblr_inline_mm3t2lduUJ1qz4rgp.jpg" alt="image" /><div class="caption">Attribution: <a href="https://www.flickr.com/photos/raaphorst/3554002238/">Marco Raaphorst</a></div>

<h2>Introduction</h2>
<p>For years I had a beginner’s electric guitar amp. After a while I wasn’t satisfied with the sound that I was getting from it. After looking at (and listening to) products like Native Instrument’s Guitar Rig I decided to transition to a digital rig. Why not just get a better amp? Good amps are expensive! Tube amps sound the best with their warmth and rich distortion, but they need to be cranked to a high volume. I couldn’t have anything too loud in my small bedroom.</p>

<h2>Signal Chain</h2>
![](https://media.tumblr.com/050f643b9a433bf95726f4f1e09f7453/tumblr_inline_mm3t3t4jJ81qz4rgp.png)

<p>This is what people probably care about the most. The iMic is required since the input port on my Macbook doesn’t have microphone-level input. For a while I didn’t use a distortion pedal. I plugged my guitar straight into my computer and tried to introduce the harmonic distortion digitally. That was a whole new challenge.</p>

<h2>Distortion pedals</h2>
<p>I don’t really have a high-fiedelity setup. Simply put, the amount of noise that is introduced after the iMic is too high to have decent distortion. The audio gets even worse when I apply noise gates and tweak the EQ levels. Eventually, I just grabbed a Satchurator and it’s been providing awesome harmonic distortion.</p>

<h2>Simulation</h2>
<p>Guitar amps are essentially a preamp, power amp, and the speakers. The power amp drives the speakers—it has little effect on the audio itself. I can forget about simulating that. The preamp and the speakers affect the sound for the most part. You can probably just do some EQ magic for the preamp stuff. It isn’t too complicated. As for the speaker cabinet, it’s also very easy to simulate. All you have to do is apply a speaker cabinet impulse to your source audio.</p>

<h2>Convolution Reverb</h2>
<p>The speaker cabinet simulation is <em>the most</em> important part of the entire system. What I essentially do is simulate my guitar signal going through a speaker cabinet and recorded with a microphone (like an SM57). It’s a really neat application of convolution reverb. We can take some sort of audio signal and modify it so it sounds like it was played somewhere else. If we have the impulse response of a speaker cabinet, we can apply it to any sound and it would sound as if it came out of the speaker cabinet.</p>

