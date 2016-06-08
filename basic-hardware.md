# Getting started: TI-99/4A minimal hardware

Intro blurb, power supply, video, and basic specs

Keyboard quirks and joystick port, cassette, ROM and expansion ports.

## The power supply

The power connector on the back side of the machine takes AC voltages from an
external transformer.  The connector will most likely have four pins, although
the power supply from the later QI models has only two.  Older transformers
designed for four pin connectors do work with the newer machines.  Voltages
are described <http://mainbyte.com/ti99/hardware/power_supply.html>, but if
that looks like something ain't right with those numbers, it's because voltage
test points come in pairs and these numbers don't.  Probably this is a center
tapped transformer.  FIXME if you can.

During the life of the console, someone got the idea AC powered appliances
needed safety fuses to keep from potentially killing people for some reason,
and TI had to hastily add one to the TI-99/4A.  Transformers without fuses are
in the wild, and they're of the "wall wart" variety.  Newer models have a
brick with a cord going to the console, and another cord that ends in a plug
permanently glued into a socket a short extension cord with an inline AC
socket.  TI spared no expense fixing this!  ;)

Of course that fuse can fail, and if it ever does your transformer is dead.
The fuse cannot be replaced and your only option is to cut the transformer's
AC plug out of the socket or just cut off the plug and wire a new one.  Doing
euther is beyond the scope of this beginners guide and if you electrocute
yourself to death playing with live mains power, your zombie is not allowed to
sue us.  If you don't know what you're doing here, don't do it.  C'mon, the TI
is not a rare and expensive system here, get a new brick or find someone who
knows how to fix it right.

It is unknown if European appliances of the day were allowed to possibly
contain deathtraps, but your author has read that most people in the UK at
least who would have ever seen one of these consoles in their prime would have
learned how to wire a power jack in school, including to make the earthing
wire longer so that if the others wer somehow pulled free, the device would
still be earthed.  Because in Europe, they use twice the voltage Americans
use, which makes it twice as dangerous, and therefore twice as good an idea to
teach children how to start with bared wires and end up shoving something into
an electrical socket.  Brilliant!  :)


## Video display

US and EU video ports exist, where was each distributed?  RF modulator or monitor or...

### US video port

RF modulator, pinout, Commodore/Atari composite cable compatible, sources for
cables

### EU video port

RF modulators and what to look for, pinout of the video port, using the YPbPr
output?  Are cap/resistor mods remotely worthwhile?  Xref to modding RF
modulators.

### Other video considerations

Some troubleshooting info, cap and resistor fixes for US models (only?), xref F18A upgrade

## Joystick port

TI wired remotes, WICO (and other) joystick adapters, xref build your own
joystick adapter

## Cassette port

BASIC programs and cartridge databases, single and dual cassette cables, xref
making your own cable.  Alternatives to cassettes, xref to using a USB sound
device with a modern computer.

