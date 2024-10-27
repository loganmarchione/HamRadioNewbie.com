---
title: "Licensing"
date: "2024-12-30"
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

You can't stop radio waves from reaching you. Right now, you're being bombarded with radio waves, microwaves, gamma rays, etc... Nothing is stopping you from picking up a radio and tuning to the correct frequency. It's free to listen (i.e., you don't need a license). However, if you want to transmit, you need a license.

## Licensing and the FCC

There is only a finite amount of electromagnetic spectrum (you can't make more of it), so someone or some entity needs to regulate who uses what pieces. In the U.S., that entity is the [Federal Communications Commission](https://en.wikipedia.org/wiki/Federal_Communications_Commission) (FCC). I'm not going to debate the merits of the FCC and what they do (you can read about that [here](https://www.fcc.gov/about-fcc/what-we-do)), because regardless, they are the ones in charge of the airwaves.

An interesting thing is that while countries might have different rules about specific frequencies, physics doesn't care. For example, 146.520 MHz is the same frequency in every country (but not every country will use that frequency for the same thing). So, there are some country-by-country rules, but generally, all ham radio frequencies are the same over the globe.

### Post Office Box

When you get licensed, your name and address will go into a public FCC database. In fact, on [this page](https://wireless2.fcc.gov/UlsApp/UlsSearch/searchAdvanced.jsp), you can search for registered hams near you (select *Amateur* from the Service Group, then *HA* from the box, then enter your ZIP code).

{{< img src="20241022_001.png" alt="fcc database search" >}}

If you don't want spam from having your information exposed (like WHOIS domain privacy or voter registration), you can rent a [Post Office (PO) Box](https://www.usps.com/manage/po-boxes.htm) from your local Post Office (just prepare to pay about $100/yr for the smallest size).

### FRN

You'll need to register with the FCC to [get your FCC Registration Number (FRN)](https://www.fcc.gov/wireless/support/knowledge-base/universal-licensing-system-uls-resources/getting-fcc-registration). You will need this later when you take your exam.

If you want a PO Box, you should get that setup *before* you create your FRN. The reason is that if you switch to a PO Box after you get your license, someone could go through your license history and find your old address.

Just a heads up, the FCC website/registration process is garbage (it's the government 🙃). First, read the [instructions](https://www.fcc.gov/wireless/support/knowledge-base/universal-licensing-system-uls-resources/getting-fcc-registration) extremely carefully. You need to register your email/password in their CORES system, then from within there, register a new FRN. Also, I was unable to register from my Linux PC (on Firefox or Chrome), so I had to use Windows for this part (maybe you could change your user agent, I didn't try it). Also, you will need to give the FCC your Social Security Number (SSN).

## The exam

VCE

* Technician
    * 35 multiple-choice questions (must get 26 correct)
    * grants access to all ham bands above 30MHz and some high-frequency bands
* General
    * requires Technician license
    * 35 multiple-choice questions (must get 26 correct)
    * grants access to all ham bands
* Extra
    * requires General license
    * 50 multiple-choice questions (must get 37 correct)

Technician radio generally allows use of light-of-sight communication and repeaters. If you want to reflect your signal off of the atmosphere, you need to use lower frequencies, which requires the General license.



Exam Tools

Test online to get immediate results

Photo ID

Testing fee

FCC 605 form

FRN - FCC Registration Number

Calculator and pencil/paper

### Study resources

https://hamstudy.org/

### After you pass

Pay the $35 fee (10 days)

Call sign in a day or two

Carry your license with you

### The rules

[Part 97 of the FCC rules](https://www.ecfr.gov/current/title-47/chapter-I/subchapter-D/part-97) govern the rules of ham radio. A few key things to point out are below.

* Identify yourself by callsign at the end of every communication and once every 10 minutes (this must be done in English)
* Non-commercial use only
* Avoid interference and use the minimum power necessary
* No swearing
* No encryption
* No broadcasting music
* Although your ham radio *can* work on FRS/CB/GMRS bands, you shouldn't use it for that (you should buy a separate radio for that)
* Ham radio can be used without a license in an emergency

## FRS vs. CB vs. MURS vs. GMRS vs. ham

| Service                                                                                                                                  | Common Usage                   | Max Power  | Frequency Band  | Detachable Antenna  | Repeaters Allowed  | License Required                           |
|------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|------------|-----------------|---------------------|--------------------|--------------------------------------------|
| [FRS (Family Radio Service)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/family-radio-service-frs)                   | Walkie-talkies (retail stores) | 2 watts    | UHF             | No                  | No                 | No                                         |
| [CB (Citizen Band)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/citizens-band-radio-service-cbrs)                    | Trucker radios                 | 4 watts    | HF              | Yes (often)         | No                 | No                                         |
| [MURS (Multi-Use Radio Service)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/multi-use-radio-service-murs)           | Business radios                | 2 watts    | VHF             | Yes (often)         | No                 | No                                         |
| [GMRS (General Mobile Radio Service)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/general-mobile-radio-service-gmrs) | Walkie-talkies (marked "GMRS") | 50 watts   | UHF             | Yes (often)         | Yes                | Yes (no test, family coverage)             |
| [Amateur Radio (ham)](https://www.fcc.gov/wireless/bureau-divisions/mobility-division/amateur-radio-service)                             | Amateur/dual-band radios       | 1500 watts | VHF/UHF         | Yes                 | Yes                | Yes (multiple tests, individual coverage)  |


A few more things:

1. FRS, CB, MURS, and GMRS are channelized, meaning you don't tune to a specific frequency, you just tune to a channel (e.g., channel 1). In fact, FRS and GMRS use the same set of channels (meaning FRS and GMRS users will be able to communicate). However, GMRS has more channels and allows the use of repeaters.
1. For FRS, CB, and MURS, the manufacturers of radios need to submit their designs to the FCC for approval. That's why you don't need a license to use these radios (because the license is already part of the radio you purchased). With GMRS and ham radio, the person is licensed, not the radio. 
1. Because ham radio is not channelized and and allows up to 1500 watts of power, the FCC assumes that the ham radio operator is knowledgeable about radio and responsible for their actions (that's why there is a test).

## GMRS license

I applied for my GMRS license and paid the $35 fee. It was very easy, just follow [these instructions](https://www.fcc.gov/wireless/support/knowledge-base/universal-licensing-system-uls-resources/applying-new-license) after you have your FRN (and PO Box) and choose *GMRS* from the dropdown.

## Common frequencies

144/440

2m/70cm

## Conclusion

If you're interested, [Jeff Geerling](https://www.jeffgeerling.com/), whose dad is a radio engineer, just got his technician license in late 2023.

{{< youtube PIeavEhUhSw >}}

\-HamRadioNewbie