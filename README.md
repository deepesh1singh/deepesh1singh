<!DOCTYPE html>
<html>
<head>
<style>
body {
  font-family: Georgia, serif;
  line-height: 1.6;
  max-width: 1000px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f9f9f9;
  color: #1a1a1a;
}
h1, h2, h3 {
  font-family: Georgia, serif;
  color: #0a0a0a;
}
a {
  color: #0066cc;
  text-decoration: none;
}
a:hover {
  text-decoration: underline;
}
.header {
  text-align: center;
  padding: 40px 0 20px 0;
  border-bottom: 2px solid #e0e0e0;
  margin-bottom: 30px;
}
.name {
  font-size: 3.5em;
  font-weight: bold;
  margin: 0;
  letter-spacing: 1px;
  color: #0a0a0a;
}
.subtitle {
  font-size: 1.2em;
  color: #444;
  margin-top: 5px;
}
.project-card {
  background: white;
  border-radius: 10px;
  padding: 20px 25px;
  margin: 20px 0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  border-left: 4px solid #0066cc;
}
.project-card h3 {
  margin-top: 0;
  margin-bottom: 10px;
  font-size: 1.3em;
}
.project-card p {
  margin: 8px 0;
  color: #333;
}
.project-card .tech-tag {
  display: inline-block;
  background: #eef2f7;
  padding: 2px 12px;
  border-radius: 20px;
  font-size: 0.8em;
  margin: 4px 4px 0 0;
  color: #1a1a1a;
}
.section-title {
  font-size: 2em;
  border-bottom: 2px solid #e0e0e0;
  padding-bottom: 10px;
  margin-top: 40px;
  margin-bottom: 20px;
}
.badge {
  background: #0066cc;
  color: white;
  padding: 2px 14px;
  border-radius: 20px;
  font-size: 0.7em;
  margin-left: 8px;
  vertical-align: middle;
  display: inline-block;
}
.banner {
  background: linear-gradient(135deg, #1a1a2e, #16213e);
  color: white;
  padding: 30px 40px;
  border-radius: 12px;
  text-align: center;
  margin: 20px 0 30px 0;
}
.banner h2 {
  color: white;
  margin: 0;
  font-size: 1.8em;
}
.banner p {
  color: #ccc;
  margin: 8px 0 0 0;
  font-size: 1.1em;
}
.stats-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
  gap: 15px;
  margin: 20px 0 30px 0;
}
.stat-box {
  background: white;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  box-shadow: 0 2px 6px rgba(0,0,0,0.06);
}
.stat-box .number {
  font-size: 2em;
  font-weight: bold;
  color: #0066cc;
}
.stat-box .label {
  font-size: 0.85em;
  color: #666;
  margin-top: 5px;
}
</style>
</head>
<body>

<div class="header">
  <div class="name">Deepesh Singh</div>
  <div class="subtitle">Indian Institute of Technology Kharagpur<br>Department of Computer Science and Engineering</div>
</div>

<div class="banner">
  <h2>🚀 Systems & AI Researcher</h2>
  <p>Building high-performance systems, exploring AI for cryptanalysis, and developing full-stack applications</p>
</div>

<div class="stats-grid">
  <div class="stat-box"><div class="number">39</div><div class="label">Projects</div></div>
  <div class="stat-box"><div class="number">C/C++</div><div class="label">Primary Systems</div></div>
  <div class="stat-box"><div class="number">Python</div><div class="label">ML & AI</div></div>
  <div class="stat-box"><div class="number">Full-Stack</div><div class="label">Web Apps</div></div>
</div>

<h2 class="section-title">📌 Featured Projects</h2>

<div class="project-card">
  <h3>🔬 <a href="https://github.com/deepesh1singh/Cache-Aware-Performance-Optimization-using-gem5-and-RISC-V">Cache-Aware Performance Optimization using gem5 and RISC-V</a></h3>
  <p>Systems performance analysis and optimization using gem5 simulator and RISC-V architecture. Evaluates cache hierarchies and memory access patterns to optimize performance.</p>
</div>

