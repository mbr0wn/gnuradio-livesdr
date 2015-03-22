## Content

This DVD comes with a pre-installed GNU Radio as well as many
out-of-tree modules.

### GNU Radio Companion

You can launch the GNU Radio Companion (GRC) either from the
command line, by running the command `gnuradio-companion`, or
by clicking the GRC icon on the desktop.

There are a great number of examples for GRC under the `/usr/local/share`
directory, which are a great way to learn about how GNU Radio
applications may look like.

### PyBOMBS

PyBOMBS was used to install all GNU Radio-related software,
including GNU Radio itself, during the ISO creation process,
and is also installed on this DVD, allowing you to query
installation status and/or install other modules.

You can find the pre-installed GNU Radio in `/usr/local/src/pybombs`.
Try running a command such as `./pybombs help` to get started.

### Out-of-tree modules

There are a great number of pre-installed out-of-tree modules (OOTs)
on this DVD. As mentioned before, most provide GRC files as examples,
which serve as a good starting point to explore these OOTs. Also,
most add blocks to GNU Radio which will be available through GRC.

### Device drivers

This DVD can run the following hardware without installing additional
drivers:

* All Ettus Research devices (USRPs)
* All RTL-SDR devices that are supported by gr-osmosdr
* HackRF
* BladeRF


