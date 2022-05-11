# hyperv_windows_home

How to install hyperv on Windows home

## installation

The batch script downloads the hyperv packages and installs them.

Tested successfully on Windows 11 home.

## network

I had some network issue and I solved by sharing my wifi connection to a new virtual network and using external network VMware Virtual Adapter for VMnet8.
After that, the VM has internet connection. Trying to attach to ethernet PCi driver or wifi driver failed all the time with different error message.
