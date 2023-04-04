# Mastering ERC20 Token in Solidity
The article concentrates on the [ERC20 standard,](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/) which is widely used to create digital tokens on the Ethereum network. It covers the deployment procedure utilizing [Remix EVM](https://remix.ethereum.org/)  (Ethereum Virtual Machine) and the integration of ERC20 tokens with the Solidity programming language.

Developers can use the information from this article to develop their [digital tokens](https://uk.practicallaw.thomsonreuters.com/w-024-0323?transitionType=Default&contextData=(sc.Default)&firstPage=true) for a variety of purposes, including fundraising, reward schemes, and in-app currency. They can also create decentralized applications ([dApps](https://ethereum.org/en/dapps/)) that use these tokens for transactions like payments and value exchange. Developers that want to take advantage of the Ethereum blockchain's capabilities and design cutting-edge solutions in the decentralized finance ([DeFi](https://ethereum.org/en/defi/)) field must be familiar with the ERC20 standard in Solidity.

# A Brief History of ERC20 Token

One of the most widely used token specifications on the Ethereum network is ERC20. Because of its simplicity and adaptability, it was swiftly embraced after being introduced by [Fabian Vogelsteller](https://www.linkedin.com/in/fabian-vogelsteller-46365042/?originalSubdomain=de) in November 2015. Smart contracts that establish a set of rules for tokens to abide by are what make ERC20 tokens fungible and simple to maintain.

The creation and management of tokens by businesses and people have been completely transformed by the standardization of ERC20 tokens. It was challenging for developers to guarantee compatibility with other tokens and wallets before ERC20 because each token had to be designed from the ground up. Developers can use ERC20 to build tokens that work with any wallet or exchange that accepts the standard.

Thousands of tokens on the [Ethereum network,](https://ethereum.org/en/) including some of the biggest and most valuable ones like Chainlink, Binance Coin, and Tether, have been built on the ERC20 standard since its debut. Several token standards, including [ERC721](https://docs.openzeppelin.com/contracts/3.x/erc721#:~:text=ERC721%20is%20a%20standard%20for,across%20a%20number%20of%20contracts.) (for non-fungible tokens) and [ERC1155](https://docs.openzeppelin.com/contracts/3.x/erc1155#:~:text=ERC1155%20is%20a%20novel%20token,their%20guides%20before%20moving%20on.), were also influenced by the standard (multi-fungible tokens). ERC20 has been crucial to the expansion and improvement of the Ethereum ecosystem.



# What is an ERC20 Token?

A digital asset built on the Ethereum blockchain under the [ERC20 standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/) is known as an ERC20 token. It is a standardized token that is fungible, which means that each token may be used to exchange one for another of equal value. Since its introduction in 2015 to address problems with smart contract tokens, the ERC20 standard has gained popularity within the [Ethereum ecosystem.](https://crypto.com/price/categories/ethereum-ecosystem)

On the Ethereum network, ERC20 tokens provide compatibility with a range of wallets, exchanges, and [decentralized apps.](https://ethereum.org/en/dapps/) They also offer improved security and dependability, as well as the capacity to be programmed to do particular tasks. They have made it possible to represent a variety of assets, including digital currencies, stock in a corporation, tangible goods, and reputation points, among other things.



# Benefits of Utilizing ERC20 Token

In the Ethereum blockchain, token creation is governed by the [ERC20 technical standard](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/). The following are some advantages of using [ERC20 tokens](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/):

- Reduced Costs: As ERC20 tokens do not require middlemen and enable quicker settlement times than traditional financial systems, they have lower transaction fees and costs.
- Decentralization: ERC20 tokens are decentralized since they are created on the [Ethereum blockchain,](https://ethereum.org/en/) which means they are not governed by a single entity. This makes them safer and more transparent.
- Programmability: ERC20 tokens are programmable, allowing for the customization of their actions to carry out particular tasks such as enabling automatic payments, voting processes, or access control.
- Security: Transactions for ERC20 tokens are stored on the unchangeable Ethereum blockchain, which makes them highly safe and resistant to hacking, fraud, and other nefarious activities.



# How Does ERC20 Token Work?

[Tokens](https://www.coinbase.com/learn/crypto-basics/what-is-a-token) must adhere to a set of guidelines outlined by ERC20 to be deemed ERC20-compliant. These guidelines include [computer languag](https://en.wikipedia.org/wiki/Computer_language#:~:text=A%20computer%20language%20is%20a,problem%20solution%20to%20a%20computer)e features that facilitate simple interoperability across various wallets, exchanges, and [decentralized apps.](https://www.techtarget.com/iotagenda/definition/blockchain-dApp#:~:text=A%20decentralized%20application%20(dApp)%20is,than%20on%20a%20single%20computer.) As a result, the [Ethereum ecosystem](https://ethereum.org/en/) makes it simple to trade and use tokens that adhere to the ERC20 standard.

The details of the agreement between the buyer and seller are immediately entered into code and implemented as smart contracts, which are self-executing contracts. The token's supply is held by these smart contracts, which also enforce the ERC20 standard's restrictions. An ERC20 token transaction is documented on the Ethereum blockchain and the token balance is updated when a user delivers an ERC20 token to another user. 


# Defining the ERC20 Token Standard and its Guidelines

The Ethereum blockchain uses a set of rules and specifications called the ERC20 token standard to produce tokens. ERC stands for "Ethereum Request for Comment," and the proposal identification given to this standard is 20. To produce an ERC20 token, you must adhere to the following rules:

- Token Name: This is what the token is called.
- [Symbol](https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#IERC20Metadata-symbol--): The token's identifying mark.
- [Decimal points:](https://ethereum.org/en/developers/docs/standards/tokens/erc-777/#decimals) The number of decimal points used to represent the token. One token, for instance, is equal to 1000000000000000000 (1018) units if the token has 18 decimal places.
- [TotalSupply](https://ethereum.org/en/developers/docs/standards/tokens/erc-4626/#totalsupply): The total quantity of tokens that will be issued is known as the total supply.
- [BalanceOf](https://ethereum.org/en/developers/docs/standards/tokens/erc-4626/#balanceof): This function returns the token's balance.
- [Transfer](https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#IERC20-transfer-address-uint256-): The ability to move tokens from one address to another via this function.
- [TransferFrom](https://docs.openzeppelin.com/contracts/4.x/api/token/erc721#IERC721-transferFrom-address-address-uint256-): This feature enables authorized addresses to send tokens on behalf of additional addresses.
- [Approve](https://docs.openzeppelin.com/contracts/4.x/api/token/erc721#IERC721-Approval-address-address-uint256-): This feature enables an address to permit another address to spend tokens on its behalf.
- [Allowance](https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#IERC20-allowance-address-address-): This function gives the number of tokens that have been authorized for a certain address to use on behalf of another address.

The token will be simple to integrate with other systems and wallets that accept ERC20 tokens if these standards are followed. Furthermore, it makes sure that the token may be exchanged on cryptocurrency exchanges that accept ERC20 tokens.




# Examples of ERC20 Tokens in Action

Below are just a few examples of [ERC20 tokens](https://ethereum.org/en/developers/docs/standards/tokens/erc-20/) in action. ERC20 tokens are widely used in the blockchain ecosystem and provide a standard way for creating and managing tokens on the Ethereum blockchain. There are numerous instances of ERC20 tokens being used in the blockchain ecosystem. These are a few instances:

- [USDT (Tether):](https://tether.to/) Tether is a stable coin that is tied to the US dollar, with each USDT token standing in for one dollar. Tether is an ERC20 token that is frequently used as a stablecoin for trading and money transfers on different cryptocurrency exchanges.
- LINK ([Chainlink](https://chain.link/)): Chainlink is a decentralized oracle network that links smart contracts to outside data sources. The LINK currency is used to reward node operators for providing correct data to the network.
- BAT (Basic Attention Token): The Brave browser ecosystem uses Basic Attention Token to compensate users for viewing adverts. On the platform, the token can be used to pay for premium products or services.
- OMG ([OmiseGO](https://www.abra.com/cryptocurrency/omise-go/)): OmiseGO is a blockchain-based payment system that enables quick, safe, and inexpensive payments. On the platform, [OMG tokens](https://www.kraken.com/learn/what-is-omisego-omg) are utilized as a medium of trade.
- REP (Augur): Augur is a decentralized platform for prediction markets that enables users to build and trade their own. The REP token is used on the platform to report the results of events and to reward truthful reporting.





# Why are ERC20 Tokens Popular?

Because of their portability and standardization, which make them simple to use and trade inside the Ethereum ecosystem, ERC20 tokens are well-liked. To maintain compatibility with other tokens and wallets, the standard specifies a set of guidelines that all [ERC20-compliant tokens](https://docs.openzeppelin.com/contracts/2.x/api/token/erc20) must adhere to. Because of how simple it is for developers to produce new tokens and for users to interact with them, ERC20 tokens are now widely used across a variety of industries.

The development of [decentralized applications](https://ethereum.org/en/dapps/) and [smart contracts](https://en.wikipedia.org/wiki/Smart_contract) on the [Ethereum network](https://ethereum.org/en/) has also been made possible by ERC20 tokens. [Decentralized financing](https://ethereum.org/en/defi/) (DeFi) and [initial coin offerings](https://www.investopedia.com/terms/i/initial-coin-offering-ico.asp#:~:text=Initial%20coin%20offerings%20(ICOs)%20are,have%20yielded%20returns%20for%20investors.) (ICOs) are two new use cases for digital currencies made possible by these dApps and smart contracts ([ICOs](https://www.investopedia.com/terms/i/initial-coin-offering-ico.asp)). ERC20 tokens have additionally been used to symbolize a range of assets, including virtual currencies, stock in a corporation, and tangible goods, among others. ERC20 tokens are well-liked and frequently used within the Ethereum ecosystem due to their standardization and interoperability.


# Advantages of Using ERC20 Tokens over other types of Tokens

Anybody interested in the [blockchain ecosystem](https://www.geeksforgeeks.org/what-is-blockchain-ecosystem/) must understand the benefits of using ERC20 tokens over other token types. The [Ethereum blockchain-based ERC20 tokens](https://www.investopedia.com/news/what-erc20-and-what-does-it-mean-ethereum/#:~:text=our%20editorial%20policies-,What%20Is%20ERC%2D20%3F,(NFTs)%20are%20not%20interchangeable.) are a popular form of token that is used for many different things, such as trade, user incentives, and fundraising. Compared to other token types, ERC20 tokens have several benefits, such as:

- Standardization: To ensure interoperability across various ERC20 tokens, the ERC20 standard offers a set of rules and principles. Because of this standardization, it is simple for programmers to design and incorporate fresh ERC20 tokens into already-existing platforms.
- Security: The Ethereum blockchain, which is a decentralized and unchangeable record, is the foundation upon which ERC20 tokens are based, making them secure. As a result, it is more challenging for hackers or other bad actors to undermine the integrity of the token.
- Reduced expenses: Because ERC20 tokens do not employ intermediaries and offer quicker settlement times than traditional financial systems, they have lower transaction fees and costs.
- Liquidity: ERC20 tokens have a high level of liquidity, which means that it is simple to buy or sell them on exchanges, giving investors more freedom to manage their portfolios.



# Use cases for ERC20 tokens

It is crucial to comprehend the use cases for ERC20 tokens since doing so sheds light on the potential of blockchain technology and how it can be applied to solve problems in the real world. The following are some applications for ERC20 tokens:

- Fundraising: ERC20 tokens can be utilized for funding via [security token offers](https://hedera.com/learning/tokens/what-is-a-security-token-offering-sto) (STOs) or [initial coin offerings](https://www.investopedia.com/terms/i/initial-coin-offering-ico.asp#:~:text=Initial%20coin%20offerings%20(ICOs)%20are,have%20yielded%20returns%20for%20investors.) (ICOs) (STOs). Tokens based on the ERC20 standard can be issued by corporations and startups to attract investors.
- Payment systems: In several ecosystems, ERC20 tokens can be used as a form of payment. Businesses, for instance, can design their own ERC20 tokens and implement them as a means of payment for products and services offered by their ecosystem.
- Reward systems: ERC20 tokens can be converted into points for loyalty programs, offering users rewards for utilizing a specific service or platform.
- Decentralized applications: Users can be encouraged to contribute to decentralized applications by using ERC20 tokens (dApps). By compensating users with ERC20 tokens, for instance, a dApp that offers file storage services can encourage users to donate their idle disk space.
- Gaming: In gaming ecosystems, ERC20 tokens can be used as in-game money or products. This gives players a new source of income by enabling them to exchange in-game goods or money for ERC20 tokens.



# Notable Examples of ERC20 Tokens and their Success Stories

Successful ERC20 tokens include several prominent examples, such as:

- [Tether](https://tether.to/en) (USDT) is a stablecoin whose value is tied to that of the US dollar. With a market valuation of more than $50 billion, it is one of the most popular ERC20 tokens. Since the cryptocurrency markets are highly volatile, Tether is utilized as a store of value and a method of value transfer between various exchanges.
- [Uniswap](https://uniswap.org/) (UNI): Uniswap is an automated market maker (AMM)-based decentralized exchange (DEX) that enables trading between ERC20 tokens. The UNI coin is employed to reward liquidity providers and serves as a governance token for voting on initiatives about the advancement of the Uniswap protocol.
- [Binance Coin](https://www.binance.com/en-NG/price/bnb) (BNB): The Binance cryptocurrency exchange developed the Binance Coin, an ERC20 token. The Binance exchange accepts it as payment for transaction costs, and it also offers users savings on trading costs.



# How to Create an ERC20 Token

This section will demonstrate how to utilize [Openzeppelin](https://www.openzeppelin.com/) to produce an [ERC20 Token,](https://docs.openzeppelin.com/contracts/4.x/erc20) as well as how to generate a Solidity token known as "MyToken.” However, if the name has already been used elsewhere, the unique name will have no impact. As a result, the contract address will be the unique criterion, not the token itself. Additionally, the ERC20 token symbols will have a short name of “MYT`, which is an abbreviation for MyToken. It is important to note that this name was generated independently.

Just paste the code below on remix to integrate. We will go over all you need to know about this code before we deploy.

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.18;
import "@openzeppelin/contracts/token/ERC20/ERC20.sol";
import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Capped.sol";
import "@openzeppelin/contracts/token/ERC20/extensions/ERC20Burnable.sol";

contract MyToken is ERC20Capped, ERC20Burnable {
    address payable public owner;
    uint256 public blockReward;

    constructor(uint256 cap, uint256 reward)
        ERC20("MyToken", "MYT")
        ERC20Capped(cap * (10**decimals()))
    {
        owner = payable(msg.sender);
        _mint(owner, 70000000 * (10**decimals()));
        blockReward = reward * (10**decimals()); // Setting block reward for first deploy
    }

    // Setting miner reward
    function _mintMinerRewad() internal {
        _mint(block.coinbase, blockReward);
    }

    // block.conbase validation for rewarding the minder; prevents miner from manipulating teh token
    function _beforeTokenTransfer(
        address from,
        address to,
        uint256 value
    ) internal virtual override {
        if (
            from != block.coinbase &&
            to != block.coinbase &&
            block.coinbase != address(0)
        ) {
            _mintMinerRewad();
        }
        super._beforeTokenTransfer(from, to, value);
    }

    function _mint(address account, uint256 amount)
        internal
        virtual
        override(ERC20Capped, ERC20)
    {
        require(
            ERC20.totalSupply() + amount <= cap(),
            "ERC20Capped: cap exceeded"
        );
        super._mint(account, amount);
    }

    //Destroying the contract
    function destroyContract() public onlyOwner {
        selfdestruct(owner);
    }

    // Set block rewards
    function setBlockReward(uint256 reward) public onlyOwner {
        blockReward = reward * (10**decimals());
    }

    //reusable modifier
    modifier onlyOwner() {
        require(msg.sender == owner, "Only the owner can call this function");
        _;
    }
}
```

The above code is a Solidity smart contract that establishes a custom ERC20 token titled "MyToken." It inherits three [OpenZeppelin ERC20-related contracts](https://docs.openzeppelin.com/contracts/4.x/erc20): [ERC20Capped](https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#ERC20Capped)`, `[ERC20Burnable](https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#ERC20Burnable)`, and `[ERC20](https://docs.openzeppelin.com/contracts/4.x/api/token/erc20#ERC20)`. These contracts set a maximum token supply, permit tokens to be burned, and provide basic functionality for an ERC20 token.

The contract includes two public state variables: `owner` and `blockReward`. The `owner` variable signifies the owner of the contract, while the `blockReward` variable denotes the amount of tokens awarded to the miner who mines the block containing a transfer.
The [contract's constructor function](https://docs.soliditylang.org/en/v0.8.17/contracts.html?highlight=constructor#constructors) receives two arguments: `cap` and `reward`. `cap` represents the maximum token supply for the token, while `reward` represents the reward given to miners who mine the block that includes a transfer.
The constructor assigns the `owner` variable to the `msg.sender`, mints 70,000,000 tokens to the owner, and sets the `blockReward` variable to the reward multiplied by 10 to the power of the decimals for the token.

Moreover, the contract has two internal functions: `_mintMinderRewad()` and `_mint()`. `_mintMinderRewad()` is triggered when a transfer is executed and mints the `blockReward` amount of tokens to the miner who mined the block including the transfer. `_mint()` overrides the `_mint()` function from `ERC20Capped` and `ERC20` and ensures that the total token supply does not exceed the cap.
The contract includes a [public function](https://docs.soliditylang.org/en/v0.8.17/control-structures.html?highlight=public%20function#external-function-calls) `destroyContract()` that enables the owner to terminate the contract and recover any remaining funds. It also includes a public function `setBlockReward()` that enables the owner to modify the `blockReward` value. Finally, the contract features a `modifier onlyOwner` that restricts access to certain functions to the contract's owner.




## Deploying the contract:

To deploy the [smart contract](https://ethereum.org/en/developers/docs/smart-contracts/#:~:text=A%20%22smart%20contract%22%20is%20simply,be%20the%20target%20of%20transactions.), we will continue to use [Remix](https://remix.ethereum.org/), the platform where we developed the smart contract. Remix offers a user-friendly deployment process that is simple and easy to use. In this section, we will provide a step-by-step guide to deploying the smart contract using Remix.
The deployment process is straightforward and can be initiated by following these steps:

**Step 1**: Click on the "compile" button located on the left-hand side of the smart contract. In the image provided below, the "auto-compile" and "compile" buttons are indicated within a red box. If the "auto-compile" function is enabled, there is no need to click on the "compile" button.


![](https://paper-attachments.dropboxusercontent.com/s_04D9A06549A669201DAE34C458EDFFCE4EA71BB6460C09D727180843C004F704_1680519151023_Screenshot+2023-04-03+at+11.38.13+AM.png)



**Step 2:** It is important to ensure that the contract to be deployed is the "MyToken" contract, which is the most important contract on the list, although there might be other [sub-contracts](https://ethereum.org/en/developers/docs/smart-contracts/#:~:text=A%20%22smart%20contract%22%20is%20simply,be%20the%20target%20of%20transactions.) listed as well. This is because "MyToken" contract is the one that inherits from another contract. Next, click on the second checkbox to reveal two fields where the cap and the miner's reward for the tokens can be added. Step 3 shows the result when the dropdown is clicked.


![](https://paper-attachments.dropboxusercontent.com/s_04D9A06549A669201DAE34C458EDFFCE4EA71BB6460C09D727180843C004F704_1680519206319_Screenshot+2023-04-03+at+11.48.31+AM.png)



Step 3: Once the dropdown mentioned in Step 2 is clicked, the deployment user interface becomes standardized and easy to understand. It is now possible to enter the cap and reward values for the [smart contract](https://ethereum.org/en/developers/docs/smart-contracts/#:~:text=A%20%22smart%20contract%22%20is%20simply,be%20the%20target%20of%20transactions.). For our smart contract, we will set the cap at 100 million and the miner's reward at 50. After inputting these values, click on the "deploy" button.



![](https://paper-attachments.dropboxusercontent.com/s_04D9A06549A669201DAE34C458EDFFCE4EA71BB6460C09D727180843C004F704_1680519165068_Screenshot+2023-04-03+at+11.39.19+AM.png)


**Step 4:** involves the creation of a new contract after deployment. The image below shows the newly created contract, which is indicated by the red box. Please click on it.

![](https://paper-attachments.dropboxusercontent.com/s_04D9A06549A669201DAE34C458EDFFCE4EA71BB6460C09D727180843C004F704_1680519175380_Screenshot+2023-04-03+at+11.40.25+AM.png)


**Step 5:** once you click on the newly created contract, you will be able to see the list of public functions and events that were previously discussed. When you click on the functions button, you will be able to view details such as the token name, token symbol, total supply, block reward, and cap values that were added during deployment. It's important to note that the [cap](https://docs.openzeppelin.com/contracts/2.x/api/token/erc20#ERC20Capped) value is initially set at 100 million with 18 zeros. This is a representation of [wei](https://www.investopedia.com/terms/w/wei.asp), which is the smallest unit.



![](https://paper-attachments.dropboxusercontent.com/s_04D9A06549A669201DAE34C458EDFFCE4EA71BB6460C09D727180843C004F704_1680521573783_Screenshot+2023-04-03+at+12.32.19+PM.png)




# Potential Dangers and Difficulties with ERC20 Tokens

Due to security issues and vulnerabilities, ERC20 tokens have the potential to cause substantial losses of money or data. It is challenging to fix security problems since the contract code cannot be altered once it has been deployed. The difficulty of tracking stolen assets from [smart contracts](https://ethereum.org/en/developers/docs/smart-contracts/#:~:text=A%20%22smart%20contract%22%20is%20simply,be%20the%20target%20of%20transactions.) makes it more difficult to secure ERC20 tokens. Developers must implement appropriate access control methods and create secure smart contracts in order to reduce these dangers.

Threats from backdoors are another potential issue with ERC20 coins. Attackers can utilize certain ERC20 functions to steal money or violate people's privacy by having them affect other accounts or the entire system without their knowledge or consent. Researchers have suggested detection techniques like Pied-Piper, which combines datalog analysis and directed fuzzing to find backdoor risks in [ERC20 contracts](https://docs.openzeppelin.com/contracts/4.x/erc20), as a solution to this problem. Ultimately, even though ERC20 tokens have numerous advantages, such as interoperability and programmability, developers and consumers must be aware of and take precautions against any potential risks and challenges.



# Typical Errors to Avoid when Developing ERC20 Tokens

There are several common mistakes that developers should avoid while creating an ERC20 token, including:

- Not adhering to the ERC20 standard: To be compatible with other tokens and wallets, ERC20 tokens must adhere to a set of rules and specifications. If the requirements are not met, the token may not work with wallets and other ERC20 tokens.
- Without taking adequate security precautions: ERC20 tokens are vulnerable to several security threats, including hacking and phishing attempts. To safeguard the token and its users, developers must put in place suitable security safeguards like multi-factor authentication and encryption.
- Not thoroughly testing the token: Not thoroughly testing the ERC20 token might result in bugs and errors that can cause serious issues, such as lost money or security breaches. To make sure the token works as planned and is safe, developers must run extensive testing.
- Failure to adequately explain the token will result in it not being clear to other developers and users how to use and comprehend the ERC20 token. When working with the token, improper documentation might lead to misunderstandings and mistakes.




# Conclusion

I hope you found the article interesting; we covered all you need to know before using the ERC20 token in this article. The advantages and applications of the ERC20 token were highlighted. There is a lot more information about the ERC20 token, and I think you learned a lot about it while reading this post. You may modify the ERC20 token code we used in this article to build a complicated token and to create a token for your client. You can [click here](https://docs.openzeppelin.com/contracts/4.x/erc20) to learn more about ERC20 tokens and how to generate new tokens.


