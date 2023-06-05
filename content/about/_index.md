---
title: "about"
date: 2020-10-20T17:51:47+03:30
draft: false
headless: true

full_name: "Linsong Guo"
profile_picture: "profile.png"
cv: "cv.pdf"
# set to false if you don't want to show your blog
blog: false

affiliations:
    - affiliation:
        # name: "Shanghai Jiao Tong University"
        email: "l1guo at ucsd dot edu"

education:
    - course:
        degree: "Ph.D. in Computer Science and Engineering."
        institution:  "University of California San Diego (UCSD)"
        start_date: "Sep 2022"
        loc: La Jolla, CA

    - course:
        degree: "B.Eng. in Computer Science (Member of ACM class)."
        institution:  "Shanghai Jiao Tong University (SJTU)"
        start_date: "Sep 2018"
        end_date: "Jun 2022"
        loc: Shanghai, China
        other_info2: "GPA: 88/100"

experience:
    # - course:
    #     degree: Supervised by [**Prof. Yiying Zhang**](https://cseweb.ucsd.edu/~yiying/)
    #     institution: 'WukLab, UCSD'
    #     start_date: 'Sep 2022'
    #     end_date: 'Dec 2022'
    #     flag: 0
    #     projects:
    #         - project:
    #             name: Worked on Memory Disaggregation.

    - course:
        degree: Graduate Student Researcher (GSR)
        institution: 'UCSD'
        start_date: 'Sep 2022'
        end_date: 'Dec 2022'
        flag: 0
        # projects:
        #     - project:
        #         name: Worked on Memory Disaggregation.
    
    - course:
        degree: Advised by [**Prof. Dong Xie**](https://sites.psu.edu/dongx)
        institution: 'Database System Group, Pennsylvania State University'
        start_date: 'Jul 2021'
        end_date: 'Dec 2021'
        flag: 0
        projects:
            - project:
                name: Exploring Functions Placement on Disaggregated Storage Datacenters
                # infos:
                #     - info: Functions running in the compute server need several data transmissions including *get()/put()* with the storage server, which hurts **end-to-end latency** of functions.
                #     - info: The storage server wastes some CPU on processing these *get()/put()* network requests, which hurts the **throughput** of both the compute and storage server.
                
    - course:
        degree: Advised by [**Prof. Quan Chen**](https://www.cs.sjtu.edu.cn/~chen-quan/index_EN.html)
        institution: 'Emerging Parallel Computing Center (EPCC Lab), SJTU'
        start_date: 'Jul 2020'
        end_date: 'Jun 2021'
        projects:
            - project:
                name: Eliminating Cold Startup in Serverless Computing by Sharing Containers between Functions
                # infos:
                #     - info: Proposed **an effective inter-function container sharing policy based on startup frequency**, which helped our system to alleviate 87.9% of cold startup.
                #     - info: Implemented most of the system, designed and ran experiments, especially **a large-scale evaluation in cloud environment**.
            - project:
                name: Reducing data movement overhead in real-world stateless workflows
                # infos:
                #    - info: Proposed **a QoS-aware workflow partitioning policy** that divides a workflow into several groups.
                #    - info: Developed **group-level granularity scheduling**, reducing the data transmission overhead in real-world stateless workflows by 50.1%.
            # - project:
            #     name: Alleviating Cold Startup in Serverless Computing By Safe Inter-Function Container Sharing
            #     infos:
            #         - info: Proposed **an effective inter-function container sharing policy based on startup frequency**, which helped our system to alleviate 87.9% of cold startup.
            #         - info: Implemented most of the system, designed and ran experiments, especially **a large-scale evaluation in cloud environment**.
            # - project:
            #     name: Enable Efficient Workflow Execution for Function-as-a-Service
            #     infos:
            #        - info: Co-proposed **an efficient workflow scheduling mechanism**, which mitigates the workflow scheduling and data transmission overhead by 42.7% and 50.1%.
            #        - info: Designed **an adaptive storage library** which automatically chooses the appropriate storage between local memory and remote database for user workflows.
            #        - info: Designed a workflow parser which could parse hierarchy workflows into DAGs for better scheduling workflows.
            # - project:
            #     name: A Serverless Computing Survey
            #     infos:
            #        - info: Contributed one subsection to the survey.

other_experience:
    - course:
        degree: Instructed by [**Prof. Huiyu Weng**](https://www.cs.sjtu.edu.cn/en/PeopleDetail.aspx?id=148)
        institution: 'Teaching Assistant of C++ Programming Course, SJTU'
        start_date: 'Sep 2019'
        end_date: 'Jan 2020'
        # info: Designed some assignments, gave a lecture about the introduction to C++ programming, guided a group of students in programming and algorithms, and contributed one programming problem to the final exam.
    - course:
        degree: Guided by [**Prof. Yong Yu**](http://apex.sjtu.edu.cn/members/yyu)
        institution: 'Member in ACM-ICPC Team, SJTU'
        start_date: 'Jun 2018'
        end_date: 'Jul 2019'
        info: A member of a team named Quasar. Earned three gold medals (one 1st runner-up) in ACM-ICPC Asia regional contests and one gold medal in China Collegiate Programming Contest.

project:
    - course:
        name: Java-and-C-like Language Compiler (∼16K lines in Java)
        github: https://github.com/LinsongGuo/Mxstar-compiler
        info: The compiler can convert a piece of code to an AST, then to LLVM IR, and eventually to RISC-V assembly. I enhanced the compiler’s back-end with numerous optimizations, including mem2reg, inlining, CSE(Common SubExpression Elimination), LICM(Loop Invariant Code Motion), SCCP(Sparse Condtional Constant Propagation), and so on.
    - course:
        name: Replicated KV Store Based on Raft Consensus Protocol (∼1.5K lines in C++)
        github: https://github.com/LinsongGuo/Raft
        info: The replicated store could run on a cluster of servers communicated via gRPC and support basic operations such as get and put.
    - course:
        name: RISC-V CPU with 5-Stage Pipeline (∼3.7K lines in Verilog)
        github: https://github.com/LinsongGuo/risc-v-cpu
        info: To gain a better understanding of computer architecture, I added components including d-cache, i-cache, and a branch predictor combining BTB and BHT. The CPU could run successfully on an FPGA board.

honor:
    - course:
        name: 1st Runner-Up
        info: ACM-ICPC Asia Regional Contest, Nakhon Pathom Site
        year: 2018

pub:
    - one:
        title: Single photon fluctuation Microscopy
        where: Manuscript in preparation
        date: 2021
        me: 0
        authors:
        - Si-yuan Yin
        - Zhan-ming Li
        - Shi-Bao Wu
        - Heng Zhou    
        - Xian-Min Jin

    - one:
        title: Photon Arrival Time Analysis Enhanced Confocal Microscopy
        where: Manuscript in preparation
        date: 2021 
        me: 0
        authors:
        - Si-yuan Yin
        - Zhan-ming Li
        - Hao-ran Lu
        - Shi-Bao Wu
        - Heng Zhou
        - Xian-Min Jin

    - one:
        title: Quantum induced bio-randomness
        where: Manuscript in preparation
        date: 2021
        me: 1
        authors:
        - Zhi-qiang Jiao
        - Si-yuan Yin
        - Jun Gao
        - Zhe-yong Zhang 
        - Wen-hao Zhou
        - Chao-ni Zhang 
        - Lu-feng Qiao
        - Xiao-ling Pang
        - Jian-Peng Dou
        - Xian-Min Jin

    - one:
        title: Fast correlated-photon imaging enhanced by deep learning
        where: Optica 8, 323-328
        date: 2021
        me: 6
        authors:
        - Zhan-Ming Li
        - Shi-Bao Wu
        - Jun Gao
        - Heng Zhou
        - Zeng-Quan Yan
        - Ruo-Jing Ren
        - Si-yuan Yin
        - Xian-Min Jin

    - one:
        title: Thresholded single-photon underwater imaging and detection
        where: Optics Express 29, 28124-28133
        date: 2021
        me: 7
        authors:
        - Zhan-Ming Li
        - Heng Zhou
        - Zhong-Yuan Li
        - Zeng-Quan Yan
        - Cheng-Qiu Hu
        - Jun Gao
        - Shi-Bao Wu
        - Si-yuan Yin
        - Xian-Min Jin  

    - one:
        title: Immuno-SABER enables highly multiplexed and amplified protein imaging in tissues
        where: Nature Biotechnology 37, 1080–1090
        date: 2019
        me: 11
        authors:
        - Sinem K. Saka
        - Yu Wang
        - Jocelyn Y. Kishi
        - Allen Zhu
        - Yitian Zeng
        - Wenxin Xie
        - Koray Kirli
        - Clarence Yapp
        - Marcelo Cicconet
        - Brian J. Beliveau
        - Sylvain W. Lapan
        - Siyuan Yin
        - Millicent Lin
        - Edward S.Boyden
        - Pascal S. Kaeser
        - German Pihan
        - George M. Church
        - Peng Yin
---

