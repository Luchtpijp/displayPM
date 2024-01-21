# displayPM

A display for sensor.community.

This is my first project on github, so sorry if not all rules here are respected.
I'm not new to programming, in fact I wrote my first program in Intel 8085 assembler back in 1977, when I was 23.

In 2019 the need arose here in Belgium, with the LUCHTPIJP project, to show measured PM values from the 
sensor.community network on a big stand-alone display to the general public. A display consisting of 
16 LED blocks 8*8 dotmatrix driven by an ESP8266 WiFi controller, getting the data from internet.

Although it was the intention to distribute the sourcecode on github from the beginning, COVID intervened,
and prevented the rollout of the display.
So the whole project was put on hold in the first half of 2020, including making the source program public.

At that time the software supported one meter, or two meters with comparison betwwen the two.

The one meter configuration, intended for an outside meter, had its measurements explained in full text.

The two meter configuration could be a PM meter inside and outside the same home, with the measuments compared & explained 
in full text. Also a configuration with two outside meters was supported, with measurements compared & explained in full text.

In summer 2023, things started to move again, and after a small overhaul & debugging session starting in June, new features 
were implemented. A start was made to show 24 hour peak values, with local storage for calculating it. 

A start was made for monitoring more than the two meters already supported.
The display can now be used as a monitoring device for an unlimited number of sensors, while limiting the messages 
to show only the mean value over aal meter, and the exceptions, such as peak values and meters not working, 
with their identification.

More new features will follow:

- Showing results from the DNMS system (digital noise measuring system) from sensor.community.
- Showing the results of Telraam, another project here in Belgium, to count traffic according to category of vehicle.
- A web interface for configuring, as the configuration now is through editing the sourcecode & recompiling,
  limiting the rollout by non-programmers.

Building & explaining sessions will be held starting starting March 2, 2024 in HackerSpace Brussels, Osseghemstraat 53, 
1060 Molenbeek-Belgium. If you want to participate, please enroll via https://www.meetup.com/nl-NL/civic-lab-brussels/

Extensions & corrections to the sourcecode will be made public through this channel.
Software falls under the GNU public Licence, for use in citizen science projects.
If you modify the main program, please send me a copy of your finished work at rik.drabs@gmail.com,
so that interesting things can get published through this channel.

In no way modify the main branch yourself.
