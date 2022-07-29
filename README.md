## ABBA-IoT
ABBA-IoT stands for Artificial Behaviour Based Authentication for IoT. It is a data tampering and spoofing detection system that monitors a network of devices to detect anomalies in real-time.

# What is it?
Strictly speaking it is an intrusion detection system that enables a central controler to monitor data from a network of devices for signs of intrusion by an attacker.
This technique is based off of a weak form of authentication of the data transmitted by networked devices using pulses/heartbeats distributed pseudo-randomly over time. The pulse sequence is akin to a behaviour for any specific device, hence the name of the technique.

# Origins
The development of ABBA was started by [Dr. Raoul F. Guiazon](https://www.linkedin.com/in/raoulguiazon/) with the support of the Royal Academy of Engineering and the Office of the Chief Science Adviser for National Security under the UK Intelligence Community Postdoctoral Fellowship Programme.
The aim of this project is to improve the security of sensor networks - which are often at the foundation of many critical infrastructure - by increasing the probability of detection of malicious activities within the network.
This project was selected amongst 28 other promising projects for commercial development through CyberASAP (Cyber security Academic Start-up Accelerator Programme). CyberASAP is funded by the UK Government's [Department for Digital, Culture, Media and Sport (DCMS)](https://www.gov.uk/government/organisations/department-for-digital-culture-media-sport) in partnership with [Innovate UK](https://www.gov.uk/government/organisations/innovate-uk) and [KTN](https://ktn-uk.org/).

# Foundation

The algorithm implemented here is based on the article ["ABBA: A quasi-deterministic Intrusion Detection System for the Internet of Things"](https://arxiv.org/pdf/2108.03942.pdf). That article defines the conceptual structure and framework of the technique ABBA and provides mathematical proofs with respect to the probability of detection of an intruder given the types of primitives used in any practical implementation. Any such implementation like the one presented in our [repository](https://github.com/abbaiot/ABBA_Concept) will come with different security garantees due to the primitives and parameters chosen.

# Implementation

The code presented [here](https://github.com/abbaiot/ABBA_Concept) is developed using [Node-red](https://nodered.org/) a low-code programming tool for event-driven applications and based on Node.js. This was chosen for the ease of use and the flexibility it allows in quickly building and testing prototypes with easily available sensors. 

# Demo
Click on this [youtube](https://youtu.be/TmyAqOMl52U) link to watch a video demonstration of the technology ABBA-IoT adapted and applied to a CAN network for a usecase in automotive.

# Warning

The code available is at a very early stage of development an should only be used for testing and research purposes.

# Open development

Please feel free to contribute to this project, the list of issues to address will be available shortly along with the long term vision for this project.