<div class="project-card">
  <h3>🧠 <a href="https://github.com/deepesh1singh/ML-Cryptanalysis">Machine Learning in Cryptanalysis</a></h3>
  <p>Applies machine learning and statistical pattern recognition to analyze and attack classical ciphers such as Caesar, Vigenère, and substitution ciphers. Generates encrypted datasets, extracts character-frequency and n-gram features, and trains Random Forest, SVM, and Neural Networks to identify cipher patterns.</p>
</div>

<div class="project-card">
  <h3>⚙️ <a href="https://github.com/deepesh1singh/Resource-Allocation-and-Deadlock-Avoidance">Resource Allocation and Deadlock Avoidance</a></h3>
  <p>Operating systems project simulating concurrent resource allocation among multiple threads. Compares normal allocation with deadlock avoidance using the Banker's Algorithm. Uses POSIX threads, mutexes, condition variables, and barriers.</p>
</div>

<div class="project-card">
  <h3>📊 <a href="https://github.com/deepesh1singh/cross-encoder-early-exit-reranking">Efficient Re-ranking with Cross-Encoders via Early Exit</a></h3>
  <p>Information retrieval project that improves cross-encoder-based document re-ranking efficiency using early-exit techniques. Evaluates inference early stopping and ranked-list truncation to reduce computational cost while maintaining effectiveness.</p>
</div>

<div class="project-card">
  <h3>🤖 <a href="https://github.com/deepesh1singh/AI-Powered-Resume-Analyzer-Interview-Prep-Platform">Review AI – Intelligent Resume Analyzer & Interview Prep System</a></h3>
  <p>Full-stack AI-powered application that analyzes resumes against job descriptions. Generates match scores, skill-gap analysis, technical/behavioral questions, and personalized preparation plans. Supports PDF generation and report history.</p>
</div>

<div class="project-card">
  <h3>💼 <a href="https://github.com/deepesh1singh/Job-Platform">JobConnect Platform</a></h3>
  <p>Full-stack job recruitment platform connecting job seekers with employers. Enables job discovery, applications, profile management, and recommendations for candidates; job posting, application management, and candidate search for recruiters. Built with React.</p>
</div>

<div class="project-card">
  <h3>📈 <a href="https://github.com/deepesh1singh/Limit-Order-Book-Matching-Engine">Limit Order Book Simulator</a></h3>
  <p>Production-style C++20 matching engine simulating electronic exchange mechanics with strict price-time priority. Supports multiple order types, lifecycle management, self-trade prevention, multithreaded processing, historical replay, live statistics, and comprehensive validation.</p>
</div>

<div class="project-card">
  <h3>📉 <a href="https://github.com/deepesh1singh/Bias-Variance-Model">Customer Churn Prediction using XGBoost</a></h3>
  <p>Machine learning classification project predicting customer churn for a telecommunications company. Features data preprocessing, categorical encoding, hyperparameter tuning with RandomizedSearchCV, and evaluation using AUC, accuracy, precision, recall, and F1-score — achieving 0.85 validation AUC.</p>
</div>

<div class="project-card">
  <h3>🔐 <a href="https://github.com/deepesh1singh/Differential-distinguishers-for-ASCON-permutation">Differential Distinguishers for ASCON Permutation</a></h3>
  <p>Machine-learning-based cryptanalysis of the ASCON lightweight cryptographic permutation. Trains and compares LightGBM, CNN, and LSTM models to distinguish differential ciphertext pairs.</p>
</div>

<div class="project-card">
  <h3>🏦 <a href="https://github.com/deepesh1singh/BankBrain-Cloud-Ready-Microservices-Banking-Backend">BankBrain Smoke Tests</a></h3>
  <p>End-to-end testing framework for a cloud-ready, multi-agent banking backend. Validates integration across Mock Bank API, MCP Server, Support Agent, and A2A Gateway using FastAPI TestClient and fully mocked in-memory network calls.</p>
</div>

<div class="project-card">
  <h3>💾 <a href="https://github.com/deepesh1singh/Demand-Paging-Page-Replacement-Simulator">Virtual Memory Simulation with Approximate LRU</a></h3>
  <p>C-based virtual memory simulator modeling demand paging and page replacement across 128 concurrent processes. Implements page tables, shared physical frames, page-fault handling, and a 16-bit history-based Approximate LRU policy with a 4-tier frame selection strategy.</p>
