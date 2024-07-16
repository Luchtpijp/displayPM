# displayPM

A display for sensor.community.
In 2019 the need arose with the Belgian LUCHTPIJP project, to show measured PM values from the 
sensor.community network on a big stand-alone display. A display consisting of 16 LED blocks 
8*8 dotmatrix driven by an ESP8266 WiFi controller, getting the data from internet over WiFi.

Although it was the intention to distribute the sourcecode for the display on github from the beginning, 
COVID intervened, and prevented the rollout of the display. So the whole project was put on hold in the 
first half of 2020, including making the source program public.

At that time the software supported one or two meters with a comparison between the two.
The one meter configuration, intended for an outside meter, had its measurements explained in full text.
The two meter configuration could be a PM meter inside and outside the same home, with the measurements compared & explained 
in full text. Also a configuration with two outside meters was supported, with measurements compared & explained in full text.

In summer 2023, things started to move again, and after a small overhaul & debugging session starting in June, new features 
were implemented. A start was made to show 24 hour peak values, with local storage for calculating it. 

A start was made for monitoring more than the two meters already supported.
The display can now be used as a monitoring device for a maximum of 32 sensors.

More new features will follow:
- Showing results from the DNMS system from sensor.community.
- Showing the results of Telraam, another project here in Belgium, to count traffic according to category of vehicle.
- A web interface for configuring, as the configuration now is through editing the sourcecode & recompiling,
  limiting the rollout by non-programmers.

A new version implementing these new features will be published shortly.
It is so different from this early version, that it will be published under a new name, "SCdisplay".

Software falls under the GNU public Licence.

In no way modify this main branch yourself.
