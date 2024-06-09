---
title: "A Desktop Monitor For 2025"
date: 2024-06-08T23:00:00-04:00
draft: false
tags:
- monitors
resources:
- src: "images/*.jpg"
---

- Discuss on [Hacker News](https://news.ycombinator.com/item?id=40627264)

_This post is an extension of a [rant
thread](https://hachyderm.io/@ddl/112584091556177153)[^0] I wrote recently._

All I want is a monitor that looks good next to my 14" M1 MacBook Pro. Is that
too much to ask? Apple has taken the quality of MacBook displays seriously for
as long as I can remember, which for me goes back to the first unibody designs.
Soon after that, Apple was the first company brave enough to ship a notebook
computer with a truly dense display, and then a few months ago, Apple introduced
the first production tandem OLED display in the M4 iPad Pro, with the purpose of
solving the OLED brightness issue. It has a new set of flaws and tradeoffs, as
do all display technologies, but it serves as clear evidence of Apple's
commitment to good displays. Despite the obvious passion engineers at Apple have
for display technology, they have not demonstrated the same commitment in their
desktop displays, or at least been unable to do so for corporate strategy
reasons. What I want is an external display that stands shoulder to shoulder
with the MacBook it's connected to. For me, Apple made all of the right trade
offs in the MacBook Pro display, and so I use it as my benchmark for the ideal
desktop monitor. I know it is possible with today's display technologies. I know
I'm not the only person who cares about this stuff, and I know I'm not the only
one willing to pay for it. Hear me out.

# My demands

An ideal monitor meets **ALL** of these requirements, or comes very close:

```
- 27-inch (16:9) or ultrawide equivalent
- 10-bit, glossy
- >= 160 ppi, (i.e., 4K or greater)
- 120Hz or 144Hz, more is overkill
- Better than average office display response times
- 400 nits BARE minimum, 600 nits (actual)
- Looks like a MacBook display side-by-side
- Not more expensive than a Studio Display
```

I don't feel like my use cases are weird: programming, web browsing, some
videos, some photo editing, occasional gaming on weekends. I work from home as a
programmer. MacBooks are comfortable programming machines for millions of
developers. The recipe works.

For reference, these are the display specifications of a 14" M3 MacBook Pro
(2023).

- 14.2-inch optically bonded glass display
- 3024 by 1964 pixels (254 ppi)
- 10-bit IPS, mini-LED backlight
- 120Hz (with VRR)
- SDR: 600 nits peak brightness
- HDR: 1000 nits sustained, 1600 nits peak brightness

The primary technical trade off in the MacBook Pro is the very poor response
times, which is strange for a high refresh rate monitor. It's most noticeable in
gaming, admittedly rare for me on a MacBook. There may have been some
improvements since the first model, which is slightly less bright than current
models, but not major. For the things I do on it, it feels so much better than a
60Hz display with better response times. 60Hz displays almost feel broken to me
now.

## Size and resolution

These are the most common large monitor resolutions you can buy today:

- 4K at 32-inch (140 ppi)
- 4K at 27-inch (160 ppi)
- 1440p at 27-inch (108 ppi)

Many 1080p displays are still sold, for some reason.

Apple and LG have made a few exceptional high DPI displays as well:

- 5K at 27-inch (218 ppi) (Studio Display, LG Ultrafine, 5K iMac)
- 6K at 32-inch (218 ppi) (Pro Display XDR)
- 4.5K at 24-inch (218 ppi)

Mobile displays come in so many more exotic resolutions and densities. Why not
desktop displays? Ultrawide monitors generally have low refresh rates and the
same pixel pitch as 16:9 panels. I imagine it's unlikely that my requirements
will be met by an ultrawide, because of bandwidth issues. I don't mind using
them though.


## Refresh rate

If you're reading this post, there's a good chance you have read Dan Luu's
popular post on [input lag](https://danluu.com/input-lag/)[^1]. In it he shows
that all modern computers have slower response times than old 8-bit computers
from the 70s and 80s. Only recently, with the popularity of high refresh rate
monitors meant for gaming, has the gap started to close. I highly recommend
reading it to see where all of the places input lag is introduced in modern
computing.

Dan's post is a little out of date at this point, as it does not include recent
OLED monitors with even higher refresh rates and much, much lower pixel response
times. It also does not include tests for Apple's 120Hz "ProMotion" displays
found in recent Macs. I suspect they would not fare well in raw end-to-end
latency in all scenarios, though. 

It seems high refresh rate monitors are mostly targeted at the gaming market.
The only exceptions I am aware of are MacBook displays and the recently
announced Framework 120Hz high density [upgrade
panel](https://frame.work/ca/en/products/display-kit?v=FRANJF0001)[^2]. Any
other panel with a refresh rate above 75Hz (which is a barely noticeable
improvement over 60Hz, by the way) is strictly marketed to gamers, and makes
compromises in other areas. 120Hz is a fantastic jump over 60Hz. 144Hz only
feels slightly better. 240Hz is noticeably smoother than 120Hz, but only in
gaming. I haven't personally tried anything faster than that, so I'll settle for
120Hz as the baseline for the ideal monitor. 

## Brightness, contrast, and colour

400 nits, bare minimum. Blacks appear darker and colours appear more vibrant on
glossy displays, preferably behind actual glass. That's all. IPS is really good
and can get really bright. OLED panels struggle with brightness, TN panels are
bad at everything, and VA panels have awful contrast. Apple made the only choice
they could for their bigger displays.

## Desktop utility

Dell is excellent for this with their office monitors. Most of them include a
functional KVM hub with plenty of USB ports, and sometimes even an Ethernet port
that keeps both machines attached to the monitor connected to the network at the
same time, no matter which one is active. Like Apple, Dell monitors always have
a built-in power supply. It's really nice for cable management to get that bulky
brick off the floor or cable tray.

Power delivery over USB-C is a must for MacBooks, and it's great to have in a
pinch to charge other devices.

KVM is tricky to do well, and I'm pretty sure that's why Apple decided not to
include more than a single input in the Studio Display and Pro Display XDR.
Cheeky. A good solution is going to involve software on all connected machines,
and the main reason for me to use KVM is to switch between my work Mac, personal
Mac, and desktop PC. The Macs I switch with the cable, but I'm not willing to
crawl under my desk to plug and unplug my monitor.

# Existing contenders

Here's what I've tried and ruled out, so far. There are a lot of monitors out
there, most of them matte. As you'll see in the Dell section, reviews from sites
like RTINGS have limited utility for predicting how the monitor will actually
look on my desk.

## Apple Studio Display

It's brutally expensive, it's beautiful, it's quite bright, and it has bad deal
breakers. It only has a single monitor input, and it only goes up to 60Hz. Those
together are disqualifying. If it went up to 120Hz, I'd have put up with
swapping cables or an external KVM switcher. I believe it also has pretty bad
input lag. I don't have much else to say besides that I hope Apple refreshes it
some day soon with a faster panel. 5K would be really nice to have.

## Dough Spectrum One

**DO NOT BUY the monitor described in this section from Dough (formerly Eve).
The company is as sketchy as they get. They have an
[ongoing](https://en.wikipedia.org/wiki/Eve_V)[^3] 
[history](https://www.reddit.com/r/evev/)[^4] of [fraudulent
business practices](https://www.doughscam.com/)[^5]. In my PERSONAL EXPERIENCE, I
was not able to make warranty claims for the two monitors I bought during the 1
year warranty period. PLEASE DO NOT SPEND YOUR MONEY ON DOUGH PRODUCTS. I deeply
regret doing so myself.**

I feel the need for such a harsh warning up front because, on paper, and when it
decides to work, the Dough Spectrum is somehow still the best answer to my
demands currently on the market, AND it's priced competitively. I am reluctant
to mention the price or even link to the product listing here because of the
risk that I may sell a monitor for them, which is something I truly cannot
endorse.

Here are the specs for the ES07DCA I current have on my desk. The product
currently sold as the Dough Spectrum One is essentially identical. They are not
transparent about the differences, if there are any. The constant rebrandings
and product relabelings should be a bright red flag to stay away from this
company on their own.

- Orignally sold as the EVE Spectrum (Glossy)
- 27" IPS panel
- 3840 by 2160 (4K)
- 144Hz refresh rate
- 500 nits (advertised, more like 450 nits in practice)
- HDMI, DisplayPort, and USB-C inputs
- USB-C PD (100 watt)
- USB-B 3.1 upstream

It's a great looking monitor. The black enclosure is solid and sleek. The bezels
are only 5mm on the top and sides, around 10mm on the bottom. It has a standard
100mm VESA mount, which is handy, because the (also very solid stand) is sold
separately. Sounding good so far, right?

As mentioned in the warning, I bought two of these monitors together in 2022,
which I ended up waiting 13 months for. The wait was so long that I asked around
the 10 month mark to cancel my order, which they did. However I did not get a
refund. I should have immediately gone for a chargeback, which was a big mistake
on my part. By the time I realized I was not going to get a refund, it was too
late to do a chargeback through my bank because more than a year has elapsed.
After being lied to for months by Eve support about the status of my refund, I
requested they re-open my order, which to their credit, I did eventually get a
few months later.

The first monitor had half of its backlight fail after two weeks. I was unable
to get a return label, nor did I trust that if I shipped it back to them that I
would get a refund given the recent experience of asking for a refund. It sat in
the box for a year and I sold it very cheap locally to someone who wanted to try
to repair it. I don't know if they were successful, so I consider it to be
e-waste.

The second monitor is flaky, but works most of the time. It has a black dead
pixel in the upper middle section of the display. The edges of the screen have
noticeable backlight bleed, especially at the bottom. This has worsened over
time. The most frustrating issue is random display connectivity drops, which
seem to occur with long screen-on time on warmer days, always during an
important Zoom call. Summers here regularly hit 30 °C (86 °F), which is hot,
sure, but really not that hot. I also have a small air conditioner, so we're
talking ambient room temps around 25 °C at worst. Nothing crazy at all. There
have been other times that I can't associate with temperature that the monitor
doesn't show an image when connected to any input. The only fix for that is not
to power the monitor off, no, but to _completely unplug from the wall_ for about
a minute so the capacitors drain. It usually works after that stupid process.

It also happens to take a really long time to wake from sleep, which keeps me on
my toes wondering if it finally died like the first one. It's also very slow to
switch between KVM inputs. When powering on cold, it takes a solid 45 seconds to
get a picture. Ridiculous.

If a reputable brand like LG or Dell sold a monitor with the same LG panel Dough
uses in the Spectrum I would not have written this post. I do not know why Dough
is the only company that makes a bright, glossy IPS, 144Hz monitor. I would love
to have the opportunity to ask product managers at big monitor manufacturers why
this cannot be done, because I really do not get it.

Reminder, **PLEASE DO NOT BUY DOUGH PRODUCTS.**

## Gamer OLED monitors

They're really expensive and they just don't get bright enough. Most top out
around 250 nits. Even though they usually come with a glossy finish, they do not
look good next to a MacBook, even after a lot of calibration.

I recently bought and returned a Dell Alienware 32” 4K QD-OLED AW3225QF. I
figured the high price and semi-glossy OLED panel would make up for it.

For the price it has too many compromises. The low peak brightness makes it look
washed out next to a MacBook Pro and my Dough Spectrum (when it works). The
input lag is the lowest I have ever experienced on any monitor, which is what
it’s meant for. Its 240Hz feels fantastic, but it could only do 120Hz when
plugged into my MacBook. My Dough Spectrum can do 144Hz over USB-C, for some
reason. I also really do not like the anxiety of pixel burn in. Every few
minutes, this particular Dell monitor shifts the display contents by a pixel in
a random direction. It's jarring when you're staring at code, or doing pixel
peeping in Figma. It's a compromise, like increased input lag and ghosting is on
a MacBook.

RTINGS rates it very highly for creators, so I guess it’s technically very
colour accurate. It's just really dim, almost like the displays Lenovo used to
[put in ThinkPads](/posts/thinkpad-2020)[^6]. To my eye, I was shocked at how
bad it looked. It felt more like VA or TN panel. It was washed out. It didn't
feel vibrant like the other experiences I have with OLED screens, like LG's
awesome OLED TVs, or my iPhone. It was a really disappointing experience. I'm
really grateful I could trust that Dell would accept a return, which was easy. I
didn't have to speak to anybody on the phone, no email volleys, just a Purolator
return label and a quick trip to the depot. You will not get this experience
with Dough past the short return windows of their resellers like Newegg and B&H.

## Conclusion

Better is possible. Dough gave us a good recipe with ingredients we already have
today. With patience, new display technologies could trickle down from high end
TVs, or up from smartphones. Desktop monitors are stuck in this awkward middle
spot where little to no innovation seems to happen. 60Hz desktop displays are
still extremely common, but phones and TVs have had 120Hz panels for a decade
now. Some laptops are starting to get good panels, and OLED monitors are getting
pretty common too. I have hope that micro-LED displays and advancements to OLED
tech will help out here, but for now, I'll settle for a Spectrum with a Dell
logo on it that comes with a fucking warranty. Seriously, **do not buy Dough**.

## Links, references, and footnotes

[^0]: The Mastodon thread that inspired this post: https://hachyderm.io/@ddl/112584091556177153

[^1]: Computer Latency: 1977-2017: https://danluu.com/input-lag/

[^2]: Framework | Display Kit:
    https://frame.work/ca/en/products/display-kit?v=FRANJF0001

[^3]: The Eve V was Eve's first major product, anounced in 2014. Some units did
    eventually ship in 2017, but there are still people waiting for a refund to
    this day. Wikipedia: https://en.wikipedia.org/wiki/Eve_V

[^4]: The Eve V subreddit, still active: https://www.reddit.com/r/evev/

[^5]: A collection of stories similar to my own about Eve/Dough:
    https://www.doughscam.com/

[^6]: My 2020 piece in a similar format about ThinkPads:
    [posts/thinkpad-2020](//posts/thinkpad-2020/)