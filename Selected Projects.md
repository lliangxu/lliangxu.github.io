---
layout: page
permalink: /project/index.html
title: Selected Projects
---

Selected Projects
--------------------
1. **MicroEC** [TPDS 2024]
	- This project proposes a new workflow to deploy erasure coding in disaggregated memory storage system. 
	- I design the smart coding stack and fine-granulariity pipeline parallism. This project is implemented atop Apache Crail. 
2. **SelectiveEC** [HotStorage 2020, TPDS 2022]
	- This project proposes a balanced scheduling module, SelectiveEC, to dynamically select some stripes to be reconstructed in a batch, and select source and replacement nodes for each reconstruction task. It achieves balanced network recovery traffic, computing resources and disk I/Os against single node failure in erasure-coded storage systems.
	- I design the scheduling algorithm, build the SelectiveEC prototype and validate it by simulation. 
3. **PDL** [INFOCOM 2020, TC 2021]
	- This project proposes an efficient PBD-based (Pairwise Block Design) Data Layout, PDL, to speed up data repair for single node failure in mixed erasure-coded distributed storage systems. It achieves almost uniform distribution, and higher repair performance due to reduced cross-rack traffic and load balance of read and write I/Os during repair process.
	- I design the data distribution method, and the corresponding failure recovery scheme. And I also implement them in Hadoop 3.1.1. 
4. **D<sup>3</sup>** [IPDPS 2019, TPDS 2020]
	- The proposed distribution D<sup>3</sup> uniformly distributes data/parity blocks among nodes in large scale erasure-coded distributed storage systems, and minimizes the cross-rack repair traffic against a single node failure. 
	- I integrate the distribution D<sup>3</sup> into HDFS-EC module of Hadoop 3.1.0 and evaluate the repair performance over Reed-Solomon codes. In the journal version, I extend it to locally repairable codes, provide efficient strategy to maintain the D<sup>3</sup> data layout after recovery, and conduct more experimental evaluations.
5.  **A Note on One Weight and Two Weight Projective Z<sub>4</sub>-codes** [TIT 2017]
   - This is the work in my undergraduate.
   - I solve the open problems about algebraic codes, moreover, I work out the diophantine problem and then give the sufficient conditions for the nonexistence of two-Lee weight projective codes over Z<sub>4</sub> with type 4<sup>k<sub>1</sub></sup>2<sup>k<sub>2</sub></sup>. 
