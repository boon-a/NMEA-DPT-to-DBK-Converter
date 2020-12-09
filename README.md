# NMEA-DPT-to-DBK-Converter
The NMEA0183 DPT sentence contains the depth below the transducer and the offset of the transducer from the bottom of the keel. I want to convert the DPT sentence into a DBK sentence, which has the depth below the keel (ie depth below the transducer plus the transducer offset). I want to display DBK on a repeater in the cockpit (and not depth below the transducer, as it currently does).
I am using a RedBoard DEV-13975 and a Transceiver Breakout MAX232.
