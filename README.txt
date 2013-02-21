# Mechnical vibrations simulator

This script illustrates mechnical vibrations, described by

    mu'' + yu' + ku = F cos(wt).

Modelled as a mass attached to a spring and a dash pot, m is the mass, y the
damping from the dash pot, k the restoring force of the spring, F the driving
force and w the frequency.

This demo is inspired by a series of blog posts on John Cook's
[Endeavour](http://www.johndcook.com/blog/2013/02/19/mechanical-vibrations).

## How to run

    python ./vibrations.py

## Saving as a video

    python ./vibrations.py -o vibrations.mp4

