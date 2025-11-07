# 🧩 QueueCTL - Background Job Queue (Jupyter Notebook Version)

## Objective
**QueueCTL** is a background job queue system implemented entirely in a **Jupyter Notebook** using **Python + SQLite**.

It demonstrates a production-style background job processor that supports:
- Multiple workers
- Automatic retries with **exponential backoff**
- **Dead Letter Queue (DLQ)** for permanently failed jobs
- Persistent storage across restarts

This project is the **Jupyter-based implementation** of the *QueueCTL Backend Developer Internship Assignment*.

## ⚙️ Features Covered
Enqueue background jobs  
Process jobs with multiple worker threads  
Retry failed jobs automatically  
Exponential backoff retry delay  
Dead Letter Queue (DLQ) for failed jobs  
Retry jobs from DLQ  
SQLite persistence (`jobs.db`)  
Live visualization using pandas  

## Tech Stack

| Component | Technology |
|------------|-------------|
| **Language** | Python 3.9+ |
| **Database** | SQLite |
| **Interface** | Jupyter Notebook |
| **Concurrency** | threading |
| **Visualization** | pandas |

## Project Structure
QueueCTL/
├── QueueCTL_Final.ipynb # Main notebook (complete solution)
├── README.md # Documentation (this file)
└── jobs.db # SQLite database (auto-created)

