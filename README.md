# arduimu_vD
clone of arduIMU version D variant see. https://code.google.com/p/ardu-imu/downloads/list

A great many thanks for their efforts.

I have included support for the EM 406 which requires the addition of the '\r\n' at the end of each configuration instruction.

I have also set the baud to 38400 for some reason, can't remember.

I aim to use this with the freeboard so I am only really interested in the magnetic bearing (without declination) and the
GPS location (and direction of travel).  So I will change the output for this benefit.

I have a hunch I will use the DCM at some stage, probably an artificial horizon to stop me throwing up ;-)