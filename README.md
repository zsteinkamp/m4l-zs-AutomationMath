# Automation Math

This is a Max For Live device that lets you combine two automation signals using math. This allows you to have more complex modulation than what you can normally do in Ableton Live.

For example, two sine-wave LFOs running at different speeds whose values are added together will produce a complex wave. Another example is to use an LFO for vibrato, but manually control a second offset with a MIDI controller.

You can add, subtract, multiply, and divide two input signals. From there, you can invert, scale, and shift the resulting signal and map it to any other parameter.

![How it Looks](images/device.png)

## Installation

[Download the newest .amxd file from the frozen/ directory](https://github.com/zsteinkamp/m4l-zs-AutomationMath/tree/main/frozen/) or clone this repository, and drag the `AutomationMath.amxd` device into a track in Ableton Live.

## Usage

Usually, you would map a MIDI controller or automation source to `Input A` and `Input B`. Choose an operator, and then map the output to some other parameter. The example above shows it mapped to the Auto Filter Frequency.

The scale and shift knobs operate on the output signal, in that order.

The invert toggle (Ø) will flip the output signal, so 0 becomes 1, and 1 becomes 0.

## Attention to Detail

* Works with any well designed theme.
* Good Push / Push2 integration.
* Fully automatable, with sensible and consistent automation names.

## TODO

* ...

## Changelog

* 2022-04-27 [0.0.4](https://github.com/zsteinkamp/m4l-zs-AutomationMath/raw/main/frozen/AutomationMath-0.0.4.amxd) - Add multiple mapping destinations (thanks AYA)
* 2022-04-26 [0.0.3](https://github.com/zsteinkamp/m4l-zs-AutomationMath/raw/main/frozen/AutomationMath-0.0.3.amxd) - Fix bug (#1) with multiple instances.
* 2022-04-09 [0.0.2](https://github.com/zsteinkamp/m4l-zs-AutomationMath/raw/main/frozen/AutomationMath-0.0.2.amxd) - Change layout to match LFO device.
* 2022-04-08 [0.0.1](https://github.com/zsteinkamp/m4l-zs-AutomationMath/raw/main/frozen/AutomationMath-0.0.1.amxd) - Initial release.

## Contributing

I'd love it if others extended this device. If you would like to contribute, simply fork this repo, make your changes, and open a pull request and I'll have a look.
