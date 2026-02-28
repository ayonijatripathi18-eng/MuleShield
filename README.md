# MuleShield
A real-time graph-based system for detecting cross-channel mule accounts in financial transactions. It links identities across banks, UPI, and wallets, builds a live transaction graph, and applies continuous risk scoring to flag suspicious money flows and intermediary behavior early.

# Solution Description
 Our solution is a real-time, graph-based system designed to detect cross-channel mule accounts in financial ecosystems. It continuously monitors live transactions across banks, UPI, and digital wallets. Instead of analyzing accounts in isolation, the system models all transactions as a dynamic graph, enabling detection of hidden relationships and suspicious money flows as they occur.

# How It Works
Live Transaction Processing
 Incoming transactions are processed in real time, closely simulating real-world payment systems and allowing immediate analysis.

Cross-Channel Identity Linking
 Accounts across different platforms are linked using shared attributes such as phone numbers, device IDs, or IP addresses. This provides unified visibility across channels and helps identify coordinated activity.

Dynamic Transaction Graph
 Each transaction updates a live graph where nodes represent accounts and edges represent money transfers. This evolving structure captures complex movement patterns that are difficult to detect with traditional methods.

Real-Time Risk Scoring
 Every account is assigned a continuously updated risk score based on behavioral and network signals, including rapid inflow and outflow of funds, interaction with many unique senders, intermediary behavior within transaction chains, and usage across multiple platforms.

Alerts and Visualization
Accounts that cross risk thresholds are flagged immediately. A visualization dashboard displays transaction flows, linked identities, and emerging mule networks, enabling faster investigation and response.

# Why This Works
 The system enables early fraud detection before significant losses occur. Graph-based analysis exposes hidden mule behaviors that rule-based or isolated monitoring systems often miss. Cross-channel visibility removes platform silos, and the explainable, rule-driven scoring makes the solution practical and suitable for real-world financial environments.
