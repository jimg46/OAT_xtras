# OAT_xtras
OpenAstroTracker bits and pieces
Various objects and experiences found useful in setting up the OpenAstroTracker.
Use as you will at your own risk.
Jim Gardner

File 2020parallel_level.stl
End fixing for 10mm (nominal) bubble mounted into 2020 slot.
Use for both base levelling and on side of camera bar to indicate pitch is set to build latitude (ie bar level).

File 2020cross_level.stl
Fixing for 10mm (nominal) bubble mounted across 2020 slot.
Use on top of camera bar to indicate roll is set to 0 (ie bar level).

Files RAstop.stl, DECstop_arm.stl
Retro fit parts to ptrovide limits for the stepper motion, to activate the StallGuard option for TMC2209 drivers.
The RA stop fits over the upper-right spider arm and the DEC stop arm fits over the upper right bar support at the DEC wheel. In both cases, remove the 12mm M3 screws and replace with 16mm.

barmount_v2.stl
Mounts MPU6050 accelerometer and HMC5883 compass on the side of the camera bar. MPU6050 can be used to set the camera bar level in pitch and roll (see MPU calibration notes in this folder). Compass is too dfficult to calibrate to reasonable accuracy ("hard-iron correction").

OATMPU6050.pdf
Notes on performance of a bar-mmounted accelerometer and how to use it for DEC homing and initial polar alignment.



