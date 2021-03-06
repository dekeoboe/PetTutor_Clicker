# PetTutor_Clicker
Uses Arduino Nano 33 BLE as clicker to trigger PetTutor. treat dispenser.  Initial sketch. The latest revision seems to maintain connection over the span of a 9v battery life.
THis is currently about 3 days - power and built-in LED are on full time while connected and the sketch loops to maintain connection with the feeder.  I'm working to reduce battery drain - looking at disabling the LEDs (power and built-in) and possibly changing
the handshake routine used to maintain the connection which is somewhat constrained by the PetTutor Feeder superisory timeout and BLE timeout specs.
