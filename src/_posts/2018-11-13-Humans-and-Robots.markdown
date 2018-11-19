---
layout: post
title:  "Robots & Humans"
date:   2018-11-13 23:57:49 -0600
categories: dunno
comments: true
---
## Robots 
"Robots" are programs that trawl the web for information which can be used in a variety of applications such as e.g. search engines, spam, marketing etc.

### Robots.txt
"Robots.txt" is a simple text-file which web site owners can use to instruct benevolent robots which information or what pages on the site the robots are allowed to scan. The text file can specify which robots are disallowed certain pages on the site through the variable "User-agent". A robots.txt file sits in the root of the site and may e.g. look something like this:
```
User-agent: GoodBot
Disallow: 

User-agent: *
Disallow: /
```
This robots.txt would allow "GoodBot" but disallow every other robot. 

It is however important to note that robots can ignore the robots.txt-file, e.g. spammers will not follow the instructions. Furthermore, the robots.txt is publically availible. Thus, by scanning the file other entities may see which sections of your server or disc you do not want robots to access. More information regarding robots.txt can be found at [the web robots pages](http://www.robotstxt.org/).

#### Config for this site
This sites "robots.txt" looks like this:
```
User-agent: *
Disallow: /
```
Thus, no robots are allowed, but they will of course creep through anyway.

## Humans
Humans are animals that trawls the earth for resources which they will ultimately convert to heat.

### Humans.txt 
"Humans.txt" is a simple text-file that contains information regarding the people who have created the site on which the file sits. The file sits at the root of the site, perhaps next to the "robots.txt" file. More information regarding humans.txt can be found [here](http://humanstxt.org/).

#### Config for this site
This sites "humans.txt" looks like this:
```
/* TEAM */
       Web designer: Claes
       From: Stockholm, Sweden
```
Quite minimalist.


