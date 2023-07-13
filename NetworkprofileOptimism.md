
Network name
Optimism
Token
ETH
RPC
[mainnet.optimism.io](https://mainnet.optimism.io)
Chain ID
10
Block explorer
[Optimistic Ethereum Explorer](https://optimistic.etherscan.io/)
Website
<https://www.mainnet.optimism.io/>

 


Also known as Optimistic Ethereum, Optimism is a **layer 2 (L2) rollup** helping to scale Ethereum. Let's unpack how it works.


L2s are a type of blockchain closely linked to a corresponding layer 1 (L1), which, in this case, is Ethereum. Transactions are handled on the L2 itself, the *execution layer*, whilst data about these transactions is 'rolled up' into a condensed form and posted on L1, demanding significantly less computation than if all of the transactions were to be conducted entirely on L1. Their structure allows users access to high-capacity, fast and low-cost alternative to Ethereum mainnet whilst retaining the same fundamental mechanisms and features. Critically, L2s also inherit Ethereum's security and reliability. Optimism's execution layer is called the **OVM**, or Optimism Virtual Machine.


Optimism uses a system similar to Proof-of-Stake, in which entities running nodes help secure the network. In this case, they are called **verifiers.** Additionally, Optimism requires a **sequencer**, responsible for collecting transactions from the L2, rolling them up, and posting them to L1 (Ethereum). Optimism itself currently runs the sole sequencer on the network. 


As its name not-so-subtly hints, Optimism belongs to the **optimistic rollup** category. Similarly to Arbitrum, one of the other major L2 platforms, Optimism's protocols assume that all transactions are valid. This approach means that the network does not have to compute every transaction, significantly reducing congestion; instead, computation is only performed when the validity of the block is challenged.


This occurs in a process referred to as a **fraud proof**, which is where verifiers come in: when the state information or 'commitment' (i.e. the bundle of rolled-up transactions) is posted to Ethereum, a one-week 'challenge window' begins. Verifiers check state information and are responsible for initiating a fraud proof to resolve the issue. If proven right, verifiers are rewarded and the proposed commitment is replaced with a new one. This '[How Optimism Works](https://community.optimism.io/docs/protocol/2-rollup-protocol/)' page is a good explainer if you want to find out more. 



#### Gas controls on Optimism


When using Optimism in MetaMask, you won't be able to manually adjust the amount of gas you pay using [advanced gas controls](https://support.metamask.io/hc/en-us/articles/360022895972), as you would on other networks. The feature is disabled instead. This is because it's not possible for users to specify gas limits when Optimism submits the transaction to Ethereum. You can read more [here](https://community.optimism.io/docs/developers/build/transaction-fees/#the-l1-data-fee).



 


**Using Optimism**
------------------




**How do I add Optimism to MetaMask?**

Adding a network is a straightforward process.


Optimism is already configured as a popular network in MetaMask, so adding it is straightforward. Click 'Add network' and head to the 'Add popular networks' area (instructions [here](https://support.metamask.io/hc/en-us/articles/360043227612)). From here, adding it to MetaMask should only take a few clicks or taps.


However, you can also manually input the network information above. For guidance, see [here](https://support.metamask.io/hc/en-us/articles/360043227612-How-to-add-a-custom-network-RPC). 





**Switching networks to Optimism in MetaMask**

When you add Optimism as a new network, you will automatically switch to it.


However, if you need to switch back, follow the guidance below:




Extension Mobile


Find where your current selected network is displayed at the top of your wallet page:


![how_to_change_network_-_extension.png](https://support.metamask.io/hc/article_attachments/4427180109467/how_to_change_network_-_extension.png)


Click it to bring up a list of previously connected networks that you can choose from. Find Optimism in the list and click it.




Locate the current network at the top of the screen:


![how_to_change_networks_-_mobile.jpeg](https://support.metamask.io/hc/article_attachments/4427195268251/how_to_change_networks_-_mobile.jpeg)


Tap it to view your previously connected networks, and then tap again on Optimism to switch to it.






**What token do I need?**
Optimism uses Ether (ETH) as its native token, which means you'll need it to pay for transactions.


**How do I bridge tokens onto Optimism?**

Optimism has an official bridge, called the Optimistic Ethereum Gateway, which can be accessed [here](https://gateway.optimism.io/welcome). Optimism have put together step-by-step guide to using the Gateway, available [here](https://help.optimism.io/hc/en-us/articles/4411894687387-Deposits-into-Optimism).


You can also bridge to and from Optimism using MetaMask Portfolio, [here](https://portfolio.metamask.io/bridge).


Another alternative is to use a direct on-ramp. These platforms allow you to purchase crypto with fiat currency (e.g. dollars, euros) and have the appropriate quantity of tokens deposited into your wallet. Again, MetaMask Portfolio's [Buy section](https://portfolio.metamask.io/buy/) covers this need too. 


Optimism has a list of supported on-ramps [here](https://help.optimism.io/hc/en-us/articles/4413642522139), and you can also buy ETH on Optimism directly in MetaMask Extension. Just make sure you have Optimism selected as your current network and hit the 'Buy' button. Read more [here](https://support.metamask.io/hc/en-us/articles/360058239311).





**Can I use my MetaMask address?**
Yes. When you add Optimism to MetaMask and use MetaMask on the network, you will be using your existing MetaMask public address.


**Can I send tokens directly to and from Optimism without bridging?**

No. Always use the bridging methods described above to get your tokens onto Optimism.





**What kinds of tokens can be used on Optimism?**

Optimism supports its native token, Ether (ETH), as well as ERC-20 tokens. **You can move any token from Ethereum to Optimism, provided it exists on both networks.**


However, an ERC-20 token on Ethereum is not interchangeable with an ERC-20 token on Optimism. **They must be bridged first**, and you must ensure the token is supported on Optimism before trying to bridge it over.


This is because ERC-20 tokens are essentially created by smart contracts. If a token exists on Ethereum it will have a corresponding token (contract) address. This same logic applies to Optimism: so if there is no contract address for a token on Optimism, you cannot move that token to the network.


To get around this potential barrier, it's best to stick to using the Optimism Gateway bridge, which will only allow you to transfer the token if it is supported on Optimism.


Since Optimism is a L2 rather than a conventional EVM-compatible network (such as Binance Chain or Avalanche C-Chain), you cannot move tokens from these networks onto Optimism, even if they have an ERC-20-equivalent standard (such as BEP-20). You must go via Ethereum mainnet.






**Useful resources**
--------------------


[Optimism docs: How Optimism works](https://community.optimism.io/docs/protocol/1-design-philosophy/) (detailed but accessible overview of the purpose of Optimism and its key features).


[Optimism help center](https://help.optimism.io/hc/en-us)


[Optimism bridge](https://gateway.optimism.io/welcome)


[Optimism ecosystem](https://www.optimism.io/apps/all)


 


**Relevant support articles**
-----------------------------


[User Guide: Custom networks and sidechains](https://support.metamask.io/hc/en-us/articles/4404424659995-User-Guide-Custom-networks-and-sidechains)

