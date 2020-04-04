# SwiftCash - Web Wallet

SWIFT's web wallet is an open-source wallet written in html, css and javascript. All signatures are handled on the client-side and private keys never leave the browser.
To secure the account of users who login with an email and password rather than a private key, the wallet hashes the email and passsword 144,000 times, and then uses the final hash to create an address and private key in the end.
The wallet also enforces very strong passwords using a password strength meter to further secure the accounts against brute-force attacks.

# Hosting
This web wallet is hosted on github, and can be verified and accessed via the following links:

* https://swiftcashproject.github.io/webwallet/
* https://wallet.swiftcash.cc/

To avoid becoming a victim of phishing attacks, make sure you always double check the domain in your browser's address bar. You can also download the wallet and run it locally. But you're still going to need Internet in order to transact with the blockchain.

# BTC, LTC and DOGE Support
Bitcoin, Litecoin and Dogecoin transactions are created and signed locally and then sent to their own networks using api(s) provided by https://blockchair.com/ - https://www.blockcypher.com is also used for following up on transaction details.

# Login With Your Private Key(s)
You can login with a SwiftCash, Bitcoin, Litecoin or Dogecoin private key. If you login with a SwiftCash private key, the wallet will generate a Bitcoin, Litecoin and Dogecoin address using your SwiftCash private key. If you login with a Bitcoin private key, the wallet will generate a SwiftCash, Litecoin and Dogecoin address using your Bitcoin private key. And so will be the case if you login with a Litecoin or Dogecoin private key. It is however highly recommended to use email and password to login if you intend to stash all your cryptos in the same wallet per se, and only use the login with private key feature to spend your paper or brain wallets.

# Transaction Fees
The wallet enforces a minimum of `0.002 SWIFT`, `0.0001 BTC`, `0.001 LTC` and `1 DOGE` transaction fees and allows users to increase this fee. To help avoid situations in which ridiculously high fees are paid by accident, the wallet enforces a maximum of `0.2 SWIFT`, `0.01 BTC`, `0.1 LTC` and `100 DOGE` transaction fees.

# Change Addresses
By default, all changes are sent back to the sender's address. To specify a custom change address, click on the vial icon. You need to specify a custom change address everytime you login or switch between different coins, to override the default behavior.

# Lottery and HODLx
To enter into SwiftCash DeLotts(Decentralized Lotteries), you can burn your coins using the web wallet by sending them to Lottery. To lock your coins for in the SwiftCash blockchain for HODL deposits and rewards, you can send your coins to HODLx where x can be an integer between 1 and 12 representing x-month. Best rate is given to HODL12 deposits and is shown above the wallet next to the current jackpot.

# Notes
* To copy your address, click on the copy icon next to your address.
* To refresh your balance, click on the bolt icon next to your balance.
* To view your balance in US dollars, click on your balance.
* To specify a custom change address, click on the vial icon.
* To change/adjust the transaction fee, click on the wrench icon.
* To copy your private key, click on the key icon.
* To donate, click on the donate icon.

# License
Copyright (C) 2018-2020 SwiftCash Developers <br />
This software is provided as is and with no warranty under the MIT license.

# Donation Addresses
* SWIFT: `SXucSXaV5HURNyJUWnPrVFHTdRzoVff6gU`
* BTC: `1E9xPAPifPFHmVTX1pDdPLcsgub71zdpDY`
* LTC: `LYNueNhYk3VM2J9gBxCvfMgdu7xP9WdLVL`
* DOGE: `DJJ3vRLMxo9aJVe7kQDBw6nUa3KQL8zzfv`

# Support
For support, join http://discord.swiftcash.cc

# Whitepaper
To find out more about SwiftCash, consider reading our whitepaper!
https://swiftcash.cc/assets/whitepaper.pdf
