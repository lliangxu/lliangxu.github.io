---
layout: page
---

# About Me

<!-- <img src="https://llianglxu.github.io/caihanlin.jpg" class="floatpic" width="360" height="480"> -->

Here is **Liangliang Xu (徐亮亮)**.

Liangliang Xu is currently an associate professor at [Xidian University](https://en.xidian.edu.cn/). He received his Ph.D. degree in the School of Computer Science and Technology under the supervision of Prof. [Yinlong Xu](http://cs.ustc.edu.cn/2020/0828/c23235a460084/page.htm) and associate Prof. [Min Lyu](http://cs.ustc.edu.cn/2020/0906/c23239a460125/page.htm) at University of Science and Technology of China. He has published several papers in top conferences and journals of storage systems, including INFOCOM, ICPP, IPDPS, HotStorage, HotOS, TIT,  TC, TPDS and JPDC. 

His research interests include designing and building dependable techniques (theory + system), e.g., erasure coding (RS/LRC/MSR codes, etc), for distributed persistent/caching(in-memory) storage systems.


## Education

- *2019.09 - 2022.06*:    **Ph.D. degree, Computer Science**; [ADSL](https://adsl.ustc.edu.cn) lab, University of Science and Technology of China (Advisors: Prof. [Yinlong Xu](http://cs.ustc.edu.cn/2020/0828/c23235a460084/page.htm) & associate Prof.  [Min Lyu](http://cs.ustc.edu.cn/2020/0906/c23239a460125/page.htm)).
- *2017.09 - 2019.08*:    **M.S. degree, Computer Science**; [ADSL](https://adsl.ustc.edu.cn) lab, University of Science and Technology of China (Advisors: Prof. [Yinlong Xu](http://cs.ustc.edu.cn/2020/0828/c23235a460084/page.htm) & associate Prof.  [Min Lyu](http://cs.ustc.edu.cn/2020/0906/c23239a460125/page.htm)).
- *2013.09 - 2017.06*:   **B.S. degree, Information and Computer Science**; GPA: 3.69/4.0; Anhui University ( Advisor: Prof. [Minjia Shi](https://scholar.google.com/citations?user=kBajA4AAAAAJ&hl=zh-CN)).

Work Experience
----------
- *2024.04 - now*:  **Associate professor - Xidian University**
- *2022.08 - 2024.04*:  **Research Scientist - Huawei Cloud**
- *2020.10 - 2021.01*: **Software Engineer Intern - Huawei CloudBU**

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

Publications
----------

1. **A Note on One Weight and Two Weight Projective Z<sub>4</sub>-codes.**   
   Minjia Shi, **Liangliang Xu**, and Gang Yang.
   IEEE Transactions on Information Theory (TIT 2017), 63.1: 177-182. 
2. **D<sup>3</sup>: Deterministic Data Distribution for Efficient Data Reconstruction in Erasure-Coded Distributed Storage Systems.**   
   Zhipeng Li, Min Lv, Yinlong Xu, Yongkun Li and **Liangliang Xu**.
   The 33rd IEEE International Parallel & Distributed Processing Symposium (IPDPS 2019).
3. **PDL: A Data Layout towards Fast Failure Recovery for Erasure-coded Distributed Storage Systems.**
   **Liangliang Xu**, Min Lv, Zhipeng Li, Cheng Li and Yinlong Xu.
   IEEE International Conference on Computer Communications (INFOCOM 2020) .
4. **Deterministic Data Distribution for Efficient Recovery in Erasure-Coded Distributed Storage Systems.**
   **Liangliang Xu**, Min Lyu, Zhipeng Li, Yongkun Li and Yinlong Xu.
   IEEE Transactions on Parallel and Distributed Systems (TPDS 2020), 31.10: 2248-2262.
5. **SelectiveEC: Selective Reconstruction in Erasure-coded Storage Systems.**
   **Liangliang Xu**, Min Lyu, Qiliang Li, Lingjiang Xie and Yinlong Xu.
   The 12th USENIX Workshop on Hot Topics in Storage and File Systems (HotStorage 2020).
6. **A Data Layout and Fast Failure Recovery Scheme for Distributed Storage Systems with Mixed Erasure Codes.** 
   **Liangliang Xu**, Min Lyu, Zhipeng Li, Cheng Li and Yinlong Xu.
   IEEE Transactions on Computers (TC 2021), 71.08: 1740-1754.
7. **Fast Reconstruction for Large Disk Enclosures Based on RAID2.0.** 
   Qiliang Li, Min Lyu, **Liangliang Xu**, Yinlong Xu and Wei Wang.
   The 50th International Conference on Parallel Processing (ICPP 2021).
8. **SelectiveEC: Towards Balanced Recovery Load on Erasure-coded Storage Systems.** 
   **Liangliang Xu**, Min Lyu, Qiliang Li, Lingjiang Xie, Cheng Li and Yinlong Xu.
   IEEE Transactions on Parallel and Distributed Systems (TPDS 2022), 33.10: 2386-2400. 
9. **Skadi: Building a Distributed Runtime for Data Systems in Disaggregated Data Centers.** 
   Cunchen Hu, Chenxi Wang, Sa Wang, Ninghui Sun, Yungang Bao, Jieru Zhao, Sanidhya Kashyap, Xiaoyang Deng, Pengfei Zuo, Rongfeng He, Xushen Chen, **Liangliang Xu**, Qin Zhang, Hao Feng, Yizhou Shan.   
   The 19th Workshop on Hot Topics in Operating Systems (HotOS 2023).
10. **Enabling Efficient Erasure Coding in Disaggregated Memory Systems.**
   Qiliang Li#, **Liangliang Xu**#, Yongkun Li, Min Lyu,  Wei Wang, Pengfei Zuo and Yinlong Xu.  (#equal contribution)
   IEEE Transactions on Parallel and Distributed Systems (TPDS 2024), 35.01: 154-168.
11. **Fast Recovery for Large Disk Enclosures Based on RAID2.0: Algorithms and Evaluation.** 
   Qiliang Li, Min Lyu, **Liangliang Xu** and Yinlong Xu.
   Journal of Parallel and Distributed Computing 104854 (JPDC 2024).
<!-- 12. **Towards Fast Erasure Coding at Register Efficiency.** 
   Wei Wang, Yongkun Li, Min Lyu, Tianyang Niu, **Liangliang Xu**, Qiliang Li and Yinlong Xu.
   ISCA 2024 Under Review. -->
12. **Inference without Interference: Disaggregate LLM Inference for Mixed Downstream Workloads.** 
   Cunchen Hu, Heyang Huang, **Liangliang Xu**, Xusheng Chen, Jiang Xu, Shuang Chen, Hao Feng, Chenxi Wang, Sa Wang, Yungang Bao, Ninghui Sun and Yizhou Shan.
   arXiv preprint arXiv:2401.11181.
<!-- 14. **Repair-Efficient MDS Code Constructions with Linear Sub-Packetization  Level and Small Field Size.** 
   Yuan Zeng, Min Lyu, **Liangliang Xu** and YinLong Xu.
   ISIT 2024 Under Review. -->

Skills
--------------------

- **Programming Languages:** C/C++; Java; Matlab; Linux Shell; Python.
- **Distributed systems:** HDFS; Crail; Ceph; ZooKeeper.


Selected Awards
--------------------
- Outstanding Graduate, USTC-CS, 2022
- Excellent Award of President Scholarship, CAS, 2022 (中科院院长优秀奖，CN ￥ 5,000)
- Outstanding Graduate, USTC, 2022 (CN ￥ 500)
- National Scholarship for Doctoral Student, 2021 (博士国家奖学金，CN ￥ 30,000)
- Shenzhen Stock Exchange Scholarship, 2020 (CN ￥ 12,000)
- INFOCOM  Student Conference Award, 2020 (USD $ 400)
- Graduate with Excellent Character and Learning in AHU, 2017 (CN ￥ 1,000)
- Award of Excellent B.E. thesis in AHU, 2017
- First-class Scholarship for Academic Science and Technology in AHU, 2016 (CN ￥ 5,000, team)
- Meritorious Winner of the MCM/ICM contest, 2016
- AHU Merit Student, 2016 
- National Encouragement Scholarship, 2014/2015/2016 (CN ￥ 5,000)
- Scholarship for Group Study, 2015 (CN ￥ 800)
- Second Prize of the Challenge Cup in AHU, 2014 (CN ￥ 5,000,  team)

Talks
--------------------
- 2022.03: **Invited Talk** **in The** **Graduate Academic Forum of School of Computer Science**, **University of Science and Technology of China**, Study on Key Technologies in High Reliability Systems, Online.
- 2020.07: **Paper Presentation in INFOCOM 2020**, PDL: A Data Layout towards Fast Failure Recovery for Erasure-coded Distributed Storage Systems, Online.
- 2020.07: **Paper Presentation in HotStorage 2020**, SelectiveEC: Selective Reconstruction in Erasure-coded Storage Systems, Online.
- 2020.06: **Invited Talk in the 18th ChinaSys Workshop**, PDL: A Data Layout towards Fast Failure Recovery for Erasure-coded Distributed Storage Systems, Online.

Services
--------------------
- Shadow PC at EuroSys 2023.



<!-- ## Research Interests

- Internet of Everything
- Cyber-Physical System
- Industrial Informatics
- Applied Machine Learning
- [My latest research proposal (Dec 2023)](https://caihanlin.com/file/proposal-2023.pdf)🔗

My current research focuses on practical problems that artificial intelligence faces in real life. My interests are on the **Machine Learning** and its applications in **Industrial IoT**. In a word, advanced technologies like ML and IoT positively influence the life of everybody.  I wish to devote my talent to this meaningful cause and bring well-being to society.

---

## News and Updates

- **April 2024：**Our work *BLEGuard* has been accepted to [MobiSys 2024](https://www.sigmobile.org/mobisys/2024/) as a poster paper. See you in Japan!
- **March 2024：**Very excited to get a MPhil offer from Engineering department at Cambridge University!
- **Dec 2023：**Very excited to be selected as [AAAI-24 UC Scholar](https://aaai.org/aaai-conference/undergraduate-consortium-program/). See you in Canada!
- **Dec 2023：**Got a MSc offer from the physics department of Imperial College London.
- **Aug 2023：**Happy to be awarded the FEPG Scholarship.
- **May 2023：**Happy to be awarded the XiamenAir Scholarship.
- **May 2023：**Collected the Finalist Award in MCM 2023 (Top 1%).
- **Jun 2022：**Started research programme at [Cambridge AI Group](https://www.cl.cam.ac.uk/research/ai/), advised by Prof. Pietro Liò.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Thrilled to be an AAAI-UC Scholar at <a href="https://twitter.com/hashtag/AAAI24?src=hash&amp;ref_src=twsrc%5Etfw">#AAAI24</a>, thanks to <a href="https://twitter.com/hashtag/AAAI?src=hash&amp;ref_src=twsrc%5Etfw">#AAAI</a> &amp; <a href="https://twitter.com/hashtag/GoogleExploreCSR?src=hash&amp;ref_src=twsrc%5Etfw">#GoogleExploreCSR</a> for the sponsorship. Grateful for the knowledge gained and new friendships formed.<br><br>Wonderful trip in Vancouver. Looking forward to staying connected with all.<a href="https://twitter.com/hashtag/AAAI24?src=hash&amp;ref_src=twsrc%5Etfw">#AAAI24</a> <a href="https://twitter.com/hashtag/Vancouver?src=hash&amp;ref_src=twsrc%5Etfw">#Vancouver</a> <a href="https://twitter.com/hashtag/GoogleExploreCSR?src=hash&amp;ref_src=twsrc%5Etfw">#GoogleExploreCSR</a> <a href="https://t.co/wUQUp8XlSM">pic.twitter.com/wUQUp8XlSM</a></p>&mdash; Hanlin CAI (seeking a PhD position 2025) (@lancecai2002) <a href="https://twitter.com/lancecai2002/status/1762210025173344260?ref_src=twsrc%5Etfw">February 26, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> -->

