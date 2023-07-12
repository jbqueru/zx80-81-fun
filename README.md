# zx80-81-fun
Experiments for Sinclair ZX80/81

# Why? What For?
At a high level, the goal is to better understand the actual
capabilities of old hardware, when applying decades of software
experience and modern tools that software engineers of the time
didn't. There's some e-waste aspect to that goal, both looking
back (the kind of tricks we can use to keep existing hardware
useful for longer) and looking ahead (the kind of tricks we can
use to implement features now for which we don't quite have the
hardware yet, therefore increasing the time span of usefulness
for a given piece of software).

In the big picture, targeting old hardware at very low levels
might look relatively useless compared to contributing to current
software. However, the underlying properties of old hardware,
and especially the limited or non-existent storage and networking
capabilities, mean that code running on such hardware creates
less exposure to regulations such as GDPR and CRA (to name a few).
With GDPR and CRA alone creating a minimum liability of 25 million
euros, reducing liability by 1 percent or even 0.1 percent is
significant, respectively enough to by a large house or a large
new car.

As for the ZX80/ZX81 specifically, a few aspects make them appealing:
their low introductory price, their bad reputation around flicker on
the ZX80 and the "slow" mode introduced on the ZX81 to work around it,
the deep limitations but also the flexibility of their graphics
hardware, and the lack of sound (which therefore reduces the range of
skills necessary to use them to their full potential).

# What?
In a first phase, demos of graphics capabilities with no or minimal
interactivity. Potentially, as a second phase, interactive games.
Later, though seeming less likely, some language interpreter that
maintains a similar level of graphics capabilities while simplifying
programming.

# Who?
This is a single-person endeavor, and, while contributions and other
inputs are welcome, they realistically are unlikely and therefore are
not expected.

# How?
Besides the minimum amount of bootstrap BASIC, the development work
happens in Z80 assembly, via emulation. Ad-hoc might be developed
along the way.

# When?
There's no defined timeframe, development happens as time allows.
