TimeTagger Modules Integration Guide
====================================

.. only:: html

    .. image:: _static/TDC-Module_3D.png
      :alt: 3D image of a TimeTagger Module
      :align: center
      :scale: 100%

.. raw:: latex

   \RaggedRight

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
`TimeTagger <https://www.cronologic.de/product/timetagger>`_ TDC cards.
As such, they are ideally suitable in applications that do require a
**compact form factor**, **high data-acquisition** rates,
and low **multiple-hit** dead time.

This Integration Guide provides an overview of the modules operation and 
installation requirements. An overview of the **functionality** and the **C 
API** can be found in the
`TimeTagger4 User Guide <https://download.cronologic.de/TimeTagger/TimeTagger4_User_Guide.pdf>`_.

.. raw:: latex

    This Integration Guide is also available online at
    \href{https://docs.cronologic.de/timetaggermodule/}{docs.cronologic.de/timetaggermodule}.
    \vspace{-\baselineskip}

.. "only html" and "raw latex" is to fix section numbering in the PDF output
   in the index page

.. only:: html

    Module Overview
    ---------------

.. raw:: latex

    \phantomsection
    \addcontentsline{toc}{section}{Module Overview}
    \section*{Module Overview}

`cronologic <https://www.cronologic.de>`_ offers the 
`TimeTagger4-10G <https://www.cronologic.de/product/timetagger>`_ boards
as a modular version, as well, providing:

**Space-saving installation**
    All TimeTagger modules can be installed via board-to-board connectors with 
    minimal hardware effort.

**Integrate at minimum cost**
    Our TimeTagger4 TDC modules are the perfect choice if you are looking for
    picosecond resolution at the best possible price/performance ratio.

**Use the TiGer timing generator**
    Control your device with periodic pulse patterns, the exact timing of which
    is measured by the TDC. You can use any input channel of our module to 
    output these pulses.

.. only:: html

    Features
    --------

.. raw:: latex

   \phantomsection
   \addcontentsline{toc}{section}{Features}
   \section*{Features}

- 4-channel common-start TDC module
- Quantization (measurement resolution): 100 ps
- Double-pulse resolution: 200 ps
- Dead time between groups: none
- Minimum interval between starts: 3.2 ns
- Up to 8000 Hits per Packet
- 5 to 0.625 GHz for bursts of up to 4096 starts
- 5 to 0.625 GHits/s per channel for bursts of up to 3900 stops
- 40 MHits/s per channel of sustained stops
- 60 MHits/s over all channels of sustained stops

For an extensive overview of all features and functions, please refer to the
`TimeTagger4 User Guide <https://download.cronologic.de/TimeTagger/TimeTagger4_User_Guide.pdf>`_.

.. toctree::
   :maxdepth: 2
   :numbered: 3
   :hidden:
   
   hardware
   techdata
   revhistory

