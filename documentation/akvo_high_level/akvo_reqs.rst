Akvo High-Level Requirements
============================

Change log
----------
13 November 2012: Initial creation of content.

Table of contents
-----------------
-Overview
-Organisational requirements
-Technical requirements

Overview
========

This document describes what we call Akvo's fundamental requirements. These requirements describe the core thoughts and principles around which Akvo Foundation was created, how it is operated on a daily basis, and the rational behind it. Not only is it a non-trivial task to write fundamental requirements down, the requirements constantly change, so this document will never be "finished".

Akvo's vision
-------------
We see a future in which international development is open, transparent and collaborative. 

Akvo's mission
--------------
We build a superior open online platform and a trusted partner network which allows international development to be collaborated around, financed through, reported on and monitored, via interoperable platforms.

Akvo's strategy
---------------
We will achieve this mission by balancing the construction of tools with the assembly of a network of partners and communication about our progress, to create a strong combination of people, organisations and tools to get the job done. We use open-source methods and tools wherever practical and possible. We only build what is not already available and we openly share all the tools and content which we create. 

Technical requirements
======================

The technical requirements are structured in three sections for each requirement. Requirements statement. Implementation statement. Rational statement. One key reason for structuring it this way is to make it easy to quickly browse and get an overview understanding of what we are trying to do.

1. Sustainable and resilient systems
------------------------------------
**Requirement**: We need an information and data eco-system which is sustainable and resilient.

**Implementation**: We build open systems.

**Rationale**: To quickly create successful information and data systems to achieve our vision, we argue that together we must make use of open systems. This will allow many of us to collaborate and to quickly reach the next level. It is the fastest method which also creates a sustainable and resilient information eco-system.

**Comment**: 

By open systems we mean:

- using **open standards** to work with data, for example to track progress towards goals and objectives, complimented with an open data exchange format, as exemplified in the IATI XML standard

- **open data**, where all the data is open with anyone free to use, reuse, and redistribute it — subject only, at most, to the requirement to attribute and share-alike

- **open APIs**, where different computer systems containing goal data can interchange the data automatically via Application Programming Interfaces (APIs), the APIs should be open, meaning that their form may be copied freely by others as well as being accessible and usable by anyone

- **open source software**, where the underlying software that drives the systems which collects, collates, stores and distributes the data are built on software that adhere to the open source standards set by the Open Source Initiative


2. Fast and resilient knowledge sharing when building systems
-------------------------------------------------------------
**Requirement**: We need knowledge sharing which is fast and resilient

**Implementation**: We use open licenses

**Rationale**: Open knowledge sharing has proven to be the fastest way to create more and better knowledge, as well as sharing this knowledge widely, as exemplified by most academic research and Wikipedia. We believe that stating upfront that our information is available openly, through the use of open licenses, we not only promote sharing, but we also ensure that our information is treated correctly by others.

3. Open data and content
------------------------
**Requirement**: All data in our systems needs to be open. 

**Implementation**: All of our systems publish data and content1 under an open license. (With a few exceptions below.) All our systems have open APIs which allow data to be extracted and used for other purposes. We use open licensing for the data which our partners enter into our systems. We use two licenses in particular: Creative Commons Attribution Share Alike (CC-BY-SA) and the Open Database License (ODbL). Photographs or pictures entered into Akvo RSR use the Creative Commons Attribution Share Alike Non-commercial (CC-BY-SA-NC), as it may not be comfortable for many NGOs to have commercial use of their photography.

- http://creativecommons.org/licenses/by-sa/3.0/

- http://opendatacommons.org/licenses/odbl/

- http://creativecommons.org/licenses/by-sa-nc/3.0/

- http://creativecommons.org/licenses/by-nc-sa/3.0/

**Rationale**: [TBD]

4. Akvo only works on "safe" data
---------------------------------
**Requirement**: We do not work on data which need very high levels of security protection or shouldn't be published for some reason.

**Implementation**: [TBD]

**Rationale**: Some data which one could collect with our systems could be needing high levels of security protection. For example, one could imagine collecting data about refugee camps near to a war zone. If we have detailed data [TBD]

5. Privacy
----------

**Requirement**: We need privacy for some of our data

**Implementation**: We host data in Europe, primarily in the Netherlands. We don't consider the US having adequate data protection legislation and will move away from US services when  possible.

**Rationale**: Even when you are working with open data there is always some data which needs to be kept private. Examples would be: 

- household data from surveys
- user data from user accounts, login information, API keys etc.

Other data that we want to keep private is data which could be used to compete against us. In particular there are some data which we don't want to tempt our competitors or potential future competitors with, so we shouldn't put it under their control. This in particular is: 

- web site traffic data

As we are working with information which could potentially be politically sensitive, such as data on water, and we have several partners which we work with that are national governments and large multilateral organisations, we should host data in jurisdictions with good privacy and data protection laws.

6. Handling of private data
---------------------------

**Requirement**: If our partners have private data, such as household survey data, then some type of summary data should be published openly anyway.

**Implementation**: We should have functions which allow our systems to always openly publish anonymised or summary data.

**Rationale**: If we start compromising on open data then there will more and more arguments from organisations which don't want to publish open data from our systems that their data is somehow different and needs to be secret. If we don't enforce open data at system level then we will be fighting a losing battle against the urges to keep data secret. 



