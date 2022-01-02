## Smart Contract Lottery:

Made a smart contract lottery.

### what is smart contract?
smart contract is a set of instructions that can be executed without intervention from third parties. 
- Another advatage of the smart contracts is that It can be used to store and manage assets.   

# Smart Contract Lottery:

## step 1: 
1. User can enter lottery with ETH based on a USD fee
2. An admin will choose when the lottery is over
3. The lottery will select a random winner

### functions used in the contract:
```cpp
    function enter() public payable {}
    function getEntranceFee() public {}
    function startLottery() public {}
    function endLottery() public {}
```
## step 2:  

### Is this really decentralized?
- It is because single person (admin) chooses when the lottery is over.
### How could we make it decentralised?
  - we can make the lottery open and closed by using time parameters
