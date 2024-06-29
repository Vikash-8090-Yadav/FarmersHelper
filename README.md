# This project  is  made under Vortex 2024 

![Screenshot from 2024-04-29 22-34-18](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/2dcb4667-a18a-4a3b-bc5c-de9656b67d9e)


### Demo Video: https://youtu.be/Tqpfy42BtMc?si=a8T9l0bs4iS5lbB_

### Frontend Deploy Link: https://vortex2024-lk8d.vercel.app/


## Introduction 

We are solving a major problem ,where farmer can sell goods directly to the customer and make huge profits.Our website works where no middle men involved 
like distributers where farmers can feel free by selling their vegetables and goods in our marketplace.
This make easier to the farmers and customers which ease at a pace and simplifies major barriers like 
traditional flow to marketplace like farmers has to move to distributers ,logistics and then recieved to customers our 
solutions will drive to sell directly to the customers which can help farmers maximize their profits from the crops


## Contract Info 

Contract Address: 0xc466d29DC75A85173086055212677e9b416201B0

Verfied: https://sepolia.scrollscan.com/address/0xc466d29dc75a85173086055212677e9b416201b0#code



## Working Flow !!

- **Listing Products**: Farmers can easily list their products on our website.

- **Unique Digital Assets**: Each product is represented as a unique digital asset called an NFT (non-fungible token), ensuring it has its own digital identity that can't be replicated or divided.

- **Buy and Resell**: Anyone can buy these NFT products from the farmers, and once someone owns an NFT, they can resell it to others.

- **Case Registration**: If a farmer isn't satisfied with how a particular item is being treated or represented, they can register a case for it to maintain the integrity and reputation of their products.

- **Transparency**: The complete history of transactions and interactions with the smart contract is visible to anyone, providing full transparency into how products are bought, sold, and handled, which adds trust and accountability to the entire process.


## The Graph Integration


I created subgraph for this prroject and query  to make various dashboard like Marketplace , History of txn, Report a case, Purchase a  itwem etc

### Here's the Link of the subgraph-> https://thegraph.com/studio/subgraph/helperfarm/

![Screenshot from 2024-04-29 19-47-25](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/40fbf211-c607-4ffd-bd09-596b25277327)


###  The code for creating the Marketplace is in: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js

###  The code for seeing the History  of the txn can be found in: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/components/AnalysisReposrt.jsx
and the above component is being used here in this code https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/Analysis.jsx

###  The code for regestering any case for the farmers can be seen  here: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/components/Memos.jsx
amnd the above component is used here in this code -> https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/comment.jsx#L65




## Covalent INtegeration

I used covalent for  Taking out the Lates txn from the contract Address, Visualizing the NFT via the TokenID (Frtching the NFT txn and the holders) BUt the sad part is am geeting the error that  ``` Web3 provider connection is not setup```

### The code for the same can be found in this directory ->  https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js#L48

I used covalent to check the txn hash as well and the code for this can be found  here

### The code is : 

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/CreateNFT.js#L210

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js#L163

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/ResellCrops.jsx#L43

### Errors

![cov](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/f3d1265c-8a62-4824-bed1-7eb66284206f)

![cv](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/0623bf0f-9059-4d6e-ad5d-fcf29da5b165)

![dxsd](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/84c9cd1a-a537-4fff-8674-67b1ea6f9711)



## 🛠️Technologies we used

