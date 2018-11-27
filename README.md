# touchdesigner-components

A collection of reusable TouchDesigner components

These are the available components:

- combine_rgb: combine 3 TOPs and take one RGB channel from each
- fractal_noise: a looping version of fractal noise
- progress: get a normalized progress of the timeline
- split_rgb: splits a TOP in 3, one for each color channel

The components we want to build:

- colorama: equivalent of the After Effects effect
- delay: makes it easy to delay TOPs in time
- mirror: equivalent of the After Effects effect
- glass: equivalent of the After Effects effect
- vector_blur: equivalent of the After Effects effect

Compound components:

- rgb_delay: a component that uses split_rgb and delay components for delaying color channels in time
- time_difference: uses delay and composites with difference blend mode
