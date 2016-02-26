my-project: snappy motto!
=========================

Release v\ |release|

.. toctree::

    self
    further-detail-1
    further-detail-2

1: Introduction
------------

This project demonstrates a few headaches I'm having with the sphinx
TOC system.



2: Explanation
--------------

#. I want the above Table of Contents to list sections of *this* page.
   The ``self`` keyword seems to be designed for this, but it only results in the title,
   and none of the subsequent sections.
#. I'd like the sidebar Table Of Contents (at left) to show "Documentation overview" rather than "snappy motto!".
#. Navigation should list *all* top-level sections: 1, 2, 3 and 4.
#. 3.3 and 3.4 should be listed after 3.1 and 3.2, at the same level.
   They're minor enough that I dont want to include them directly under section 3,
   but they still need to be part of the TOC.