</div>

<div class="project-card">
  <h3>⚖️ <a href="https://github.com/deepesh1singh/Multi-Agent-Framework-with-Formalized-Knowledge-Representations">Construction of Benchmark Datasets for Neuro-Symbolic Legal Reasoning</a></h3>
  <p>Multi-agent framework with formalized knowledge representations for legal reasoning and benchmark dataset construction.</p>
</div>

<div class="project-card">
  <h3>📁 <a href="https://github.com/deepesh1singh/Recursive-file-finder-by-extension">Recursive File Finder</a></h3>
  <p>POSIX C utility for recursive directory traversal and case-insensitive file-extension matching. Reports file ownership, size, and full paths for discovered files.</p>
</div>

<div class="project-card">
  <h3>🧩 <a href="https://github.com/deepesh1singh/Distributed-Sudoku-with-Processes-and-Pipes">Distributed Sudoku with Processes and Pipes</a></h3>
  <p>C-based interactive Sudoku system distributing the 9 board blocks across independent processes. Uses POSIX pipes for IPC with a coordinator routing commands and synchronizing updates across block processes.</p>
</div>

<div class="project-card">
  <h3>⏱️ <a href="https://github.com/deepesh1singh/CPU-Scheduling-Simulation-FCFS-and-Round-Robin">CPU Scheduling Simulation</a></h3>
  <p>Simulation of FCFS and Round-Robin CPU scheduling algorithms.</p>
</div>

<div class="project-card">
  <h3>🎮 <a href="https://github.com/deepesh1singh/Signal-Based-Child-Process-Game">Signal-Based Child Process Game</a></h3>
  <p>C-based Linux process-management simulation modeling an elimination game using multiple child processes and Unix signals. Uses fork(), exec(), and SIGUSR1/SIGUSR2 for inter-process communication.</p>
</div>

<div class="project-card">
  <h3>🔨 <a href="https://github.com/deepesh1singh/Dependency-Based-Rebuild-Simulator">Dependency-Based Rebuild Simulator</a></h3>
  <p>C-based build-system simulator modeling dependency-driven module rebuilding using process creation and synchronization. Generates dependency graphs and recursively rebuilds modules using fork(), exec(), and waitpid().</p>
</div>

<div class="project-card">
  <h3>🎤 <a href="https://github.com/deepesh1singh/Speech-Emotion-Recognition-using-CNN-on-Cross-Cultural-Audio-Data">Speech Emotion Recognition</a></h3>
  <p>TensorFlow-based CNN system classifying speech into 9 emotion categories using European and Indian datasets. Uses Mel-spectrogram features, actor-aware splitting, augmentation, mixed-precision training, and TTA — achieving 86.52% accuracy and 0.89 macro F1-score.</p>
</div>

<div class="project-card">
  <h3>⚡ <a href="https://github.com/deepesh1singh/High-Performance-Cache-Optimization-and-Memory-Analysis">High-Performance Cache Optimization and Memory Analysis</a></h3>
  <p>Systems performance project evaluating cache optimization techniques and memory hierarchy behavior using C, Linux perf, Python, and CACTI. Analyzes loop interchange, cache blocking, and cache access time/energy across sizes and associativities.</p>
</div>

<div class="project-card">
  <h3>🤖 <a href="https://github.com/deepesh1singh/AI-Job-Assistant">AI Job Assistant</a></h3>
  <p>Full-stack AI-powered job analysis platform using Sentence Transformers (MPNet) for semantic matching of job descriptions and resumes. Identifies matched/missing skills, generates insights and cover letters, tracks applications, and provides real-time analysis via cross-browser extension.</p>
</div>

<div class="project-card">
  <h3>🌐 <a href="https://github.com/deepesh1singh/Custom-Network-Transport-Protocol-with-Sliding-Window-over-UDP">KTP KSocket</a></h3>
  <p>Custom network transport protocol with sliding window over UDP.</p>
</div>

