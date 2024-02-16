* `bitcoin` -> currency
* `Bitcoin` -> system
- not individual digital coins but  implied in transactions that transfer value from spender to receiver.
- The difficulty of the computational task that miners must perform is adjusted dynamically so that, on average, someone succeeds every 10 minutes regardless of how many miners (and how much processing) are competing at any moment. 
- Total coins -> 21 million -> half every four years
- `Liquidity` ->  An asset is considered liquid if it can be bought or sold in the market quickly and with minimal impact on its price. 
- `Bitcoin` was first described in 2008 ->  paper  "Bitcoin: A Peer-to-Peer Electronic Cash System,
- ### `Byzantine Generals' Problem` -> 
   - It consists of trying to get multiple participants without a leader to agree on a course of action by exchanging information over an unreliable and potentially compromised network
   -  concept of proof of work to achieve consensus without a central trusted authority,
- ### Types of Bitcoin wallets-<
 * **Mobile Wallet(you control the keys)** 
    - Running on smart-phone OS
    - To avoid downloading and storing large amounts of data, most mobile wallets retrieve information from remote servers, reducing your privacy by disclosing to third parties information about your Bitcoin addresses and balances.

 * **Web Wallet(you don't control the keys)**-> 
    - accessed through a web browser and store the user’s wallet on a server owned by a third party.
    - 3rd party take control of the Bitcoin keys from users in exchange for ease-of-use.


* `Full Node` -> 
   - program that validates the entire history of Bitcoin transactions.
   - It offers complete autonomy (does'nt have to depend on external ones for transctions operations) to its users.
* `Lightweight client`-> 
   -  `simplified-payment-verification (SPV) client`, connects to a full node or other remote server for receiving and sending Bitcoin transaction information, but stores the user wallet locally, partially validates the transactions it receives, and independently creates outgoing transactions.
   -  more autonomy compared to third-party API clients, they still rely on external sources for some functions.
  
* `Third-party API client`->
   - one that interacts with Bitcoin through a third-party system of APIs rather than by connecting to the Bitcoin network directly. 
   - The wallet may be stored by the user or by third-party servers, but the client trusts the remote server to provide it with accurate information and protect its privacy  

- ### Key management software (based on control):
   -  wallets, where you control the keys(`noncustodial wallet`).
   -  funds and accounts with custodians where some third-party controls the keys.(`custodial wallet`)
-  

- ### Recovery Code(mnemonic/seed phrase) -> 
  - to get private keys
  - +--------------------------------------------------------+
|                   Wallet Recovery                     |
+--------------------------------------------------------+
                              |
                              v
+--------------------------------------------------------+
|      Loss of Wallet (e.g., due to device failure)      |
+--------------------------------------------------------+
                              |
                              v
+--------------------------------------------------------+
|       Download New Wallet Software & Enter             |
|               Recovery Code                             |
+--------------------------------------------------------+
                              |
                              v
+--------------------------------------------------------+
|        Rebuild Wallet Database Using Recovery Code      |
|                   (Transaction History)                 |
+--------------------------------------------------------+
                              |
                              v
+--------------------------------------------------------+
|    Missing Metadata (Labels, etc.) Not Automatically   |
|                  Restored-> 
   many payments -> offchain but recovery code -> rely on onchain data                           |
+--------------------------------------------------------+
                              |   
                              v
+--------------------------------------------------------+
|         Importance of Additional Backup Feature         |
|                   (for Metadata)                        |
+--------------------------------------------------------+
                              |
                              v
+--------------------------------------------------------+
|              Frequent Backups Required                  |
|               (especially for Offchain Payments)        |
+--------------------------------------------------------+
                              |
                              v
+--------------------------------------------------------+
|      Re-Verification of Recovery Code for Security      |
+--------------------------------------------------------+
                              |
                              v
+--------------------------------------------------------+
|       Beware of Scams - Phishing Risk Awareness        |
+--------------------------------------------------------+



- **Invoice** -> payment request
- **Maintain Privacy while transcations** -> Though address -> helps to conceal identity -> but anyone can track the trascation history/activity -> if we use single address always -> HD wallet creates new address for each transcation -> privacy
- ### Price of Bitcoin->
   - floating exchange rate->
      -  the value of Bitcoin changes based on how much people want to buy or sell it. This means its price goes up and down all the time.
      -   Imagine you're at a busy market where people are trading Bitcoin for US dollars. The price you see for Bitcoin in dollars is determined by the most recent trades happening there.
      -   We take average ->(price + voulume of trade in that region) to get overall value of it
      -   #### Sites-> 
           - **Bitcoin Average**
           - **CoinCap**
           - **Chicago Mercantile Exchange Bitcoin Reference Rate**
 - ### Confirmations->
    - after initiating transcations -> show `Unconfirmed` -> sent to network but not recorded in blockchain
    - transcation -> included in block-> added to blockchain
    -   +---------------------------------------+
  |          Request Bitcoin Payment      |
  |                                       |
  |  - Recipient opens their mobile       |
  |    wallet and selects the option to   |
  |    receive Bitcoin.                    |
  |  - Recipient specifies the amount     |
  |    they wish to receive, if needed.   |
  +---------------------------------------+
                    |
                    v
  +---------------------------------------+
  |     Mobile Wallet Generates QR Code   |
  |                                       |
  |  - Mobile wallet generates a unique   |
  |    Bitcoin address associated with    |
  |    the recipient's wallet.            |
  |  - Wallet also generates a QR code    |
  |    containing the Bitcoin address.    |
  +---------------------------------------+
                    |
                    v
  +---------------------------------------+
  |          Display QR Code to Sender    |
  |                                       |
  |  - Recipient displays the generated   |
  |    QR code on their device screen.    |
  |  -QR code === invoice                 |
  |  - Sender visually scans the QR code  |
  |    using their own wallet app.        |
  +---------------------------------------+
                    |
                    v
  +---------------------------------------+
  |        Sender Scans QR Code           |
  |                                       |
  |  - Sender opens their mobile wallet   |
  |    and selects the option to send     |
  |    Bitcoin.                            |
  |  - Sender scans the QR code displayed |
  |    by the recipient's device using    |
  |    their own wallet app.              |
  +---------------------------------------+
                    |
                    v
  +---------------------------------------+
  |   Sender Sends Bitcoin to Recipient   |
  |                                       |
  |  - Sender specifies the amount of     |
  |    Bitcoin they wish to send.         |
  |  - Sender confirms the transaction    |
  |    details and initiates the payment. |
  |  - Bitcoin is sent from sender's      |
  |    wallet to the recipient's Bitcoin  |
  |    address.                            |
  +---------------------------------------+
                    |
                    v
  +---------------------------------------+
  |       Bitcoin Received by Recipient   |
  |                                       |
  |  - Recipient's mobile wallet monitors |
  |    the Bitcoin network for incoming   |
  |    transactions to the recipient's    |
  |    Bitcoin address.                   |
  |  - Once the transaction is confirmed  |
  |    on the Bitcoin network, the        |
  |    recipient's wallet displays the    |
  |    newly received Bitcoin balance.    |
  +---------------------------------------+
 

 - 1 bitcoin === 10^9 satoshis.

