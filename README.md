The module is given to us to teach us the fundamentals of creating a block chain

 Description

This program aims to help us understand the basics and also to give us a knowledge about 
block chain

 Getting Started
 To be able to execute this application, you may use Remix, an online Solidity IDE, which can be found at https://remix.ethereum.org/.

 Create a new file on the Remix website by clicking the "+" symbol in the left-hand sidebar. Save the file as Phoenixtoken.sol . Insert the following code into the file:

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

import "@openzeppelin/contracts/token/ERC20/ERC20.sol";

contract MyToken is ERC20 {
    constructor(string memory name, string memory symbol, uint256 initialSupply) ERC20(name, symbol) {
        _mint(msg.sender, initialSupply * (10 ** decimals()));
    }
}

Authors
Jorge ramiscal
@JRamiscal

Contributors names and contact info

Ramiscal Jorge
[@Jay2kkkk](https://twitter.com/Jay2kkkk)


## License

This project is licensed under the Ramiscal Jorge License - see the LICENSE.md file for details
