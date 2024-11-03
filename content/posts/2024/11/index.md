---
title: "The electromagnetic spectrum"
date: "2024-11-03"
summary: "🤯 A brief overview of the EM spectrum"
description: "🤯 A brief overview of the EM spectrum"
toc: true
readTime: true
autonumber: true
math: false
tags: ["ham"]
showTags: false
hideBackToTop: false
---

## Introduction

As Carl Sagan once said: 

>If you wish to make an apple pie from scratch, you must first invent the universe.

{{< youtube BkHCO8f2TWs >}}

This won't be quite *that* complicated, but we do need to start with the basics. Understanding radio requires a grasp of fundamental [physics](https://en.wikipedia.org/wiki/Physics) and the [electromagnetic spectrum](https://en.wikipedia.org/wiki/Electromagnetic_spectrum). I'm not a physicist, or a radio engineer, so we're going to go an inch deep and a foot wide on this topic.

## The electromagnetic spectrum

The [electromagnetic spectrum](https://en.wikipedia.org/wiki/Electromagnetic_spectrum) encompasses all electromagnetic radiation, from relatively long radio waves, to microwaves, to visible light, to relatively short gamma rays. Radio (the wave) is just a small slice of the spectrum that includes things like AM/FM radio, television broadcasts, NFC, RFID, WiFi, Bluetooth, 5G, and more.

{{< figure src="20241021_001.png" width="100%" loading="lazy" alt="the electromagnetic spectrum" attr="Image from Wikipedia" attrlink="https://en.wikipedia.org/wiki/Electromagnetic_spectrum">}}

It's important to note that there is no hard boundary between wave types (e.g., radio waves and microwaves). It's a spectrum that slowly spreads from type one to the other.

### Waves

The energy coming out of an antenna is a wave which travels at the speed of light (in a vacuum).

A cycle is one complete repetition of a wave's shape. In the diagram below, there are two cycles (I've colored them red and blue to make it easier to see).

The number of wave cycles that pass a fixed point in a given amount of time is called frequency. This is measured in cycles per second or Hertz (Hz). In the diagram below, the time between the two green dots is one second. Because two cycles pass in one second, this wave has a frequency of 2 Hz.

The distance between two of the same points on wave cycles is called the wavelength. This is measured in meters (m) and sometimes represented by the symbol λ (lambda).

The maximum distance between a wave's resting position and the peak or trough of a wave is called amplitude. This can be measured in different units depending on the type of wave.

{{< img src="20241021_002.png" alt="radio wave" >}}

In the diagram below, the time between the two green dots is one second. Because four cycles pass in one second, this wave has a frequency of 4 Hz. You can see how the waves are closer together and more waves will pass in the same amount of time compared to the diagram above.

{{< img src="20241021_003.png" alt="radio wave" >}}

Because we're using the metric system, we can use [metric prefixes](https://en.wikipedia.org/wiki/Metric_system) for our units of measurement. For example, frequency could be 1,000 hertz or simply one kilohertz (1 kHz). Wavelength could be .01 meters or simply one centimeter (1 cm).

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

### Radio waves

