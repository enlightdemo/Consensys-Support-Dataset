**The information in this article is applicable to Ethereum mainnet *and* other networks, such as BSC and Polygon.**


If the gas price has been set too low when attempting to carry out a transaction, this sort of error can occur:


"Transaction <*your transaction # here*> failed! Error: [ethjs-query] while formatting outputs from RPC '{"value": {"code":-32000,"message":"transaction underpriced"}}'"


This can happen when attempting to make a swap via a DEX (decentralized exchange) or simply when sending tokens to an address.


In order to successfully complete the transaction, you should issue a new transaction whilst**raising the amount of gas you pay.**However, before you do so, check on the relevant block explorer (e.g. [Etherscan](https://etherscan.io/), [BscScan](https://bscscan.com/), [Polygonscan](https://polygonscan.com/) etc.) to make sure you are not generating an increasingly longer queue of pending transactions. 


To do this:




Extension Mobile


1. Make sure you have '**Advanced gas controls**' turned on. This can be found in Settings > Advanced. 


![Screenshot_2022-02-08_at_08.26.53.png](https://support.metamask.io/hc/article_attachments/4418165732379/Screenshot_2022-02-08_at_08.26.53.png)
2. Start a new transaction, using the same recipient details and token amount as the original (assuming you want them to remain the same).


When sending a transaction, hit 'Edit':


![Screenshot_2022-02-11_at_16.27.21.png](https://support.metamask.io/hc/article_attachments/4419352862235/Screenshot_2022-02-11_at_16.27.21.png)
3. You'll now be presented with a set of fields you can adjust, resembling the below:


![Screenshot_2022-02-11_at_16.27.54.png](https://support.metamask.io/hc/article_attachments/4419362710043/Screenshot_2022-02-11_at_16.27.54.png)


Here you should:


	* **Input a comparable or slightly higher gas limit** than you did for the transaction that failed
	* Raise the **max priority fee** at least **10% higher (in gwei) than the gas fee of the failed transaction**
	* Set your **max fee** at least **30% higher** than that of the failed transaction.


If you are trying to cancel that pending transaction altogether, you need to send 0 ETH (or equivalent currency) to your own address with the same nonce as the pending transaction. See our [article on cancelling transactions](https://support.metamask.io/hc/en-us/articles/360015489251-How-to-speed-up-or-cancel-a-pending-transaction) for more guidance.




1. Initiate the new transaction by hitting 'Send' from the homepage of the relevant account.
2. Input the details of your transaction, such as the recipient address and the quantity of tokens you want to send. These details should be the same as the original (failed) transaction, assuming you still want to send the same amount to the same address. Tap 'Next'. You should now see the screen below. Tap on the highlighted gas fee number:


![transaction_screen.PNG](https://support.metamask.io/hc/article_attachments/5488079525019/transaction_screen.PNG)
3. This will bring up an additional menu where you'll be presented with the options to set your gas fee low, medium, or high. Ignore these and tap 'Advanced options' instead.


![standard_settings.PNG](https://support.metamask.io/hc/article_attachments/5488052652827/standard_settings.PNG)
4. You can now customize your gas settings with more precision to ensure your new transaction goes through.


![advanced_settings.PNG](https://support.metamask.io/hc/article_attachments/5488068228635/advanced_settings.PNG)


Here you should:


	* **Input a comparable or slightly higher gas limit** than you did for the transaction that failed
	* Raise the **max priority fee** at least **10% higher (in gwei) than the gas fee of the failed transaction**
	* Set your **max fee** at least **30% higher** than that of the failed transaction.


If you are trying to cancel that pending transaction altogether, you need to send 0 ETH (or equivalent currency) to your own address with the same nonce as the pending transaction. See our [article on cancelling transactions](https://support.metamask.io/hc/en-us/articles/360015489251) for more guidance.




For more information on gas, see our [user guide](https://support.metamask.io/hc/en-us/articles/4404600179227-User-Guide-Gas).

