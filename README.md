All the copypasta from @arsanus and @cyprian01

For Garlium connection issues, shutdown Garlium, press `Win+R > %appdata%/Garlium` and edit `recent_servers` with a text editor, and replace what you have with :
 
``[
    "clovemines.fun:50002:s",
    "172.93.54.31:50002:s",
    "ske.wtf:50004:s",
    "mhamburger.net:50002:s",
    "garlium.kenzierocks.me:50002:s",
    "electrum.garlicsoup.xyz:50002:s"
]``
Save, and start Garlium.
 
~~~~~~~~~~~~~~~~~~~~~~ If ^ doesn't work

-Under the tools option on the top bar select network

-In the new window select the server tab on the top

-Uncheck the box that says select server automatically

-In the server box input one of the servers below and the port in the adjescent box

-Click on close and wait a couple minutes for it to update

-If this doesnt work, repeat with a different serer

-If youve tried all the servers and its still not working recheck the box and restart the wallet client

Pools are at the bottom of this page:

~~~~~~~~~~~~~~~~~ For "Server is Lagging"
 
Press `Win + R` and enter %appdata%/Garlium and delete blockchain_headers
 
~~~~~~~~~~~~~~~~~~~~~~ For people who are asking why their address changed in their receive tab
 
Your old address is still there. Go to View -> Show addresses
The switching thing is for anonymity on the receive tab
Cause you can use the QR code to make invoices essentially
To turn it off go to Tools>prefrences>Transactions and tick off "Use Change Address"
 
~~~~~~~~~~~~~~~ For Garlium if people are missing their coins or some extra are sent in a transaction
 
Go to view > Show Coins
and view> Show Addresses
In addresses, on the top left go to "Receiving" and change it to Change

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ Absurdly high fees

Go to view > Show Coins
Move to the coins tab
Select as many as you can with ''Ctrl click''
Right click and select ''spend''
Select the amount you desire and send it to an address of your own so that it can be sent more effeciently


~~~~~~~~~~~~~~~~~ Stuck on 0 Blocks -cli Wallet


Stuck on Block 0? Here's a fix (Full wallet, not Garlium):
"garlicoind -connect=butterpool.com"
"garlicoin-cli getblockcount"

Keep checking until you are at the latest block..

"garlicoin-cli stop"

Wait for garlicoind to stop running, it may take a minute.

"garlicoind"
"garlicoin-cli getconnectioncount"

In a few minutes you should have a few connections.
You should be good now.
Love @Buss1000#6034 & @iBłackSunday#5025

