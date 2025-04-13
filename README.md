 
# Paper Title: FLDQN: Cooperative Multi-Agent Federated Reinforcement Learning for Solving Travel Time Minimization Problems in Dynamic Environments Using SUMO Simulation

This repository contains the implementation and results for the FLDQN algorithm, as presented in the related research paper.

This repository contains the implementation code for the paper *"FLDQN: A Novel Approach for Efficient Agents Cooperation and Travel Time Minimization Using Federated Learning, Reinforcement Learning, and SUMO Simulation"*. The code demonstrates how FLDQN can reduce travel time through efficient learning.

📄 **Read the full paper here:** [https://www.mdpi.com/1424-8220/25/3/911](https://www.mdpi.com/1424-8220/25/3/911)

 
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/WahabMam/FLDQN-Paper-Code/tree/main
2. Navigate to the project directory:
   ```bash
   cd FLDQN-Paper-Code

3. Install the required Python packages:
    ```bash
    pip install -r requirements.txt
4. Ensure you have SUMO installed version(1.14.1), as it is required for traffic simulation.
    
You need to install [SUMO](https://www.eclipse.org/sumo/) based on your operating system:

- [Download for Windows](https://sumo.dlr.de/docs/Installing/Windows_Build.html)
- [Download for Linux](https://sumo.dlr.de/docs/Installing/Linux_Build.html)
- [Download for macOS](https://sumo.dlr.de/docs/Installing/MacOS_Build.html)

5. Modify the parameters in the config.yaml and in the server.py files to match your system's specifications and your desired settings.
6. It is recommended to use a virtual environment to manage your dependencies and avoid conflicts with other packages on your system.


## Generating the Results
To run the experiment and generate results, please refer to the instructions in our related repository [here](https://github.com/nclabteam/sumo-marl).
