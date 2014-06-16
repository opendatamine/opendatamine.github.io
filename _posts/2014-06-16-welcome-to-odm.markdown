---
layout: post
title:  "OpenDataMine: A Read-only API for the real world"
date:   2014-06-16 02:03:04
categories: odm meta
---

OpenDataMine Manifesto
========================

Welcome to the OpenDataMine. An API and clearinghouse for all the open data
in the real world.

It is the year 2014 and we're now seeing a deluge of open civic data available
to like-minded hackers around the world. However, there's no standards for this
data and not all governments everywhere collect, store, and open data in the
same way. As a result hackers and app developers have to deal with the troubles
of cleaning up and parsing data and doing it over and over again for every new
dataset they support as opposed to spending energy building better app
experiences to benefit communities, as they should. One good example of such a
standard is the GTFS (General Transit Feed Spec) which quite a few cities are
using to provide open transit data.

This is where ODM comes in. Our goal is to help define standards around this
open data and act as an API to all real world data sources out there so that
people can get to the real task of using this data to build better communities.

In order to attack this monumental task, we'll take a leaf from the Internet
Engineering Task Force (IETF) handbook and be organized like the IETF: "a
loosely self-organized group of people who contribute to the engineering and
evolution of open data APIs". One of the "founding beliefs" is embodied in an
early quote about the IETF from David Clark: "We reject kings, presidents and
voting. We believe in rough consensus and running code". Another early quote
that has become a commonly-held belief in the IETF comes from Jon Postel: "Be
conservative in what you send and liberal in what you accept". (source: http://www.ietf.org/tao.html)

Anyone can propose RFCs for open data such as the GTFS (for crime, roads,
schools, restaurants, etc.) as long as they support it with working code enabling
mapping 2 or more existing open civic data sets into a common spec. 

(This is the hard part, converting existing data sets into a new format is
massively challenging but there is enormous value to be able to allow an API
user to, for example, get crime statistics for any zip code in the world by
changing one parameter in an API call, without having to worry about getting,
cleaning, hosting, updating the underlying data sets). 

Once a spec is proposed and the working group for that spec agrees to it, we
get down to the task of allowing people to migrate other city data sets into
this new format, by using brute-force, or machine learning techniques such as
naive bayesian classification.

Once converted, the organization could possibly support itself by asking for
cash for commercial use of the underlying data sets, or donated storage/compute
resources (with a high regard for transparency).

An added side-benefit of allowing this data to be used is that we create new forms of useful data, answering questions about the usage of open data (ie. How many people look up directions to Times Square in NYC on Wednesday nights.)

Open questions:
- what do we need to start?
- where does this data get hosted and how does it get served?
- how do we enable city-based champions to interact with city governments better?
- how does this tie-in to all the open data activities all happening out there?
