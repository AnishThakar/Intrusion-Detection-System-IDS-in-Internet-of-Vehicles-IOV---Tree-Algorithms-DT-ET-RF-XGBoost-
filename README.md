# Intrusion-Detection-System-IDS-in-Internet-of-Vehicles-IOV---Tree-Algorithms-DT-ET-RF-XGBoost-

Intrusion Detection System(IDS) in Internet of Vehicles(IOV) --- Tree Based ALGORITHMS
[AV] Autonomous Vehicle + [IOV] *Internet of vehicle = *[ITS]Intelligent Transport Systems

[AV] = [V2X] Vehicle to Public[V2P], Vehicle[V2V], Infra[V2I]

[IDS] <--[AV] + [IOV] <-- External /Internal Communication Threat

Dataset: CICID 2017- Standard Attack Scenario___________________ [28,30,743 x 79]

Pre Processing : Normalization ,Encoder_____________________________[56,661 x 79]

Oversampling : SMOTE <-- Handle Class Imbalance Data __{4 :1500}

Models ⁉

                Accuracy     Acc(with Imp Feature)
Decision Tree  : 99.67 %             99.68 %
Random Forest  : 99.62 %             99.74 %
Extra Trees    : 99.53 %             99.64 % 
XGBoost        : 99.55 %             99.53 %
________________________________________________
Stack          : 96.63 %             99.63 %
