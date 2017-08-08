# MSP::Max/MSP Visual Programming in the Twin Cities
meeting notes and patches from MSP::Max/MSP Visual Programming in the Twin Cities

## 2017-8-5 build a birdcall synth
from [Designing Sound](https://www.amazon.com/Designing-Sound-Press-Andy-Farnell-ebook/dp/B008H5QA04/ref=sr_1_1?ie=UTF8&qid=1502219883&sr=8-1&keywords=designing+sound), derived from [PureData implementation](http://aspress.co.uk/sd/practical28.html)

### Birdcall Synth

#### The patch(es)
* bird
	- syrinx
		+ ringmod
			* crossfade
		+ vposc
	- trachea

#### Parameters
* bp1 - Left bronchus pressure (pulse freq)
* bw1 - Left bronchus impedance (pulse width)
* bp2 - Right bronchus pressure (pulse freq)
* bw2 - Right bronchus impedance (pulse width)
* rm - Ring modulation mix
* mod - FM modulation index
* bf - Syrinx base frequency
* pw - Syrinx pulse width
* tf1 - First trachea formant
* tf2 - Second trachea formant
* amp - Attenuation

### Meeting notes

* Automationism (Pd modular library)
* Darwin Gross - works for cycling74 - Art Music Technology 
	- Mod duo
* Organelle Pd
* Gendy - stochastic synth

#### complaints about max
* no easy way to refactor
