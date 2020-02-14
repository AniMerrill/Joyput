# Joyput
An input helper class intended to streamline the use of different control schemes and devices with Input in the Godot Engine.

By AniMerrill, a.k.a. Ethan Merrill (MIT License)

## Synopsis

**NOTE:** *This addon is not by any stretch of the imagination ready for any serious use in games and will need significant amounts of work. Right now the addon only features the ability to unify digital and analogue inputs, basically treating all devices as equal. I have only uploaded this publicly in an attempt to be transparent with the games I am currently creating, so they can be fully open source. Please follow and star if you would like to see progress, I hope to make this worth installing over the following year.*

TODO: Add full synopsis later.

## Install Instructions

Joyput v0.1 is intended for use in Godot 3.2.

As far as I know, installing this addon should be as simple as putting the root folder of this repository (`animerrill.joyput`) into `res://addons` within your project. The plugin can then be activated from Project Settings. Eventually though, I will add more thorough installation instructions for different skill levels once I have time to get the project to a more stable release.

## Documentation

**NOTE:** *Eventually I will add more in depth documentation to explain what Joyput actually does, why it is useful, and how to properly use it. Again I want to reiterate that this addon is currently not suitable for general use by other people, but if you want to understand what is going on please read the source code. I've tried to put comments and docstrings to help explain what each of the core classes do and how they do it.*

TODO: Add full documentation later.

## Roadmap
* Version 1.0
    * Add full support for multiple devices.
    * Add support for buttons and triggers.
    * Add support for mouse as an axis replacement with keyboard controls.
* Beyond
    * Potentially add in editor GUI (and config file standard) to instantiating mappings when the game launches.
    * Add easy remapping per device profile.