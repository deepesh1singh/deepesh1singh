<div align="center">

<img src="banners/header_banner.png" alt="" width="100%"/>

<br/>

# Deepesh Singh

### Indian Institute of Technology Kharagpur
**Department of Computer Science and Engineering**

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-deepesh1singh-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/deepesh1singh)

<br/>

I build across the stack — from cache-level performance work and OS internals, through applied ML for cryptanalysis, to full-stack products and custom network protocols. Below is a categorized tour of my work, grouped by area rather than chronology, so you can jump straight to what's relevant to you.

</div>

<br/>

## 📌 Table of Contents

- [🖥️ Systems & Computer Architecture](#systems-computer-architecture) — 5 projects
- [🧠 Machine Learning & Cryptanalysis](#machine-learning-cryptanalysis) — 8 projects
- [🔀 Concurrency & Process Simulation](#concurrency-process-simulation) — 8 projects
- [🌐 Networking & Transport Protocols](#networking-transport-protocols) — 6 projects
- [🚀 Full-Stack Web Platforms](#full-stack-web-platforms) — 6 projects
- [⚡ Data, Retrieval & Performance Engineering](#data-retrieval-performance-engineering) — 6 projects

<br/>

## 🖥️ Systems & Computer Architecture

<img src="banners/banner_systems.png" alt="Systems & Computer Architecture banner" width="100%"/>

Cache behavior, memory hierarchies, and hardware-level performance analysis.

<br/>

<table>
<tr>
<td width="100%">

### [Cache-Aware Performance Optimization using gem5 and RISC-V](https://github.com/deepesh1singh/Cache-Aware-Performance-Optimization-using-gem5-and-RISC-V)

![gem5](https://img.shields.io/badge/gem5-333333?style=flat-square) ![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Computer architecture project using gem5 simulation to study how L1/L2 cache size and associativity affect performance. Runs parameter sweeps, analyzes hit rates, execution time, and Pareto-optimal configurations, and compares simple vs. cache-aware chunked merge sort to show how memory-access patterns drive cache performance.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [High-Performance Cache Optimization and Memory Analysis](https://github.com/deepesh1singh/High-Performance-Cache-Optimization-and-Memory-Analysis)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Linux perf](https://img.shields.io/badge/Linux%20perf-FCC624?style=flat-square&logo=linux&logoColor=black) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![CACTI](https://img.shields.io/badge/CACTI-333333?style=flat-square)

Evaluates cache optimization techniques and memory hierarchy behavior using C, Linux perf, Python, and CACTI. Analyzes loop interchange and cache blocking performance, and studies cache access time and read energy across cache sizes and associativities.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Virtual Memory Simulation with Approximate LRU](https://github.com/deepesh1singh/Demand-Paging-Page-Replacement-Simulator)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Operating Systems](https://img.shields.io/badge/Operating%20Systems-424242?style=flat-square)

C-based virtual memory simulator modeling demand paging and page replacement across 128 concurrent processes. Implements page tables, shared physical frames, page-fault handling, and a 16-bit history-based Approximate LRU policy with a 4-tier frame selection strategy under memory pressure.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Virtual Memory Simulation with LRU-Style Replacement](https://github.com/deepesh1singh/Virtual-Memory-Simulation-with-LRU-Style-Replacement)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Operating Systems](https://img.shields.io/badge/Operating%20Systems-424242?style=flat-square)

Virtual memory simulator modeling demand paging for multiple processes performing binary searches over large logical arrays, with page-fault handling, fixed-frame allocation, LRU-style replacement, and frame-acquisition classification under constrained memory.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Demand Paging Simulator (Binary Search + Swapping)](https://github.com/deepesh1singh/Demand-Paging-Simulator-Binary-Search-Swapping-)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Operating Systems](https://img.shields.io/badge/Operating%20Systems-424242?style=flat-square)

Demand paging simulator modeling memory management for multiple concurrent processes performing binary searches on paged data, with page-fault handling, frame allocation, process-level swapping, and restoration of essential resident pages under constrained physical memory.

</td>
</tr>
</table>


<br/>

## 🧠 Machine Learning & Cryptanalysis

<img src="banners/banner_ml_security.png" alt="Machine Learning & Cryptanalysis banner" width="100%"/>

Applying ML and neural architectures to classical and modern cipher analysis.

<br/>

<table>
<tr>
<td width="100%">

### [Machine Learning in Cryptanalysis](https://github.com/deepesh1singh/ML-Cryptanalysis)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![Random Forest](https://img.shields.io/badge/Random%20Forest-2E8B57?style=flat-square) ![SVM](https://img.shields.io/badge/SVM-2E8B57?style=flat-square) ![Neural Networks](https://img.shields.io/badge/Neural%20Nets-FF6F00?style=flat-square)

Applies ML and statistical pattern recognition to analyze classical ciphers (Caesar, Vigenère, substitution). Generates encrypted datasets, extracts character-frequency and n-gram features, and trains Random Forest, SVM, and neural network models to identify cipher patterns.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Differential Distinguishers for ASCON Permutation](https://github.com/deepesh1singh/Differential-distinguishers-for-ASCON-permutation)

![LightGBM](https://img.shields.io/badge/LightGBM-9ACD32?style=flat-square) ![CNN](https://img.shields.io/badge/CNN-FF6F00?style=flat-square) ![LSTM](https://img.shields.io/badge/LSTM-FF6F00?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

ML-based cryptanalysis of the ASCON lightweight permutation. Trains and compares LightGBM, CNN, and LSTM models to distinguish differential ciphertext pairs from random pairs across 1–5 rounds, reaching >99% test accuracy for 1–3 rounds and analyzing distinguishability degradation in later rounds.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Hybrid CNN-LSTM Differential Distinguisher for Ciphers](https://github.com/deepesh1singh/Hybrid-CNN-LSTM-differential-distinguisher-for-ASCON-ACE-SIMECK-LLBC-and-future-ciphers)

![CNN](https://img.shields.io/badge/CNN-FF6F00?style=flat-square) ![LSTM](https://img.shields.io/badge/LSTM-FF6F00?style=flat-square) ![AlexNet](https://img.shields.io/badge/AlexNet-FF6F00?style=flat-square) ![VGG](https://img.shields.io/badge/VGG-FF6F00?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Evaluated eight neural architectures (AlexNet, LeNet-5, LSTM, MLP, VGG-11/13, LbEC, TbEC) for differential cryptanalysis of ASCON. Designed a hybrid CNN–LSTM distinguisher reaching 6 rounds for ASCON/ACE/FUTURE and 19 rounds for Simeck — extending prior neural attack depth from 4→6 and 12→19 rounds respectively, with stronger resistance observed for LLBC-256 vs. LLBC-128.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Customer Churn Prediction using XGBoost](https://github.com/deepesh1singh/Bias-Variance-Model-)

![XGBoost](https://img.shields.io/badge/XGBoost-0668E1?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)

ML classification project predicting telecom customer churn. Covers preprocessing, categorical encoding, and hyperparameter tuning with RandomizedSearchCV, evaluated on AUC, accuracy, precision, recall, and F1 — achieving 0.85 validation AUC.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Speech Emotion Recognition (Cross-Cultural Audio)](https://github.com/deepesh1singh/Speech-Emotion-Recognition-using-CNN-on-Cross-Cultural-Audio-Data)

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![CNN](https://img.shields.io/badge/CNN-FF6F00?style=flat-square) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

TensorFlow CNN classifying speech into 9 emotion categories using European and Indian audio datasets. Uses Mel-spectrogram features, actor-aware/emotion-based splitting, augmentation, mixed-precision training, and test-time augmentation — achieving 86.52% test accuracy and 0.89 macro F1 on 653 samples.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Approximate Nearest Neighbor Search (LSH & HNSW)](https://github.com/deepesh1singh/Approximate-Nearest-Neighbor-Search-Implementation-with-LSH-and-HNSW)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Implements and evaluates ANN search using Locality-Sensitive Hashing and HNSW graphs. Compares Recall@5/10/15 and query latency across configurations, with benchmark visualizations of the accuracy–latency trade-off.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [ML Model Comparison using PyTorch and Apache Spark](https://github.com/deepesh1singh/Machine-Learning-Model-Comparison-using-PyTorch-and-Spark)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

Compares ML models across PyTorch and Apache Spark, evaluating behavior across configurations and activation functions using MSE, with reproducible notebook implementations for both frameworks.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Large-Scale Multi-Label Text Classification with PyTorch](https://github.com/deepesh1singh/Large-Scale-Multi-Label-Text-Classification-with-PyTorch)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

Multi-label text classifier on Amazon-670K (135,909-dim TF-IDF features, 670,091 labels). Uses a sparse low-rank classifier (rank-128 projection) with memory-efficient label chunking, comparing SGD, SGD+Momentum/Nesterov, and Adadelta across learning rates via precision/recall/F1.

</td>
</tr>
</table>


<br/>

## 🔀 Concurrency & Process Simulation

<img src="banners/banner_concurrency.png" alt="Concurrency & Process Simulation banner" width="100%"/>

Threads, shared memory, and inter-process coordination in C and C++.

<br/>

<table>
<tr>
<td width="100%">

### [Resource Allocation and Deadlock Avoidance](https://github.com/deepesh1singh/Resource-Allocation-and-Deadlock-Avoidance)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![POSIX Threads](https://img.shields.io/badge/pthreads-6E4C13?style=flat-square)

Simulates concurrent resource allocation among threads, comparing normal allocation with deadlock avoidance via the Banker's Algorithm. Uses mutexes, condition variables, and barriers to coordinate requests and ensure safe allocation.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Boating Simulation with Threads and Synchronization](https://github.com/deepesh1singh/Boating-Simulation-with-Threads-and-Synchronization)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![POSIX Threads](https://img.shields.io/badge/pthreads-6E4C13?style=flat-square)

Boating-center simulation modeling concurrent boat and visitor activity with synchronized visitor-to-boat assignment, randomized ride durations, and controlled concurrent execution across multiple boats and visitors using pthreads.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Restaurant Simulation (Processes, Shared Memory, Semaphores)](https://github.com/deepesh1singh/Restaurant-Simulation-Processes-Shared-Memory-Semaphores-)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![System V IPC](https://img.shields.io/badge/SysV%20IPC-6E4C13?style=flat-square) ![Semaphores](https://img.shields.io/badge/Semaphores-6E4C13?style=flat-square)

Restaurant simulation using multiple processes and System V IPC to model customers, waiters, and cooks. Shared memory holds global state; semaphores coordinate table capacity, order processing, food prep, arrivals, and closing-time behavior.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Leader and Followers Using Shared Memory](https://github.com/deepesh1singh/Leader-and-Followers-Using-Shared-Memory)

![C++17](https://img.shields.io/badge/C%2B%2B17-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![System V Shared Memory](https://img.shields.io/badge/SysV%20SHM-6E4C13?style=flat-square)

Leader-follower coordination system across multiple processes using System V shared memory for IPC. Implements turn-by-turn synchronization, shared-state coordination, iterative sum computation, and termination on duplicate-sum detection.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Signal-Based Child Process Game](https://github.com/deepesh1singh/Signal-Based-Child-Process-Game)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Unix Signals](https://img.shields.io/badge/Unix%20Signals-6E4C13?style=flat-square)

Linux process-management simulation modeling an elimination game across multiple child processes. Uses fork(), exec(), and SIGUSR1/SIGUSR2 for IPC, with the parent coordinating execution, ball-passing, and elimination logic.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Dependency-Based Rebuild Simulator](https://github.com/deepesh1singh/Dependency-Based-Rebuild-Simulator)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Build Systems](https://img.shields.io/badge/Build%20Systems-6E4C13?style=flat-square)

Build-system simulator modeling dependency-driven module rebuilding via process creation and synchronization. Generates dependency graphs and recursively rebuilds modules using fork(), exec(), and waitpid(), with file-based state tracking.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Distributed Sudoku with Processes and Pipes](https://github.com/deepesh1singh/Distributed-Sudoku-with-Processes-and-Pipes)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![POSIX Pipes](https://img.shields.io/badge/POSIX%20Pipes-6E4C13?style=flat-square)

Interactive Sudoku system distributing the 9 board blocks across independent processes. Uses POSIX pipes for IPC, with a coordinator process routing commands and synchronizing updates across block processes in separate terminals.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [CPU Scheduling Simulation (FCFS and Round Robin)](https://github.com/deepesh1singh/CPU-Scheduling-Simulation-FCFS-and-Round-Robin-)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Operating Systems](https://img.shields.io/badge/Operating%20Systems-424242?style=flat-square)

Event-driven simulator modeling process scheduling with CPU and I/O bursts. Implements FCFS and Round Robin with configurable time quanta, evaluating scheduling decisions and reporting per-process and aggregate performance metrics.

</td>
</tr>
</table>


<br/>

## 🌐 Networking & Transport Protocols

<img src="banners/banner_networking.png" alt="Networking & Transport Protocols banner" width="100%"/>

Custom protocol design and implementation over TCP, UDP, and raw sockets.

<br/>

<table>
<tr>
<td width="100%">

### [KTP KSocket — Custom Transport Protocol over UDP](https://github.com/deepesh1singh/Custom-Network-Transport-Protocol-with-Sliding-Window-over-UDP)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![UDP](https://img.shields.io/badge/UDP-2E8B57?style=flat-square) ![POSIX Threads](https://img.shields.io/badge/pthreads-6E4C13?style=flat-square) ![System V Shared Memory](https://img.shields.io/badge/SysV%20SHM-6E4C13?style=flat-square)

Reliable transport protocol over UDP with a socket-like API: sliding-window flow control, ACK-based reliability, timeout retransmission, and out-of-order packet handling. Uses shared memory and multiple processes/threads to coordinate sender/receiver operation and reliable transfer under simulated packet loss.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [CLDP Raw Discovery](https://github.com/deepesh1singh/CLDP-Raw-Discovery)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![Raw Sockets](https://img.shields.io/badge/Raw%20Sockets-2E8B57?style=flat-square) ![IPv4](https://img.shields.io/badge/IPv4-2E8B57?style=flat-square)

Custom network discovery protocol implemented directly over IPv4 raw sockets using experimental protocol number 253. Defines HELLO/QUERY/RESPONSE messages, handles packet construction/parsing at the IP layer, and exchanges node metadata over local-network broadcast.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [TCP File Encryption Client-Server](https://github.com/deepesh1singh/TCP-File-Encryption-Client-Server)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![TCP](https://img.shields.io/badge/TCP-2E8B57?style=flat-square) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

Client-server application transferring text files over TCP with server-side monoalphabetic substitution encryption. Implements chunked transfer, key validation, and application-level termination, with Wireshark used to inspect network traffic.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [TaskQueue Server-Worker](https://github.com/deepesh1singh/TaskQueue-Server-Worker)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![TCP Sockets](https://img.shields.io/badge/TCP%20Sockets-2E8B57?style=flat-square)

TCP task-queue system distributing arithmetic tasks from a central server to multiple worker clients, supporting concurrent connections, task assignment/result submission, queue management, and recovery when a worker disconnects mid-task.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [MiniSMTP](https://github.com/deepesh1singh/MiniSMTP)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![TCP Sockets](https://img.shields.io/badge/TCP%20Sockets-2E8B57?style=flat-square) ![POSIX Threads](https://img.shields.io/badge/pthreads-6E4C13?style=flat-square)

SMTP-like mail client-server system over TCP implementing HELO, MAIL FROM, RCPT TO, and DATA commands, with per-user mailbox storage/retrieval and multi-client handling via POSIX threads.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [UDP Word-by-Word File Transfer](https://github.com/deepesh1singh/UDP-Word-by-Word-File-Transfer-Client-Server-)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![UDP Sockets](https://img.shields.io/badge/UDP%20Sockets-2E8B57?style=flat-square)

Client-server file transfer over UDP transmitting text line-by-line through a custom application-layer protocol, with filename requests, sequential WORD-based data requests, file-not-found handling, and HELLO/FINISH control messages.

</td>
</tr>
</table>


<br/>

## 🚀 Full-Stack Web Platforms

<img src="banners/banner_webstack.png" alt="Full-Stack Web Platforms banner" width="100%"/>

End-to-end product engineering across the frontend, backend, and database layers.

<br/>

<table>
<tr>
<td width="100%">

### [Review AI — Resume Analyzer & Interview Prep System](https://github.com/deepesh1singh/AI-Powered-Resume-Analyzer-Interview-Prep-Platform)

![Full-Stack](https://img.shields.io/badge/Full--Stack-1abc9c?style=flat-square) ![AI/ML](https://img.shields.io/badge/AI%2FML-1abc9c?style=flat-square)

AI-powered app that scores a resume against a job description and generates skill-gap analysis, technical/behavioral interview questions, and a personalized prep plan. Supports resume PDF generation and interview-report history.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [JobConnect Platform](https://github.com/deepesh1singh/Job-Plateform)

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

Full-stack job recruitment platform connecting candidates and employers — job discovery, applications, profile/application tracking, and recommendations for candidates; posting, applicant management, candidate search, and hiring pipeline for recruiters.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [AI Job Assistant](https://github.com/deepesh1singh/AI-Job-Assistant)

![Sentence Transformers (MPNet)](https://img.shields.io/badge/Sentence%20Transformers-FFB000?style=flat-square) ![Browser Extension](https://img.shields.io/badge/Browser%20Extension-4285F4?style=flat-square&logo=googlechrome&logoColor=white)

AI job-analysis platform using Sentence Transformers (MPNet) to semantically match job descriptions with resumes. Identifies matched/missing skills, generates insights and cover letters, tracks applications, and provides real-time analysis via a cross-browser extension for LinkedIn, Indeed, Naukri, and Glassdoor.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Multimedia Database System](https://github.com/deepesh1singh/multimedia-database-system)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white) ![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)

Full-stack system managing books, videos, music, images, and articles with JWT auth, bcrypt hashing, secure uploads, advanced search, playlists, comments/ratings, real-time notifications (Socket.IO), and an admin analytics dashboard. Hardened with rate limiting, Helmet, CORS, Sharp-based image optimization, and DB indexing.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Event Management System](https://github.com/deepesh1singh/Event-Management-System)

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express.js](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![EJS](https://img.shields.io/badge/EJS-B4CA65?style=flat-square) ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white)

Role-based event platform (Managers, Vendors, Accountants, Customers) covering event creation, ticket booking, payments, JWT auth, PDF ticket generation via Puppeteer, email notifications (Nodemailer), and revenue/expenditure reporting across a modular MVC structure.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Gram Panchayat Management System](https://github.com/deepesh1singh/GRAM-PANCHAYAT-MANAGEMNT-SYSTEM)

![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)

PHP-based system for digitizing citizen services and admin workflows, with role-based dashboards for administrators, employees, monitors, and citizens — covering secure login, complaint management, citizen data entry, and administrative monitoring.

</td>
</tr>
</table>


<br/>

## ⚡ Data, Retrieval & Performance Engineering

<img src="banners/banner_data_perf.png" alt="Data, Retrieval & Performance Engineering banner" width="100%"/>

Benchmarking and optimizing systems for throughput, latency, and scale.

<br/>

<table>
<tr>
<td width="100%">

### [Limit Order Book Simulator](https://github.com/deepesh1singh/Limit-Order-Book-Matching-Engine)

![C++20](https://img.shields.io/badge/C%2B%2B20-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Multithreading](https://img.shields.io/badge/Multithreading-00599C?style=flat-square)

Production-style matching engine simulating exchange mechanics with strict price-time priority. Supports multiple order types, full order-lifecycle management, self-trade prevention, multithreaded processing, historical replay, live stats, benchmarking, fuzz testing, and sanitizer-based validation.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Efficient Re-ranking with Cross-Encoders via Early Exit](https://github.com/deepesh1singh/cross-encoder-early-exit-reranking)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Information Retrieval](https://img.shields.io/badge/Information%20Retrieval-6A5ACD?style=flat-square)

Improves cross-encoder document re-ranking efficiency using early-exit techniques, evaluating how early inference stopping and ranked-list truncation reduce compute cost while preserving retrieval effectiveness across in- and out-of-domain datasets.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [High-Performance Financial Data Processing](https://github.com/deepesh1singh/High-Performance-Financial-Data-Processing)

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat-square&logo=polars&logoColor=white)

Benchmarks Pure Python, NumPy, Polars, and C++ for processing millions of financial records — as-of joins and trading analytics up to 5M trades, using isolated subprocess timing, memory profiling, and cross-implementation correctness checks. C++ achieved 15.5× lower execution time and 3.7× lower memory than pure Python at 2M trades.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [BankBrain Smoke Tests](https://github.com/deepesh1singh/BankBrain-Cloud-Ready-Microservices-Banking-Backend)

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Multi-Agent Systems](https://img.shields.io/badge/Multi--Agent-6A5ACD?style=flat-square)

End-to-end test suite for a cloud-ready, multi-agent banking backend, validating integration across the Mock Bank API, MCP Server, Support Agent, and A2A Gateway using FastAPI TestClient with fully mocked in-memory calls — no ports or network access required.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Construction of Benchmark Datasets for Neuro-Symbolic Legal Reasoning](https://github.com/deepesh1singh/Multi-Agent-Framework-with-Formalized-Knowledge-Representations-)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![NLP](https://img.shields.io/badge/NLP-6A5ACD?style=flat-square) ![Legal Tech](https://img.shields.io/badge/Legal%20Tech-6A5ACD?style=flat-square)

Converts statutory text into machine-interpretable benchmark datasets — variables, grounded predicates, logical rules, supporting legal spans, and validation reports. Builds automated generation pipelines for the SARA and COLIEE legal datasets with structured JSON/Excel outputs.

</td>
</tr>
</table>

<table>
<tr>
<td width="100%">

### [Recursive File Finder](https://github.com/deepesh1singh/Recursive-file-finder-by-extension-find-all-)

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white) ![POSIX](https://img.shields.io/badge/POSIX-6E4C13?style=flat-square)

POSIX C utility for recursive directory traversal and case-insensitive file-extension matching, reporting file ownership, size, and full paths for all discovered files.

</td>
</tr>
</table>


<br/>

---

<div align="center">

### 📊 GitHub Stats

<img src="https://github-readme-stats.vercel.app/api?username=deepesh1singh&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" height="165"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=deepesh1singh&theme=tokyonight&hide_border=true" alt="GitHub Streak" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=deepesh1singh&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" height="165"/>

<br/>
<br/>

*Thanks for stopping by — feel free to explore the repositories above or reach out via GitHub.*

</div>
