#####Bark Tracker
This sketch listens to a sound sensor on Port A0, analyzes any sound that it hears, and then logs the sound level and time to a Phant.io data feed if the sound is over a certain threshold.

The JS file also converts the server timestamp to a human-readable format with Moment and Moment.timezone.

- Links
	- [data.sparkfun Phant.io stream link](https://data.sparkfun.com/streams/yA8Llvj4MXtdr3OmZ2VG)
	- [analog.io chart link](http://analog.io/#/s29)
	
- Tech
	- Node.js
	- MRAA
	- Forever
	- Request
	- Moment
	- Moment.timezone