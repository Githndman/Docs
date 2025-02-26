.. Introduction to BPI-STEAM documentation master file, created by
    sphinx-quickstart on Sun May 26 22:43:43 2019.
    You can adapt this file completely to your liking, but it should at least
    contain the root `toctree` directive.

BPI-STEAM 用户文档
=====================================================

.. Hint::

    本文档托管于 `BPI-STEAM <https://github.com/BPI-STEAM>`_ 组织。

认识 BPI-BIT 板子
---------------------------

BPI-BIT 是一款基于 ESP32 高性能芯片且兼容 micro:bit 设计的开源 STEAM 教育开发板。

.. image:: bpi-steam/readme/product.jpg
    :alt: 正面外观

.. toctree::
    :maxdepth: 2
    :caption: BPI-BIT

    bpi-steam/readme
    bpi-steam/driver

使用 Webduino 编程
---------------------------

用户通过烧写 Webduino 固件，就可以使用面向全世界的 Webduino Blockly 积木化在线编程。

.. toctree::
    :maxdepth: 2
    :caption: Webduino

    bpi-web/tutorials/index
    bpi-web/advanced/index
    bpi-web/modules/index

只需浏览器，即可随时查看云端和托管你的代码，配合 Github 上各种有趣的插件系统与多语言化环境，享受全世界流行的积木编程吧!

使用 MicroPython 编程
---------------------------

用户通过烧写 MicroPython 固件，就可以使用当下世界上最流行的 Python 语言进行编程。

提供丰富的 examples 配合专业 IDE 的支持（如：VsCode、PyCharm），以便您轻松地将代码从电脑传输到板子中，从而体验程序创作的无穷乐趣！

.. toctree::
    :maxdepth: 2
    :caption: MicroPython

    bpi-mpy/tutorials/index
    bpi-mpy/advanced/index
    bpi-mpy/samples/index
    bpi-mpy/modules/index
    mPython/docs/library/micropython/index.rst
    mPython/docs/library/pythonStd/index.rst

使用 Arduino 编程
---------------------------

.. Hint::

    Arduino 将不会阐述过多基础内容，请自行具备 C/C++ 的语言开发基础。

BPI-BIT 提供了入门 Arduino 的软件工具和最佳示例，这将成为你进入嵌入式专业开发的最低门槛。

.. toctree::
    :maxdepth: 2
    :caption: Arduino

    bpi-adu/tutorials/index
    bpi-adu/advanced/index
    bpi-adu/modules/index

拓展板支持
---------------------------

BPI-BIT 大幅度的兼容 microbit 的底座硬件设计与使用，你可以查看以下支持的 Microbit 的拓展板或根据拓展板设计方案进行拓展应用。

.. toctree::
    :maxdepth: 2
    :caption: 拓展板

.. 
.. toctree::
    :maxdepth: 2
    :caption: 引用区域
    mPython/docs/index
    micropython/docs/index
.. 

.. image:: _static/footer.png

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
