# awesome-system-paper-list
A list for computer system papers reading

# Datacenter Systems

## Workload and Application Survey

### Profiling Survey

- [Profiling a warehouse-scale computer](https://dl.acm.org/doi/pdf/10.1145/2749469.2750392) `ISCA15`

### Other Related

- [Telescope: Telemetry for Gargantuan   Memory Footprint Applications](https://www.usenix.org/system/files/atc24-nair.pdf) `ATC24`
- [Ripple: Profile-Guided Instruction Cache Replacement for Data Center Applications](https://par.nsf.gov/servlets/purl/10271670) `ISCA21`

## Disaggregate memory

### Survey

- [Disaggregated Memory in the Datacenter: A Survey](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10056149)

### RDMA Swap Approach

- [Efficient Memory Disaggregation with Infiniswap](https://www.usenix.org/system/files/conference/nsdi17/nsdi17-gu.pdf)  `NSDI17`
- [LegoOS](https://www.usenix.org/system/files/osdi18-shan.pdf) `OSDI18`
- [Can Far Memory Improve Job Throughput?](https://dl.acm.org/doi/pdf/10.1145/3342195.3387522)  (Fastswap)  `Eurosys20`
- [Semeru](https://par.nsf.gov/servlets/purl/10227338) `OSDI20`
- [Hermit](https://www.usenix.org/system/files/nsdi23-qiao.pdf) `NSDI23`
- [Canvas](https://www.usenix.org/system/files/nsdi23-wang-chenxi.pdf) `NSDI23`
- [Atlas](https://www.usenix.org/system/files/osdi24-chen-lei.pdf) `OSDI24`

### Library-based Approach

- [AIFM: High-Performance, Application-Integrated Far Memory](https://www.usenix.org/system/files/osdi20-ruan.pdf) `OSDI20`



## Network and Distributed Systems

### Interconnect Optimization

- [LITE Kernel RDMA Support for Datacenter Applications (ucsd.edu)](https://cseweb.ucsd.edu/~yiying/LITE-sosp17.pdf) `SOSP17`

### Schedule

- [Shenago](https://www.usenix.org/system/files/nsdi19-ousterhout.pdf) `NSDI19`
- [Caladan](https://www.usenix.org/system/files/osdi20-fried.pdf) `OSDI20`
- [Junction](https://www.usenix.org/system/files/nsdi24-fried.pdf) `NSDI24`

### Distributed

- [Nu](https://www.usenix.org/system/files/nsdi23-ruan.pdf) `NSDI23`

### RPC

- [Datacenter RPCs can be General and Fast](https://www.usenix.org/system/files/nsdi19-kalia.pdf) `NSDI19`



## Exploring Unused Hardware Resource

### SMT

- [ Stretch: Balancing QoS and Throughput for Colocated Server Workloads on SMT Cores](https://ease-lab.github.io/ease_website/pubs/STRETCH_HPCA19.pdf) `HPCA19`
- [Enhancements for Hyper-Threading Technology in the Operating System](https://www.usenix.org/legacy/publications/library/proceedings/wiess02/tech/full_papers/nakajima/nakajima.pdf) `WIESS02`

### Cache OPT

- [Ripple: Profile-Guided Instruction Cache Replacement for Data Center Applications](https://par.nsf.gov/servlets/purl/10271670) 

## PL4Sys

- [Harvesting Idle Memory for Application-Managed  Soft State with Midas](https://www.usenix.org/system/files/nsdi24-qiao.pdf) `NSDI24`



## Microservice

- [CRISP: Critical Path Analysis of Large-Scale  Microservice Architectures](https://www.usenix.org/system/files/atc22-zhang-zhizhou.pdf) `ATC22`
- [Datacenter Architectures for the Microservices Era](https://deepblue.lib.umich.edu/bitstream/handle/2027.42/167978/miramir_1.pdf?sequence=1)`Phd dissertion`

# CPU Micro Architecture

## Performance Analysis

### Top-Down Analysis (TMA)

- [A Top-Down Method for Performance Analysis and Counters Architecture](https://rcs.uwaterloo.ca/~ali/cs854-f23/papers/topdown.pdf) `ISPASS14`

### Micro Analysis

- [uops.info: Characterizing Latency, Throughput, and Port Usage of Instructions on Intel Microarchitectures (arxiv.org)](https://arxiv.org/pdf/1810.04610) `ASPLOS19`

## Cache && TLB Improvement

- [Improving the Utilization of Micro-operation Caches in x86 Processors](https://jbk5155.github.io/publications/MICRO_2020.pdf) `MICRO20`
- [Rebooting Virtual Memory with Midgard](https://www.cs.yale.edu/homes/abhishek/sidgupta-isca21.pdf) `ISCA21`

### ICache

- [Ripple: Profile-Guided Instruction Cache Replacement for Data Center Applications](https://par.nsf.gov/servlets/purl/10271670) `ISCA21`

# Emerging Hardware

## CXL

- [Pond: CXL-Based Memory Pooling Systems for Cloud Platforms (huaicheng.github.io)](https://huaicheng.github.io/p/asplos23-pond.pdf) `ASPLOS23`



# PL

### Code Translation

- [Don’t Write, but Return: Replacing Output Parameters with Algebraic Data Types in C-to-Rust Translation](https://dl.acm.org/doi/pdf/10.1145/3656406) `PLDI24`





飞光飞光，劝尔一杯酒。
吾不识青天高，黄地厚。
唯见月寒日暖，来煎人寿。
食熊则肥，食蛙则瘦。
神君何在？太一安有？
天东有若木，下置衔烛龙。
吾将斩龙足，嚼龙肉，使之朝不得回，夜不得伏。
自然老者不死，少者不哭。
何为服黄金、吞白玉？
谁似任公子，云中骑碧驴？
刘彻茂陵多滞骨，嬴政梓棺费鲍鱼。

​					李贺《苦昼短》