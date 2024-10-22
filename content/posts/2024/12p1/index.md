---
title: "The electromagnetic spectrum"
date: "2024-12-01"
summary: "🤯 A brief overview of the EM spectrum"
description: "🤯 A brief overview of the EM spectrum"
toc: true
readTime: true
autonumber: true
math: true
tags: ["ham"]
showTags: false
hideBackToTop: false
---

## Introduction

As Carl Sagan once said: 

>If you wish to make an apple pie from scratch, you must first invent the universe.

{{< youtube BkHCO8f2TWs >}}

This won't be quite *that* complicated, but we do need to talk about the basics of the [electromagnetic spectrum](https://en.wikipedia.org/wiki/Electromagnetic_spectrum) and *how* radio works. I'm not a radio engineer, or a physicist, so we're going to go an inch deep and a foot wide on this topic.

## The electromagnetic spectrum

The [electromagnetic spectrum](https://en.wikipedia.org/wiki/Electromagnetic_spectrum) encompasses all electromagnetic radiation, from relatively long radio waves, to microwaves, to visible light, to relatively short gamma rays. Radio (the wave) is just a small slice of the spectrum that includes things like AM/FM radio, television broadcasts, NFC, RFID, WiFi, Bluetooth, and more.

{{< figure src="20241021_001.png" width="100%" loading="lazy" alt="the electromagnetic spectrum" attr="Image from Wikipedia" attrlink="https://en.wikipedia.org/wiki/Electromagnetic_spectrum">}}

It's important to note that there is no hard boundary between wave types (e.g., radio waves and microwaves). It is a spectrum that slowly spreads from one to the other.

## Waves

The energy coming out of an antenna is a wave which travels at the speed of light.

A cycle is one complete repetition of a wave's shape. In the diagram below, there are two cycles (I've colored them red and blue to make it easier to see).

The number of wave cycles that pass a fixed point in a given amount of time is called frequency. This is measured in cycles per second or Hertz (Hz). In the diagram below, the time between the two green dots is one second. Because two cycles pass in one second, this wave has a frequency of 2Hz.

The distance between two of the same points on wave cycles is called the wavelength. This is measured in meters (m).

The maximum distance between a wave's resting position and the peak or trough of a wave is called amplitude. This can be measured in different units depending on the type of wave.

{{< img src="20241021_002.png" alt="radio wave" >}}

In the diagram below, the time between the two green dots is one second. Because four cycles pass in one second, this wave has a frequency of 4Hz. You can see how the waves are closer together and more waves will pass in the same amount of time.

{{< img src="20241021_003.png" alt="radio wave" >}}

Because we're using the metric system, we can use [metric prefixes](https://en.wikipedia.org/wiki/Metric_system) for our units of measurement. For example, frequency could be 1,000Hz or simply one kilohertz (1KHz). Wavelength could be .01 meters or simply one centimeter (1cm).

| Prefix    | Symbol | Factor                       | Power    |
|-----------|--------|------------------------------|----------|
| tera      | T      | 1,000,000,000,000            | 10¹²     |
| giga      | G      | 1,000,000,000                | 10⁹      |
| mega      | M      | 1,000,000                    | 10⁶      |
| kilo      | k      | 1,000                        | 10³      |
| hecto     | h      | 100                          | 10²      |
| deca      | da     | 10                           | 10¹      |
| (none)    | (none) | 1                            | 10⁰      |
| deci      | d      | 0.1                          | 10⁻¹     |
| centi     | c      | 0.01                         | 10⁻²     |
| milli     | m      | 0.001                        | 10⁻³     |
| micro     | μ      | 0.000 001                    | 10⁻⁶     |
| nano      | n      | 0.000 000 001                | 10⁻⁹     |
| pico      | p      | 0.000 000 000 001            | 10⁻¹²    |

## Radio waves

* Extremely low frequency (ELF)
* Super low frequency (SLF)
* Ultra low frequency (ULF)
* Very low frequency (VLF)
* Low frequency (LF)
* Medium frequency (MF)
* High frequency (HF)
* Very high frequency (VHF)
* Ultra high frequency (UHF)
* Super high frequency (SHF)
* Extremely high frequency (EHF)
* Tremendously high frequency (THF)

## Refraction

In the diagram below, the red and green antennas can communicate with each other via line-of-sight. Remember that unless using a directional antenna, radio waves travel outward in all directions at the speed of light. Because of this, the red and green radios will be able to talk to each other, and in fact, their waves will continue into space forever.

However, the purple radio is blocked by a mountain and the curvature of the Earth. In this case, the green radio can take advantage of a unique property called [refraction](https://en.wikipedia.org/wiki/Refraction). In this case, a lower frequency band can be used to "bounce" the signal off of Earth's atmosphere (it happens in all directions, but for the sake of this diagram, I've only shown it in one).

{{< img src="20241022_001.png" alt="refraction" >}}

## Misc

FRS CB MURS GMRS HAM

UHF is this close 🤏🏻 to being heat

## Conclusion

\-HamRadioNewbie