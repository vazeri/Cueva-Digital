---
title: DIY 10A Power Supply 
keywords: proyectos
sidebar: misidebar
toc: false
permalink: PowerSupply.html
folder: PowerSupply
---


{% include note.html content="If you're cloning this theme, you're probably writing documentation of some kind. I have a blog on technical writing here called <a alt='technical writing blog' href='http://idratherbewriting.com'>I'd Rather Be Writing</a>. If you'd like to stay updated with the latest trends, best practices, and other methods for writing documentation, consider <a href='https://tinyletter.com/tomjoht'>subscribing</a>. I also have a site on <a href='http://idratherbewriting.com/learnapidoc'>writing API documentation</a>." %}


## Introduction

Why do it for 3 when we can design for 10?! At college we were in charge of designing a 3 Amp power supply, but I was seeking for a challenge, not a grade!

## Design
Overcomplicating this kind of “simple” projects can make your life a bit harder but way more exiting, and the rewards just have no price, you will also learn way more than doing a small 3 Amp power supply, fortunately I had a good and experienced mentor to guide me, Lopez Hernandez Jose Antonio from the Investigation and Technologic Innovation Center (CIITEC) in Mexico City.

## Conclusion 
 
I completed the project in time thanks to some administrative and economic planning technics , the right tools and a bit of will power

A linear power supply takes the 120vCA 60 Hz mains power, steps the voltage down through a transformer, rectifies, filters, and regulates it. It's simple and robust; the main problem is that it's inefficient. You need a big, heavy transformer to handle the current, high current diodes, huge electrolytic capacitors, and lots of thermal dissipation for your Darlington arrays. It can also become prohibitively expensive to build high power linear supplies, even if they're easy to design. (This one was around $6,500 MXN pesos, around 433 USD considering 1 USD = 15 MXN pesos)

Here you will learn to do what I did right, and how not to not commit the same mistakes I made, mistakes are good because you do learn from them, but on the other hand you can save a lot of time and money by learning from my mistakes instead of doing your own.

Needless to say, this is my first instructable… and this my first project using copper clads… and my first time using Altium CAD PCB software… and my first linear power supply ever… and my first time documenting something in English.... so try to not be so hard on me on the comment section ;), all the feedback is welcome.

The guide is a bit long, as I said please beware, if you find any grammar , calculation or technical mistakes please let me know , and I will review them and see them fixed as soon as possible.

Along the start of each step I will be adding underlined text where I warn about what I did wrong , this bold underlined text can also be an upgrade note to do what I did in a better way, with some other ways I have learned over the time after completing the project

Every single file used to make the power supply is in my GitHub Repository feel free to use it at your discretion, hopefully you can do it better, smaller, cheaper, or why not even bigger!


## Build the Theme

Follow these instructions to build the theme.

### 1. Download the theme

First, download or clone the theme from the [Github repo](https://github.com/tomjoht/documentation-theme-jekyll). Most likely you won't be pulling in updates once you start customizing the theme, so downloading the theme (instead of cloning it) probably makes the most sense. In Github, click the **Clone or download** button, and then click **Download ZIP**.

### 2. Install Jekyll

If you've never installed or run a Jekyll site locally on your computer, follow these instructions to install Jekyll:

* [Install Jekyll on Mac][mydoc_install_jekyll_on_mac]
* [Install Jekyll on Windows][mydoc_install_jekyll_on_windows]
