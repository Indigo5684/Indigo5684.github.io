---
title:  "Is WiFi Getting Worse? Electromagnetic Pollution, and Why It Matters"
---

"My cell service just isn't what it was five years ago."

If this quote rings true, you're not alone. Though our digital infrastructure has been growing faster and faster, so has the amount of people utilizing it, leading to an overall slower experience. Sometimes, though, the solution isn't to buy a faster phone plan. Sometimes, the solution is to get everyone else to just *shut up*.

The internet is not an infinite resource. This sounds counter-intuitive at first - can't you simply buy a faster modem? But no, at some point, even the fastest equipment will bottleneck against the internet's **frequency allocation**. At it's most fundamental level, wireless internet is simply a radio communicator. A radio transciever (a reciever and transmitter combo) is located in your phone, and its counterpart in your modem. And like any other radio, it must be dialed to the proper frequency.

Intuitively, this frequency would be determined by what network you select, with each network operating on a separate frequency to avoid interference from eachother. Yet this is not the case. All modern WiFi transcievers are pre-dialed to select frequencies ([**2.4GHz** and **5GHz**](https://www.intel.com/content/www/us/en/products/docs/wireless/2-4-vs-5ghz.html) in the United States) by the manufacturer, shared by *all* networks. As a consequence, someone streaming high-definition video within range of your WiFi will slow your devices down respectively, even if they're on a completely different network.

And nowdays, with the exponential increase in wireless devices, from laptops to lightbulbs, we are increasingly utilizing the limited frequency space availible to us.

---

![Sample Kitten](https://loremflickr.com/700/500)

> Alt text: A picture of a waterfall display, which showcases the signal level across a frequency band. Note the noise floor at **measurement**.

This cat will be replaced with an actual picture

---

To fully investigate radio pollution, we must first distinguish the two types of pollution that are applicable to us: a rising **noise floor**, and selective **interference**. In radio communications, the noise floor is the background data collected by an antenna in the absence of an intentional signal. On an FM radio, the noise floor is obvious: it is the static heard when slightly off-frequency, or when tuned to a frequency without a station. Conversely, interference is the presence of an unwantetd or unintelligable signal above the noise floor, distorting or invalidating data in transit.

However, tracking down the sources has proved to be difficult. Recent [studies](https://www.youtube.com/watch?v=dQw4w9WgXcQ) (TODO ContempNoiseLevels) have found that the noise floor and rates of interference are elevated in populated areas, to the point where communications systems must be  designed around the higher ambient noise, yet have failed to list a specific noise source. For example, one [study](https://www.youtube.com/watch?v=dQw4w9WgXcQ) (TODO Chiaraviglio_Bianchi_Blefari-) investigated cellular towers, with the theory that the increase in noise is caused by compounding signals from far-off cellular towers, too quiet for actual data transfer but not quite silent. Additionally, the study investiaged power lines, as alternating current (in)famously oscillates at 50/60Hz, and altternating electric currents create radio waves. However, while there was an increase in ambient noise on the target frequencies, it was not to the point of breaching regularions.

Interference, on the other hand, is far, far easier to track. Among the hobbyist community, finding hidden transmitters has become a game/contest of sort, known as "foxhunting", with dedicated [hardware](https://byonics.com/foxhunt) for both the searchers and hiders. However, often don't have to deal with interference due to legislature. The Federal Communications Commission (FCC), who enforce radio regulaations in the United States, has strict regulations on permissable out-of-band emissions, and any intentional jamming of signals is treated [harshly](https://www.fcc.gov/general/jammer-enforcement).

Yet there is one class of emitters that one in place, cannot feasibly be removed: satellites. 

---

To end things off, 