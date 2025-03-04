## RP2350 test board

Now that JLCPCB have stock of RP2350s, here's a test board.  It's designed around the RP2350B and, I think, follows the 
guidance in the RPi hardware design guide.  With one exception: given the length of the USB lines, I've made no attempt 
to impedance match them.

I've put this together as a starting point for me to build on and for others, so I'm licensing this broadly under 
CC BY 4.0 - details here: https://creativecommons.org/licenses/by/4.0/?ref=chooser-v1

As a starting point, it doesn't have much on it - one LED (as, of course, a blinking LED is proof of concept) and a
header connected to 8 GPIOs.  That's by design.

Any and all feedback, good or bad, is welcome - david.knell@gmail.com will find me.  All use is at your own risk.

You'll need EasyEDA Pro to open and use this - if you've been using the standard version, it's worth the slight learning
curve.  Trust me - I've been there.

I think that I've specified JLCPCB's basic parts wherever possible to keep low-volume build costs to a minimum.  If I've
missed anything, please let me know.

The design went through JLCPCB's checks without any queries being raised and, about three days after submission, boards
were on their way to me.

Tested and working as 2025-02-27.
