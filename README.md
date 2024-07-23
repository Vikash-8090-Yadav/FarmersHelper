![Screenshot from 2024-06-30 16-58-46](https://github.com/Vikash-8090-Yadav/FarmersHelper/assets/85225156/8b3065a0-cd78-43a4-895a-33d20a4b8b54)






## Farcater Frame:  https://warpcast.com/~/developers/frames?url=https%3A%2F%2Ffarmers-helper-cr7y.vercel.app%2Fapi




## Contract Info 

Contract Address: 0xc466d29DC75A85173086055212677e9b416201B0

Verfied: https://sepolia.scrollscan.com/address/0xc466d29dc75a85173086055212677e9b416201b0#code

## SOurce Code for SubGraph: https://github.com/Vikash-8090-Yadav/FarmersHelper/tree/main/Frontend/helperfarm

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


