From ROB: 4/10/2016
  This RFM69 library implements the SPI TRANSACTION patch that overcomes multiple SPI devices deadlock.
  See https://lowpowerlab.com/forum/moteino/moteino-w5100-ethernet-spi-support-spi_has_transaction/msg5132/#msg5132 
  It includes a work around to make these changes compatible with ESP8266 micro-controllers.
  Despite the fact that there is no version management, the source code reference of this library is the one downloaded 
  from the https://github.com/LowPowerLab/RFM69 the 4/10/2016
  It also add extra definition introduced by TWS for the Control Byte used by secure RFM_SessionKey library.
  All modifications are surrounded by !!! ROB.  
