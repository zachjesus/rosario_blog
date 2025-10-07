---
title: Graphing Shadow Libraries
date: 2025-10-06
draft: false
description: How are Shadow Libraries so resiliant?
---
Inspired by this [paper](https://www.emerald.com/oir/article/49/8/62/1267576/Decentralized-digital-preservation-the-LOCKSS), I decided to use [Hyphe](https://github.com/medialab/hyphe), a research orientated web scraper, to graph the relationships between shadow libraries as a warmup exercise for my Senior Thesis.

With my settings in Hyphe every website is represented as a node and every site it hyperlinks to gets a node connected by an edge. In fashion of the paper, I started with Monoskop for my first shadow library to scrape. Out of the all sites I visited, it has the most links to both popular and obscure digital libraries plus it is more up to date in information. I also crawled textz, Memory of the World and Annas Archive for their hyperlinks too.

Here's the first result. Try opening it in a new tab, zooming/scrolling around and maybe ctrl+f your favorite site. You may have to zoom out all the way!

![Graph of Monoskop, textz, Memory of the World and Annas Archive's Hyperlinks](/images/shadow_library_test_one.svg)
*Fig 1. Graph of Monoskop, textz, Memory of the World and Annas Archive's Hyperlinks by Zach Rosario*

Another thing I did for this graph was merge shadow libraries, represented by green nodes and linked by green edges, spanning multiple top level domains (TLD's) into one node. Meaning that the boundary of each shadow library was their repository. In doing so, I was hoping to trace the interrelations between shadow libraries rather than their links across the web.

I was satisfied with the result, but it did not bring much clarity to the network structure of shadow libraries repositories. Just as the paper did, I found that the popular shadow libraries: (1) hyperlinked to each other and social media, see Fig. 1 and (2) that they spanned multiple TLD's.

Though, a lot of the links shadow libraries shared could not simply be extracted from hyperlinks. Well, literally some of the sites were not able to be scraped by Hyphe, but they also behaved in mirroring of each others repositories and some no longer operated.

So for the next graph I narrowed my search to sites whose focus was mainly distributing works of writing. I also did more research into the relations of shadow libraries, adding my own connections based on what I found online on the criteria discussed above.

Here is my diagram of the shadow library "ecology". 

![Relationships of the Popular Shadow Libraries with Nodes Scaled to Collection Size](/images/shadowlib2.png)
*Fig 2. Relationships of the Popular Shadow Libraries with Nodes Scaled to Collection Size by Zach Rosario*

Certain behaviors can be found in Fig. 2 that were not present in the former. Take the case of Library Genesis, as of today the original repository and domain are no longer operating due to legal issues. However, the closure has not actually affected the shadow library community because Library Genesis+ a new project mirrors the original, so does Z Library a for-profit shadow library and Anna's Archive a non-profit shadow library. 

The mirroring of shutdown libraries is not new. Back in 2012 the closing of Library.nu was compared to the burning of Alexandria by [Lawrence Liang](https://www.e-flux.com/journal/37/61228/shadow-libraries). Ironically, in it's ashes rose Library Genesis a significantly larger library, which was mirrored as a base for many other popular shadow libraries online today. 

Another unique behavior, exhibited only by Annas Archive, is the partial mirroring of repositories. Since many of the libraries mirror Library Genesis, Anna's Archive uses partial mirrors of the four repositories linked to the original Library Genesis to fill in the gaps of its collection. In fact, the efforts to mirror Library Genesis+ and Z-Library where done in direct collaboration with Anna's Archive.

The mirroring of files to ensure resiliency is nothing new for pirates. They have long used P2P networking to achieve this aim. But the collections of shadow libraries are too large for our collective memory and books would surely be lost in a totally distributed P2P networking scheme. Some central authorities(s) with a lot of memory must carry the burden if shadow libraries want to prevent a disaster like Library.nu from actually harming their collective collection. It is clear from Figure 2, and given it's coordination with other shadow libraries, that Anna's Archive has taken this role. Though, it wouldn't be possible for Anna's Archive without the preemptive mirroring of Library.nu by Library Genesis and the preemptive mirroring of Library Genesis by Z-library and Library Genesis+. 

Expanding on the original [paper](https://www.emerald.com/oir/article/49/8/62/1267576/Decentralized-digital-preservation-the-LOCKSS), the resiliency of shadow libraries ultimately comes from three factors: (1) Being embedded into the social media land scape, (2) Multiple TLD's for repositories and (3) the preemptive mirroring of repositories. Today, it seems shadow libraries are focusing more and more on factor three. In comparison to 2012, there is a lot more large shadow libraries and almost all have overlapping collections. But as these collections and the cost to store them grows, the people who can feasibly mirror their entirety will shrink. If that were to happen, the shadow library community could face a real "burning of Alexandria" moment not just a drill. Or will the cost of storage decrease enough before then? Or will the pirates innovate again like they did with widespread pre-emptive mirroring and TLD's after the closure of Library.nu? Maybe more efforts at partial mirroring? Either way my money is on the pirates to find a way.