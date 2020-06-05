# USB power switcher

When connecting the Seer Electronics USB power switcher two USB devices are attached, one is the downstream port and the other is a virtual serial port.

The serial port is used to select power modes on the downstream port and can be controlled with any terminal program. Configure the port for 115200 bps, 8 data bits, no parity and 1 stop bit.

The following commands are available:

   * poff: Power off USB port
   * psdp: Activate SDP mode
   * pcdp: Activate CDP mode
   * pdivider: Activate DCP divider mode
   * pdcp: Activate DCP mode
   * p?: Show the currently selected mode
