# FCCM 2023 Poster Presentation
## Making BRAMs Compute: Creating Scalable Computational Memory Fabric Overlays
MD Arafat Kabir, Joshua Hollis, Atiyehsadat Panahi, Jason Bakos, Miaoqing Huang, and David Andrews
### Abstract
The increasing density of distributed BRAMs diffused throughout modern Field
Programmable Gate Array (FPGAs) is ideal for forming the core of scalable
processor in/near memory architectures for next-generation machine learning
applications. This can break the traditional von Neumann memory bottleneck that
limits concurrency and degrades energy efficiency. Ideally, processing density
should scale linearly with BRAM capacity, and clock frequencies should be set
by the read/write access times of the BRAM. Today’s automated tools are not
designed to optimize processing density to BRAM capacity which must be done by
hand. Moreover, in machine learning applications significant delay is incurred
while moving data for accumulation/reduction. The data movement network within
an array processor needs to be optimized to minimize this delay. This requires
careful design of the network pipeline and FPGA architecture-specific
optimizations. In this paper, we present a set of FPGA design specific
optimizations that can produce near optimal processing in/near memory
architectures. Results show the proposed approach generates Processing Blocks
that are as fast as the BRAM read/write access speed and their array size
linearly scales with the number of BRAMs in the FPGA. We observe an improvement
of performance by 2x, logic resource utilization by 2x, and accumulation delay
by 17x compared to prior published work.


![Poster](https://github.com/Arafat-Kabir/FCCM-2023-Poster/blob/main/other/poster-A0.svg?raw=true)