The electromagnetic spectrum is a...spectrum. As such, [radio waves themselves are a spectrum](https://en.wikipedia.org/wiki/Radio_spectrum) from 1 Hz to 3 THz (anything higher is literally a microwave 🧑🏻‍🍳). Below is a table comparing the different radio frequency bands and their properties.

| Frequency Band                   | Abbreviation | Frequency Range  | Wavelength Range    | Uses                                                                                                     | Comments                                                     |
|----------------------------------|--------------|------------------|---------------------|----------------------------------------------------------------------------------------------------------|--------------------------------------------------------------|
| Extremely low frequency          | ELF          | 3–30 Hz          | 10^5^–10^4^ km      | communication with submarines                                                                            | Low frequencies can penetrate oceans and Earth's crust       |
| Super low frequency              | SLF          | 30–300 Hz        | 10^4^–10^3^ km      | communication with submarines                                                                            |                                                              |
| Ultra low frequency              | ULF          | 300 Hz – 3 kHz   | 10^3^–100 km        | communication with submarines                                                                            |                                                              |
| Very low frequency               | VLF          | 3–30 kHz         | 100–10 km           | communication with submarines, navigation, through-the-Earth mine communication, time signals            |                                                              |
| Low frequency                    | LF           | 30–300 kHz       | 10–1 km             | AM broadcasting, communication with submarines, time signals                                             |                                                              |
| Medium frequency                 | MF           | 300 kHz – 3 MHz  | 1 km – 100 m        | AM broadcasting, maritime communication                                                                  | Can reflect signals off of Earth's atmosphere                |
| High frequency                   | HF           | 3–30 MHz         | 100–10 m            | Amateur radio, citizen's band (CB) radio, international broadcasting, shortwave radio                    | Can reflect signals off of Earth's atmosphere                |
| Very high frequency              | VHF          | 30–300 MHz       | 10–1 m              | Aircraft communication, FM broadcasting, television                                                      | Here and below (in the table) is line-of-sight communication |
| Ultra high frequency             | UHF          | 300 MHz – 3 GHz  | 1 m – 100 mm        | Cellular (3G and 4G), FRS, GMRS, radar, television, WiFi (2.4 GHz)                                       |                                                              |
| Super high frequency             | SHF          | 3–30 GHz         | 100–10 mm           | Cellular (5G), microwave links, radar, WiFi (5 GHz)                                                      |                                                              |
| Extremely high frequency         | EHF          | 30–300 GHz       | 10–1 mm             | Cellular (5G), millimeter wave scanners, radar                                                           |                                                              |
| Tremendously high frequency      | THF          | 300 GHz – 3 THz  | 1 mm – 0.1 mm       | Experimental research (check out the [terahertz gap](https://en.wikipedia.org/wiki/Terahertz_radiation)) | THF is this close 🤏🏻 to being heat                           |

{{< figure src="20241022_002.png" width="100%" loading="lazy" alt="the radio spectrum" attr="Image from U.S. Department of Transportation" attrlink="https://www.transportation.gov/pnt/what-radio-spectrum">}}

## Properties of waves

### Attenuation and penetration

[Attenuation](https://en.wikipedia.org/wiki/Attenuation) refers to the reduction in signal strength of a radio wave over a distance or through a medium, often due to scattering or absorption. Even in a vacuum (like in space), the strength of a wave degrades (think of the faint signals of the [Voyager probes](https://en.wikipedia.org/wiki/Voyager_program)). On Earth, although radio waves travel through "thin air", they encounter various obstacles (like air molecules, trees, building, etc...) that can reduce their strength.

[Penetration](https://en.wikipedia.org/wiki/Penetration_depth) describes how deeply a wave can travel into a medium before it is significantly attenuated. Generally, lower frequency waves can penetrate better due to their longer wavelengths. This is why 2.4GHz WiFi penetrates your house's walls better than 5GHz WiFi, and why millimeter wave 5G is easily blocked by almost anything (see below).

{{< youtube 4PLhxYIDwJs>}}

### Modulation

[Modulation](https://en.wikipedia.org/wiki/Modulation) is the process of changing a wave, usually to encode information (voice, data, etc...). Modulation allows signals to travel farther and with less interference, and it helps to separate different signals transmitted over the same medium. It's essential for radio communication, as it helps convert audio or data into a form that can be transmitted over radio waves.

Modulation works by taking a constant frequency wave (called a carrier wave) and laying another wave containing the information to be transmitted (called the modulating wave) on top of it. When they waves "mix", you're left with the resulting wave.

In radio, we're mainly concerned about three types of modulation: amplitude, frequency, and phase modulation.

#### AM/FM

[Amplitude modulation (AM)](https://en.wikipedia.org/wiki/Amplitude_modulation) encodes information by changing the amplitude (strength) of a wave, while frequency remains constant. [Frequency modulation (FM)](https://en.wikipedia.org/wiki/Frequency_modulation) encodes information by changing the frequency (waves per unit of time) of a wave, while the amplitude stays constant. AM is simpler, more susceptible to interference, and travels further, while FM offers better sound quality and resistance to interference, but doesn't travel as far (this is why FM radio in your car always sounds better than AM).

In the diagram below, note the differences between the resulting waves.

{{< figure src="20241027_001.jpg" width="100%" loading="lazy" alt="am and fm modulation" attr="Image from Tait Radio Academy" attrlink="https://www.taitradioacademy.com/topic/how-does-modulation-work-1-1/">}}

The diagram below is an animated version of the same AM/FM concept.

{{< figure src="20241025_001.gif" width="500px" loading="lazy" alt="am and fm modulation" attr="Image from Wikipedia" attrlink="https://en.wikipedia.org/wiki/Modulation">}}

#### Phase

Phase is basically *where* a wave is in time. While not really useful by itself, when you have two waves that are not in phase with each other (i.e., they're not overlapping), you can measure the difference between them (called phase difference or phase shift). In the diagram below, the purple and green waves are out of phase.

{{< img src="20241025_002.png" alt="radio wave" >}}

[Phase modulation (PM)](https://en.wikipedia.org/wiki/Phase_modulation) encodes information by moving waves "forward" or "backward" (i.e., shifting) along the time axis to encode data.

{{< figure src="20241025_003.gif" width="500px" loading="lazy" alt="phase modulation" attr="Image from Vassar College" attrlink="https://pages.vassar.edu/magnes/page/24/">}}

### Reflection and refraction

Remember that, unless using a directional antenna, radio waves travel outward in all directions at the speed of light. In the not-to-scale diagram below, the red and green antennas can communicate with each other via line-of-sight. However, the purple radio is blocked by a mountain and the curvature of the Earth.

In this case, the green radio can use [skywave propagation](https://en.wikipedia.org/wiki/Skywave) to communicate to the purple radio. Skywave relies on two key phenomena: [reflection](https://en.wikipedia.org/wiki/Reflection_(physics)) (the bouncing of waves off surfaces) and [refraction](https://en.wikipedia.org/wiki/Refraction) (the bending of waves as they pass through different mediums). In this process, radio waves can be redirected off the Earth's atmosphere, allowing communication beyond the horizon or obstacles. Typically, lower frequency bands are favored for skywave, as they reflect and refract more effectively. Although the waves reflect and refract in all directions, this diagram simplifies the concept by illustrating just one path. 

{{< img src="20241022_001.png" alt="skywave" >}}

Reflection and refraction are one of the main ways that ham radio operators can increase their signal's distance. When you see videos of hams talking across oceans, they're using reflection and refraction to do it.

{{< youtube X0y55Meu0NY >}}

#### Day vs night

The effectiveness of skywave changes throughout the day due to changes in Earth's [ionosphere](https://en.wikipedia.org/wiki/Ionosphere), which is the ionized part of Earth's upper atmosphere. During the day, the Sun's UV radiation ionizes the ionosphere more, causing lower frequency radio waves to be absorbed by the atmosphere (making them less-effective for long-distance communication). At night, without the Sun's UV radiation, the ionosphere is less ionized, which allows these lower frequency radio waves to be reflected back towards Earth, allowing them to travel farther.

#### Solar cycle
In addition to the daily cycle, the [solar cycle](https://en.wikipedia.org/wiki/Solar_cycle) also plays a significant role in radio wave propagation. The solar cycle, first observed in 1755 (called cycle one), is a cycle of changes every 11-ish years in the Sun's activity, including number of sunspots, solar flares, etc... Basically, during the peak of the solar cycle, increased solar activity affects the ionosphere in a way that enhances skywave (allowing radio waves to travel further). We are currently in solar cycle 25, with the peak of the cycle being expected in 2025 or 2026 (which is when radio waves will go the furthest).

## Conclusion

I know this was probably a dry post, but it contains the absolute basics you'll need to get started with this hobby and some of it will be on the Technician exam. Plus, it doesn't hurt to have an understanding (however basic) of the world around you.

\-HamRadioNewbie