1) Resistors 
==================================

Voltage divider resistors for the alphasense 4-electrode gas sensors
-------------------------------------------------------------------------- 

* R1-R23 odd-numbered resistors (68K) and R2-R24 even-numbered resistors (20K) are paired. For example, R1 & R2 are paired, R3 & R4 etc.
* Each resistor pair is for one of the 12 analog inputs.
* The resistor pair form a voltage divider for scaling 0-5V sensor output to 0-1.2V analog input range (using 1.2V internal reference voltage).

Take the 68K resistors are solder these into each of the 12 odd-numbered positions from R1-R23 i.e. R1,3,5,7,9,11,13,15,17,19,21 and 23.

.. figure:: _static/1a.JPG
   :align:  center

Next, take the 20K resistors are solder these into each of the 12 even-numbered positions from R2-R24 i.e. R2,4,6,8,10,12,14,16,18,20,22 and 24.


.. figure:: _static/2b.JPG
   :align:  center

   
   
Pull-up resistors 
--------------------------------------------

* R25 and R26 are pull-up resistors for the amphenol particulate sensor (P10). Note, these will be likely removed in the next board revision.
* R29 and R30 are I2C pull-up resistors for the UEXT header 

Solder these resistors to the board as shown in the image below.

.. figure:: _static/5.JPG
   :align:  center

   
   

   
   
