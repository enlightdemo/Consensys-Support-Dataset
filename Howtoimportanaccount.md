*This article covers the process of adding accounts to your wallet which are not associated with your MetaMask wallet's Secret Recovery Phrase. If you're starting from a fresh install and want to access an existing MetaMask account, you should head to our article on [restoring your wallet using your Secret Recovery Phrase](https://support.metamask.io/hc/en-us/articles/360015289612). Please note that you can't import a second MetaMask Secret Recovery Phrase into your existing MetaMask wallet. It will overwrite the original and all associated data.*


**Quick links:**
----------------


* [Import using a private key](#h_01G01W07NV7Q94M7P1EBD5BYM4)
* [Import using a JSON](#h_01G01W0D3TGE72A7ZBV0FMSZX1)



#### Note:


**Imported accounts ARE NOT BACKED UP by your Secret Recovery Phrase**. Even though they will appear in your MetaMask wallet, you need to save the private keys used to import them the same way you save your Secret Recovery Phrase. **If you delete your wallet from your device, your imported accounts will be removed with it.** When/if you then [restore your wallet using your Secret Recovery Phrase](https://support.metamask.io/hc/en-us/articles/360015289612), you will need to re-add imported accounts with their private keys. 


Read more about imported accounts [here](https://support.metamask.io/hc/en-us/articles/360015289932).



For this process, you'll need the private key string or JSON file of the account you're looking to import. Refer to the documentation of that wallet provider to learn how to find it. 


**Importing using a private key**
---------------------------------




Extension Mobile


1. Click the circle icon at the top right corner of your MetaMask pop-up next to the network indicator.
2. Select “**Import Account**” on the dropdown menu:
3. You will be directed to the Import page. Paste your private key and click “**Import”**.


![How to import an account from private key](https://support.metamask.io/hc/article_attachments/9313845990683/How_to_import_an_account_from_private_key.gif)


 


You should be able to see the newly added account in the dropdown menu with an "Imported" tag next to the account.


![MetaMask extension imported wallet tag](https://support.metamask.io/hc/article_attachments/9313890833819/MetaMask_extension_iported_wallet_tag.png)




1. From your homepage, tap on the hamburger icon in the top left.
2. From here, tap on your account's name to bring up the account selector.
3. Hit 'Import an Account'.
4. On this screen, paste in the private key of the account you want to import, or scan a QR code if supported by the other wallet. Tap 'Import' to complete the process.


![How_to_import_an_account_from_private_key_mobile.gif](https://support.metamask.io/hc/article_attachments/9335360787995/How_to_import_an_account_from_private_key_mobile.gif)




**Importing using a JSON file**
-------------------------------


JSON (JavaScript Object Notation) is a file format commonly used to store and share data. For our purposes, it's used to encrypt the private key. 


You can use a JSON to import a wallet into MetaMask, but **only on Extension**. To do so, get the JSON file from your external wallet and follow the steps for Extension above until you get to the import page in step 3. From there:


1. On the Import page, expand the dropdown from “**Select Type**”.
2. Select “**JSON File**”.
3. Click “**Choose File**” and locate the file from your computer.
4. Enter the password that protects your JSON file (**not** your MetaMask password).
5. Click “**Import**".


![How to import an account from json file](https://support.metamask.io/hc/article_attachments/9313931325467/How_to_import_an_account_from_json_file.gif)


 


 

