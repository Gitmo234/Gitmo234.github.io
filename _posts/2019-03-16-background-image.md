---
layout: post
title: Baselining magnetic noise floors
description: "A basic sampling of Magnetic noise"
tags: [B-field]
image:
  background: triangular.png
---

Here is as basic sample modeling the magnetic noise floor of the earth in one general area. On the X axis is the frequency in KHz, and on the Y access is the dB level. 

{% capture images %}
	/images/noiseflooreaston.png
{% endcapture %}
{% include gallery images=images caption="Magnetic Noise Floor" cols=1 %}


```yaml
credit: C Duncan
```

The data is collected via six axis directional sensor and stored in a Midas file, then processed the a Fast Fourier Transform script to produce the plot. This 'noise' is produced by everything from lightning strikes, to the earths magnetic fields and any other device. At the lower end the length of the waves are exceptionally long and may come from anywhere. 


