# Queueing Theory Calculator — M/M/1 and M/M/k Models

This Python program calculates key performance metrics for **queueing systems** under the **M/M/1** (single server) and **M/M/k** (multiple servers) models.  
It is designed for academic, research, and operations analysis purposes, following **PEP-8** style conventions and fully written in English.

---

## Features

- Calculates essential queueing parameters:
  - **ρ (rho)** — System utilization  
  - **Lq** — Average number of customers in queue  
  - **L** — Average number of customers in the system  
  - **Wq** — Average waiting time in queue  
  - **W** — Average total time in the system  
  - **P₀** — Probability that the system is empty  
- Computes the **probability that queue length exceeds n** → *P(Lq > n)*  
- Supports both:
  - **M/M/1 model** (single-server system)  
  - **M/M/k model** (multi-server system)  
- Includes factorial calculations and probability distribution functions for states *n < k* and *n ≥ k*.  
- User-interactive console interface for data input.

---

## How It Works

1. The user chooses between M/M/1 or M/M/k.  
2. The program requests input values:
   - Arrival rate (λ or `lambda`)  
   - Service rate (μ or `mu`)  
   - Number of servers (`k`, only for M/M/k)  
3. The script computes performance metrics and, if selected, calculates the probability that the queue length exceeds a given number of customers.  
4. Results are displayed clearly in the terminal.

---

## Example Output

```text
1. M/M/1
2. M/M/k

Lambda: 3
Mu: 5

rho = 0.6
Lq = 0.9
L = 1.5
Wq = 0.3
W = 0.5
P0 = 0.4
P(Lq > 3) = 0.005305
```
## Applications
1. Operations research and industrial engineering courses.
2. Performance evaluation in service systems, production lines, and network design.
3. Educational projects in probability and stochastic processes.

