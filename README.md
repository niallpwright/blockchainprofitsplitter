# blockchainprofitsplitter


##Profit splitter

First we set the three addresses that we are using to "payable" so that they may recieve funds. 
Second, we set up the constructor passing thru the 3 address payable parameters so we are able to input the three addresses.
We then set up a function for balance which returns a uint of the account balance. 
Next we set up a function for deposit, this function takes the msg.value and splits it into thirds then uses transfer to move the divided profits to each of the three adddresses.
Lastly we make sure that potential remainders are sent back to the sender to avoid any lost profits. 



![Maincode](https://user-images.githubusercontent.com/78838822/135163546-66e1f3c0-03ba-49fc-a951-ecfcf9551efe.PNG)
![fundedaccount](https://user-images.githubusercontent.com/78838822/135163592-9ac3b723-6317-47bc-9091-3e2e93618201.PNG)
![image](https://user-images.githubusercontent.com/78838822/135163839-d7af3c5a-5946-4bc1-a25e-9668e94ad690.png)
