***This article describes the wallet reset process, which is different from an account reset**. [Click here](https://support.metamask.io/hc/en-us/articles/360015488891) to read about resetting your account.*


 


**Contents:**


* [What is a wallet reset?](#h_01FXJ8NN1X1PJNG0AH3XKKJR93)
* [Why might I need to do it?](#h_01FXJ8NVJ9X7ZY96H1WBA0NCHX)
* [How do I do it?](#h_01FXJ8P07CG8H4A8A9GK0X0EKA)
* [Re-adding accounts after your wallet reset](#h_01FXJNJHE3W732SMMVS3ZSC145)


 


**What is a wallet reset?**
---------------------------


A wallet reset essentially returns your MetaMask Extension or Mobile app to the state it was in when you downloaded it: it **clears your Secret Recovery Phrase and your accounts from the software**. After you execute a reset, you'll need to re-enter your Secret Recovery Phrase to get access to your wallet again. (*This is why you should never reset your wallet unless you have your SRP to hand.)*


Currently, the **wallet reset function is** **only visible on Mobile** (on the lock screen, when you log out). However, **you can also reset your wallet on Extension**. See our [steps](#h_01FXJ8P07CG8H4A8A9GK0X0EKA) below for more detail. 


### What's the difference between resetting my wallet and resetting my account?


Although similar in name, these two options have different effects. 


**Reset wallet** will completely remove your wallet from the device, requiring you to restore with your SRP. '**Reset account**' will wipe your transaction history, leaving your wallet otherwise untouched. See our [account reset article](https://support.metamask.io/hc/en-us/articles/360015488891) for additional detail.



#### In summary:


**Reset account** will wipe your transaction history, but keep your wallet in MetaMask.


**Reset wallet** will completely remove your wallet from this MetaMask install.



Most users will have no need to reset their account, and we suggest only doing so when recommended to by a Support agent or when one of our articles suggests it.


 


**Why might I need to reset my wallet?**
----------------------------------------


The two main reasons are:


* You want to stop using your existing MetaMask wallet and create a new one, with a new Secret Recovery Phrase
* You want to [reset your password](https://support.metamask.io/hc/en-us/articles/360039616872), potentially because you've forgotten it.


Currently, the process is the same in both cases. 


 


**How do I reset my wallet?**
-----------------------------



#### Warning!


**Only follow these instructions if you have your Secret Recovery Phrase backed up and available.**


If you start the reset process without it, you may not be able to access your account ever again.


If you don't have it to hand, and are still signed in to MetaMask, learn how to reveal your phrase [here](https://support.metamask.io/hc/en-us/articles/360015290032). 


Please note that when resetting your wallet, **any accounts (addresses) that do not originate from your Secret Recovery Phrase will not be recovered afterwards**. These imported accounts, either hardware wallet or imported via private key, are **not included** under the Secret Recovery Phrase and will need to be [re-added manually](https://support.metamask.io/hc/en-us/articles/360015489271). Please be sure to verify that you have the private key details for any imported accounts before proceeding with the reset process. See [here](https://support.metamask.io/hc/en-us/articles/360015289932) for more on imported accounts.





Extension Mobile


1. To start with, you will need to uninstall MetaMask. Rather than doing this within the app itself, you'll need to remove it using your browser's extension settings. For example, on Chrome, you can just right click on the extension icon in the top right, and click 'Remove from Chrome'.


![How can I delete my MetaMask Wallet](https://support.metamask.io/hc/article_attachments/9220162293403/How_can_I_delete_my_MetaMask_Wallet.gif)


 


You can also go to chrome://extensions/ and click the 'Remove' button there:


![Remove MetaMask Extension](https://support.metamask.io/hc/article_attachments/9220262640155/Remove_MetaMask_Extension.png)


 


2. [Reinstall MetaMask](https://support.metamask.io/hc/en-us/articles/360015489531-Getting-started-with-MetaMask#:~:text=How%20to%20install%20MetaMask%3A).
3. When you reinstall the MetaMask Extension, you'll see a welcome message. Click through. Now you'll be presented with the option to either import a wallet or create a new one. Since we're resetting in this case, we just want to import.


![How to restore wallet.png](https://support.metamask.io/hc/article_attachments/9220504019483/How_to_restore_wallet_1.png)


 


4. Enter your Secret Recovery Phrase (all lower case) and your preferred password:


![How to restore wallet.png](https://support.metamask.io/hc/article_attachments/9220537423899/How_to_restore_wallet_2.png)


 


If you entered your Secret Recovery Phrase correctly, the process is now complete, and you should be able to access your wallet in Extension as before.




1. Lock your account by tapping the hamburger icon in the top left, and selecting the lock option at the bottom.
2. On the lock screen, tap 'Reset wallet':
3. A warning message will appear, reminding you that you should not proceed unless you have your Secret Recovery Phrase. Tap through and then type 'delete' in the field in the subsequent screen to confirm your intention.


![How to reset your account mobile](https://support.metamask.io/hc/article_attachments/9186314346523/How_to_reset_your_account_mobile.gif)


 


4. Now you'll be redirected to a screen that looks like this. Tap 'Import using Secret Recovery Phrase'.


![Reset_Wallet_Mobile_1.png](https://support.metamask.io/hc/article_attachments/9186483545883/Reset_Wallet_Mobile_1.png)


 


5. Input your Secret Recovery Phrase -- all in lower case, with spaces between words. You'll also need to choose a password.


![Reset Wallet Mobile](https://support.metamask.io/hc/article_attachments/9186523757723/Reset_Wallet_Mobile_2.png)


Once you input your Secret Recovery Phrase correctly, you're finished!




 


**Re-adding accounts after you reset your wallet**
--------------------------------------------------


Now that your wallet has been reset, let's talk about **re-adding accounts**:


* Any imported accounts (such as hardware wallets) will not automatically reappear -- you need to re-add them manually.
* Any additional accounts you originally had on that MetaMask instance will not necessarily be restored alongside the auto-generated original (i.e. Account 1, before renaming). MetaMask will proceed through your previous accounts in ascending order until it hits one with 0 ETH, in which case it will stop, and any beyond that will not be added. However, you can easily get them back by  [re-adding accounts](https://support.metamask.io/hc/en-us/articles/360015489271-How-to-add-missing-accounts-after-restoring-with-Secret-Recovery-Phrase) until you reach the one you're looking for.
