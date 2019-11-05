.. moduleauthor:: Paul Ross <apaulross@gmail.com>
.. sectionauthor:: Paul Ross <apaulross@gmail.com>

.. TotalDepth introduction

.. _TotalDepth-intro:

**************************
Introduction to TotalDepth
**************************

TotalDepth is an Open Source, cross platform, software collection that can process petrophysical data from the oil field such as wireline logs, seismic data and so on.

Conventional, proprietary, software for petrophysical data tends to be expensive to licence, restrictive, slow to develop for and tied to expensive hardware. TotalDepth changes all of that. 

TotalDepth is open and cross-platform, and produces results straight to the bowser. TotalDepth supports such technologies such as HTML5, AJAX, Software as a Service (SaaS) and Cloud Computing.

TotalDepth is currently at **Alpha** version |version|, release |release|. For the licence see :ref:`licence_text`.

Software Technology
===================

For rapid development and performance TotalDepth is written in `Python <http://www.python.org>`_ with performance critical code written in C or C++.

Petrophysical File Formats Supported by TotalDepth
=========================================================

+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| Format                | Support   | Since     | Notes.                                                            |
+=======================+===========+===========+===================================================================+
| LIS79                 | Full      | 0.1.0     |                                                                   |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| LIS-A                 | Partial   | 0.1.0     | No direct XNAM support.                                           |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| LAS version 1.2       | Full      | 0.1.0     |                                                                   |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| LAS version 2.0       | Full      | 0.1.0     |                                                                   |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| LAS version 3.0       | None      |           | No evidence that this is used by the industry.                    |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| WellLogML             | None      |           | No evidence that this is used by the industry.                    |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| RP66v1 "DLIS"         | Full      | 0.3.0     |                                                                   |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+
| RP66v2 "DLIS"         | None      |           | No evidence that this is used by the industry.                    |
+-----------------------+-----------+-----------+-------------------------------------------------------------------+