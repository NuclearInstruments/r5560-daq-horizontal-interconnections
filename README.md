# R5560/SE DAQs horizontal interconnection 

This document explains how to use the FLAG signals and fast horizontal link between DAQ.
Each DAQ is directly connected to the DAQ on the right and on the left with two kind of link:
•	FLAG links: two links per side (right/left), one in the direction left to right (left out, right in) the other in the opposite direction right to left (left out, right in). Flag has no propagation delay and can be used as trigger/busy/timestamp purpose
•	H-LINK: two link per side (right/left), one in the direction left to right (left out, right in) the other in the opposite direction right to left (left out, right in). H-LINK is 64 bit wide and can be used to transport information between two DAQ. H-LINK has a latency of about 300ns and the latency is not deterministic.
