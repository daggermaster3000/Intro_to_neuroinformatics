

**nfet**
The drain voltage and the source voltage should be greater or equal to the bulk voltage (for an **nfet**), so that there is a reverse biais, that implies:

- $V_{sb}=V_{s}-V_{b}\geq 0$
- $V_{db}=V_{d}-V_{b}\geq 0$

This guarantees only a small reverse leakage current (most of the current will flow in the channel). 
In an **nfet** the n+ region biaised at **the higher voltage** is called the **drain** and the other is called the source. The positive flow of current is from **drain to source**. 
The bulk is usually tied to the lowest voltage.




**pfet**
The p+ regions should be biased negatively to the bulk to reverse biais the pn junctions.

- $V_{sb}\leq 0$
- $V_{db}\leq 0$

The **n-well** of the pfet should be biased higher than the p- substrate. For a pfet the p+ region which is biased at the **higher voltage** is called the **source** and the other, the **drain**. I flows from the **source to the drain**.
The bulk is usually tied to the highest voltage supplied to the chip. In an **n-well**, the substrate is connected to $Vss$ and the well to $Vdd$.


