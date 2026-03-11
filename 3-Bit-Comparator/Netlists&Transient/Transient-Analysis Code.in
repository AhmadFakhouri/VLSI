 Power Supply
vdd
VGND GND

 A = 010 --  A3=0, A2=1, Al=0
VINA1 A1 GND PWL (Ons OV, 10ns OV, R 0)
VINA2 A2 GND PWL (Ons Vdd, 10ns Vdd, R 0)
VINA3 A3 GND PWL (Ons OV, 10ns OV, R 0)

 B = 100 --  B3=1, B2=0, B1=0
VINB1 B1 GND PWL (Ons OV, 10ns OV, R 0)
VINB2 B2 GND PWL (Ons OV, 10ns OV, R 0)
VINB3 B3 GND PWL (Ons Vdd, 10ns Vdd, R 0)

. DC SWEEP VA3 0 5 0.05
WN 1 10 1
Vdd 3 5 1
. DC OP
 . PARAM WN=2u

. PARAM Vdd = 5V
.TRAN 0.1ns 100ns
.Options captab
.TEMP 125
.options converge=1 gmindc=1e-9

.GLOBAL Vdd GND
.LIB C:\Users\fakho\Downloads\CD-TRANNERT\Spice70\examplessaleh-exampletsmc3v.lib tsmc.tt
.PRINT DC V(A3) V(Y3)
.PRINT TRAN V(A-BIGGER) V(B-BIGGER)

Vdd

GND 5.0V
0