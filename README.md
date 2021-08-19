# ftdi_dumps
FTDI EEPROM dumps for common JTAG FPGA programmers mostly pulled from https://gist.github.com/rikka0w0/24b58b54473227502fa0334bbe75c3c1. To flash a binary, run the following command.

	ftdi_eeprom --flash-eeprom <config-file>

| conf file | chip |
| --- | --- |
| digilent_hs2.conf | FT232H |
| arrow_ftdi.conf | FT2232H |
| digilent_smt1.conf | FT2232H |
| pynqz2_ftdi.conf | FT2232H |
| ft4232h.conf | FT4232H |
