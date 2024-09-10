
# Blockchain-Based Data Sharing System

This project demonstrates a blockchain-based system for secure data sharing, designed to ensure privacy and trust between data owners and data requesters. It involves multiple Python scripts that simulate various roles in the system, such as data providers, clients, and the blockchain network.

## Project Overview
This project implements a blockchain-based architecture to handle secure data queries. The system is designed to ensure that data ownership is preserved and that queries for data are handled transparently, securely, and without tampering. It includes components that simulate data owners, clients, and a blockchain ledger for accountability.

## Directory Structure
- **Python Scripts/**: Contains all the Python scripts necessary to run the system.
  - `db_provider.py`: Simulates the database provider's role, who manages the data in the system.
  - `data_owner.py`: Represents the role of the data owner who controls access to their data.
  - `blockchain.py`: Implements a basic blockchain structure to keep a ledger of all transactions and queries made on the data.
  - `adv_client.py`: Simulates an adversary client, used to test the security and privacy features of the system.
  - `query_client.py`: Represents the role of a client who requests data.
  - `driver.py`: A central driver script to run the system and coordinate the interactions between the different components.
  
- **Mini Project3 Report.pdf**: A report outlining the objectives, design, and implementation of the project.

## Requirements
The project is implemented in Python and requires the following libraries:
- `flask`
- `requests`
- `blockchain` (if using a custom blockchain library)
  
You can install the required libraries using `pip`:

```bash
pip install -r requirements.txt
```

## How to Run the Project
1. Clone the repository or download the project files.
2. Navigate to the `Python Scripts` directory.
3. Run the `driver.py` script to start the system:
   
   ```bash
   python driver.py
   ```
   
4. The system will simulate the interaction between data providers, clients, and the blockchain, ensuring the secure sharing of data.

## Project Features
- **Blockchain-Based Security**: Ensures that all transactions and data queries are immutable and traceable.
- **Data Ownership**: Data owners have control over who can access their data.
- **Client Interaction**: Multiple clients can query data, and their interactions are logged on the blockchain for transparency.

## Authors
This project was developed as part of a mini project on blockchain-based systems for secure data sharing.
