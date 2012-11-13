Akvo High-Level Requirements
============================

Change log
----------
13 November 2012: Intitial creation of content.

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

**Comement**: 

- using open standards to work with data, for example to track progress towards goals and objectives, complimented with an open data exchange format, as exemplified in the IATI XML standard

- open data, where all the data is open with anyone free to use, reuse, and redistribute it — subject only, at most, to the requirement to attribute and share-alike

- open APIs, where different computer systems containing goal data can interchange the data automatically via Application Programming Interfaces (APIs), the APIs should be open, meaning that their form may be copied freely by others as well as being accessible and usable by anyone

- open source software, where the underlying software that drives the systems which collects, collates, stores and distributes the data are built on software that adhere to the open source standards set by the Open Source Initiative


2. Fast and resilient knowledge sharing when building systems
-------------------------------------------------------------
**Requirement**: We need knowledge sharing which is fast and resilient

**Implementation**: We use open licenses

**Rationale**: Open knowledge sharing has proven to be the fastest way to create more and better knowledge, as well as sharing this knowledge widely, as exemplified by most academic research and Wikipedia. We believe that stating upfront that our information is available openly, through the use of open licenses, we not only promote sharing, but we also ensure that our information is treated correctly by others.



EXAMPLES - not part of documentation
====================================
This document contains examples of how to layout text and images in RST.

|more| Linking to other documents :ref:`uploading data <uploading_data>`

Including an image with a caption:

.. figure:: img/phone_4.png
   :width: 200 px
   :alt: image of phone
   :align: center

   This is the caption of the figure. In the code, don't forget to indent the text.
   
   
Next section
-----------------

The standard inline markup is quite simple: use

* one asterisk: ``*text*`` (result *text*) for emphasis (italics),
* two asterisks: ``**text**`` (result **text**) for strong emphasis (boldface), and

Another section
------------------
List markup is natural: just place an asterisk at
the start of a paragraph and indent properly.  The same goes for numbered lists;
they can also be autonumbered using a ``#`` sign::

   * This is a bulleted list.
   * It has two items, the second
     item uses two lines.

   1. This is a numbered list.
   2. It has two items too.

   #. This is a numbered list.
   #. It has two items too.

The result is:
   * This is a bulleted list.
   * It has two items, the second
     item uses two lines.

   1. This is a numbered list.
   2. It has two items too.

   #. This is a numbered list.
   #. It has two items too.


Nested lists are possible, but be aware that they must be separated from the
parent list items by blank lines::

   * this is
   * a list

     * with a nested list
     * and some subitems

   * and here the parent list continues

The result:
   * this is
   * a list

     * with a nested list
     * and some subitems

   * and here the parent list continues

Definition lists are created as follows::

   term (up to a line of text)
      Definition of the term, which must be indented

      and can even consist of multiple paragraphs

   next term
      Description.

With this result:

   term (up to a line of text)
      Definition of the term, which must be indented

      and can even consist of multiple paragraphs

   next term
      Description.

Note that the term cannot have more than one line of text.

Quoted paragraphs are created by just indenting
them more than the surrounding paragraphs.

	For example, this is a quoted paragraph.


A simple table is done like this::

   =====  =====  =======
   A      B      A and B
   =====  =====  =======
   False  False  False
   True   False  False
   False  True   False
   True   True   True
   =====  =====  =======

with this result:

   =====  =====  =======
   A      B      A and B
   =====  =====  =======
   False  False  False
   True   False  False
   False  True   False
   True   True   True
   =====  =====  =======


One more section, with subsections
---------------------------------------------------

Subsection 1
^^^^^^^^^^^^^^^^

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin in ligula et ipsum feugiat egestas ac vel arcu. Mauris sollicitudin pretium sem eget mollis. Cras sit amet mauris turpis. Ut molestie lobortis laoreet. Fusce lectus nibh, feugiat eu adipiscing a, gravida vitae risus. Suspendisse velit lorem, molestie sed commodo non, aliquet ornare arcu. Suspendisse potenti. 


Subsection 2
^^^^^^^^^^^^^^^^^
Pellentesque pellentesque lacus sed justo egestas et dignissim mauris placerat. Integer ornare, nisi vel elementum dignissim, purus elit ullamcorper massa, at tincidunt felis eros ac sem. Nunc non lacus tortor. Cras in lectus libero. Vestibulum a nisi velit. Vivamus id eros lobortis eros tempus porta. Nulla facilisi. Mauris facilisis magna sit amet ante imperdiet accumsan volutpat lectus ultricies. Quisque quis diam eros, quis porttitor est.




