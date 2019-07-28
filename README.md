# Microsoft Codefundo 

### Team bits_R4

##### Team Member 1: Amit Mishra
##### Team Member 2: Yaduraj Gupta

## Idea on secure voting system using Azure Blockchain

#### Why Use BlockChain?
A normal Database has to be tracked by a single computer and hence that computer has to be trusted but in Blockchain the system is decentralized and hence working on many computers simultaneously which means none of the computers have to be trusted. In fact, to take over a complete Blockchain network you would need to control over half the nodes(computers) in it which is a mighty task for any one person or organization.

#### Major Components
Now we explain some Major components of a blockchain and then we go on to explain how we use said components to implement a voting System

#### Database
Stores the complete history of transactions and the order in which these transactions occurred.
#### Peer-to-Peer Network-
It is the mechanism that manages the database and communicate changes to the database which are called transactions.

#### Implementation of the voting system
##### ID Verification : 
A person has to prove that He/She is allowed to vote in a given election which can be done as a transaction on a block chain.

##### Anonymous Voting Account : 
A voting account can be shown to be owned by one of the voting ids but you can’t tell which voting ID specifically it belongs to. Also you know that each ID owns at most one account. Creating this account can also be done as a transaction on the network.

Finally when we have set up this Blockchain Network, we have a public ledger that anyone already part of the network can verify .This make it extremely transparent and hence above the suspicion of sabotage or foul play.

#### Implementing in India

##### Who will be a suitable user for this system or What does ID verification checks?
i. Person must be above 18 years old.\
ii. He/she should hold an Aadhaar Card.\
iii. He/she should have a phone with a working camera. 

##### Registering on the voting system
i. Use OTP based authentication on mobile number linked with aadhar number.\
ii.Check if user is eligible for voting and authenticate accordingly. 

##### Voting
i. Vote can be given only once. Multiple confirmation dialog boxes so that the user doesn't make a mistake.\
ii. Allot different slots such that server is never overloaded with requests.\
iii. While voting, to confirm a legible vote the user must click a video of himself saying a random phrase.\
iv. Use speech to text api to check if the voter said the correct phrase and also confirm the identity of the voter via face recognition and cross check with Aadhar Card photo.\
v. Use Azure Blockchain to register vote.  

