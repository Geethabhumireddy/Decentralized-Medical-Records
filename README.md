**Decentralized Medical Records System**
Overview
This project aims to provide a secure, decentralized platform for maintaining patient records. Patients can authorize specific doctors to access their medical records for examination purposes, ensuring privacy, security, and transparency. The system leverages blockchain technology to create a tamper-proof and efficient solution for healthcare data management.

**Features**
Decentralized Storage: Medical records are stored securely on a blockchain network, ensuring data integrity and privacy.
Patient-Controlled Access: Patients have complete control over who can access their records.
Real-Time Updates: Records can be updated in real-time, facilitating efficient consultations.
Technology Stack:
Frontend: Built with ReactJS for a user-friendly and responsive interface.
Backend: NodeJS to handle API requests and interactions with the blockchain network.
Blockchain: Smart contracts written in Solidity to manage data securely.
Database: MongoDB to store visual records and metadata.
**Project Architecture**
Patient Interface:
Patients can create, view, and grant access to their records.
Records are linked to unique patient IDs and stored on the blockchain.
Doctor Interface:
Doctors can request access to patient records.
Authorized doctors can view medical records for diagnostic purposes.
Blockchain:
Implements a Solidity smart contract to ensure tamper-proof transactions.
Tracks access permissions and record modifications.
Database:
MongoDB is used to store non-sensitive data, such as visual files or supplementary metadata.
**Technologies Used**
Frontend:
ReactJS: For building a dynamic and responsive UI.
Bootstrap: To create a clean and modern design.
Backend:
NodeJS: For handling server-side logic.
ExpressJS: To create RESTful APIs.
Blockchain:
Solidity: For writing smart contracts.
Ganache: Local blockchain for development and testing.
Web3.js: To interact with the Ethereum blockchain.
Database:
MongoDB: For storing and retrieving patient record metadata.
Tools:
MetaMask: To connect to the blockchain network.
Postman: For API testing.
