//SPDX-License-Ifentifier: MIT pragma solidity ^0.8.30 ; import "@openzeppelin/contracts/token/ERC20/ERC20.sol"; import "@openzeppelin/contracts/access/Ownable.sol"; contract MillardBoswellToken is ERC20 ("Millard Boswell Token","MBT"),Ownable { constructor (address initialOwner )Ownable(initialOwner ){} function mintFifty() public onlyOwner { _mint(msg.sender,50* 10**18); } }



<!---
BeadtMODE/BeadtMODE is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
