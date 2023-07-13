
#### Note:


Any **imported** accounts will **not** be re-added when you restore your wallet using your Secret Recovery Phrase. [They need to be manually re-added](https://support.metamask.io/hc/en-us/articles/360015489331) in the same way you imported them originally.



**DO NOT share your Secret Recovery Phrase with anyone! These words can be used to steal all your accounts. You cannot edit or change your Secret Recovery Phrase.**


 


When you [restore a wallet](https://support.metamask.io/hc/en-us/articles/360015289612-How-to-restore-your-MetaMask-account-from-Seed-Phrase-Secret-Recovery-Phrase) using your Secret Recovery Phrase, MetaMask will automatically re-add any additional accounts you had previously [created](https://support.metamask.io/hc/en-us/articles/360015289452) — but only under certain conditions.


MetaMask will attempt to add your additional accounts where possible (assuming they were not [imported](https://support.metamask.io/hc/en-us/articles/360015289932)) by checking your previous accounts in ascending order (i.e. Account 2, then Account 3, etc.). **Accounts are automatically re-added if they have a non-zero ETH balance**. However, this process ends when MetaMask encounters an account with 0 ETH — so the first account with 0 ETH (and any beyond it) will *not* be added.


Bear in mind that **this process only checks for balances of ETH on Ethereum mainnet**, so other tokens or tokens on other networks will not result in your account being automatically re-added.


**For any which are not re-added automatically, you will have to add them back by "[creating](https://support.metamask.io/hc/en-us/articles/360015289452)" an account**. For example, if you have some tokens in Account 4, but Account 4 isn't automatically added because those tokens are not ETH on mainnet, all you need to do is manually add accounts (using the below steps) until you get to Account 4. Your Account 4 *before* the restore corresponds to Account 4 *after* the restore, regardless of any name you previously applied.


If you do need to use the "create" button to re-add accounts, don't worry about the account address being different. The addresses are cryptographically derived *deterministically* from your private key, which means they will always be the same. And since an Ethereum account, once created, exists permanently, you can just pick up where you left off. 


Please follow the steps below on how to restore your other accounts in the order they were originally created:




Extension Mobile


1. Click on the favicon on the top right corner of the MetaMask dropdown menu
2. Click “Create Account” to restore your MetaMask accounts in the order they were created
3. If the accounts were previously named, you can name them again in the step below, before clicking "**Create**"


![How_to_add_missing_accounts_after_restoring_with_Secret_Recovery_Phrase.gif](https://support.metamask.io/hc/article_attachments/9026739981083/How_to_add_missing_accounts_after_restoring_with_Secret_Recovery_Phrase.gif)




1. Tap the hamburger icon in the top left of the screen to bring up the menu. From here, tap on the drop-down arrow next to your account name:
2. Tap 'Create New Account':


![How_to_add_missing_accounts_after_restoring_with_Secret_Recovery_Phrase_Mobile.gif](https://support.metamask.io/hc/article_attachments/9027058464027/How_to_add_missing_accounts_after_restoring_with_Secret_Recovery_Phrase_Mobile.gif)




If you still do not see the addresses you were looking for, they were probably created with a different Secret Recovery Phrase, or you had an imported account that you still need to reimport using private keys or JSON. Please see [this article on how to import an account](https://support.metamask.io/hc/en-us/articles/360015489331-Importing-an-Account). 

