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

## Progress

- [ ] Port C++ Vulkan code directly into Rust
- [ ] Make ported Vulkan code more idiomatic 
- [ ] TBD

## Bugs

None so far!
