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
        name: "Shanghai Jiao Tong University"
        email: "gls1196@sjtu.edu.cn"

education:
    - course:
        degree: "B.S. in Computer Science (Member of ACM class)."
        institution:  "Shanghai Jiao Tong University"
        start_date: "Sep 2018"
        loc: Shanghai, China
        # other_info: "Member of ACM Class, an elite CS program for the top 5% talented students."
        other_info2: "GPA: 88/100"

experience:
    - course:
        degree: Supervised by [**Prof. Dong Xie**](https://sites.psu.edu/dongx)
        institution: 'Database System Group, Pennsylvania State University'
        start_date: 'Jun 2021'
        flag: 0
        projects:
            - project:
                name: Adaptive Serverless Functions Placement for Disaggregated Storage Datacenters
                infos:
                    - info: Functions running on the compute server need several data transmissions including *get()/put()* with the storage server, which hurts **e2e latency** of functions.
                    - info: These *get()/put()* requests waste storage server's CPU dispatching requests from NIC to userspace and unpacking requests, which hurts the **throughput**.
                
    - course:
        degree: Supervised by [**Prof. Quan Chen**](https://www.cs.sjtu.edu.cn/~chen-quan/index_EN.html)
        institution: 'Emerging Parallel Computing Center (EPCC Lab), SJTU'
        start_date: 'Jul 2020'
        end_date: 'Jun 2021'
        projects:
            - project:
                name: Eliminating Cold Startup in Serverless Computing by Sharing Containers between Functions
                infos:
                    - info: Proposed **an effective inter-function container sharing policy based on startup frequency**, which helped our system to alleviate 87.9% of cold startup.
                    - info: Implemented most of the system, designed and ran experiments, especially **a large-scale evaluation in cloud environment**.
            - project:
                name: Optimizing Data Communication across Functions within Serverless Applications
                infos:
                   - info: Co-proposed **an efficient workflow scheduling mechanism**, which mitigates data transmission overhead by 50.1%.
                   - info: Designed **an adaptive storage library** which automatically chooses the appropriate storage between local memory and remote database for user functions.
                   - info: Designed a parser which could parse hierarchy application workflows into DAGs for better scheduling workflows.
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
        info: Designed some assignments, gave a lecture about the introduction to C++ programming, guided a group of students in programming and algorithms, and contributed one programming problem to the final exam.
    - course:
        degree: Guided by [**Prof. Yong Yu**](http://apex.sjtu.edu.cn/members/yyu)
        institution: 'Member in ACM-ICPC Team, SJTU'
        start_date: 'Jun 2018'
        end_date: 'Jul 2019'
        info: I was a member of a team named **Quasar**. In this team, I practiced programming and algorithms with two other team members at least twice each week. And we won **three gold medals (one 1st runner-up)** in ACM-ICPC Asia regional contests and one gold medal in China Collegiate Programming Contest. Therefore, my programming and algorithmic abilities have been improved in the ACM-ICPC team.

project:
    - course:
        name: Java-and-C-like Language Compiler (∼16K lines in Java)
        github: https://github.com/LinsongGuo/Mxstar-compiler
        info: Given a piece of code, the compiler could convert it into an AST, then LLVM IR, and finally RISC-V assembly. Due to my interest in exploring the compiler back-end, I added some optimizations to it, including mem2reg, inlining, CSE(Common SubExpression Elimination), LICM(Loop Invariant Code Motion), SCCP(Sparse Conditional Constant Propagation), and so on.
    - course:
        name: Replicated KV Store Based on Raft Consensus Protocol (∼1.5K lines in C++)
        github: https://github.com/LinsongGuo/Raft
        info: The store could run on a cluster of servers communicated via gRPC and support basic operations, including get and put.
    - course:
        name: RISC-V CPU with 5-Stage Pipeline (∼3.7K lines in Verilog)
        github: https://github.com/LinsongGuo/risc-v-cpu
        info: To explore more about computer architecture, I add some components like d-cache, i-cache, and branchpredictor combining BTB and BHT. The CPU could run successfully on an FPGA board.
    - course:
        name: Playing Atari Games
        github: https://github.com/LinsongGuo/Atari-Games
        info: To explore reinforcement learning, I trained several DQN models, including DoubleDQN, DuelingDQN, RainbowDQN, and so on, to play some Atari games.

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

