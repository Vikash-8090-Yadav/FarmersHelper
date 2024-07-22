![Screenshot from 2024-06-30 16-58-46](https://github.com/Vikash-8090-Yadav/FarmersHelper/assets/85225156/8b3065a0-cd78-43a4-895a-33d20a4b8b54)






## Farcater Frame:  https://warpcast.com/~/developers/frames?url=https%3A%2F%2Ffarmers-helper-cr7y.vercel.app%2Fapi



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


### Graph Query used in Frames 

```
 const query = `
  {
    donations(first: 10, orderBy: id) {
      from
      id
      message
      name
      timestamp
    }
  }
  `;
```

The above query can be found here: https://github.com/Vikash-8090-Yadav/FarmersHelper/blob/main/Frames/api/index.tsx#L100C2-L110C5


### Graph Query used in Frontend (Dapp)

You can  find the query  Here: 

For marketplace Query : https://github.com/Vikash-8090-Yadav/FarmersHelper/blob/main/Frontend/src/pages/marketplace.js#L33

For  History Analysis Query : https://github.com/Vikash-8090-Yadav/FarmersHelper/blob/main/Frontend/src/components/AnalysisReposrt.jsx#L15




I created subgraph for this prroject and query  to make various dashboard like Marketplace , History of txn, Report a case, Purchase a  itwem etc

### Here's the Link of the subgraph-> https://thegraph.com/studio/subgraph/helperfarm/

![326470897-40fbf211-c607-4ffd-bd09-596b25277327](https://github.com/Vikash-8090-Yadav/FarmersHelper/assets/85225156/3b017506-74b9-4cd6-a3a3-c883e450286d)


