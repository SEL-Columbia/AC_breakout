todo:

bigger holes for shunt resistor

low current fuse or varistor on probe points

purpose:


board allows for direct probing of AC voltages and the voltage across a
shunt resistor.  this permits the power measurements of loads.

the voltage source is connected via the input terminal block and the
load is placed on the output terminal block.

the voltage divider is a 100:1 voltage divider.
R1:
1.0MQBK-ND
CFR-25JB-1M0

R2:
10KQBK-ND
CFR-25JB-10K

eagle footprint
0309/10 has about 30 mil opening

the cfr-25 is 6.3mm x 2.4mm with a lead diameter of 0.55mm.
(0.25 inch x 0.094 inch lead diameter 0.022 inch)
voltage divider load:
This 1 megohm voltage divider draws a current of 230 microamps on a
230VAC load.

these are yageo 1/4 watt
package size
layout size


trace resistance:


banana jacks and test probe loops are provided to probe voltages.

shunt resistor:
Yageo RSF200JB-1R0
(digikey 1.0W-2-ND)
the shunt resistor is a Yageo RSF200 (L = 15.5mm D = 5.0mm lead = 0.8mm)
(0.61 inch x 0.20 inch lead diameter 0.031 inch)
the lead diameter is then 31.5 mils.
for the shunt resistor, i'm using a modified 0309/12
package size in eagle with a pad hole size of 51 mils to accomodate
the larger diameter leads.  the standard hole size was about 30 mils and
made it difficult to rework the shunt resistor.

the eagle 0617/17 package has a 0.04 drill on the pad which gives
about 10 mils of clearance.


power handling:
A 1 ohm resistor dissipates 1 W of power at a 1 A load.  At 230V this
is a 230W load and at 120VAC this is a 120W load.  This design will use
a 2W rated resistor.


