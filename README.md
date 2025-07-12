# Blockchain Backed Federated Learning for IoT Device Authentication
The rapid expansion of Internet of Things (IoT) networks has created an urgent need for
secure, efficient, and privacy-preserving device authentication mechanisms. Traditional centralized approaches to machine learning for IoT security often require collecting raw data from
devices, leading to concerns around data privacy, single points of failure, and vulnerability
to adversarial attacks. This project proposes a Blockchain-Backed Federated Learning (FL)
framework that addresses these challenges by enabling IoT devices to collaboratively train
a global machine learning model without sharing their local data. Each device independently
trains a lightweight anomaly detection or device classification model on its own data and shares
only model updates with a central FL server. To ensure the authenticity and integrity of these
updates, they are hashed and recorded on a private blockchain network before aggregation,
providing a tamper-resistant audit trail. The blockchain also validates model updates by verifying their hashes, protecting against model poisoning and data manipulation attacks. A central
server combines the validated updates to refine the global model, which is then redistributed
to participating devices. This framework not only enhances privacy and data security but also
ensures the robustness of IoT device authentication through decentralized consensus and immutable record-keeping. Future extensions could include blockchain-based identity management, advanced consensus mechanisms, and real-time performance visualization through interactive dashboards 

## Contributors
- Harshitha Yarra
- Srihita Karempudi
- Anamitra Joshi
