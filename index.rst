SampleDoc: Docs /Developers Italia
==================================

Questo è un documento di test. E' pertanto un E'.

Indice dei contenuti
--------------------

.. warning:: 
        Attenzione! Lingua sconosciuta


.. note:: 
        Questa è una nota


.. important:: 
        Questo invece è importante


.. _fig1:
.. figure:: _img/logo.png
   :scale: 50

   Questa è la didascalia alla figura.


Questo testo continua dopo l'immagine :numref:`fig1`, cui fa riferimento.

.. _tab1:

.. table:: Titolo della tabella
   
   +--------+-----------+-----------------------+
   | numero | oggetto   | nome del protagonista |
   +========+===========+=======================+
   | 1      | mela      | Biancaneve            |
   +--------+-----------+-----------------------+
   | 2      | scarpetta | Cenerentola           |
   +--------+-----------+-----------------------+


Questa invece è una tabella, cui posso fare riferimento (vedi :numref:`Tabella %s <tab1>`).


.. tabularcolumns:: |p{1cm}|p{7cm}|

.. csv-table:: Lorem Ipsum
   :file: lorem-tab.csv 
   :header-rows: 1 
   :class: longtable
   :widths: 1 1



