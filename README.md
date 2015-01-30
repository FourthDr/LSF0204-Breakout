LSF0204 Breakout Board
======================

Here are Eagle files for my LSF0204(D) Breakout Board.

<p align="center">
  <a href="image.png"><img src="https://github.com/ftruzzi/LSF0204-Breakout/blob/master/image.png" align="center" height="300"   width="300" ></a>
</p>


The LSF0204 is a 4-bit, bidirectional, multi-voltage level translator. More info and datasheet here: http://www.ti.com/product/lsf0204

##Features and parts list:

* **U1:** LSF0204(D) IC from Texas Instruments, TSSOP-14 package.
* **C1,C2:** 0.1uF 0805 package. These are decoupling caps.
* **R1-R8:** 4.7k-10k ohm, 0805 package. I2C pull-up resistors for every input/output.
* **R9:** 10k ohm, 0805 package. Pull-down resistor to GND, for LSF0204D: the EN pin is active low.
* **SJ1:** solder jumper to VA, connect for LSF0204 (non-D): the EN pin is active high.

You can visit my website at www.truzzi.me.

Any suggestions or comments are appreciated!
