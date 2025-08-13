---
title: "Licensing"
date: "2025-08-12"
summary: "🇺🇸 All about licensing"
description: "🇺🇸 All about licensing"
toc: true
readTime: true
autonumber: true
math: false
tags: ["ham"]
showTags: false
hideBackToTop: false
---

## Introduction

This post is all about the legal mumbo-jumbo around getting licensed. No, not this kind of license.

![meme](/assets/memes/mclovin.jpg)

You can't stop radio waves from reaching you. In fact, right now, you're being bombarded with radio waves. Nothing is stopping you from picking up a radio and tuning to the correct frequency to listen to those waves. It's free to listen (i.e., you don't need a license). However, if you want to transmit, you need a license.

## Licensing and the FCC

There is only a finite amount of electromagnetic spectrum (you can't make more of it), so someone or some entity needs to regulate who uses what pieces of that spectrum. Imagine a few scenarios where no one regulated the airwaves:

- Your Bluetooth earbuds keep dropping out because a neighbor’s DIY transmitter is spilling over into the same frequency
- Your WiFi slows to a crawl because the coffee shop next door is blasting on the same channel
- Your GPS tells you that you’re in the middle of the ocean because a nearby business’s equipment is swamping the satellite signals
- Firefighters at a scene can’t talk to each other because a hobbyist is using their emergency band to play music
- A plane crashes while landing because there is no radio standard for airplane communication

In the U.S., the [Federal Communications Commission](https://en.wikipedia.org/wiki/Federal_Communications_Commission) (FCC) is the entity that regulates the electromagnetic spectrum. They allocate spectrum, license operators, enforce the rules, and approve equipment.

An interesting thing is that while different countries might have different rules about specific frequencies, physics doesn't care. For example, 27 MHz is the same frequency in every country (on every planet), but not every country will use that frequency for the same thing. While there are some country-by-country rules, in *general*, most ham frequencies are similar worldwide (but there are exceptions).

### Post Office Box

When you get licensed, your name and address will go into a public FCC database. In fact, on [this page](https://wireless2.fcc.gov/UlsApp/UlsSearch/searchAdvanced.jsp), you can search for registered hams near you (select *Amateur* from the Service Group, then *HA* from the box, then enter your ZIP code).

{{< img src="20241022_001.png" alt="fcc database search" >}}

If you don't want physical spam from having your information exposed (like WHOIS domain privacy or voter registration), you can rent a [Post Office (PO) Box](https://www.usps.com/manage/po-boxes.htm) from your local Post Office to use as your address (just prepare to pay about $100/yr for the smallest size).

### FRN

You'll need to register with the FCC to [get your FCC Registration Number (FRN)](https://www.fcc.gov/wireless/support/knowledge-base/universal-licensing-system-uls-resources/getting-fcc-registration). You will need this later when you apply for your license.

If you want a PO Box, you should get that setup *before* you create your FRN. The reason is that if you switch to a PO Box after you get your license, someone could go through your license history and find your old address.

Just a heads up, the FCC website/registration process is garbage (it's the government 🙃). First, read the [instructions](https://www.fcc.gov/wireless/support/knowledge-base/universal-licensing-system-uls-resources/getting-fcc-registration) extremely carefully. You need to register your email/password in their CORES system, then from within there, register a new FRN. Also, I was unable to register from my Linux PC (on Firefox or Chrome), so I had to use Windows for this part (maybe you could change your user agent, I didn't try it). Also, you will need to give the FCC your Social Security Number (SSN).

## FRS vs. CB vs. MURS vs. GMRS vs. ham

There are many different types of radios, each with different qualities and uses, but not all of them require a license to use.

| Service                                                                                                                                  | Common Usage                               | Max power  | Frequency band  | Detachable antenna? | Repeaters allowed? | License required?          | Who does the license cover? |
|------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|------------|-----------------|---------------------|--------------------|----------------------------|-----------------------------|
| [FRS (Family Radio Service)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/family-radio-service-frs)                   | Walkie-talkies (purchase at retail stores) | 2 watts    | UHF             | No                  | No                 | No                         | N/A                         |
| [CB (Citizen Band)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/citizens-band-radio-service-cbrs)                    | Trucker radios                             | 4 watts    | HF              | Yes (often)         | No                 | No                         | N/A                         |
| [MURS (Multi-Use Radio Service)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/multi-use-radio-service-murs)           | Business radios                            | 2 watts    | VHF             | Yes (often)         | No                 | No                         | N/A                         |
| [GMRS (General Mobile Radio Service)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/general-mobile-radio-service-gmrs) | Outdoor/backcountry exploring              | 50 watts   | UHF             | Yes (often)         | Yes                | Yes ($35, no test)         | Family of licensee          |
| [Amateur Radio (ham)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/amateur-radio-service)                             | Amateur/dual-band radios                   | 1500 watts | VHF/UHF         | Yes                 | Yes                | Yes ($35, multiple tests)  | Licensee only               |

A few more things:

1. FRS, CB, MURS, and GMRS are channelized, meaning you don't tune to a specific frequency, you just tune to a channel (e.g., channel 1). In fact, FRS and GMRS use the same set of channels (meaning FRS and GMRS users will be able to communicate). However, GMRS has more channels and allows the use of repeaters.
1. For FRS, CB, and MURS, the manufacturers of radios need to submit their designs to the FCC for approval. That's why you don't need a license to use these radios (because the license is already part of the radio you purchased). With GMRS, the radio **and** the person are licensed. However, with ham radio, **only** the person is licensed. This means that a ham operator could build a radio from scratch because there is no restriction on the hardware.
1. Because ham radio is not channelized and and allows up to 1500 watts of power, the FCC assumes that the ham radio operator is knowledgeable about radio and is responsible for their own actions (that's why there is an exam).

## The exam

There are [three classes of ham license in the U.S.](https://en.wikipedia.org/wiki/Amateur_radio_licensing_in_the_United_States), and each subsequent license comes with more permissions and available frequencies.

* Technician
    * 35 multiple-choice questions (must get 26 correct)
    * grants access to all ham bands above 30MHz (the start of VHF)
* General
    * requires Technician license
    * 35 multiple-choice questions (must get 26 correct)
    * grants access to most HF bands (allowing skywave communication)
* Extra
    * requires General license
    * 50 multiple-choice questions (must get 37 correct)
    * grants all privileges on all ham bands

The Technician license generally allows use of light-of-sight communication and repeaters. If you want to use skywave, you need to use lower frequencies, which requires the General license. If you want to flex, get the Extra license.

### Study resources

There are tons of free resources for learning (this blog is not a study resource).

* [HamStudy.org](https://hamstudy.org/) - This is a great free website and they have an [offline app](https://hamstudy.org/appstore) as well
* [Ham Radio Crash Course](https://www.youtube.com/@HamRadioCrashCourse) - This is a YouTuber who offers tons of info for free and also has a [video playlist about the Technician exam](https://www.youtube.com/playlist?list=PL1KAjn5rGhixvvb_jMZFWmbP97-t9Kyxk)
* [The American Radio Relay League (ARRL)](https://www.arrl.org/) - A U.S.-based non-commercial organization that has lots of useful info
* Books - There are tons of books on the subject, so I may pickup [one that is highly recommended](https://www.amazon.com/2022-2026-Technician-Class-WB6NOA-Gordon/dp/0945053010)

### Taking the test

The test consists of a pool of questions, and your questions are chosen at random from the pool. The pool of questions changes every four years (the current pool is from 2022-2026). I'm focusing on the Technician exam, but the General and Extra exams have their own pools and schedules.

In the past, the exam was proctored in-person by Volunteer Examiners (VEs). With COVID-19, the FCC now allows online testing (it's still proctored by VEs, but it's online now). When you test online, you get your results immediately.

When you take your test, you'll need to [bring a few things with you](https://www.arrl.org/what-to-bring-to-an-exam-session):

- Photo ID
- Exam fee (typically $15, paid to the VE team)
- FCC license fee ($35, only paid *after* you pass your exam)
- FRN (FCC Registration Number)
- Non-programmable calculator
- Pencil/paper

### After you pass

After you pass the test and pay the FCC license fee, you're not licensed *yet*. You need to wait until the FCC processes your application and you receive your license and callsign (this usually takes a few days). Once your get your license, you should carry it with you while you use your radio (or keep a digital copy).

[Part 97 of the FCC rules](https://www.ecfr.gov/current/title-47/chapter-I/subchapter-D/part-97) govern the use of ham radio. A few key things to point out are below.

* Identify yourself by callsign at the end of every communication and once every 10 minutes (this must be done in English)
* Non-commercial use only
* Avoid interference and use the minimum power necessary
* No swearing
* No encryption
* No broadcasting music
* Although your ham radio *can* work on FRS/CB/GMRS bands, you shouldn't use it for that (you should buy a separate radio for that)
* Ham radio can be used without a license in an emergency

## What next?

As as full-fledged ham, you'll now have the world at your fingertips. Where should you start? Some commonly used frequencies are below.

### 2-meter and 70-centimeter

The [2-meter band](https://en.wikipedia.org/wiki/2-meter_band) covers VHF frequencies from about 144 MHz to 148 MHz (4 MHz of spectrum). It is popular for direct communication, emergency communication, and it allows you to use repeaters.

The [70-centimeter band](https://en.wikipedia.org/wiki/70-centimeter_band) covers UHF frequencies from about 420 MHz to 450 MHz (30 MHz of spectrum). Because it’s a higher frequency than 2m, it can support wider signal bandwidths, which allows certain modes to carry more data. However, it typically has less range in open terrain.

| Band and frequency range    | Common uses in the U.S.                                                                                                                  | Pros                                                                                                                           | Cons                                                                           |
|-----------------------------|------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| 2-meter (144–148 MHz)       | FM repeaters (most common), emergency communications, amateur satellites, digital voice/data, public service events                      | Longer range in open terrain, widely available repeaters, good balance of range and antenna size                               | Larger antennas than 70 cm, more susceptible to interference from VHF services |
| 70-centimeter (420–450 MHz) | FM repeaters (often linked to 2m), linked repeater networks, digital voice/data, amateur satellites, short-range tactical communications | Smaller antennas than 2m, better building penetration, more available channels in urban areas, less congestion in many regions | Shorter range in open terrain, more affected by foliage and terrain blocking   |

### The wilderness protocol

If you are out in the field and outside of repeater range, it is recommended to use what is called [the wilderness protocol](https://en.wikipedia.org/wiki/Radio_silence#Amateur_radio_Wilderness_Protocol). This provides a predictable listening schedule so that hams in remote areas have a chance to find each other without keeping their radios on continuously, which is especially useful for backcountry hiking, boating, off-roading, or expeditions where conserving battery power is critical. This involves announcing your presence and transmitting your message on 146.520 MHz for five minutes at the top of every third hour from 7am-7pm.

* 0700am
* 1000am
* 0100pm
* 0400pm
* 0700pm

The script goes like this:

* Give your callsign
* Say "monitoring for wilderness protocol or emergency traffic"
* Wait for five minutes
* Repeat every three hours

Obviously, in a real emergency, you would call at any time (the protocol is just for routine presence checks and relaying messages).

## Conclusion

If you're interested, [Jeff Geerling](https://www.jeffgeerling.com/), whose dad is a radio engineer, just got his technician license in late 2023. This video is a good intro to radio and the licensing process.

{{< youtube PIeavEhUhSw >}}

\-HamRadioNewbie