# from 775 (2008) </br>
# 45nm to 10nm </br>

This Historic Study / Analisys of CPU processors, is focused around intel 4-core CPUs, </br>
the idea is to have a clear view of the improvement of similar CPUs since socket 775 "2008" </br>
will ignore older gens because there was No Quad-cores from intel, </br>
Apple did had G5 Quad-core in (2005), but was 2x PPC6 Dual-core 970MP CPU's, Not a single Quad-core, </br>
also will ignore [13th & 14th gen](https://www.intel.com/content/www/us/en/support/articles/000099569/processors.html) because the [13th curse](https://en.wikipedia.org/wiki/Triskaidekaphobia) </br>
New Ultra "15th gen"+A.I. will see... </br>

Improvement can be measured in different ways: </br>
Clock vs. Clock: Performance gain at same clock speeds, </br>
Watt vs. Watt, Performance gain at same Watts. </br>
New features vs. Features used by most people. </br>

### The LGA775 era: </br>
Probably Q6600 was the most popular, but... Q9650 was the 3rd best, The fastest under 100w "The Best Overall", </br>
QX9775 was the 1st, but 150w, small improvement, was about pushing the limits. </br>
QX9775 was the only that allowed multi-cpu boards. </br>
QX9770 was the 2nd but 136w, the power target for 4th next generations. </br>
pga478 was the last with Pin Grid Array CPU, 775 was the 1st with LGA "Land Grid Array".</br>
There were many [chipsets](https://en.wikipedia.org/wiki/List_of_Intel_chipsets#Core_2_chipsets) for 775, Core2 Era & Core2Quad, the most notable: 975x, P45, X38, X48 </br>
chipset transistor size from 130nm to 65nm, behind CPU 45nm, using older Fabs to make chipsets, New Fabs to make CPUs </br>
everybody wished both were the same. </br>

### Next Gen LGA1366 </br>
There were many changes from 775 to 1366, most notable chipset: [X58](https://en.wikipedia.org/wiki/List_of_Intel_chipsets#LGA_1366,_LGA_2011,_and_LGA_2011-v3) / [5520](https://en.wikipedia.org/wiki/List_of_Intel_Xeon_chipsets#Dual_processor_Nehalem-based_Xeon_chipsets) </br>
makes some PCI cards incompatible, like Digidesign 001 driver v6.4 </br>
LGA1366 "Land Grid Aray" also introduced Tripple Channel DDR3 memory, many boards had issues broken traces, </br>
because pcb routing complexity "many layers & 1366 traces" combined with a socket mount pressure that does Not have a stop, </br>
many Heatsink screws could be over tightened, or screwed uneven, squashing & bending the PCB, there were No mounting plates, </br>
Boards that had Tripple Channel "6x memory slots" most only worked Dual-Channel "4-slots" with out errors in Memtest86+</br>
Windows Memory Diagnostic did Not detected memory errors in Tripple channel memory. </br>
some 775 had DDR3 but Dual-Channel, </br>
MacPro 4,1 / 5,1 (2009 / 2010 / 2012) lga1366 also had Dual-Channel design. </br>
i think Turbo v1.0 mode was also introduced in lga1366 </br>
Virtualization became standard, in 775 was optional. </br>

#### i7-930 / W3530 / X5630  </br>
X version combined with 5500 / 5520 chipset allowed boards with multi-cpus, also ECC Memory </br>
[i7-930](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_930-vs-intel_core_2_quad_q9650) has same clock 3GHz as Q9650 </br>
small improvement of +9% in Single-core, but has New AES instructions required by some software like Avid Composer 8.4 (2015) </br>
Windows8 required SSE2/NX/PAE in [(2014)](https://learn.microsoft.com/en-us/previous-versions/windows/it-pro/windows-8.1-and-8/dn482072(v=win.10)?redirectedfrom=MSDN) </br>
Windows8.1 required True [MPS 1.4](https://en.wikipedia.org/wiki/MultiProcessor_Specification) for some PCI cards / drivers, like Lynx AES16, some X58 boards did Not work. </br>

Multi-core: i7-930 has a New technology: </br>
HyperThreading, an improvement around ~25% in most CPU's, this case 27%. </br>
but requires software to be compiled to take advantage of Multi-Threads. </br>
Q9650 Single Core has a loss of -17% in Multi-Core "All Cores." </br>
i7-930 has a Net Gain of 103.2% in Multi-Thread "Single core loss in Multi-Core + Hyper Threading Gain." </br>

### The fastest 4-core of the LGA1366 era: </br>
[i7-975](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_975-vs-intel_core_2_quad_q9650) / [X5687](https://www.cpu-world.com/Compare/867/Intel_Xeon_X5687_vs_Intel_Xeon_X5690.html) / [W3580](https://www.cpu-world.com/Compare/862/Intel_Xeon_W3580_vs_Intel_Xeon_X5687.html) </br>
Single Core Q9650 is 77% vs. i7-975 "+29%". </br>
slight clock boost: 3.6GHz vs. 3GHz. </br>
In Multi-core i7-975 has a clock loss from 3.6Ghz to 3.33Ghz </br>
Q9650 is 63% vs. i7-975 in Multi-Thread "+58%". </br>
4-cores vs. 4c+4t "8-threads" </br>

There was a Faster 2-core [X5698](https://www.cpu-world.com/CPUs/Xeon/Intel-Xeon%20X5698%20-%20AT80614007314AA.html) </br>
very rare. </br>

### Next Gen:  </br>
MacPro 6,1 2013 Quad Core era. </br>
[E5-1620v2](https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_1620_v2-vs-intel_core_2_quad_q9650) </br>
In Single-core: Q9650 is 54% of an E5-1620v2 "85% improvement"</br>
44% in Multi-Thread, "2.27x improvement" </br>
E5-1620v2 has Higher Power Consumption, 130w vs. 95w "a 36% power increse." </br>
its an improved QX9770 136w "-6w" with New AES instructions like i7-930 / i7-975, </br>
smaller Transistor 22nm vs. i7-930 45nm / i7-975 32nm 130w, </br>
Quad-Channel Memory, Turbo mode and New AVX instructions, </br>
a slightly higher Clock boost. </br>
3.9GHz vs. 3.2Ghz in QX9770 136w / QX9775 150w </br>
3.6Ghz / 3.33Ghz in i7-975 130w </br>
3Ghz in Q9650 95w / [i7-930](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_930-vs-intel_core_2_quad_q9650) 130w. </br>
[QX9770](https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_1620_v2-vs-intel_core_2_extreme_qx9770) is 52% Single vs. E5-1620v2 "+92%" </br>
45% Multi-core a 2.22x increase in performance </br>
vs. QX9775 150w </br>
[QX9775](https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_1620_v2-vs-intel_core_2_extreme_qx9775) is 53% Single Core vs. E5-1620v2 +88% performance increase, </br>
45% Multi-Thread, also 2.22x </br>

The Goal of the E5-v2 CPU was to combine 12-cores in a Single CPU, </br>
previous generation LGA1366 required dual X5690 CPU's to have 12-Cores / 24-Threads in a single board, </br>
previous 775 required 2x QX9775 CPU's to have 8-cores in a single board, </br>
but that was an improvement most people did Not see. </br>
most software & operating systems are designed for a Fast Dual-Core CPU. </br>
in my opinion a Quad-core is the minimum to run a single Virtual Machine, </br>
a Dual-core can do it, but performance will be severe compromised. </br>
also a Quad-core has enough low power consumption for everyday use, Browsing internet, IP security cameras, etc... </br>
more cores is only required for High-demanding tasks, like CPU video encoding / transcoding h.264 h.265 video editing, etc... </br>
but video capture and encoding is better with a capture card that has dedicated DSP. </br>

QX9775 & QX9770 have +1% & +2% performance increase in Single-core vs. Q9650  </br>
with massive power consumption increase: +36% & +58%. </br>
E5-1620v2 has +85% performance increase in Single core vs. Q9650, </br>
with +43% power consumption, </br>
but... 12-core E5-2697v2 CPU vs. dual 6-core X5690 CPUs had a [-50% power](https://www.cpu-monkey.com/en/compare_cpu-intel_xeon_e5_2697_v2-vs-intel_core_i7_990x) reduction, same 130w, </br>
with a Clock Frequency loss of: 2.70 GHz / 3.5 GHz "Turbo" vs. 3.46 GHz / 3.73 GHz (1-core) </br>
Not a -50% power consumption clock speed vs. clock speed. </br>
but E5-2697v2 has a slight performance boost of +6.3% Single-core with lower clock speed vs. i7-990x / X5690 / W3690. </br>

[i7-975](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_975-vs-intel_xeon_e5_1620_v2) is 82% Single-core of an E5-1620v2 "E5-v2 has 22% improvement" </br>
79% Multi-core of an E5-1620v2 = 26.5% improvement. </br>

### FastForward to 7th gen: </br>
[7700HQ = 10100T](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_7700hq-vs-intel_core_i3_10100t) same clock speeds 3.8Ghz, </br>
but 10100T has lower power consumption and more performance. </br>
HQ & T are Low Power versions. </br>
Q9650 is ~50% performance, </br>
[i7-7700HQ](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_7700hq-vs-intel_core_2_quad_q9650) & [i3-10100T](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_10100t-vs-intel_core_2_quad_q9650) </br>
Both 100% faster "2x" in Single core. </br>
small clock boost: </br>
3.8Ghz vs. 3Ghz = Not really 100% faster, if were running at same clock speed. </br>

[7700K](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i7_7700k-vs-intel_core_2_quad_q9650) the fastest 4c/8t of the 7th Generation. </br>
Q9650 is 38% vs. Single Core "2.63x" </br>
Multi-Thread is 29%-33% 4c+4t "8t" 3.22x </br>

### Around 7th & 8th gen:  </br>
MacPro 2019 with [W-32xx CPUs](https://github.com/juanpc2018/Best-CPUs-for-LGA-3647) similar to Gold 61xx 62xx </br>
W- CPUs are the server version of the 8th gen, with slightly lower clock speeds,  </br>
but ECC memory, and much more PCIe lanes. </br>
older boards like 975x "high end" had 1x PCIe x16 or 2x PCIe x8 "16-lanes" </br>
X48 boards had 2x PCIe x16, "32 lanes" </br>
most gamer boards have limited PCIe lanes,  </br>
Not designed for adding more PCIe cards without halving speed, </br>

[i3-8350K](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_8350k-vs-intel_core_2_quad_q9650) the fastest of the 8th gen, No HyperThreading. </br>
Q9650 is 40% vs. single core "2.5x faster" </br>
40% vs. Multi-Core same 4c vs, 4c No HT. </br>
45nm vs, 14nm </br>
same Monolithic design </br>
2008 vs. 2017 </br>
95w vs 91w "slight power saving = drastic power efficiency increase" </br>
4Ghz vs. 3GHz.  </br>

### 9th gen </br>
[i3-9350K](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_9350k-vs-intel_core_2_quad_q9650) </br>
same power vs. 8350K = 91w </br>
but... </br>
Q9650 is 37% in Single Core "-3%" </br>
33% "-7%" in Multi-Core. </br>

### 10th gen </br>
[i3-10100](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_10100-vs-intel_core_2_quad_q9650) No-T, the fastest 4c + HT "4t" </br>
Q9650 is 40% Single-core = same vs. 8350K,  </br>
i3-9350K is faster +3% in Single Core,  </br>
but i3-10100 power consumption is much lower. </br>
65w = -26w "Big Power Efficiency improvement" </br>
31% Multi-Thread, 10100 Non-T is faster in Multi-Thread because has Hyper Threading vs. 8350k and 9350k. </br>
its a side improvement. </br>

### 11th gen </br>
[i3-1110B](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_11100b-vs-intel_core_2_quad_q9650) </br>
Q9650 is 33% both Single core or Multi Thread 4c+4t </br>
Faster than 9350k in Single Core, </br>
same in Multi-Thread. </br>
65w same as 10100 No-T </br>
Slight improvement in Single Core, </br>
Slight loss in Multi-Thread vs. i3-10100 No-T </br>

### 12th gen: </br>
[i3-12100T](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_12100t-vs-intel_core_2_quad_q9650) </br>
Q9650 is 28% vs. in Single  </br>
28% in Multi-Thread. "+3.57x" </br>
T is a low power version, </br>

[i3-12100](https://www.cpu-monkey.com/en/compare_cpu-intel_core_i3_12100-vs-intel_core_2_quad_q9650) No-T </br>
Q9650 is 27%-28% in Single Core ~3.7x </br>
21%-24% in Multi-Thread vs 4c+4t "4.16x" </br>
Average 3.93x almost 4x. </br>
with 60w vs. 95w </br>
10nm vs. 45nm </br>
Newer SSE4.2, AVX2, AVX2+ instructions that boost performance in software updated with compilers designed for those instructions. </br>

a reduction from 45nm to 10nm "4.5:1" </br>
did Not bring an improvement of "4.5x" in Single-core</br>
with a power reduction of 50%, was close 63% 3.7x. </br>
In Theory Power consumption reduction should be 1/4.5 = 21.1w, Not 60w </br>
But... New CPU's have New instructions, New circuits, More Cache, Increased complexity, Higher Clock, that increase power consumption. </br>
Not a direct comparison. </br>

improvement limits reason probably is the [Black Silicon](https://semiengineering.com/knowledge_centers/low-power/techniques/dark-silicon/) areas "Dead Silicon" </br>
1/3 "33.3%" in 20nm upto 80% in 5nm. </br>

as a side Note, the nightmare of Board manufacturers is the dream of vintage collectors, </br>
a New re release CPU's with smaller transistors, but pin compatible with older boards. </br>
Anniversary Editions. </br>
