===============================
Host-Side Data Types and Macros
===============================

The host side API exposes several layers to drivers, some of which are
more necessary than others. These support lifecycle models for host
side drivers and devices, and support passing buffers through usbcore
to some HCD that performs the I/O for the device driver.

.. kernel-doc:: include/linux/usb.h
   :internal:
