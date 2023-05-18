HV 文档中文化
=============

:doc:`changelog` (2023.05 ~ )

硬件产品
-----------

- VSP Gx00 and VSP Fx00
- VSP G130 G/F350 G/F370 G/F700 G/F900
- :doc:`vsp_e_series`
- :doc:`vsp_e_series/replacement`

软件产品
-----------

- Dynamic Link Manager (HDLM)
- Remote Ops (Hi-Track)


**HVDocs** (/lu'make/) is a Python library for cooks and food lovers
that creates recipes mixing random ingredients.
It pulls data from the `Open Food Facts database <https://world.openfoodfacts.org/>`_
and offers a *simple* and *intuitive* API.

Check out the :doc:`usage` section :doc:`changelog` for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   changelog
   usage
   api
   markdown

Lumache has its documentation hosted on Read the Docs.


+-----+----------+------+---------------------+
| A   | B        | C    | C                   |
+=====+==========+======+=====================+
|     | 磁盘数量 | 最小 | 4                   |
+-----+----------+------+---------------------+
| 1   |          | 最大 | 24 (内部 NVMe)      |
+-----+----------+      +                     +
|     |          |      | 240 (SAS 接口 SSD)  |
+-----+----------+------+---------------------+
|     | 2        | 3    | 3                   |
+-----+----------+------+---------------------+