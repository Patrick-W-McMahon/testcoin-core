## this test coin objectives
 - build out a fully working core that can be packaged into a node.js module
 - build UX using NW.js or Electron with node.js
 - Create new way to mint coins and distribute them to meet the needs of a (town or nation)
 
 
## The Treasury System
The genesis block will hold the first sending wallet this will be the genesis wallet AKA the Treasury. The Treasury
will have the ability to mint coins using the mint coin action. This transaction will create new coins and deposit them
into the Treasury wallet.
## Deflationary systems
The Treasury is able to make global settings changes using the set global attribute transaction. The Treasury can
  - change the base transaction fee
  - change the burn fee/%
  - change the treasury fee
  
When a transaction is made (exception of the Treasury) a transaction fee is calculated along with burn fee and treasury fee.
The base transaction fee sets the bottom limit for any transaction. This amount is awarded to the miner of the block. The burn fee is an amount added to the transaction fee that is deleted. The coins are removed from circulation and cease to exist. The
Treasury fee acts much like the burn fee but rather than deleting the coins it sends them to the treasury wallet. The burn fee and treasery fee are used as deflationary systems to stabilize the currency and reduce volatility. For example if the supply of coins
is very high the treasury can increase the burn fee to reduce circulation. On the other hand if the supply is very low the Treasury can mint new coins into circulation. The method of minting and getting Treasury fees helps fund the project. This method will be used
sparingly to keep a stable price. In most cases the burn fee will be low if not zero and the treasury fee will be implemented. 
 
