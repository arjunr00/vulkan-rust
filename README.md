# Vulkan in Rust

This is just a playground for me to learn Vulcan through Rust. I'll be using [Ash], which is pretty
mature and gives me more lower-level control than something like [Vulkano], keeping me as close to
the "metal" as possible.

[Ash]: https://github.com/MaikKlein/ash
[Vulkano]: https://github.com/vulkano-rs/vulkano

## Goals

I've made a [foray into Vulkan development before using C++], following [this tutorial]. I stopped
at a reasonable point there, having drawn a triangle to the screen, so I'm going to start by trying
to port that into Rust. Shouldn't be too hard.

[foray into Vulkan development before using C++]: https://github.com/arjunr00/vulkan-hellotriangle-tutorial
[this tutorial]: https://vulkan-tutorial.com/

After that, the aim is to make the code more idiomatic and "Rusty". This means building safe wrappers
around unsafe code, using useful Rust constructs where they are more appropriate than whatever was
being used in C++, etc.

Once that's done, I can start implementing more features. The precise next steps are yet to be
determined, but I'm thinking I'll start trying to draw more complex objects and transformations. I'll
make this up as I go, since there's no concrete end goal for this project.

As with most of my projects, I'm trying to use as few dependencies as possible. That means that
unless it's outrageously time- and effort-consuming to do so (like building my own RNG), I'll be
reinventing the wheel here and there.

## Why?

I find rendering technology fascinating---I've built a [pathtracer] using Rust before, but I also
really want to build a solid realtime renderer. Maybe (and this is a lofty, way-out-there goal that
I realistically probably won't achieve) building a rudimentary game engine at some point would be
cool.

As for why I'm using Rust instead of C++ like I already have, I just like Rust better (not that I
don't like C++, cause I love it). It's fun to use and helps exercise my ability to think and write
safe code.

**EDIT:** Having started, I'm starting to think this isn't quite worth it. I might return to this later,
but for now I'll just stick with C++.

## Progress

- [ ] Port C++ Vulkan code directly into Rust
- [ ] Make ported Vulkan code more idiomatic 
- [ ] TBD

## Bugs

None so far!
