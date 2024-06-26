环境光传感器
============
:link_to_translation:`en:[English]`

环境光传感器包含光照强度传感器、颜色传感器、紫外线传感器和兼具多种功能的传感器。

已适配列表
----------

+------------+---------------------------------+-------+----------+-------------------------------------------------------------------------------------------------------+----------+
| 名称       | 功能                            | 总线  | 供应商   | 规格书                                                                                                |硬件抽象层|
+============+=================================+=======+==========+=======================================================================================================+==========+
| BH1750     | Light                           | I2C   | rohm     | `规格书    <https://www.mouser.com/datasheet/2/348/bh1750fvi-e-186247.pdf>`__                         |  √       |
+------------+---------------------------------+-------+----------+-------------------------------------------------------------------------------------------------------+----------+
| VEML6040   | Light RGBW                      | I2C   | Vishay   | `规格书    <https://www.vishay.com/docs/84276/veml6040.pdf>`__                                        |  √       |
+------------+---------------------------------+-------+----------+-------------------------------------------------------------------------------------------------------+----------+
| VEML6075   | Light UVA UVB                   | I2C   | Vishay   | `规格书    <https://cdn.sparkfun.com/assets/3/c/3/2/f/veml6075.pdf>`__                                |  √       |
+------------+---------------------------------+-------+----------+-------------------------------------------------------------------------------------------------------+----------+

API 参考
----------

以下 API 实现了对环境光传感器的硬件抽象，用户可直接调用该层代码编写传感器应用程序，也可以使用 :doc:`sensor_hub <sensor_hub>` 中的传感器接口，实现更简单的调用。

.. include-build-file:: inc/light_sensor_hal.inc
