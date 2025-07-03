
# Call Center Queue Optimization

This project simulates a multi-server call center queue system using Python and SimPy, with an interactive dashboard built in Streamlit. It models customer call arrivals, service times, and abandonment behavior to analyze performance metrics and optimize staffing strategies.

---

## 🧠 Project Summary

- **Simulation Framework**: Discrete-event simulation using SimPy  
- **System Modeled**: Multi-server queue (call center) with customer abandonment  
- **KPIs Analyzed**:
  - Average wait time
  - Queue length
  - Customer abandonment rate
  - Agent utilization

The goal is to identify system bottlenecks, test different queue configurations, and provide insight into performance under varying load and staffing conditions.

---

## 📁 Project Structure

```

call-center-queue-optimization/
│
├── simulation.py        # SimPy simulation logic for queue behavior
├── kpi\_analysis.py      # Functions to compute and return KPIs
├── app.py               # Streamlit dashboard interface
├── config.yaml          # Simulation parameters (arrival rate, service time, etc.)
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation

````

---

## ⚙️ Technologies Used

- Python
- SimPy – for queue simulation
- Streamlit – for dashboard and UI
- pandas, matplotlib, seaborn – for data analysis and visualization

---

## 📦 Installation

Clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/call-center-queue-optimization.git
cd call-center-queue-optimization
pip install -r requirements.txt
````

---

## ▶️ How to Run

1. Configure simulation parameters in `config.yaml`.

2. Launch the dashboard:

```bash
streamlit run app.py
```

3. View and interact with queue performance metrics in your browser.

---

## 📊 Key Features

* **Abandonment modeling**: Customers leave the queue after waiting beyond their patience threshold.
* **Multi-server support**: Simulate multiple concurrent agents.
* **Real-time KPIs**: View how changes in arrival rate, service time, or server count affect:

  * Wait times
  * Queue length
  * Abandonment rate
  * Agent utilization
* **Flexible parameters**: Adjust number of agents, arrival rate, service time distribution, and more.

---

## 🔍 Insights & Use Cases

* Determine optimal staffing to reduce customer wait times
* Evaluate trade-offs between abandonment and agent idle time
* Simulate real-world call center conditions with adjustable variables

---

## 📈 Sample KPIs

| Metric            | Description                                 |
| ----------------- | ------------------------------------------- |
| Avg Wait Time     | Average time a caller waits before service  |
| Queue Length      | Average and max number of callers waiting   |
| Abandonment Rate  | % of callers who leave before being served  |
| Agent Utilization | % of time agents are actively serving calls |

---

## 🛠️ Future Enhancements

* Add caller priority classes
* Enable logging and export of simulation results
* Batch run experiments for different parameter sets

---

## 📄 License

This project is intended for academic and research purposes.

---

## 👤 Author

**Anthony Baptiste**
[LinkedIn](https://www.linkedin.com/in/anthony-baptiste00)
[Portfolio](https://antbap23.github.io/portfolio)






