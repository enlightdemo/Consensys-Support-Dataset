Getting MetaMask Logs
---------------------


To help us deliver better support, we might ask you to provide your MetaMask state logs to further analyze the issues you face. These logs tell us:


* Your account addresses
* Your sent transaction history
* Your internal UI State


They don’t reveal:


* Your Private Keys
* Your Secret Recovery Phrase


Despite this, **DO NOT POST YOUR LOGS PUBLICLY.**


There are four types of logs that we might ask you to provide:




State logs Chrome popup logs Chrome background logs Chrome crash logs




**Extension**

If you've had an issue sending transactions or found a visual glitch in the rendering of MetaMask, we might ask you for a state log. To get them:


1. Open MetaMask and ensure it's unlocked
2. Click on your Account icon on the top right corner
3. Click on **Settings** and then select **Advanced**
4. Click on**Download State Logs**
5. Attach the file in your response on a support ticket


 


![How to download state logs](https://support.metamask.io/hc/article_attachments/9025714505115/How_to_download_state_logs.gif)





**Mobile**

1. In the MetaMask app, tap the Menu icon on the top left of the app
2. Tap on **Settings** (gear icon)
3. Select **Advanced**
4. Scroll down and tap on "**Download State Logs**"
5. Attach the file in your response on a support ticket


 


![How to download state logs mobile](https://support.metamask.io/hc/article_attachments/9025721591067/How_to_download_state_logs_mobile.gif)







To get logs from the popup:


1. Click the MetaMask fox in the top right of your browser.
2. Wait for the popup to open (or partially open if that's part of the bug).


![Chrome popup logs MetaMask](https://support.metamask.io/hc/article_attachments/9501232783387)


3. Right-click in the newly opened popup, and select **Inspect**.
4. Click **Console**at the top of the Inspector window.


![Chrome popup logs MetaMask](https://support.metamask.io/hc/article_attachments/9501232776603)


5. Look for any strange logs, especially red errors!
6. Share a screenshot with us.




To get logs from MetaMask's background process in Chrome:


1. Right-click the MetaMask fox in the top right of your browser.
2. Select **Manage Extensions**.


![Chrome background logs](https://support.metamask.io/hc/article_attachments/9501535348123)


3. Ensure "Developer Mode" is selected in the top right.
4. Scroll down to MetaMask, and click the "**Inspect views: background page**" link.


![Chrome background logs MetaMask](https://support.metamask.io/hc/article_attachments/9501580906779)


5. Click Console at the top of the Inspector window.
6. Look for any strange logs, especially red errors!


![Chrome background logs MetaMask](https://support.metamask.io/hc/article_attachments/9501232776603)


 


If you are using Windows OS, usually you could see the state logs in your **Downloads** folder.


![Chrome_background_logs3.1.png](https://support.metamask.io/hc/article_attachments/9502222681627)




If your bug involves crashing the whole browser, then having a browser console won't be much good! (It will be crashed).


In these cases, you'll need to start your browser in a way that it writes its logs to the disk, so you can open that log file after the browser crashes.


[This process is described here](https://www.chromium.org/for-testers/enable-logging), and we hope to write more specific steps on this in the future. If you have to go through this process, please do record the steps, so we can have more detailed instructions here for different platforms.



