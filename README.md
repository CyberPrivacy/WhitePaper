# [CyberPrivacy Protocol](https://github.com/CyberPrivacy/WhitePaper)  - Some solutions to Web3 privacy data 
[![solidity](https://img.shields.io/badge/dynamic/xml?color=brightgreen&label=solidity&query=0.8&url=https%3A%2F%2Fdocs.soliditylang.org%2Fen%2Fv0.8.19%2F)](https://docs.soliditylang.org/en/v0.8.19/)  &emsp;[Chinese Version](https://github.com/CyberPrivacy/WhitePaper/blob/main/README_CH.md) 


In the era of web2, our data is stored on facebook, twitter, google and other large Internet product providers. In order to get the permission to use these products, we need to compromise our **crucial privacy rights**.

From BBS, Tweets, Chats, Bank Accounts, Stocks, Investment Assets, E-books, real estate, GPS Information, Illness ,Vehicles, Electrical Appliances, Surveillance, Government Affairs to all your future activities in VR, AR glasses record ,even your **mindset and thought** reflected by the brain-computer interface such as Neuralink, All these things will be stored on the server in digital form. **We are entering the cyber world at an unprecedented speed now, but our data is not being properly protected**.

Have you ever doubted that many administrators may have the access to view the private conversations between you and your close girlfriend. While home cameras are providing services for you, your data is also sold by administrators on the dark web. Funds in your bank account may be frozen and cleared by a manager's intentional or unintentional operation. In the future, the access to enter public places and join in activities may disappear directly due to the prejudice and personal hatred of managers against you, which will lead to your social death.

<div align=center>
<img src="https://images.pexels.com/photos/96612/pexels-photo-96612.jpeg?cs=srgb&dl=pexels-photomix-company-96612.jpg&fm=jpg" width="50%" >
</div>

Large Internet companies arbitrarily decide whose accounts should be locked, whose videos should be pushed, and which kind of videos should get more traffic than others. We can only passively accept the emotional tendencies, ideologies, political concepts, and values by Internet administrators . They only need to change a simple parameter, and it may be possible to change the subconscious of a large number of people.

**We can't be aware of the management's real judgment standard**, in the meanwhile we cannot know anything from a system which works by the unpredictable code on the server.

**The individual is powerless in the face of a monopoly digital organization, even the most talented genius**. The only option is to bend your waist, and agree to all the terms it sets for you in order to get the services which you deserved.  Users, employees, and small companies will lose their voice to speak, and can only hope to get gifts from the large organization.

The rapid development of Internet technology has successfully connected the world and created unbelievable communications of different cultures, but at the same time, it has created a centralized largest digital monster. The power of this world has never been so centralized that the administrators who hold the keys easily control the fate of the world.

**Whether you realize it or not, we have come to the cyber world, and what the future cyber world will be  depends on everyone's choices**.

## Current Development in Web3

In the era of web3, we can see the vigorous development of blockchain technology, from centralization to decentralization, from blockchain to smart contracts, from tokens to DAO(decentralized autonomous organization), you can faintly feel the fully new birth of a new concept-**“Code is the law”**. 

**Trust the code, not the authority of the organization, trust the process, not the credit of the administrators**.

Because of the credit of the code, Uniswap can accumulate a large amount of funds in a short time, DAO  can allow everyone to use their voting rights in a fair way, Aave can realize a mechanism that protects both borrowers and lenders. However, the existing Ethereum cannot support huge social applications. In aspects of performance, it can only execute several transactions per second. In aspects of privacy protection, data is stored on the public chain and can be accessed by everyone. In aspects of system architecture, it cannot support the migration of Current Internet applications.

|  |Traditional internet | Ethereum  | Ideal Web3 |
|  ---- | ---- | ----  | ----  |
| language |  variety | solidity | variety |
| performance  | high speed | very slow | high speed |
| fee  | no fee | expensive | no fee |
| privacy  |  not meet| public storage | protect everyone |
| code is law  |  not meet | perfect | satisfied |

## How to create a technology that can solve the problems we currently face.

How to build a new generation of system architecture can not only meet the performance and software architecture requirements of existing Internet systems, but also conform to the needs of privacy protection. I think the following 6 principles need to be implemented.

First, **all code need to be released publicly,any code change can only be deployed after sufficient audit time**. After developers finish code, it need to be published on the Internet for public audit, allowing stakeholders(included users) to review the code. After a fixed deployment interval period and approved by the DAO(application owner) community, the code can finally be deployed to the server.

Second, **we need to invent a special trusted server cluster called “Privacy Server Cluster” whose data cannot be obtained by the server operators**. The Privacy server cluster will run a specific operation system, and provide a virtual environment for application and the server operator can only decide whether to start the system, and which DAO community and code to connect to the virtual environment, they can not get any data from the server cluster. After the system starts, it will automatically pull the voting records on the blockchain, the code, and deploy the latest code.

Third, **the operation system needs to support verifiable**, verifying that the currently running code is the specified code, not fake one.

Fourth, **the connections between the user and privacy server cluster should be encrypted in the network**. The server-side digital certificate used must be able to be generated only on the server-side, and cannot be copied or accessed to prevent data theft in the connections.

Fifth, data is owned by users, and all developers should provide **a unified interface specification to allow users to transfer, delete, and authorize data**.

Sixth,**the administrators’ every action should be publicly displayed**. They can get benefit from the application, but the power is fairly limited. They can only configure system parameters, view statistical information, decide which algorithm is used. Above all, they cannot access the user's private data information.

Seventh,**server clusters need to distribute form a blockchain**
<div align=center>
<img src="https://github.com/CyberPrivacy/WhitePaper/blob/main/code-release-process.png" width="100%" >
</div>

## How to make the system operator lose the permission to read system data?

In the existing server cluster technology, to ensure network connections security, **SSL should be generated internally by the server**, and only the server application can decrypt network traffic; in addition, **TPM can be used to handle disk encryption and lock the basic configuration of the system**; there is also **memory encryption technology**, the memory’s data will keep encrypted until CPU,but it is conceivable that the operator can physically disassemble the CPU package, connect the physical circuit, and obtain the CPU data in an intrusive or semi-intrusive way to obtain key.. There are many security technologies in use to prevent from attack(, and so on) .

Such as **physically isolating the server**, increasing the difficulty of physically intruding into the server, and triggering the key removal program if physical intrusion is discovered. The system can not only use encryption at the physical level of the disk, but also add encryption at the developers’ side, so that even the server operator and developer master private key ,they can not decrypt data independently. And we can use side-channel random protection to prevent from obtaining some side-channel info.

What's more, we can use **homomorphic encryption** to consolidate **data security**. **In this way, the data's key can be mastered by yourself, only you can decrypt the sensitive data locally, and in the meanwhile**.  But Homomorphic encryption has many issues currently and now it is only an aid in my system to enhance security, and in my vision it is only used within particularly sensitive personal data.(If the system runs rightly as I mentioned above, there is no need to use Homomorphic)


But how to verify whether the server adopts the specific security mechanism, if the server operator claims to have adopted the security mechanism in fake. I think it may be necessary to verify the security of the system through live broadcasts, videos, materials, and even field visits by verifiers.

Can we expect a centralized Amazon-like cloud server that deprives operators of their access to data, I think, compared to the current system, this is still a huge improvement. The interests of the platform side are different from those of the application owner(DAO), which makes it less likely to do evil things even if it reserves the access for itself, **but I do not hope that there is only one monopoly CyberPrivacy in the world. Many distributed providers are the best solution**.

## How to be compatible with the existing application architecture?

**We can use docker technology, which can automatically complete the server configuration required by the code**. The server downloads the docker configuration file and code, and the docker automatically builds and deploys the code.

With the increased number of users, the performance of the Privacy Server Cluster needs to be increased accordingly. How to enhance the performance of the server cluster, while this server cluster is protected from physical touching? 

We can imagine two approaches.

First, we can solve it through the management method. If it needs to be expanded, the DAO community should public a notification, after a fixed period of time for stakeholders to learn about it, the validator can participate in monitoring the expanded process ,and report any suspicious behavior.

Second, we can solve it through technology. Creating a distributed system will be a good choice.But Obviously, each server cluster in this distributed system should be Privacy Server Cluster.

## How to develop code that meets the security requirements?

From the release of the code to deployment in the production, it is necessary to have sufficient time for stakeholders to audit and review. But in the meanwhile, we need to respond quickly to significant code security issues ,so that we can protect the data from hackers’ attack by exploiting vulnerability.

The review time lap can be set according to the amount of new code (objective items), the complexity of code changes, and the urgency of the event. Among them, the complexity of code changes and the urgency of events require subjective judgment. It is recommended that a third-party organization undertake this responsibility to prevent cheating.

In addition, we also need a unified protocol mechanism for users to authorize the transfer of data.I think a better solution is the **digital wallet** account key system. This key system is used as a unified account mechanism. Users only need to confirm the authorization, and they can automatically accept data migration in the target application, but the key may be leaked. So the special security application can provide more identity verification and initiate an authorization application.

This account system should be made into a version that conforms to each software language and embedded in the system.

**Code is law, when you write code, it is the same as you make law,which determines that CyberPrivacy code is totally different from ordinary code and requires extremely strict code security**.

If we finally implement the CyberPrivacy plan, what will it bring to the world?

After depriving the owner(DAO) and operators of the right to modify the data, it also means that the concept borned that **“Code Is Law”**.

If public code can be trusted, data trust is no longer a problem, even the foundation of the metaverse is formed.

<div align=center>
<img src="https://github.com/CyberPrivacy/WhitePaper/blob/main/privacy-security.png" width="100%" >
</div>

## Commercialization Plan

Commercialization is such an important approach to success that it may be crucial to success.

We can realize commercialization by authorizing trusted server to use "CyberPrivacy". This is the simplest way to earn money.

Maybe we can go further. Release token which is used by purchasing rent of CyberPrivacy Server, and DAO governance.


## What will happen in the future?

1. Replacement of traditional Internet applications. There will be applications similar to twitter, google, Facebook, Tiltok, etc., but the new system will not have the same serious privacy stealing and security leak problems as the old system. Because of the convenience of data migration, internet applications cannot establish their own data monopoly advantages, it will lead to a more free market. Because the administrator's operation is fully open and transparent, corruption and shady activities will be greatly reduced.

2. **When we can ensure the data is true, the value of data will be enhanced. When we truly give data rights to every person, a new data world will come**. We can easily transfer and combine our personal data between different applications to realize our purpose. For example, if you allow, when you buy something in application A, you can immediately get the order information in application B . 

3. When the code specify everyone and every role's obligations and rights, and it cannot be changed in a easy way, a new conception will appear in our society "**Code is law**". With the gradual deepening of this concept, we will be able to completely reconstruct the social order. Such as commodity trading, contract signing, corporate affairs, charitable donations, legal affairs etc.. We can even establish a dispute resolution system just as court, which will greatly reduce the space for corruption and make the society more fair. On the furthermore, a poll system based on real identity can be utilized to resolve our traditional election issue.

**We don't need mercy and blessings from the monopoly internet companies, what we need to do is limit power and only allow limited power to operate transparently in the sun.**

These are some thoughts about CyberPrivacy, virtually there are too many affairs to finish this conception for me. 

If you are interested in this career, we can cooperate.

The core technical difficulty of this technical solution is that the trusted computing server cluster runs automatically and cannot be directly accessed by anyone. This solution requires the joint investment of many talented software engineers. At present, there is no such ability, but even if we cannot build a fully automated trusted server cluster, we can still create an application developer and operation and maintenance Isolation of vendors, forming a structure similar to application vendors and cloud server platform vendors, and then carrying out various management and mechanism checks and balances on cloud server platform vendors can also improve the privacy problems of the traditional Internet to a considerable extent.

Here are some preliminary design ideas:
Form a DAO community with the DAO protocol of the blockchain, use the proposal as the basis for application upgrades, use the immutability of IPFS files, and use RANCHER+K8S+JENKIS+HARBOR to create an automatically running trusted service cluster and create a preliminary plan.
When the title of a DAO community proposal begins with Software Update, it is a special function proposal. The special function proposal must use an IPFS address. The proposal must include specific application code, DOCKERFILE image package file, K8S yaml service deployment file, and pipeline template number. When the trusted service cluster detects a new proposal, it will use the pre-defined pipeline template of jenkis to fill in the sensitive information to form a pipeline file, automatically download the code and configuration file, push HARBOR according to the DOCKERFILE packaged image, and trigger K8S to deploy the file according to the YAML service Perform a system update.			
	 	 
  	
   
