Electronic voting System using Blockchain
ELEN E6883
Topics in Signal Processing: Introduction to Blockchain
Spring-2022
Name: Uday Mukhija
UNI: um2158

Abstract

Online voting as a phenomenon is gaining momentum as well as importance in modern society. It has great potential to decrease organizational costs, increase transparency and increase voter turnout. It eliminates the need to print ballot papers or open polling stations—voters can vote from wherever there is an Internet connection. Despite these benefits, online voting solutions are viewed with a great deal of caution because they introduce new threats. 
The first aspect of our design is the registration process, verifying a voter is essential in establishing security within the system. Making sure that someone’s identity isn’t being misused for fraudulent purposes is important, especially when voting is considered, where every vote matters. A single vulnerability can lead to large-scale manipulations of votes. Electronic voting systems must be legitimate, accurate, safe, and convenient when used for elections. Nonetheless, adoption may be limited by potential problems associated with electronic voting systems. Blockchain technology came into the ground to overcome these issues and offers decentralized nodes for electronic voting and is used to produce electronic voting systems mainly because of their end-to-end verification advantages. This technology is a beautiful replacement for traditional electronic voting solutions with distributed, non-repudiation, and security protection characteristics. For a sustainable blockchain-based electronic voting system, the security of remote participation must be viable, and for scalability, transaction speed must be addressed.

Introduction to Decentralized Application:

Blockchain technology provides a platform for creating a highly secure, decentralized, anonymized yet auditable chain of record. In this project, this has been used to record and report votes and prevent voter fraud in elections. 
The project has been made using the following applications:
1.	Remix IDE
2.	Ganache
3.	Metamask Wallet

The Blockchain Structure is also known as an append-only data structure, such that new blocks of data can be written to it, but cannot be altered or deleted. Private blockchain limits the read and write access, only specific participants can verify their transactions internally. That makes the transaction on a private network cheaper, since they only need to be verified by a few nodes that are trusted and with guaranteed high processing power. Nodes are very well-connected and faults can quickly be fixed by manual intervention, allowing the use of consensus algorithms which offer finality after much shorter block times. In this project, I have used Permissioned Blockchain which will use the Proof of Authority(PoA) consensus Algorithm. A Consensus Algorithm is used to set restrictions on selected known entities to certify and validate transactions on Blockchain. Here, this will help us to stop adding new people without Administrators Permission. This Algorithm Proves to be helpful because it does not leak the Voter’s Information and Voting Data.

The smart contract will be linked to the wallet (in the sample run shown below, it is linked with a Metamask wallet). The user types in the candidate ID, age and name. Then they proceed to voting for the candidate of their choice. Each user can only vote once. The user can check the candidate they voted for, as well see get a breakdown of votes in the voting results, see owners of the votes cast and see the winners of the election. 


Originality:

Currently, in most parts of the world, voting either takes place through a ballot or through Electronic Voting Machines (EVMs). These EVMs are of two of types, namely remote voting system and a direct recording system. The direct recording system architecture consists of a power unit, control unit, display unit and a voting unit. However, there are constant rumours and conspiracy theories about the EVM machines, as well as ballot votes, if one is to look at how political discourse shapes in large democracies like India and the United States of America.
Compared to existing EVM machines, the smart contract in the project offers fast synchronization, secure channel and enrollment control. 
Also, in the literature review, it was found that present smart contracts worked with Exonum, which uses rust programming language and isn’t user developer friendly. So I used Solidity. The vote can be viewed publicly, it is easily verifiable along with the person making it and it cannot be changed once it is given a unique hash. Apart from voter verification, a distributed system like this the attackers will have to DDoS every single boot node in the private network, which can be immediately located. No individual also has the access to create a large number of nodes for a Sybil attack in the system proposed in this project. 

Sample Run:

 
 
 
 

Conclusion:
We have created a decentralized voting system that promises increased transparency, eliminates fraud and rigging, shows results in real time and empowers voters and shareholders. It makes remote voting easier and reliable, thereby leading to a more direct and inclusive democracy.  
![image](https://user-images.githubusercontent.com/78294167/167953303-5671ea7f-0c49-4aaf-a435-2f6eab1b47e5.png)