[![Powered by Filecoin](https://img.shields.io/badge/Powered_by-Filecoin-0174F2?logo=filecoin)](https://filecoin.io/)
[![Powered by Lighthouse](https://img.shields.io/badge/Powered_by-Lighthouse-ff69b4?logo=lighthouse)](https://lighthouse.filecoin.io/)
[![Built with React.js](https://img.shields.io/badge/Built_with-React.js-61DAFB?logo=react)](https://reactjs.org/)
[![Developed in Motoko](https://img.shields.io/badge/Developed_in-Motoko-2196F3?logo=dfinity)](https://sdk.dfinity.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-Tailwind_CSS-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Powered by Ethereum](https://img.shields.io/badge/Powered_by-Ethereum-3C3C3D?logo=ethereum)](https://ethereum.org/)

| Technology        | Description                                                | Official Website                                     |
|-------------------|------------------------------------------------------------|------------------------------------------------------|
| React.js          | JavaScript library for building user interfaces, often used for server-rendered or statically-generated applications | [React.js](https://reactjs.org/)                      |
| Tailwind CSS      | Utility-first CSS framework for building custom designs   | [Tailwind CSS](https://tailwindcss.com/)              |
| Solidity | Programming language used for smart contract development on the Ethereum blockchain | https://docs.soliditylang.org/ |
|LightHouse | Store file Secure, Reliable, & Lightning-Fast with Lighthouse. |https://www.lighthouse.storage/|
|ChainLLink | Chainlink is the decentralized computing platform powering the verifiable web| https://chain.link/|
|The Graph| The Graph is a decentralized protocol for indexing and querying blockchain data. The Graph makes it possible to query data that is difficult to query directly.|https://thegraph.com/ | 
| Covalentt |Data infrastructure for the blockchain industry |https://www.covalenthq.com/docs/ |
|Scroll| Scroll is a decentralized, global team of developers that is focusing on building a holistic approach to scaling Ethereum, prioritizing quality over speed. | https://scroll.io/ | 



## Demo Video



# This project  is  made under Vortex 2024 

![Screenshot from 2024-04-29 22-34-18](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/2dcb4667-a18a-4a3b-bc5c-de9656b67d9e)


### Demo Video: https://youtu.be/Tqpfy42BtMc?si=a8T9l0bs4iS5lbB_

### Frontend Deploy Link: https://vortex2024-lk8d.vercel.app/


## Introduction 

We are solving a major problem ,where farmer can sell goods directly to the customer and make huge profits.Our website works where no middle men involved 
like distributers where farmers can feel free by selling their vegetables and goods in our marketplace.
This make easier to the farmers and customers which ease at a pace and simplifies major barriers like 
traditional flow to marketplace like farmers has to move to distributers ,logistics and then recieved to customers our 
solutions will drive to sell directly to the customers which can help farmers maximize their profits from the crops


## Contract Info 

Contract Address: 0xc466d29DC75A85173086055212677e9b416201B0

Verfied: https://sepolia.scrollscan.com/address/0xc466d29dc75a85173086055212677e9b416201b0#code



## Working Flow !!

- **Listing Products**: Farmers can easily list their products on our website.

- **Unique Digital Assets**: Each product is represented as a unique digital asset called an NFT (non-fungible token), ensuring it has its own digital identity that can't be replicated or divided.

- **Buy and Resell**: Anyone can buy these NFT products from the farmers, and once someone owns an NFT, they can resell it to others.

- **Case Registration**: If a farmer isn't satisfied with how a particular item is being treated or represented, they can register a case for it to maintain the integrity and reputation of their products.

- **Transparency**: The complete history of transactions and interactions with the smart contract is visible to anyone, providing full transparency into how products are bought, sold, and handled, which adds trust and accountability to the entire process.


## The Graph Integration


I created subgraph for this prroject and query  to make various dashboard like Marketplace , History of txn, Report a case, Purchase a  itwem etc

### Here's the Link of the subgraph-> https://thegraph.com/studio/subgraph/helperfarm/

![Screenshot from 2024-04-29 19-47-25](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/40fbf211-c607-4ffd-bd09-596b25277327)


###  The code for creating the Marketplace is in: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js

###  The code for seeing the History  of the txn can be found in: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/components/AnalysisReposrt.jsx
and the above component is being used here in this code https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/Analysis.jsx

###  The code for regestering any case for the farmers can be seen  here: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/components/Memos.jsx
amnd the above component is used here in this code -> https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/comment.jsx#L65




## Covalent INtegeration

I used covalent for  Taking out the Lates txn from the contract Address, Visualizing the NFT via the TokenID (Frtching the NFT txn and the holders) BUt the sad part is am geeting the error that  ``` Web3 provider connection is not setup```

### The code for the same can be found in this directory ->  https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js#L48

I used covalent to check the txn hash as well and the code for this can be found  here

### The code is : 

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/CreateNFT.js#L210

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js#L163

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/ResellCrops.jsx#L43

### Errors

![cov](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/f3d1265c-8a62-4824-bed1-7eb66284206f)

![cv](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/0623bf0f-9059-4d6e-ad5d-fcf29da5b165)

![dxsd](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/84c9cd1a-a537-4fff-8674-67b1ea6f9711)



## 🛠️Technologies we used

[![Powered by Filecoin](https://img.shields.io/badge/Powered_by-Filecoin-0174F2?logo=filecoin)](https://filecoin.io/)
[![Powered by Lighthouse](https://img.shields.io/badge/Powered_by-Lighthouse-ff69b4?logo=lighthouse)](https://lighthouse.filecoin.io/)
[![Built with React.js](https://img.shields.io/badge/Built_with-React.js-61DAFB?logo=react)](https://reactjs.org/)
[![Developed in Motoko](https://img.shields.io/badge/Developed_in-Motoko-2196F3?logo=dfinity)](https://sdk.dfinity.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-Tailwind_CSS-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Powered by Ethereum](https://img.shields.io/badge/Powered_by-Ethereum-3C3C3D?logo=ethereum)](https://ethereum.org/)

| Technology        | Description                                                | Official Website                                     |
|-------------------|------------------------------------------------------------|------------------------------------------------------|
| React.js          | JavaScript library for building user interfaces, often used for server-rendered or statically-generated applications | [React.js](https://reactjs.org/)                      |
| Tailwind CSS      | Utility-first CSS framework for building custom designs   | [Tailwind CSS](https://tailwindcss.com/)              |
| Solidity | Programming language used for smart contract development on the Ethereum blockchain | https://docs.soliditylang.org/ |
|LightHouse | Store file Secure, Reliable, & Lightning-Fast with Lighthouse. |https://www.lighthouse.storage/|
|ChainLLink | Chainlink is the decentralized computing platform powering the verifiable web| https://chain.link/|
|The Graph| The Graph is a decentralized protocol for indexing and querying blockchain data. The Graph makes it possible to query data that is difficult to query directly.|https://thegraph.com/ | 
| Covalentt |Data infrastructure for the blockchain industry |https://www.covalenthq.com/docs/ |
|Scroll| Scroll is a decentralized, global team of developers that is focusing on building a holistic approach to scaling Ethereum, prioritizing quality over speed. | https://scroll.io/ | 



## Demo Video



# This project  is  made under Vortex 2024 

![Screenshot from 2024-04-29 22-34-18](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/2dcb4667-a18a-4a3b-bc5c-de9656b67d9e)


### Demo Video: https://youtu.be/Tqpfy42BtMc?si=a8T9l0bs4iS5lbB_

### Frontend Deploy Link: https://vortex2024-lk8d.vercel.app/


## Introduction 

We are solving a major problem ,where farmer can sell goods directly to the customer and make huge profits.Our website works where no middle men involved 
like distributers where farmers can feel free by selling their vegetables and goods in our marketplace.
This make easier to the farmers and customers which ease at a pace and simplifies major barriers like 
traditional flow to marketplace like farmers has to move to distributers ,logistics and then recieved to customers our 
solutions will drive to sell directly to the customers which can help farmers maximize their profits from the crops


## Contract Info 

Contract Address: 0xc466d29DC75A85173086055212677e9b416201B0

Verfied: https://sepolia.scrollscan.com/address/0xc466d29dc75a85173086055212677e9b416201b0#code



## Working Flow !!

- **Listing Products**: Farmers can easily list their products on our website.

- **Unique Digital Assets**: Each product is represented as a unique digital asset called an NFT (non-fungible token), ensuring it has its own digital identity that can't be replicated or divided.

- **Buy and Resell**: Anyone can buy these NFT products from the farmers, and once someone owns an NFT, they can resell it to others.

- **Case Registration**: If a farmer isn't satisfied with how a particular item is being treated or represented, they can register a case for it to maintain the integrity and reputation of their products.

- **Transparency**: The complete history of transactions and interactions with the smart contract is visible to anyone, providing full transparency into how products are bought, sold, and handled, which adds trust and accountability to the entire process.


## The Graph Integration


I created subgraph for this prroject and query  to make various dashboard like Marketplace , History of txn, Report a case, Purchase a  itwem etc

### Here's the Link of the subgraph-> https://thegraph.com/studio/subgraph/helperfarm/

![Screenshot from 2024-04-29 19-47-25](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/40fbf211-c607-4ffd-bd09-596b25277327)


###  The code for creating the Marketplace is in: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js

###  The code for seeing the History  of the txn can be found in: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/components/AnalysisReposrt.jsx
and the above component is being used here in this code https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/Analysis.jsx

###  The code for regestering any case for the farmers can be seen  here: https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/components/Memos.jsx
amnd the above component is used here in this code -> https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/comment.jsx#L65




## Covalent INtegeration

I used covalent for  Taking out the Lates txn from the contract Address, Visualizing the NFT via the TokenID (Frtching the NFT txn and the holders) BUt the sad part is am geeting the error that  ``` Web3 provider connection is not setup```

### The code for the same can be found in this directory ->  https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js#L48

I used covalent to check the txn hash as well and the code for this can be found  here

### The code is : 

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/CreateNFT.js#L210

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/marketplace.js#L163

https://github.com/Vikash-8090-Yadav/Vortex2024/blob/main/TheGraph/Frontend/src/pages/ResellCrops.jsx#L43

### Errors

![cov](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/f3d1265c-8a62-4824-bed1-7eb66284206f)

![cv](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/0623bf0f-9059-4d6e-ad5d-fcf29da5b165)

![dxsd](https://github.com/Vikash-8090-Yadav/Vortex2024/assets/85225156/84c9cd1a-a537-4fff-8674-67b1ea6f9711)



## 🛠️Technologies we used

[![Powered by Filecoin](https://img.shields.io/badge/Powered_by-Filecoin-0174F2?logo=filecoin)](https://filecoin.io/)
[![Powered by Lighthouse](https://img.shields.io/badge/Powered_by-Lighthouse-ff69b4?logo=lighthouse)](https://lighthouse.filecoin.io/)
[![Built with React.js](https://img.shields.io/badge/Built_with-React.js-61DAFB?logo=react)](https://reactjs.org/)
[![Developed in Motoko](https://img.shields.io/badge/Developed_in-Motoko-2196F3?logo=dfinity)](https://sdk.dfinity.org/)
[![Tailwind CSS](https://img.shields.io/badge/Styled_with-Tailwind_CSS-38B2AC?logo=tailwind-css)](https://tailwindcss.com/)
[![Powered by Ethereum](https://img.shields.io/badge/Powered_by-Ethereum-3C3C3D?logo=ethereum)](https://ethereum.org/)

| Technology        | Description                                                | Official Website                                     |
|-------------------|------------------------------------------------------------|------------------------------------------------------|
| React.js          | JavaScript library for building user interfaces, often used for server-rendered or statically-generated applications | [React.js](https://reactjs.org/)                      |
| Tailwind CSS      | Utility-first CSS framework for building custom designs   | [Tailwind CSS](https://tailwindcss.com/)              |
| Solidity | Programming language used for smart contract development on the Ethereum blockchain | https://docs.soliditylang.org/ |
|LightHouse | Store file Secure, Reliable, & Lightning-Fast with Lighthouse. |https://www.lighthouse.storage/|
|ChainLLink | Chainlink is the decentralized computing platform powering the verifiable web| https://chain.link/|
|The Graph| The Graph is a decentralized protocol for indexing and querying blockchain data. The Graph makes it possible to query data that is difficult to query directly.|https://thegraph.com/ | 
| Covalentt |Data infrastructure for the blockchain industry |https://www.covalenthq.com/docs/ |
|Scroll| Scroll is a decentralized, global team of developers that is focusing on building a holistic approach to scaling Ethereum, prioritizing quality over speed. | https://scroll.io/ | 