<div class="project-card">
  <h3>📊 <a href="https://github.com/deepesh1singh/High-Performance-Financial-Data-Processing">High-Performance Financial Data Processing</a></h3>
  <p>Benchmark comparing Pure Python, NumPy, Polars, and C++ for processing millions of financial market records. Evaluates as-of joins and trading analytics up to 5M trades. C++ implementation achieved 15.5× lower execution time and 3.7× lower memory usage than Python at 2M trades.</p>
</div>

<div class="project-card">
  <h3>🔒 <a href="https://github.com/deepesh1singh/TCP-File-Encryption-Client-Server">TCP File Encryption Client-Server</a></h3>
  <p>C-based client-server application transferring text files over TCP with server-side monoalphabetic substitution encryption. Implements socket communication, chunked transfer, encryption-key validation, and application-level message termination with Wireshark analysis.</p>
</div>

<div class="project-card">
  <h3>📋 <a href="https://github.com/deepesh1singh/TaskQueue-Server-Worker">TaskQueue Server-Worker</a></h3>
  <p>C-based TCP task queue system distributing arithmetic tasks from a central server to multiple worker clients. Supports concurrent connections, task assignment, result submission, queue management, and task recovery on worker disconnection.</p>
</div>

<div class="project-card">
  <h3>📧 <a href="https://github.com/deepesh1singh/MiniSMTP">MiniSMTP</a></h3>
  <p>C-based SMTP-like mail client-server system using TCP sockets. Implements HELO, MAIL FROM, RCPT TO, DATA, per-user mailbox storage, email retrieval, and multiple concurrent clients via POSIX threads.</p>
</div>

<div class="project-card">
  <h3>🔍 <a href="https://github.com/deepesh1singh/CLDP-Raw-Discovery">CLDP Raw Discovery</a></h3>
  <p>C-based custom network discovery protocol implemented directly over IPv4 raw sockets using experimental IP protocol number 253. Defines HELLO, QUERY, and RESPONSE messages with packet construction/parsing at the IP layer.</p>
</div>

<div class="project-card">
  <h3>🧬 <a href="https://github.com/deepesh1singh/Hybrid-CNN-LSTM-differential-distinguisher-for-ASCON-ACE-SIMECK-LLBC">Hybrid CNN-LSTM for Differential Distinguishers</a></h3>
  <p>Developed and evaluated eight neural architectures (AlexNet, LeNet-5, LSTM, MLP, VGG-11, VGG-13, LbEC, TbEC) for differential cryptanalysis of ASCON. Hybrid CNN-LSTM extends attack depth from 4→6 rounds for ASCON and 12→19 rounds for Simeck.</p>
</div>

<div class="project-card">
  <h3>🚤 <a href="https://github.com/deepesh1singh/Boating-Simulation-with-Threads-and-Synchronization">Boating Simulation with Threads and Synchronization</a></h3>
  <p>C-based boating center simulation using POSIX threads and synchronization primitives. Models concurrent boat and visitor activities with synchronized assignment, randomized durations, and controlled concurrent execution.</p>
</div>

<div class="project-card">
  <h3>🍽️ <a href="https://github.com/deepesh1singh/Restaurant-Simulation-Processes-Shared-Memory-Semaphores">Restaurant Simulation (Processes, Shared Memory, Semaphores)</a></h3>
  <p>C-based restaurant simulation using multiple processes and System V IPC. Models concurrent customers, waiters, and cooks with shared memory for state and semaphores for synchronization, including table capacity, order processing, and closing-time behavior.</p>
</div>

<div class="project-card">
  <h3>👥 <a href="https://github.com/deepesh1singh/Leader-and-Followers-Using-Shared-Memory">Leader and Followers Using Shared Memory</a></h3>
  <p>C++17 leader-follower coordination system using multiple processes and System V shared memory. Implements turn-by-turn synchronization, shared-state coordination, number generation, sum computation, and duplicate-sum detection.</p>
</div>

<div class="project-card">
  <h3>🔎 <a href="https://github.com/deepesh1singh/Demand-Paging-Simulator-Binary-Search-Swapping">Demand Paging Simulator (Binary Search + Swapping)</a></h3>
  <p>C-based demand paging simulator modeling memory management for concurrent processes performing binary searches on paged data. Implements page-fault handling, frame allocation, process-level swapping, and restoration under constrained physical memory.</p>
</div>

