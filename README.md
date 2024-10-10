# from 775 (2008) </br>
# 45nm to 10nm </br>

This Historic Study / Analisys of CPU processors, is focused around intel 4 core CPUs, </br>
the idea is to have a clear view of the improvement of similar CPUs since socket 775 "2008" </br>
will ignore 13th gen & 14th gen because the [13th curse](https://en.wikipedia.org/wiki/Triskaidekaphobia) </br>
New Ultra "15th gen"+A.I. will see.. TBU. </br>

### The LGA775 era: </br>
Q9650 "was the 3rd best", The fastest under 100w "The best overall", </br>
QX9775 was the 1st, but 150w, small improvement, was about pushing the limits of that transistor size 45nm. </br>
also QX9775 was the only that allowed multi-cpu boards. </br>
QX9770 was the 2nd but 136w, the power target for 4th next generations. </br>
775 was the last with Pin Grid Array CPUs. </br>
There were many [chipsets](https://en.wikipedia.org/wiki/List_of_Intel_chipsets#Core_2_chipsets) for 775, Core2 Era & Core2Quad, the most notable: 975x, P45, X38, X48 </br>
chipset transistor size from 130nm to 65nm, behind CPU 45nm, using older Fabs to make chipsets, New Fabs to make CPUs </br>

### Next Gen LGA1366 </br>
There were many changes from 775 to 1366, most notable chipset: [X58](https://en.wikipedia.org/wiki/List_of_Intel_chipsets#LGA_1366,_LGA_2011,_and_LGA_2011-v3) / [5520](https://en.wikipedia.org/wiki/List_of_Intel_Xeon_chipsets#Dual_processor_Nehalem-based_Xeon_chipsets) </br>
makes some PCI cards incompatible, like Digidesign 001 driver v6.4 </br>
LGA1366 "Land Grid Aray" also introduced Tripple Channel DDR3 memory, many boards had issues broken traces, </br>
because pcb routing complexity "many layers & 1366 traces" combined with a socket mount pressure that does Not have a stop, </br>
many Heatsink screws could be over tightened, or screwed uneven, squashing & bending the PCB, </br>
Boards that had Tripple Channel "6x memory slots" most only worked Dual-Channel "4-slots" with out errors in Memtest86+</br>
Windows Memory Diagnostic did Not detected memory errors in Tripple channel memory. </br>
some 775 had DDR3 but Dual-Channel, </br>
MacPro 4,1 / 5,1 (2009 / 2010 / 2012) lga1366 also had Dual-Channel design. </br>
i think Turbo v1.0 mode was also introduced in lga1366 </br>
Virtualization became standard, in 775 was optional. </br>

#### i7-930 / W3530 / X5630  </br>
X version combined with 5500 / 5520 chipset allowed boards with multi-cpus, also ECC Memory </br>
same clock 3GHz as Q9650 </br>
only has a small improvement +9% in Single Core, but has New AES instructions. </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_930-vs-intel_core_2_quad_q9650 </br>
Mult-core: i7-930 has a New technology: </br>
HyperThreading, an improvement around ~25% in Multi-Threads, this case 27%. </br>
but requires software to be compiled to take advantage of Multi-Threads. </br>
Q9650 Single Core has a loss of -17% in Multi-Core "All Cores." </br>
i7-930 has a Net Gain of 103.2% in Multi-Thread "Single core loss in Multi-Core + Hyper Threading Gain." </br>

### The fastest 4-core of the LGA1366 era: </br>
i7-975 / X5687 / W3575 </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_975-vs-intel_core_2_quad_q9650 </br>
Single Core Q9650 is 77% vs. i7-975 "+29%". </br>
slight clock boost: 3.6GHz vs. 3GHz. </br>
In Multi-core i7-975 has a clock loss from 3.6Ghz to 3.33Ghz </br>
Q9650 is 63% vs. i7-975 in Multi-Thread "+58%". </br>
4-cores vs. 4c+4t "8-threads" </br>

### Next Gen:  </br>
MacPro 6,1 2013 Quad Core era. </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_1620_v2-vs-intel_core_2_quad_q9650 </br>
Q9650 is 54% in Single Core vs. E5-1620v2 "85% improvement</br>
44% in Multi-Thread, "2.27x improvement" </br>
E5-1620v2 has Higher Power Consumption, </br>
its an improved QX9770 136w "-6w" with New AES instructions like i7-930 / i7-975, </br>
smaller Transistor 22nm vs. i7-930 45nm / i7-975 32nm 130w, </br>
Quad-Channel Memory, Turbo mode and New AVX instructions, </br>
but those improvements does Not translate to Big improvements in power consumption or performance. </br>
Only a slightly higher Clock boost. </br>
3.9GHz vs. 3.2Ghz in QX9770 136w / QX9775 150w </br>
3.6Ghz / 3.33Ghz in i7-975 130w </br>
3Ghz in Q9650 95w. </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_1620_v2-vs-intel_core_2_extreme_qx9770 </br>
Qx9770 is 52% Single vs. E5-1620v2, </br>
45% Multi. </br>
or vs. QX9775 150w </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_1620_v2-vs-intel_core_2_extreme_qx9775 </br>
Q9775 is 53% Single Core vs. E5-1620v2 </br>
45% Multi-Thread. </br>
The Goal of the E5-v2 CPU was to combine 12-cores in a Single CPU, </br>
previous generation LGA1366 required dual X5690 CPU's to have 12-Cores / 24-Threads in a single board, </br>
previous pga775 required 2x QX9775 CPU's to have 8-cores in a single board. </br>
but that was an improvement most people did Not see, </br>
most software and operating systems are designed for Fast Dual-Core CPU's, </br>
in my opinion a Quad-Core is the minimum system to run a single Virtual Machine, </br>
a dual-core can do it, but performance will be severe compromised. </br>

QX9775 & QX9770 have +1% & +2% increase Single core vs. Q9650,  </br>
with massive power consumption increase </br>
+36% & +58%. </br>
E5-1620v2 has +85% performance increase in Single core vs. Q9650, </br>
with +43% power consumption, </br>
but... 12-core CPU E5-v2 vs. dual 6-core X5690 CPUs had a [-50% power](https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_2697_v2-vs-intel_core_i7_990x) reduction, same 130w, </br>
with a Clock Frequency loss of: 2.70 GHz / 3.5 GHz "Turbo" vs. 3.46 GHz / 3.73 GHz (1-core) </br>
improvement was Not a true -50% power consumption same clock speed vs. same clock speed. </br>
E5-2697v2 has a slight performance boots +6.3% Single-Core with a lower clock speed vs. i7-990x / X5690 / W3590. </br>

https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_975-vs-intel_xeon_e5_1620_v2 </br>
i7-975 is 82% Single-core vs. E5-1620v2 "E5v2 has +22% improvement" </br>
79% Multi-core "+26.5% improvement" </br>

### FastForward to 7th gen: </br>
7700HQ = 10100T </br>
HQ & T are Low Power versions. </br>
Q9650 is 50%, </br>
Both are 100% faster "2x" in Single core. </br>
small clock boost: 3.8Ghz vs. 3Ghz = not really 100% faster if were running at same clock. </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_7700hq-vs-intel_core_2_quad_q9650 </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_10100t-vs-intel_core_2_quad_q9650 </br>

7700K the fastest 4c/8t of the 7th Generation. </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_7700k-vs-intel_core_2_quad_q9650 </br>
Q9650 is 38% vs. Single Core. </br>
Multi-Thread is 29%-33% 4c+4t "8t"</br>

### Around 7th & 8th gen:  </br>
MacPro 2019 with W-35xx CPUs, similar to Gold 61xx 62xx </br>
W- CPUs are the server version of the 8th gen, with slightly lower clock speeds,  </br>
but ECC memory, and much more PCIe lanes. </br>
older boards like 975x "high end" had 1x PCIe x16 or 2x PCIe x8 "16-lanes" </br>
X48 boards had 2x PCIe x16, "32 lanes" </br>
most gamer boards have a limited PCIe lanes,  </br>
Not designed for adding more PCIe cards without halving speed, </br>

i3-8350K the fastest of the 8th gen, No HyperThreading. </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_8350k-vs-intel_core_2_quad_q9650 </br>
Q9650 is 40% vs. single core "2.5x faster" </br>
40% vs. Multi-Core same 4c vs, 4c No HT. </br>
45nm vs, 14nm </br>
same Monolithic design </br>
2008 vs. 2017 </br>
95w vs 91w "slight power saving = drastic power efficiency increase" </br>
4Ghz vs. 3GHz.  </br>

### 9th gen </br>
i3-9350K </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_9350k-vs-intel_core_2_quad_q9650 </br>
same power vs. 8350K = 91w </br>
but... </br>
Q9650 is 37% in Single Core "-3%" </br>
33% "-7%" in Multi-Core. </br>

### 10th gen </br>
i3-10100 No-T, the fastest 4c + HT "4t" </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_10100-vs-intel_core_2_quad_q9650 </br>
Q9650 is 40% Single-core = same vs. 8350K,  </br>
i3-9350K is faster +3% in Single Core,  </br>
but i3-10100 power consumption is much lower. </br>
65w = -26w "Big Power Efficiency improvement" </br>
31% Multi-Thread, 10100 Non-T is faster in Multi-Thread because has Hyper Threading vs. 8350k and 9350k. </br>
its a side improvement. </br>

### 11th gen </br>
i3-1110B </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_11100b-vs-intel_core_2_quad_q9650 </br>
Q9650 is 33% both Single core or Multi Thread 4c+4t </br>
Faster than 9350k in Single Core, </br>
same in Multi-Thread. </br>
65w same as 10100 No-T </br>
Slight improvement in Single Core, </br>
Slight loss in Multi-Thread vs. i3-10100 No-T </br>

### 12th gen: </br>
i3-12100T </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_12100t-vs-intel_core_2_quad_q9650 </br>
Q9650 is 28% vs. in Single  </br>
28% in Multi-Thread. "+3.57x" </br>
T is a low power version, </br>
i3-12100 "No-T" </br>
https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_12100-vs-intel_core_2_quad_q9650 </br>
Q9650 is 27%-28% in Single Core ~3.7x </br>
21%-24% in Multi-Thread vs 4c+4t "4.16x" </br>
Average 3.93x almost 4x. </br>
with 60w vs. 95w </br>
10nm vs. 45nm </br>
Newer SSE4.2, AVX2, AVX2+ instructions that boost performance in software updated with compilers designed for those instructions. </br>

a reduction from 45nm to 10nm "4.5:1" </br>
did Not bring an improvement of "4.5x" </br>
the reason probably is the [Black Silicon](https://semiengineering.com/knowledge_centers/low-power/techniques/dark-silicon/) areas "Dead Silicon" </br>
1/3 "33.3%" in 20nm upto 80% in 5nm. </br>
