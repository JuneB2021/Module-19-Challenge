# Fintech Finder Application

An application to help locate the fintech professional with the Ethereum blockchain network integration for instant payment upon the hiring.

---

## Installation Guide

The following packages installation is required for Modules and Liabrary used in the app.
    
   #### Streamlit
    pip install streamlit
    
   #### Web3.py library
    pip install web3==5.17
    
   #### mnemonic
    pip install mnemonic
    
   #### bip44
    pip install bip44

---

## Inspect the Transaction on Etherscan

   #### Send Transaction
    i.   Launch the Streamlit application by type 'streamlit run fintech_finder.py' in the terminal
    ii.  On the resulting webpage, select a candidate from the drop-down menu, then enter the number of hours you'd like to hire them
    iii. Click the Send Transaction button to sign and send the transaction with your Ethereum account information
    
         ![markdown_image](https://github.com/JuneB2021/Module-19-Challenge/tree/main/Images/ValidationTransactionHash.PNG)
    
   #### Validate Transaction 
    i.   Navigate to Kovan Etherscan and enter Ethereum address into the Kovan Etherscan search bar to retreive balance and history

         ![markdown_image](https://github.com/JuneB2021/Module-19-Challenge/tree/main/Images/EtherBalance.PNG)
         
    ii.  Click on the Txn Hash number associated with the transaction that paid the Fintech Finder candidate for the payment detail

         ![markdown_image](https://github.com/JuneB2021/Module-19-Challenge/tree/main/Images/TransactionDetail.PNG)
         
    iii. Click on the TO address number associated with the transaction paid to validate the payment sending from the sender

         ![markdown_image](https://github.com/JuneB2021/Module-19-Challenge/tree/main/Images/EtherPayment.PNG)

---

## Contributors

contact: JuBeaver@hotmail.com

---

## License

MIT
