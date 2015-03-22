## Using Ettus Research USRPs

All peripheral USRPs that are supported by the installed UHD version can
directly be used while running this live system. For USB devices, they simply
need to be connected to a USB port; Ethernet-based devices require a specific
network configuration which can easily be set up using network manager.

UHD and GNU Radio provide several UHD-specific utilities which can be used
to test functionality. To bring up a device reliably and test both transmit
and receive capabilities, these three tools are highly recommended:

* `uhd_usrp_probe`: Run this on the command line to detect and probe a device.
   It will print out information on all detected peripherals, such as
   available bandwidths, rates, and frequencies, GPS controllers etc.
   If this does not succeed, check the device shows up on the network
   or USB.
* `uhd_fft`: This is a very simple spectrum analyzer tool. By playing
   with the center frequncy and gain settings, this can be used to
   check if receive capabilities are working as intended.
* `uhd_siggen_gui`: A graphical tool to transmit simple signals, such
   as sinusoids. Similar to the previous tool, you can use this to
   test transmit features.
