SCSS configurable grid system
===============

A configurable SCSS grid system based on some of the principles used in foundation and bootstrap.

## Usage

Currently, this grid system takes a sass map and uses the values in that map to produce the css.
This should (hopefully soon) be optional depending on the usage.

Therefore a map of breakpoints must be set up. 

It also requires some config variables to be set ($col-count, $gutter-w, $containerClass & $rowClass).
These variables will become optional with sensible defaults.

An example of the breakpoint map and the config variables can be seen in 'example-globals'.


This grid system relies on sass maps, and so requires version 3.3 of sass or higher.