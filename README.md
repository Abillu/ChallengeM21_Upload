
# KaseiCoin Token Crowdsale

## Overview

This a smart contract for  a fungible token that is ERC-20 compliant and that will be minted by using a `Crowdsale` contract from the OpenZeppelin Solidity library.

The `Crowdsale` contract created has capability to manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KSC, or KaseiCoin tokens. The  contract mints the tokens automatically and distribute them to buyers in one transaction.

### Approach and Methodology

1. Created the KaseiCoin Token Contract

2. Created the KaseiCoin Crowdsale Contract

3. Created the KaseiCoin Deployer Contract

4. Deployed the Crowdsale to a Local Blockchain

5. Extend the Crowdsale Contract by Using OpenZeppelin to allow the following functionality:

 - cap the total amount of ether that may be raised during your crowdsale.

 - set a time limit for your crowdsale by adding an opening time and a closing time.

 - set a goal amount of ether to raise. If the goal is not reached, it is common practice to refund your investors. This contract adds this capability to a crowdsale


#### Results 

 After deploying  the crowdsale to a local blockchain with Remix, MetaMask  the following were the ressults:

1. Testing  the functionality of the crowdsale by using test accounts to buy new tokens and then checking the balances associated with those accountsin Ganache, Remix and MeatMask.

![crowdsaleDeploymentGanache](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/afbb1126-9867-45b5-a5ba-64384a293800)

![crowdsaleDeploymentMetaMask](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/d09d0a57-2cfb-498d-9954-46a148bbae2d)

![crowdsaleDeploymentRemix](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/b79fc03b-5e39-4b3d-ade6-05d9483d6e28)

![Kasei  sol compiled](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/3ed55983-b8a6-490e-8e72-9a2ac0ecb3b0)

![KaseiCoinCrowdsale sol  sol compiled](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/0abc096d-fd0f-42cc-8389-ca614e0f1e4a)

![purchaseTokenGanache](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/3f7f1ed6-923c-429e-9f19-d191296b3107)

![purchaseTokenRemix](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/de9683e4-84ce-4750-bfcd-82680d90906e)



2. The amount of wei that has been raised in the crowdsale contract.
![purchaseTokenWeiraised](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/7c855611-57a7-4869-8016-4052bc21126e)


3. And finally the results after testing the enhanceed features of the `Crowdsale` contract are exibitted below:

   
![enhancedCrowdsaleRemix](https://github.com/Abillu/ChallengeM21_Upload/assets/126644613/37ac0da2-bae2-4cea-b24b-e1891798c49a)