<div class="project-card">
  <h3>💾 <a href="https://github.com/deepesh1singh/Virtual-Memory-Simulation-with-LRU-Style-Replacement">Virtual Memory Simulation with LRU-Style Replacement</a></h3>
  <p>C-based virtual memory simulator modeling demand paging for multiple processes performing binary searches. Implements page-fault handling, fixed-frame allocation, LRU-style replacement, and frame acquisition classification.</p>
</div>

<div class="project-card">
  <h3>🎬 <a href="https://github.com/deepesh1singh/multimedia-database-system">Multimedia Database System</a></h3>
  <p>Full-stack multimedia database system using Node.js, Express.js, Sequelize, and SQLite. Manages books, videos, music, images, articles with JWT authentication, secure uploads, advanced search, playlists, comments, real-time notifications (Socket.IO), and admin analytics.</p>
</div>

<div class="project-card">
  <h3>📅 <a href="https://github.com/deepesh1singh/Event-Management-System">Event Management System</a></h3>
  <p>Full-stack event management system using Node.js, Express.js, MongoDB, and EJS with role-based access control.</p>
</div>

<div class="project-card">
  <h3>🏛️ <a href="https://github.com/deepesh1singh/GRAM-PANCHAYAT-MANAGEMENT-SYSTEM">Gram Panchayat Management System</a></h3>
  <p>PHP-based system for digitizing citizen services and administrative workflows. Implements role-based dashboards for administrators, employees, monitors, and citizens with secure login, complaint management, citizen data operations, and administrative monitoring.</p>
</div>

<div class="project-card">
  <h3>🔍 <a href="https://github.com/deepesh1singh/Approximate-Nearest-Neighbor-Search-Implementation-with-LSH-and-HNSW">Approximate Nearest Neighbor (ANN) Search with LSH and HNSW</a></h3>
  <p>Implemented and evaluated ANN search using Locality-Sensitive Hashing (LSH) and Hierarchical Navigable Small World (HNSW) graphs in Python. Compared approaches using Recall@5, Recall@10, Recall@15, and query latency.</p>
</div>

<div class="project-card">
  <h3>🤖 <a href="https://github.com/deepesh1singh/Machine-Learning-Model-Comparison-using-PyTorch-and-Spark">Machine Learning Model Comparison using PyTorch and Apache Spark</a></h3>
  <p>Implemented and compared ML models using PyTorch and Apache Spark. Evaluated model behavior across configurations and activation functions using MSE and comparative visualizations. Developed reproducible Jupyter Notebook implementations.</p>
</div>

<div class="project-card">
  <h3>📚 <a href="https://github.com/deepesh1singh/Large-Scale-Multi-Label-Text-Classification-with-PyTorch">Large-Scale Multi-Label Text Classification with PyTorch</a></h3>
  <p>Multi-label text classification system using Amazon-670K dataset with 135,909-dimensional TF-IDF features and 670,091 labels. Designed sparse low-rank classifier with rank-128 projection, memory-efficient label chunking, compared SGD, SGD+Nesterov, and Adadelta optimizers.</p>
</div>

<div class="project-card">
  <h3>📡 <a href="https://github.com/deepesh1singh/UDP-Word-by-Word-File-Transfer-Client-Server">UDP Word-by-Word File Transfer (Client-Server)</a></h3>
  <p>C-based client-server file transfer system using UDP and POSIX socket APIs. Transmits text files line by line through a custom application-layer protocol with filename requests, WORD-based data requests, and HELLO/FINISH control messages.</p>
</div>

<h2 class="section-title">📬 Connect With Me</h2>
<p style="font-size: 1.1em;">
  📧 <a href="mailto:deepeshsingh@iitkgp.ac.in">deepeshsingh@iitkgp.ac.in</a><br>
  🔗 <a href="https://github.com/deepesh1singh">GitHub</a> • <a href="https://linkedin.com/in/deepeshsingh">LinkedIn</a>
</p>

<hr style="border: 1px solid #e0e0e0; margin: 40px 0;">
<p style="text-align: center; color: #888; font-size: 0.9em;">
  <em>“Building systems that perform, models that reason, and code that scales.”</em>
</p>

</body>
</html>
