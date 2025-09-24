# Collision Avoidance MAC Protocol in Underwater Acoustic Sensor Network with Reinforcement Learning

This repository contains Jupyter notebooks implementing a **Collision Avoidance Medium Access Control (MAC) Protocol** for **Underwater Acoustic Sensor Networks (UASNs)** using **Reinforcement Learning (RL)** techniques.

---

## 📂 Repository Contents

### 1. `Time_MAC2.ipynb`
- Implements a **time-based MAC protocol** for underwater networks.  
- Uses RL for adaptive time-slot assignment and efficient collision avoidance.  

### 2. `Timescedul_CA_MAC_using_RL.ipynb`
- Focuses on **collision avoidance scheduling**.  
- Leverages RL agents to dynamically allocate time slots to nodes, reducing packet loss and improving throughput.  

### 3. `Timeslot_MAC_RL_ahmad.ipynb`
- Experimental notebook that refines **timeslot-based MAC scheduling** using reinforcement learning.  
- Compares results across multiple simulation runs.  

---

## 🌊 Background
Underwater Acoustic Sensor Networks (UASNs) are used in ocean monitoring, surveillance, and environmental applications.  
However, they face challenges due to:
- High propagation delays  
- Low bandwidth availability  
- High probability of collisions in shared medium  

To address these, this work applies **Reinforcement Learning** to design an intelligent **MAC protocol** for efficient communication.

---

## 🚀 Getting Started

### Prerequisites
Install the following dependencies:
```bash
pip install numpy pandas matplotlib jupyter
```

### Running the Notebooks
1. Clone this repository:
```bash
git clone https://github.com/mishaurooj/Collision-Avoidance-MAC-Protocol-in-Underwater-Acoustic-Sensor-Network-with-Reinforcement-Learning.git
cd CollisionAvoidance-MAC-RL
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook
```

3. Open and run any of the provided notebooks.

---

## 📊 Features
- **Reinforcement Learning-based scheduling** for collision avoidance.  
- **Dynamic timeslot assignment** for nodes in underwater networks.  
- **Performance metrics**:
  - Packet Delivery Ratio (PDR)  
  - Average Delay  
  - Throughput  
  - Energy Efficiency  

---

## 📌 Example Outputs
- Graphs showing reduced collisions with RL-based scheduling.  
- Plots comparing traditional MAC vs RL-enhanced MAC performance.  
- Timeslot assignment schedules optimized via RL.  

---

## 📌 Citation
If you use this repository, please cite it as:

```bibtex
@misc{uasn_mac_rl2023,
  title={Collision Avoidance MAC Protocol in Underwater Acoustic Sensor Network with Reinforcement Learning},
  author={Misha Urooj Khan},
  year={2023},
  howpublished={\url{https://github.com/mishaurooj/Collision-Avoidance-MAC-Protocol-in-Underwater-Acoustic-Sensor-Network-with-Reinforcement-Learning/}}
}
```

---

## 👥 Contributors
- Misha Urooj Khan – Implementation and experiments  
- Community contributions welcome  

---

## 📜 License
This project is released under the **MIT License**.  
Free for academic and research use with proper citation.

---
