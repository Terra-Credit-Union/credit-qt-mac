Getting started for macOS

Open your wallet, and make sure you are connected to another wallet. 

You are connected when you see the icon Wallet Connections in the lower right corner of your wallet.

Close your wallet and create the file credit.conf in the folder "$HOME/Library/Application Support/Credit/".

Paste the following text into credit.conf and save the file.

rpcuser=your_username
rpcpassword=your_password
rpcallowip=127.0.0.1
rpcport=43796
listen=1
server=1
addnode=206.189.195.40

Open your wallet.

Download the latest version of cpuminer for macOS from here and extract the zip file.

Click the Finder icon in your dock. 
Click Go.
Click Utilities.
Double-click Terminal.

Go to the directory where you extracted cpuminer.

E.G. cd Downloads

Execute the following command in Terminal to start mining your first coins.

minerd --url=http://127.0.0.1:43796 --userpass=yourusername:your_password
