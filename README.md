# **UCB-AdOptimizer**  

A reinforcement learning-based **ad selection optimizer** using the **Upper Confidence Bound (UCB)** algorithm to maximize click-through rates (CTR).  

## **Overview**  
UCB-AdOptimizer solves the **Multi-Armed Bandit problem**, where an AI dynamically learns which ads get the most clicks while balancing **exploration** (trying new ads) and **exploitation** (choosing the best ad so far).  

## **Features**  
- Implements **UCB Algorithm** for ad selection  
- Optimizes **Click-Through Rate (CTR)** over time  
- Ensures a balance between **exploration & exploitation**  
- Visualizes **ad selection trends** with a histogram  

## **Installation**  
```bash
git clone https://github.com/your-username/UCB-AdOptimizer.git
cd UCB-AdOptimizer
pip install -r requirements.txt  # If needed
```

## **Output**  
- A **histogram** displaying ad selection frequency  
- The **total reward (CTR) achieved**  
