TimeTagger Modules User Guide
=============================

.. only:: html

    .. image:: _static/TDC-Module_3D.png
      :alt: 3D image of a TimeTagger Module
      :align: center
      :scale: 100%

.. raw:: latex

   \RaggedRight

.. note::

   This User Guide is under active development.

.. raw:: latex

   \phantomsection
   \addcontentsline{toc}{chapter}{Introduction}
   \chapter*{Introduction}

The compact `TimeTagger modules <https://www.cronologic.de/product/tdc-modules>`_ 
from `cronologic <https://www.cronologic.de>`_ provide a practical solution 
to the challenge of significantly **reducing space requirements in 
measurement setups and analyzers** without sacrificing performance and 
accuracy. They can be integrated via customer-specific analog front ends.

The **TimeTagger modules** offer the same functionality as cronologic's 
`TimeTagger PCIe boards <https://www.cronologic.de/product/timetagger>`_.
As such, they are ideally suitable in applications that do require a
**compact form factor**, **high data-acquisition** rates,
and low **multiple-hit** dead time.

This User Guide provides an overview of the modules operation and installation
requirements. An overview of the **functionality** and the **C API** can be 
found in the `TimeTagger4 User Guide 
<https://download.cronologic.de/TimeTagger/TimeTagger4_User_Guide.pdf>`_.

This User Guide is also available as `PDF download 
<https://docs.cronologic.de/_/downloads/timetagger_modules/en/latest/pdf/>`_.

The user guides of all products by cronologic GmbH & Co. KG are available 
online at `docs.cronologic.de <https://docs.cronologic.de>`_.

Module Overview
---------------
`cronologic <https://www.cronologic.de>`_ offers multiple variants of the
`TimeTagger4 <https://www.cronologic.de/product/timetagger>`_ boards, offering
the following quantization (bin size):

- **TimeTagger4-1.25G**:  800 ps
- **TimeTagger4-2.5G**:   400 ps
- **TimeTagger4-5G**:     200 ps
- **TimeTagger4-10G**:    100 ps

Each of these variants is available as a modular version, as well, offering:

**Space-saving installation**
    All TimeTagger modules can be installed via board-to-board connectors with 
    minimal hardware effort.

**Integrate at minimum cost**
    Our TimeTagger4 TDC modules are the perfect choice if you are looking for
    picosecond resolution at the best possible price/performance ratio.

**Bipolar design**
    TDC modules can be combined with a wide range of detectors or constant 
    fraction discriminators (CFD) as their threshold discriminators utilize 
    positive or negative thresholds with configurable voltage.

**Use the TiGer timing generator**
    Control your device with periodic pulse patterns, the exact timing of which
    is measured by the TDC. You can use any input channel of our module to 
    output these pulses.

Features
--------

- 4-channel common-start TDC module
- Quantisation (measurement resolution): 100 to 800 ps
- Double-pulse resolution: 2 :math:`\times` quantisation size
- Dead time between groups: none
- Minimum interval between starts: 3.2 ns
- Up to 8000 Hits per Packet
- 5 to 0.625 GHz for bursts of up to 4096 starts
- 5 to 0.625 GHits/s per channel for bursts of up to 3900 stops
- 40 MHits/s per channel of sustained stops
- 60 MHits/s over all channels of sustained stops

For an extensive overview of all features and functions, please refer to the
`TimeTagger4 User Guide 
<https://download.cronologic.de/TimeTagger/TimeTagger4_User_Guide.pdf>`_.

.. toctree::
   :maxdepth: 2
   :numbered: 3
   :hidden:
   
   techdata
   revhistory

